---
title: Hyperinflation
date: 2013-09-06T18:54:00.001-07:00
updated: 2013-09-06T18:54:28.941-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/09/hyperinflation.html
---

If you let the unit of account enter into the equations in the information transfer model (i.e. let $\kappa \rightarrow \kappa (NGDP, MB)$), you get the [information trap](http://informationtransfereconomics.blogspot.com/2013/08/the-liquidity-trap-and-information.html). In that situation, the price level has only a weak response to changes in the monetary base. This allows an [excellent fit](http://informationtransfereconomics.blogspot.com/2013/07/dotting-is-and-crossing-ts.html) for the model to the empirical price level (data is in green, model fit is blue):


![](<media/price level.png>)

If we look at a given year (say 1985) and look at the model response to an increase in the monetary base (at fixed $NGDP$) we have a price level that rises for a bit and subsequently falls. In terms of the value of a dollar ($1/P$), we get a picture with a fall in the value of a dollar followed by a flattening out (actually a rise) in the value:



![](<media/how do you get hyperinflation.png>)



This is the [information trap](http://informationtransfereconomics.blogspot.com/2013/08/the-liquidity-trap-and-information.html) ([diminishing marginal utility of increasing the monetary base](http://informationtransfereconomics.blogspot.com/2013/08/visualizing-diminishing-marginal.html)). The dashed line shows the traditional economic view (a long run quantity theory of money) that $P \sim MB$. In that case, increasing the base decreases the value of a dollar and leads to inflation ... and eventual hyperinflation.



The question I want to explore is _How do we get hyperinflation in the information transfer model?_ Hyperinflation was declared to be a political phenomenon by [Matthew Yglesias](http://www.slate.com/blogs/moneybox/2013/08/29/syria_inflation_hyperinflation_s_not_about_money.html), and there isn't complete agreement on the [mechanisms](http://en.wikipedia.org/wiki/Hyperinflation#Models) behind it. The government's use of [seigniorage](http://en.wikipedia.org/wiki/Seigniorage) as a source of revenue for a failing economy is a common theme, as well as the so-called inflation tax. This all points to the use of a model.



I will take an agnostic approach and only make the assumption that in the market $P : NGDP \rightarrow MB$, the monetary base represents a [constant information destination](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html) that isn't determined by signals from the aggregate demand (as opposed to a floating information source, i.e. a market determined one). One way of viewing this is that the government or central bank begins issuing base money without regard to any market mechanism while the aggregate demand ($NGDP$) does respond to the signal from the detector of the information transfer ($P$). Performing the [integral here](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html) results in the equations:






These equations actually define a supply curve in the information transfer model (as opposed to a demand curve). If we eliminate $\langle Q^d \rangle$ and replace the supply and demand with $MB$ and $NGDP$, respectively, we obtain:






If we [include](http://informationtransfereconomics.blogspot.com/2013/09/in-singular-interest-of-accounting-for.html) the function of the monetary base $MB$ as the unit of account, then $\kappa = \kappa (NGDP, MB)$, we arrive at






If we add this function starting at the given year (1985, fitting to the price level in 1985 and borrowing $c_0$ from the price level fit at the top of this post), we happily (well, in the academic sense) get a rapidly decreasing value of the dollar (red curve):



![](<media/hyperinflation from constant information source.png>)

The price level associated with this curve if we fit to the rate of growth versus time starting in 1985 is shown in this graph (again, red):



![](<media/accel price level.png>)

The price level in this case basically assumes that the monetary base increases at a constant rate (specifically, the average rate from 1983-1987). This path of the price level results in accelerating inflation:



![](<media/accel inflation.png>)

This is an interesting result! It says that a constant rate of increase in the monetary base results in **_accelerating inflation_** (as opposed to the traditional economic view where a constant rate of increase of the base, ceteris paribus, is supposed to lead to constant inflation).



Ah, but this is just accelerating inflation. I wanted to achieve hyperinflation. We can do that if we increase the rate of increase of the monetary base (say, to 30% per year), which results in a faster increase in the price level:



![](<media/hyper price level.png>)

We achieve hyperinflation (>50% annual inflation rate) in no time:



![](<media/hyper inflation.png>)

The key choice appears to be selecting a constant information destination in the market $P : NGDP \rightarrow MB$. This choice represents a scenario where the aggregate demand responds to price signals, but the monetary base is instead set by the monetary authority without regard to price signals. Aggregate demand "floats" inside the market, while the monetary base doesn't float and is set outside the market.



The price level fit and information trap at the top of this post occur for both a floating information source and floating destination. In that case, information transmission and reception occur in a market (floating = market): the aggregate demand shifts to respond to the price level and the central bank adjusts the monetary base through open market operations that take into account the price level (in the US there is a de facto inflation target on the order of 2%).



In my next post, I plan to take these observations further, summarize the past several market constructions ([IS-LM](http://informationtransfereconomics.blogspot.com/2013/08/deriving-is-lm-model-from-information.html) and [LS-MS](http://informationtransfereconomics.blogspot.com/2013/08/scott-sumners-model-part-2_30.html)) and outline a "theorem" where **_any use_** of a market to set monetary policy (including interest rate, inflation or even NGDP growth or level targeting) can result in an information trap.
