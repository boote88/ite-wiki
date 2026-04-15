---
title: "Mistakes, random behavior or complex behavior?"
date: 2015-10-03T14:31:00.004-07:00
updated: 2015-10-03T14:31:43.454-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/10/mistakes-random-behavior-or-complex.html
---

![Complex quasi-random and pseudo-random points in [0,1] x [0,1] ... or a lattice with random mistakes?](media/halton v random v square.png)





Mark Thoma points us to [this voxeu.org article](http://www.voxeu.org/article/errors-source-macroeconomic-frictions) on mistakes as a source of price stickiness:

> _To model costly, error-prone choice we adopt the ‘control cost’ approach from game theory, which treats actions as random variables, and assumes that greater precision can be achieved by paying a higher decision cost. ... we choose a specification which implies that decision probabilities take the familiar form of [multinomial logits](https://en.wikipedia.org/wiki/Multinomial_logistic_regression)_ \[aka MaxEnt, and a result of a categorical distribution (see footnote [here](http://informationtransfereconomics.blogspot.com/2015/05/the-economic-allocation-problem.html))\]_. ... Errors in_ **which** _prices firms set help reproduce a variety of observations from microdata. But errors in_ **when** _firms adjust their prices help fit macrodata by increasing the non-neutrality of monetary policy. One microeconomic finding we address is the coexistence of very small and large price adjustments ...  In contrast, with control costs, the price change distribution is smoothed out by errors._ 



Emphsis in the original. This creates a world where many prices don't change, but can change at the 'wrong' time by the 'wrong' amount when they do (because firms don't want to spend money to figure out the optimal change). The issue is that they are trying to reconcile macro stickiness (slow to change due to macro conditions) and micro flexibility (incorrect change by sometimes large amounts). This is the reconciliation achieved with random changes in [this post](http://informationtransfereconomics.blogspot.com/2015/04/micro-stickiness-versus-macro-stickiness.html). I also wrote about mistakes being key to the "hot potato effect" [here](http://informationtransfereconomics.blogspot.com/2015/03/the-hot-potato-effect-is-entropic-force.html); these 'mistakes' are actually random transactions.



Say the game theory model is (for sake of simplicity) a normal distribution centered on the "right time" to adjust a price. You can spend money to reduce the variance of that normal distribution. **But it's still a normal distribution.** That is to say we've established agents are random, we're now arguing about how random. And any amount of randomness will tend to create maximum entropy distributions over time.



Those maximum entropy distributions will be based on whatever macro observable you fix. In many of my simple models (e.g. [here](http://informationtransfereconomics.blogspot.com/2015/09/a-random-walk-inside-simplex.html)), I take the maximum entropy distribution where the maximum value is fixed (a uniform distribution), but the partition function approach (see the draft [paper](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html)) fixes the observed macro as the ensemble average value (in physics, this usually fixes energy). It gives us the most likely distribution of price changes consistent with observed core inflation, for example.



The voxeu.org article calls the randomness "errors" because they are looking at it with a rational utility maximizing framework in their head. Some price changes don't follow from rational maximizing behavior? They must be rational and just made a mistake! And maybe that is a good intuition. I am coming from a maximum entropy framework in my head, so I see random and attribute it to either pure randomness of thermal systems or the pseudo-randomness of complexity. 



Some firm doesn't adjust its prices when it should to maximize utility ... what is happening?



-   They made a mistake
-   They have no idea what they are doing (pure randomness)
-   They have specific, complex reasons that don't show up in macro data



Only the MaxEnt approach allows all three.
