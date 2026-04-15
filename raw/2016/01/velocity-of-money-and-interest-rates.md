---
title: Velocity of money and interest rates
date: 2016-01-15T12:00:00.000-08:00
updated: 2016-01-16T19:11:58.272-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/01/velocity-of-money-and-interest-rates.html
---

Since it came up in the [top shared posts of 2015](http://informationtransfereconomics.blogspot.com/2016/01/top-feedly-posts-of-2015.html), I re-read this post and comments on [an MZM quantity theory](http://informationtransfereconomics.blogspot.com/2015/09/an-mzm-quantity-theory.html). John Handley left a comment about how this wasn't all that new ...

> _V following i has been part of economic theory for a long time. Heck, it's implicitly in IS-LM (something like log(M/P) = L(y,i) = a log(y) - bi). In more modern macro, there are models ranging from Cash-Credit models (my favorite) to Money in the Utility Function models which most people recognize how terrible this assumption is; but it's mathematically tractable. Every (I hesitate, but I'm pretty sure...) understands that V is not constant and that it empirically tracks interest rates._

He gives a couple of references \[1, [pdf](http://users.ox.ac.uk/~exet2581/msc/ec924cia.pdf)\], \[2, [pdf](http://akson.sgh.waw.pl/~mbrzez/Ekonomia%20monetarna/MIU.pdf)\]; we'll follow the former and look at the cash-credit \[CC\] models. The key here to understand is the word "tracks", which isn't quite the same as "is a good model for". From \[1\]:

> _\[Hodrick, Kocherlakota and D. Lucas\] find that if they use the basic cash in advance model, whether it be that of Lucas or Svensson, they cannot generate under any plausible scenario enough variation in the velocity of money. For instance, over the last 100 years the velocity of money has had a standard deviation of around 4.5% but with the basic cash in advance model they cannot generate a standard deviation any greater than 0.09%. However, the cash-credit CIA model can generate more plausible numbers for the variability of velocity, with the numbers ranging between 0.6 % and 5.1%. However, to generate these more plausible numbers the authors have to assume very high levels of risk aversion. As a consequence, while they can explain observed volatility in the velocity of money they are unable to account for several other features of the data, such as the low level of actual interest rates._

This is moment matching (getting the same standard deviation for fluctuations); if we take the basic model in the end of \[1\] with _V_ being velocity and _i_ being the long term interest rate (see also **IS-LM model** below), there is indeed a linear relationship between _V_ and _i_:



_V = 1/α + i (1 - α)/α_


The parameter _α_ represents the relative weighting of utility between goods that can be purchased with cash versus credit. From the text: "This varies positively with the rate of interest ... and so potentially the model is quite realistic." Yes, potentially. The best fit I was able to achieve is this:



![](<media/velocity models MZM 1.png>)

If you look at the fluctuations, they actually do track each other. We'll make it more obvious (and make the model work better) by performing a linear transformation on velocity:



_a V + b = 1/α + i (1 - α)/α_


Now the best fit looks a bit better (showing the \[smoothed\] fluctuations this time -- the linear transformation is just a scaling of the fluctuations):



![](<media/velocity models MZM 2.png>)![](<media/velocity models MZM 3.png>)

They do track each other. The information equilibrium \[IE\] model still works much better (matching both levels and rates):



![](<media/velocity models MZM 4a.png>)![](<media/velocity models MZM 4b.png>)


_log i = c log(NGDP/MZM) + k_



_(i ⇄ p) : NGDP ⇄ MZM_



i.e. the interest rate _i_ is in information equilibrium with the price of money _p_ which is the detector of signals maintaining information equilibrium between NGDP and MZM.



**IS-LM model**

As John correctly states, the IS-LM's downward sloping LM curve does sort of imply a linear relationship between velocity and the interest rate. Starting with:



_M/P = L(i, Y)_
Let's say _L(i, Y)_ is separable so that

_M/P = Y L(i)_
Which means:

_V = 1/L(i)_
If we take

_V = a i + b_
Then:

_L(i) = 1/(a i + b) = (1/b) - a i/b² + ..._



... which is a downward sloping curve for _a_ and _b_ positive (as they are). I do put together an [empirically accurate form of the IS-LM model](http://informationtransfereconomics.blogspot.com/2014/03/the-islm-model-again.html) in this post that instead uses investment and the monetary base (as opposed to MZM). One important piece of that model is that it looks at the short term interest rate instead of the long term interest rate, which is more relevant to policy as the Fed sets short term interest rates. The information equilibrium relationships are:



_(i ⇄ p) : I ⇄ MB_

_c : NGDP ⇄ I_



Where _I_ is investment, _MB_ is the monetary base, _p_ is the price of money, _i_ is the short term interest rate, and c is an irrelevant price in the investment market. Two additional notes:

-   The IS-LM model is valid when the price level does not change rapidly with _MB_ because it makes the assumption that _P_ does not depend strongly on monetary policy so that _NGDP = α Y_ with _α_ constant. This also means there's no significant difference between real and nominal interest rates.
-   You can add a labor market to this [through the Solow model](http://informationtransfereconomics.blogspot.com/2015/05/dynamics-of-savings-rate-and-solow-is-lm.html), pull out dynamics for the savings rate and add capital.

...

**Update 16 January 2015**

With some tweaking I was able to get a pretty decent fit with the modified CC model:

![](<media/velocity models MZM new.png>)
