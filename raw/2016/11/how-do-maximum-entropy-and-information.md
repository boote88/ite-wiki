---
title: "How do maximum entropy and information equilibrium relate?"
date: 2016-11-22T17:00:00.000-08:00
updated: 2016-11-25T09:37:06.572-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/11/how-do-maximum-entropy-and-information.html
---

I think I need a better post about how information equilibrium and maximum entropy relate to one another. As I'm still learning myself, this is partially for my own benefit. The short answer is that information equilibrium is a way of saying that two maximum entropy probability distributions from which two different random variables _A_ and _B_ are drawn are in some sense (i.e. informationally) equivalent to each other. This equivalence will show up in specific relationships between _A_ and _B_ defined by an information equilibrium condition. For example, fluctuations in one will show up as fluctuations in the other.



Maximum entropy seeks to maximize the function _H(X)_ over possible probability distributions _p(X)_ for random variable _X_



_p(X = xk) = pk_



_H(X) = - Σ pk log pk_



subject to some constraint, where the _pk_ represents a probability of an event in some abstract space indexed by _k_. For example, if that constraint is that _X_ has a maximum and minimum value, then _p_ is a uniform distribution. The outcome of entropy maximization is a distribution _p(X)_ that maximizes _H(X)_.



Information equilibrium is essentially a rephrasing of the question of whether two maximum entropy distributions of random variables _A_ and _B_ are (informationally) equivalent to each other (e.g. represent different observables based on an underlying variable _C_, for example), and tells us how one distribution will change relative to the other if they are. Symbolically,



_H(A) = H(B)_



with underlying probability distributions _p1(A)_ and _p2(B)_. This is fairly meaningless for a single observation of _A_ and _B_ (any single probability is proportional to another), but for a series of observations (particularly time series) we can see if both series of random variables _A_ and _B_ represent the same underlying information (or at least approximately so). This doesn't tell us if _A_ or _B_ (or maybe some unknown _C_) is the true information source, but only that _A_ and _B_ are in some sense equivalent.



In the case of uniform distributions _p1(A)_ and _p2(B)_, we can rewrite this as a differential equation relating the stochastic variables _A_ and _B_ (in the limit that _A_ and _B_ represent the sum of a large number of "events", for example A is total energy made up of the energy of millions of atomic kinetic energy terms)


![](<media/CodeCogsEqn -4-.png>)

where _P_ turns out to represent an abstract price in applications to economics when _A_ is abstract demand and _B_ is abstract supply. We can think of instances of the random variable A as "demand events", B as "supply events" and the two coinciding per the condition above as a "transaction event". The practical result of this is that it gives us a framework to understand [time series of exponential growth functions](http://informationtransfereconomics.blogspot.com/2016/03/information-equilibrium-and-time-series.html) and [power laws](http://informationtransfereconomics.blogspot.com/2016/02/power-laws-and-information-equilibrium.html) (and fluctuations around them) that is directly related to supply and demand.



Since _p1(A)_ and _p2(B)_ represent maximum entropy probability distributions, changes (shocks) will be accompanied by entropic forces restoring maximum entropy (i.e. the most likely state given prior information). We can interpret e.g. the forces of supply and demand as manifestations of these entropic forces (as well as things like [sticky prices or so-called statistical equilibrium](http://informationtransfereconomics.blogspot.com/2016/09/the-economic-state-space-mini-seminar.html)). [Here](http://informationtransfereconomics.blogspot.com/2015/03/supply-and-demand-as-entropy.html) are some simulations of these entropic forces for supply and demand.



Additionally, if we can identify _A_ as the source of the information, we can turn the equivalence into a bound (you can't receive more information at _B_ than is sent by _A_)



_H(A) ≥ H(B)_



This is called [non-ideal information transfer](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html). If we use uniform distributions as above, means that the [differential equation becomes a bound](http://informationtransfereconomics.blogspot.com/2016/06/gronwalls-inequality-and-information.html).



These concepts are explored further [in the paper](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html). [Here](http://informationtransfereconomics.blogspot.com/2016/02/slides.html) are some slides presenting these ideas. [Here](http://informationtransfereconomics.blogspot.com/2015/03/supply-and-demand-as-entropy.html) are some simulations showing the supply and demand (and price) relationships captured by the ideas above.

**Update 23 November 2016**

Here's the above relationship in picture format

![](<media/max ent.png>)
