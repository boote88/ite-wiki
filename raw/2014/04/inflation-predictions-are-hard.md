---
title: "Inflation predictions are hard, especially about future inflation"
date: 2014-04-05T16:36:00.000-07:00
updated: 2014-04-05T16:36:00.786-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/04/inflation-predictions-are-hard.html
---

Currently reading through [Simon Wren-Lewis's post on microfoundations and the Phillips curve](http://mainlymacro.blogspot.com/2014/04/microfoundations-and-phillips-curve.html). I'm going to have an empirical look at this quote:

> _First, although various microfounded models suggest inflation should depend on expected inflation next period, the empirical evidence is more equivocal. A number of studies have found that inflation today depends on both expected inflation next period, but also on actual inflation last period (‘inflation inertia’)._

Now I don't think [very](http://informationtransfereconomics.blogspot.com/2013/09/the-useless-power-of-expectations.html) [highly](http://informationtransfereconomics.blogspot.com/2013/07/the-fragility-of-expectations.html) of expectations as a long run driver of macro variables (or even [microfoundations](http://informationtransfereconomics.blogspot.com/2014/02/ii-entropy-and-microfoundations.html)). In the short run, any influence of expectations is likely to [reduce information flow](http://informationtransfereconomics.blogspot.com/2014/03/modeling-macroeconomic-fluctuations.html) because: 1) who knows anything about the future, 2) the EMH and 3) in financial markets any sort of stock picking behavior tends to under-perform the market. (I guess all three of those are related.)



Anyway, here's a plot of year-out inflation expectations from the Michigan survey (red) alongside previous year-over-year inflation (i.e. prior period, blue) and instantaneous inflation (i.e. d/dt log P, or current period inflation, in gray):



![](<media/ite inflation expectations -wren-lewis- 1.png>)

So let's check out a simple model where instantaneous inflation (current period) is the average of expected inflation and past inflation (prior period). The result is in purple in the next graph:



![](<media/ite inflation expectations -wren-lewis- 2.png>)

How does this model compare with the simple [martingale](http://en.wikipedia.org/wiki/Martingale_%28probability_theory%29) of using only the prior period inflation? It actually makes it a bit worse. In the graph below, you can see the model error for the martingale (MTG) in blue and the averaging model (AVG) in purple, the latter has a slight linear trend, being low in the 1980s and high in the 2000s (i.e. the trend is non stationary/has a unit root):



![](<media/ite inflation expectations -wren-lewis- 3.png>)

In the next graph, I show the error histograms for AVG (purple), MTG (blue) and expectations-only (EXP, red). The positive skew of the averaging model derives almost entirely from the expectations -- therefore any more complicated linear combination of the averaging model, say of the form (1-λ) MTG + λ EXP with 0 ≤ λ ≤ 1, will also have a larger positive skew than MTG by itself.



![](<media/ite inflation expectations -wren-lewis- 4.png>)



Overall, inflation expectations are biased toward more inflation than appears and actually throw off the simple prior period inflation heuristic (which itself is slightly slightly biased towards higher inflation than occurs). There are two scenarios (at least) that could account for this:

1.  People are still psychologically affected by the high inflation of the 70s and 80s. This would explain not only the expectations (obviously), but also the trend towards lower inflation due to a central bank staffed with psychologically affected people.
2.  There is an underlying trend towards lower inflation due to e.g. the [diminishing impact of monetary expansion](http://informationtransfereconomics.blogspot.com/2014/03/the-diminishing-effect-of-monetary.html) (see also [here](http://informationtransfereconomics.blogspot.com/2013/10/the-1970s.html)). This would cause even people who used the simple (and fairly accurate) martingale to overshoot inflation, and the Fed to undershoot its _de facto_ if not _de jure_ inflation targets because what worked to achieve 2% inflation in the prior period wouldn't work in the future period.
