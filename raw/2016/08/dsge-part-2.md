---
title: "DSGE, part 2"
date: 2016-08-17T12:30:00.000-07:00
updated: 2019-08-02T15:38:31.820-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/08/dsge-part-2.html
---

I am continuing to build a standard DSGE model (specifically, the simple three equation New Keynesian DSGE model) using information equilibrium (and maximum entropy). In [part 1](http://informationtransfereconomics.blogspot.com/2016/08/dsge-part-1.html), I summarized the references and built a "Taylor rule". In this installment, I will use the Euler equation to derive the "IS curve". I'll assume rational expectations for simplicity at first (one can drop the $E$'s), but will add some discussion at the end.



Let's start with the information equilibrium relationship between (real) output and (real) consumption $Y \rightleftarrows C$. This tells us that






or in log-linear form $y = \frac{1}{\sigma} \; c$. I took the information transfer index to be $1/\sigma$ so that we end up something that might be recognizable by economists. Now let's [import the maximum entropy condition](http://informationtransfereconomics.blogspot.com/2015/06/the-euler-equation-as-maximum-entropy.html) relating two periods of consumption at time $t$ and $t+1$ from this post:






or in log-linear form $c_{t+1} = c_{t} + r_{t}$. Substituting output $y$, defining the real interest rate in terms of the nominal interest rate $i$ and expected inflation $r_{t} \equiv i_{t} - \pi_{t+1}$, and rearranging we obtain:






And there we have the NK IS curve. We can add in the expectation operators if you'd like:






And this is where the information equilibrium version of the IS curve has a different interpretation. The information equilibrium model can be viewed as a transfer of information [from the future to the present](http://informationtransfereconomics.blogspot.com/2014/12/how-money-transfers-information-from.html). We can interpret the "expected" value as the ideal information transfer value, and deviations from that as non-ideal information transfer. The value added by this interpretation is that instead of rational expectations where the deviation from the expected value has some zero-mean distribution, we generally have e.g. prices that will be bounded from above by the ideal information equilibrium solution. Here's [an example using interest rates](http://informationtransfereconomics.blogspot.com/2014/05/the-effect-of-expectations-in-economics.html):



![](<media/ite expectations interest rate 02.png>)

We could think of the $E$ operators as a warning: this variable may come in below expectations due to [coordinations (financial panic, recession)](http://informationtransfereconomics.blogspot.com/2014/10/coordination-costs-money-causes.html). Therefore, we should think of the information equilibrium NK DSGE model as a bound on a dynamic system, not necessarily the real result. With this in mind, it is no wonder DSGE models would work well for the great moderation but fail during a massive coordination event.

...

**Update**

[Here's the summary with links to each part](https://informationtransfereconomics.blogspot.com/2016/08/dsge-part-5-summary.html).
