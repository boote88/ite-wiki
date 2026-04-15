---
title: The interest rate in the information transfer model
date: 2013-08-25T22:54:00.000-07:00
updated: 2013-08-26T00:56:11.455-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/08/the-interest-rate-in-information.html
---

This post is a first step towards integrating the information transfer versions of the [IS-LM model](http://informationtransfereconomics.blogspot.com/2013/08/deriving-is-lm-model-from-information.html) and the [quantity theory](http://informationtransfereconomics.blogspot.com/2013/07/dotting-is-and-crossing-ts.html). We'll begin with one of the basic equations from the [information transfer framework](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html):



$$
P = \frac{1}{\kappa}\frac{Q^d}{Q^s}
$$



In the [LM market](http://informationtransfereconomics.blogspot.com/2013/08/deriving-is-lm-model-from-information.html), we have aggregate demand represented by $NGDP$ as an information source sending information to the money supply (the monetary base, $MB$) with the interest rate as the price (the detector that detects the signal transmitted from the demand to the supply). We'll write this price $P \rightarrow r$ as



$$ c \log r&nbsp;= \log \frac{1}{\kappa}\frac{NGDP}{MB}
$$



With $c$ being an arbitrary constant. If I fit this equation to the [Effective Fed Funds](http://research.stlouisfed.org/fred2/series/FEDFUNDS) rate, I get a very good fit (model is blue, data is green):



![](<media/combining islm and the quantity theory.png>)



The fit parameters are $1/\kappa = 39.1$ and an overall normalization of $c = 0.279$ (assuming of course that the fed funds rate is divided by 100 to change from a percentage into a dimensionless number).



An interesting way to visualize this data is to plot the interest rate versus real GDP (aka real output, denoted $Y$ in the ISLM model). With the information transfer model providing both the interest rate (above) and RGDP derived from $NGDP$ and the price level in the [quantity theory](http://informationtransfereconomics.blogspot.com/2013/07/dotting-is-and-crossing-ts.html), we can observe "LM curves" in the data where increasing $Y$ traces out an upward sloping curve with the interest rate.



![](<media/combining islm and the quantity theory 2.png>)



It appears as though the LM curves are "reset" by the Fed lowering interest rates to "heat" the economy (by increasing the monetary base via the equation above). There was a period of relative constant interest rates (dashed red line) from the mid-90s to the early 2000s (the late 90s "tech boom") where the economy grew with limited intervention from the Fed. That last statement would probably send Scott Sumner up the wall. The Fed is always intervening, but in this case by limited intervention I mean keeping the monetary base growing roughly at the same rate as NGDP. This keeps interest rates constant via the equation above.



In 2008 we see the data bump up against the zero lower bound. The LM market stops sending information detectable by the interest rate. Here we would obtain the "flat" LM curve of the liquidity trap. This is different from the constant interest rate of the late 1990s, which is the LM market equilibrium moving along at roughly a constant interest rate as $Y$ increases until 2001.



It appears there is a qualitative change in the properties of the LM market that begin in the early 1990s -- interestingly the first recession with Alan Greenspan as Fed chair. For some reason, no LM curve appears after the recession ends. Could raising interest rates in the late 1990s have helped us avoid the Great Recession later on by leaving interest rates high enough to avoid the zero lower bound?



Should proper macroeconomic stabilization produce a picture that looks (heuristically) like this:



![](<media/combining islm and the quantity theory 3.png>)



And do the 90s look like a massive failure in retrospect?



The next step (next post maybe?) is to see if using the real interest rate (related via the Fisher equation to the nominal rate) shows any significant difference in qualitative behavior.
