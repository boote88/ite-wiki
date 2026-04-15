---
title: Growth and the business cycle in the information transfer model
date: 2015-06-17T19:18:00.000-07:00
updated: 2015-06-17T19:18:10.262-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/06/growth-and-business-cycle-in.html
---

There was some good discussion [in comments on the previous post](http://informationtransfereconomics.blogspot.com/2015/06/mathiness-is-next-to-growthiness-4.html); I thought I'd summarize some aspects of the information transfer model (ITM) brought up by John Handley (on the components of the model involved in the growth rate) and LAL (on the business cycle). The overall model shows that without the recessions and the ITM trend, the fluctuations in RGDP growth [do not have unit root](http://informationtransfereconomics.blogspot.com/2014/01/rgdp-growth-does-not-have-unit-root.html) -- which means they are essentially random fluctuations with zero mean. This means we can look at RGDP growth as the sum of three components:



![](<media/rgdp growth generic.png>)

These three components are pictured above:

> **Noise** _(in gray)._ Random fluctuations around the ideal growth path. It may be entirely measurement error or fundamental fluctuations because the economy is (in physics terms) a mesoscopic system with the system size _N > 1_, but not _N >> 1_.  Note that this is simulated with a normal distribution with standard deviation of 2 (percentage points) and mean of zero.

> **Non-ideal information transfer** _(recessions, dashed blue)._ This is the component that is least understood in terms of the model itself. The ITM _allows_ non-ideal information transfer, but doesn't tell us what it looks like. The piece I put here is a guess (it's a step function on the leading edge and a Fermi distribution on the trailing edge). Although it is uncertain at this point how much of these recessions are real shock and how much are human emotion. More on that [here](http://informationtransfereconomics.blogspot.com/2015/03/non-ideal-information-transfer-tail.html). 

> **Ideal information transfer** _(information equilibrium, solid blue)._ This is the trend of GDP that falls out of the [partition function approach](http://informationtransfereconomics.blogspot.com/2014/06/the-macroeconomic-partition-function.html) (or just treating it [as a line in NGDP-M0 space](http://informationtransfereconomics.blogspot.com/2013/10/the-1970s.html)). RGDP slowly falls because as an economy grows, a given dollar is more and more likely to be found facilitating a transaction in a low growth market. I just simulated this with a slowly falling function here.

You can sum them up to produce these pictures of the growth rate and the level:



![](<media/rgdp growth generic together.png>)![](<media/rgdp growth generic level.png>)

With this interpretation there really isn't a thing that I'd call a "business cycle". Going back to the [sandpile analogy](http://informationtransfereconomics.blogspot.com/2014/03/the-monetary-base-as-sand-pile.html) we have a randomly fluctuating flow of sand with an average rate. The height of the sand pile grows, but more slowly over time. Every once in awhile there is an avalanche and the height drops by more than usual. There is a cycle in the sense that the growth rate becomes negative and then positive again when avalanches occur. But instead of referring to the "sandpile height cycle", I'd personally just refer to "avalanches". By analogy, there isn't a "business cycle", but rather occasional "adverse shocks". Those shocks may be entirely random (although I have a speculative theory they are not in the sense that you can predict an [increasing likelihood of shock](http://informationtransfereconomics.blogspot.com/2014/08/can-information-theory-predict.html) ... and [interest rates look like a good indicator](http://informationtransfereconomics.blogspot.com/2014/08/are-interest-rates-good-indicator-of.html) too).






As a postscript, John Handley did have one question about the moving average that was the subject of the last post. The Great Recession looks like it permanently lowers the average growth rate in the graphs in that post. However that is just an artefact of using a 10-year window when the Great Recession was less than 10 years in the past. In the simulation above, I use a 5 year window to show that the effect of the lower average goes away when the shock leaves your averaging window (black line):



![](<media/rgdp growth generic avg.png>)

I also show the average rate using Cochrane's original method (gray). It comes out a bit higher as it did in the previous post.
