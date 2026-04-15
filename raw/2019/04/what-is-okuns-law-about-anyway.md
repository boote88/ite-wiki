---
title: "What is Okun's law about, anyway?"
date: 2019-04-05T16:27:00.001-07:00
updated: 2019-10-11T12:56:41.666-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2019/04/what-is-okuns-law-about-anyway.html
---

In my iconoclastic way, I've referred to any relationship between employment and output as "Okun's law" (e.g. [here](https://informationtransfereconomics.blogspot.com/2018/03/okuns-law-and-labor-force.html) and [here](https://informationtransfereconomics.blogspot.com/2017/03/the-quantity-theory-of-labor-and.html)). In the first of those links, I noted that "Okun's law" understood that way was at best an approximation. However, [a few weeks ago Britonomist on Twitter](https://twitter.com/Britonomist/status/1111418722718121986) piqued my interest in the original form by saying:

> _I don’t remember being taught any explanation of why c in Okum’s law was 2 for instance, but I would have found the subject very dull if it was just memorising various estimated parameters without any deeper explanation._

I set off to try and show why _c_ = 2 using the dynamic information equilibrium model. What I learned was that the interesting part of Okun's law is almost entirely about the one or two quarters spent in recession. If we take the form _ΔY/Y = k − c Δu_ where the change is over a year, and the typical coefficients where _k_ \= 3% and _c_ \= 2, we can show a pretty good "explanation" of _k_



_k__e_γ_−__c__e_α_ū_


where γ ≈  2.4% [is the dynamic equilibrium for RGDP growth](https://informationtransfereconomics.blogspot.com/2018/01/24-growth-forever.html) (i.e. the difference between the dynamic equilibria for NGDP = 3.8% and the GDP deflator = 1.4%), α ≈ − 8.3% is [the dynamic equilibrium for the unemployment rate](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3094757), and _ū_ is the average unemployment rate over the period (~ 5.9%). This gives us


_k_ ≈ 2.4% _−_ 2 ( _−_ 8.3%) × 5.9% = 3.4%

_k__−_  _−_


That _ū_ shows up because the RHS of Okun's law is in terms of the change in the unemployment rate _Δu_ rather than _Δu/u ≈_ _Δu/ū_ (otherwise, we'd have a direct relationship between dynamic equilibria). The exponentials convert a logarithmic growth rate (dynamic equilibria) to a yearly change.

The truth is that we get _k_ approximately right for _c_ = 1, 2, or 1.4 (per the best fit later, and these values give 2.9%, 3.4% and 3.1%, respectively) as that term is about a 10-20% correction. The main driver behind the value of _c_ is the recessions:

![](<media/DIEM okuns law coefficients.png>)
In the figure, I show year over year RGDP growth (gray) along with the DIEM model for the unemployment rate (purple). Okun's law is a transformation of the latter, and I show both the traditional coefficients (red) and the best fit over the data shown (dashed red). I also show the dynamic equilibria (dashed purple for the unemployment rate and dashed gray for RGDP). You can see that the _k_\-value is mostly about the constant levels between non-equilibrium shocks (vertical lines) — it turns out the _c_\-value is mostly about the shocks themselves.

The peak of shock _n_ in (_d/dt_) log _u(t)_ is _aₙ_/(4 _bₙ_) above the dynamic equilibrium α using the logistic function ansatz of step height _aₙ_ and width _bₙ_. But again, we have that factor of _ū_ to account for in relating _Δu_ rather than _Δu/u ≈_ _Δu/ū_, which means that the shocks to unemployment are about 1/_ū_ = 16.9 times bigger than the shocks to real GDP if _c_ = 1. If _c_ = 2, we have about a factor of 8.4. [This turns out to be a better empirical fit](https://fred.stlouisfed.org/graph/?g=nxn5) (at least for more recent years):

![](<media/fredgraph -1-.png>)
So we end up with c = 2 because the shocks to the unemployment rate are about 8 times bigger than the shocks to real GDP and the average unemployment rate is about 5-6%. This is all to say that _c_ = 2 is essentially a fluke of scaling two correlated relative rates of change. If we use that scaling factor of 8.4 to try and match (the log of) the unemployment rate and RGDP with a dynamic equilibrium subtracted (the correct frame), we can match the size of the steps without changing the scaling factor, but we have to move around the dynamic equilibrium and the offset (click to enlarge):

![](<media/DIEM okuns law coefficients 1.png>)![](<media/DIEM okuns law coefficients 2.png>)

![](<media/DIEM okuns law coefficients 3.png>)
I had to change the dynamic equilibrium for _Y_ \= RGDP (γ) from 5% to 4% and eventually down to 2.4% to get these to line up (this is due to the demographic shift of the 1960s and 70s). Taking the rates of change _ΔY_ and _Δu_ removes the offset, but leaves the changing dynamic equilibrium which shows up in the graphic above as the size of the shocks not exactly matching.

Again, this makes Okun's law seem more like scaling two correlated series to match each other than any structural relationship between variables. Effectively, big recessions have big drops in RGDP and big spikes in unemployment while small recessions have small drops in RGDP and small spikes in unemployment. The fact that _c_ = 2 means this proportional relationship hasn't changed very much over the past few decades (it's actually risen from about 1 in the 50s and 60s to about 2 in the 90s), but the actual value of _c_ is an empirical point estimate. Mainly, _c_ is based on the relative size of recession shocks to real output compared to recession shocks to the unemployment rate.
