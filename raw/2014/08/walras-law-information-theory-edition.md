---
title: "Walras' law, information theory edition"
date: 2014-08-30T19:50:00.000-07:00
updated: 2014-08-30T19:50:08.457-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/08/walras-law-information-theory-edition.html
---

[Nick Rowe](http://worthwhile.typepad.com/worthwhile_canadian_initi/2014/08/a-simple-question-about-walras-law.html) has a new post up and it inspired me to take up his challenge (entering as a non-economist). Rowe is probably one of the best economist bloggers out there if you want to get more technical than the typical post from Scott Sumner or Paul Krugman. His question is this:

> _Q. Assume an economy where there are (say) 7 markets. Suppose 6 of those markets are in equilibrium (with quantity demanded equal to quantity supplied). Is it necessarily true that the 7th market must also be in equilibrium (with quantity demanded equal to quantity supplied)?_

I've looked at Walras' law before (e.g. [this post](http://informationtransfereconomics.blogspot.com/2013/09/walras-law.html)). I'm going to answer this using information theory with progressively more complexities, but I'll start with some notation.



Define $I(D_{k})$ to be the source (demand) information in the $k^{\text{th}}$ market and $I(S_{k})$ to be the received information (supply). Define aggregate source information (aggregate demand, AD) and aggregate received information (aggregate supply, AS) as

















**First is the "Walras' law is correct" version \[1\] ...**












Now the thing is that all we can really say is that $I(AS) \leq I(AD)$ (the market doesn't necessarily transfer all the information), so that brings us to **the non-ideal information transfer version \[2\] ...**



We assume that the information in each market is independent and that $I(AS) \leq I(AD)$, so that












That means Walras' law doesn't pin down that last market, and says that there can be excess demand. But it's even worse than that, which brings us to **the non-independent (i.e. mutual) information version \[3\] ...**












This says for practical purposes that some of the information in the source in one market may be the same as the information in the source in another, hence they do not necessarily add to yield more information. So that all we really know is that






based on the fact that you can't get more information out than you put in. This means that knowing the six markets clear doesn't necessarily even tell us about the aggregate demand of the 6 markets (ignoring the seventh).



Nick Rowe basically arrives at this last version -- he says there can be excess demands/supplies of money in each of the six markets so Walras' law can't really tell us anything about the seventh. The information theory argument presented here does not require money, which is consistent with Rowe. He says that the same result could hold in a barter economy because some good could effectively operate as money and there would be excess demands for various barter goods in each of the individual markets. Rowe says that:

> _Walras' Law is true and useful for the economy as a whole only if there is only one market in the whole economy, where all goods are traded for all goods._

This appears to be saying that if you can't decompose $AD = D_{1} + D_{2} + \cdots$ (or the decomposition is trivial), then you get Walras' law back -- and it's true. If you can't decompose the markets, then there are no "joint entropies" that can be formed from their decomposition, so there is no information loss in equation (1) above. This doesn't rule out non-ideal information transfer in version \[2\] above, but assuming markets work, saying you can't decompose the markets (or the decomposition is trivial) gets you back to version \[1\] where Walras' law holds.



[sub-additivity of joint entropy](http://en.wikipedia.org/wiki/Joint_entropy#Less_than_or_equal_to_the_sum_of_individual_entropies)
