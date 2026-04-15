---
title: The economy of the United Kingdom
date: 2017-01-21T21:32:00.000-08:00
updated: 2017-01-21T21:32:40.129-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/01/the-economy-of-united-kingdom.html
---

I thought I'd try a couple of models out on the UK economy.



**I. Dynamic equilibrium and employment**


First, the [dynamic equilibrium unemployment rate model](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-unemployment-rate.html). This turned out reasonably well, but I am confused by a few shocks where I cannot identify a source. Here is the resulting fit:



![](<media/uk unemployment dynamic equilibrium.png>)
![](<media/uk unemployment dynamic equilibrium 2.png>)

The transitions (shocks) are at 1975.3, 1981.2, 1988.8, 1991.4, 1997.3, 2005.9, 2009.0, 2011.4, 2014.3. Most of these line up with shocks to the US or EU (labeled), representing either global recessions, or in the case of 2011.4 the ECB raising interest rates. However this leaves four shocks that are unaccounted for labeled _A_ (1988.8), _B_ (1997.3), _C_ (2005.9), and _D_ (2014.3).



The shock labeled _C_ is the most uncertain, and might correspond to a delayed reaction to the early 2000s stock market bust. It could be left out and chalked up to measurement error or random fluctuations.



The shocks _A_, _B_, and _D_ are all **_positive_** shocks to the UK economy, reducing unemployment. Shock _D_ corresponds to the positive shock in the US associated with the ACA (2014.4). It is not impossible that the subsequent "boom" in the US economy boosted the UK economy but that seems a bit far fetched. Possibly there was some global boom that impacted both the US and UK. Shock _A_ does correspond with a massive spike in RGDP growth (see below). Shock _D_ corresponds to RGDP growth that is high as well ‒ at least high relative to the post-financial crisis norm. If anyone out there has some theories as to what could be happening, let me know in comments.



**II. Quantity theory of labor and capital**


I don't think I went through the "[quantity theory of labor and capital](http://informationtransfereconomics.blogspot.com/2016/03/a-quantity-theory-of-labor-and-capital.html)" for the UK before. The model is basically a modification of the Solow model and gives us functions NGDP = NGDP(L, K) and CPI = CPI(L, K) = dNGDP(L, K)/dL. Here are the 4-parameter (+ 1 normalization factor that drops out of the rates shown below) fits to the data:



![](<media/uk solow macro model 1.png>)
![](<media/uk solow macro model 2.png>)
![](<media/uk solow macro model 3.png>)

I show year-over-year growth rates in order to cut down the seasonal noise. The NGDP growth is a bit low and CPI inflation is a bit high meaning the CPI-deflated RGDP model (blue in the third graph) is significantly below the CPI-deflated RGDP data (yellow). The year of year change of the RGDP data reported in [FRED](https://fred.stlouisfed.org/series/CLVMNACSCAB1GQUK#0) is shown in green. Not bad for almost 50 years of data for two (independent) time series and 4 parameters.



**III. The two together**



Additionally, we can see the rough correspondence between the RGDP growth rate (green data from above) and the employment shocks from the dynamic equilibrium model in the graph below. This isn't necessarily groundbreaking research as it is basically a confirmation of [Okun's law](https://en.wikipedia.org/wiki/Okun's_law).



![](<media/uk unemployment dynamic equilibrium 3.png>)

We end up with a fairly simple information equilibrium model that captures most of the empirical data that has 5 parameters:



_CPI : NGDP ⇄ L_
         _NGDP ⇄ K_
         _U ⇄ CLF_


where _U_ is the total unemployed, _CLF_ is the civilian labor force, _L_ is the number of people employed, and _K_ is the nominal capital stock (from [here](https://fred.stlouisfed.org/series/RKNANPGBA666NRUG)). The five parameters are the IT indices of the three relationships (_α_, _β_, and _k_, respectively with the former two being the Solow exponents) along with two normalization factors (_L₀_, _K₀_).
