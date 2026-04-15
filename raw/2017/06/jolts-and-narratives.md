---
title: JOLTS and narratives
date: 2017-06-09T14:45:00.005-07:00
updated: 2017-06-09T14:45:30.021-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/06/jolts-and-narratives.html
---

The latest [JOLTS data came out](https://fred.stlouisfed.org/categories/32241) this past week, and I've previously [looked at the data with the dynamic equilibrium model](http://informationtransfereconomics.blogspot.com/2017/01/a-dynamic-equilibrium-in-jolts-data.html) (in fact, that analysis led [to my current understanding](http://informationtransfereconomics.blogspot.com/2017/04/a-tour-of-information-equilibrium.html)). However, I saw [Nick Bunker's charts on the Equitablog](http://equitablegrowth.org/equitablog/jolts-day-graphs-april-2017-report-edition/) where we see the problem that frequently pops up in economics where trends in data are ascribed to particular narratives that aren't supported by the data. These narratives might be consistent with the data, but are the scientific equivalent of saying unemployment is falling because the economy is becoming more [awesome](http://informationtransfereconomics.blogspot.com/2015/06/everything-is-awesome.html).



In the charts, Bunker claims:



-   _Fewer unemployed workers per job opening shifts bargaining power to employees_
-   _When workers are more confident about the labor market, they quit more_
-   _As the US labor market tightens, job openings yield fewer hires_

The last one is tautological ‒ what does it mean for a labor market to tighten besides fewer hires per job opening? The other two are behavioral relationships: humans are deciding to quit at a higher rate than they would otherwise or e.g. negotiating higher salaries than they would otherwise.





I went through and tried some dynamic equilibrium models for the relevant JOLTS data series (quits, hires, openings, total separations, unemployment) and uploaded the _Mathematica_ code [to the dynamic equilibrium GitHub repository](http://informationtransfereconomics.blogspot.com/2017/02/information-equilibrium-code.html). The story told by these models is that not much new is really happening. We're in the same post-shock dynamic equilibrium we've been in since 2010 and nothing has changed. People are still quitting at the same increasing rate they were between the 2000 and 2008 recessions (the quit rate increases by few 10ths of a percentage point per year):


![](<media/simple dynamic equilibrium test -hires quits openings- GRAPH 2.png>)

Hires are also increasing, as are openings and separations:



![](<media/simple dynamic equilibrium test -hires quits openings- GRAPH 0.png>)
![](<media/simple dynamic equilibrium test -hires quits openings- GRAPH 1.png>)
![](<media/simple dynamic equilibrium test -hires quits openings- GRAPH 3.png>)

In fact, the unemployment rate shows the same basic structure except inverted (and this model correctly forecasts the unemployment rate from the beginning of 2016 shown in black):



![](<media/usa unemployment dynamic equilibrium -data updates-.png>)

As a scientist, I look at this data and conclude there is probably a single underlying process governing it all. The dynamic equilibrium model is the incredibly simplistic view that the underlying process is a constant log-linear increase in population interrupted by occasional shocks (recessions). If population grows as ~ exp(_r_ × _t_), then the hire rate, job opening rate, unemployment rate, and quit rate [all grow (or shrink) at some (relative) rate](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html) ~ (_k_ − 1) × _r_ (interrupted by occasional shocks) with different (constant) values of _k_ for each time series. That is to say nothing really happens except recessions and population growth. Workers are quitting via the same process they quit at any other time besides 2008-2009. They aren't more confident. You could actually say that as the economy increases in size more jobs become available meaning it just becomes more likely that someone changes jobs at random (to use [the maximum entropy narrative underlying](http://informationtransfereconomics.blogspot.com/2016/02/slides.html) the information equilibrium/dynamic equilibrium model). You can make this connection [more explicit with a matching model](http://informationtransfereconomics.blogspot.com/2017/01/matching-theory-and-employment-in.html).



This is not to say there aren't behavioral effects or other economic effects due to other mechanisms. Tightening of labor markets [might well lead to a (second order) effect on PCE inflation](http://informationtransfereconomics.blogspot.com/2017/04/can-we-see-phillips-curve.html) because of increased bargaining power (or employers increasing wages offered in order to simply find/hire scarce employees). In the dynamic equilibrium picture, inflation in the post war period is explained mostly be women entering the workforce (first order), accompanied by 'Phillips curve'-like effect between recessions (second order, and stronger at higher inflation [consistent with the flattening of the Phillips curve](http://informationtransfereconomics.blogspot.com/2016/01/the-slope-of-phillips-curve-is-roughly.html)).



Aside from a bit of "isn't the information equilibrium model awesome", what I am saying is that we should be careful about the narratives created around economic data. Plausible stories are not evidence, and there could be equally good (or better, or more empirically accurate, or simpler) explanations that tell a different story. Or, as in the case of information equilibrium, no story at all.
