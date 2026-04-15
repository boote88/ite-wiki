---
title: Diamond-Dybvig as a maximum entropy model
date: 2015-04-19T19:46:00.001-07:00
updated: 2015-09-18T14:21:51.695-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/04/diamond-dybvig-as-maximum-entropy-model.html
---

I'm pretty sure this is not the standard way to present Diamond-Dybvig (which seems more commonly to be presented as a game theory problem).  However, this presentation will allow me to leverage some of the machinery of [this post](http://informationtransfereconomics.blogspot.com/2015/03/utility-in-information-equilibrium-model.html) on utility and information equilibrium. I'm also hoping I haven't completely misunderstood the model.

Diamond-Dybvig is originally a model of consumption in 3 time periods, but we will take that to be a large number of time periods (for reasons that will be clear later). Time $t$ will be between 0 and 1.



Let's define a utility function $U(c_{1}, c_{2}, ...)$ to be the information source in the markets






for $i = 1 ... n$ where $MU_{c_{i}}$ is the marginal utility (a detector) for the consumption $c_{i}$ in the $i^{th}$ period (information destination). We can immediately write down the main information transfer model equation:






Solving the differential equations, our utility function $U(c_{1}, c_{2}, ...)$ is






Where the $C_{i}$ and $a$ are constants. The basic timeline we will consider is here:


![](<media/itm diamond dybvig timeline.png>)

Periods $i$ and $k$ are some "early" time periods near $t = 0$ with consumption $c_{i}$ and $c_{k}$ while period $j$ is a "late" time period near $t = 1$ with consumption $c_{j}$. We introduce a "budget constraint" that basically says if you take your money out of a bank early, you don't get any interest. This is roughly the same as in the normal model except now period 1 is the early period $i$ and period 2 is the late period $j$. We define $t$ to be $t_{j} - t_{i}$ with $t_{j} \approx 1$ so the bank's budget constraint is






The total available state space is therefore an $n$-dimensional polytope with vertices along axes $c_{1}$, $c_{2}$, ... $c_{n}$. For example, in three dimensions (periods) we have something that looks like this:



![](<media/itm diamond dybvig polytope.png>)



Visualizing this in higher dimensions [is harder](http://www.penzba.co.uk/cgi-bin/PvsNP.py?SpikeySpheres). Each point inside this region is taken to be equally likely (equipartition or maximum information entropy). Since we are looking at a higher dimensional space, we can take advantage of the fact that nearly all of the points are near the surface ... here, for example is the probability density of the location of the points in a 50-dimensional polytope (where 1 indicates saturation of the budget constraint):



![](<media/itm diamond dybvig states.png>)



Therefore the most likely point will be just inside the center of that surface (e.g. the center of the triangle in the 3D model above). If we just look at our two important dimensions -- an early and late period -- we have the following picture:



![](<media/itm diamond dybvig.png>)



The green line is Eq. (1) the bank's budget constraint (all green shaded points are equally likely, and the intercepts are given by the constraint equation above) and the blue dashed line is the maximum density of states just inside the surface defined by the budget constraint. The blue 45 degree line is the case where consumption is perfectly smoothed over every period -- which is assumed to be the desired social optimum \[0\]. The most likely state with equal consumption in every period is given by E in the diagram.



The "no bank" solution is labeled NB where consumption in the early period is $c_{i} \approx 1$. The maximum entropy solution where all consumption smoothing (and even consumption "roughening") states are possible because of the existence of banks is labeled B.



The utility level curves are derived from the Cobb-Douglas utility function at the top of this post. You can see that in this case we have B at higher utility than E or NB and that having banks allows us to reach closer to E than NB.



If people move their consumption forward in time (looking at time $t_{k} &lt; t_{i}$), you can get a bank run as the solution utility (red, below) passes beyond the utility curve that goes through the NB solution. Here are the two cases where there isn't a run (labeled NR) and there is a run (labeled R):



![](<media/itm diamond dybvig no run.png>)![](<media/itm diamond dybvig run.png>)

Of course, the utility curves are unnecessary for the information equilibrium/maximum entropy model and we can get essentially the same results without referencing them \[1\], except that in the maximum entropy case we can only say a run happens when R reaches $c_{i} \approx 1$ (the condition dividing the two solutions becomes the **consumption** in the early period is equal to the **consumption** in the case of no banks, rather than the _utility_ of the consumption in the first period is equal to the _utility_ of the consumption in the case of no banks).



I got into looking at Diamond Dybvig earlier today because of [this post by Frances Coppola](http://coppolacomment.blogspot.co.uk/2015/04/rediscovering-old-economic-models.html), who wanted to add in a bunch of dynamics of money and lending with a central bank. The thing is that the maximum entropy approach is agnostic about how consumption is mediated or the source of the interest rate. So it is actually a pretty general mechanism that should be valid across a wide array of models. In fact, we see here that the Diamond Dybvig mechanism derives mostly from the idea of the bank budget constraint (see footnote \[1\], too), so in any model where banks have a budget constraint of the form Eq. (1) above, you can achieve bank runs. Therefore deposit insurance generally works by alleviating the budget constraint. No amount of bells and whistles can help you understand this basic message better.



It would be easy to add [this model of the interest rate](http://informationtransfereconomics.blogspot.com/2015/02/information-equilibrium-paper-draft_23.html) so that we take (allowing the possibility of non-ideal information transfer)







This would be equality in the ideal information transfer (information equilibrium) case. Adding in the [price level model](http://informationtransfereconomics.blogspot.com/2014/06/the-information-transfer-model.html), we'd have two regimes: high and low inflation. In the high inflation scenario, monetary expansion raises interest rates (and contraction lowers them); in the low inflation scenario, monetary expansion lowers interest rates (and contraction raises them). See e.g. [here](http://informationtransfereconomics.blogspot.com/2014/03/the-effects-that-move-interest-rates.html). I'll try to work through the consequences of that in a later post ... it mostly moves the bank budget constraint Eq. (1).



**Footnotes:**



\[0\] Why? I'm not sure. It makes more sense to me that people would want to spend more when they take in more ... I guess it is just one of those times in economics where this applies: ¯\\\_(ツ)\_/¯



\[1\] In that case the diagrams are much less cluttered and look like this:



![](<media/itm diamond dybvig a.png>)
![](<media/itm diamond dybvig b.png>)![](<media/itm diamond dybvig c.png>)
