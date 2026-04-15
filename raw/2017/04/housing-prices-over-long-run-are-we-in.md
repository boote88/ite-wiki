---
title: "Housing prices over the long run (are we in a boom?)"
date: 2017-04-21T16:26:00.002-07:00
updated: 2017-04-22T12:19:32.011-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/04/housing-prices-over-long-run-are-we-in.html
---

Kevin Drum has [a piece at Mother Jones](http://www.motherjones.com/kevin-drum/2017/04/were-now-second-biggest-housing-boom-all-time) (H/T [David Anderson](https://twitter.com/bjdickmayhew/status/855488296822206465)) that posits we are in the midst of another housing boom in the US, calling it the second biggest on record according to the Case-Shiller index. \[_Update:_ [Brad DeLong comments](http://www.bradford-delong.com/2017/04/must-read-there-were-three-good-reasons-in-the-mid-2000s-to-believe-that-housing-prices-should-jump-substantially-the-c.html) on Drum, proposing a boom, bust, overshoot, rebound mechanism discussed below.\] Now I've previously looked at the index [using the dynamic equilibrium model](http://informationtransfereconomics.blogspot.com/2017/01/housing-prices-and-dynamic-equilibrium.html) (see also [this presentation](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html)), but only back to the late 70s because that was what was available on FRED. Using Shiller's data from [his website](http://www.econ.yale.edu/~shiller/data.htm), we can now go back to the late 1800s.



Drum uses "real" values, adjusting for inflation. This creates some issues if your measure of inflation is mis-matched with respect to your nominal values (as described [in an example here](http://informationtransfereconomics.blogspot.com/2017/04/growth-regimes-lowflation-and-dynamic.html), and see addendum below), so we're going to focus on nominal values.



First, Drum seems to be correct about the boom ‒ assuming that we returned to the long run dynamic equilibrium, we should be at a much lower level (in everything that follows, blue is the model and yellow is the data):



![](<media/simple dynamic equilibrium test -case shiller-.png>)
![](<media/simple dynamic equilibrium test -case shiller- -model boom-.png>)

In the second graph we show the 9 shocks that best describe the data (7 booms, 2 busts):



![](<media/simple dynamic equilibrium test -case shiller- -model boom- tab.png>)

The two busts are associated with the Great Depression (1930.0) and the Great Recession (2008.5). Also of interest ‒ the Great Recession was twice as bad for housing prices as the Great Depression (in relative terms): 0.34 vs 0.78. The equilibrium rate of growth in the absence of shocks is ~ 1% per year.



According to the model, the latest boom appears to be ending, being centered in 2014.0 with a duration (width) of 1.5 years (think of this as the two-sided 1-sigma width of the [Gaussian](https://en.wikipedia.org/wiki/Gaussian_function) shock). It is not the largest boom in relative size (actually the smallest, but comparable to the 1917.9, 1970.0, and 1986.7 booms). However, with only the leading edge of the boom visible in the data, the duration and size are somewhat uncertain:



![](<media/simple dynamic equilibrium test -case shiller- -model boom- zoom.png>)

Going back to David Anderson's tweet up at the top, my own anecdotal evidence confirms this second boom as housing prices in the Seattle area have increased dramatically. Some other observations:

-   It does not appear that any housing booms are necessarily unsustainable. Out of seven booms, there have been only two busts. And the only two busts were during the Great Depression and Great Recession. While it may be that the housing bubble contributed to the latter, that leaves a sample of one on which to base conclusions like "unsustainable housing boom causes recessions when they bust". In fact, of the three largest booms, only one was followed by a bust.
-   In the absence of shocks, housing prices increase at about 1% nominally per year meaning that in the absence of shocks, housing would naturally become more affordable if wages kept up with inflation. It is housing price booms that make housing unaffordable.

**\*  \*  \***

**Addendum: Inflation**



Shiller deflates his housing prices by the consumer price index (all items). If we apply the above analysis to his data, we find a roughly similar structure:



![](<media/simple dynamic equilibrium test -case shiller- -real-.png>)


![](<media/simple dynamic equilibrium test -case shiller- -real- inflation.png>)
_Update + 3 hours:_ forgot the inflation rate graph.


However there is no CPI bust accompanying the Great Recession like for the Great Depression. Also, CPI has a shock in 1974 likely due to the oil crisis. That leaves us with 8 shocks (7 booms, 1 bust):



![](<media/simple dynamic equilibrium test -case shiller- -real- tab.png>)



As you can see, the centers and durations (σ in the figure below) are mis-matched, yielding the fluctuating effect [discussed in this post](http://informationtransfereconomics.blogspot.com/2017/04/growth-regimes-lowflation-and-dynamic.html) when you subtract the inflation shocks from the nominal housing price shocks:



![](<media/gaussian difference.png>)



Of the 7 shocks that match between the nominal index and the CPI index, all have some serious mismatch with the closest match being the 1970/1969 shock:



Center \[y\] (duration \[y\]) (size/amplitude \[rel\])



  1917.9 vs 1917.5 (1.7 vs 1.2) (0.3 vs 0.5)

  1930.0 vs 1930.5 (1.7 vs 3.4) (0.3 vs 0.5)

  1945.8 vs 1945.5 (3.1 vs 3.4) (0.9 vs 0.4)

  1970.0 vs 1969.4 (1.8 vs 1.8) (0.2 vs 0.2)

  1978.0 vs 1979.8 (3.0 vs 2.2) (0.8 vs 0.5)

  1986.7 vs 1989.7 (1.6 vs 4.4) (0.3 vs 0.3)

  2004.8 vs 2004.2 (5.4 vs 4.8) (1.3 vs 0.1)



These mis-matches yield fluctuations in the "real" price index (I am showing 4 cases = 1917, 1970/69, 1978/79, and 1986/89):



![](<media/simple dynamic equilibrium test -case shiller- -real- fluc1.png>)



In fact, the latter two are close enough together that they combine into a series of two booms and two busts (in the real data) when in fact they are just two booms (in the nominal data and cpi):



![](<media/simple dynamic equilibrium test -case shiller- -real- fluc2.png>)





The net effect is to make it look like the 1970s boom and the 1980s boom were followed by busts when neither the nominal price index nor the CPI have "busts". Another way to put this is that (in nominal terms) 1 boom + 1 boom = 2 booms + 2 busts (in real terms).



Therefore it is questionable whether the real housing price is the best measure during shocks. Outside of shocks, the real housing price shows how much housing increases relative to inflation (i.e. most goods and some fixed income). In fact, the dynamic equilibrium shows CPI grows at about 1.5% per year. This means that real housing prices in the absence of shocks **_decrease_** at about 0.5% per year (note that [gold's _nominal_ price decreases at about 2.7%](http://informationtransfereconomics.blogspot.com/2017/02/dynamic-equilibrium-price-of-gold.html)). This is apparent in Drum's graph of Shiller's data in the periods between the booms. Combining the above descriptions of the nominal price index and the CPI, we have a (remarkably good) model of the real Case-Shiller index:



![](<media/simple dynamic equilibrium test -case shiller- -model boom- -with inflation-.png>)



Note that the real index lacks a strong visible shock for the Great Depression (!) (the period from 1917 to 1945 shows relatively stable housing prices) whereas in the nominal index, it is one of the only negative shocks. 



Because the above model for the nominal index sees the most recent boom ending, we should see a return to the 0.5% decrease per year. But again, figuring out the size of booms and busts before they occur is generally difficult and fraught with uncertainty (for example, [see these estimates](http://informationtransfereconomics.blogspot.com/2017/04/predicting-future-recessions.html) of the unemployment rate ‒ the model appears to under-predict at first, then over-predict so we should probably take this as an under-prediction of the size of the current boom).

**Update 22 April 2017**

Brad DeLong [comments](http://www.bradford-delong.com/2017/04/must-read-there-were-three-good-reasons-in-the-mid-2000s-to-believe-that-housing-prices-should-jump-substantially-the-c.html) on Drum's article, saying that we might be experiencing a rebound from too far of a collapse post-financial crisis. Now it doesn't appear that the pre-2000s housing bubble equilibrium has been restored:

![](<media/simple dynamic equilibrium test -case shiller- -model boom bust boom- 1.png>)
We're still a ways above that, so is seems unlikely. However, if part of the 2000s housing bubble was sustainable, then it is possible:

![](<media/simple dynamic equilibrium test -case shiller- -model boom bust boom- 2.png>)
This does lend itself to an overshoot, bust, undershoot, and return equilibrium picture. However it requires an _ad hoc_ decomposition of the 2000s bubble into a "sustainable" and an "unsustainable" component. And there is insufficient data (only 2 busts: the Great Depression and Great Recession) to start making up theories for complex decomposition/dynamics involved in a boom-bust cycle.

The simpler model (with independent booms and busts) also says something similar ‒ a flattening of nominal housing price increases and a return to the (dynamic) equilibrium of 1% increase per year. Therefore Occam's razor should come in to play again: the simpler explanation is better ... at least until we get more data.
