---
title: "Sticky \"information\", i.e. knowledge, and emergence"
date: 2016-10-04T18:00:00.000-07:00
updated: 2016-10-04T18:00:09.489-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/10/sticky-information-ie-knowledge-and.html
---

I spent some more time pondering an paper Noah Smith tweeted out the other day (and Tom Brown also retweeted to me) and [wrote a blog post about a bit later](http://noahpinionblog.blogspot.com/2016/10/hunting-rational-expectations-whale.html) (see his post for all the background). The article and Noah both emphasize "emergence", so of course it is of interest to this blog. However I am not sure that is an appropriate interpretation.



First, let's see if I can understand the paper itself. I am going to make a vocabulary change however -- let's use the word **knowledge** instead of **information** because this has little to do with information theory.



With that vocabulary change, the paper makes several points:



1.  Sticky knowledge (information) and noisy knowledge (information) models lead to (equivalent) dependence of the forecast error on forecast revisions FE = β FR + n where β = β(λ) (knowledge  stickiness) or β = β(G) (noisy knowledge Kalman gain) and n is a noise term.
2.  Actual forecast errors from a variety of sources indicate β ~ 1, meaning λ ~ 0.5 or G ~ 0.5.
3.  Additional tests to show this isn't due to some other factors, and applies across consumers, professionals, academics, and internationally.
4.  Forecasts can be useful estimates of non-rational expectations
5.  Non-rational expectations can "emerge" from aggregating rational agents



Let me set up a toy model version of what is happening here. (Aside: this is a specific example where an unrealistic model is useful for understanding a result about the real world.) Let's take our observable O (inflation, growth rate, whatever) to be a Wiener process (Brownian motion) with zero drift. In this case the "rational expectations" forecast (REF) for any future price is the present price (i.e. the EMH for a random walk). If we look at forecasts that are updated every integer unit of time T = n, our sticky knowledge forecast (SKF) with stickiness λ for time T = 3 will be









Think of 1-λ as a probability of an individual agent updating their forecast. Also note that





















i.e. forecast revisions versus forecast error. For λ = 0, we get the rational expectations result --  the forecast error and the forecast revisions are uncorrelated:



![](<media/sticky information and rational expectations 3.png>)![](<media/sticky information and rational expectations 4.png>)


For λ = 0.5, we get correlation:



![](<media/sticky information and rational expectations 1.png>)![](<media/sticky information and rational expectations 2.png>)

In the above pictures, I show a "typical" path alongside several hundred simulation results. Effectively, the SKF(t, T = t-k) is a biased estimator of the future value of O(t) while O(t-k) = REF(t, T = t-k) is an unbiased estimator.



This pretty much covers points 1-4 above. I would like to add that sticky knowledge ("information") models can be interpreted as agents ignoring most outside information, making them uncorrelated. Agents that all updated their forecasts at the same time to exactly the same data would end up very correlated -- [which leads to a failure of information equilibrium](http://informationtransfereconomics.blogspot.com/2016/09/channel-capacity-and-rate-distortion-in.html) (which is bad and probably behind recessions).



Now let's talk emergence (point 5). It's a bit easier to explain in the case of sticky "information". At time t, individual agents either forecast REF(t-1, T = t+k) or REF(t, T = t+k) -- which are both "rational" expectations (one is fresh and one is stale) and unbiased estimators of O(t+k). The average agent, however, forecasts






But it seems to me a bit cheeky to say the bias of forecast revisions is really emergent. Individual agents either revise or don't revise, so it doesn't make sense to talk about the bias of forecast revisions for agents that don't revise. It's not a revision of zero, it's no revision. The concept of forecast revisions is itself somewhat emergent -- you are averaging a set of revision numbers with a bunch of [NaN](https://en.wikipedia.org/wiki/NaN)s you take to be zero.



Additionally, this exact same result can be obtained if we think of λ as a weight instead of a probability and apply it to every agent.



But the biggest problem is that a stale (i.e. not updated with probability 1 - λ) rational expectation from time t - 1 at time t isn't technically a rational expectation at time t. The aggregating process for a forecast at time t is aggregating λ N agents with rational expectations and  (1 - λ) N agents with non-rational (i.e. stale) expectations. The aggregation of rational agents and non-rational agents being non-rational isn't really "emergence". It's kind of like saying an average over the whole numbers {0, 0, 0, 0, 0, 1, 1, 1, 1, 1} isn't 0 and the average 0.5 (a fraction) is "emergent". I'd call that a stretch.



It's not the worst thing to do in a paper and sometimes a little flair is good to draw attention. As there's no hard and fast definition of "emergence", so there's no technical flaw with what the authors say.






PS As a side note, the models presented in the paper fail for "complete stickiness" λ = 1 (or Kalman gain G = 0). In that case the coefficient of the forecast revision is singular, which should make sense to us all: if we never update our forecast with new knowledge, then how could you have revisions? This creates a "scope" for these models: λ < 1. This means agents must update their forecasts with rational expectations at some point. If agents never update their forecasts with true rational expectations, then these results don't apply to the real world -- even though the data appears to be described by the sticky knowledge (information) model!
