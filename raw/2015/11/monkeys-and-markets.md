---
title: Monkeys and markets
date: 2015-11-05T18:39:00.003-08:00
updated: 2015-11-05T18:44:29.478-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/11/monkeys-and-markets.html
---

So I found out my Dad reads the blog, and he sent me a [link to an article](http://www.nytimes.com/2005/06/05/magazine/monkey-business.html?_r=0) from about 10 years ago about observing capuchin monkeys engaging in market behavior set up by experimenters. Previously I noted that [E. coli also exhibits something](http://informationtransfereconomics.blogspot.com/2015/08/obviously-e-coli-is-rational-utility.html) like supply and demand.



I showed you could get this [behavior from random agents](http://informationtransfereconomics.blogspot.com/2015/03/utility-in-information-equilibrium-model.html), based primarily on the properties of the [available state space](http://informationtransfereconomics.blogspot.com/2015/10/economics-as-and-versus-social-science.html). It turns out my contribution wasn't original as [Gary Becker](http://informationtransfereconomics.blogspot.com/2015/10/gary-beckers-emergent-rational-agents.html) had also worked this out in the 1960s (and economists responded negatively to giving up the idea of utility maximization).



The implicit theorizing in the article is great:

> _It took several months of rudimentary repetition to teach the monkeys that these tokens were valuable as a means of exchange for a treat and would be similarly valuable the next day. Having gained that understanding, a capuchin would then be presented with 12 tokens on a tray and have to decide how many to surrender for, say, Jell-O cubes versus grapes. This first step allowed each capuchin to reveal its preferences and to grasp the concept of budgeting._ 

> _Then Chen introduced price shocks and wealth shocks. If, for instance, the price of Jell-O fell (two cubes instead of one per token), would the capuchin buy more Jell-O and fewer grapes? The capuchins responded rationally to tests like this -- that is, they responded the way most readers of The Times would respond. In economist-speak, the capuchins adhered to the rules of utility maximization and price theory: when the price of something falls, people tend to buy more of it._

[Revealed preferences](https://en.wikipedia.org/wiki/Revealed_preference), budget constraint, price shocks, rational responses, utility maximization: the whole framework is there. Even [intertemporal](http://informationtransfereconomics.blogspot.com/2015/10/when-is-intertemporal-budget-constraint.html) expectations ("similarly valuable the next day"). Note that the axiom of revealed preference is equivalent to assuming real-valued utility functions (ensuring transitivity creates a total order which means that whatever it is, it can be represented with real numbers if it's not pathological).



Of course, you can get these results just from the properties of the state space. Start with 12 tokens and look at the available state space for Jell-O (quantity _Q₁_) with a price of 0.8 token, 1 token and 2 tokens. If the monkeys chose a budget completely at random in the available state space, they'd on average choose the point (colored points) at the center of the area bounded by the budget constraint (colored lines):



![](<media/itm monkey 2.png>)

If we change the price of Jell-O from 2 to 1 and then 0.8 token, we move (on average) from the red point to the blue point to the green point. Plotting these out in price-quantity space, we get a downward sloping demand curve:



![](<media/itm monkey 1.png>)

Apparent rational behavior from averaging random choices.



Note that if you add dimensions, i.e. different goods (grapes, Jell-O, crackers, chocolate, beer, ...), the centroids approach the budget constraint lines (most of the volume of a high dimensional space is near its surface), and the random choice approximates utility maximization if you consider utility functions that aren't too asymmetric.
