---
title: "Employment doesn't depend on inflation"
date: 2015-08-19T14:00:00.000-07:00
updated: 2015-08-19T14:01:33.037-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/08/employment-doesnt-depend-of-inflation.html
---

[Robert Waldmann](http://rjwaldmann.blogspot.co.uk/2015/08/romer-delong-and-krugman-on-solow-and.html) and [Simon Wren-Lewis](http://mainlymacro.blogspot.com/2015/08/reform-and-revolution-in-macroeconomics.html), in discussing [Paul Romer's history of macro 1977-1982](http://paulromer.net/solows-choice/), bring up the Phillips curve. I've also [written about it](http://informationtransfereconomics.blogspot.com/2013/10/the-phillips-curve.html) on occasion.



I thought I'd have a look at the Phillips using [the DSGE form of the information equilibrium model](http://informationtransfereconomics.blogspot.com/2014/12/an-information-transfer-dsge-model.html). Turns out it results in something really cool ... Here are the relevant equations from the DSGE form link:








Here $n$ is nominal output, $m$ is base money (minus reserves), $\pi$ is the price level, and $\ell$ is the total employed. The symbol $\sigma$ represents 'nominal shocks'. They are the stochastic part of the model, and they're typically positive. They represent the difference between where $n$ is at time $t$ and where it should be based on the change in $m$ from time $t-1$ to time $t$ alone -- essentially equation (1). The rest of the symbols are constants, with $\kappa$ being the IT index (approximately constant over the short run).



I had hoped to show some kind of relationship between changes in the total employed ($\ell_{t} - \ell_{t-1}$) -- and thus changes in unemployment -- and inflation ($\pi_{t} - \pi_{t-1}$). But the math led me to something I didn't expect. With a bit of algebra, you can show that labor growth is given by:






_regardless_ of the information transfer index $\kappa$. Those [nominal shocks](http://informationtransfereconomics.blogspot.com/2014/08/lowflation-is-meaningful-concept.html) I've talked about since [this post](http://informationtransfereconomics.blogspot.com/2013/07/extracting-nominal-shocks.html)? They are basically changes in the number of employed. That's why they're typically positive and typically around a few percent.



Effectively, employment growth is the part of nominal output (NGDP) that is left over after accounting for inflation. Thus there shouldn't be any relationship between inflation and unemployment -- i.e. the Phillips curve isn't real. This even applies to [a version of the model](http://informationtransfereconomics.blogspot.com/2014/12/how-money-transfers-information-from.html) consistent with expectations, since we could easily write:






That is to say expected changes in unemployment are the expected shocks to the economy _after_ accounting for inflation.



How does this look empirically? Pretty good ($\sigma$ in blue, $\ell$ in yellow):



![](<media/itm shocks and labor growth.png>)
