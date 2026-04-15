---
title: "Supply, demand, stock, flow"
date: 2015-12-04T15:01:00.003-08:00
updated: 2016-12-06T18:36:34.535-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/12/supply-demand-stock-flow.html
---

Steve Roth of Asymtosis, Angry Bear, and other places [stopped by the blog the other day](http://informationtransfereconomics.blogspot.com/2015/12/money-is-that-which-is-conserved-via.html) and over the course of some discussion -- and perusing his links -- I wanted to note a couple things.



**I.**

[says](http://www.asymptosis.com/supply-and-demand-for-financial-assets.html)

> _Am I foolish to suggest that the central concepts of economics, supply and demand, are embarassingly un(der)theorized?_

I agree! Actually, I think economists might not even understand supply and demand (except [Gary Becker](http://informationtransfereconomics.blogspot.com/2015/10/gary-beckers-emergent-rational-agents.html)). For one, [the supposed experiment designed by Vernon Smith](http://informationtransfereconomics.blogspot.com/2015/01/im-not-sure-economists-understand.html) (Nobel prize winner for this very kind of experimental economics) actually assumes its result. If you assign numerical utility to people, along with a budget constraint, you get supply and demand. This is how [monkeys](http://informationtransfereconomics.blogspot.com/2015/11/monkeys-and-markets.html) can end up illustrating supply and demand. Additionally, various [classroom experiments](http://informationtransfereconomics.blogspot.com/2015/01/is-demand-curve-shaped-by-human.html) don't show what they purport to show. [Supply and demand is a property of the state space](http://informationtransfereconomics.blogspot.com/2015/10/economics-as-and-versus-social-science.html). Gary Becker showed this way back in 1962.



**II.**


There was also some discussion of [stocks and flows](http://www.asymptosis.com/no-saving-does-not-increase-the-supply-of-loanable-funds.html). This is one area where many economists and non-economists get a little too fastidious. It is true that in one case you can have an associated [time (well, 'velocity') scale](http://informationtransfereconomics.blogspot.com/2015/12/by-magic-number-nick-rowe-means-scale.html) (flows) and one where you don't (stocks) and it is important to understand where this scale comes from.



However, in the information equilibrium model, I frequently put a flow in information equilibrium with a stock -- notably in the relationship _NGDP ⇄ M0_. Nominal output is dollars per year (or annualized), whereas the money supply is a stock of currency. And there is nothing particularly wrong with this. Why? Because the information in a distribution doesn't really care too much about the domain it's over ... just what the distribution is over the domain. [This post](http://informationtransfereconomics.blogspot.com/2015/05/the-economic-allocation-problem.html) has a bit of background (it goes over the rationale behind the blog's favicon and the meaning of the diagram up in the upper right corner on a desktop browser).



Let's say we have a spatial-temporal distribution of an information source distribution (demand, translucent white) and one for the destination (supply, blue):



![](<media/it distributions 2.png>)![](<media/it distributions 1.png>)

As you move along the time axis, you have different "stocks" at different instants in time; the change as you move along the time dimension is a "flow". When these are in information equilibrium, they match up:



![](<media/it distributions 3.png>)

When they don't match up (demand doesn't meet supply at the right place and right time), you have information loss that can be measured with the [KL divergence](https://en.wikipedia.org/wiki/Kullback%E2%80%93Leibler_divergence) between the two 2-dimensional distributions:



![](<media/it distributions 4.png>)

However, I can also integrate over the time dimension (add up the areas under the blue and white surfaces in one direction) and still see the information loss as a "stock" (an integrated flow):



![](<media/it distributions 5.png>)

For a simplified version of this with widgets, you can go to [that aforementioned post](http://informationtransfereconomics.blogspot.com/2015/05/the-economic-allocation-problem.html). Once I've done this integration, I am free to compare it to the information content of a probability distribution of something else:



![](<media/it distributions 6.png>)






Now maybe you don't buy this. That's fine. But here's a well known equation in physics that says a stock is equal to a flow (plus a change in flow):



_ẍ + (1/τ) ẋ + ω² x = 0_




This equation for a damped harmonic oscillator is essentially



change in flow + flow + stock = 0



There are just parameters (scales _τ_ and _ω_) that make the units work out. If I say



stock _Y_ \= flow _X_



There is just an implicit time scale _T_ (parameter, or constant of proportionality) so that:



_Y = T X_



If you never couple stocks to flows (putting a stock and a flow in the same equation 'couples' them -- makes them depend on each other), then all flows will be independent of all stocks! There will be a stock description of the economy and a flow description of the economy, and the two will have nothing to do with each other.



Caring a bit too much about stocks and flows is a bit like saying you can't set time equal to a position. And while it's true _x = t_ gets the units wrong, time and position can be in equilibrium -- just add a constant of proportionality (velocity) so that _x = v t_.



In fact, the great achievement of Einstein was creating the idea of _space-time_ -- space and time are in a sense equivalent. The reason they're equivalent is the existence of a universal constant of proportionality: the speed of light _c_. Or you could say the equivalence means there must be a universal constant with units of velocity.

...

**Update 06 December 2016**

Since I wrote this [I found that SFC analysis](https://informationtransfereconomics.blogspot.com/2016/12/stock-flow-consistency-is-tangential-to.html) does couple stocks to flows -- [it also forgets those time scales _T_](https://informationtransfereconomics.blogspot.com/2016/03/more-like-stock-flow-in-consistent.html) -- by looking at stock-to-flow ratios.
