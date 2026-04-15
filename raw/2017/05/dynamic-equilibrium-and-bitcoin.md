---
title: Dynamic equilibrium and the bitcoin exchange rate
date: 2017-05-30T21:31:00.001-07:00
updated: 2017-05-30T21:31:44.737-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/05/dynamic-equilibrium-and-bitcoin.html
---

I saw [JP Koning's post](http://jpkoning.blogspot.com/2017/05/evaluating-my-bitcoin-predictions.html) on bitcoin today, and the graph of the dollar/bitcoin exchange rate shows the tell-tale signs of a [dynamic equilibrium](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html).



After cobbling together a time series from [this source of data](http://api.bitcoincharts.com/v1/csv/), the model shows that there are nine major shocks. Eight centroids are (one at the beginning didn't have enough data): 2012.5, 2013.2, 2013.8, 2014.4, 2015.8, 2016.4, 2017.0, and 2017.4 (the current massive rise). Graphically, this is what it looks like (in linear and log scale):


![](<media/bitcoin dynamic equilibrium 1.png>)
![](<media/bitcoin dynamic equilibrium 2.png>)

I wouldn't put too much stock in the exact timing of the collapse of the latest shock; it's fairly uncertain (as we can see from [the graphs of the unemployment rate forecast](http://informationtransfereconomics.blogspot.com/2017/04/determining-recessions-with-algorithm.html)). But it it's correct, then I'll totally take credit. Just kidding.



The interesting thing is that the dynamic equilibrium itself is a fractional decrease of −2.6/y (i.e. bitcoin loses more than half its value over the course of a year). This makes it [similar to gold](http://informationtransfereconomics.blogspot.com/2017/02/dynamic-equilibrium-price-of-gold.html), but on a much faster time scale (gold is −0.027/y). That is to say, you can think of bitcoin as a time lapse picture of gold; what happens to gold over 100 years happens to bitcoin in a year.



Another consequence of that is that bitcoin is just as stable for a transaction that takes place over a day (trading in the 21st century) as gold is for a transaction that takes place over 100 days (trading in the 18th century).



I found that absolutely fascinating. 



What does this mean for the future? Well, as long as positive shocks keep coming that are big enough and/or frequent enough, the value of bitcoin never has to go to zero. Estimating using a Poisson process with the current shocks, we have a time scale of 1.4 years (inter-shock period) which may well be sufficient given the size of the shocks already visible in the data (I want to analyze this further).
