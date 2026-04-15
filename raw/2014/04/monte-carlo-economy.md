---
title: Monte Carlo economy
date: 2014-04-03T14:15:00.003-07:00
updated: 2014-04-03T14:15:35.455-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/04/monte-carlo-economy.html
---

I've still been looking into the deviations (for the 1960s and the 1990s) of the actual path of the economy from the Monte Carlo average (see [here](http://informationtransfereconomics.blogspot.com/2014/03/the-monetary-base-as-sand-pile.html) and [here](http://informationtransfereconomics.blogspot.com/2014/03/moar-monte-carlo.html)). Removing the data from the recession in 1960 right at the start of the data fixes the problem - there is a downward jog that starts the integration off in the wrong direction in the simulations at the links.


![](<media/ite numerical diffeq C.png>)

It would make sense not to set the initial conditions for a differential equation in the middle of a shock. However, there still is the issue of the large deviation in the 1990s.
