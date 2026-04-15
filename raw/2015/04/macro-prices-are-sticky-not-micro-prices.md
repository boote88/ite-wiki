---
title: "Macro prices are sticky, not micro prices"
date: 2015-04-17T16:58:00.001-07:00
updated: 2015-04-17T16:58:28.712-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/04/macro-prices-are-sticky-not-micro-prices.html
---

![](media/price1.gif)![](media/price2.gif)

Two not very sticky prices ...



[David Glasner](http://uneasymoney.com/2015/04/17/price-stickiness-and-macroeconomics/), great as always:

> _While I am not hostile to the idea of price stickiness — [one of the most popular posts I have written](http://uneasymoney.com/2014/02/06/why-are-wages-sticky/) being an attempt to provide a rationale for the stylized (though controversial) fact that wages are stickier than other input, and most output, prices — it does seem to me that there is something ad hoc and superficial about the idea of price stickiness ..._ 

> _The usual argument is that if prices are free to adjust in response to market forces, they will adjust to balance supply and demand, and an equilibrium will be restored by the automatic adjustment of prices. ..._ 

> _Now it’s pretty easy to show that in a single market with an upward-sloping supply curve and a downward-sloping demand curve, that a price-adjustment rule that raises price when there’s an excess demand and reduces price when there’s an excess supply will lead to an equilibrium market price. But that simple price-adjustment rule is hard to generalize when many markets — not just one — are in disequilibrium, because reducing disequilibrium in one market may actually exacerbate disequilibrium, or create a disequilibrium that wasn’t there before, in another market. Thus, even if there is an equilibrium price vector out there, which, if it were announced to all economic agents, would sustain a general equilibrium in all markets, there is no guarantee that following the standard price-adjustment rule of raising price in markets with an excess demand and reducing price in markets with an excess supply will ultimately lead to the equilibrium price vector. ..._ 

> _This doesn’t mean that an economy out of equilibrium has no stabilizing tendencies; it does mean that those stabilizing tendencies are not very well understood, and we have almost no formal theory with which to describe how such an adjustment process leading from disequilibrium to equilibrium actually works. We just assume that such a process exists._



Calvo pricing is an ad hoc attempt to model an entropic force with a microeconomic effect (see [here](http://informationtransfereconomics.blogspot.com/2015/03/nominal-rigidity-is-entropic-force.html) and [here](http://informationtransfereconomics.blogspot.com/2015/03/entropy-and-walrasian-auctioneer.html)). As I commented below his post, assuming ignorance of this process is actually the first step ... if equilibrium is the most likely state, then it can be achieved by **_random_** processes:

> Another way out of requiring sticky micro prices is that if there are millions of prices, it is simply unlikely that the millions of (non-sticky) adjustments will happen in a way that brings aggregate demand into equilibrium with aggregate supply. 

> Imagine that each price is a stochastic process, moving up or down +/- 1 unit per time interval according to the forces in that specific market. If you have two markets and assume ignorance of the specific market forces, there are 2^n with n = 2 or 4 total possibilities 

> {+1, +1}, {+1 -1}, {-1, +1}, {-1 -1} 

> The most likely possibility is no net total movement (the “price level” stays the same) — present in 2 of those choices: {+1 -1}, {-1, +1}. However with two markets, the error is ~1/sqrt(n) = 0.7 or 70%. 

> Now if you have 1000 prices, you have 2^1000 possibilities. The most common possibility is still no net movement, but in this case the error (assuming all possibilities are equal) is ~1/sqrt(n) = 0.03 or 3%. In a real market with millions of prices, this is ~ 0.1% or smaller.
>
> In this model, there are no sticky individual prices — every price moves up or down in every time step. However, the aggregate price p = Σ p\_i moves a fraction of a percent. 

> Now the process is not necessarily stochastic — humans are making decisions in their markets, but those decisions are likely so complicated (and dependent e.g. on their expectations of others expectations) that they could appear stochastic at the macro level. 

> This also gives us a mechanism to find the equilibrium price vector — if the price is the most likely (maximum entropy) price though “dither” — individuals feeling around for local entropy gradients (i.e. “unlikely conditions” … you see a price that is out of the ordinary on the low side, you buy). 

> This process only works if the equilibrium price vector is the maximum entropy (most likely) price vector consistent with macro observations like nominal output or employment. 

> [http://informationtransfereconomics.blogspot.com/2015/03/entropy-and-walrasian-auctioneer.html](http://informationtransfereconomics.blogspot.com/2015/03/entropy-and-walrasian-auctioneer.html)
