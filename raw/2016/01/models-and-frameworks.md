---
title: Models and frameworks
date: 2016-01-27T15:30:00.000-08:00
updated: 2016-01-27T15:30:03.299-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/01/models-and-frameworks.html
---

Given that I [recently put forward](http://informationtransfereconomics.blogspot.com/2016/01/its-people-economy-is-made-out-of-people.html) the idea that inflation and growth are all about labor force growth, I thought I'd clarify some things. Some of you might have asked yourself (or did ask me in comments) about how this ["new model" \[1\]](http://informationtransfereconomics.blogspot.com/2016/01/its-people-economy-is-made-out-of-people.html) relates to the ["old model" \[2\]](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html) that's all about money. I know I did.



The key thing to understand is that the information transfer framework (described in more detail [in my arXiv paper](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html)) is just that: a framework. It isn't a model itself, just a tool to build models. Those models don't have to be consistent with each other. So there really is no "new model" or "old model", just different models that may be different approximations (or one or both might become empirically invalid as more data comes in).



And as a tool, it's basically an information-theoretic realization of Marshallian supply and demand diagrams. What you do is posit an information equilibrium relationship between _A_ and _B_, which I write _A ⇄ B_, or an information equilibrium relationship with an abstract price _p = dA/dB_, which I write _p : A ⇄ B_, and here's what's included (act now!) ...



-   A general equilibrium relationship between _A_ and _B_ (with price _p_) where _A_ and _B_ vary together (that always applies). Generally, more _A_ or more _B_ leads to more _B_ or more _A_, respectively.
-   A partial equilibrium supply and demand relationship between _A_ and _B_ (with price _p_) with _B_ being supply and _A_ being demand -- it applies when either _A_ or _B_ is considered to move slowly with respect to the other (it's an approximation to the former where _A_ or _B_ is held constant).
-   The possibility of "market failure" where we have non-ideal information transfer that I write _A  → B_ (all of the information from _A_ doesn't make it to _B_). This leads to a non-ideal price _p\* < p_ as well as a non-ideal supply _B\* < B_.
-   A maximum entropy principle that describes what (information) equilibrium between A and B actually means, including a causality that can go in both directions along with potentially emergent entropic forces that have no formulation in terms of agents.



So in the information transfer framework there are information equilibrium relationships _A ⇄ B_ and more general information transfer relationships _A  → B_. I tend to refer to these individual relationships as "markets". Given these basic "units of model", you can construct all kinds of relationships. Traditionally crossing-diagrams are easiest. Things like [the AD-AS model](http://informationtransfereconomics.blogspot.com/2015/04/what-does-ad-as-model-mean.html) or the [IS-LM model](http://informationtransfereconomics.blogspot.com/2014/03/the-islm-model-again.html) can be concisely written as the market



_P : AD ⇄ AS_


where AD is aggregate demand and AS is aggregate supply, or the markets



_(r ⇄ p) : I ⇄ M_
_PY ⇄ I_
_PY ⇄ AS_


for the IS-LM model where _PY_ is nominal output (i.e. _P × Y = NGDP_, I also tend to write it _N_ on this blog and in the paper), _I_ is investment, _M_ is the "money supply", _p_ is the "price of money" and _r_ is the interest rate.



Another aspect of the model is that information equilibrium is an equivalence relation, so that _AD ⇄ M_ and _M ⇄ AS_ implies _AD ⇄ AS_ (this makes [an interesting definition of money](http://informationtransfereconomics.blogspot.com/2015/05/money-defined-as-information-mediation.html)). This means that if you find a relationship (as I did in \[2\])



_CPI : NGDP ⇄ CLF_


there could be some other factor(s) _X_ (, _Y, Z_, ...) such that



_NGDP ⇄ X ⇄ Y ⇄ Z ⇄ CLF_


Relationships like this can be inferred from a price that doesn't follow _CPI\* < CPI_, but can be above or below the ideal price _CPI_ (_CPI\* < CPI_ or _CPI\* > CPI_) that follows from [being careful about the direction of information flow](http://informationtransfereconomics.blogspot.com/2015/05/money-defined-as-information-mediation.html) and the intermediate abstract prices _p₁_ and _p₂_ in the markets



_p₁ : NGDP ⇄ X_
_p₂ : X ⇄ CLF_


These would probably find their best analogy in "supply shocks" (price spikes due to non-ideal information transfer) as opposed to "demand shocks" (price falls due to non-ideal information transfer). Note that in the model _CPI : NGDP ⇄ CLF_ with intermediate _X_,  _CPI = p₁ × p₂_ because _CPI = dNGDP/dCLF = (dNGDP/dX) (dX/dCLF)_ via the chain rule.



In the end, however, the only way to distinguish among different information equilibrium models (or information transfer models) is empirically. This framework works much like how quantum field theory works as a framework (as a physicist, I like to have a framework ... anything else is just philosophy). You observe something in an experiment and want to describe it. One group of researchers models it as a real scalar field and writes down a Lagrangian



_ℒ = ϕ (∂² – m) ϕ_


Another group models it as a spin-1/2 field



_ℒ = ψ (i ∂ – m) ψ_


(ok, that one's missing a slash and a bar). Both "theories" are perfectly acceptable ex ante, but ex post one or both may be incompatible with empirical data.



Actually [one of the goals of this blog](http://informationtransfereconomics.blogspot.com/2013/04/an-informal-abstract-addition-why-now.html) (and the information transfer model) was to introduce exactly this kind of model rejection to economics:

> _I was inspired to do this because of Noah Smith's [recent post on why macroeconomics doesn't seem to work very well](http://noahpinionblog.blogspot.com/2013/04/the-reason-macroeconomics-doesnt-work.html). Put simply: there is limited empirical information to choose between alternatives. My plan is to produce an economic framework that captures at least a rich subset of the phenomena in a sufficiently rigorous way that it could be used to eliminate alternatives._

I've come up with several different information equilibrium relationships -- or models built from collections of relationships (see below) -- and I am [testing their abilities with forecasts](http://informationtransfereconomics.blogspot.com/2015/09/prediction-aggregation-redux.html). Some might fail. Some have failed already. For example, the IS-LM model does not work if inflation is high (but represents an implicit assumption that inflation is low, so it is best to think of it as an approximation in the case of low inflation). A few of Scott Sumner's versions of his "market monetarist" model can be written as information equilibrium relationships (see below) ... and they mostly fail.



In a sense, I wanted to try to get away from the typical econoblogosphere (and sometimes even academic economics) BS where someone says "_X_ depends on _Y_" and someone else (such as myself) would say "that doesn't work empirically in magnitude and/or direction over time" and that someone would come back with other factors _A_, _B_ and _C_ that are involved at different times. I wanted a world where someone asks: is _X ⇄ Y_? And then looks at the data and says yes or no. DSGE almost passes this test -- these models are at least specific enough to compare to data. However they don't ever seem to look at the data and say no ... it's always "add a financial sector" or "add behavioral economics". [There isn't enough data to support that kind of elaboration](http://informationtransfereconomics.blogspot.com/2015/04/all-models-are-wrong-but-some-are.html).



A good example is the quantity theory of money. It says _PY = MV_. Now this was great in a world where people thought _V_ was constant (i.e. the old Cambridge _k_). But that turns out not to be the case and now _V_ could depend on _E\[PY\]_ or _E\[P\]_ or _E\[M\]_ or something else. What are these specific expectation models? Is _E\[P\]_ \= TIPS? Or is _V ≡ PY/M_ is now a definition? And what is _M_? M2? MB?



Essentially various versions of the quantity theory of money have been falsified empirically (or at best a loose approximation when inflation is high) ... but it keeps trucking along because it doesn't exist in a framework where either its scope or validity can be challenged.



It's probably a naive hope, but it's the kind of naive hope that distinguishes "science" from "mathematical philosophy".





**Addendum: information equilibrium models**



_I. The "quantity theory of labor" \[1\]_

_P : PY ⇄ CLF_

[this post](http://informationtransfereconomics.blogspot.com/2016/01/its-people-economy-is-made-out-of-people.html)

_II. "The" IT model \[2\]_

_P : PY ⇄ M0_
_(r¹⁰ʸ ⇄ pᴹ⁰) : PY ⇄ M0_
_(r³ᵐ ⇄ pᴹᴮ) : PY ⇄ MB_
_P : PY ⇄ L_


where the _r_'s represent the long and short term interest rates (3 month and 10 year), _M0_ is base minus reserves, MB is the monetary base (including reserves) and _L_ is the labor supply (the last relationship is essentially Okun's law). I usually measure the price level _P_ with core PCE, but empirically it is hard to tell the difference between core PCE and core CPI (or the deflator). This model also allows the information transfer index in the first market to slowly vary. This represents a kind of [analytic continuation](https://en.wikipedia.org/wiki/Analytic_continuation) from a "quantity theory of money" to an "IS-LM model with liquidity trap".



It also has a "[DSGE form](http://informationtransfereconomics.blogspot.com/2014/12/an-information-transfer-dsge-model.html)" that connects [labor shocks to nominal output shocks](http://informationtransfereconomics.blogspot.com/2015/08/employment-doesnt-depend-of-inflation.html), shows [more clearly the limits where monetary expansion is expansionary vs not (liquidity trap)](http://informationtransfereconomics.blogspot.com/2014/12/an-information-transfer-dsge-model.html) as well as [interest rate dynamics in those two limits](http://informationtransfereconomics.blogspot.com/2015/11/dsge-form-of-it-model-active-but-not.html) (separating out [the income/inflation effect and the liquidity effect](http://informationtransfereconomics.blogspot.com/2014/03/the-effects-that-move-interest-rates.html)).



Both this model and the next one [are in my paper](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html).



_III. Solow model (plus IS-LM)_

_PY ⇄ L_
_PY ⇄ K ⇄ I_
_K ⇄ D_
_1/s : PY ⇄ I_
_(__r³ᵐ_ _⇄ p) : I ⇄ MB_


where the last market is the IS-LM piece, _K_ is capital and _D_ is depreciation. This is a bit different from the traditional Solow model in that it is written in terms of nominal quantities. This may sound problematic, but it throws out total factor productivity as unnecessary and is [remarkably empirically accurate](http://informationtransfereconomics.blogspot.com/2015/05/dynamics-of-savings-rate-and-solow-is-lm.html) in describing output as well as the short term interest rate.



_IV. Scott Sumner's various models [(1)](http://informationtransfereconomics.blogspot.com/2013/08/scott-sumners-model-part-1.html), [(2)](http://informationtransfereconomics.blogspot.com/2015/02/scott-sumners-contentless-theory.html) and [(3)](http://informationtransfereconomics.blogspot.com/2015/08/scott-sumners-information-equilibrium.html)_

_u : NGDP ⇄ W/H_


... this is just empirically wrong over more than a few years. _H_ is total hours worked and _W_ is total nominal wages.



_(W/H)/(PY/L) ⇄ u_


... but  _H/L ⇄ u_ has almost no content (higher unemployment means fewer worked hours per person) and the relationship _c : PY ⇄ W_ has a constant abstract price meaning  _PY = c W_ with _c_ constant. The model reduces to _(1/c) (H/L) ⇄ u_ or just the content-less _H/L ⇄ u_.



The correct version of both of these is _P : PY ⇄ L_ or _P : PY ⇄ H_, which are just Okun's law (above).



_(1/P) : M/P ⇄ M_


This may look a bit weird, but it could potentially work if Sumner didn't insist on an information transfer index  _k = 1_ (if _k_ is not 1, that opens the door to a liquidity trap, however). As it is, it predicts that the price level is constant in general equilibrium and unexpected growth shocks are deflationary in the short run.
