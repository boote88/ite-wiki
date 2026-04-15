---
title: Comparison of interest rate predictions
date: 2015-08-18T17:00:00.000-07:00
updated: 2015-09-18T14:23:42.092-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/08/comparison-of-interest-rate-predictions.html
---

![](<media/chart1_ Historical_Rates_Forecasts_blogcharts.jpg>)

> _The decline \[in long term interest rates\] has come largely as a surprise. Financial markets and professional forecasters alike consistently failed to predict the secular shift, focusing too much on cyclical factors._

The above graph and quote are from this [blog post by Obstfeld and Tesar](https://www.whitehouse.gov/blog/2015/07/14/decline-long-term-interest-rates) (H/T [John Cochrane](http://johnhcochrane.blogspot.com/2015/08/the-decline-in-long-term-interest-rates.html)) from July of this year.



I've been doing some [time series forecasting using the information equilibrium (IE) model recently](http://informationtransfereconomics.blogspot.com/2015/08/interest-rates-and-predictions.html); how does the IE model compare to the Blue Chip Economic Indicators (BCEI)?



With the exception of 2005 (which is when the Fed embarked on its tightening before \[1\] the great recession) where the prediction is uncertain, the IE model does a much better job of forecasting 10-year nominal interest rates in the far future. The bands in the following are the 1-sigma errors (68% confidence limits).



**1996**


In this case, the IE model is a bit low in the near term, but better in the long term -- the opposite of the BCEI predictions.



![](<media/ITM interest rates and price level -prediction comparison- 1996.png>)

**2000 (1999)**


In this case, I used 1999 as the prediction year instead of 2000 because the spike in base money due to fears of the 1999/2000 transition throws the model off. Even this does better than the (March of) 2000 BCEI predictions.



![](<media/ITM interest rates and price level -prediction comparison- 1999.png>)

**2005**


This is the aforementioned case where the IE model becomes uncertain of the path of future rates and the Fed guides the economy between the high (initially) and low end (after the crisis) of the prediction bands.



![](<media/ITM interest rates and price level -prediction comparison- 2005.png>)

**2010**



![](<media/ITM interest rates and price level -prediction comparison- 2010.png>)

**2015**


We don't have the data yet, but I'd hazard a guess that the IE model predictions will be better than the BCEI predictions. If the Fed goes through with its projected short term rate increase in September-ish time period, it could impact this projection, but only if the Fed unwinds a large fraction of the QE in the short term.



![](<media/ITM interest rates and price level -prediction comparison- 2015.png>)




The information equilibrium model for interest rates is described [here](http://informationtransfereconomics.blogspot.com/2015/02/information-equilibrium-paper-draft_23.html) and [here](http://informationtransfereconomics.blogspot.com/2014/06/the-information-transfer-model.html). In the notation I've used (described at the second link), we have the model _(r → p) : N → M_ where _N_ is NGDP, _M_ is base money (minus reserves), _r_ is the interest rate and _p_ is the 'price of money'. In words, that model reads:

> Aggregate demand (_N_) is in information equilibrium with base money (_M_). The quantity information flow from aggregate demand to aggregate supply ([mediated](http://informationtransfereconomics.blogspot.com/2015/05/money-defined-as-information-mediation.html) by money) is measured by the price of money (_p_). That price is in information equilibrium with the nominal interest rate (_r_).


**Update 8/19/2015:**


The model (green line) shown in all of the graphs above is actually the model fit using all of the data from 1960 to 2015. However, the projections only use the model fit to the data from 1960 to the projection year (1996, 1999, 2005, 2010, 2015). This is visible in some of the projections above as the start point of the projection is noticeably off of the green line (2005 is the most visible, 1999 is the second most visible).



The model fit for 2015 is:

_log r = k₁ log(N/M) - k₂_

with

_k₁ = 2.8_

_k₂ = 6.4_



Using FRED series _M =_ MBCURRCIR \[converted from millions to billions of dollars\], _N =_ GDP and _r =_ GS10.



You can have a look at the model here (with fit parameters):



[https://research.stlouisfed.org/fred2/graph/?g=1EJp](https://research.stlouisfed.org/fred2/graph/?g=1EJp)



**Footnotes:**


\[1\] I wanted to put "precipitating" instead of "before" because of [some other considerations of the IE model](http://informationtransfereconomics.blogspot.com/2014/09/the-emerging-story-of-great-recession.html), but went with the more neutral version.
