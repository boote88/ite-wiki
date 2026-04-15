---
title: Economy in the U.K.
date: 2013-10-01T15:24:00.000-07:00
updated: 2017-01-21T22:29:15.658-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/10/economy-in-uk.html
---

_I know what I want and
I know how to get it_


Although I tried it already, I thought I'd do [this](http://informationtransfereconomics.blogspot.com/2013/09/analyzing-eu-with-information-transfer.html) for the UK. I re-used some the [data I used in this attempt](http://informationtransfereconomics.blogspot.com/2013/08/modeling-uk.html), however the problem with that was that there was insufficient data from the period before the recent crisis so the fit over-weighted it. The reserves component of the base only goes back to 2006, and the currency component only goes back to 1996, so in reality I was only working with data from 2006-2013.





Therefore I decided to use some extrapolation (linear extrapolation in log space) as well as (for the first time) actually trusting my [interest rate model](http://informationtransfereconomics.blogspot.com/2013/08/the-interest-rate-in-information.html) in order to determine the monetary base further back. It worked when I used a fit to US interest rates from 1960-2013 on data from 1930-1960, so I figured I could extrapolate the monetary base data back to 1986 through the interest rate data from [FRED](http://research.stlouisfed.org/fred2/series/GBP3MTD156N).



I did it in two stages. First, I did a linear extrapolation (in log space) of the reserve balances data before 2008 back to the beginning of the currency data (1996). This formed the basis for a fit to the interest rate:



![](<media/price level uk.png>)

The dashed blue curve represents using the interest rate model to extrapolate the 1996-extrapolated data (solid blue curve) to 1986. The 3-month LIBOR data is green. The resulting monetary base is shown here:



![](<media/price level uk mb.png>)

Green is actual reserve balance data, red is actual currency data, dark blue is the 1996-extrapolated data (the sum of the currency and extrapolated reserves) and light blue is the interest rate 1986-extrapolated data. Using this monetary base, we can now show the model (blue) of the price level (CPI data less food and energy, green):



![](<media/price level uk p.png>)

This is an improvement over the [original result](http://informationtransfereconomics.blogspot.com/2013/08/modeling-uk.html), but still shows a deviation for the current crisis that is not as apparent in the [US model](http://informationtransfereconomics.blogspot.com/2013/09/exit-through-hyperinflation.html). We'll see how this progresses over time. Maybe this is real and deflation will set in in the UK. Inflation is in fact [falling](http://www.bbc.co.uk/news/business-24124705). However this more likely represents residual model error.



What is interesting is that if we plot the path in NGDP-MB space, the information trap rate in the UK seems to be about 3% ([it is 2% in the EU, 1% in Japan and 0.1% in the US](http://informationtransfereconomics.blogspot.com/2013/09/top-ten-successes-of-information.html)):


![](<media/price level uk trap.png>)

The red lines represent constant interest rates, the dashed black line is the information trap criterion (∂P/∂MB = 0) and the actual path (well, extrapolated path) is shown in blue.

**Update 21 January 2017**

Another more recent post with a better model is [here](http://informationtransfereconomics.blogspot.com/2017/01/the-economy-of-united-kingdom.html).
