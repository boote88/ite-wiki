---
title: Market monetarism falls in the liquidity trap
date: 2013-09-07T19:46:00.002-07:00
updated: 2014-05-10T23:21:25.551-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/09/market-monetarism-falls-in-liquidity.html
---

We've seen that the choices of a constant (outside the market) or floating (inside the market) information sources and destinations has a considerable impact on the resulting model. Having a market aggregate demand and a non-market monetary base with the price level detecting the signal from the demand to the base can lead to [hyperinflation](http://informationtransfereconomics.blogspot.com/2013/09/hyperinflation.html) (or runaway interest rates). Choosing a market aggregate demand and a market base leads to [very powerful monetary policy](http://informationtransfereconomics.blogspot.com/2013/08/scott-sumners-model-part-2_30.html) if you don't include the effect of the base modifying the unit of account, but leads to "liquidity trap"-like conditions if you do. In the [market shorthand](http://informationtransfereconomics.blogspot.com/2013/08/scott-sumners-model-part-2_30.html), all of these markets are represented by P:NGDP→MB where P is the price level.



There are three main cases

-   **Market source, set destination:** This includes the [hyperinflation](http://informationtransfereconomics.blogspot.com/2013/09/hyperinflation.html) case P:NGDP→MB and generally describes a supply curve. 
-   **Market source and destination:** This includes the [quantity](http://informationtransfereconomics.blogspot.com/2013/07/recovering-quantity-theory-from.html) [theory](http://informationtransfereconomics.blogspot.com/2013/07/dotting-is-and-crossing-ts.html) of [money](http://informationtransfereconomics.blogspot.com/2013/08/the-liquidity-trap-and-information.html) and the MS market in the [LS/MS](http://informationtransfereconomics.blogspot.com/2013/08/scott-sumners-model-part-2_30.html) model (for labor supply/money supply). Both of these are also P:NGDP→MB as in the previous case but the monetary authority conducts its operations in a market (the MB "floats"). This combination generally describes an equilibrium path for a market (both supply and demand reacting to price signals). 
-   **Set source, market destination:** This includes the LS market (P:NGDP→LS) in the LS/MS model and both markets in the [IS/LM](http://informationtransfereconomics.blogspot.com/2013/08/deriving-is-lm-model-from-information.html) model (r:NGDP→AS aggregate supply/goods market and r:NGDP→MB the money market, respectively with the interest rate r as the price). This generally describes a demand curve. 

There is an additional modification mentioned in the introduction. In the special case of P:NGDP→MB, the monetary base describes both the amount of money in the supply as well as the units all three pieces are measured in (the price level in the US is a ratio of two prices in dollars at different times). In economics this is known as two of the [functions of money](http://en.wikipedia.org/wiki/Money#Functions): the medium of exchange and the unit of account, respectively. We incorporate this by allowing the [information transfer index](http://informationtransfereconomics.blogspot.com/2013/04/the-information-transfer-model.html) κ, which measures the number of symbols used to describe the signal in the information source and destination (demand d and supply s, respectively, and sorry about the s-d source-demand and d-s destination-supply pairings), to vary with the size of the monetary base and the aggregate demand. In particular,





The constant $K_0$ determines the unit of information ($=1/\log 2$ for bits and $= 1$ for nats) and $c_0$ is a dimensionful constant that is fit to the data. Ever since [this post](http://informationtransfereconomics.blogspot.com/2013/07/universalizing-model-kappa-sigma-space.html) (refer to it for the rationale), I've taken $c_0 = \gamma Q^s_{ref} = \gamma MB_{ref}$ where $\gamma ∼ 0.016$ is a universal constant across countries. There is one additional assumption: κ is slowly varying which allows us to [pull it out of the integral](http://informationtransfereconomics.blogspot.com/2013/07/dotting-is-and-crossing-ts.html). The logarithmic dependence on MB and NGDP as well as the empirical fact that the value only changes from ∼0.6 to ∼0.8 over 60 years justifies this assumption.



This modification allows this [excellent fit](http://informationtransfereconomics.blogspot.com/2013/07/dotting-is-and-crossing-ts.html) to the price level (and [inflation rate](http://informationtransfereconomics.blogspot.com/2013/09/hyperinflation.html) and [RGDP growth](http://informationtransfereconomics.blogspot.com/2013/06/real-growth.html), as well as describing [Japan](http://informationtransfereconomics.blogspot.com/2013/09/i-refute-it-thus.html)). I did not include it in the LS/MS model above because I didn't think Scott Sumner would appreciate it (because it leads to the [information trap](http://informationtransfereconomics.blogspot.com/2013/08/the-liquidity-trap-and-information.html), analogous to the liquidity trap popularized by Paul Krugman, where monetary policy loses effectiveness). I even [included it](http://informationtransfereconomics.blogspot.com/2013/09/in-singular-interest-of-accounting-for.html) in a fit to the interest rate, which led to a marginal improvement.




> **Information Trap Theorem** Given the market $P : NGDP\rightarrow MB$ with a floating information source and destination and the functional form $\kappa(NGDP,MB)$ given by $\text{(1)}$ above, with $0 \lt \kappa \lt 1$ for $MB = MB_0$, then for some value $MB = MB_*$ with $MB_0 \lt MB_*$ we have



**Proof**

[goes through zero](http://informationtransfereconomics.blogspot.com/2013/07/universalizing-model-kappa-sigma-space.html)





What does this mean in terms of economics? Well, here is a less mathematical version:

> **Information Trap Theorem** Given a market determination of the monetary base via a price mechanism with the monetary base acting as the medium of exchange and the unit of account, then for a given level of aggregate demand there is some level of the monetary base where increases in base money will not increase the price level.

This is actually fairly general and follows from information theory (assuming a market is transferring information). It says that any open market monetary policy target (with floating aggregate demand and floating monetary base) -- be it interest rate, price level, inflation rate, NGDP level, or NGDP growth rate -- will suffer from a situation where monetary policy becomes ineffective (resulting in "liquidity trap"-like conditions). The key requirements are the market determination of the base and money acting as the medium of exchange and the unit of account. Monetary aggregate targets (like the Friedman rule for the constant growth of M2) and other formulas with constant growth in the money supply won't suffer from an information trap, but will lead to [accelerating inflation](http://informationtransfereconomics.blogspot.com/2013/09/hyperinflation.html) if they don't include a market mechanism.



This means that the market monetarists will fall in the information trap just like any other type of open market monetary policy (besides, say, a constant rate of growth in the base which unfortunately leads to accelerating inflation). Or using Scott Sumner's metaphor, the steering wheel doesn't work when you need it when you use NGDP targeting either.




