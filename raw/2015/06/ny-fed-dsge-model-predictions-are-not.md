---
title: NY Fed DSGE model predictions are not doing well
date: 2015-06-01T16:00:00.000-07:00
updated: 2015-09-18T14:23:42.081-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/06/ny-fed-dsge-model-predictions-are-not.html
---

The latest core PCE inflation numbers are out for April 2015 (at FRED), so here's an update of the IT model prediction in [the head-to-head](http://informationtransfereconomics.blogspot.com/2015/03/the-latest-pce-inflation-numbers-are-out.html) with the [NY Fed DSGE model](http://libertystreeteconomics.newyorkfed.org/2014/09/the-frbny-dsge-model-forecast.html#.VWzR1M9VhHx). With the additional data points available since the last update, the NY Fed DSGE model has gone from performing terribly (relative to the IT model), to just performing poorly (relative to the IT model):


![](<media/comparing with the NY Fed 1.png>)

It is not yet statistically significant using some basic tests (the distribution of residuals), but comparing both models to an "ideal" model (dashed gray) based on an HP-like filter of the data (actually a LOESS filter, but these are roughly equivalent for some choice of smoothing parameters), the IT model (blue) is performing better than the DSGE model (red).



![](<media/comparing with the NY Fed 2.png>)

Actually, a constant model (inflation = constant, green dotted above) seems to be performing better than the NY Fed DSGE model at this point. The main problem is that the NY Fed DSGE model is showing the inflationary bias evident in both the market (from e.g. [TIPS spreads](http://informationtransfereconomics.blogspot.com/2014/07/better-than-tips.html)) and the [simple martingale model](http://informationtransfereconomics.blogspot.com/2014/04/inflation-predictions-are-hard.html) of adaptive expectations.
