---
title: Extracting nominal shocks
date: 2013-07-26T18:31:00.000-07:00
updated: 2013-07-26T18:31:26.516-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/07/extracting-nominal-shocks.html
---

In this post I will extract "nominal shocks". I mean this in a very generalized way. If we take the diagram from [this post](http://informationtransfereconomics.blogspot.com/2013/07/fiscal-and-monetary-stimulus.html), we can see the effect of what small changes to the monetary base or NGDP look like. Each of the arrows represents a pure increase in NGDP (blue arrow) or a pure increase in the base (red arrow) both of the same (fractional) size. The empirical path is shown in light blue.

![](<media/response to mp and fp -along track-.png>)

If we zoom in on some of the years shown, we can see some details and come up with a way to extract "shocks", i.e. the difference from where we are expected to be vs where we actually are. Here are some zooms for 1970, 1980, 1990 as well as 2000 and 2010 in the same graph.

![](<media/response to mp and fp -along track- 1980.png>)![](<media/response to mp and fp -along track- 2000.png>)

If we look at 1970 and 1990, the empirical path appears to follow the monetary arrow. We ended up where we expected if there was no change in NGDP except due to changes in the monetary base. It is tempting to refer to this situation as a lack of real growth, i.e. NGDP growth = inflation rate. However, this is not the case. Since the information transfer index is > 1/2 (we are not near the QTM line), the price level growth rate is not equal to the monetary base growth rate -- in fact the inflation rate is only about ~ 30%  post 1980 (using the long run limit of 1.31 from [this calculation](http://informationtransfereconomics.blogspot.com/2013/07/recovering-quantity-theory-from.html)) of the monetary base growth rate. For every three dollars created by the Fed/Treasury in 1990, only about one was eaten up by inflation. The remaining two became new wealth. In the 1970s, this was a somewhat smaller amount (using an information transfer index of 0.6, two dollars would be eaten up, leaving one for new wealth). 



If we look at 1980, 2000 and 2010, we see that we ended up somewhere different than expected by the red arrow. I will refer to this as a nominal shock -- basically we ended up at some different NGDP than expected by MB growth alone. My procedure to extract these nominal shocks will be to calculate where the change in the monetary from e.g. 1970 to 1971 takes you in MB-NGDP space (along a red arrow that will have a different length based on the change in the MB) and then see what delta-NGDP (nominal shock) will bring from the expected point to the empirical point.



Note that there is still an ambiguity in terms of resolving these differences from the expected path in terms of, say, AD and AS shocks (the coordinate system is not orthogonal, except at a subset of points). Therefore I will just refer to the difference between the real and expected point as a "nominal shock", which can be both positive (say, an uptick in productivity) and negative (say, a sudden increase in perceived risk).



I will also note that the definition of AS I've been using in the model (money supply) differs from what is typically thought of as AS (the total supply of goods in an economy) and is closer to the LM curve of the IS-LM model. This further motivates why I am just referring to these differences as nominal shocks.



On to the nominal shocks!



Here is the plot of the nominal shocks by year from 1960 to 2012 (in blue). 

![](<media/price level best fit -extract shocks 1-.png>)

The dashed red line is the Federal deficit. Why did I put that there? Well,  NGDP = C + I + G + NX. To first order, then, deficit spending by the government simply creates NGDP. Now there are two arguments made against that bold claim. The first is [Ricardian Equivalence](http://en.wikipedia.org/wiki/Ricardian_equivalence). If the government engages in deficit spending, C and I pull back immediately in anticipation of future taxes to cover G. The second is [crowding out](https://en.wikipedia.org/wiki/Crowding_out_%28economics%29). If the government engages in large scale borrowing, it drives up interest rates reducing I. 



I have two responses to this. First, it is unlikely that C or I will respond to exactly cancel the deficit spending (it is _**by definition**_ a second order effect, responding to perturbations of G relative to the total NGDP and the first order effect must be larger or else the whole thing is [non-perturbative](http://en.wikipedia.org/wiki/Non-perturbative) and we can all just go home right now). Second, I think it is interesting to figure out what the shocks are if we can take out one contribution we already know -- the crowding out (and Ricardian equivalence) will remain as a negative contribution to the nominal shock after the deficit spending has been removed. The remainder is then = crowding out + Ricardian equivalence + productivity changes + technology changes + random noise + ... whatever else.



Therefore, here are the results (nominal shocks in blue, nominal shocks minus the federal deficit for the following year in dashed dark blue).

![](<media/price level best fit -extract shocks 2-.png>)

In case there is any quibble with taking the deficit number for the following year (the deficit number is the realized deficit from the prior year, so that makes sense to me) here is what it looks like if you take +/- 1 year.

![](<media/price level best fit -extract shocks 3-.png>)

Anything to take away form this? Well, it's a small data set so probably not. But here goes some unwarranted speculation and random facts.

-   Before 1980 the recessions appear to precede large positive shocks whereas after 1980 the recessions seem to follow large negative shocks.
-   The Great Recession appears to have resulted from a negative shock on the order of 15% of GDP (the observed NGDP change was on the order of 5% of GDP). The Great Depression had an observed NGDP change on the order of 30%.
-   I would like to stress that the >10% of GDP nominal shock is what is left over after taking into account monetary policy, i.e. we were >10% below where we would expect to be if all change in NGDP was due to a change in the price level alone due to increasing the base.
