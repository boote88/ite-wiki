---
title: "\"Out of sample\" predictions with the information transfer model"
date: 2014-05-30T15:18:00.000-07:00
updated: 2014-05-30T15:26:00.324-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/05/out-of-sample-predictions-with.html
---

I understand some of the issues (see [here](http://en.wikipedia.org/wiki/Model_validation) and [here](http://en.wikipedia.org/wiki/Cross-validation_\(statistics\))) that come up when you try to test a model by fitting it to one subset of the available data and using it to predict values in another subset (that's what I mean by the quotation marks around "out of sample"). However, I thought it might be illuminating to see how much of the data from the period 1960-2014 is needed to accurately model the price level and inflation rate or "predict" generic trends. To that end, I fit the price level model to the data from the periods 1960-1970 (red), 1960-1975, 1960-1980, ... 1960-2005, and 1960-2010 (violet), following a rainbow color scheme (the data is the gray dotted line). In the graph below, I only show the "predicted" values extrapolated from the fits, which start at the vertical lines:



![](<media/itm out of sample price level 2.png>)
**Update 5/30/2014**[model](http://informationtransfereconomics.blogspot.com/2014/03/the-diminishing-effect-of-monetary.html)


We can see fairly rapid convergence to the price level after about 25 years of training data (1960-1985), which is shown more clearly in this plot of the fit parameter values:



![](<media/itm out of sample price level 1.png>)

The interesting piece is that the trend towards a less-steep price level as the monetary base increases (a falling inflation rate, i.e. the effect seen in [this graph](http://informationtransfereconomics.blogspot.com/2014/02/it-really-does-seem-to-be-about-size-of.html)) is already visible even in the fit to 1960-1970 (red) extrapolated to 1960-2014 -- that is, using the information transfer model, you could have seen the current "[lowflation](http://krugman.blogs.nytimes.com/2014/05/10/already-in-the-lowflation-trap/)" environment in the US coming in the 1970s (amazingly, when inflation was at its peak).



This finding is more visibly dramatic if you look at the (year-over-year) inflation rate:



![](<media/itm out of sample price level 3.png>)



**The red line is predicting low inflation in the 2000s just from 10 years of data in the 1960s** (given the empirical path of the monetary base and NGDP). In fact, the issue that throws off the price level fits from that time and isn't predicted by the extrapolation are the two big spikes in inflation in the 1970s. We saw these before in [this post on the 1970s](http://informationtransfereconomics.blogspot.com/2013/10/the-1970s.html) -- attributed (at least in narrative form) to the oil shocks of the time, but could also be related to the "[Fisher effect](http://informationtransfereconomics.blogspot.com/2014/03/the-fisher-effect.html)" and expected inflation.



Let me caveat the use of the word "prediction" here. The model uses as input empirical values of the currency component of the monetary base ('M0') and NGDP in the extrapolations. However, the model parameters are fixed in that original 10 years of data. In order to get the current inflation rate, you'd stick the current values of NGDP and M0 into the formula you would have had around since the 1970s (if it had existed at the time). That is, the model _predicts a fixed relationship_ between P, M0 and NGDP and given any two values, fixes (i.e. "predicts") the third.
