---
title: "Which way does the information flow?"
date: 2014-09-02T18:12:00.000-07:00
updated: 2014-09-02T18:12:12.890-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/09/which-way-does-information-flow.html
---

I've been asked how I know information flows from the demand to the supply several times, most recently by [commenter Jamie](http://informationtransfereconomics.blogspot.com/2014/08/you-dont-need-to-understand-how-people.html?showComment=1409571336280#c8261821082626625779) and [David Glasner](http://uneasymoney.com/2014/08/22/the-trouble-with-is-lm-and-its-successors/#comment-225064). The easiest answer is that I don't really know, but just assumed that for now. However there are some plausible arguments that I will try to clearly present here. For concreteness, let's call I(D) the information sent (or received) by "the demand" and I(S) the information received (or sent) by "the supply".



This is going to be both technical and philosophical, but first let me start off with three points:

1.  The direction of information flow is largely irrelevant to most of the results of the information transfer model I've presented on this blog because I nearly always take I(D) = I(S); in that case the direction of information flow essentially comes down to a sign convention in which solutions of the differential equation to choose to reproduce supply and demand diagrams.
2.  "Information" in the information transfer framework is not specific insider knowledge about corporate earnings, understanding of the IS-LM model, political intuition, theories of inflation or really anything people colloquially equate with the word information. Actually, information in information theory generally represents a lack of knowledge (a random sequence of numbers has more information than a predictable one). The entirety of I(D) would consist of a list of numbers of widgets purchased at various prices by different individuals. Now it is true that e.g. consumers' theories about inflation might determine the numbers of widgets they might buy at various prices, but as far as the market is concerned (and the information transfer framework), those theories are irrelevant once you have that list of numbers of widgets purchased at various prices. This also helps us understand point three ...
3.  The selection of I(D) or I(S) as the information source is not ideological. Nor does it mean that corporations are "dumber" than consumers or vice versa.

Now for cases where I(S) < I(D) -- or I(D) < I(S) -- it does make a difference which one is the information source; let me present a couple of arguments for how one should be able to tell the difference.


**Argument from abstract physical processes**


This argument is based on email discussions with [Peter Fielitz](http://arxiv.org/abs/0905.0610) and can be found in his paper with Guenter Borchardt \[1\]. What follows is my version of his argument and any errors are mine. The idea is that if a process variable (our D or S above) could theoretically generate an infinite amount of information, then it cannot be an information source -- the amount of information transferred must be finite, i.e. I(source) < ∞.



This seems to point towards demand being the information source since one could (theoretically) produce an infinite supply of widgets (or an effectively infinite supply of widgets relative to the number of consumers -- so many that no more will be bought or the price goes to zero), but a market with an infinite quantity demanded relative to the number of consumers is non-sensical.



Peter gives an analogy with an ideal gas where the internal energy E maps to the demand D and the volume V maps to the supply S. We could set up an experiment where V is effectively infinite (relative to the number of particles) but an experiment where E is infinite relative to the number of particles is non-sensical.



Peter also allows that if one changes the conditions (e.g. keeping one variable constant), it might change the status of which process variable is the source or the destination.


**Argument from information loss**


Peter Fielitz also had an interesting observation in our email exchange. Using the ideal gas analogy where E maps to D and V maps to S, he pointed out that the internal energy of an ideal gas is hard to measure directly. However one can achieve a very accurate estimate by measuring the pressure and volume and using the ideal gas law _E ~ pV_.



Now demand is hard to measure directly, but if one uses the analog of the ideal gas law _D ~ PS_ where P is the market price, one should be able to get an accurate estimate of the demand. This is especially interesting because _**this is exactly how the government tries to measure aggregate demand**_ (AD) or NGDP. Either the statisticians tally up how much everyone made from selling all their goods (income method) or tally up how much all the goods were purchased for (expenditure method), but the result in both cases is an estimate of aggregate demand.



This analogy also points to demand being the information source so that I(S) ≤ I(D): that tally based on aggregate supply AS at best will give us aggregate demand. The estimate of NGDP is either below the true NGDP (in which case it is missing information or wrong) or it is above the true NGDP (in which case it is wrong). Overestimates of NGDP are always wrong; underestimates are either missing information (but can be wrong, too). Even the best estimate from the market will result in NGDP below potential NGDP.



This was part of my original intuition behind why demand is typically the information source in trying to describe economic data -- the total sum of widgets sold (along with their prices) is at best a lower bound for the maximum possible number of widgets sold at various prices.



Let's imagine the demand as a probability distribution _P(i, j, k)_ where _i_ represents a given consumer, _j_ represents a given number of widgets and _k_ represents a given price, and _Q(i, j, k)_ is the probability distribution of desired sales. You could imagine P as the number of people that will buy widgets (at a given price point) in Seattle vs Tacoma and Q as how many widgets at what prices suppliers put in stores in Seattle vs Tacoma.



It seems fairly obvious to me that the market mechanism is trying to figure out P and suppliers with incorrect Q's will lose money (or not make as much) relative to those with correct Q's. I personally don't care how many pounds of bacon the bacon industry is trying to sell in which markets (i.e. Q) -- and I am spending zero effort to find out.



As pointed out by commenter Jamie, firms will produce advertising to influence P. However advertising does not travel through the price mechanism, but rather through human communication systems -- advertising does not represent information flowing from I(S) to I(D) or vice versa. Additionally, firms will spend money on market research in order to figure out P -- they are essentially bypassing the market estimate Q. This could represent an individual firm's lack of information about P (because they have competition and so don't know the entire market estimate Q) or the fact that the full market estimate Q is also imperfect ... giving further evidence that that I(S|Q) ≤ I(D|P). \[The notation _I(x|y)_ means the information in the process variable _x_ given the probability distribution _y_.\]



The probability distribution Q as an incorrect estimate of the distribution P represents information loss calculated via the [Kullback-Leibler divergence](http://en.wikipedia.org/wiki/Kullback%E2%80%93Leibler_divergence) D(P||Q). Now in general 0 ≤ D(P||Q), so an incorrect estimate Q of the distribution P _always represents information loss_. This is relevant to e.g. [this post on Walras' law](http://informationtransfereconomics.blogspot.com/2014/08/walras-law-information-theory-edition.html) where information loss could represent excess demand or excess supply at a given price -- the distribution in either case is wrong, and only when there is no excess supply or demand is P = Q.



In this view, the market appears to be a mechanism that attempts to find the best available Q to minimize D(P||Q) given potential constraints, but since D is semi-definite, we generally have I(S|Q) ≤ I(D|P).


**Summary**


While it's not set in stone (feel free to point out errors in comments!), I think these are some pretty plausible arguments for why we can assume information flows from demand to supply.



The other thing to keep in mind is that for most of this blog, remember point 1 at the top of this post: I assume I(D) = I(S) so the direction of flow doesn't really matter.
