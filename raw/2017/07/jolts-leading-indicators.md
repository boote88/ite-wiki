---
title: "JOLTS leading indicators?"
date: 2017-07-12T14:30:00.000-07:00
updated: 2017-07-12T14:30:06.352-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/07/jolts-leading-indicators.html
---

In what is becoming a mini-series on the utility of the forecasts made using the information equilibrium/[dynamic equilibrium](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html) framework ([previous installment here](http://informationtransfereconomics.blogspot.com/2017/07/does-information-equilibrium-add.html)), I wanted to assess whether the Job Openings and Labor Turnover survey (JOLTS) data could be used as leading indicators of a potential recession (I looked at the various measures [previously here](http://informationtransfereconomics.blogspot.com/2017/06/jolts-and-narratives.html)).



The latest data for job openings seems to be showing the beginnings of a correlated negative deviation that could be the start of a downturn:


![](<media/simple dynamic equilibrium test -hires quits openings- DATA UPDATES.png>)

The other indicators were more mixed, so I asked myself: does one measure show a recession earlier than the others? A note before we start -- this analysis is based on a sample of one recession (JOLTS only goes back to the early 2000s), so we should take it with a bit more than a grain of salt.



I looked at the estimate of the center of the 2008 recession transition for hires rate (HIR), job openings rate (JOR), quits rate (QUR), and the unemployment rate (UNR):


![](<media/jolts which first.png>)

The errors shown are 2 standard deviations, and the months on the x-axis are the months that the data points are for (the data usually becomes after another month or so, e.g. May 2017 data was released 11 July 2017). We can see that hires leads the pack -- i.e. the center of the hires transition precedes the other measures.



Note this is not the same thing as figuring out when a transition becomes detectable. I looked at this using unemployment rate data [back in April](http://informationtransfereconomics.blogspot.com/2017/04/determining-recessions-with-algorithm.html). Two factors enter into the detectability: the width of the transition and the relative measurement noise level. While most of the data has comparable widths:


![](<media/jolts which first 2.png>)

(the error bars show the parameter that determines the width of the transition), the hires data has more relative noise than the unemployment rate (think signal-to-noise ratio). This could potentially make the hires data less useful as an early detector of a recession despite being the leading observable.



With those caveats out of the way, it is possible the hires data might show the beginnings of a recession a several months in advance of the unemployment rate. Like the job openings, it is also showing a negative deviation:


![](<media/dynamic equilibrium 2 -jolts hires-.png>)

However the most recent data lends support the null hypothesis of no deviation. Regardless, I will continue to monitor this.
