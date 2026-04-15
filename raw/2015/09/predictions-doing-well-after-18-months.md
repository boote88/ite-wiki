---
title: Predictions doing well after 18 months
date: 2015-09-09T13:00:00.000-07:00
updated: 2015-09-18T14:23:42.075-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/09/predictions-doing-well-after-18-months.html
---

69 days into 2014, and less than a year since I started this blog I (and my hubris) decided to [try to predict the next two years of macroeconomic indicators](http://informationtransfereconomics.blogspot.com/2014/03/macroeconomic-predictions-for-2016.html): core CPI, short (3-month) and long (10-year) interest rates, RGDP and the unemployment rate. OK, the last two weren't really model predictions -- RGDP falls out of the NGDP projection and the core CPI (so it's not really independent of the CPI prediction) and the unemployment rate model was actually just some speculation and a "metastability" model I invented in the original prediction post. There have been two previous updates ([one](http://informationtransfereconomics.blogspot.com/2014/08/prediction-update-not-bad-for-five.html), [two](http://informationtransfereconomics.blogspot.com/2015/01/not-bad-for-five-parameters-take-two.html)).



The model took as input some ('theory-free') simple quadratic extrapolations of the data from 2013 Q1-Q4 out to the end of 2016. I only later came up with the [NGDP-M0 path](http://informationtransfereconomics.blogspot.com/2014/06/output-and-price-level-behavior-across.html) which would turn NGDP into a predicted value.



Since there are some new readers out there, I thought I'd write up the details of the procedure so you don't have to go hunting around the blog. The basic models appear in the [draft paper](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html). All of the data is from FRED.



**Inputs:**


-   NGDP 1960 Q1 to 2013 Q4 (GDP)
-   M0 1960 Q1 to 2013 Q4 (MBCURRCIR)
-   MB 1960 Q1 to 2013 Q4 (BASE)


_α__m0_ _γ_
_a_ _b_
_kL/kU = u\*_




**Data used in fit:**


-   NSA core CPI 1960 Q1 to 2013 Q4 (CPILFENS, as available March 2014)
-   3-month secondary market rate 1960 Q1 to 2013 Q4 (WTB3MS, as available March 2014)
-   10-year constant maturity rate 1960 Q1 to 2013 Q4 (DGS10, as available March 2014)
-   Unemployment level (UNEMPLOY), total employed (PAYEMS) and civilian labor force (CLF16OV) 1960 Q1 to 2013 Q4 (all as available March 2014)


**Extrapolations (log-quadratic):**


-   NGDP 2014 Q1 to 2015 Q4
-   M0 2014 Q1 to 2015 Q4
-   MB 2104 Q1 to 2015 Q4




![](<media/pred 5.png>)


**Outputs:**


-   Year over year core CPI (NSA)
-   RGDP
-   3-month interest rate (bound and band)
-   10-year interest rate (bound and band)
-   "Natural rate" of unemployment (just a single number _u\*_ = 5.7%)



![](<media/pred 3.png>)
![](<media/pred 4.png>)
![](<media/pred 2.png>)

There was a spike in short term rates this past summer -- likely stemming from talk of the Fed raising rates after the upcoming meeting.



![](<media/pred 1.png>)

There wasn't any noticeable pause in the blue region, so the metastability theory may not be correct. Or maybe we're heading directly to the utopian 4% green band that hasn't been realized since the 1990s.



Aside from the extrapolated paths, I had one other "caveat" that there wouldn't be any '[nominal (NGDP) shocks](http://informationtransfereconomics.blogspot.com/2015/08/employment-doesnt-depend-of-inflation.html)' in during the prediction period. Since these appeared to be unpredictable at the time (and only later did I come up with a tentative metric for [determining whether shocks were likely](http://informationtransfereconomics.blogspot.com/2014/08/are-interest-rates-good-indicator-of.html)), I had a plot of predicted value of NGDP shocks (based on NGDP and the model prediction from CPI):



![](<media/pred 6.png>)
