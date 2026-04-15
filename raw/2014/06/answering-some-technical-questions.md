---
title: Answering some technical questions
date: 2014-06-11T11:06:00.003-07:00
updated: 2014-06-11T11:06:52.450-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/06/answering-some-technical-questions.html
---

An [anonymous commenter](http://informationtransfereconomics.blogspot.com/2014/05/models-matter.html) has been [working to reproduce the results](http://imgur.com/vqGMUC3) on this blog and had some questions that I thought would be beneficial for others trying to do the same thing.

> _**1) I'm a little stuck on how you're getting the blue & red vectors. I grok the general concept but are those vectors representing changes in P or NGDP? My first attempt was just taking the gradient of the P surface but that doesn't seem to line up...**_

The arrows represent changes in NGDP and MB. It is kind of like the gradient, except that an increase in the price level P increases NGDP = P\*Y (also I didn't add $\delta MB$ and $\delta NGDP$ and divide by the step -- I just multiplied by a factor $\alpha$ to look at relative fractional increases). The red arrows are defined by

$$<br />
M \rightarrow \alpha M \text{ and } N \rightarrow N \frac{P(N,\alpha M)}{P(N, M)}<br />
$$

i.e. an increase in the base changes the price level, affecting NGDP. The blue arrows are given by

$$<br />
M \rightarrow M \text{ and } N \rightarrow \alpha N<br />
$$

i.e. an increase in NGDP doesn't change the base. Here is the Mathematica code:

![](<media/response to fp mp.png>)

In the picture above, I cut out some of the pieces that make the other lines in the graph to simplify the presentation. The vector "yearlist" is a list of years where the arrows are being evaluated. There is also an overall scale factor to make the pictures look nice. It is a 20% increase (1.2) and a scale factor of 2.



As a side note, I look at the gradients in more detail in this post:

[http://informationtransfereconomics.blogspot.com/2013/10/the-1970s.html](http://informationtransfereconomics.blogspot.com/2013/10/the-1970s.html)

> _**2) I don't know if this is just the vagaries of the Matlab solver(s), but I'm not getting the exact fits that you are for the parameters. A lot of the time I don't seem to get proper fits at all and it's extremely dependent on starting values.. is this your experience as well?**_

Yes, the parameter values are fairly sensitive to initial conditions. The data is noisy, so the objective function over the parameter space $p$ is noisy, and you can get stuck in a lot of local minima. I set the problem up as a minimization problem over the parameters $\min_{p} f(p, t) = |P(M(t), N(t), p) - CPI(t)|$ over a grid in the time variable (using monthly or quarterly values depending on the resolution of the data, so for e.g. a year of data, I'm solving 12 or 4 separate optimizations ... over the 50 years, that is 600 optimizations) using [this method](http://reference.wolfram.com/mathematica/tutorial/UnconstrainedOptimizationPrincipalAxisMethod.html) which is a little more robust. The Mathematica code is in the picture below:



![](media/fit.png)

> _**3) Do you have a data source for countries other than the US? I'm struggling to find good data series for places like Japan etc. and have had it with navigating the often byzantine central bank websites of these countries**_

Most of the GDP and CPI data is from [FRED](http://research.stlouisfed.org/fred2/). Monetary base data is also available there for Argentina and Switzerland (which I've used ... and apparently Russia, China, Poland and South Africa, which I haven't). For the monetary data, I frequently do have to go to the central bank websites.



For Japan, the long term time series for the monetary base is here:

[https://www.boj.or.jp/en/statistics/boj/other/mb/index.htm/](https://www.boj.or.jp/en/statistics/boj/other/mb/index.htm/)

For Canada, you can find monetary base data here:

[http://homes.chass.utoronto.ca/~floyd/macro.html](http://homes.chass.utoronto.ca/~floyd/macro.html)

I link to 300 years of UK data in this post:

[http://informationtransfereconomics.blogspot.com/2013/11/the-long-run-in-uk.html](http://informationtransfereconomics.blogspot.com/2013/11/the-long-run-in-uk.html)

For the EU, I sometimes go here (but only if I'm desperate and up for a maddening experience):

[http://epp.eurostat.ec.europa.eu/portal/page/portal/eurostat/home/](http://epp.eurostat.ec.europa.eu/portal/page/portal/eurostat/home/)

> _**4) When you put multiple countries on one chart, how are you normalizing P? I assume with a P0, but is that fitted value.. or do you say normalize all your CPIs before feeding them in..?**_

I use the fitted coefficient P0 (in the pic above, I refer to it as ΔUS in the code and α on the diagram). I also normalize all CPIs to 1 instead of 100 (out of habit) before feeding them in. The fits have a strong tendency to make P = P0 at M = M0; it has worked that way in every fit, except for Switzerland (because it is normalized to 100 in 2010 in the data from FRED). The normalization of the price level is completely arbitrary, so there was an adjustment to the Swiss data to make 1982-1984 = 100 like the US data (and then normalizing to 1).

> _**5) I've been trying to read up on information theory and the original paper - curious as to if there's any way of combining multiple sources, detectors etc. into one model - my math/intuition is not developed enough to work out how that might be done but it seems like an interesting avenue to explore...**_

I have looked at multiple (well, two) interacting markets with the same price "detector" and same information source (aggregate demand):

[http://informationtransfereconomics.blogspot.com/2013/08/deriving-is-lm-model-from-information.html](http://informationtransfereconomics.blogspot.com/2013/08/deriving-is-lm-model-from-information.html)

[http://informationtransfereconomics.blogspot.com/2013/08/scott-sumners-model-part-2\_30.html](http://informationtransfereconomics.blogspot.com/2013/08/scott-sumners-model-part-2_30.html)


The main "information transfer model" is a combination of three markets: _P:NGDP→M0_ (price level, with endogenous NGDP and M0), _P:NGDP→L_ (labor market, with exogenous NGDP and endogenous L) and _r:NGDP→M_ (interest rate market, with exogenous NGDP and exogenous M = M0 or MB for long and short interest rates, respectively).



I started down the path of combining several markets, but have only gotten to the point of Walras' law (which involves an assumption about how markets interact):



[http://informationtransfereconomics.blogspot.com/2013/09/walras-law.html](http://informationtransfereconomics.blogspot.com/2013/09/walras-law.html)

Thanks for the questions; I hope this answers them!
