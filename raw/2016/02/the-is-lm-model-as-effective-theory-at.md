---
title: The IS-LM model as an effective theory at low inflation
date: 2016-02-04T18:00:00.000-08:00
updated: 2017-03-28T17:31:26.128-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/02/the-is-lm-model-as-effective-theory-at.html
---

No one seems to like the poor old IS-LM model except Paul Krugman. I thought I'd defend it as an effective macro theory. What does that mean? It means it is a theory that operates given a certain scope. For IS-LM, assuming the IT model is the "true" theory, that scope is low inflation. Here's how it works:



Start with the AD-AS model (with aggregate demand aka nominal output _N_ and aggregate supply _S_), and [introduce money](http://informationtransfereconomics.blogspot.com/2015/05/money-defined-as-information-mediation.html) (_M_)



_N ⇄ S_

_N ⇄ M ⇄ S_



_P : N ⇄ M_


The _P_ just names the abstract price (the price level) and the above notation means:



_P ≡ dN/dM = k (N/M)_



_N ~ Mᵏ_

_P ~ k Mᵏ⁻¹_


That should be a k - 1 in the exponent, not _(M^k)^-1_. If _k ≈ 2_, then we have _P ~ M_ (a "quantity theory of money" where inflation is money growth). If _k ≈ 1_ (one way of stating our scope condition), then



_N ~ M_

_P ~ constant_


so that inflation _π ≈ 0_ (another way of stating our scope condition \[1\]). If inflation is "small", then



_N ~ Y_


where _Y_ is real output. Now let's introduce another set of information equilibrium relationships



_p : N ⇄ MB_
_i ⇄ p_


where _MB_ is the monetary base, _p_ is the abstract price of money and _i_ is the nominal (short term) interest rate. If _π ≈ 0_, then we can write this as:



_p : Y ⇄ MB_
_r ⇄ p_


using _N ~ Y_ and _i ~ r_ where _r_ is the real interest rate. The differential equations associated with this pair of information equilibrium relationships has a similar solution in general equilibrium to the one above, but I'll write it differently:



_log(r) = c log(b Y/MB)_


Now which variables do you think will react the fastest to monetary expansion? I'd go with the monetary base and the interest rate, rather than real output. That puts us on the partial equilibrium solution where _Y_ "moves last" (in economics parlance). In physics terms, this is analogous to an isothermal expansion of an ideal gas (an 'iso-output' expansion of an economy) that looks like this:



![](<media/ISLM -diagram-.png>)![](<media/ISLM 2 -diagram-.png>)

Those angle brackets mean ensemble averages ([weighted average over random markets](http://informationtransfereconomics.blogspot.com/2014/06/the-macroeconomic-partition-function.html)).



The interest rate falls and the monetary base expands from _MB₁_ to _MB₂_. Note at this level of effective theory, it is not important which one causes the other one -- increasing the base lowers interest rates or lowering interest rates expands the base. As _Y_ rises, interest rates will come back up and equation (1) will hold -- general equilibrium restored.



What about fiscal policy? That's the second diagram above. In that case, the central bank "moves last". Fiscal expansion should take us from _Y₁_ to _Y₂_, but if the central bank didn't let rates rise or the base expand, you could end up back where you started. This is the basic monetary offset picture that happens when inflation is low and nominal (and real) interest rates are positive.



That captures most of the mechanics of the IS-LM model; you could rewrite this in terms of investment if you wanted (as I do [here](http://informationtransfereconomics.blogspot.com/2014/03/the-islm-model-again.html)). And there is a bit more to the details of how it works, but the theories are roughly isomorphic to each other.



Paul Krugman points out in the liquidity trap argument everything changes at the zero lower bound (or basically, anytime interest rates are very low ... remember we're still in a limit where inflation is very low as well). This is the limit where _r ≈ 0⁺_. Here we have a different-looking pair of diagrams:



![](<media/ISLM -diagram- zero 1.png>)![](<media/ISLM -diagram- zero 2.png>)

The general idea is the same, but the magnitudes are very different. A large expansion of the base drops your interest rate to zero without moving output very far to the right (monetary expansion is ineffective). A large fiscal expansion can happen without large movement in the monetary base (i.e. monetary offset doesn't work). In this case, we have a model that captures the essence of the liquidity trap.



Recall that we built this out of the AD-AS model, but we did it by restricting the scope to _r ≈ 0⁺_, _π ≈ 0_ (or just _π ≈ 0_ for the IS-LM model) \[1\]. This doesn't mean this model is right, but it does mean if you are using the AD-AS model where inflation is low and interest rates are low, then you are effectively using the IS-LM model (if you are doing it correctly).



And since the above model does pretty well empirically (see [the paper](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html) or the [forecasts](http://informationtransfereconomics.blogspot.com/2015/09/prediction-aggregation-redux.html)), it means that **any theory that describes the data** (when _π ≈ 0_) **will also be approximated by the IS-LM model.**

An analogy: since Newton's inverse square law describes the orbits of planets fairly well, any theory that describes the orbits of planets fairly well will be approximated by Newton's inverse square law. This is actually true of general relativity (which reduces to Newton's inverse square law) and will also be true of the fundamental quantum theory of gravity -- should it exist.



...



Footnotes



\[1\] Strictly speaking, these inflation and interest rates are small compared to some other scale in the theory, in this case we could use the average growth rate of the monetary base (minus reserves) _r << μ_, _π << μ_. In the US, this has been about 7% per year. Inflation is about 1-1.5% and (short term, nominal) interest rates are 0.3-0.5% -- both are less than 7% and that gives us an idea that the error in this model could be ~10% ... i.e. 0.005/0.07 ~ 0.01/0.07 ~ 0.1.
