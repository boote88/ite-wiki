---
title: Attainable definitions of equilibrium
date: 2016-02-03T17:00:00.000-08:00
updated: 2016-02-03T17:00:02.461-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/02/attainable-definitions-of-equilibrium.html
---

An article from Steve Keen was [reprinted at Evonomics](http://evonomics.com/economists-prove-that-markets-are-unecessary/) that makes some pretty bold claims. One of them is effectively a restatement of an old result about the stability of  tâtonnement given some assumptions of how it works:

> _... the original “Neoclassical” mathematical model of a market economy is mathematically unstable: it doesn’t converge to a stable pattern of relative prices and a stable growth path for the economy ... the argument ... was first made in the 1960s by Jorgenson (who was applying a mathematical theorem from the early 1900s) ..._

There are a lot of mentions of math at the beginning.



I went back to Keen's lecture (linked in the article) to get the details of the argument, which is in general sensible. The matrices that evolve output and prices from one period to the next are proportional to R and R⁻¹. The stability of iterating R and R⁻¹ depends on their eigenvalues. But R and R⁻¹ are non-negative so one of R and R⁻¹ is going to lead to an "unstable" (non-equilibrium) result ... the growth rate of some good (its output or price) will diverge from the "equilibrium growth rate" (of output or prices).



As I said, makes sense. But it hinges critically on the definition of equilibrium. This definition (from Keen's lecture):



_– \[Two\] conditions apply for a growing economy to be in equilibrium:_



1.  _Output of every good must be growing at the same rate_
2.  _Relative prices must be constant_



Well, then an economy isn't in equilibrium by definition because [this isn't true of e.g. the US economy](https://research.stlouisfed.org/fred2/graph/?g=3lnN). At least this is consistent: if an economy was in equilibrium, then it couldn't be growing, but since it's growing, it's not in equilibrium.



But we don't need the fancy proof. If equilibrium is defined as it is above, then economies are not in equilibrium, QED. Could an economy be in equilibrium with this definition? According to the proof, no. So we have a definition of equilibrium where not only is the observed state not in equilibrium, there is no chance of any observed state ever being in equilibrium.



Is a definition that nothing can meet a useful definition?






Anyway the actual neoclassical definition of equilibrium is that there is no excess supply or demand \[1\]. That's what Walras was talking about with tâtonnement -- prices change in response to excess supply and demand in order to bring them back to zero. There is nothing in there requiring the output of each good to grow at the same rate. Computers can grow in output at 20% per year and bread at 1% with supply of computers and bread being equal to demand for computers and bread, respectively, at each time step.



And really, neoclassical [equilibrium is a pretty decent model](http://informationtransfereconomics.blogspot.com/2014/07/in-defense-of-equilibrium.html). We don't show up to the grocery store with piles of rutabegas one day, piles of cheddar then next, or empty places where the bacon should be most of the time. That is to a first order approximation roughly zero excess demand and zero excess supply. I made an economics joke graph:



![](<media/naive equilibrium model.png>)

The neoclassical model of equilibrium unemployment says that the employment rate e ≈ 100%. The real world actually approximates this (at least in the post-war US) fairly well with employment varying from e ≈ 85% to e ≈ 96%. The later natural rate and matching models predict something closer to e ≈ 94-95% most of the time -- a bit better.



[I wrote in the past](http://informationtransfereconomics.blogspot.com/2013/08/econophysics-for-fun-and-profit.html) that mathematical theorems are usually not a good fit for real human systems. If someone has claimed a "mathematical proof" that the economy is unstable (or [stable](https://en.wikipedia.org/wiki/Arrow%E2%80%93Debreu_model)), you have to take it with a grain of salt. The real world likely only approximates the strict mathematical conditions for the proof of stability or instability, so you can at best say the real world is "approximately stable" or "approximately unstable".



As always, I must bring the discussion back to the information equilibrium model. In the partition function approach ([discussed in the paper](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html)), an economy has a picture that looks like this:



![](media/distribution0.png)

Both prices and nominal output are made up of "growth states" (think inflation for prices) that look like this (typically, the distribution for prices -- inflation rates -- has a lower average than the one for nominal output -- hence real growth is positive). Equilibrium is the state where there is no change in **_the distribution_** -- and it is defined by the average growth rate. However individual prices and outputs can move from one state to another. An analogy is a Maxwell distribution of velocities in an ideal gas. The distribution (in equilibrium) doesn't change, but individual atoms can scatter off each other, resulting in changes in their velocities.



That means Keen's definition of equilibrium doesn't apply. Relative prices are changing all the time, and output growth for every good is different (and changing).



It also looks more like a real world.



And at least it's a definition of equilibrium that isn't unattainable.






**Footnotes**


\[1\] Keen's critique of the method of restoring equilibrium is more applicable to the Ramsey-Kass-Coopmans (neoclassical growth) model. [I talk about that instability here](http://informationtransfereconomics.blogspot.com/2015/06/the-importance-of-transversality.html). The "people will see the problem and correct it" argument makes the entire model about people seeing the problem and correcting it, and not about the RCK equations at all. But in RCK model there is simply an aggregate "consumption" -- so there aren't outputs for different goods that could have differential growth.
