---
title: The Phillips curve
date: 2013-10-16T19:38:00.000-07:00
updated: 2013-10-16T19:38:01.850-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/10/the-phillips-curve.html
---

Earlier this year [John Quiggin](http://crookedtimber.org/2013/01/05/the-state-of-macroeconomics-it-all-went-wrong-in-1958/) made the bold claim that macroeconomics went wrong in 1958 after the discovery of the [Phillips curve](http://en.wikipedia.org/wiki/Phillips_curve). I've been working over the past couple months trying to figure out how the Phillips curve comes about in the information transfer framework and I basically come to the same conclusion. Here is my bold claim:



**The Phillips curve is real but barely useful regularity in the data that has been completely misinterpreted.**


OK, let's begin. The curve is generally drawn as a downward sloping curve in unemployment rate-inflation rate space. In the information transfer model, this immediately says that the information source is aggregate demand (NGDP), the information destination is the supply of unemployed people (U, e.g. [this metric](http://research.stlouisfed.org/fred2/series/UNEMPLOY) -- and n.b. here and throughout U is the total number of unemployed, not the unemployment rate), and the price level P is detecting signals from the demand to the supply. In my notation, P:NGDP→U. Therefore we can write 






![](<media/phillips 1.png>)

This fit works as well as the fit to the [interest rate in the IS-LM model](http://informationtransfereconomics.blogspot.com/2013/08/the-interest-rate-in-information.html), so it gives some hint that we may be able to extract information from it. One interesting thing to consider is that the price level curve could define a "natural rate" of unemployment (actually more of a mean level of unemployment, blue):



![](<media/phillips 2.png>)

The graph divides the number of unemployed by the size of the civilian labor force (L) to get the unemployment rate. Here is the graph of deviations from the blue curve:



![](<media/phillips 3.png>)




[wikipedia entry](http://en.wikipedia.org/wiki/Phillips_curve)










[new classical form](http://en.wikipedia.org/wiki/Phillips_curve#New_classical_version)











![](<media/phillips p2.png>)
![](<media/phillips p1.png>)

Graphs of the Phillips curve tend to be broken up into "regimes" (from the wikipedia article we have 1955-1971, 1974-1984, 1985-1992 and 2000-2013); we can see how this segmentation approximates the behavior of the parameters $b$ and $\pi^e + \nu$:



![](<media/phillips P.png>)

Basically, the Phillips curve "regimes" represent relatively constant segments of the parameter values. Here are the graphs of the resulting Phillips curves for the different "regimes":



![](<media/phillips curves.png>)

This allows us to posit a reason for the failure to find microfoundations for the Phillips curve. It is a property of the unemployment rate (quick rise, slow fall) that is only marginally connected to inflation (the slow fall in unemployment occurs during a recovery hence during a temporary increase of the inflation rate from a low level brought on by the recession). The real nugget of statistical regularity is that a recession causes unemployment to rise and inflation to fall with the Phillips curve describing the subsequent return to normal (unemployment to fall and inflation to rise). Or another way, the Phillips curve is just mean reversion. And mean reversion doesn't really need microfoundations, does it?



In any case, the Phillips curve is dependent on the dominance of data where $dU/dt &lt; 0$ after recessions.
