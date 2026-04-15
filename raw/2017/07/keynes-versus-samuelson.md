---
title: Keynes versus Samuelson
date: 2017-07-13T15:30:00.000-07:00
updated: 2017-12-19T17:34:59.991-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/07/keynes-versus-samuelson.html
---

![](media/KeynesSamuelson.png)
I read through Roger Farmer's [book excerpt up at _Evonomics_](http://evonomics.com/new-keynesian-economics-betrays-keynes/) (and have subsequently bought the book). I tweeted a bit about it, but I think one point I was trying to make is better made with a blog post. Farmer's juxtaposition of Samuelson's neoclassical synthesis and Hick's IS-LM model made clear in my mind the way to understand "what went wrong":

> _The program that Hicks initiated was to understand the connection between Keynesian economics and general equilibrium theory. But, it was not a complete theory of the macroeconomy because the IS-LM model does not explain how the price level is set. The IS-LM model determines the unemployment rate, the interest rate, and the real value of GDP, but it has nothing to say about the general level of prices or the rate of inflation of prices from one week to the next._ 

> _To complete the reconciliation of Keynesian economics with general equilibrium theory, Paul Samuelson introduced the neoclassical synthesis in 1955. According to this theory, if unemployment is too high, the money wage will fall as workers compete with each other for existing jobs. Falling wages will be passed through to falling prices as firms compete with each other to sell the goods they produce. In this view of the world, high unemployment is a temporary phenomenon caused by the slow adjustment of money wages and money prices. In Samuelson’s vision, the economy is Keynesian in the short run, when some wages and prices are sticky. It is classical in the long run when all wages and prices have had time to adjust._

There are two ways to think about what it means for the IS-LM model to fail to explain the price level:



1.  It is a model of the short run -- so short that prices do not change appreciably from inflation during the observation time. Symbolically, _t << 1/π_ such that _P ~ exp(π t) ≈ 1 + π t ≈ 1_. This is Samuelson's version: prices are "sticky" in the short run, but adjust in the long run.
2.  It is a model of a low inflation economy. Inflation is so low that the price level can be considered approximately constant (and therefore real and nominal just differ by a scale factor). Symbolically, _d log P/dt = π ≈ 0 << γ_ where _γ_ is some other growth scale such as interest rates, NGDP, or population (I'd go with the former \[1\]).



These two scenarios overlap in some short run (because _d log P/dt ~ π t_); the difference is that inflation can be low much longer than the price level can be low. This distinguishes Keynes' view of e.g. persistent slumps versus Samuelson's view of eventual adjustment. [I've made the case](http://informationtransfereconomics.blogspot.com/2016/02/the-is-lm-model-as-effective-theory-at.html) that the IS-LM model should be understood as an effective theory derived from the second limit, not the first.



As an aside, not that Samuelson's limit doesn't make empirical sense in today's economy. Inflation is on the order of _π_ ~ 2%, which implies a time horizon (1/_π_) of 50 years (and therefore IS-LM should apply for 5 or so years to an accuracy of about 10%). That's a pretty long short run.



Another point I'd like to make is that the second limit is more definitively a "macro" limit in the sense that it is about macro observables (low inflation) rather than micro observables (sticky prices). In fact, we can consider the second limit as "[macro stickiness](http://informationtransfereconomics.blogspot.com/2015/04/micro-stickiness-versus-macro-stickiness.html)": individual prices fluctuate (i.e. aren't sticky), but the aggregate distribution is relatively constant ([statistical equilibrium](http://informationtransfereconomics.blogspot.com/2016/09/the-economic-state-space-mini-seminar.html)). We can further connect the second limit (and the potential for a persistent slump) to properties of the [effective theory of the ensemble average](http://informationtransfereconomics.blogspot.com/2017/06/self-similarity-of-macro-and-micro.html) of that statistical equilibrium (namely that 〈_k_〉 - 1 ≈ 0). This is all to say that the second limit is a true emergent "macro" theory that can be understood without much knowledge of the underlying agents (or another way, ignorance of how agents behave).


...

**Update 19 December 2017**

I eventually turned this post into an example for a [presentation on macroeconomics and ensembles of markets](https://informationtransfereconomics.blogspot.com/2017/07/presentation-macroeconomics-and.html).


...



**Footnotes:**



\[1\] This also opens up discussion of the "liquidity trap". If interest rates _r_ are the proper scale to compare to inflation, we have an additional regime we need to understand where both inflation and interest rates are near zero (_π, r ≈ 0_).
