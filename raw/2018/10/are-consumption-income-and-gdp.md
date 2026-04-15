---
title: "Are consumption, income, and GDP different measures?"
date: 2018-10-16T16:00:00.000-07:00
updated: 2018-10-16T16:00:01.729-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2018/10/are-consumption-income-and-gdp.html
---

I read [this great blog post by Beatrice Cherrier on macro modeling](https://beatricecherrier.wordpress.com/2018/10/15/working-on-1960s-macroeconometrics-theres-an-echo-on-the-line/), and I plan on having more to say about it in the future. However, there was an example of discourse on modeling consumption and income that made me wonder: What is the relationship between consumption and income? Does income drive consumption? I used the idea [here](https://informationtransfereconomics.blogspot.com/2018/10/building-models.html) — that dynamic information equilibrium models (DIEMs) with comparable shock structure are related — to take a look at Personal Income, Personal Consumption Expenditures, and Nominal GDP (FRED series PI, PCE, and GDP, respectively). But the best I can conclude is that these data series represent the same information, and it is likely the differences are entirely measurement errors (questions of e.g. what is treated as income versus what agents think of as income). It's either that, or there's no fixed relationship — sometimes increased income drives consumption, sometimes increased consumption drives income.



Here are the DIEMs for the three data series — they consist of the demographic shock (increasing labor force participation by women) of the 60s and 70s and the boom-bust-boom-bust cycle of the dot-com and housing bubbles. There is a residual "business cycle" element on top of the demographic shift that I will discuss later. PCE is red, PI is purple, and GDP is turquoise (click to enlarge).



![](<media/consumption and income.png>)

As far as can be gleaned from the data, the demographic shock as well as the 2001 and 2008 recessions are effectively simultaneous ([the "asset bubble era"](https://informationtransfereconomics.blogspot.com/2018/01/24-growth-forever.html)). The dot com asset bubble has income precede consumption and the housing asset bubble has consumption precede income (they both look statistically significant based on the errors estimates of the shock centers). If we look at the residual "business cycle" ([the "Phillips curve era"](https://informationtransfereconomics.blogspot.com/2018/01/24-growth-forever.html)) after extracting the demographic shock, the measures are all over the place in terms of causality (aside from simultaneously falling during recessions):



![](<media/PI and PCE.png>)

The bottom line is that it seems more likely that the various discrepancies could be accounted for by measurement differences than, say, a nonlinear and complex relationship between consumption and income that fails to be measurable at this level of fidelity. True, it's Occam's razor, but the idea that to a good approximation consumption is 68% of NGDP \[1\] and 78% of income seems both useful and reasonable. Especially given the alternative is an armchair behavioral relationship that couldn't be rejected by data for at least another 100 years.





**Footnotes:**


\[1\] Actually, consumption is about 60% of NGDP before the demographic shift and rises to 68% after. [A similar story is told using wages](https://informationtransfereconomics.blogspot.com/2018/06/women-in-workforce-and-labor-share.html).
