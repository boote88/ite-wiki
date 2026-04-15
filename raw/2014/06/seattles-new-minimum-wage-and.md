---
title: "Seattle's new minimum wage and information theory"
date: 2014-06-03T19:16:00.000-07:00
updated: 2014-06-03T19:16:14.998-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/06/seattles-new-minimum-wage-and.html
---

I mentioned [yesterday](http://informationtransfereconomics.blogspot.com/2014/06/on-travel-again-light-blogging.html) I was working on a post about the minimum wage increase in my hometown of Seattle to 15 dollars per hour \[1\]. I worked up an analysis with the information transfer model and it turns out it is largely consistent with [Scott Sumner's rather even-handed assessment](http://www.themoneyillusion.com/?p=26871) of the possibilities of the impacts. In particular, Sumner points out that the effect of a minimum wage increase is largely model-dependent (although he doesn't use those words exactly).



One take-away from this analysis, though, is that the "economics 101" view that an increase in the minimum wage leads to fewer jobs involves unstated assumptions, and, as it is usually presented, wrong. The easy way to see that (from my perspective) is that a number p > 7.5 and a number p > 15 carry the same amount of information, so that inside the market itself, there really is no difference between them. Just like moving the decimal place to the right two places on all prices (a scale factor), shifting all minimum wage workers hourly wage by 7.5 (constant shift) has no impact on its own. The impact lies entirely in the interaction of the labor market with the markets for goods and services.



Let's begin at the beginning with an ideal system with a labor supply S, money supply M (it doesn't matter which aggregate at this point) and labor demand D. We can follow [this post](http://informationtransfereconomics.blogspot.com/2014/03/how-money-transfers-information.html) and write down a relationship between the information transferred to the supply from the demand that is mediated by money





We'll ignore the demand side of this (it isn't necessary here, basically we can say that demand and money supply are the same thing in this analysis) and just write down the differential equation resulting from the second equals sign (taking $n_{s} = S/dS$ and $n_{m} = M/dM$)





where $a = \log s/\log m$ is a constant. The left hand side of equation (2) is the exchange rate of labor supply for money basically the price of labor (i.e. wages). This differential equation [can be solved](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html) holding each of $S$ and $M$ constant, resulting in supply and demand curves pictured in the graph below. This result has a mimimum wage of zero. But before we get to the graph, let's apply a finite minimum wage by adding a constant $c$ to the left hand side (or subtract it from the right hand side), leaving you with the equation





If you solve this differential equation you get the thick blue curve in the graph below:


![](<media/itm min wage 1.png>)

We've recovered the "economics 101" picture: the price of labor goes up, the number of jobs goes down. However, there is something that's been left out. See, the "demand curve" (black) is the solution to equation (2), not equation (3). In the graph below, I've added in the actual minimum wage price (= 1.5 here) as well as a dotted gray line:


![](<media/itm min wage 2.png>)

Our supply and demand curves for a given market should be the solution to the same differential equation. The result of using (3) for the demand curve as well gives the picture below:


![](<media/itm min wage 3.png>)

The equilibrium price has gone up (from 1 to 2.5 = 1 + 1.5), but the equilibrium quantity demanded is the same as for the zero minimum wage solution. The implied assumption in the "economics 101" analysis must be that the supply curve shifts to the right (or the demand curve shifts to the right):


![](<media/itm min wage 4.png>)

This assumption can follow from budget constraints, supply shocks or even expectations, but it is importatnt to realize it is model dependent.



Now let's look at non-ideal information transfer. In that case, the supply and demand curves (via [Gronwall's inequality](http://en.wikipedia.org/wiki/Gronwall%27s_inequality)) [form a bound](http://informationtransfereconomics.blogspot.com/2013/04/sticky-prices-from-non-ideal.html) on the equilibrium price and quantity demanded/supplied. Let's also assume that every state (point in quantity-price space) is equally likely, i.e. maximum ignorance. We can use that to see where the averge wage would fall over the purple triangle of allowed states (you'll need to integrate $e^{-x}$ to $\infty$). In the graph below, the area above the purple line and below it are equal:


![](<media/itm min wage 5.png>)

One thing to note is that in this picture, the most likely wage is anchored at the minimum wage (in this case = 0), while the average is a little bit higher (it's about = 0.17).



If we perform the shift in equation (3), the whole diagram basically shifts upward. This view makes sense intuitively -- if we assume the minimum wage labor market is small enough to be considered independent of aggregate demand, then when apply a minimum wage increase, the most likely wage is at the new minimum wage and the average wage is slightly above it.


![](<media/itm min wage 6.png>)

The key take-away here is that the fall in employment with a minimum wage increase is not "economics 101", but rather a model dependent result. "Economics 101" _**should**_ say that an arbitrary shift in the price of good in a single market does not matter.



\[1\] I try to avoid "dollar signs" because they mess with the mathjax and I haven't figured out a way to fix it.
