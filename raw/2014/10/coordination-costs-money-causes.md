---
title: "Coordination costs money, causes recessions"
date: 2014-10-13T22:45:00.003-07:00
updated: 2015-09-18T14:21:51.671-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/10/coordination-costs-money-causes.html
---

_coordination_


This is, in a sense, the converse of what [David Glasner refers](http://uneasymoney.com/2014/10/08/aggregate-demand-and-coordination-failures/) to in his recent and several of his prior posts. Glasner advocates a theory of coordination failure to explain what recessions are, how unemployment can rise above full employment and why wages are "sticky". I will get back to Glasner towards the end of this post.



I started to put together an initial version of my thesis [in part III of this post](http://informationtransfereconomics.blogspot.com/2014/10/entropy-in-three-pieces.html); here I plan to further develop it with a toy model (although there is no real loss of generality here -- it just helps to be explicit).



In [my response](http://informationtransfereconomics.blogspot.com/2014/10/wage-stickiness-is-entropic-force.html) to one of Glasner's prior posts, I put forward the idea that wage stickiness is an entropic force. Coordinated changes to the distribution of wages costs "entropy", and this cost is experienced in the macroeconomy as the resistance of the wage distribution to change ("stickiness"). Let me return to the wage distribution in that post; we had four cases:


![](<media/ite adjustment 0.png>)![](<media/ite adjustment 1.png>)
![](<media/ite adjustment 2.png>)![](<media/ite adjustment 3.png>)

Starting from the top left and going clockwise we have (1) the original distribution(roughly coinciding with the theoretical curve in blue) , (2) the distribution re-arranged to over-represent nominal wage cuts (the vertical line represents zero growth), (3) the distribution re-arranged to over-represent zero nominal wage growth (as [observed in data](http://www.frbsf.org/economic-research/publications/economic-letter/2012/april/strong-wage-growth/) from the SF Fed), and finally (4) a distribution with 10% of the distribution thrown out of the labor force (i.e. unemployment).



Of course, dealing with a continuous normal distribution is hard, so I decided to take these scenarios on as uniform distributions:


![](<media/ite adjustment uniform distribution 0.png>)![](<media/ite adjustment uniform distribution 1.png>)
![](<media/ite adjustment uniform distribution 2.png>)![](<media/ite adjustment uniform distribution 3.png>)

The other benefit to using a uniform distribution is that we can directly relate it to [the economic combinatorial problem](http://informationtransfereconomics.blogspot.com/2014/09/the-economic-combinatorial-problem.html) where the number of states goes as $NGDP!$ (that's a factorial, not shouting NGDP) and "economic entropy" $S_{e}$ is:





Let's call $(NGDP/c_{0})! \equiv n$ the number of states in the economy. The other key ingredient we need to use is the fact that total nominal wages (NW) are directly proportional to NGDP -- this allows us to make identical arguments and switch back and forth between NGDP and nominal wages. Now scenario 4 directly reduces NW -- we've thrown 10% (let's call that $m$) of the labor force out of the economy -- and is associated with a fall in $S_{e}$:





It is not necessarily immediately obvious that the other changes are also associated with changes in $\Delta S_{e}$, but it turns out they are. In scenario 2, if we take the probability that a state is one of the over-represented states to be $p$ and the under-represented states to be $1 - p$, then going back to the [definition of entropy](http://en.wikipedia.org/wiki/Entropy) in terms of the probability of states (which coincides with the Shannon entropy in information theory I touched on once before [in this post](http://informationtransfereconomics.blogspot.com/2014/05/expectations-destroy-information.html)), we can work out the change in entropy to be:





If we take $m = 0.1 n$ and $p = 0.3$, then  equation (1) gives us -0.105 and equation (2) gives us -0.154. If $p = 0.262$, then the entropy loss is the same for scenarios 2 and 4 (i.e. -0.105). That is to say that an over-representation of 10% of the wage growth (or here, wage cut) states by a bit more than a factor of 2 (e.g. doubling the number of people who take wage cuts relative to normal times) is an equivalent entropy loss to removing that 10% from the labor force.



We can also use equation (2) to give us an estimate of the entropy loss from "sticky wages" in scenario 3 -- zero nominal wage growth for some fraction of the population. In that case $m = 1$ (a single state, zero growth, is over-represented). If we have a lot of states and $n \gg 1$, we can approximate





where $H$ is the binary entropy function with information measured in nats. The entropy loss in scenario 3 is approximately the fraction of entropy given by the probability of an individual in the labor force finding himself or herself in the zero nominal wage growth state. In the data from the SF Fed, 16% of individuals are in that state, so that would represent a loss of 16% of "entropy" ... assuming the initial distribution was uniform. Now it isn't a uniform distribution and what really matters is the change in the distribution relative to the distribution in normal times. Most people usually go for a long period of time -- maybe a year or so -- at the same wage/salary after they get a raise, for example. That would mean the zero growth state is probably over-represented in normal times regardless of the distribution, and we would be referring to over-representation above and beyond that level.



The key take-away, however, is that all three scenarios represent a loss of entropy. And for small changes in NGDP, we can use Stirling's approximation in equation (0) to show:





Entropy loss is NGDP loss -- an economic shock. In each of the scenarios 2 and 3, the resulting distribution is more coordinated relative to the normal state in scenario 1. The uniform distribution (or Gaussian/normal distribution) represent minimally informative (maximum ignorance) distributions; another way, there is knowledge gained (ignorance lost) in the distributions of scenarios 2 and 3. Something is coordinating market outcomes to produce a distribution that otherwise would not exist. That something is human behavior.



A recession is a temporary human coordination of the market \[2\] (through some sort of market panic or possibly guided by an economic authority like the central bank) that results in a loss of NGDP. This is how we can have all the same stuff before and after a recession strikes, but somehow it's all worth a bit less in the aftermath. The temporary coordination results in a bit of scenario 4 (the economy shedding jobs) and scenario 3 (zero nominal wage growth/sticky wages).



_Why not scenario 2 (nominal wage cuts)?_ This is the problem that Keynes tried to deal with via sticky wages and the liquidity trap and to suggest that it wouldn't happen was so implausible to neoclassical economics that they assumed it away. This is Glasner's _**coordination failure**_ -- if we (or the market) implemented scenario 2 instead of scenario 4 (unemployment), we could keep everyone employed.



My guess is that scenarios 3 and 4 represent channels that are much more efficient than scenario 2. In order to achieve the same entropy loss as scenario 4, scenario 2 has to over-represent 10% of the wage states by more than a factor of 2 -- that means that on the order of 30% of the labor force has to get nominal wage cuts (rather than 10% of the labor force getting pink slips). Likewise, 10% of the labor force having zero wage growth can accommodate a shock of 5% of NGDP (using NGDP ~ 2.1 NW). Using scenarios 3 and 4 together can have more impact than scenario 2 and involve fewer people. This suggests the market could be using its own [principle of least effort](http://en.wikipedia.org/wiki/Principle_of_least_effort).



Interestingly, attempting to implement the nominal wage cut coordination it after the recession hits would involve adding NGDP comparable to the loss in NGDP from the sticky wages/unemployment coordination -- immediately bringing to mind fiscal stimulus sufficient to close the output gap as advocated by Keynesians.



Whether the coordination happens spontaneously due to announcements from the Fed or financial panics or is encouraged through government spending or monetary stimulus, it costs money in both senses of the word -- you lose money if coordination happens and you have to pay in order to get coordination.


**Footnotes:**


\[1\] Also note that for a system with constant volume and temperature, a change in entropy is a change in "free energy" -- a reduction in entropy consumes free energy, whereas an increase in entropy gives off free energy (this is how e.g. life typically works).



\[2\] Basically, because the market is made of people, we can violate the second law of thermodynamics (ΔS > 0) by coordinating ourselves in a way that atoms or particles can't. There is no second law of econo-dynamics because of human behavior -- which is unfortunate because otherwise (if human nature didn't matter) ΔS > 0 would imply ΔNGDP > 0 -- the economy would always grow (absent real shocks like natural disasters or resources running out).
