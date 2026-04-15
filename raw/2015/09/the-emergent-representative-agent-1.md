---
title: "The emergent representative agent [1]"
date: 2015-09-09T17:00:00.000-07:00
updated: 2017-09-13T15:46:42.565-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/09/the-emergent-representative-agent-1.html
---

This is a [nice article](http://www.pieria.co.uk/articles/the_intuition_dance_in_microeconomics) by _unlearning economics_ on Pieria about some assumptions in microeconomics. I have a couple of things to add to this (I'll leave the great discussion of game theory for another time) ... as well as a possible solution to the issues raised.



First, the assumption of transitivity (or the different but related assumption of [GARP](https://en.wikipedia.org/wiki/Revealed_preference)) is actually equivalent to the idea that humans have a measure called "utility". Basically all that is involved is that the manifold of \[transitive\] preferences has a structure that allows them to be related by a diffeomorphism to the manifold of real numbers ... numbers we call utility. A real number we can maximize.



There is no \[meaningful\] difference between assuming "well-behaved preferences" or "transitivity" and assuming there is a property of economic agents called "utility" measured by a real number.



Another assumption mentioned in the article is monotonicity of utility functions. This is required in order for the utility maximum to saturate the budget constraint and be a single point on that constraint. Again, this assumption is only required because you want to use utility (to come up with a single solution).



So here we are making strange assumptions that are only required because we want to use utility to analyze economic problems.



It reminds me of the history of physics where physicists came up with a bunch of odd assumptions in order to continue to use a theoretical construct. It was called the aether and it asked physicists to assume partial aether dragging and length contraction.



What if I told you you could get the same general results as utility without assuming transitivity or monotonicity? And what if I told you it had a single assumption: [the principle of indifference](https://en.wikipedia.org/wiki/Statistical_mechanics#Fundamental_postulate).



Let's start with a basket of consumption goods (or intertemporal consumption periods or both) _C₁, C₂, C₃, ... Cn_ subject to the budget constraint _Σ Ci ≤ M_.



Let's assume every consumption "state" _Ci = pi xi_ in this _d_\-dimensional space is equally likely (the principle of indifference). This could be intertemporal consumption (_i ≤ d_ indexing time) or different goods (_i ≤ d_ indexing goods) or even intertemporal consumption of different goods (_i ≤ d_ indexing goods and time).



_d_

![](<media/itm utility 2.png>)
_d_

![](<media/money 3d xi 2.png>)![](<media/money 3d xi 3.png>)


How can I saturate the budget constraint (and select a point on it) using this? Dimensionality. As _d → ∞_, the distribution of points becomes highly concentrated around _Σ Ci =_ _Σ pi xi_ _\= M_ as can be seen in this graph:



![](<media/itm utility distribution.png>)

For an infinite number of goods and/or an infinite number of time periods, the 'representative' (average) point approximately saturates the budget constraint. The (emergent) representative agent spends all of its money. However individual agents can vary from spending all to saving all of their money.



This representative agent also appears to engage in consumption smoothing (if you look at _i_ indexing time in the intertemporal problem, all time periods are roughly equal in terms of the value of consumption ... \[a symmetry that can be broken by [the rate of interest](http://informationtransfereconomics.blogspot.com/2015/06/the-euler-equation-as-maximum-entropy.html)\]). Consumption smoothing is an emergent property of the ensemble of agents that are free to choose any point in the domain (and any given agent is unlikely to have very smooth consumption).



This maximum entropy view reproduces the basics of the utility maximization model without the utility. In fact, [utility can be seen as emergent](http://informationtransfereconomics.blogspot.com/2015/03/utility-in-information-equilibrium-model.html) \[2\]. And since utility, a real number, can be used to describe the solutions (equilibria) we see in the maximum entropy view we see that transitivity (or GARP, both equivalent to real number utility) is an emergent property of the emergent representative agent. **This is important:** transitivity is explicitly not true of the individual agents -- they have _random_ consumption baskets that they have revealed they prefer! Their preferences are not transitive -- they aren't even [stable](http://noahpinionblog.blogspot.com/2014/01/what-if-preferences-are-unstable.html)! Agent 9000 prefers A to B one day and B to A another.



So here's a list of some emergent properties of the emergent representative agent:



-   Transitive preferences (a consequence of emergent utility)
-   Monotonicity of utility (satiation)
-   Consumption smoothing



And here's a list of properties of the underlying individual agents:



-   Preferences are not transitive and are unstable (random preferences)
-   No preference to more or less of a good (random preferences)
-   Consumption fluctuates (random consumption)



The idea of a rational utility maximizing representative agent is an emergent construct \[1\] in the entropy maximization paradigm; real individual people need not have any of these properties.



...



**Footnotes:**


\[1\] Noah Smith references emergent representative agents in [a recent post](http://noahpinionblog.blogspot.com/2015/09/the-case-for-mindless-economics-10.html):

> _For example, suppose psychologists find that most human beings are incapable of forming the kind of expectations that time-varying utility models say they do. That would mean one of two things. It could mean that the economy as a whole behaves qualitatively differently than the individuals who make it up (in physics jargon, that would mean that the representative agent is "emergent"). Or it could mean that time-varying utility models must not be the reason for excess volatility._

\[2\] This is a bit subtle -- entropy maximization chooses a particular utility function (or really a class of utility functions that are maximized at the entropy maximization point).
