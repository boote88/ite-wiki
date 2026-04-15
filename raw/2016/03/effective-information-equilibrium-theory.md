---
title: Effective information equilibrium theory
date: 2016-03-26T21:00:00.001-07:00
updated: 2019-05-31T16:47:16.237-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/03/effective-information-equilibrium-theory.html
---

While the original information equilibrium condition was derived using a uniform distribution, it lead to an equation that contains a conformal symmetry:






such that if $A \rightarrow \alpha A$ and $B \rightarrow \beta B$, we get the original equation back. If you take the effective field theory approach (which I mention [in the paper](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html)), you would write down all the possible terms on the right hand side that are consistent with the symmetry to first (or lower) order in the process variables. That only adds a constant term:







This is one of the earliest differential equations to ever be solved (in 1694 by John Bernoulli) and the solution is:







The big change is the addition of a linear component -- so that for small values of $B$ (with $k &gt; 1$), we no longer have $A \sim B^k$, but $A \sim B$. The limit for $B &gt;&gt; B_{0}$ is the same as the original solution (i.e. $A \sim B^k$). This could have potential application to e.g. the minimum wage or minimum costs of production. Here are graphs depending on whether c is positive or negative:



![](<media/eff ITM 1.png>)![](<media/eff ITM 2.png>)


![](<media/eff ITM price 1.png>)![](<media/eff ITM price 2.png>)



**Second order?**


Going to second order in the conformal symmetry adds several terms:



$$<br />
\frac{dA}{dB}= k_{00} +&nbsp;k_{10} \frac{A}{B}&nbsp;+ k_{20} \left( \frac{A}{B} \right)^2&nbsp;+ k_{11} \frac{A}{B} \frac{dA}{dB}&nbsp;+ k_{02} A \frac{d^{2}A}{dB^{2}}<br />
$$


_Mathematica_ can (implicitly) solve this if you take $k_{02} = 0$ (making it a first order nonlinear differential equation) -- it's a mess. However, the general form is a nonlinear second order differential equation that requires numerical solution. Including just the additional $k_{20}$ term is solvable in closed form (but also a mess). Numerically, it affects the behavior more when $A/A_{0} &gt;&gt; B/B_{0}$:



![](<media/second order ITM.png>) The price shows similar behavior:

![](<media/second order ITM price.png>) ...

**Update 29 March 2016**


I thought I'd combine the first and second order result, with both using negative coefficients. This gives a result that is relatively flatter near the endpoints and relatively steeper in the middle :



![](<media/second order ITM s.png>)
