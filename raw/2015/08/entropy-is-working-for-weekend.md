---
title: Entropy is working for the weekend
date: 2015-08-24T19:33:00.002-07:00
updated: 2015-08-24T19:33:57.927-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/08/entropy-is-working-for-weekend.html
---

Nick Rowe employs his ability for distillation in the task of explaining a monetary coordination failure that results in a recession. [In his recent post](http://worthwhile.typepad.com/worthwhile_canadian_initi/2015/08/good-shocks-bad-shocks-and-shocks-that-cause-a-monetary-coordination-failures.html), he mentions the coordination occurring on the weekend:

> _Every Saturday Canadian output and employment drop. And they drop again every Sunday. Every weekend, output and employment drop for two successive days. Are weekends mini recessions? I would say "no"._

If you've been following along this blog -- in particular [this post](http://informationtransfereconomics.blogspot.com/2014/10/coordination-costs-money-causes.html) \[1\] -- you might ask: _I thought you said coordination causes recessions?_



I did say that. The important thing to understand is that it is coordination relative to the equilibrium distribution. Let's say here's what (the probability density of) output looks like during a typical week (I made this data up):



![](<media/weekend coordination 1.png>)

Call this distribution _P_. It's the equilibrium distribution. Some people (by no means everybody) have the opportunity to take weekends off. Now week to week the information loss measured by the KL divergence is zero:



_D(P||P) =_ 0



But if suddenly this happens (call this distribution _Q_):



![](<media/weekend coordination 2.png>)

We get a KL-divergence that results in an information loss of:



_D(P||Q) =_ 0.18 bit



It turns out that is a loss of about 6.6% relative to the information entropy of _P_ ~ 2.78 bits. That would be a mini recession (if weeks were all the same except that one, it would be a recession of about 0.1% of output).



What would really be happening? What is the story behind this mini-recession? With more people off on days that they used to have on, they might go shopping. But with fewer people to stock the shelves and no one expecting a Thursday rush of long weekend consumers, less gets sold than in the status quo. ATM's might not have enough money in them for Wednesday being the new Friday and cash only establishments would miss out. Restaurants unexpectedly fill up for Friday brunch and people can't get a table.



We seasonally adjust data; that's an admissible procedure only because the seasonality represents the equilibrium distribution.



Now you may ask: _What about holidays? Or the Stanley Cup?_



Well, the first graph was actually a simplification. The actual distribution would be more complex, taking into account your country's public holidays, major sporting events and vacations. That would be the real _P_.



If part way through the year, 5% more people became unemployed so that your distribution of output changed (i.e. more the output would have been at the beginning of the year relative to an equilibrium year), then you would probably have a recession. That's a bad coordination.



Now I actually think the real coordination comes in the form of pessimism about asset prices and future sales, so the rise in unemployment is a symptom, not the cause. The entropy loss manifests as a fall in employment (and a rise in the number of people with zero wage change) as seen in the post above \[1\].
