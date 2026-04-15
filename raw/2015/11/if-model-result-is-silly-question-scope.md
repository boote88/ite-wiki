---
title: "If a model result is silly, question the scope before questioning the model"
date: 2015-11-07T14:16:00.003-08:00
updated: 2015-11-07T14:16:52.580-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/11/if-model-result-is-silly-question-scope.html
---

Awhile ago I [wrote a bit](http://informationtransfereconomics.blogspot.com/2015/10/we-built-this-theory-on-scope-conditions.html) about scope conditions (or rather the lack of them) in economics. Nick Rowe provides us with a good illustration of this problem with [his post](http://worthwhile.typepad.com/worthwhile_canadian_initi/2015/11/drop-your-shovels-now-on-ending-fiscal-policy-in-nk-models.html) on the effects of a delay in ending fiscal policy in New Keynesian models. After reading his post, I commented:

> So wait: expectations of a delay in returning taxes to normal produce a change in expectations from an expected temporary change in tax rates to an expected permanent change in tax rates? 

> Can we add in rational expectations of an expected delay (obviously the government doesn't stop on a dime), so that people don't revise their expectations of a permanent/temporary tax change based on a delay in returning taxes to normal?

I was being a bit tongue in cheek; the result that an infinitesimal delay in the end of fiscal stimulus changing people's expectations of fiscal policy from temporary to permanent (and thus changing the sign and magnitude of the multiplier) is, in a word, silly. It's a bit like a child thinking that because class didn't let out at exactly 3pm, class will instead last (literally) forever.



You could cure this by saying that the theory is valid for government delays _dt_ << 1 so that _t + 1 ≈ t +dt  + 1_. But then, _that's the kind of thing that should have been a scope condition in the theory in the first place_.



Nick says:

> _How long is "one period"? It's as short as you want it to be._

No; that is false. For one thing it can't be shorter than the [Planck time](https://en.wikipedia.org/wiki/Planck_time). In general, it can't be shorter than the time it takes for light to traverse the entire country in question and return to that point (about 20 milliseconds for the US). It takes a few milliseconds for sensory input to register in our brains.



Less sarcastically, there is a definite period of time over which rational expectations can reasonably take hold. Quarterly NGDP data from the BEA isn't released until a month after the quarter ends. Budgets generally have annual cycles. It takes months (weeks, on rare occasions) to get bills through the US congress. There obviously exist timescales over which macroeconomic and government processes happen.



The New Keynesian theory should have something to say about what "one period" means (it seems to be quarterly from various models I've seen). It should also have some kind of estimate about the relative size of the timescale of government actions (_dt_) and the reaction of the macroeconomy (_dT_). Is _dt_ << _dT_? In that case Nick's analysis is silly, not the result. Nick implicitly assumes _dt_ \>> _dT_ (the macroeconomy reacts faster than the government). Maybe that is true (data would help), but it is obviously not a region of validity of the New Keynesian model -- we know this because you get silly results like sudden shifts between fiscal policy being contractionary or expansionary based on a one month delay in changing marginal tax rates.



It's a bit like saying electrodynamics predicts atoms will radiate all their energy and collapse so atoms must not exist. But electrodynamics is not valid for cases where _ћ ~ dx dp_; you need quantum mechanics. That is to say you need to understand the scope conditions of your theory. If you've found a problem, the problem could well be that you've applied the theory incorrectly.



Funny enough, this is very similar to the [mathiness issue between Paul Romer and Robert Lucas](http://informationtransfereconomics.blogspot.com/2015/05/the-irony-of-paul-romers-mathiness.html). The issue has the same form: Lucas's model is assumed to have infinite scope for its variables and Romer says Lucas's model has different limits if _1/β >> T_ and _1/β << T_ where _1/β_ is the timescale for innovation and _T_ is the observation time of the economy. Those two limits have different model interpretations: innovation is slow (so it never happens) versus innovation is fast (so it has already happened). These are entirely different kinds of worlds.



But no one in economics seems to care about scope \[1\]. Nick Rowe is just fine with the idea that the New Keynesian model is valid for both extremely fast and extremely slow changes in government fiscal policy. He says the extremely slow version gives us silly results so we shouldn't trust the extremely fast version either. 



But you can't extrapolate from one limit to the other. The more logical conclusion is that the extremely slow version is out of scope of the theory.



**Footnotes:**



\[1\] Don't just take my word for it; [Noah Smith says](http://noahpinionblog.blogspot.com/2015/09/a-bit-of-pushback-against-empirical-tide.html):

> _I have not seen economists spend much time thinking about domains of applicability (what physicists usually call "scope conditions"). But it's an important topic to think about._
