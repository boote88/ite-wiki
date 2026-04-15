---
title: Matching theory and employment in information equilibrium
date: 2017-01-30T17:30:00.000-08:00
updated: 2017-01-30T17:44:15.762-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/01/matching-theory-and-employment-in.html
---

In reading up for this piece on Roger Farmer's "post-Keynesian DSGE" theory, I noted his microfoundations: search/matching theory. [Here](http://www.rogerfarmer.com/rogerfarmerblog/2017/1/28/keynesian-economics-without-the-consumption-function):

> _I provide a foundation—Keynesian search theory—to the Keynesian theory of aggregate supply. This new theory is rooted firmly in the microeconomic theory of behavior._

and [here](http://rogerfarmerblog.blogspot.com/2014/01/old-keynesian-economics-and-equilibrium.html):

> _By modelling the process by which unemployed workers are matched with jobs, we can use search theory (for which Dale Mortensen, Chris Pissarides and Peter Diamond were awarded the 2010 Nobel prize) to understand how unemployment varies over time._

Now I have presented information equilibrium as a kind of search/matching process [before](http://informationtransfereconomics.blogspot.com/2016/08/is-information-equilibrium-silly.html) (demand events matching with supply events forming transaction events), but I thought I'd look at the job openings and hires data at FRED to try to put together a general theory of employment dynamics.



_H__U__V_[From the differential equations](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html)[Cobb Douglas form](http://informationtransfereconomics.blogspot.com/2014/05/more-on-cobb-douglas-functions-and.html)








The derivation is [here](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-unemployment-rate.html) (and we also look at _U/V_ [in the JOLTS data](http://informationtransfereconomics.blogspot.com/2017/01/a-dynamic-equilibrium-in-jolts-data.html)). We can fit to the data using the same procedure as those posts:



![](<media/itm matching model 1.png>)![](<media/itm matching model 2.png>)

The resulting logarithmic derivative (slope) is -0.17/y for $\log U/H$ and 0.08/y for $\log V/H$. Now Petrongolo and Pissarides (2001) \[[pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.589.7046&rep=rep1&type=pdf)\] survey of estimations of the cobb Douglas form generally support constant returns to scale such that $a + b = 1$; this is not required in the information equilibrium model, but gives us a neat trick to use to determine the Cobb Douglas exponents $a$ and $b$.









![](<media/itm matching model 3.png>)


![](<media/itm matching model 4.png>)

Note that the difference isn't constant! The thing is that the dynamic equilibrium models with constant slopes _have non-equilibrium shocks_. During these shocks the derivation above does not hold and therefore the matching function shouldn't hold either. But the good news is that the aforementioned difference is pretty well approximated by a logistic curve (a smoothed step function) ‒ the difference is constant except during a shock:



![](<media/itm matching model 5.png>)

This tells us that during "normal times" (non-recessions) we can use a Cobb-Douglas matching function to understand the constant rate of change of the unemployment rate. However, during recessions, the shocks cause this picture to fail.



Now this doesn't mean matching theory fails during recessions. It just means a simple matching model fails and that the matching function should include its own shocks:






It would be interesting to see if the matching function shocks have any relationship to the shocks to $U/H$ and $V/H$ e.g. are they basically equal to the latter, in which case high unemployment can be seen as a shock to vacancies/openings? The data series aren't long enough to resolve it at this point (only one and a half recessions since the hires and openings data started).
