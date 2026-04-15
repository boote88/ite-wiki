---
title: "Euler's theorem, rival inputs and distinguishable particles"
date: 2015-06-12T18:57:00.002-07:00
updated: 2016-09-01T20:44:57.004-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/06/eulers-theorem-rival-inputs-and.html
---

> Update: [Romer responded](http://paulromer.net/reactions-to-denialism/) to Waldmann while I was still writing this post. I added comments below in brackets. Overall

[Paul Romer](http://paulromer.net/eulers-theorem-deniers/) seems to think Euler's theorem is like the second law of thermodynamics. [Robert Waldmann](http://rjwaldmann.blogspot.com/2015/06/thoughts-on-eulers-theorem-denialism.html) put it more succinctly than I ever could \[and Romer agrees that the analogy wasn't complete, see the response for more\]:

> _I find this odd, because Euler's theorem is math while the second law of thermodynamics is a scientific hypothesis_

A minor quibble: I would have said _successful_ scientific hypothesis ... it follows from similar assumptions to the ones this blog makes about economics, by the way. Except humans can make [coordinated decisions](http://informationtransfereconomics.blogspot.com/2014/10/coordination-costs-money-causes.html) (panic, herd, etc) which causes economic entropy to fall much more than would be allowed by the [fluctuation theorem](http://en.wikipedia.org/wiki/Fluctuation_theorem) (that is to say, the second law of thermodynamics is actually violated in small systems, but the violations in the second law of "econo-dynamics" are too big to be a result of something like the fluctuation theorem).



The real thing that Romer says Andolfatto violates is the idea that if you double all rival inputs, output should double. \[Romer points this out again in his response.\] Romer points to [Vollrath's very good explanation](https://growthecon.wordpress.com/2015/06/05/market-power-versus-price-taking-in-economic-growth/) of the basic logic. This seems completely reasonable, but is wrong in general. 



Here's an example. Let's say the only industry on Earth involves searching sequenced DNA for markers. Everyone does this with _X_ computers and produces _Y_ output (locations of DNA markers). These computers are rival, there is perfect competition and the algorithms ("ideas") are all the same. Typically a good parallel algorithm follows Euler's theorem -- you double the number of computers, you double output. However, there are actually two massive [super-linear speed-ups](http://en.wikipedia.org/wiki/Speedup#Super-linear_speedup) you can get when increasing the number of computers -- when the size of the problem becomes less than the total RAM available on all of the computers together and another when the size of the problem fits into the total memory cache (I think it is it L4 cache). The number of disk accesses (or RAM accesses) decreases as you approach this amount of memory, and during this transition from many to zero accesses _the speed of your calculation goes up faster than linearly_ and therefore your output goes up faster than linearly. For some _X_, _2X_ computers produces _(2 + δ)Y_ output (because it does it faster). And _δ_ can be huge -- _δ ~_ 10 or 100! A computer architecture that has a memory hierarchy like this can be super-linear across several orders of magnitude. Yes, if you allow for _α >> 1, X → α X_ does result in _Y → α Y_, but such a large _α_ is not necessarily empirically relevant.



The issue here is that Euler's theorem assumes you're doubling something that's non-interacting. The computers in the example above interact: their memory structures combine to open up a path to greater efficiency that isn't available for smaller _X_.



Actually, you can get an interesting violation of "constant returns to scale" in physics -- it's called [Gibb's paradox](https://en.wikipedia.org/wiki/Gibbs_paradox) and it refers to entropy failing to be extensive (the physics term for constant returns to scale) using a naive entropy formula. Take two boxes and their entropy is twice the entropy of one box (call it _2S_):



![](<media/entropy and eulers theorem 2.png>)

Putting these boxes together raises the entropy by a small amount to _(2+δ)S_ according to the naive formula (that I use again in the graph at the bottom of this post).



![](<media/entropy and eulers theorem 1.png>)

Separating them reduces the entropy back to _2S_ -- in violation of the second law!



![](<media/entropy and eulers theorem 2-15396c52.png>)

The resolution of this paradox for the physical system is that the formula fails to take into account the particles are indistinguishable -- you can't tell if a Helium atom that starting in the left box is in the left or right box when you separate them. Making that correction makes the entropy extensive (i.e. restores constant returns to scale).



However! In economics, with the exception of money (and similar abstract assets), we don't have indistinguishable particles. Amy is different from Bill, so you can tell when their companies merge and then split up (like the pictures above) who works for which company. In physics you can [in principle](https://en.wikipedia.org/wiki/Landauer%27s_principle) find this information out about the atoms, however it costs energy to do so and ends up raising the temperature of the system to identify every atom. In economics, this information is pretty cheap to get.



Additionally, the formulas for thermodynamics are all evaluated at large values of the number of particles (_N_). Really large, like 10²³. However, for large but more **economically relevant** scales (10⁶), we still haven't reached the limits ... in fact, if you look at the [entropy function](http://informationtransfereconomics.blogspot.com/2014/09/the-economic-combinatorial-problem.html) _log N! ≈ N log N - N_ you'd have "increasing returns to scale" with the sum of the production function exponents being > 1:



![](<media/entropy and eulers theorem.png>)

What if that is all secular stagnation is? An approach to the limit where economics is extensive, there are constant returns to scale for rival inputs and all economic growth ... halts. Maybe growth economists are studying the eventual future of economics ...



Anyway, in conclusion, the things that can allow increasing returns to scale are interacting rival inputs, distinguishable rival inputs and finite rival inputs. If you think of rival inputs (capital) as an infinite frictionless fluid of indistinguishable molecules, then, yes, Romer seems to be basically correct. However competitive equilibrium with price taking makes only one of these assumptions (the infinite one) -- in particular, it doesn't make the indistinguishable assumption. That's an important one if [entropy is related to output](http://informationtransfereconomics.blogspot.com/2014/10/coordination-costs-money-causes.html). Amy and Bill could be identically productive, the same in every way. However, just allowing for them to have names means that the entropy (and hence output) of Amy, Bill, Catherine and Dave (who are also the same as Amy and Bill) can be more than just twice the output of Amy and Bill.
