---
title: "Dynamic equilibrium: health care CPI"
date: 2020-02-28T20:32:00.001-08:00
updated: 2020-02-28T20:32:06.939-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2020/02/dynamic-equilibrium-health-care-cpi.html
---

Since I've been looking at a lot of health care data recently, I thought I'd run the US [medical care CPI component](https://fred.stlouisfed.org/series/CPIMEDSL) through the [dynamic information equilibrium model](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3094757) (DIEM). It turns out to have roughly the same structure as CPI overall (click to enlarge):



![](<media/DIEM health care costs.png>)

A big difference is that the dynamic equilibrium growth rate is _α_ = 0.035/y, basically a full percentage point above [the rate for all items](https://informationtransfereconomics.blogspot.com/2019/06/cpi-and-diem-inflation-forecasts.html) _α_ = 0.025/y. As it's been basically at play since the 50s (at least), medical prices are now twice what prices as a whole have risen in the same period.



I was curious — was the US an outlier ([lol](https://informationtransfereconomics.blogspot.com/2020/02/leaning-over-backwards-health-care.html))? I ran the model over a bunch of HICP health data from Eurostat (which the UI is at best silly, at worst pathological) for several countries (Sweden, France, the Netherlands, Switzerland, Germany, the UK, Estonia, Italy, Turkey, Denmark, and Spain). This is definitely a graph you have to click to enlarge:


![](<media/DIEM health care costs GRID.png>)

They're all remarkably similar to each other except France, which came out with an equilibrium rate of _α_ \= 0. That could be wrong due to the recent data being in the middle of a non-equilibrium shock — time will tell.



I also compared the dynamic equilibrium to the DIEM model of the CPI (HICP) for all items for each country which produces an interesting plot:


![](<media/DIEM results health care cost findings.png>)

It looks like the US is not much of an outlier on that graph — but that's a bit misleading since the possible inflation rates can't really deviate too much above the diagonal _y_ = _x_ line otherwise headline inflation (i.e. all the components) would rapidly be overtaken by health care price inflation (one of those components). In fact, nearly every time it came out that the health care rate was basically equal to the headline rate. You can see it if we plot the difference versus the headline CPI rate:



![](<media/DIEM results health care cost findings 2.png>)
![](<media/DIEM results health care cost findings 3.png>)

Most of the countries are clustered right around zero, with outliers being the US and France. France is an outlier because its health care price inflation [has been basically zero for the past decade](https://fred.stlouisfed.org/series/CP0600FRM086NEST) meaning the difference graphed above is essentially the negative of the inflation rate of about 2%. The US is an outlier in the other direction — by 4 standard deviations if we leave out France and the US in the estimate of the distribution.



If this is correct, the US health care prices rise at nearly a percentage point faster than prices overall, meaning prices are nearly 30% higher today from growth over the period from 1996-2020 (the Eurostat data range) than they would be if those prices grew like any other country's. And these are _**prices**_ — not income, profits, or consumption.




**Appendix**


Here are all the individual graphs. The dashed lines are lines at the dynamic equilibrium rate, but in some of the graphs they appear well off the lines — that's because in some of the cases the different levels add the shocks in different ways (e.g. the 2nd shock is positive but the 3rd shock is negative) so they add or subtract differently for each country. Couple that with the fact that I determine the sign of a shock in the parameter estimation by the sign of the width, not the amplitude but instead of using that sign I set it by hand for the dashed line guides, and well, you see the result — random dashed lines appearing across the graphs (albeit with the right slope). Anyway, click to enlarge.



![](<media/DIEM health care costs -compare denmark-.png>)![](<media/DIEM health care costs -compare Estonia-.png>)

![](<media/DIEM health care costs -compare france-.png>)![](<media/DIEM health care costs -compare Germany-.png>)

![](<media/DIEM health care costs -compare Italy-.png>)![](<media/DIEM health care costs -compare Netherlands-.png>)

![](<media/DIEM health care costs -compare Spain-.png>)![](<media/DIEM health care costs -compare sweden-.png>)

![](<media/DIEM health care costs -compare Switzerland-.png>)![](<media/DIEM health care costs -compare Turkey-.png>)

![](<media/DIEM health care costs -compare UK-.png>)
