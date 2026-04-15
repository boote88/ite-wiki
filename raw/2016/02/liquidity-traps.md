---
title: Liquidity traps
date: 2016-02-27T13:59:00.002-08:00
updated: 2016-02-27T14:00:48.061-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/02/liquidity-traps.html
---

Paul Krugman has [a nice post](http://krugman.blogs.nytimes.com/2016/02/27/the-cases-for-public-investment/) with a concise definition of the liquidity trap:

> _... we are still in or near a liquidity trap, a situation in which cutting interest rates as far as possible isn’t enough to restore full employment._

Note that the current interest rate target range is 0.25-0.5%, so zero/low interest rates will only tend to be associated with a liquidity trap -- they aren't a requirement. He also provides a graph, but here's my improved version (nominal interest rates in black, real in red and the natural rate in blue):



![](<media/liquidity trap diagram.png>)



The idea behind the liquidity trap is that monetary policy can't get the red line down to the blue line, and is therefore unable to restore full employment. It doesn't actually matter where the red line (or black line) is -- just that the red line can't get there. QE is supposed to produce inflation, lowering the real interest rate ... but it doesn't seem to have worked that way in the real world (there was almost no effect on inflation).



So really there are two questions here:

1.  Why can't the central bank restore full employment?
2.  Why can't the central bank create inflation?

The standard liquidity trap answers are:

1.  The central bank cannot lower real interest rates to the natural rate.
2.  Inflation expectations are too well anchored (fear that the punch bowl will be taken away).

So what about models in the information transfer framework? There are a couple of ways to understand it with two different models. The first is the monetary information equilibrium model (that's described in [my paper on the arXiv](http://arxiv.org/abs/1510.02435)) where the effects of monetary policy depend on a parameter called the information transfer (IT) index _k_. The IT index _k_ is mostly controlled by the relative size of the economy (NGDP) to the monetary base (minus reserves). When _k >> 1_, the model behaves like a quantity theory of money. When _k ~ 1_, the model [behaves like an IS-LM model](http://informationtransfereconomics.blogspot.com/2016/02/the-is-lm-model-as-effective-theory-at.html) ... and when _k ≈ 1_, the price level loses its dependence on monetary factors. I describe this in terms of the IS-LM model [in this post](http://informationtransfereconomics.blogspot.com/2014/06/krugman-keynes-and-liquidity-trap.html), and in terms of interest rates [in this post](http://informationtransfereconomics.blogspot.com/2014/03/the-effects-that-move-interest-rates.html) (see [here](http://informationtransfereconomics.blogspot.com/2014/03/the-islm-model-again.html) for the connection between those two posts). Since the result largely depends on the IT index _k_, the reason why _k ≈ 1_ becomes the answers to the two questions. The simplest description is that _k_ represents a Lagrange multiplier (like temperature in thermodynamics) and the maximum entropy distribution associated with _k_ near 1 consists of more lower growth and lower inflation states: larger economies are colder economies. I discuss this in more detail [here](http://informationtransfereconomics.blogspot.com/2014/09/the-great-stagnation-information.html).



So the monetary information equilibrium model answers are:

1.  Monetary policy does not effectively control NGDP or inflation when _k ≈ 1_.
2.  There are more ways to configure a large economy out of many low growth/low inflation states than a few high growth/high inflation states. The result is low inflation and _k → 1_ over time (all advanced economies tend toward this state).

A second way to address this in the information transfer framework is with the what I (with a bit of snark) called a [quantity theory of labor](http://informationtransfereconomics.blogspot.com/2016/01/its-people-economy-is-made-out-of-people.html). In this model, there is no direct monetary control over NGDP or inflation -- both follow from the size of the civilian labor force. Our answers in this case are simple:

1.  The central bank doesn't control full employment.
2.  The central bank doesn't control inflation. Inflation falls for demographic reasons.

That first answer is actually a pretty good explanation for the [remarkable regularity in employment recoveries](http://informationtransfereconomics.blogspot.com/2014/07/remarkable-recovery-regularity-and.html) -- if the central bank isn't involved, then the different central bank policies from the 1940s to the 2010s shouldn't have shown an impact on employment. In a sense, I produced this model as a _reductio ad absurdum_. It is fairly empirically successful for several countries ([here](http://informationtransfereconomics.blogspot.com/2016/01/is-cpi-information-theoretic-measure-of.html)), so represents a real Occam's razor: is your model more empirically accurate than this quantity theory of labor? No? Well, it sucks to be your model, then.



Now you may ask: _Why do you have two models? Which one is it??!_ This also has two answers:

1.  I am a scientist and am capable of holding more than one model in my head at once.
2.  The labor model may well still be the reason why larger economies are colder economies (or the monetary model is what is behind the size of the labor force)
