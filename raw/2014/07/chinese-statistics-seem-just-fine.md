---
title: Chinese statistics seem just fine
date: 2014-07-28T18:56:00.000-07:00
updated: 2017-01-14T16:58:18.190-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/07/chinese-statistics-seem-just-fine.html
---

I got a request to run the model for China in an email from Jonathan Prince, so here it is. I half expected to get nonsensical results; the "conventional wisdom" in the US is that Chinese statistics are suspect (see [here](http://blogs.wsj.com/moneybeat/2014/07/27/chinese-data-dont-add-up/) for example). However, after running the model using data from FRED (derived from OECD and IMF data), it turns out that aside from potentially understating inflation in the late 90s/early 2000s, the results for China are largely in line with other countries. Here are the NGDP-M0 and P-M0 plots I've been showing lately with China added:


![](<media/basic chinese price level 1c.png>)![](<media/basic chinese price level 1d.png>)

Here is the actual model fit with parameters (everything below shows model calculations in blue and data in green):


![](<media/basic chinese price level 1a.png>)

You can see the understatement of inflation in 1999-2000. The information transfer index is high, but constant, meaning that the Chinese economy roughly follows something like the quantity theory of money (however the rate of change of the price level is smaller than the rate of change in the money supply, i.e. _log P ~ k log M0_ with _k < 1_):


![](<media/basic chinese price level 1b.png>)

Due to the seasonal effects and the lack of quarterly NGDP data or "core" CPI data, the year over year inflation is a bit noisy, but the model seems to give us something that looks like "core" CPI:


![](<media/basic chinese price level 1e.png>)

Again, inflation seems to be understated in 1999-2000. Overall, China seems like a pretty typical high-growth large economy, like the US in the 1960s.

**Update 14 January 2017**

There might be some issues with the [unemployment rate data](http://informationtransfereconomics.blogspot.com/2015/08/the-chinese-unemployment-rate.html), however.
