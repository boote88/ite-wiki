---
title: Core CPI and lags
date: 2015-10-15T13:30:00.000-07:00
updated: 2015-10-15T15:02:18.378-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/10/core-cpi-and-lags.html
---

The latest core CPI data came out today and is up on FRED. I thought I'd post a picture of the model results without smoothing [as I did for the PCE numbers](http://informationtransfereconomics.blogspot.com/2015/10/prediction-update-core-pce-inflation.html) that came out at the beginning of the month. However I noticed a pretty obvious lag in the CPI data relative to the model (there is no obvious lag in the PCE inflation data \[1\]), so I decided to try and do a four-parameter fit with a lag _y0_ (along with _α_, _m0_ and _γ_ \-- [see paper](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html)).



Overall, it works pretty well (model = blue, data = green and 1-sigma error bands) with the lag being _y0_ \= 1.2 years:



![](<media/ITM basic us price level model -core CPI- with lag 1.png>)


![](<media/ITM basic us price level model -core CPI- with lag 2.png>)

If the lag is correct, then the model gives the future values of core CPI (past the vertical line) using data available today.





**Update**


Although less obvious, the lag has the opposite sign for Japan (_y0_ \= -0.9):



![](<media/japan inf -lags- 1.png>)![](<media/japan inf -lags- 2.png>)


**Footnotes:**

\[1\] Here is the graph for reference:

![](<media/FOR PAPER ite predictions us 2.png>)

One interesting thing is that maybe PCE inflation measures CPI inflation y0 = 1.2 years in the future -- which might (partially) explain why PCE inflation comes in about [0.3 percentage points lower](http://informationtransfereconomics.blogspot.com/2015/03/undershooting-inflation.html) (per Scott Sumner).
