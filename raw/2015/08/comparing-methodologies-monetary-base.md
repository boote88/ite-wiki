---
title: Comparing methodologies (monetary base and short term interest rates)
date: 2015-08-09T18:34:00.004-07:00
updated: 2015-08-09T18:34:20.951-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/08/comparing-methodologies-monetary-base.html
---

[mentioned here](http://informationtransfereconomics.blogspot.com/2015/08/granger-causality-is-information.html)

> _... if a time series model’s results are reported without routine references their statistical significance, then they should always be viewed with deep skepticism. ..._

> _... an argument consisting of little more than a line graph depicting the time series of values of a quantity should never be accepted as a proof of anything, except that the person who is arguing that it proves something is not familiar with what constitutes acceptable empirical evidence, is incapable of understanding what constitutes acceptable empirical evidence, or is simply willfully ignoring what constitutes acceptable empirical evidence because it contradicts their preferred model._

Almost zero theoretical physics papers pay attention to statistical significance in this way. Obviously physics is "doing it wrong" and that's why the field is in a state of existential methodological crisis. Oh, wait. That's economics.



Personally, I'd say any statistical results presented without reference to an explicit model means that an implicit model has been used -- and you treat any implicit results with deep skepticism.



[Paul Krugman](http://krugman.blogs.nytimes.com/2014/10/14/the-state-of-macro-six-years-later/)

> _Any time you make any kind of causal statement about economics, you are at least implicitly using a model of how the economy works. And when you refuse to be explicit about that model, you almost always end up – whether you know it or not – de facto using models that are much more simplistic than the crossing curves or whatever your intellectual opponents are using._

Here's an example where you can see this at work ... first setting up the data



![](<media/granger causality -sadowski- single lag 1.png>)

The next bit looks for the best single lag to compare the first differences of the two time series (in both directions) ...



![](<media/granger causality -sadowski- single lag 2.png>)
This is a basic fit with a single lag ...

![](<media/granger causality -sadowski- single lag 3.png>)

It works pretty well for an economic model (changes short term interest rates cause changes in the monetary base: rates go down, base goes up ...)



![](<media/granger causality -sadowski- single lag 4.png>)

How about the same thing but looking at levels? Well the traditional stats test is going to be garbage because of spurious correlation ... but the model looks much better than the statistically "proper" version ...



![](<media/granger causality -sadowski- single lag 5.png>)
![](<media/granger causality -sadowski- single lag 6.png>)
Does a slavish devotion to statistical purity lead us away from real understanding?
