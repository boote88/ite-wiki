---
title: "Utility maximization, matching and information equilibrium"
date: 2015-05-01T18:32:00.001-07:00
updated: 2015-05-01T18:41:53.856-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/05/utility-maximization-matching-and.html
---

Roger Farmer mentioned in a comment on his blog (that I discuss [here](http://informationtransfereconomics.blogspot.com/2015/04/equilibria.html)) that he was using competitive search instead of Arrow-Debreu equilibrium -- that is to say [search/matching theory](http://en.wikipedia.org/wiki/Matching_theory_\(economics\)) (S/M) instead of [utility maximization](http://en.wikipedia.org/wiki/Utility_maximization_problem) (UM) as a guiding principle. Matching is a somewhat weaker assumption than utility maximization (you end up at a point a little worse off than the utility maximum ... and there are invariably more points _close to_ the utility maxima than there are utility maxima).



I thought this was a good context in which to present the idea of information equilibrium (IE) and non-ideal information transfer (NI). Let's use a concrete example; we'll say we have 11 people labeled by the numbers _2-12_. Let's also say the distribution of utility _D0_ is given by the probability distribution of the roll of two dice:



![](<media/utility matching and information equilibrium -dice- 1.png>)

That is to say person 7 has the highest utility (will pay the highest price for the widgets) and people 2 and 12 lave the lowest utility (have the lowest price they are willing to pay). You can also think of this as the _distribution of demand_ in this example. Additionally, it is useful to think of person 2 and person 12 as effective producers of widgets and others as relative consumers of widgets.



What distribution of widgets _W_ maximizes utility? _W = D0_. I'll illustrate this in the following graph for 20 widgets \[0\] (blue boxes):



![](<media/utility matching and information equilibrium -dice- utility.png>)

That means for UM we have the condition _W = D0_ \[1\] defining the allocation. You can also think of the blue boxes as representing the _distribution of supply_. 



How does this work for matching theory? Well, search costs enter into that model and we end up with some unfulfilled utility ... and for small search costs we have the condition _W ≈ D0_ for S/M. The distribution looks like this:



![](<media/utility matching and information equilibrium -dice- matching.png>)

You in general have unmet supply (not all 20 widgets are allocated) with the matching approach -- this corresponds to e.g. unemployment in labor search models.



Information equilibrium represents a further weakening of the allocation condition to _I(W) = I(D0)_, i.e. the information in the distribution of widgets/supply is equal to the information in the distribution of utility/demand. We can construct a distribution of widgets containing asymptotically the same information as _D0_ by rolling dice 20 times:



![](<media/utility matching and information equilibrium -dice- ieq.png>)

And finally we come to the least restrictive condition _I(W) < I(D0)_ for non-ideal information transfer. The worst case (farthest from ideal) would be all 20 widgets belonging to person 2 or person 12 (i.e. the producers of widgets haven't sold anything -- a good analogy of a recession). A typical case (well, one generated randomly) would look like this \[2\]:



![](<media/utility matching and information equilibrium -dice- nonideal.png>)

With these examples, we have generated a hierarchy of the restrictiveness of the conditions -- in order of decreasing restrictiveness



1.  Utility maximization (UM) with _W = D0_
2.  Search/matching (S/M) with _W ≈ D0_
3.  Information equilibrium (IE) with _I(W) = I(D0)_
4.  Non-ideal information transfer (NI) with _I(W) < I(D0)_



In the limit of a large number of rolls over a long time, the condition _I(W) = I(D0)_ is equivalent to _W = D0,_ but for any finite example there exist more states where _I(W) = I(D0)_ than states where _W = D0._

A sequence of 20 rolls that fit with information equilibrium at each roll (each time step) are varied -- they are all sequences you can get from rolling dice 20 times. Here are 10 examples:



![](<media/utility matching and information equilibrium -dice rolls 1-.png>)

None of the above rolls are consistent with utility maximization at each time step (the 3rd one from the right comes close, though). The sequences consistent with utility maximization at each roll all begin with **7, 6, 8 ...**  or **7, 8, 6 ...** ; they represent less than 1.3% of all possible histories (the probability of rolling 7, 6, 8 or 7, 8, 6) while the IE-consistent rolls make up more than 98.7% of the possible histories.



However, the key point I wanted to make is that **utility maximization and search/matching approaches represent special cases of the information theory approach**. The history of transactions bringing the distributions _W_ and _D0_ into 'equilibrium' (i.e. making _W → D0_) in the UM and S/M cases are contained in the sequences of transactions bringing _W_ and _D0_ into information equilibrium.



**Footnotes**


\[0\] Ok, there are 21 boxes here. For those who counted, you have won this round!



\[1\] This also illustrates rational expectations if we consider the process by which widgets are assigned is via the rolling of dice -- the utility distribution is equal to the distribution of dice being rolled. No one expects an oversupply of 2's or a roll of 13, so the utility distribution matches the outcome.



\[2\] In reality, you'd need to look at a far larger number of widgets to really tell the difference between the ideal and non-ideal cases. The NI distribution is an improbable result of rolling 20 dice, but is not actually significant at the 5-sigma level, for example.
