---
title: All your BASE
date: 2013-07-29T18:25:00.000-07:00
updated: 2013-07-29T18:25:54.648-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/07/all-your-base.html
---

There are several measures of the so-called money supply. Which measure is the "correct" measure is a matter of debate and seems to depend on the effect you are trying to model (which seems like a terrible way to do things, but as I am about to make a case for one measure in particular base on an effect I am trying to model that probably comes across as a bit hypocritical). Here are a few that the Fed still publishes:

![](<media/different kinds of base.png>)

M1 (currency and checking deposits, dark blue), M2 (M1 and close substitutes, orange), Money with zero maturity (MZM, red), the St. Louis Adjusted Monetary Base (AMB, light blue) are shown in the graph. Originally I did most of my work with AMB because it was available on FRED, went back to 1917 and seemed to look like the graph that most people put up when complaining about the money supply.



I subsequently did some calculations with other countries; however, FRED seems only to have M1 for other countries. I thought this might suffice as a proxy since M1 and AMB are roughly the same order of magnitude. M1 includes money created by fractional reserve banking (i.e. your checking account) but doesn't include deposits/credit with the Fed itself. In the information transfer model (ITM) we are concerned with money acting as a unit of measurement which means that AMB is probably the best measure because that is the source (base) from which all other money comes from. It also happens to work better at measuring the price level (on the left is the best fit to the CPI, on the right is the fractional difference from the CPI):

![](<media/different kinds of base FITS.png>)![](<media/different kinds of base DIFF.png>)

Mostly bad fits with AMB winning out, but the same "secular trend" as they say in economics. However, if we look at the model results in the [normalized sigma-kappa space](http://informationtransfereconomics.blogspot.com/2013/07/universalizing-model-kappa-sigma-space.html), we get very different stories:

![](<media/different kinds of base sigma kappa.png>)

The question of whether the US have crossed the ridge into the region where expansion of the money supply is contractionary (and thus the US is like Japan, at least in the ITM) depends on which measure you use. For M1 and the AMB the US was relatively near the ideal quantity theory of money (kappa = 1/2) and has drifted away relatively slowly. For M2 and MZM, there is a rapid divergence. Additionally if you use AMB, there aren't large fluctuations in the price level that exist for other measures. It is interesting to note that Japan is on the other side of the ridge [regardless if you use the MB or M1](http://informationtransfereconomics.blogspot.com/2013/07/all-your-m1.html). I haven't done the calculation, but it seems that if you were to use M1, then there would be fewer countries near kappa = 1/2 and so the quantity theory [would not work as well as it does](http://informationtransfereconomics.blogspot.com/2013/06/which-is-failing-itm-or-qtm.html). In the data from the previous link, you can see Indonesia and Mexico are already far from kappa = 1/2.
