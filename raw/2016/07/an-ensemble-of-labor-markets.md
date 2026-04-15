---
title: An ensemble of labor markets
date: 2016-07-17T15:04:00.000-07:00
updated: 2016-07-19T16:08:43.154-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/07/an-ensemble-of-labor-markets.html
---

Believe it or not, this post is actually a response of sorts to David Glasner's nice post "[What's Wrong with Econ 101](https://uneasymoney.com/2016/06/16/whats-wrong-with-econ-101/)" and related to John Handley's request on Twitter for a computation of the implied unemployment rate given an output gap (which I will answer more directly as soon as I find the code that generated the original graph in question). It is also a "new" model, but still fairly stylized. I will start with the [partition function](https://en.wikipedia.org/wiki/Partition_function_\(statistical_mechanics\)) approach described in [the paper](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html) as well as [here](http://informationtransfereconomics.blogspot.com/2014/06/the-macroeconomic-partition-function.html). However instead of being written in terms of money, I will write it in terms of labor.



Consider aggregate demand as a set of markets with demand $A = \{ a_{i} \}$, labor supply $L = \{ \ell_{i} \}$, information transfer indices (which I will label 'productivity states' for reasons that will become clear later) $p = \{ p_{i} \}$, and a price level $CPI = \{&nbsp;cpi_{i} \}$. I use the notation:






which just represents the differential equation ([information equilibrium condition](http://informationtransfereconomics.blogspot.com/2015/12/information-theory-101-information.html))










You can see how the $p_{i}$ values are related to 'productivity'; if the growth rate of $\ell_{i}$ is $r_{i}$, then the growth rate of $a_{i}$ is $p_{i} r_{i}$ and the ratio of $\ell_{i}$ to $a_{i}$ (assuming exponential growth for the two variables) is $e^{p_{i}}$.  Let's take the labor market to be a single aggregate (analogously to taking the money supply to be a single aggregate), so that we can drop the subscripts on the $\ell$'s. Define the partition function






so that the ensemble average of operator $X$ (which will be over 100 markets, i.e. $i = 1 .. 100$ with different values of $p_{i}$ in the Monte Carlo simulations below) is:






I assumed the productivity states had a normal distribution which results in the following plot of 30 Monte Carlo throws for 100 markets for $\langle \ell^{p}\rangle$:



![](<media/ite partition function labor market 1.png>)

The ensemble of 'productivity states' $p_{i}$ looks something like this:



![](<media/ite partition function labor market 2.png>)

This picture illustrates David Glasner's point about general and partial equilibrium analysis in economics 101. The distribution (in black) represents a macroeconomic general equilibrium. Individual firms or markets will move from different productivity states over time. Partial equilibrium analysis looks at individual states that move or have idiosyncratic shocks **_that do not change the overall distribution_**. If the distribution changes, you have moved to a different general equilibrium and partial equilibrium analysis will not suffice. That is to say Economics 101 assumes this distribution does not change. (In this model, shocks are represented as productivity shocks, changing the values of $p_{i}$ and/or the average of the distribution in the figure.)



We can fit this ensemble average to the graph of nominal output (NGDP) versus total employees (PAYEMS on FRED, measured in Megajobs \[Mj\]):



![](<media/ite partition function labor market 3.png>)

The price level should then be given by the ensemble average $\langle p \ell^{p-1}\rangle$ (switching to linear scale instead of log scale):



![](<media/ite partition function labor market 4.png>)

The black lines in these graphs represent a single macroeconomic general equilibrium; as you can see, the true economy (blue) fluctuates around that equilibrium. Now the ensemble of individual markets can be represented as a single macro market, but with a (slowly) changing value of the single 'macro' information transfer index $p = \langle p_{i} \rangle$ plotted below:



![](<media/ite partition function labor market 7.png>)

Note that as the size of the labor market grows, productivity falls. This is analogous to the interpretation of the result for nominal output in terms of money supply: a large economy has more ways of being organized as many low growth states than as a few high growth ones. In thermodynamics, we'd interpret a larger economy (larger money supply or larger labor supply) as a colder economy.



The single macro market with changing $p$ is $CPI : A \rightleftarrows L$, which is basically the information equilibrium relationship that leads to Okun's law (shown in the paper as well as [here](http://informationtransfereconomics.blogspot.com/2015/02/information-equilibrium-paper-draft_23.html) in terms of hours worked, but labor supply also leads to a decent model, graph from [here](http://informationtransfereconomics.blogspot.com/2013/10/apparently-monetary-offset-only-offsets.html)):



![](<media/sumner model -unemployment question- 1.png>)

This correspondence means that we should view the difference between equilibrium output and actual output as well as the difference between the equilibrium price level and the actual price level as a measure of the output gap (difference from potential NGDP) and the unemployment rate, respectively ... which works pretty well for such a simple model:



![](<media/ite partition function labor market 6.png>)
![](<media/ite partition function labor market 5.png>)

Differences between the model and data could be interpreted as non-ideal information transfer which includes correlations among the labor markets (e.g. coordinating plans that fail together) or deviation from the equilibrium distribution of productivity states. Note that in the output gap calculation, you can see what looks like [a plucking model](http://informationtransfereconomics.blogspot.com/2015/02/this-plucking-model-redux.html) of [non-ideal information transfer](http://informationtransfereconomics.blogspot.com/2016/01/nominal-shocks-in-presence-of-growth.html) with a changing equilibrium.



This simple model brings together output and employment, falling inflation and productivity, as well as macroeconomic general equilibrium and microeconomic partial equilibrium in a single coherent framework. It's not perfect empirically, but there isn't much competition out there!

...

**Update 19 July 2016**

Here's how the distribution of 'productivity' states changes as $\ell$ increases:

![](<media/partition function probability.png>)
