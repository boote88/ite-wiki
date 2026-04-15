---
title: Principal component analysis of jobs data
date: 2017-03-15T13:30:00.000-07:00
updated: 2017-03-16T12:54:32.375-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/03/principal-component-analysis-of-jobs.html
---

Narayana Kocherlakota [tweeted](https://twitter.com/kocherlakota009/status/841975558594564096) about employment making a random claim about the "steady state" employment growth that seems to come from nowhere which inspired me to do something I've been meaning to do for awhile: a principal component analysis of the Job Openings and Labor Turnover time series data ('[JOLTS](http://informationtransfereconomics.blogspot.com/2017/01/a-dynamic-equilibrium-in-jolts-data.html)'):



![](<media/PCA and hiring data 1.png>)

I used a pretty basic [Karhunen–Loève](https://en.wikipedia.org/wiki/Karhunen%E2%80%93Lo%C3%A8ve_theorem) decomposition (_Mathematica_ function [here](https://reference.wolfram.com/language/ref/KarhunenLoeveDecomposition.html)) on several seasonally adjusted hires time series from FRED (e.g. [here](https://fred.stlouisfed.org/series/JTS6200HIL)). For those interested (apparently no one, but alas I'll do it anyway) the source code can be found in the [Dynamic Equilibrium GitHub repository](http://informationtransfereconomics.blogspot.com/2017/02/information-equilibrium-code.html) I set up. Here's the result (after normalizing the data):



![](<media/PCA and hiring data 2.png>)![](<media/PCA and hiring data 3.png>)

The major components are the blue and yellow one (the rest are mostly noise, constant over time). I called these two components the "cyclical" (blue) and the "growth/decline" (yellow) for fairly obvious reasons (the growth/decline is strongest after 2011). It's growth or decline because the component can be added with a positive (growth) or negative (decline) coefficient. Here are how those two components match up with the original basis:



![](<media/PCA and hiring data 4.png>)
![](<media/PCA and hiring data 5.png>)

The story these components tell is consistent with the common narrative and some conventional wisdom:



-   Health care and education are not very cyclical
-   Health care and education are growing 
-   Manufacturing and construction are declining  



Here's health care on its own (which looks pretty much like the growth/decline component):


![](<media/PCA and hiring data health.png>)


![](<media/PCA and hiring data manuf.png>)

To get back to Kocherlakota's claim, the "steady state" of jobs growth then might seem to depend on the exact mix of industries (because some are growing and some are declining) and where you are in the business cycle. However, [as I showed back in January](http://informationtransfereconomics.blogspot.com/2017/01/matching-theory-and-employment-in.html), total hires can be described by constant relative growth compared to the unemployment level and the number of vacancies ‒ except during a recession. This is all to say: _it's complicated_ \[1\]. 



PS Here are all of the components ([here's a link](https://drive.google.com/file/d/0B6qAxdK1gOgwNFFYNkoyRlBhemM/view?usp=sharing) to my Google Drive which shows a higher quality picture):


![](<media/PCA and hiring data.png>)


**Update 16 March 2017**

[standardized](http://reference.wolfram.com/language/ref/Standardized.html)[algorithm](http://reference.wolfram.com/language/ref/KarhunenLoeveDecomposition.html)

![](<media/PCA and hiring data a.png>)![](<media/PCA and hiring data b.png>)


![](<media/PCA and hiring data new 1.png>)
![](<media/PCA and hiring data new 2.png>)


![](<media/PCA and hiring data 0.png>)


**Footnotes:**


\[1\] Although I'm still not sure where the 1.2 million jobs per year comes from; here's the employment change year over year:

![](<media/payems data.png>)

The bottom line is Kocherlakota's 1.2 million figure. The second from the bottom is the 1.48 million rate that comes from averaging the growth rate including recessions (it's almost 1.6 million for just post 1960 data). The upper line is my "guesstimate" for the average excluding recessions (2.5 million). Maybe it was a typo and he meant 2.2 million.
