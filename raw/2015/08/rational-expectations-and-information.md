---
title: Rational expectations and information theory
date: 2015-08-23T18:27:00.003-07:00
updated: 2015-08-23T18:27:48.186-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/08/rational-expectations-and-information.html
---

![KL Divergence using Gaussian distributions from Wikipedia.](media/KL-Gauss-Example.png)



Noah Smith once again deleted my comment [on his blog](http://noahpinionblog.blogspot.com/2015/08/a-great-critique-of-rational.html), so I'll just have to preserve it (well, the gist of it) here.



He discussed an argument against rational expectations he'd never considered before. Since counterfactual universes are never realized, one can never explore the entire state space to learn the fundamental probability distribution from which macro observable are drawn. Let's call this probability distribution _A_. The best we can get is some approximation _B_.



_A ≈ B_


If this sounds familiar, it's exactly the way one would approach this with the information equilibrium model [as I discussed several months ago](http://informationtransfereconomics.blogspot.com/2014/11/expectations-rational-or-otherwise-and.html).



In that post, I showed that the [KL divergence](https://en.wikipedia.org/wiki/Kullback%E2%80%93Leibler_divergence) measures information loss in the macroeconomy based on the difference between the distributions _A_ and _B_.



_

_D(A||B) = ΔI_

_

That was the content of my comment on Noah's post. I go a bit further at the link and say that this information loss is measured by the difference between the price level and how much NGDP changes when the monetary base changes



_ΔI ~ P - dN/dM = dN\*/dM - dN/dM_ 



Which to me seems intuitive: it compares how much the economy should grow from an expansion of the money supply (ideally) to how much it actually does grow.



Just the aggregate _ΔI_ is measured, however. Two different distributions _B_, _B'_ and _B''_ can have the same KL divergence so this doesn't give us a way to estimate _A_ better.



Now rational expectations are clearly wrong at some given level of accuracy, but then so are Newton's laws. The question of whether you can apply rational expectations depends on the size of _ΔI_. Since _ΔI_ is roughly proportional to nominal shocks (the difference between where the economy is and where it should be based on growth of _M_ alone \[1\]) and these nominal shocks are basically the size of the business cycle, it means _rational expectations are not a useful approximation to make when analyzing the business cycle_.



As far as I know, this is the first macroeconomic estimate of the limits of the rational expectations assumption that doesn't compare it to a different model of expectations (e.g. bounded rationality, adaptive expectations). (There are lots of estimates for micro.)




**Footnotes:**

\[1\] In case anyone was curious, this also illustrates the apparent inconsistency between e.g. [this post](http://informationtransfereconomics.blogspot.com/2014/03/the-monetary-base-as-sand-pile.html) where nominal shocks are negative and e.g. [this post](http://informationtransfereconomics.blogspot.com/2015/08/are-higher-interest-rates-inflationary.html) where they are positive. It depends on whether you apply them before including the effect of inflation or after. Specifically



_0 = dN\*/dM - (dN/dM + σ) = (dN\*/dM - σ) - dN/dM_
