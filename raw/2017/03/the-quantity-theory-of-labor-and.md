---
title: "The \"quantity theory of labor\" and dynamic equilibrium"
date: 2017-03-23T15:00:00.000-07:00
updated: 2017-05-30T09:50:35.246-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/03/the-quantity-theory-of-labor-and.html
---

One of [the earliest models](http://informationtransfereconomics.blogspot.com/2013/08/scott-sumners-model-part-2_30.html) I looked at with the [information equilibrium](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html) (IE) framework was the relationship $P : N \rightleftarrows L$ where $P$ is the price level, $N$ is nominal output, and $L$ is the level of employment. The relationship effectively captures [Okun's law](https://en.wikipedia.org/wiki/Okun's_law) (i.e. changes in real GDP are related to changes in employment), and is a component of what I called the "[quantity theory of labor](http://informationtransfereconomics.blogspot.com/2016/03/a-quantity-theory-of-labor-and-capital.html)" (and capital). The IE notation is shorthand for the equation:






with information transfer (IT) index (a free parameter) $k$. The price level is shown as the "detector" of information flow, and represents an abstract price in the information equilibrium framework. The solution to this differential equation is






Note that if $k = 2$, we have $P \sim L$ (hence the "quantity theory of labor" moniker), and we can obtain (one form of) Okun's law







**Dynamic equilibrium**


Now [dynamic equilibrium](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html) (in the presence of shocks) is another way of looking at the same equation where we look at [the growth of the (abstract) price](http://informationtransfereconomics.blogspot.com/2017/01/housing-prices-and-dynamic-equilibrium.html) on the left hand side and [the growth of the ratio](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-unemployment-rate.html) on the right hand side. Symbolically:






If we take $L \sim e^{\lambda t}$, $P \sim e^{\pi t}$, and $N/L \sim e^{\gamma t}$ then






I have previously [looked at the core PCE price level](http://informationtransfereconomics.blogspot.com/2017/02/nairu-and-other-connections-between.html), and noticed that it is well-described by a single shock centered at 1978.7 (I hypothesized this was related to a demographic shock of women entering the workforce). My question to myself was: what about $N/L$? The answer turned out to tell us that the abstract price $P$ isn't the measured by PCE (i.e. equation (2) is wrong), but rather something in information equilibrium with PCE. We also gain some new perspective on shocks.





![](<media/dynamic equilibrium -inflation- and NGDP over L 1.png>)![](<media/dynamic equilibrium -inflation- and NGDP over L 2.png>)


![](<media/dynamic equilibrium -gdp- 1.png>)
![](<media/dynamic equilibrium -gdp- 2.png>)

The biggest shock is centered at 1977.5, which is equal to the location of the shock to PCE inflation within the error. However, the first issue is that there is an additional shock associated with the aftermath of the great recession (centered at 2014.7). This shock is not obvious in the PCE data. This can be cleared up a bit by forcing the model to have an additional shock:



![](<media/dynamic equilibrium -inflation- and NGDP over L -extra shock-.png>)

The model places a tiny shock (also centered at 2014.7 \[2\]) that is basically buried in the noise. Note that this shock may explain part of the [low post-recession inflation](http://www.bradford-delong.com/2017/03/will-somebody-please-tell-me-why-the-federal-reserve-has-embarked-on-a-tightening-cycle-again.html) and the more recent rise (the equilibrium inflation rate is 1.7%). More on this below in the forecasting section. In any case, this shows the small post-recession shock is not a serious issue.



What is a serious issue is that $\pi =$ 1.7% equilibrium inflation rate compared with the ratio $N/L$ growth rate of $\gamma =$ 3.8%. This tells us that the IE relationship $PCE : NGDP \rightleftarrows L$ is **_at best_** an approximate effective theory. However, it's not a serious issue that can't be dealt with via a simple fix; much like the [interest rate model](http://informationtransfereconomics.blogspot.com/2015/02/information-equilibrium-paper-draft_23.html) \[1\] instead of PCE _being_ the abstract price $P$, we just assume PCE _is in information equilibrium with_ the abstract price $P$:






This introduces a second IT index we'll call $c$ and take $P \sim e^{\gamma t}$ (required by the theory above) and $PCE \sim e^{\pi t}$ so that






Now $\pi = $ 1.7% per year and $\gamma = $ 3.8% so $c = $ 0.45. Note that $\lambda \sim $ 2% meaning that $k \sim 2$ (i.e. the "quantity theory of labor").



What does this mean? Well, if we thought this model was accessing some fundamental "truth", we could say that the growth rate of $P$ (i.e. $\gamma$) is the "true" inflation rate that we only measure crudely with measures like PCE (actually CPI would be a slightly "better" measure with $c$ closer to 1). 



But such a simple model is unlikely to be the best possible description of a macroeconomy, so it's probably best to take an agnostic "[effective theory](https://en.wikipedia.org/wiki/Effective_theory)" approach. In that view, we just take the model above to be a decent approximation for some scope (e.g. average values over time scales of 10s of years, with errors for e.g. [oil shocks](http://informationtransfereconomics.blogspot.com/2016/09/paul-romer-on-volcker-disinflation.html)).



**Addendum: forecasting**


The dynamic equilibrium results do lend themselves to (conditional \[3\]) forecasting, so here is the recent data for $N/L$ and core PCE (and their derivatives) along with a forecast through 2020:



![](<media/dynamic equilibrium -gdp- 3a.png>)
![](<media/dynamic equilibrium -gdp- 3b.png>)

This forecast predicts growth will rise back towards the equilibrium growth rate of 3.8%. Note that this is the growth rate of $N/L$, **_not_** NGDP growth.



Here is PCE including the tiny post-recession shock:



![](<media/dynamic equilibrium -inflation- and NGDP over L 4a.png>)
![](<media/dynamic equilibrium -inflation- and NGDP over L 4b.png>)

The horizontal line is at 1.7% inflation; we can just make out the tiny dip centered at 2014.7 accounting for a 0.25 percentage point drop below 1.7% at the peak of the shock (i.e. about 1.4% inflation during 2014, which is in fact the average during that time ... 1.36%).



For completeness, here is the forecast without this shock:


![](<media/dynamic equilibrium -inflation- and NGDP over L 3a.png>)![](<media/dynamic equilibrium -inflation- and NGDP over L 3b.png>)


**Footnotes**


\[1\] Instead of being the price of money, the interest rate is assumed to be in information equilibrium with the price of money.



\[2\] I previously associated the positive inflation shock with a demographic shift (women entering the workforce). The second shock occurs nearly 40 years later (potentially associated with the cohort that entered the workforce in the 1970s leaving the workforce). It could also be that we are seeing the demographic effect of people affected by the great recession leaving the workforce (the drop in the employment-population ratio), or of the baby boomer cohort retiring (the peak of which was centered in in the mid-1950s, meaning the mid-2010s shock is 60 years later).



\[3\] The condition is that no additional shock occurs during the forecast period.
