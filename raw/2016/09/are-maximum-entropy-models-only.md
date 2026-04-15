---
title: "Are maximum entropy models the only possible models with rational expectations?"
date: 2016-09-25T20:01:00.005-07:00
updated: 2016-10-06T17:02:07.685-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/09/are-maximum-entropy-models-only.html
---

This post is an incomplete speculative synthesis of several previous posts:

> \[1\] [Balanced growth, maximum entropy, and partition functions](http://informationtransfereconomics.blogspot.com/2016/09/balanced-growth-maximum-entropy-and.html)
>
> \[2\] [Neo-Fisherism and causality](http://informationtransfereconomics.blogspot.com/2016/04/neo-fisherism-and-causality.html)
>
> \[3\] [How money transfers information from the future to the present](http://informationtransfereconomics.blogspot.com/2014/12/how-money-transfers-information-from.html)
>
> \[4\] [II. Entropy and microfoundations](http://informationtransfereconomics.blogspot.com/2014/02/ii-entropy-and-microfoundations.html)

The question is whether you can have any expectation of a future model equilibrium besides the model-consistent (i.e. rational) expectation of a maximum entropy model? Or another way: Is the information loss required for the time translation (inverse Koopman) _Et_ operator \[2\] the same information loss in reaching the maximum entropy state?



This is true for a normal distribution. The information in the initial distribution besides the mean and variance is exactly the information lost with the (inverse) _Et_ operator.



Consider the [KL divergence](https://en.wikipedia.org/wiki/Kullback%E2%80%93Leibler_divergence) between an arbitrary distribution _Q_ of given mean and variance and a normal distribution _N(μ,σ)_: _DKL(N||Q) ≡ ΔI_. Propagation of _Q_ into the future (via inverse of _Et_) leads to normal distribution (central limit theorem), resulting in information loss _ΔI_. Additionally, the normal distribution is maximum entropy distribution constrained to have a given mean and variance, so the approach to maximum entropy (disappearance of the initial condition _Q_ information) will also yield a normal distribution, and therefore the same information loss _DKL(N||Q) ≡ ΔI_.



Does this always work out? We'd like to ask the question: Is whether every universal distribution (with constraint _C_) is also a maximum entropy distribution (with constraint _C_)?



One issue is that the uniform distribution is the maximum entropy distribution for a bounded random variable, but not universal in the sense of the central limit theorem (samples from the universal distribution that propagate in time via _Et_ become a normal distribution). However, any distribution can be related to a uniform distribution ([probability integral transform](https://en.wikipedia.org/wiki/Probability_integral_transform)), so maybe this issue isn't as problematic as it first appears. I'll see if I can work out a proof\*\*.



For right now, this post is just capturing my half-baked thinking. Here is my intuition in terms of economics. The key point is that agents must expect the information loss (in any model) because otherwise the operator _Et_ is ill-defined (the inverse of a non-invertible operator \[2\]). Additionally, information loss (about the initial conditions) is exactly what happens when a system drifts toward is entropy maximum. Purchasing goods and services (i.e. transactions that propagate an economy into the future) consumes to the information in the prices (one way to think about the efficient markets hypothesis \[4\]), therefore the economic model must be a maximum entropy model \[1\] in order for the model to contain _Et_ operators (expectations) and propagate the system towards the future equilibrium given initial conditions (losing information as both entropy maximizing and via the _Et_  operator).



This will fail if there is a failure of information equilibrium ([non-ideal information transfer](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html)) because then you're not in an equilibrium (and therefore not moving towards a maximum entropy state) which breaks the connection between the information loss in the time translation and the entropy maximizing process.



This may seem like a word salad, but I swear it contains some useful intuition.



...



**Footnotes:**



\*\* I have a nagging feeling is that what you end up with is something where the information loss in the entropy maximizing process is proportional to the information loss in the expectations/time translation (into the future) process -- resulting in a condition that is precisely an information equilibrium condition specific to the distributions involved (for uniform distributions, you end up with the [basic information equilibrium equation](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html) of Fielitz and Borchardt) with the information transfer index relating to the proportionality. I'd probably have to consider the propagation into the future as an information equilibrium relationship between the future and the present \[3\].
