---
title: On limits
date: 2015-11-08T14:53:00.001-08:00
updated: 2016-01-17T14:16:42.302-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/11/on-limits.html
---

One thing to keep in mind when using mathematics to describe physical reality is that you have to be very careful about taking limits. In pure mathematics it's generally acceptable to send a variable off to infinity, _m → ∞_. If you are using mathematics to describe physical reality, then _m_ might just have 'dimensions' (aka 'units') so sending a dimension**ful** number off to dimension**less** infinity (or zero) can give you weird results.



Generally, if, say, _m_ is a mass (with units of kilograms) the only way you can send it off to infinity or zero is to have another scale (say, another mass _M_ with units of kilograms) to compare it to. You can send _m/M → ∞_ or _m/M → 0_ ... or better yet, as physicists tend to put it: _m/M_ \>> 1 or _m/M_ << 1 (i.e. _m_ \>> _M_ or _m_ << _M_).



I do my best to be very careful about this (I probably have made some mistakes). However, I don't think economists care about this _at all_. For example, [Paul Romer and Robert Lucas](http://informationtransfereconomics.blogspot.com/2015/05/the-irony-of-paul-romers-mathiness.html) both take limits where time _T_ and a time scale (_1/β,_ where _β_ is a rate) go off to infinity simultaneously. In pure math, this produces an issue of almost uniform convergence; however, if you're using math to describe physical reality then it is nonsense to send these two dimensionful scales off to dimensionless infinity simultaneously. A [(possible, since it was EJR) econ student](http://informationtransfereconomics.blogspot.com/2015/05/another-mistake-from-romer.html) also had no idea about this, which makes me think this attitude is very widespread. The only sensible thing you can do is look at _T β_ >> 1 or _T β_ << 1. Other limits are **nonsense**.



Nick Rowe doesn't seem to have a problem with sending dimensionful numbers to dimensionless infinity either (which [I wrote about yesterday](http://informationtransfereconomics.blogspot.com/2015/11/if-model-result-is-silly-question-scope.html)), sending time steps _dT_ to zero when he should really be looking at the relationship to the other physical scale in his theory -- the delay in the onset of the end of fiscal stimulus _dt_. This carelessness creates nonsense results.



Noah Smith, John Cochrane and Michael Woodford (see [Noah](http://noahpinionblog.blogspot.com/2015/07/woodford-vs-neo-fisherians.html) for one-stop shopping, and see slide 30 of [Woodford's presentation](http://www.riksbank.se/Documents/Forskning/Konferenser_seminarier/2015/Woodford.pdf) \[pdf\] \[1\]) all make this same error when talking about neo-Fisherism in terms of permanent rate pegs and expectations infinitely far in the future. And if Woodford is considered the Ed Witten of economics (per Noah in the link above), that doesn't bode well for _any_ economist knowing about how to use math to describe reality. It also makes me think the whole neo-Fisherite view may just be an artefact of poor dimensional analysis (something that I will be looking into ... )





The problem is that economists don't see this as an issue. And they don't seem [to take kindly](https://orderstatistic.wordpress.com/2014/03/21/why-are-physicists-drawn-to-economics/) to physicists trying to tell them what to do. When Chris House says "\[Physicists'\] mathematical abilities are actually not that much better than most economists (if they are better at all)" my spidey sense starts suggesting the reason is probably [Dunning-Kruger](https://en.wikipedia.org/wiki/Dunning%E2%80%93Kruger_effect) \[2\]. The second paper on his list on [his website](http://www-personal.umich.edu/~chouse/) ("Layoffs, Lemons and Temps") has a individual firms with "production function\[s\] with the usual properties" which in the footnote contains two nonsense limits where the number of workers _n_ goes to zero and infinity ... treated as if it's an everyday assumption (even relegated to a footnote). They are in fact everyday assumptions in economics (called the [Inada conditions](https://en.wikipedia.org/wiki/Inada_conditions))! The only sensible limits in that case would be (for instance) _n/N_ >> 1 or _n/N_ << 1 where _N_ is the number of firms (in English, a few firms have a large number of workers versus many firms have a small number of workers). Another way would be to compare to the population size (does everyone work for a few companies, _n/P ~_ 1, or do very few people work for the same company, _n/P_ << 1). I don't think this impacts the results of House's paper, but it is careless mathematics. At least the Inada conditions are described in terms of a pure mathematical function with dimensionless inputs.



**Update 11/9/2015:**


Even if the reason for finite number of belief updates in footnote \[1\] is that they cost some amount of money _dm_ (or people are just _n_\-smart), you still can't send dimensionful time _T_ to dimensionless infinity when things happen in your model that take finite amount of time (or have some finite timescale such as the decaying functions on Woodford's slide 26). The version where revisions take a finite time _dt_ is just one possible way to make the limit make sense -- not necessarily the only way. It's sort of like the example above with Chris House's paper where I used _N_ and _P_. The issue is that there has to be **_some_** scale that the number of workers _n_ is large compared to be it the number of firms or the total population, and there has to be some timescale that time _T_ is long compared to.



**Footnotes:**


\[1\] Woodford takes two limits of _n_ → ∞ and  _T_ → ∞ where _n_ is the number of 'belief revisions'; these revisions obviously take some finite time _dt_ (or else you could do an infinite number of revisions instantaneously), so the only sensible (in the sense of using math to describe reality) limits are _n dt/T_ >> 1 or _n dt/T_ << 1. The first says that belief revisions take longer than the time horizon of the interest rate peg (interest rates stop being pegged before you fully revise your beliefs -- which doesn't seem like a very long peg); the second says you revise your beliefs to a high order before the interest rate peg ends (which actually makes more sense). The limits that Woodford takes (_n dt_ → ∞ and _T_ → ∞ simultaneously, in both orders) don't make any sense.



\[2\] I've sort of come through the rabbit hole on this one. In my first forays into econ, I basically thought economists were just fine with math. I tended to defend econ from usurping physicists ([here](http://informationtransfereconomics.blogspot.com/2014/04/economics-is-neither-physics-nor.html) and [here](http://informationtransfereconomics.blogspot.com/2013/08/econophysics-for-fun-and-profit.html)). But these limit problems (in  a paper by preeminent economist Michael Woodford, no less) coupled with Paul Romer's diatribe against mathiness and [Nick Rowe on the RCK model](http://informationtransfereconomics.blogspot.com/2015/06/the-importance-of-transversality.html) makes me think that maybe economists don't really know what they are talking about.
