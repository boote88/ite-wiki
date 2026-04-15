---
title: "Are higher interest rates inflationary?"
date: 2015-08-13T16:00:00.000-07:00
updated: 2015-08-18T12:58:56.504-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/08/are-higher-interest-rates-inflationary.html
---

Scott Sumner [writes](http://www.themoneyillusion.com/?p=30120) "higher interest rates are inflationary, as they raise velocity". Is this true? Generally? Is the mechanism true?



I had forgotten exactly how useful the log-linearized ["DSGE form" of the information equilibrium model](http://informationtransfereconomics.blogspot.com/2014/12/an-information-transfer-dsge-model.html) was to answer this kind of question. Ubiquitous caveat: this is a model-dependent result. The conclusions are true assuming the information equilibrium model (and my math is right). Anyway, here's are the (relevant) equations from [this post](http://informationtransfereconomics.blogspot.com/2014/12/an-information-transfer-dsge-model.html) (and ignore the difference between monetary base and monetary base minus reserves for right now):








If we take $\kappa$ = 0.5, i.e. the quantity theory of money, then we can show:






The interest rate at time $t$ is the interest rate at time $t-1$ plus a 'nominal shock' that is part of NGDP growth -- $\sigma_{t}$ in equation (1) -- that is generally positive (think population growth or TFP growth) but is negative when recessions hit (negative shocks tend to cause recessions and may actually be the same thing as a recession).









So when  $\kappa$ = 0.5, interest rates tend to rise because of positive nominal shocks, while the price level tends to  rise because of NGDP growth minus the nominal shocks -- i.e. just plain money growth. The rising interest rates are not related to rising price level.



Now what happens when $\kappa$ is close to 1? That is the liquidity trap/IS-LM regime ... Well, first:




There is approximately zero inflation when $\kappa \simeq 1$. And for interest rates we get an extra term in equation (4):




Monetary expansion lowers interest rates if it is larger than the nominal shocks. Note that when $\kappa \simeq 1$, we also have







i.e. NGDP growth is mostly due to nominal shocks. You can see this point alongside some graphs of the nominal shocks [here](http://informationtransfereconomics.blogspot.com/2014/08/lowflation-is-meaningful-concept.html) (also shown below).

![](<media/basic us price level m0 interst rates -shock picture-.png>)
So when $\kappa \simeq 1$, monetary expansion (e.g. base growth) that is greater than NGDP growth makes interest rates fall and monetary expansion that is slower than NGDP growth makes interest rates rise.


**Summary:**


-   $\kappa \simeq 0.5$: Inflation is due to monetary expansion (NGDP growth without nominal shocks) and interest rates tend to rise due to nominal shocks. These are separate processes. Rate rises are dominated by what might be called the 'income effect' arising from higher nominal output.
-   $\kappa \simeq 1.0$ Inflation is approximately zero and interest rates tend to rise if monetary expansion is slower than NGDP growth and fall if monetary expansion is faster than NGDP growth. NGDP growth is entirely due to nominal shocks. Here the income and liquidity effects are acting in opposite directions with the liquidity effect (the new second term in the interest rate in equation 5) coming to dominate.

So the general picture of the US should show rising interest rates and price level, the latter of which causes $\kappa$ to rise (since $\kappa$ goes as _log M/log N,_ the denominator reaches a point of slower growth before the numerator), leading to a turn-over and falling interest rates and a flattening of the price level. This is precisely the set of effects described [here](http://informationtransfereconomics.blogspot.com/2014/03/the-effects-that-move-interest-rates.html).

**Update 8/18/2015**: Updated summary with some economic language from the link at the very end.
