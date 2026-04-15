---
title: "What happens when you push on a price?"
date: 2016-05-16T15:00:00.000-07:00
updated: 2016-05-16T15:00:25.071-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/05/what-happens-when-you-push-on-price.html
---

> _Ed. note: This post has been sitting around because I never found a satisfying answer. However, [this post from John Handley](http://ramblingsofanamateureconomist.blogspot.com/2016/05/non-walrasian-macro.html) inspired a comment that led to a more scientific take on it._

A lot of economics deals with situations where some entity impacts a market price: taxes, subsidies, or interest rates in general with a central bank. With the information equilibrium picture of economics, it's easy to say what happens when you change demand or supply ... the price is a detector of information flow.



For my thought experiments, I always like to think of an ideal gas with pressure $p$, energy $E$ and volume $V$ (analogous to price $p$, demand $D$ and supply $S$, respectively):






How do I increase the pressure of the system? Well, I can reduce $V$ or increase $E$ (raise temperature or add more gas). One thing is for certain: grabbing the pressure needle and turning it will not raise the pressure of the gas! (This is like [Nick Rowe's thought experiment](http://worthwhile.typepad.com/worthwhile_canadian_initi/2013/12/a-simple-story-about-reversibility-of-causation.html) of grabbing the speedometer needle).



... at least under the conditions where the detector represents an ideal probe (the probe has minimal impact on the system ... like that pressure gauge or speedometer needle). But our probe is the market itself -- it is maximally connected to the system. Therefore when you push on a price (through a regulation, tax, minimum wage, or quota system), it does impact supply and/or demand. The and/or is critical because these impacts are observed to be empirically different.



Since we don't know, we have to plead ignorance. Therefore price dynamics (for a short time and near equilibrium with $D \approx D_{eq}$ and $S \approx S_{eq}$) should follow:






This gives us an excellent way to organize a lot of effects. The leading constant coefficient would be where un-modeled macroeconomic inflation would go (it is a kind of mean field approximation). Entering into $a_{0}$ and $a_{1}$ would be [non-ideal information transfer](http://informationtransfereconomics.blogspot.com/2015/03/non-ideal-information-transfer-tail.html) -- movements in the prices that have nothing to do with changes in supply and demand. Interestingly, these first terms also contain expectations.



The next terms do not make the assumption that $D_{eq} = S_{eq}$ or that they even adjust at the same rate. This covers the possibilities that demand could perpetually outstrip supply (leading to market-specific inflation -- housing comes to mind), and that demand adjust to price changes faster than supply does (or vice versa). For example, demand for gasoline is fairly constant for small shifts in price, so price changes reflect changes in supply ($d_{10} \approx 0$). If you think pushing on a price moves you to a different equilibrium, then you might take $X_{eq} = X_{eq}(t)$, but we'll assume $dX_{eq}/dt = 0$ for now.



Basically, your theory of economics determines the particular form of the expansion. The "Walrasian" assumption (per John Handley's post) is that $D = S$ always. Adding rational expectations of (constant) inflation leaves you with the model:






Assuming information equilibrium yields a non-trivial restriction on the form of the expansion (see e.g. [here](http://informationtransfereconomics.blogspot.com/2016/03/information-equilibrium-and-time-series.html) for what happens when you add time to the information equilibrium condition). We obtain (taking $X - X_{eq} \equiv \Delta X$):






We find that almost all of the terms in the expansion above have zero coefficients. The leading term would be $d_{11} = k/S_{eq}$. The next terms would be the $c_{21}$ terms -- second order cross terms with one time derivative. Including only the lowest order terms and adding back in the possibility of non-ideal information transfer, we have










This means when you push on a price, at least to leading order, you impact demand (or cause non-ideal information transfer). It also has the opposite sign you might expect. An increase in price would increase demand! Note that this assumes general equilibrium (where demand and supply both adjust quickly to changes). But in general equilibrium, increasing demand means increasing supply as well, so we can understand the result that way. It could also be the case that nominal demand ($D$) goes up while real demand ($D/p$) goes down depending on the value of the coefficients.



If we assume demand adjusts slowly ($dD/dt \approx 0$), then we get the "Econ 101" result (returning to information equilibrium) where an increase in price reduces demand, assuming supply is increasing (e.g. economic growth):






For information equilibrium to reproduce the Econ 101 result that a tax increase reduces demand, you have to assume 1) information transfer is ideal, 2) demand changes slowly, and 3) economic growth ... or instead of 1-3, just assume non-ideal information transfer. Therefore the simplest explanations of the standard Econ 101 impacts of pushing on a price would actually be a decline in real demand or breaking information equilibrium.



This is not to say these assumptions aren't valid -- they could well be. It's just that there are a lot of assumptions at work whenever anyone tells you what the effects of changing a price are.
