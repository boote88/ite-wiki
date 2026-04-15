---
title: "Towards Arrow-Debreu-McKenzie equilibrium, part 2 of N"
date: 2014-06-23T13:20:00.000-07:00
updated: 2014-06-23T13:20:36.279-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/06/towards-arrow-debreu-mckenzie_23.html
---

Some random notes on aggregation, especially in light of the [Sonnenschein-Mantel-Debreu](http://en.wikipedia.org/wiki/Sonnenschein%E2%80%93Mantel%E2%80%93Debreu_theorem) theorem (not saying anything new about the theorem which has been around a long time, but looking at it from the perspective of the information transfer model). This is not a coherent post.



**A.**


SMD theorem says that only things inherited from individual demand functions are (from wikipedia):

-   [Continuity](http://en.wikipedia.org/wiki/Continuous_function)
-   [Homogeneity of degree zero](http://en.wikipedia.org/wiki/Homogenous_function),
-   [Walras' law](http://en.wikipedia.org/wiki/Walras%27_law), and
-   a [boundary condition](http://en.wikipedia.org/wiki/Boundary_value_problem) assuring that, as prices approach zero, demand becomes large.

Note: homogeneity of degree zero is a fundamental aspect of the information transfer framework, and it can be seen as essentially the [simplest relationship](http://informationtransfereconomics.blogspot.com/2014/02/i-quantity-theory-and-effective-field.html) of supply and demand that maintains homogeneity of degree zero.



This means that an aggregated system of equations that satisfy homogeneity of degree zero:

$$p_{ij} = \frac{\partial n_{i}}{\partial s_{j}} = \frac{1}{\kappa_{ij}}\; \frac{n_{i}}{s_{j}}$$

must result in a function that satisfies

$$P = \frac{d N}{d S} = \frac{1}{\kappa_{1}}\; \frac{N}{S} + \frac{1}{\kappa_{2}}\; \frac{N^{2}}{S^{2}} + \frac{1}{\kappa_{3}}  \frac{N}{S} \frac{d N}{d S} +  \frac{N}{\kappa_{4}}  \frac{d^{2} N}{d S^{2}} + \cdots$$

We keep only the first term in the information transfer model.



Consequence: _The consequence of this is that the uniqueness of the equilibrium is not guaranteed : the excess-demand function may have more than one [root](http://en.wikipedia.org/wiki/Root_of_a_function) – more than one price [vector](http://en.wikipedia.org/wiki/Euclidean_vector) at which it is zero (the standard definition of equilibrium in this context)._ (from wikipedia)



I don't know if this is a correct simplified explanation, but imagine a world where fuel was slightly more expensive and cars were slightly less expensive. Depending on the relative price this could still clear the market with the same amount of money being spent in aggregate on cars and fuel.



However! If there is less fuel and more cars, then there might be fewer ways to associate gallons of fuel with cars (lower entropy since the fuel is fungible) and you could select the actual equilibrium based on maximum entropy production.



More wikipedia: _Second, by the [Hopf index theorem](http://en.wikipedia.org/wiki/Hopf_index_theorem), in [regular economies](http://en.wikipedia.org/wiki/Regular_economies) the number of equilibria will be finite and all of them will be locally unique._



That means you can potentially sort them all by entropy.



**B.**


I was reading this: _New Developments in Aggregation Economics_, Pierre Andre Chiappori, Ivar Ekeland (2010) \[[http://www.columbia.edu/~pc2167/Aggregation.pdf](http://www.columbia.edu/~pc2167/Aggregation.pdf)\], and I thought this was an odd quote:

> _They also show that these restrictions, if fulfilled, are sufficient to generically recover the underlying economy - including individual preferences. These results, how- ever, require that individual endowments be observable; **indeed, when only aggregate endowments are observable, a non-testability result can be proved.**_ 

> _The conclusion that emerges from this literature is that, in contrast with prior views, general equilibrium theory does generate strong, empirically testable predictions. The subtlety, however, is that tests can only be performed if data are available at the micro (here individual) level. One of the most interesting insights of new aggregation theory may be there - in the general sense that testability seems to be paramount when micro data are available, **but does not seem to survive (except maybe under very stringent auxiliary assumptions) in a 'macro' context, when only aggregates can be observed.**_

Emphasis mine. You can test microfounded models if micro data is available, but there are no testable implications for the macro variables?



**C.**


_aggregation (econometrics)_, Thomas Stoker (2006) \[[http://web.mit.edu/tstoker/www/Stoker\_Aggregation\_Palgrave.pdf](http://web.mit.edu/tstoker/www/Stoker_Aggregation_Palgrave.pdf)\] 



This paper claims only possibilities where a "full schedule" i.e. individual/household information (income transfer and spending result):



1\. Each household spends in exactly the same way, 

2\. The distribution of income transfers is restricted in a convenient way.



This sections makes it seem like the "aggregation problem" is entirely based on the idea that the dot product doesn't factor



$\frac{1}{n} \sum_{i} a_{i}b_{i} \neq&nbsp;\frac{c}{n}&nbsp;\sum_{i} b_{i}$


in general, where $c$ is a constant.


Point 1 above basically says that you can work around the issue by taking all the $a_{i}$ to be constant or equal to their average.



$\frac{1}{n} \sum_{i} a_{i}b_{i} = \frac{\bar{a}}{n} &nbsp;\sum_{i} b_{i}$



Point 2 says that  you can work around the issue by taking $b_{i} = s_{i}\bar{b}$ so that



$\frac{1}{n} \sum_{i} a_{i}b_{i} = &nbsp;\frac{\bar{b}}{n}&nbsp;\sum_{i} a_{i}s_{i}$



And the latter sum is taken to be a new weighted average, $\bar{a}_{w}$. However, there are a couple of other ways to deal with this



$\frac{1}{n} \sum_{i} a_{i}b_{i} = \frac{1}{n} |a| |b| \cos \theta$



where $\cos \theta$ is the angle between the vectors $a$ and $b$ which becomes another macro parameter. There is also the possibility of using the trace:



$\frac{1}{n} \sum_{i} a_{i}b_{i} = \frac{1}{n} \text{tr } a \otimes b$



which is invariant under a wide variety of transformations on the vectors $a$ and $b$. It is also related to a differential volume element of the volume defined by the matrix $a \otimes b$ (i.e. $\det a \otimes b$). I.e. the micro effect on the vector elements can be seen as a macro effect on volumes (i.e. a different theory).
