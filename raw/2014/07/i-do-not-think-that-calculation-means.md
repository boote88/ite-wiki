---
title: I do not think that calculation means what you think it means
date: 2014-07-31T20:06:00.002-07:00
updated: 2014-07-31T20:06:52.018-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/07/i-do-not-think-that-calculation-means.html
---

It took me a minute to figure out exactly how Sumner [came up with this result](http://www.themoneyillusion.com/?p=27193). I assume that Sumner meant 2013 Q4 as the ending point of his second period starting at 2014 Q4, so that wasn't the problem. The problem is that Sumner calculated the NGDP growth at some point between 2011 Q4 and 2012 Q4 and at another point between 2012 Q4 and 2013 Q4, not the average growth during those two period (or any other meaningful number).



See, Sumner took the end points of the time periods and calculated the % change between them. I show more digits to give some evidence that I did the same calculation Sumner did:






According to [the mean value theorem](http://en.wikipedia.org/wiki/Mean_value_theorem), taking the slope between the endpoints of a curve only means the slope of some presumably continuous curve achieved that value somewhere in between those end points. It is not the average growth for the period (or really anything at all).



Of course, this isn't the way you should do this. NGDP is a number with some measurement error, so relying on only the two end points means that you massively increase the error in the derived quantity.



What is the (omitted) error on Sumner's measurement? I assumed a log-linear model of GDP from 2009 Q4 to 2014 Q2 and calculated the error bands. The result is plotted here:


![](<media/sumner 1.png>)

If we use these error bars to predict the error on Sumner's measurement, we get






That isn't a typo. The two periods have exactly the same growth rate. The difference between the two periods is entirely measurement error.



We can try a different method: average the growth rate numbers. The period starting from 2009 Q4 also has an average growth rate of 3.8% by this method, however the error is larger at ± 1.9%. Here is a graph:


![](<media/sumner 2.png>)

If you look at this last graph, you can start to see how misleading the numbers in Sumner's post are. I see almost constant growth with random fluctuations around it. If you average these numbers for Sumner's two periods, you end up with another inconclusive result:






There was no failed experiment and market monetarism didn't pass any test. It's all inconclusive.



PS Sumner's commenter Kailer Mullet is incorrect: the single decimal precision (nearest 0.1%) is exactly how much precision is warranted by these numbers. Adding another decimal place is pure noise and taking one away loses information.
