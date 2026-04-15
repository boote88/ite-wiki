---
title: Expectations destroy information
date: 2014-05-01T18:31:00.002-07:00
updated: 2014-05-01T18:31:34.190-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/05/expectations-destroy-information.html
---

I have a beef with the use of expectations in economics. They seem to be so powerful as to make them [useless as an explanation](http://informationtransfereconomics.blogspot.com/2013/09/the-useless-power-of-expectations.html); they also seem to [lack empirical impact](http://informationtransfereconomics.blogspot.com/2014/04/inflation-predictions-are-hard.html) where they originally were designed to have an impact.



Here, I am going to describe the role expectations play in the economy using information theory -- it's not diving too deep, mostly just an argument using [Shannon information](http://en.wikipedia.org/wiki/Quantities_of_information#Entropy) and measuring information loss with the [KL divergence](http://en.wikipedia.org/wiki/Kullback%E2%80%93Leibler_divergence).



The KL divergence measures the extra message length for a given amount of data that must be sent if you have a code optimal for the wrong distribution relative to the true distribution. In general, it represents the information loss (measured in nats or bits depending on which logarithm you use) by being wrong about a distribution relative to being right.



Relating this to [information transfer economics](http://informationtransfereconomics.blogspot.com/2014/03/how-money-transfers-information.html), the KL divergence represents the extra information that must be sent in the market (lower [information efficiency](http://informationtransfereconomics.blogspot.com/2014/03/modeling-macroeconomic-fluctuations.html)) given the wrong expected economic state distribution relative to the true future economic state distribution. I [previously hypothesized](http://informationtransfereconomics.blogspot.com/2014/03/modeling-macroeconomic-fluctuations.html) that lower information efficiency was related to recessions.



In this post, I want to show that economic "expectations" generally destroy information unless they are right. I put together some simulations illustrating this point using a relatively simple model. Imagine there are 10 states the economy can be in (think a [hidden semi-Markov model](http://en.wikipedia.org/wiki/Hidden_semi-Markov_model)). There is a probability distribution that gives the chance it is in one of the state in the next time period, for example, if all states are equally likely, this distribution would be


0.1 0.1 0.1 0.1 0.1 0.1 0.1 0.1 0.1 0.1




If the economy was going to be in state #2 with 100% probability, then it looks like this:


0.0 1.0 0.0 0.0 0.0 0.0 0.0 0.0 0.0 0.0


We will compare two of these distributions, call them the actual (A) and the expected (E) distributions with the KL divergence. The KL divergence of the two distributions above is









That is, there is about 2.3 nats (3.3 bits) more information in the second sequence relative to the first. (Which makes sense: specifying a number from 1 to 10 -- in our case state #2 --  requires 3.3 bits.)



In the following, I actually show the negative of the KL divergence (partially because I accidentally did it that way and am too lazy to change it, and partially because it emphasizes that we are looking at information loss).



In the simulations below, I randomly generated 10,000 probability distributions on the 10 states and looked at the KL divergence. I did three cases: **one**, the expected distribution was a small perturbation from the actual distribution (E = A + δA), **two**, the expected distribution was the first distribution given above .. all states equally likely aka the least informative prior (E = 0.1), and **three**, the expected distribution was another randomly generated distribution (E and A are uncorrelated). Here are the results:


![](<media/KL divergence 1.png>)

We can see that if there aren't any big changes in the distribution (the small perturbation, blue), the information loss is minimal. If there are big changes (the new distribution is uncorrelated, red) then information loss is not only large, but has a long tail. Interestingly, the least informative prior (gray) is not only in the middle of these, but doesn't have much of a tail (there is a sharp cut-off). You'd imagine the blue histogram showing the typical case where past performance gives an indication of future performance, with only small deviations. The red histogram shows what it's like if you're wrong about the future.



What does this mean? Well, if expectations are accurate (people can accurately predict the future), then there is a limited amount of information loss. It may be reductio ad absurdum, but I'd say this pretty much proves that there is information loss in the market mechanism. Who can accurately predict the future? I'll take it a step further and say that expectations are the cause of that loss of information, and information loss appears to be a primary driver of recessions.



When people are especially bad at predicting the future, you not only get massive information loss on average, but there is a long tail of even greater loss (red histogram).



The average case for information loss, falling between the two extremes, is pretty well described by the least informative prior. This is potentially a reason why the information transfer model, which assumes this as a starting point, can do a good job with trends. This least informative prior is also effectively the efficient markets hypothesis in the real-world sense. There are trends and momentum, but price movements are unpredictable. They are not completely unpredictable; the information loss (red histogram) would be large. This least informative prior is also the assumption that expectations do not affect the long run trends.



Ah, _but,_ you say, _if you kind of know what you are talking about (you're able to predict the future), then you can do better than the least informative prior._ That's why I have this next graph: it shows that the ability to do better than the least informative prior is very sensitive to how wrong you are -- you only need to be a little bit wrong for the tail risk to be a serious negative impact on your average performance. I plot the histograms for a 10% perturbation (used in the graph above) up to a 40% perturbation (in the last one, I show the 100% perturbation from the graph above in red):


![](<media/KL divergence 2.png>)

The takeaway is that you basically always have to be right otherwise the potential losses from being wrong will add up and cause you to lose more information than the least informative prior over time.



Ah, _but,_ you say, _wouldn't an expectation based on the information transfer model give you at least some capability to predict the future -- contradicting your assertion that people are bad at predicting the future?_ Nope. The information transfer model is built on the least informative prior -- you are assuming maximum ignorance about the future, that is to say, you are assuming as much ignorance about the future as I am claiming people are already in possession of! That is to say, maximum ignorance.
