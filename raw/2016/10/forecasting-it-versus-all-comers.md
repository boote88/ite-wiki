---
title: "Forecasting: IT versus all comers"
date: 2016-10-19T20:17:00.004-07:00
updated: 2016-10-19T20:17:46.452-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/10/forecasting-it-versus-all-comers.html
---

On Twitter, [John Handley asked](https://twitter.com/jwhandley17/status/787178642455433216) about forecasting inflation with a constant 2% inflation as well as a simple AR process in response to [my post about how the information transfer (IT) model holds its own against the Smets-Wouters DSGE model](http://informationtransfereconomics.blogspot.com/2016/10/forecasting-it-versus-dsge.html) (see this link for the background). I responded on Twitter, but I put together a more detailed response here.



I compared the original four models (DSGE, BVAR, FOMC Greenbook, and the IT model) with four more: constant 2% (annual) inflation, [an AR(1) process](https://en.wikipedia.org/wiki/Autoregressive_model), and two [LOESS smoothings](https://en.wikipedia.org/wiki/Local_regression) of the data. The latter two aren't actually forecasts -- they're the actual data, just smoothed. I chose these because I wanted to see what the best possible model would achieve depending on how much "noise" you believe the data contains. I chose the smoothing parameter to be either 0.03 (achieving an _R²_ of about 0.7, per [this](http://informationtransfereconomics.blogspot.com/2016/05/a-review-of-cesar-hidalgos-why.html)) or 0.54 (in order to match the _R²_ of the IT model one quarter ahead).  And here are what the four models look like forecasting one quarter ahead over the testing period (1992-2006):


![](<media/constant inflation.png>)![](<media/AR process.png>)
![](<media/loess 003.png>)![](<media/loess 054.png>)

So how about the performance metric (the _R²_ of forecast vs realized inflation)? Here they are, sorted by average rank over the 1Q to 6Q horizon:



![](media/Picture1.png)



First, note that I reproduce the finding (per [Noah Smith](http://noahpinionblog.blogspot.co.uk/2013/05/what-can-you-do-with-dsge-model.html)) that an AR process does better than the DSGE model. Actually, it does better than anything except what is practically data itself!



The IT model does almost exactly as well as a smoothing of the data (LOESS 0.54), which is what it is supposed to do: it is a model of the macroeconomic trend, not the fluctuations. In fact, it is only outperformed by an AR process (a pure model of the fluctuations) and a light smoothing of the data (LOESS 0.03). I was actually surprised by the almost identical performance for Q2 through Q6 of the LOESS smoothing and the IT model because I had only altered the smoothing parameter until I got (roughly) the same value as the IT model for Q1.



The DSGE model, on the other hand, is only slightly better than constant inflation, the worst model of the bunch.
