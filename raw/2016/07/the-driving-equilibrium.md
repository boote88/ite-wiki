---
title: The driving equilibrium
date: 2016-07-23T13:41:00.000-07:00
updated: 2016-07-23T13:41:02.728-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/07/the-driving-equilibrium.html
---

FRED has [updated the data](https://twitter.com/stlouisfed/status/756930735689400320) on the number of vehicle miles driven, and it looked to me like a perfect candidate for a "growth equilibrium state" analysis using minimum entropy like [I did for unemployment](http://informationtransfereconomics.blogspot.com/2016/06/unemployment-equilibrium.html) (see that post for more details about the process). Here is the original data:



![](<media/driving equilibrium 1.png>)

The growth rate bins (note this is not a log-linear graph, so these are not exponential growth rates, but rather linear growth rates) look something like this:



![](<media/driving equilibrium 4.png>)

The slope that minimizes the entropy is about α = 0.062 Mmi/y ("**dr**" is the data list and "**DR**" is an interpolating function of the data list):



![](<media/driving equilibrium 2a.png>)

And here is the minimized entropy distribution (i.e. the "spikiest" distribution):



![](<media/driving equilibrium 3.png>)

Subtracting that trend and fitting a series of [logistic functions](https://en.wikipedia.org/wiki/Logistic_function) (Fermi-Dirac distributions) to the data gives a pretty good fit:



![](<media/driving equilibrium 5.png>)

The center of the transitions are at 1974.4, 1980.3, and 2009.5 -- corresponding to the three longest recessions between 1971 and 2016. This results in a pretty good "model" of the number of vehicle miles traveled:



![](<media/driving equilibrium 6.png>)
