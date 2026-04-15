---
title: Models and metrics
date: 2014-02-10T16:36:00.004-08:00
updated: 2014-02-10T16:36:48.379-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/02/models-and-metrics.html
---

I realized I hadn't given a lot of time to the metrics for the model fits. It turns out that they aren't really very informative -- errors are correlated so metrics like R squared tend not to show which model is worse. In fact, the adjusted R squared for the information transfer model (ITM) is 0.999 for both the monetary base including reserves (MB) and currency component (M0) [versions](http://informationtransfereconomics.blogspot.com/2014/02/the-role-of-central-bank-reserves-in.html). True it is "only" 0.9 for the quantity theory of money (QTM) where P = k  M0 and 0.75 for a constant (P = k), but therein lies the problem. However residuals tend to be a good metric and in this case tend to be a little more informative, so I'll present those.



First, here are the model fits to the price level (clockwise from top left: QTM, ITM constant κ \[1\], ITM M0 and ITM MB):


![](<media/basic us model m0 fit parameter tests.png>)


![](<media/model residuals.png>)

The mean residual fractional error is 0.03 for the ITM M0 model, 0.04 for the ITM MB model, 0.10 for the ITM constant κ model and 0.37 for the QTM (horizontal lines). Basically, anyone who takes the quantity theory of money seriously should take the ITM even more seriously, but that isn't saying much except to hard core monetarists.



Here are the errors for the ITM MB and ITM M0 models blown up and put on a linear scale:



![](<media/model residuals 2.png>)

You can see that the recent QE is the only obvious reason to reject the ITM MB model -- otherwise the errors are really close to each other \[2\]. But then the recent QE is the major reason MB differs from M0! Fitting the recent years makes the years in 70s and 80s worse in the MB version of the ITM than the M0 version.



Still, the errors are correlated. They don't seem to have any particular relation to recessions. There are two periods of especially low error that are associated with economic booms (the late 60s and late 90s) and the period of high inflation from the 70s and 80s is associated with the largest persistent error. However, the ITM M0 version doesn't sustain 5% errors for very long.



\[1\] Constant κ uses the same function as the M0 and MB models P ~ (1/κ) M0^(1/κ - 1), but keeps κ constant.



\[2\] Trying to match the derivative (inflation rate) will give an additional reason to accept the ITM M0 version over the MB version.
