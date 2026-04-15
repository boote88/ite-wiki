---
title: Mutual information and information equilibrium
date: 2017-09-22T11:37:00.001-07:00
updated: 2017-09-22T13:15:28.884-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/09/mutual-information-and-information.html
---

Natalie Wolchover has [a nice article](https://www.quantamagazine.org/new-theory-cracks-open-the-black-box-of-deep-learning-20170921/) on the information bottleneck and how it might relate to why deep learning works. Originally described in [this 2000 paper](https://arxiv.org/abs/physics/0004057) by Tishby _et al_, the information bottleneck was a new variational principle that optimized a functional of mutual information as a Lagrange multiplier problem (I'll use their notation):






The interpretation is that we pass the information the random variable $X$ has about $Y$ (i.e. the mutual information $I(X ; Y)$) through the "bottleneck" $\tilde{X}$.



Now I've been interested in the connection between information equilibrium, economics, and machine learning (e.g. [GAN](https://en.wikipedia.org/wiki/Generative_adversarial_network)'s real data, generated data, and discriminator have a formal similarity to [information equilibrium](https://arxiv.org/abs/0905.0610)'s information source, information destination, and detector — [the latter I use](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html) as a possible way of understanding of demand, supply, and price on this blog). I'm always on the lookout for connections to information equilibrium. This is a work in progress, but I first thought it might be valuable to understand information equilibrium in terms of mutual information.





![](<media/mutual information venn diagram.png>)

If we have two random variables $X$ and $Y$, then information equilibrium is the condition that:






Without loss of generality, we can identify $X$ as the information source (effectively a sign convention) and say in general:






We can say mutual information is maximized when $Y = f(X)$. The diagram above represents a "noisy" case where either noise (or another random variable) contributes to $H(Y)$ (i.e. $Y = f(X) + n$). Mutual information cannot be greater than the information in $X$ or $Y$. And if we assert a simple case of information equilibrium (with information transfer index $k = 1$), _e.g._:










Note that in the above, the information transfer index accounts for the "mismatch" in dimensionality in the Kronecker delta (i.e. a die roll that determines the outcome of a coin flip such that a roll of 1, 2, or 3 yields heads and 4, 5, or 6 yields tails).



Basically, information equilibrium is the case where $H(X)$ and $H(Y)$ overlap, $Y = f(X)$, and mutual information is maximized.
