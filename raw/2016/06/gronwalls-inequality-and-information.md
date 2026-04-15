---
title: "Gronwall's inequality and information transfer"
date: 2016-06-24T17:00:00.000-07:00
updated: 2016-06-24T17:00:34.679-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/06/gronwalls-inequality-and-information.html
---

In light of Brexit, non-ideal information transfer is now much more salient. And because of that, I thought it might be a good time to post this information transfer-specific form of Gronwall's inequality that's been languishing as a draft for awhile.


...


One of the key lemmas I've used liberally to say the solution of a differential inequality is bounded by the solution of the corresponding  differential equation is called [Gronwall's inequality](https://en.wikipedia.org/wiki/Gr%C3%B6nwall%27s_inequality). It's useful in stochastic differential equations, among other applications. It is not a general result for all differential equations, but fortunately applies precisely in the case we consider in the information transfer framework. It is written differently in the Wikipedia article linked, but I'd like to show this is just a notational difference. The differential equation that the inequality applies to is 



$$<br />u'(t) \leq \beta (t) u(t)<br />$$



This is just the equation





and if $\beta (t) = k/t$, we have





and we can select the variables to be whatever we'd like (and take the function arguments to be implied). Therefore, given an information transfer relationship $\alpha \rightarrow \beta$, we can say the solution to the differential inequality:






is bounded by the corresponding information equilibrium relationship $A \rightleftarrows B$
