---
title: Supply and demand and science
date: 2017-12-04T14:30:00.000-08:00
updated: 2017-12-04T14:59:15.287-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/12/supply-and-demand-and-science.html
---

![Sometimes recognizing a symmetry is the biggest step.](media/Noether_-petite_image-.png)



Sometimes when you give a seminar or teach a class a student or attendee brings up a point that perfectly sets you up to explain your topic. [A few tweets](https://twitter.com/infotranecon/status/937773909209780224) from @UnlearningEcon and Steve Roth gave me this opportunity today:

> _UE: Confused by the amount of times it is claimed demand and supply has loads of empirical evidence behind it when I've barely seen any_ 

> _UE: Naming a couple of obvious insights or point estimates is not sufficient to prove the full model! Can somebody give me an actual falsifiable test, please?_ 

> _UE: Conclusion: demand-supply is largely an article of faith which people 'prove' with a couple of casual observations. Science!_ 

> _SR: Thing is you can't measure demand (desire) and supply (willingness) to buy/sell — necessarily, across a range of prices at a point in time. Only observe the P/Q where they meet. Why S/D diagrams are always dimensionless._

There's an almost perfect analogy here with the concept of "force" in physics. Force _F_, often described using the equation _F = m a_ \[1\] or better _F = dp/dt_, is actually a definition. That is to say it's _F ≡ dp/dt_. At the time of Newton \[2\], it was an article of faith. It was an article of faith that organized a bunch of disparate empirical "point estimates" and insights from Kepler and Galileo.



That is all to say Newton represents more of a statement of "looking at it this way, it's much simpler" than an application of the oversimplified "scientific method" we all were taught in school that involves an hypothesis, collecting data, and using that data to confirm or reject the hypothesis. Unfortunately contributions to science like Newton's aren't easily reproduced in classrooms so most people end up thinking the hypothesis testing with data is all there is. Note that Einstein's famous contributions were like Newton's in the sense that the organized a bunch of disparate empirical point estimates (in this case they were deviations from a Newtonian world).



Though Newton and Einstein get all the plaudits, both of their big contributions are really specific instances of what is probably one of the greatest contributions to physics of all time: [Noether's theorem](https://en.wikipedia.org/wiki/Noether%27s_theorem). Emmy Noether was asked by David Hilbert about energy conservation in General Relativity, but she ended up proving the more general result that conservation laws are consequences of symmetry principles. Newton's symmetry was [Galilean invariance](https://en.wikipedia.org/wiki/Galilean_invariance); Einstein's were [Lorentz covariance](https://en.wikipedia.org/wiki/Lorentz_covariance) (special relativity) and [general covariance](https://en.wikipedia.org/wiki/General_covariance) (general relativity). Newton's laws are really just a consequence of conservation of momentum.



That gives us a really good way to think about Newton-like contributions to science: they involve recognizing (or steps towards recognizing) general symmetry principles.



What does this have to do with supply and demand?



This is where Steve Roth's tweet and the work on this blog comes in. Supply and demand relationships seem to be a consequence of scale invariance (the dimensionlessness Steve points out) of information equilibrium \[3\]. In fact, realizing supply and demand is a consequence of the scale invariance encapsulated by the information equilibrium condition gives us a handle on [the scope conditions](https://informationtransfereconomics.blogspot.com/2017/04/its-production-input-no-its-market-good.html) — where we should expect supply and demand to fail. And since those scope conditions (which involve e.g. changing supply much faster than demand can react) can easily fail in real-world scenarios, we shouldn't expect supply and demand as a general theory to always be observed and empirically validated. Good examples are labor and housing markets where it is really hard to make supply change faster than demand (in the former case because adding workers adds wage earners adding demand, and in the latter case because it is impossible to add housing units fast enough). What we should expect is that when the right conditions are in effect, supply and demand will be a useful way to make predictions. One of my favorites examples uses [_Magic, the Gathering_ cards](http://informationtransfereconomics.blogspot.com/2016/04/simulations-with-supply-demand-and.html).


Yes, I realize I have obliquely implied that I might be the Isaac Newton of economics \[4\]. But that isn't the main point I am trying to make here. I'm trying to show how attempts at "falsification" aren't the only way to proceed in science. Sometimes useful definitions help clarify disparate insights and point estimates without being directly falsifiable. The information equilibrium approach is one attempt at understanding the scope conditions of supply and demand. There might be other (better) ones. Without scope conditions however, supply and demand would be either falsified (since counterexamples exist) or unfalsifiable (defined in such a way as to be unobservable \[5\]).




**Footnotes**


\[1\] You may think that mass and acceleration are pretty good direct observables making force an empirical observation. While acceleration is measurable, mass is problematic given that what we really "measure" is force (weight) in a gravitational field (also posited by Newton). Sure, this cancels on a balance scale (_m₁ g = m₂ g → m₁ = m₂_), but trying to untangle the epistemological mess is best left to arguments over beer.



\[2\] Actually Newton's Lex II was a bit vague:

> _Lex II: Mutationem motus proportionalem esse vi motrici impressae, et fieri secundum lineam rectam qua vis illa imprimitur._

A somewhat direct translation is:

> _Second Law: The alteration of motion is ever proportional to the motive force impressed; and is made in the direction of the right line in which that force is impressed._

The modern understanding is:

> _Second Law: The change of momentum of a body is proportional to the impulse impressed on the body, and happens along the straight line on which that impulse is impressed._

Where momentum and impulse now have very specific definitions as opposed to "motive force" and "motion". This is best interpreted mathematically as



_**I** ≡ Δ**p**_



where _**I**_ is impulse and _**p**_ is the momentum vector. The instantaneous force is (via the fundamental theorem of calculus, therefore no assumptions of relationships in the world)



_**I** = ∫ dt **F**_



_**F** ≡ d**p**/dt_



where p is the momentum vector. The alteration of "motion" (i.e. momentum) is Δp (or infinitesimal dp), and the rest of the definition says that the **_F_** vector (and impulse vector **_I_**) is parallel to the **_p_** vector. Newton would have writen in his own notes something like _f = ẋ_ using his fluxions (i.e. _f = dx/dt_).



\[3\] I've talked about this on multiple occasions ([here](https://informationtransfereconomics.blogspot.com/2015/12/money-is-that-which-is-conserved-via.html), [here](https://informationtransfereconomics.blogspot.com/2016/10/invariance-under-inversion.html), [here](http://informationtransfereconomics.blogspot.com/2016/03/effective-information-equilibrium-theory.html), or [here](https://informationtransfereconomics.blogspot.com/2017/02/invariance-and-deep-properties.html)).



\[4\] At the rate at which new ideas become incorporated into economic theory, I will probably have been dead for decades and someone else (with the proper credentials) will have independently come up with an equivalent framework.



\[5\] People often make the point that demand isn't directly observable (or as Steve Roth says, neither supply or demand are observable). My tweet-length retort to this is that the wavefunction in quantum mechanics isn't directly observable either. In fact, given the scale invariance of the information equilibrium condition, we actually have the freedom to re-define demand as twice or half any given value. This is analogous to what is called [gauge freedom](https://en.wikipedia.org/wiki/Gauge_fixing) in physics (a result of the gauge symmetry). The electric and magnetic potentials are only defined up to a "gauge transformation" and are therefore not directly observable.



To me, this is a very satisfying way to think about demand. It is not a direct observable, but we can compute things with a particular value knowing that we can scale it to any possible value we want (at least if we are careful not to break the scale invariance in the same way you try not to break the gauge invariance in gauge theories). Nominal GDP might be an incomplete measure of aggregate demand, but so long as aggregate demand is roughly proportional to NGDP we can proceed. What is important is whether the outputs of the theory are empirically accurate, such as [this example for the labor market](http://informationtransfereconomics.blogspot.com/2017/03/the-quantity-theory-of-labor-and.html).
