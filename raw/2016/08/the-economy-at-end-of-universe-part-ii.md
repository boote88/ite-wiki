---
title: "The Economy at the End of the Universe, part II"
date: 2016-08-09T23:33:00.004-07:00
updated: 2016-08-09T23:33:59.788-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/08/the-economy-at-end-of-universe-part-ii.html
---

Nick Rowe asked [in a comment on this post](http://informationtransfereconomics.blogspot.com/2016/08/the-economy-at-end-of-universe.html) if I could look at the second model (a Cagan monetary demand model) he describes [in his post](http://worthwhile.typepad.com/worthwhile_canadian_initi/2016/07/finite-horizon-models-of-inflation-as-the-horizon-goes-to-infinity.html) and that took me on an adventure that might be enlightening. I also thought about calling this post _[Life, the Universe and Economics](https://en.wikipedia.org/wiki/Life,_the_Universe_and_Everything)_ (or something like that) as the sequel to the previous post.



Anyway, a Cagan model has $M/P$ (real money supply) as a negative function of expected inflation, so using rational expectations (model-consistent expectations) and taking $\log M \equiv m$ and $\log P \equiv p$ we have






The general (forward-looking) solution to this equation is an integral of the money supply (or monetary base or what have you)






As an aside, this is an example of [using a Laplace transform to solve a differential equation](https://en.wikipedia.org/wiki/Laplace_transform#Example_1:_Solving_a_differential_equation). We can see that $\tau$ is essentially a time horizon. It weights the future (expected) money supply by a decreasing exponential factor (similar to a discount factor).



But that infinity is also a time horizon -- it tells us where to stop considering the future at all. Note that times $T \gg \tau &gt; t$ don't contribute much to the integral. If we look at the limiting behavior of this integral (at times $t$ in the distant future after any impact of a shock to monetary policy such that $m(t) = \mu t$ -- constant money growth) we have:






This has two different limits depending on whether you take $\tau$ to infinity first (it's 0) or $T$ to infinity first (it's infinite). Again, we have the same issue as we had with Nick Rowe's _reductio ad absurdum_ and the conclusion we should draw is that only the limits $T \gg \tau$ and $\tau \gg T$ could make sense. There's either rapid discounting or slow discounting (those limits just mentioned, respectively) at the horizon. And in those two cases we have either $P \sim \exp \mu t$ (steady growth in the price level) or $P \sim 1$ (i.e. constant, but with a growing money supply).



If we take the first limit we have something that looks basically like the previous post (except the steady state has constant growth, which we could have chosen for the previous model but didn't for simplicity):



![](<media/finite horizons nick rowe -part IIa-.png>)

In any case, we have the same problem that as the time horizon $t_{0}$ at which $m(t_{0})$ returns to "normal" moves out, the result differs by a larger and larger amount from $P \sim \exp \mu t$. Here's the graph of inflation ($\dot{p}(t)$):



![](<media/finite horizons nick rowe -part IIa- 2.png>)



Note that the Cagan model has [different results](http://faculty.cas.usf.edu/jkwilde/macro208/Lecture%2011.pdf) \[pdf\] for adaptive expectations. Depending on parameters, inflation is either basically monetary (it depends on $m(t)$ Nick Rowe's concrete steppes) or basically expectations (i.e. is independent of $m(t)$). The former limit is either rapid discounting, rapid adaptation, or both. The latter is either slow discounting, slow adaptation. or both (but results in exploding inflation).





**Addendum**


It is interesting to look at this model as an information transfer model $X : M \rightleftarrows P$ where "expectations" $X$ are the detector of information equilibrium between the money supply and the price level














so if we use rational expectations, we must equate the price $X$ with the value of $X$ above such that














That's not a typo -- it's a double exponential. In order to have $P$ not explode (given rational expectations), we need $k = 1$, which [implies that the price level is constant](http://informationtransfereconomics.blogspot.com/2015/08/scott-sumners-information-equilibrium.html). This is exactly the same finding as a more traditional approach to the Cagan model \[[pdf](http://faculty.cas.usf.edu/jkwilde/macro208/Lecture%2011.pdf)\].  The resolution here depends on what model you trust more. If you trust rational expectations, then you question the equilibrium. If you trust information equilibrium, you question rational expectations.



...



PS Gosh, I had to think about this for nearly two weeks and over three flights. I may still have gotten it wrong. Weird and subtle things can happen when you have to deal with infinity.



PPS You can see the limits pretty directly just looking at the equation





If $\tau \gg T$, then you have $- \tau \dot{p} \approx 0$, and thus $P \sim 1$. If $T \gg \tau$, then you have $m - p \approx 0$ and so $P \sim M(t) \sim \exp \; \mu t$ in my example.
