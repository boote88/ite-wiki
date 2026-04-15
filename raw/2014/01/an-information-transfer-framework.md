---
title: "An information transfer framework analysis of the US economy, part 1"
date: 2014-01-18T14:19:00.001-08:00
updated: 2014-01-18T14:19:50.658-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/01/an-information-transfer-framework.html
---

I realized that a) I didn't have a really good post to link to for the US model results and b) it's now 2014, so here is an information transfer framework analysis of the US economy updated through Q2 of 2013 (quarterly GDP data from [FRED](http://research.stlouisfed.org/fred2/) haven't been updated with Q3 and Q4 yet). I've put the model equations and fit parameters on the graphs as well along with some notes about phenomenology (monetary offset, sticky wages, liquidity traps). It's broken into three sections: Price level and RGDP growth, Interest rates, and The labor market. I'm going to follow up with Part 2 which is going to be about counterfactuals and the Great Recession.



**Price level and RGDP growth**


We'll start with the price level model _P:NGDP→MB_ \[1\] with [endogenous](http://informationtransfereconomics.blogspot.com/2013/10/exogenous-and-endogenous.html) AD \[2\] and money supply (model in blue and data in green):



![](<media/basic us model 1.png>)

Here is the 3D view in _{MB, NGDP, P}_ space that I find very useful (the information trap criterion _∂P/∂MB = 0_ a.k.a. the "liquidity trap" is shown as a black dotted line):



![](<media/basic us model 3.png>)

Phenomenologically, one has strong monetary offset on the steep part of the surface, but e.g. fiscal policy (ΔG) can move AD more than monetary policy near the _∂P/∂MB = 0_ line if it directly causes changes in _NGDP = C + I + G + X - M_. The price level model does an excellent job with RGDP growth as well (model in blue, data in green):



![](<media/basic us model 1a.png>)



**Interest rates**


The second model in the framework is the interest rate model _r:NGDP→MB_ with **_exogenous_** AD (in contrast to the price level model above). Here is the graph (again, model in blue, data in green):



![](<media/basic us model 2.png>)

One of the main things I am unhappy with right now is the constant _c_ in the interest rate model which does not come from the information transfer framework (we should have _c = 1_); I've done some hand-waving about how _c_ allows us to adjust for interest rate periods (a 3 month rate given as an annual rate vs an annual rate given as an annual rate vs a 10 year rate, etc), but the math doesn't quite work out. I'm still working on it, but the model does really well (including [before the depression](http://informationtransfereconomics.blogspot.com/2013/09/exit-through-hyperinflation.html)) even if we just take it at face value and just say it's motivated by the information transfer framework.



Here are the price level (gray contours) and interest rate (red contours) models combined on the same graph (the actual path of the economy is in blue) that is based on an overhead view of the 3D plot above:



![](<media/basic us model 4.png>)
**The labor market**


And finally there is an information transfer framework model of the [labor market](http://informationtransfereconomics.blogspot.com/2013/08/scott-sumners-model-part-2_30.html) _P:NGDP→L_ where _L_ is the labor supply (total non-farm employees). AD is exogenous. The phenomenon of [sticky wages](http://informationtransfereconomics.blogspot.com/2013/10/sticky-wages.html) is captured in this model (in the sense that the model _P:NGDP→L_ describes the price level better than _P:NGDP→W_ where _W_ is nominal wages). Here is the model calculation of the price level (blue) vs the empirical data:



![](<media/basic us model 5.png>)

Note there is some deviation between the model and the data which is due to wages not being perfectly sticky. Another way to show this information is in a graph of **Okun's law**: the rate of change of the total number of employed is proportional to the rate of change of RGDP (in the information transfer model with perfectly sticky wages, this relationship is exact):



![](<media/basic us model 6.png>)

Note that coupling the labor market and the price level (by fitting the labor market model to the model price level at the top of this post instead of the empirical price level) produces almost identical results (κ = 0.433 instead of 0.428). However we will use this coupled version to look at the counterfactuals in Part 2.





\[1\] The notation _Price:Demand→Supply_ is shorthand an information transfer process where information is transmitted from the _Demand_ (information source) to the _Supply_ (information destination) and the information transfer is detected by the _Price_.



\[2\] Endogenous AD means that κ P ~ MB^(1/κ - 1) rather than κ P ~ NGDP/MB as in the interest rate model.
