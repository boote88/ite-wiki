---
title: "Dynamic equilibrium: unemployment in Hong Kong"
date: 2017-06-29T15:00:00.000-07:00
updated: 2017-06-29T22:46:20.429-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/06/dynamic-equilibrium-unemployment-in.html
---

On Twitter, [John Handley brought up](https://twitter.com/jwhandley17/status/880258559627284481) Hong Kong's unemployment rate as a potential counterexample/problem for [the dynamic equilibrium model](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html) which says (generally) the unemployment rate will fall when not subject to a shock like a recession. In his tweets, John points out a couple of potential red flags for the dynamic equilibrium description:

> _Hong Kong's unemployment rate has basically been constant since 2011_ 

> _The constant increase from about 1990 to 1995 is also strange & inconsistent with constantly falling unemployment when not in recession_



Now the model may not work for smaller entities like Hong Kong. However, it has roughly equivalent population to Washington State ‒ both a bit over 7 million ‒ and Washington [works fine in the model](http://informationtransfereconomics.blogspot.com/2017/03/washingtons-unemployment-rate-seattles.html). Therefore a failure would call into question at least the scope of the model, if not making us question its usefulness in general.



However, it turns out that the Hong Kong data (blue) is as well-described by the dynamic equilibrium model (red) as Washington state:



![](<media/simple dynamic equilibrium test -hk unrate- 1.png>)

One of the key things to remember is that the normal representation of unemployment data isn't as conducive to eyeballing the success or failure of a dynamic equilibrium description. The best way to see if a dynamic equilibrium model will work is to look at a log linear transformation of the data ‒ _U\*(t, α)_ = _α_ log _U(t)_ + _β_ ‒ that minimizes the entropy in the zero slope bins. For this data set, it looks like this:



![](<media/simple dynamic equilibrium test -hk unrate- 2.png>)

The step-like appearance is the tell-tale sign of a dynamic equilibrium model. It is true that some of the steps are wider than others (corresponding to the duration of the shock); these wide shocks are what leads to the periods of approximately constant unemployment.



I did notice a feature in the HK data that appears in nearly every unemployment data set I've looked at with this model: post-recession shock overshooting. After every recession, there appears to be a brief blip of higher than expected unemployment (relative to the model). For example, here is that aforementioned WA state data:



![](<media/WA unemployment dynamic equilibrium -data updates-.png>)



![](<media/unemployment ratio -log version- 1960s.png>)

So there might be some other deterministic process happening along with recession shocks. It appears to be at the few percent level ‒ a potential subject for a second order model.

...

**Update 29 June 2017**

John Handley questioned the "just-so" nature of the shock that produced the near-constant unemployment in the most recent years. Here is the distribution of parameters for the size (amplitude) and duration of shocks [for OECD countries](http://informationtransfereconomics.blogspot.com/2017/05/dynamic-equilibrium-in-employment.html) with the recent HK shock denoted with an arrow:

![](<media/dynamic eq distribution of params 1.png>)
![](<media/dynamic eq distribution of params 2.png>)
