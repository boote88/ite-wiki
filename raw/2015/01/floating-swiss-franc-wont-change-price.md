---
title: "Floating the Swiss Franc won't change the price level"
date: 2015-01-19T11:30:00.000-08:00
updated: 2015-01-19T11:30:01.080-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/01/floating-swiss-franc-wont-change-price.html
---

Commenter [Charlie Clark asked](http://informationtransfereconomics.blogspot.com/2015/01/switzerland-depreciated-their-currency.html?showComment=1421611184394#c6253410522000045459) for a prediction from the information transfer model (ITM) after [my post on Switzerland](http://informationtransfereconomics.blogspot.com/2015/01/switzerland-depreciated-their-currency.html) in the wake of abandoning its currency peg. I mentioned at the comment that the ITM would predict essentially a linear extrapolation from the price level curve that I had that contained data through the end of 2013, but said I would post a more concrete version as soon as I got the chance \[1\]. This is that post.



Actually, the prediction below uses the same data I used in the price level graph in the Switzerland post (i.e. up until the end of 2013 -- the exact end date was 2014.0, i.e. 01 Jan 2014). This means the result is a prediction of the data from the end of 2013 (i.e. 2014.0) through the end of 2015 (i.e. 2016.0) and we can see that the CPI data points from January 2014 to November of 2014 (the last [available on FRED](https://research.stlouisfed.org/fred2/series/CHECPICORMINMEI#)) are right on the trend line as predicted (shown in solid green):


![](<media/ite switzerland model -inflation prediction-.png>)

The model is blue, and the data are green as usual on this blog. Here is year over year (YoY) inflation:


![](<media/ite switzerland model -inflation prediction- 1.png>)

I use YoY inflation because I don't currently have seasonally adjusted data \[2\]. The model basically predicts an average of near zero inflation through the end of 2015. Like the initial pegging of the Swiss Franc in March of 2011, floating in January of 2015 won't have a major impact on the price level in the information transfer model -- except for the potential for market fluctuations.


**Footnotes:**


\[1\] One change from the [previous price level fit](http://informationtransfereconomics.blogspot.com/2015/01/switzerland-depreciated-their-currency.html) was that I smoothed the monetary and NGDP data (like I [first did here](http://informationtransfereconomics.blogspot.com/2014/08/smooth-move.html)) in order to get a linear extrapolation of those datasets. However, that didn't change very much in terms of the original model result. I provide the original version as a reference.


![](<media/ite switzerland model -inflation prediction- 0.png>)

\[2\] I dislike YoY inflation as a metric because e.g. a high inflation number could just mean that the data points at time _t_ and time _t-1_ represent positive and negative fluctuations, respectively. I am working on an ARIMA filter so that I can do the seasonal adjustment myself in the future.
