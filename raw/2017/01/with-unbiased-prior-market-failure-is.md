---
title: "With an unbiased prior, market failure is the most likely outcome"
date: 2017-01-10T19:58:00.002-08:00
updated: 2017-01-10T19:58:18.209-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/01/with-unbiased-prior-market-failure-is.html
---

Noah Smith has [a short article at Bloomberg View](https://www.bloomberg.com/view/articles/2017-01-09/sometimes-it-s-hard-to-explain-market-failures) about how free market proponents make a play for the null hypothesis; he convincingly argues that maybe economists should be more amenable to not having to prove market failure.



I'd like to point out that using the information transfer framework while assuming we know nothing about the situation, market failure should be our default hypothesis. That's because generally in a market where _A_ is exchanged for _B_, we can at best assume the information entropy of the distribution of _A_ is a bound on the information about that distribution received at _B_. Symbolically:



_I(A) ≥ I(B)_



The intuition here is that if you send a signal about a change \[0\] in _A_ to which _B_ should respond (e.g. to clear excess supply or demand that results), at best _B_ can receive all of the information in the signal. Given noise, irrational human actions, or sudden drops in the information content of the distributions (e.g. everyone wants to sell the same asset so that it takes less information to describe the aggregate ‒ everyone wants to sell ‒ than to describe in a typical case ‒ Alice wants to buy, Bob wants to sell, Carol wants to sell, David wants to sell, Edna wants to buy, etc \[1\]).



If we were completely ignorant about what is happening, then we'd expect



_I(A) > I(B)_



most of the time. The math can still be useful here; the resulting differential equation \[2\] for [information equilibrium](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html) (ideal information transfer) ‒ i.e. _I(A) = I(B)_ ‒ [becomes a bound for _I(A) > I(B)_](http://informationtransfereconomics.blogspot.com/2016/06/gronwalls-inequality-and-information.html). However, we really have to accept we know a lot less than we might think.



In a sense, in order to say that markets are working, you first have to show they are working \[3\]. This will involve empirical tests; my favorite are predictions [like this one](http://informationtransfereconomics.blogspot.com/2015/08/comparison-of-interest-rate-predictions.html):


![](<media/ITM interest rates and price level -prediction comparison-.png>)

Predictions are my favorite because it's the one way you can be absolutely sure you have data you haven't trained your model on is when that data comes from the future. Actually, long term interest rates are one of the [more ideal markets out there](http://informationtransfereconomics.blogspot.com/2016/10/3d-visualizations-of-interest-rate-model.html) ‒ at least so far. [Exchange rates](http://informationtransfereconomics.blogspot.com/2015/06/exchange-rates-and-irrational-markets.html) (forex markets) might be one of the worst.



There are a lot more ways a market can fail than it can work. The more surprising fact is that there are working markets. When some people say that governments are responsible for functioning markets, this is one of the reasons I'm inclined to believe it.



...



**Footnotes**



\[0\] You can actually derive the [information equilibrium condition](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html) by assuming an infinitesimally small signal _dA_ and the infinitesimal response _dB_.



\[1\] Think of this as the sequence 00000... vs 10001... so that the second one requires more information to specify. A constant sequence (a light that's always on or off) carries no information.



\[2\] The interesting part is that this differential equation [was almost written down by Irving Fisher in 1892](http://informationtransfereconomics.blogspot.com/2014/08/fishers-proto-information-transfer.html).



\[3\] The micro- and macro-economic theory I've been developing on this blog actually grew out of an attempt to understand whether prediction markets were working for [a vastly different application](https://en.wikipedia.org/wiki/Aggregative_Contingent_Estimation). The answer seems to be as stated above: [probably not](http://informationtransfereconomics.blogspot.com/2015/01/is-market-intelligent.html).
