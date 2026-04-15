---
title: Reconciling expectation and information
date: 2014-06-14T14:00:00.000-07:00
updated: 2014-06-14T15:01:31.657-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/06/reconciling-expectation-and-information.html
---

There was a brief back and forth between Scott Sumner and me in comments on [his post](http://www.themoneyillusion.com/?p=26941) on whether money is tighter or looser given a drop in interest rates. Sumner said (the edited version):

> _The fed funds change is different. Whereas a change in IOR_ affected _the demand for base money, a change in the few funds rate is an_ effect _of a change in the supply of base money. That’s easier money in the short run__,_ ceteris paribus_. But whether it is_ actually _easier money depends on how the action impacts the expected future path of monetary policy._

The short run effect is the liquidity effect, which I describe in more detail [at this link](http://informationtransfereconomics.blogspot.com/2014/03/the-effects-that-move-interest-rates.html). I commented that the long run effect was the same result as I gave in this [post](http://informationtransfereconomics.blogspot.com/2014/06/krugman-keynes-and-liquidity-trap.html), except the "depends" clause was different -- in the information transfer (IT) model result the depending is measured by the size of the base relative to the size of the economy (e.g. NGDP). Sumner disagreed with it initially, but then agreed with my contention that if the base is small, the future path of monetary policy is likely expansionary (i.e. looser money, leading to higher interest rates).  I'd like to say more about that with this post.



But first, I have to correct some sloppy language on my part. I have a tendency to say "the size of the base relative to NGDP" or write "MB/NGDP" when I actually mean a) not MB but M0, the currency component of the base (i.e. without reserves) and b) not the ratio but the ratio of the logarithms _log M0/log NGDP_ (aka the IT index, denoted by the Greek letter kappa κ elsewhere in this blog). You can see what I mean when I plot the two ratios here:



![](<media/ite expectations monetary base size relative to economy -sumner comment- 1.png>)

We can see that κ goes from a smaller value in the 1960s to a larger value today, whereas the simple ratio goes down and then up (it is normalized to 2011). The IT index κ is more relevant in the model because the price level is determined by the base via _log P ~ (1/κ - 1) log M0_ which means that _P ~ constant_ for _κ = 1_. [Another way to look](http://informationtransfereconomics.blogspot.com/2014/06/money-unit-of-information-and-medium-of.html) at the IT index is that it is the fraction of a unit of source information that can be transferred with the unit of account, i.e. _1/logM0 NGDP = log M0/log NGDP_ (using my poor man's subscripting technique to represent the logarithm in base M0) analogous to [Sumner's share of the economy that can be bought with one dollar](http://www.themoneyillusion.com/?p=15308) (value of money _\= 1/NGDP_).



Now how do we reconcile the expectation of future base growth ("loose money") with the size of the base M0? Well, if we plot the numerator (blue) and denominator (red) of the IT index and assume a uniform probability distribution (maximum ignorance) using the denominator (_log NGDP_, i.e. where _κ = 1_ if _log M0 =_ _log NGDP_) as the upper bound and the quantity theory of money (_κ = 1/2_) \[1\] as the lower bound (dashed gray) for the possible values of _log M0_, we can see that if the IT index is below _κ = 3/4_, more states in _log M0_ space exist above than below the current value of the base in 1970. See the relative length of the green line segments the diagram below:



![](<media/ite expectations monetary base size relative to economy -sumner comment- 2.png>)



We can put this in Sumner's language in the quote above. In 1970, there are more places for _log M0_ to be above its current value than below, meaning a larger base and therefore looser money is expected. That means interest rates will tend to rise as an effect of base expansion. In 2005, a larger or smaller base are closer to being equally likely (i.e. that base expansion is less likely than it was before in the 1970s), meaning that interest rates will tend to stay constant or fall as an effect of base expansion.



The uniform distribution over the values of _κ ∈ \[1/2, 1\]_, of course, is an oversimplified picture. The actual probability distribution over the possible expected values would likely involve more understanding of human behavior (in response to [Mike Freimuth's comments here](http://informationtransfereconomics.blogspot.com/2014/05/utility-is-silly-and-other-observations.html)) -- the distribution is probably peaked at the value of the (log of) the base and goes to zero at (the log of) NGDP as well as zero (log 0 = -∞), but its exact form would depend on how humans discount rare events (see e.g. [prospect theory](http://en.wikipedia.org/wiki/Prospect_theory)).



The actual cross-over point, [based on the behavior of IS curves](http://informationtransfereconomics.blogspot.com/2014/06/krugman-keynes-and-liquidity-trap.html) (i.e. the effect of expansionary policy on interest rates), seems to be in the late 1970s or early 1980s. This is where the IS curves turn over and loose money means lower interest rates.

\[1\] If we have _log P ~ (1/κ - 1) log M0_ then _κ = 1/2_ means that  _(1/(1/2) - 1) log M0 =_ _(2 - 1) log M0 = log M0 = log P,_ i.e. _P ~ M0_ (the quantity theory of money) and the rate of growth of the price level is equal to the rate of growth of the base. \[Added in update 6/14/2014\]
