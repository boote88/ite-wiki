---
title: Deriving the price level from NGDP and the monetary base
date: 2013-06-28T10:18:00.001-07:00
updated: 2013-06-28T10:18:30.525-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/06/deriving-price-level-from-ngdp-and.html
---

I'm not sure which way solving the system of equations would give the biggest bang for the buck for an economist. As a physicist, you would want to compare against the most direct measurement. In our case, a physicist would want to solve for the monetary base like the [previous entry](http://informationtransfereconomics.blogspot.com/2013/06/this-is-getting-interesting-monetary.html) -- it used NGDP (which uses a statistical model) and the price level (another statistical model) and solved for the monetary base (supposedly directly measured by the Fed) and the information transfer index (a variable fixed by the model I'm using). This entry does a similar thing, but solves for the price level/inflation rate and the information transfer index given NGDP and the monetary base. Determining the price level seems to be of value to at least one economist, e.g. [here](http://www.themoneyillusion.com/?p=915). (Actually, there is an overall normalization to the price level that is the free parameter here, set to 374.65 \[billion $\]; much like in [renormalization](http://informationtransfereconomics.blogspot.com/2013/05/rescaling-and-inflation.html).)



Anyway, using the system of equations [here](http://informationtransfereconomics.blogspot.com/2013/06/this-is-getting-interesting-monetary.html), I set the demand to NGDP and supply to the (seasonally adjusted) St Louis adjusted monetary base (both from [FRED](http://research.stlouisfed.org/fred2/)) and solved for the price level and the information transfer index. I compared these to the CPI less food and energy (also from FRED). The derivative of the price level and CPI are the measurement of the inflation rate. I also show the smoothed inflation rate. Again, the inflation rate seems to do worst at moments when monetary policy is noteworthy: the  Volcker disinflation and the Bernanke quantitative easing.



In order, the graphs are the price level, the inflation rate 1960-2008, the smoothed inflation rate 1960-2008, the inflation rate 1960-2012 and the information transfer index. Model calculations are in blue, the empirical data is in gray.

![](<media/information transfer index price level 1.png>)
![](<media/information transfer index price level 2.png>)![](<media/information transfer index price level 2a.png>)![](<media/information transfer index price level 3.png>)![](<media/information transfer index price level 4.png>)
