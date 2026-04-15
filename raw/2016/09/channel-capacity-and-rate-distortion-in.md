---
title: Channel capacity and rate-distortion in economics
date: 2016-09-10T13:00:00.001-07:00
updated: 2016-09-10T13:00:52.930-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/09/channel-capacity-and-rate-distortion-in.html
---

Lionel Yelibi ([Twitter](https://twitter.com/TehRaio)) directed me to a lecture by Christopher Sims at Bell Labs on YouTube on information theory in economics:





Overall, it is pretty interesting. And I think it helps illustrate another aspect of a point I've made before ([here](http://informationtransfereconomics.blogspot.com/2015/03/the-price-system-as-communication.html), \[1\]): that if the price mechanism is a communication channel, there is a lot of information loss going on. I've also discussed Sims' work before in generic terms of how it fits in a steady stream of attempts to work out problems caused by assuming humans are rational utility maximizing agents ([here](http://informationtransfereconomics.blogspot.com/2015/02/stubborn-theoretical-ideas.html)).



There are two main topics in Sims talk. The first is his work on rational inattention, sticky prices, and [channel capacity](https://en.wikipedia.org/wiki/Channel_capacity); the second is about applications of [rate-distortion theory](https://en.wikipedia.org/wiki/Rate%E2%80%93distortion_theory) ([here is a relevant lecture \[pdf\]](https://www.cs.uic.edu/pub/ECE534/WebHome/ch10.pdf)). Both of these applications view the price mechanism such that the price is an information source. Sims uses limited channel capacity and lossy compression (rate-distortion theory) to explain sticky prices and deviation from rational behavior; I'd like to use his results as evidence that the price isn't aggregating information that people use.



Let's say a price is given by a Wiener process (random walk); innovation (individual moves of a stochastic variable) reveals about _~ log σ + c_ bits (log base 2) of information where _σ_ is the standard deviation of the Gaussian (normal) distribution and _c_ ~ 2 bits is a constant. Let's say prices are updated every minute during during normal working hours over the course of a year. That would be ~ 120000 (_log σ + c_) bits of information (if _σ_ = 1, this is 246,000 bits or 31 kB of data).



How much channel capacity does Sims find we humans devote to following, say, interest rates if we're assumed to be rationally adjusting to changes? Twenty-four bits over the course of a year. Effectively two coin flips a month (an audience member couches this as yes/no, up/down). That is a large amount of information loss!



Let me now draw a picture combining Sims results with \[1\] above.



![](<media/channel capacity.png>)



On the left side, we have the impossibility of compressing the complex multidimensional system of the bond market (including macro conditions, central bank actions, and expectations) into a single number drawn from a one-dimensional distribution. That is the information aggregation problem. Sims work shows that on the right side, agents only respond rationally to a few bits of that single-dimensional distribution per month -- itself already a massive simplification of the real world. That is the "rational inattention" problem.



One solution to this is that agents get their information from other places: models of how the economy works, research on fundamentals, or gut feelings. However this means the price is just a small part of the market information aggregation and dissemination process.



Another solution -- one that I have proposed in \[1\] above -- is that this way of looking at the price mechanism is incorrect. Prices aren't part of the information channel; they just measure information flowing through it. Humans aren't rational economic agents; they're complex explorers of the economic state space. The distributions of agents' economic actions match up with the distribution of changes in the economy\*\* -- the distributions are in _information equilibrium_. Here is the picture:



![](<media/channel capacity 2.png>)



Now it might not be that humans are totally random. Maybe just the majority of bits of information can be treated as random actions ([algorithmic randomness](https://en.wikipedia.org/wiki/Algorithmic_information_theory#Precise_definitions)) with respect to price changes. As Sims shows, agents respond to a few bits of price information as rational economic agents. But those few bits might well be the problem. If agents respond rationally to a price signal, many agents will respond in the same way. Sims' "few bits" represent correlated information among agents. And correlated actions of agents (e.g. panic in a financial crisis) and the resulting entropy loss [may be what is behind recessions](http://informationtransfereconomics.blogspot.com/2016/09/the-economic-state-space-mini-seminar.html).



In a way, I think Sims' work is a measurement of how good an approximation information equilibrium is.



...



\*\* I hope this is obvious. All changes in the economy are the aggregation of economic changes (actions, decisions) made by agents.
