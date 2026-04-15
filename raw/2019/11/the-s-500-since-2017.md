---
title: "The S&P 500 since 2017"
date: 2019-11-23T16:42:00.004-08:00
updated: 2019-11-23T16:42:35.180-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2019/11/the-s-500-since-2017.html
---

One of the forecasts I made when I first worked out the theory behind the [dynamic information equilibrium model](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3094757) (DIEM) besides the unemployment rate [was for the S&P 500](https://informationtransfereconomics.blogspot.com/2017/01/what-about-s-500.html). This forecast has worked out remarkably well — though one might ask how could it not with error bands on the order of 20%? I changed the color scheme a bit since the original forecast, but here's where we are (note that it's a log plot):



![](<media/dynamic equilibrium SP500 info eq -more shocks- static data from shiller 2.png>)

The black line is post-forecast data. The vertical blue bands are NBER recessions. The vertical red/pink bands are the non-equilibrium shocks to the S&P 500. The green error bands are the 90% confidence bands for the entire data series since the 1950s and the blue error band over the forecast data was the 90% confidence projection from estimating an AR process on the deviations from the dynamic equilibrium starting from the forecast date. That AR process was trained on the data since 2010.



The AR process error gets fairly close to the error bands for the whole series. My interpretation of this is that the AR process model has captured pretty much nearly the entire range of error except for recessions — that is to say the data from 2010 to 2017 gave us a decent estimate of non-recessionary deviations from the dynamic equilibrium due to news shocks, policy, foreign affairs, _et cetera_.



I think the past couple years has given us some additional evidence that hypothesis is correct as the current administration has effectively conducted some "natural experiments". I estimated a couple of non-equilibrium shocks to the post-forecast data — we can zoom in to see them better:


![](<media/dynamic equilibrium SP500 info eq -more shocks- static data from shiller.png>)

The first shock is a positive one taking place at the end of 2017 and the beginning of 2018 — almost certainly due to the TCJA (which incidentally [appears to have had other effects](https://informationtransfereconomics.blogspot.com/2019/05/tcja-and-pce-growth.html)). If that had been the only thing that happened since 2017, everyone with a 401(k) account invested in an S&P index fund (full disclosure: that's what I do) would have had 17% more in it today even without contributions.



Instead of being around 3650, we're closer to 3100 today. Why? It appears to be due to the "trade war" with China. The major announcements are shown with black arrows (**↑**). The first round of tariffs began before the ink on the TCJA had dried (green arrow) and basically cut what was estimated to be a sizable 20% gain back to **_zero_**. A second round of tariffs comes in August and September of 2018, accompanied by a subsequent shock.



The Fed's rate increase in December 2018 did produce a rapid drop in the S&P 500, but the effect seems to have since evaporated. I estimated the tariff shock with and without the data from from December 2018 and January 2019 and got nearly the exact same result in terms of the longer run level in both cases. It's of course not impossible that the effect of tariffs is what evaporated and what we're seeing is purely the effect of the Fed — but this is inconsistent with a) the fact that the tariffs seem to have had a lasting effect in 2018 and b) the December 2015 rate increase also largely evaporated \[1\].



So it seems that mismanagement of government policy does have sizable & quantifiable effects on the stock market. However, the key conclusion here is that these policy decisions appear to be within the range of the overall 20% error since the 1950s — and that policy changes are basically a 2nd order effect on the stock market after recessions with deviations on the order of δ log SP500 ~ 0.1 with recessions having an effect δ log SP500 ~ 0.6-0.8 or more \[2\].




**Footnotes:**


\[1\] The December 2015 rate increase was a shock on the order of δ log SP500 ~ 0.15, but in less than a quarter was only δ log SP500 ~ 0.05 and consistent with zero by 2017. The December 2018 rate increase has almost exactly the same structure: an initial drop by δ log SP500 ~ 0.15 and a quarter later the level was back up to within δ log SP500 ~ 0.05 of the pre-hike level.



![](<media/delta sp500 1.png>)![](<media/delta sp500 2.png>)

\[2\] And per \[1\], Fed decisions having an effect on the order of δ log SP500 ~ 0.15 that quickly evaporate over the next quarter.
