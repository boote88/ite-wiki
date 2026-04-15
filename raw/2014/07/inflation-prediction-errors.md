---
title: Inflation prediction errors
date: 2014-07-18T12:56:00.000-07:00
updated: 2015-09-18T14:23:42.109-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/07/inflation-prediction-errors.html
---

Essentially following the procedure of the [previous post](http://informationtransfereconomics.blogspot.com/2014/07/better-than-tips.html) -- fitting the price level function _P_ to data from 1960 to a year _Y_, and then log-linearly extrapolating NGDP and M0 (currency) from _Y_ to 2014 to find _P(y>Y)_ and the inflation rate _i(y>Y) = d log P/dt_ -- I thought I'd see how the errors evolve as you add more data. The log-linear extrapolations only used the past 10 years of data starting from _Y_.



In one sense, I wanted to figure out if the previous post was a fluke (it isn't), and also what the error would be on predicting inflation _2014 - Y_ years out.



Here are the inflation extrapolations colored in rainbow colors with red being the most recent and purple being the most distant past (the CPI inflation data is the green jagged line):



![](<media/ite predictions us 1.png>)

And here are the errors (absolute value of the mean difference between the prediction and the measured CPI) as function of years out the prediction is made (_2014 - Y_):



![](<media/ite predictions us 2.png>)

The graph shows the irreducible measurement errors in gray. Inflation is not a smooth curve and the measurement of CPI contains some fluctuations month to month. If one averages over shorter and shorter periods, even if you have the trend exactly right, you're going to get larger and larger errors. I estimated this effect by finding the distribution of errors around a linear fit to 1994 to 2007 inflation data (a fairly straight line) to estimate the error distribution. Using the estimated distribution, I ran Monte Carlo simulations of the absolute value of the mean error averaged over different time periods to produce the gray band of points. You can see that this accounts for much of the model prediction error over shorter time periods (red points on the left side of the graph above). Additionally, the 12 basis point error from _Y =_ 2007 (7 years back from 2014) in the previous post is typical for extrapolation from that time period and likely represents only irreducible error.



That is a pretty startling piece of information. It means you likely can't do any better than the information transfer model in predicting inflation in the medium term (5-15 years out).
