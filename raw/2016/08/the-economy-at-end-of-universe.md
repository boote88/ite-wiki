---
title: The Economy at the End of the Universe
date: 2016-08-01T17:30:00.000-07:00
updated: 2016-08-02T10:32:25.752-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/08/the-economy-at-end-of-universe.html
---

Nick Rowe [presented a model](http://worthwhile.typepad.com/worthwhile_canadian_initi/2016/07/finite-horizon-models-of-inflation-as-the-horizon-goes-to-infinity.html) \[as a _reductio ad abusrdum_\] where it appears as though the limit of a series of finite horizons differs by a greater and greater amount from the infinite time horizon model. I think this is [just another illustration](http://informationtransfereconomics.blogspot.com/2016/07/scopes-and-scales-present-value-formula.html) of how you really have to be careful when taking limits in economics -- some limits make no economic sense.



Here's a graph Nick's model where an interest rate r increase causes the price level _P(t)_ to suddenly drop in order for the path of _P(t)_ to conform to the Fisher equation. The lines represent longer and longer (but finite) time horizons:



![](<media/finite horizons nick rowe 1.png>)

You can see that a longer time horizon means you need a larger immediate drop in the price level. Does this make economic sense? If the time horizon is 70 years in the future, the drop in _P(t)_ is 50; if it is 140 years, the drop in _P(t)_ is 75. Imagine a bunch of firms with different time horizons. Firms with longer time horizons will drop their prices **_more_** based on the same 100 basis point increase in the interest rate? This seems odd.



That's because there's another limit being taken that happens before the infinite time horizon limit -- the rate at which prices drop increases with _T_. Here's a graph that approaches Nick's version as _T_ goes to infinity:



![](<media/finite horizons nick rowe 2.png>)

The initial drop in _P(t)_ gets faster and faster in order to drop farther and farther as _T_ goes to infinity. But why should the rate at which prices adjust to a monetary shock get **_faster_** with longer time horizons? Maybe there is a good reason. In any case, that is the implicit model of firm behavior in Nick's limit of finite horizons.



And even if this is a good model in a particular finite case, at _T_ equal to infinity we have an infinite (fractional) drop in the price level and an infinitely long climb back up to some finite value. That is to say the limit of Nick's function as _T_ goes to infinity is a step function (black dashed line below). Here I show you the graphs on a linear scale (with double the original time horizons) to make it more obvious:



![](<media/finite horizons nick rowe 4.png>)


> _P(t)_ \= 100 for all _t_ < 0 and _t_ = 0
> _P(t)_ \= 0 for all 0 < _t_ < ∞
> _P(∞)_ = 100

With the exception of that point at infinity, this is perfectly consistent with a price level that falls to zero for _t_ > 0. That is to say Nick's model nearly everywhere is consistent with an expectation at infinity of zero! The difference between _E\[P(∞)\]_ = 100 and _E\[P(∞)\]_ \= 0 is a single point at infinity. This makes it difficult to argue that this model faithfully represents a limit of finite time horizons with an _E\[P(∞)\]_ = 100 -- in the limit the model only satisfies _P(t)_ = 100 - _ɛ_ for _ɛ_ > 0 at _t_ = ∞.



In other words, this is kind of a mathematical trick. The function satisfies the basic constraints -- i.e. _E\[P(∞)\]_ = 100 -- but in a way that doesn't make **_economic_** sense. The infinite time horizon limit is an economy that collapses after a 100 basis point interest rate hike only to reappear for an instant just for the patrons at the _[Restaurant at the End of the Universe](https://en.wikipedia.org/wiki/The_Restaurant_at_the_End_of_the_Universe)_.
