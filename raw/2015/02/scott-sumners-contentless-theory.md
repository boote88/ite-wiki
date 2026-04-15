---
title: "Scott Sumner's contentless theory"
date: 2015-02-04T23:10:00.000-08:00
updated: 2015-02-04T23:10:38.544-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/02/scott-sumners-contentless-theory.html
---

Scott Sumner placed an update at the bottom of [this post](http://www.themoneyillusion.com/?p=28567) with an HP filtered version of his nominal hourly wages theory from a commenter named Rob. Basically it plots the relative fluctuations of _(W/H)/(NGDP/L)_ around the chosen HP filtered trend and shows that they are the same as the unemployment rate _u_. Sumner writes "W" instead of _W/H_, but Sumner's "W" is nominal hourly wages i.e. total nominal wages divided by total hours and writing the way he does not only impacts the symmetry of the formula, but obscures the fact that his theory has zero content. How is that?



Let's start with a graph. No, wait. Let's start with notation. I will write _X ≅ Y_ if the de-trended (HP filtered) quantities _X_ and _Y_ are proportional to each other. Thus, Sumner's theory is _(W/H)/(N/L) ≅ u_.



Ok, now the graph. Which of these de-trended lines (red or blue) -- after being shifted by the average unemployment rate -- is a better model of the unemployment rate (the dotted gray line)?


![](<media/sumners contentless theory.png>)

The blue one of course. The red one is Sumner's model _(W/H)/(N/L) ≅ u_. The blue one? You arrive at it by dividing Sumner's model by a factor of _W/N_; the model is _L/H ≅ u_.


**_L/H ≅ u_ has no content.**


The theory of the blue curve says the hours worked per person in the labor force goes down as the unemployment rate goes up. Or, another way, unemployed people work fewer hours than employed people. Counting the unemployment rate in terms of people thrown out of employment is approximately the same as removing 40 hours per week per unemployed person from the total number of hours worked. Sure, some people are part time, others work more than full time (overtime or multiple jobs), but that just changes the 40 to some other effective number like 35.



However! It turns out Sumner's theory is equivalent to _L/H_ ... all of the fluctuations matching up with the _u_ come from _L/H_, not the _W/N_ piece.



It becomes clearer if you scale Sumner's theory by a factor of 2 (actually, we should use [_c = 2.1_](http://informationtransfereconomics.blogspot.com/2014/01/two-kinds-of-stickiness.html)). The correlation gets much better:


![](<media/sumners contentless theory 2.png>)

What happens when you look at the relative fluctuations from the trend is that you cancel the _W/N_ by multiplying it by _c_ (i.e. _c W/N = 1_ to a good approximation) and effectively arrive at the theory  _c (W/N) x (L/H) = L/H_ _≅ u_. The blue curve. De-trending and looking at relative fluctuations (i.e. proportional fluctuations) eliminates the _W/N_ term.




_(W/H)/(N/L) ≅ L/H_


And L/H, as noted above, has no content. Therefore, **Sumner's theory has no content**. QED.




-   [I noted awhile ago](http://informationtransfereconomics.blogspot.com/2014/02/sticky-wages-information-transfer-and.html) that _W/N_ actually moves less than the employment population ratio over the past 65 years -- it is one of the most stable quantities in economics.
-   [I previously tried to make sense](http://informationtransfereconomics.blogspot.com/2013/08/scott-sumners-model-part-1.html) of Sumner's theory in the information transfer model, but it doesn't work. Nominal hourly wages are not in information equilibrium with NGDP with the fluctuations detected by the unemployment rate.
-   [I also previously showed](http://informationtransfereconomics.blogspot.com/2015/01/is-this-market-monetarist-model.html) that you can make a good model with NGDP in information equilibrium with H where the movements are detected by the price level. However, this theory is effectively Okun's law and has been known for a long time.
-   Shorter ways to say this post are that 1) the the relative fluctuations of the HP filtered quantities _(W/H)/(N/L)_ and _L/H_ are the same or that 2) HP filtered _W/N_ is effectively constant.
