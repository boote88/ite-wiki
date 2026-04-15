---
title: Smooth move
date: 2014-08-28T17:16:00.002-07:00
updated: 2014-08-28T17:16:37.081-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/08/smooth-move.html
---

Sometimes you make interesting mistakes. I wanted to address [David Beckworth's claim](http://macromarketmusings.blogspot.com/2014/08/about-fed-not-trying-hard-enough-to-hit.html) that the Fed is hitting its inflation target where the evidence consists of looking where the core PCE inflation data is, defining that as the target, and saying therefore the Fed must be on target \[1\]. This involved me switching over from core CPI data to core PCE data. I also made the change from fitting the model to price level data to fitting to inflation data. That's not the interesting part.



In the process I accidentally over-smoothed the money supply and NGDP data (FYI, I normally don't do any smoothing at all) and found a pretty awesome result. This graph reveals, for the first time ever \[2\], trend inflation:


![](<media/inflation smoothed pce.png>)


![](<media/inflation smoothed cpi.png>)

For completeness, here is the PCE price level model fit and the error distribution for PCE inflation:


![](<media/price level smoothed pce.png>)![](<media/inflation smoothed pce -error-.png>)



Of course, these results are based on the monetary base _minus reserves_ (aka currency in circulation, aka "M0"), which means the large scale asset purchases (LSAP) Beckworth claims are influencing core PCE inflation are irrelevant to describing PCE inflation \[2\]. In fact, the information transfer model explains the inflation trend outside even before financial crisis (the ostensible onset of Beckworth's "corridor" of 1-2% core PCE inflation) \[3\].


![](<media/inflation smoothed pce -corridor-.png>)

\[1\] For many market monetarists, the Bayesian prior probability of the model that the central bank can achieve its target is P = 1, therefore whatever inflation is measured to be, that must be the target (or measurement error).



\[2\] Assuming the information transfer model is right :)



\[3\] I am calculating inflation by the instantaneous derivative of the logarithm (the local slope on a log scale), so it's a bit noisier than Beckworth's graph.
