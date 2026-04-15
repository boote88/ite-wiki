---
title: Compressed sensing and the information bottleneck
date: 2017-10-07T13:53:00.001-07:00
updated: 2019-05-19T12:59:28.875-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/10/compressed-sensing-and-information.html
---

For those that don't know, my day job is actually in signal processing research and development in the aerospace sector. [As I document in my book](https://www.amazon.com/dp/B0754X3PYF/ref=as_li_ss_tl?ie=UTF8&linkCode=ll1&tag=arandomphysic-20&linkId=8203d360feb87d92a2042e67b1e353f4), I came by economics research via a circuitous route. One subject I worked on for awhile (and still do to some extent) is called [compressed sensing](https://en.wikipedia.org/wiki/Compressed_sensing) ([Igor Carron's blog](https://nuit-blanche.blogspot.com/) is a great way to keep up with the state of the art in that field, and [his Google site](https://sites.google.com/site/igorcarron2/cs) provides a nice introduction to the subject).



One of the best parts about Igor's blog is that he brings together several lines of research from machine learning, matrix factorization, compressed sensing, and other fields and frequently finds connections between them (they sometimes appear in his regular feature "[Sunday Morning Insight](https://nuit-blanche.blogspot.com/2017/10/sunday-morning-insight-demise-of.html)").



In that spirit — although more of  a Saturday Afternoon Insight — I thought I'd put a thought out there. I've been looking at how the price mechanism relates to the information bottleneck ([here](https://informationtransfereconomics.blogspot.com/2017/10/the-price-mechanism-and-information.html), [here](https://informationtransfereconomics.blogspot.com/2017/10/the-price-mechanism-as-information.html)), but I've also mused about a possible connection [between the price mechanism and compressed sensing](https://informationtransfereconomics.blogspot.com/2015/07/compressed-sensing-information-theory.html). I think now there might be a connection between compressed sensing and the information bottleneck.



![](<media/compressive sensing.png>)

In compressed sensing, you are trying to measure a sparse signal (a signal that appears in only a sparse subset of your space **_x_**, like a point of light in a dark image or a single tone in a wide bandwidth). To do so, you set up your system to make measurements in what is called the dense domain — through some mechanism (Fourier transform, random linear combinations, labeled with **Φ**) you make the variable you wish to measure appear throughout the space **_y_**. Therefore a few random samples of the entire dense space give you information about your sparse signal, whereas a few random samples of an image with a single bright point would likely only return dark pixels with no information about the point.



![](media/bottleneck.png)

Is this how the information bottleneck works? We have some domain **_X_** in which our signal is just a small part (the set of _all images_ vs the set of _images of cats_), and we train a feedforward deep neural network (DNN, **_h1_ → _h2_ → ... _hm_**) that creates a new domain **_Y_** where our signal information is dense (_cat_ or _no cat_). Every sample of that domain tells us information about whether there is an image of a cat being fed into the DNN (i.e. if it identifies cats and dogs, a result of _dog_ tells us it's not a cat).



In compressed sensing, we usually know the some properties about the signal that allow us to construct the dense domain (sparse images of points can be made dense by taking a 2D Fourier transform). However, _random_ linear combinations can frequently function as a way to make your signal dense in your domain. In training a DNN, are we effectively constructing a useful random projection of the data in the sparse domain? As we push through the information bottleneck, are we compressing the relevant information into a dense domain?



The connection between compressed sensing and the structure of a neural net has been noted before (see e.g. [here](https://brainwindows.wordpress.com/2010/03/01/compressed-sensing-in-neuroscience/) or [here](https://nakarmiukash.weebly.com/research.html)), the new part (for me at least) is the recognition of [the information bottleneck](https://arxiv.org/abs/1703.00810) as a useful tool to understand compressed sensing — "opening the black box" of compressed sensing.

...

**Update 19 May 2019**

[This might also be connected](https://nuit-blanche.blogspot.com/2019/04/why-are-big-data-matrices-approximately.html):

> _Matrices of (approximate) low rank are pervasive in data science, appearing in recommender systems, movie preferences, topic models, medical records, and genomics. While there is a vast literature on how to exploit low rank structure in these datasets, there is less attention on explaining why the low rank structure appears in the first place. Here, we explain the effectiveness of low rank models in data science by considering a simple generative model for these matrices: we suppose that each row or column is associated to a (possibly high dimensional) bounded latent variable, and entries of the matrix are generated by applying a piecewise analytic function to these latent variables. These matrices are in general full rank. However, we show that we can approximate every entry of an m×n matrix drawn from this model to within a fixed absolute error by a low rank matrix whose rank grows as O(log(m+n)). Hence any sufficiently large matrix from such a latent variable model can be approximated, up to a small entrywise error, by a low rank matrix._

[Paper link on arXiv](https://arxiv.org/abs/1705.07474) — almost all large enough matrices are effectively low rank.
