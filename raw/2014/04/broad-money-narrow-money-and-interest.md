---
title: "Broad money, narrow money and interest rates"
date: 2014-04-04T17:43:00.000-07:00
updated: 2014-04-04T17:43:06.322-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/04/broad-money-narrow-money-and-interest.html
---

I was inspired by Tom Brown (in [comments on the last post](http://informationtransfereconomics.blogspot.com/2014/04/the-downward-trend-in-real-interest.html)) to attempt to understand broader measures of money with the information transfer model. The first baby steps had me starting from [this post on Nick Rowe's model of the money stock](http://informationtransfereconomics.blogspot.com/2014/03/nick-rowes-model-of-money-stock.html). I graphed the price level using the "implied" monetary base by the Fed's interest rate target (i.e. using r = f(NGDP, MB) to solve for MB) in blue, alongside the best price level fit to MZM (money with zero maturity, which the Fed tends to regard as the money stock) in red:



![](<media/mzm 0.png>)

It seems to match up well enough that there might be something to it, but I quickly realized that this must be due to MZM being a better model of interest rates than the currency component of the base ("M0") ... here it is (the old fit in terms of M0 is light blue, while MZM is dark blue):



![](<media/mzm 1.png>)

It's not immediately obvious this is a better model if we just look at the model errors (again M0 is light blue, while MZM is dark blue):



![](<media/mzm 2.png>)

However, if we look at the histogram of the errors, we can see the significant skew in the M0 model \[1\] vanishes in the MZM model.



![](<media/mzm 3.png>)

Overall, it seems MZM is more strongly linked to interest rates than M0. I'm still working on the link between MZM and M0 themselves. One idea is that difference between MZM and M0 fills the gaps in the bound -- see footnote \[1\] below. This might tie in to the [law of reflux being discussed by Nick Rowe and David Glasner](http://uneasymoney.com/2014/03/31/can-there-really-be-an-excess-supply-of-commercial-bank-money/) (we'd think of MZM as caulk filling in the gaps between the empirical interest rate and the rate given by the bound).



\[1\] This skewing is potentially due the fact that M0 makes a good bound on the 10-year interest rate (in log space). There would be a tendency for the actual interest rate to [fall below the model result](http://informationtransfereconomics.blogspot.com/2014/03/modeling-macroeconomic-fluctuations.html) (you can at most get all of the information from the source -- communication breakdowns always mean less information):



![](<media/mzm 4.png>)
