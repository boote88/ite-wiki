---
title: An information transfer DSGE model
date: 2014-12-03T19:50:00.001-08:00
updated: 2014-12-03T19:50:33.790-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/12/an-information-transfer-dsge-model.html
---

For fun (and bowing to the [inherent superiority of economics](http://crookedtimber.org/2014/12/02/economists-arent-superior-just-because/) over other fields), here's the [information transfer (macro) model](http://informationtransfereconomics.blogspot.com/2014/06/the-information-transfer-model.html) as a fancy log-linearized DSGE/RBC model with lots of neat $\LaTeX$ symbols:










Here the log-linearized variables are $n$ (nominal output), $m$ (the currency base, M0), $b$ (monetary base, MB), $\pi$ (the price level), $\ell$ (labor supply), $w$ (nominal wages) and $r^{x}$ (interest rates with _x = l, s_ for long- and short-term). The term $\sigma$ represents the '[nominal shocks](http://informationtransfereconomics.blogspot.com/2014/03/the-monetary-base-as-sand-pile.html)' (see also [here](http://informationtransfereconomics.blogspot.com/2014/12/japans-new-recession.html), mathematically no different from the RBC TFP shocks, but could include e.g. changes in government spending). The parameters are the $c_{i}$, $m^{*}$ and $b^{*}$ (the log of the equilibrium/starting values of the monetary base components) along with our old friend $\kappa$, the information transfer index. In a log-linearized model, $\kappa$ is a constant since we're considering small deviations from the variables in the log-linearization.



This representation explicitly shows that there aren't any $E_{t}$ terms (expectations) unlike e.g the RBC model \[[pdf](http://www.karlwhelan.com/MAMacro/part6.pdf)\]. A couple of additional interesting facts pop out if we set $\kappa$ to the 'IS-LM' regime (1.0) or quantity theory of money regime (0.5) (see [here](http://informationtransfereconomics.blogspot.com/2014/05/limits-of-information-transfer-model.html) for more about the meaning of this). If $\kappa = 1.0$ we have:






where nominal output is unaffected by monetary policy and inflation is constant. If we plug (1a) back into the interest rate formula, we see that monetary expansion will cause interest rates to fall (nominal output is unchanged by monetary expansion). If $\kappa = 0.5$ we have:






which says the price level grows with the monetary base (the quantity theory of money). If we plug (1b) back into the interest rate formula, we see that monetary expansion will generally cause interest rates to rise (nominal output will increase because nominal growth will exceed monetary expansion). Explicitly:






where the nominal shocks $\sigma$ are [observed](http://informationtransfereconomics.blogspot.com/2014/08/lowflation-is-meaningful-concept.html) to be generally positive (think growth in TFP or population) along with $c_{2}$ (which is $\sim \log NGDP/M0$).



Anyway, this is just the baseline model -- I'll put in some equilibrium conditions and policy targets and see if economics really is superior to other fields of inquiry. I mean this kind of thing was [Nobel prize level work in the 1980s](http://en.wikipedia.org/wiki/Edward_C._Prescott).



PS _Where's the information theory in this, you ask?_ It's in the parameter $\kappa$ for starters which defines the relative information content of nominal output relative to the supply of money. Equations (1), (4) and (5) represent information equilibrium conditions while equations (2) and (3) represent measures of the rates of change of information transfer.
