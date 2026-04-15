---
title: "Scopes and scales: the present value formula"
date: 2016-07-25T12:00:00.000-07:00
updated: 2016-07-25T12:00:28.782-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/07/scopes-and-scales-present-value-formula.html
---

I'm not entirely sure if this conversation broke off from [the discussion of NGDP futures markets](http://noahpinionblog.blogspot.com/2016/07/criticisms-of-ngdp-futures-targeting.html), but [Nick Rowe put up a post](http://worthwhile.typepad.com/worthwhile_canadian_initi/2016/07/simple-basic-money-for-finance-people.html) about the difficulties of calculating the present value of currency. This represents another good example of why you need to be careful about [scales](http://informationtransfereconomics.blogspot.com/2015/11/on-limits.html) and [scope](http://informationtransfereconomics.blogspot.com/2015/10/we-built-this-theory-on-scope-conditions.html).



The basic present value formula of a coupon $C$ with interest rate $r$ at time $T$ is






First, note that an interest rate is actually a time scale. The units of $r$ are percent per time period, e.g. percent per annum. Therefore we can rewrite $r$ as a time scale $r = 1/\tau$ where $\tau$ has units of time (representing, say, the e-folding time if you think about continuous compounding).



Second, this formula comes from looking at a finite non-zero interest rate over a finite period of time. You can see this because the formula breaks if you decide to take $T$ or $\tau$ to infinity in a different order:



![](<media/limits not uniform.png>)

[Paul Romer had this problem](http://informationtransfereconomics.blogspot.com/2015/05/another-mistake-from-romer.html) with Robert Lucas: the limit doesn't converge uniformly. Romer would call taking the limits as $r = 1/\tau \rightarrow 0$ and $T \rightarrow \infty$ in a particular order "mathiness". And I think mathiness here is an indicator that you need to worry about scope. Just think about it -- why would you calculate the "present value" of coupon that had a zero interest rate? It's like figuring out how many stable nuclei decay (see previous link).



The present value formula does not apply to a zero interest rate coupon. It is out of scope.



There are only two sensible limits of the present value formula: $T/\tau = r T \gg 1$ and $T/\tau = r T \ll 1$. This means either $T \rightarrow \infty$ or $\tau \rightarrow \infty$ -- not both. If you want to take both to infinity at the same time, you have to introduce another parameter $a$ because then you can let $T = \tau/a$ and take the limit






The present value can be anything between $C$ and zero. You could introduce other models for $T = T(\tau)$, but that's the point: the present value becomes model dependent. (That's what Nick Rowe does to resolve this "paradox" -- effectively introducing some combination of nominal growth and inflation.)



That also brings up another point: the present value formula doesn't have any explicit model dependence, but it does have an implicit model dependence! It critically depends on being [near a macroeconomic equilibrium](http://informationtransfereconomics.blogspot.com/2016/02/one-more-physics-analogy.html) (David Glasner's macrofoundations). For example, it's possible the value of a corporate bond is closer to zero because there's going to be a major recession where the company defaults. Correlated plans fail to be simultaneously viable, and someone has to take a haircut.



Basically, the scope of the present value formula is near a macroeconomic equilibrium and non-zero interest rates.
