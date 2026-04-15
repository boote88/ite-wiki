---
title: Theories of identities are nonsensical; information equilibrium conditions are better
date: 2015-03-03T19:00:00.000-08:00
updated: 2015-03-04T10:31:44.575-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/03/theories-of-identities-are-nonsensical.html
---

In reading David Glasner's two posts (so far) on accounting identities:

-   [Why Theories of National Income Based on Accounting Identities Are Nonsensical and Error-Ridden, Part I](http://uneasymoney.com/2015/02/20/why-theories-of-national-income-based-on-accounting-identities-are-nonsensical-and-error-ridden-part-i/)
-   [Why Theories of National Income Based on Accounting Identities Are Nonsensical and Error-Ridden, Part II](http://uneasymoney.com/2015/03/03/why-theories-of-national-income-based-on-accounting-identities-are-nonsensical-and-error-ridden-part-ii/)

I suddenly realized I was looking at an argument that these so-called accounting identities represent information equilibrium (~) conditions. Let's posit something called aggregate demand _N_ (for NGDP) that is an information source for national aggregate variables. Additionally, let's say aggregate demand is in information equilibrium with income (_Y_) and expenditure (_E_):


_N ~ Y_
_N ~ E_


Now if we have ideal information transfer ('economic equilibrium'), information equilibrium is an [equivalence relation](http://informationtransfereconomics.blogspot.com/2015/03/information-equilibrium-is-equivalence.html), so that we can immediately say:


_E ~ Y_

_log E = k log Y + m_


In order to allow E = Y at some point, we must have k = 1  and m = 0, which means that E = Y in equilibrium (ideal information transfer). Now away from economic equilibrium (non-ideal information transfer), we have


_a log Y + b < log N_
_a log E + b < log N_


so in general _E ≠ Y_. (The coefficients of the logs, i.e. _a_, and the intercepts, i.e. _b_, must be equal in order to allow the possibility that _E = Y_.) The information transfer model [doesn't tell you](http://informationtransfereconomics.blogspot.com/2014/01/what-is-and-isnt-explained-by.html) how far _Y_ or _E_ fall; it just says there should be a trend where _Y ~ E_ if markets are typically in equilibrium.



This general argument would apply to any national income identity, such as savings and investment (_S ≡ I_), that isn't based on a definition (e.g. per Glasner _purchases equal sales_). More interestingly, it applies to another definition: _the equation of exchange_.



I got in an argument with Scott Sumner [on his post](http://www.themoneyillusion.com/?p=28712) that says _MV = PY_ just means _V ≡ PY/M_ for saying that, sure, in the economics profession it's just a definition, but I think the equation of exchange can be usefully restated as an information equilibrium condition.



If we look at the market _P:N→M_ \[1\] where the price level _P_ is a [detector](http://informationtransfereconomics.blogspot.com/2013/04/the-information-transfer-model.html), _N = PY_ is aggregate demand (NGDP) is an information source and _M_ is the money supply (we'll say base money minus reserves), we can write down the equations (in economic equilibrium, i.e. ideal information transfer):


_N ~ M_
_log N = k log M + c1_
_log P = (k - 1) log M + c2_



_PY/M = N/M = (1/k) P ≡ V_


How does this compare with empirical base velocity? Well, if we take [the expected value _<P/k>_ in 1000 random markets](http://informationtransfereconomics.blogspot.com/2014/06/the-macroeconomic-partition-function.html) with random _k_ values between 0 and 2, we get a pretty good fit (for such a simple model):


![](<media/itm random markets -velocity-.png>)

This is the Monte Carlo result with 10 different random sets of 1000 markets, hence the 10 gray lines. The blue points are the data (from FRED). Again, it's the trend we're capturing here, and the fluctuations represent non-ideal information transfer and/or shocks.


**Footnotes:**


\[1\] The notation _A:X→Y_ means that _X_ is an information source, _Y_ is an information destination and _A_ is a detector per [the definitions](http://informationtransfereconomics.blogspot.com/2013/04/the-information-transfer-model.html) in the original information transfer model paper.
