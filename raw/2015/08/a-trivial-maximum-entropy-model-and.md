---
title: A trivial maximum entropy model and the quantity theory
date: 2015-08-12T12:22:00.004-07:00
updated: 2015-09-18T14:21:51.625-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/08/a-trivial-maximum-entropy-model-and.html
---

This is a trivial maximum entropy model, but I still think the result is interesting.



Let's take an economy with _d_ = 100 dimensions subjected to a budget constraint _Σ m = M(t)_ where _t_ is time, _m_ is the (randomly chosen) allocation of the total amount of money _M_ to each dimension (these could be "markets", "firms" or even "agents"). This is effectively this picture except _d_ \= 3 here (the _Ci_ are the dimensions):



![](<media/money3d a.png>)


If we take the derivative of the ensemble average _d/dt log 〈m〉_(assuming a uniform distribution), we get something (blue paths) that roughly follows _d/dt log NGDP_ (yellow path):



![](<media/ITM test random economy.png>)

The paths obviously converge to _d/dt log M_ (black path) ... it doesn't even depend on d because _〈m〉= α M_ with constant α even if we don't have _d >> 1_ since



_d/dt log α M = d/dt (log M + log α) = d/dt log M_



If _d >> 1_ then we have _α ~ d/(d + 1) → 1_, but this isn't terribly important. What this does show is that



_d/dt log M ~ d/dt log NGDP_



_k M ~ NGDP_



and we have a simplistic quantity theory of money based on randomly allocating money to different markets.
