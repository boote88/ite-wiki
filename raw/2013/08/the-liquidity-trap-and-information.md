---
title: The liquidity trap and information transfer
date: 2013-08-16T11:25:00.000-07:00
updated: 2013-08-16T11:25:18.423-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/08/the-liquidity-trap-and-information.html
---

In the discussions mentioned in the [last post](http://informationtransfereconomics.blogspot.com/2013/08/the-manetarist.html), I became interested in seeing why the information transfer model [didn't seem to do so well](http://informationtransfereconomics.blogspot.com/2013/07/long-run-quantity-theory-information.html) during the Great Depression. Of course, we need a starting point to seeing what doing well means. I'd like to start with economists' favorite first order approximation: $P \sim MB$ (with $P$ the price level being the dashed line and $MB$ the monetary base being the solid lines, the darker one of which is divided by 300).



![](<media/monetarism doesnt work.png>)

This of course doesn't work so well and led to e.g. Milton Friedman proposing M2 (see the [last post](http://informationtransfereconomics.blogspot.com/2013/08/the-manetarist.html)) as the "real money supply". Let's zoom in on two pieces: pre-WWII and post-WWII:



![](<media/monetarism doesnt work 1929.png>)![](<media/monetarism doesnt work 1960.png>)

Notice however that you could probably change the constant of proportionality (in this case 300) to be different before and after WWII and it might work better. That gave me an idea; what if we fit the ITM model parameters to pre-war and post war data? It works remarkably well in the specific domains (but terribly outside them):



![](<media/ITM works.png>)


![](<media/ITM works 1929.png>)![](<media/ITM works 1960.png>)

Pretty amazing, no? So I decided to do the fit for 10 year intervals and look at the parameter values. Here is the [supply reference constant](http://informationtransfereconomics.blogspot.com/2013/07/dotting-is-and-crossing-ts.html) ($\sim 700 \text{ G$}$ for post war fits) with the dashed lines being the pre-war (red) and post-war (blue) reference constants (the red and blue solid lines represent the value for the fit parameter when fit to the entire pre-war data and post-war data, respectively):



![](<media/phase transition.png>)

The other free parameter (I kept $\gamma$ [fixed](http://informationtransfereconomics.blogspot.com/2013/07/universalizing-model-kappa-sigma-space.html)) $Q^d_{ref}/Q^s_{ref}$ shows the exact same behavior. You can see what I did next already in the graph. The gray line is a typical curve arising in phase transitions (like at the [critical temperature in an Ising model](http://farside.ph.utexas.edu/teaching/329/lectures/node110.html)). What happens if you use this curve as the reference constant? This:



![](<media/phase transition works.png>)

You get a model that works well pre-WWII and post-WWII but not at the "phase transition". Since the [price level equation](http://informationtransfereconomics.blogspot.com/2013/07/dotting-is-and-crossing-ts.html) is [analogous to an isentropic process](http://informationtransfereconomics.blogspot.com/2013/04/are-thermodynamic-analogies-useful.html) (reversible adiabatic process) one can imagine this as the economy moving along one adiabat for a time, going through an irreversible process (WWII or maybe Bretton-Woods as shown on the graph), and moving over to another adiabat, like for example, [here](http://www.gfdl.noaa.gov/blog/isaac-held/2011/12/07/20-the-moist-adiabat-and-tropical-warming/). Basically, the constant in $P V^\gamma = \text{ constant}$ changed.



I'm going to move into $\sigma \kappa$ [space](http://informationtransfereconomics.blogspot.com/2013/07/universalizing-model-kappa-sigma-space.html) (normalized monetary base and information transfer index), but first, here is the graph of $\kappa$:


![](<media/phase transition kappa.png>)

Recall that $\kappa = 1/2$ [is the pure quantity theory of money](http://informationtransfereconomics.blogspot.com/2013/07/recovering-quantity-theory-from.html). And here is the path in $\sigma \kappa$ space:



![](<media/phase transition kappa-sigma space.png>)



I had mentioned previously that the ITM bascially had the monetarist view of the Great Depression. That was incorrect and based on the fact that I thought $\kappa$ was small. If this phase transition view is correct, then we can see that the Great Depression and the Great Recession have much in common -- along with Japan's lost decade -- every one of those times occurs on the other side of [the ridge line](http://informationtransfereconomics.blogspot.com/2013/07/universalizing-model-kappa-sigma-space.html) where monetary policy is orthogonal to aggregate demand. Our path over the past century appears to have brought us over the ridge into the region of ineffective monetary policy twice, and even in the information transfer model, the Great Recession, the Great Depression and Japan's lost decade represent the same forces at work. I will call this an _information trap_ in the future, analogous to the liquidity trap.



The implications are not pleasant. Do we have to redefine money? During the depression countries left the gold standard, an option not available now. Maybe we abandon physical currency for [digital currency](http://www.slate.com/blogs/moneybox/2012/04/19/digital_currency_ends_recessions.html)? Do we simply muddle along [like Japan has for decades](http://en.wikipedia.org/wiki/Lost_Decade_\(Japan\))? Does there have to be a situation where the government takes the commanding heights again, like in WWII? If any of these are true it means we are in for a long languishing.
