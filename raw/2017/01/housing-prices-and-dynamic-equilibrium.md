---
title: Housing prices and dynamic equilibrium
date: 2017-01-31T16:30:00.000-08:00
updated: 2017-01-31T16:30:13.655-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/01/housing-prices-and-dynamic-equilibrium.html
---

I apologize if the [dynamic equilibrium](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html) \[1\] posts are getting monotonous, but as the blog's primary purpose is as a "working paper" (one that is now apparently a few hundred pages long) I must continue!



The latest [Case-Shiller price index data](https://fred.stlouisfed.org/series/CSUSHPISA) was released earlier today showing a continued rise in housing prices. In looking at the data, I noticed it has the telltale signs of a a dynamic equilibrium in the presence of shocks. However as the previous derivation looked at ratios of quantities in information equilibrium, I thought I needed to expand the theory a bit.



If we have housing demand $H_{d}$ in information equilibrium with housing supply $H_{s}$ with abstract price $P$ (i.e. $P : H_{d} \rightleftarrows H_{s}$), we can say:






We can solve the differential equation to obtain






Now if housing supply grows at some rate $r$ such that $H_{s} \sim e^{rt}$, then






Note that this is basically identical to the result for the ratios of quantities in information equilibrium in \[1\]. This should be apparent because the RHS of the first equation above is such a ratio and the LHS is the abstract price. Now let's use our procedure in \[1\] and say that the Case-Shiller index is our abstract price. The results are pretty decent:



![](<media/cas shiller dynamic equilibrium 1.png>)
![](<media/cas shiller dynamic equilibrium 2.png>)

The vertical lines again represent the centroids of the shocks. The negative shocks are at 1982.5, 1993.1, and 2007.7 (each associated with recessions). The positive shocks are at 1978.5 and 2005.6 (likely the California housing bubble and the global housing bubble, respectively).






PS I did want to note that we get increased prices with increased supply per the equations above. That is because we are assuming equilibrium (general equilibrium). If the housing supply increased _quickly_ relative to housing demand, then we would get the standard economics 101 result. I discussed this more extensively [here](http://informationtransfereconomics.blogspot.com/2016/04/affordable-housing-through-increased.html).
