---
title: "Marking my S&P 500 forecast to market"
date: 2017-09-17T11:15:00.001-07:00
updated: 2017-09-17T11:15:37.430-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/09/marking-my-s-500-forecast-to-market.html
---

Here's an update on how the [S&P 500 forecast](https://informationtransfereconomics.blogspot.com/2017/01/what-about-s-500.html) is doing (progressively zooming out in time):



![](<media/dynamic equilibrium SP500 info eq -forecast with updates-.png>)
![](<media/dynamic equilibrium SP500 info eq -forecast with updates- 2.png>)
![](<media/dynamic equilibrium SP500 info eq -forecast with updates- 3.png>)

Before people say that I'm just validating a log-linear forecast, it helps to understand that the [dynamic equilibrium model](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html) says not just that in the absence of shocks the path of a "price" will be log-linear, but will also have the same log-linear slope before and after those shocks. A general log-linear stochastic projection will have two parameters (a slope and a level) \[1\], the dynamic equilibrium model has one. This is the same as saying the data will have a characteristic "stair-step" appearance \[2\] after a log-linear transformation (taking the log and subtracting a line of constant slope).



**Footnotes:**

\[1\] An ARIMA model will also have a scale that defines the rate of approach to that log-linear projection. More complex versions will also have scales that define the fluctuations.

\[2\] For the S&P 500, it looks like this (steps go up or down, and in fact [exhibit a bit of self-similarity](http://informationtransfereconomics.blogspot.com/2017/07/self-similarity-in-dynamic-equilibrium.html) at different scales):

![](<media/dynamic equilibrium SP500 info eq -forecast with updates- 4.png>)
