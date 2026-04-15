---
title: Musical chairs and Taylor rules
date: 2015-11-02T18:05:00.002-08:00
updated: 2015-11-03T16:30:04.986-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/11/musical-chairs-and-taylor-rules.html
---

Scott Sumner [recently reiterated](http://www.themoneyillusion.com/?p=31151) his musical chairs model. [John Handley](http://ramblingsofanamateureconomist.blogspot.com/2015/11/its-not-time-to-blow-up-new-keynesian.html) has the best take on that post. However, I thought I'd try to analyze the musical chairs model -- here it is ...

> _The Musical Chairs model:_ 

> _1\.  In the short run, employment fluctuations are driven by variations in the NGDP/Wage ratio._
>
> _2\.  Monetary policy drives NGDP, by influencing the supply and demand for base money._
>
> _3\.  Nominal wages are sticky in the short run, and hence NGDP shocks cause variations in employment in the same direction._
>
> _4\.  In the long run, wages are flexible and adjust to changes in NGDP. Unemployment returns to the natural rate (currently about 5% in the US.)_

So let's look at 1 and 3: (1) "In the short run, employment fluctuations are driven by variations in the NGDP/Wage ratio." (3) "Nominal wages are sticky in the short run, and hence NGDP shocks cause variations in employment in the same direction." This comes down to: In the short run, employment fluctuations are driven by variations in NGDP.



If prices are sticky along with wages, then the price level is slowly varying in the short run and therefore changes in RGDP are proportional to changes in NGDP and we can say: In the short run, employment fluctuations are driven by variations in RGDP. This is just [Okun's law](https://en.wikipedia.org/wiki/Okun%27s_law). So Sumner's 1 and 3 are just Okun's law.



Next we'll tackle number 4. Let's split 4 into two pieces. First piece first:

> _4a. In the long run, wages are flexible and adjust to changes in NGDP._

Since the short run changes in RGDP are already accounted for in the changes in employment (Sumner's 1 and 3), the primary change in long run NGDP must come from changes in the price level. This means 4a is really just the statement: Wages are a price.



Now for the second piece:

> _4b. Unemployment returns to the natural rate (currently about 5% in the US.)_

This is just an assumption that a unique equilibrium exists -- that the fluctuations in 1 and 3 are around some level.



Sumner's 2 is a bit vague as presented here, but in previous posts (I link to [here](http://informationtransfereconomics.blogspot.com/2015/01/is-this-market-monetarist-model.html)) Sumner says that the central bank sets expectations for NGDP with monetary policy. Instead of a single NGDP futures market target (his preferred policy), the Fed sets this with a combination of a _de facto_ inflation target, IOR and its internal forecasts of NGDP and inflation.



Additionally, Sumner says his model is consistent with rational expectations, therefore the expected value of NGDP at time period _t+1_ is the actual value of NGDP at time period _t+1_ plus an (unbiased) error. He also adds in the possibility of a systematic error term stemming from the difference between a targeting an ideal liquid NGDP futures market price/growth rate and whatever the central bank does in practice.



However, we can frame this in terms of a Taylor rule. We start with:



_i = π + r\* + a (π - π\*) + a (y - y\*)_



Sometimes the parameter _a_ is taken to be different for the two terms, but let's keep them the same. Now let's re-arrange:



_i - π - r\* = a (π + y - π\* - y\*)_



Using _n ≡ π + y_ and _n\* ≡ π\* + y\*_, we have



_i - π - r\* = a (n - n\*)_



The LHS is the difference between the short term nominal interest rate target and the equilibrium nominal interest rate _i\* = π + r\*_. We can call _r\*_ the equilibrium Wicksellian rate if we'd like. Let's define this deviation to be Sumner's systematic error (_SE_) plus random unbiased error _σ_:



_i - π - r\* ≡ SE + σ_



We don't really know what SE is (except in the case of a central bank targeting an NGDP futures market), so this is completely valid. We have:



_SE + σ = a (n - n\*)_



If _a = 1_, this is Sumner's equation (2) and (3) shown at [this link](http://www.themoneyillusion.com/?p=28215). That means monetary policy in Sumner's model can be represented as a Taylor rule that is always off (in the long run) by some amount SE unless the central bank targets an NGDP futures market.



This of course should make a lot of sense from Sumner's view. If a central bank perfectly targeted an NGDP futures market, then whatever the nominal interest rates was, it would be the equilibrium nominal interest rate. If there was some other less efficient monetary policy target, then that policy could be expressed as a deviation of the observed nominal interest rate from the equilibrium nominal interest rate (whatever it was).



The systematic error can be expressed as a function of the interest rate _SE = SE(i)_. Interest rates being "high" are a sign of loose monetary policy, rates being "low" are a sign of tight monetary policy (per Sumner's invocation of Milton Friedman). Therefore _SE_ should be positive when monetary policy is "loose", negative when it is "tight" and zero when it is 'right on' as per an NGDP futures market.



Putting this all together:



1\. Okun's law in the short run

2\. A Taylor rule: _i = π + r\* + (n - n\*) = π + r\* + SE(i)_

3\. Okun's law in the short run

4\. Wages are a price. There is an equilibrium in the labor market.



Overall, 1, 3 and 4 are basically true of any economic model (unless it is inconsistent with the data). Therefore you could probably represent Sumner's model as a New Keynesian model with a particular Taylor rule containing a systematic error term.



Note: _n - n\*_ is never zero unless you target an NGDP futures market, and on average _n - n\* = SE(i)._ This doesn't really pin the model down completely since _SE(i)_ is determined by some vague judgment calls about whether interest rates are "high" or "low" relative to where they "should be". However if someone (John Handley?) wanted to, someone could generically take _SE_ to be a negative value approximately equal to the current (nominal) output gap.

**Update 11/3/2015**

I wanted to make clearer that the point of this post was that Sumner's musical chairs model as described is so generic that it is likely any number of DSGE models (New Keynesian or otherwise) could fit the 4 listed characteristics while having wildly different policy implications.

Analogous to the need for at least three points to define a plane, we need more than these 4 characteristics to define an specific economic model.
