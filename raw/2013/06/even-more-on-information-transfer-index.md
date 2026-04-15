---
title: Even more on the information transfer index (deriving the price level)
date: 2013-06-23T16:48:00.000-07:00
updated: 2013-06-23T16:48:18.713-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/06/even-more-on-information-transfer-index.html
---

Continuing from the [previous post](http://informationtransfereconomics.blogspot.com/2013/06/more-on-information-transfer-index.html), here again is the empirically derived information transfer index $\kappa$, this time with a quadratic trend shown:

![](<media/information transfer index.png>)

If we use this normalization factor as a fit parameter, we find a value of $\sim 375$ which gives the following normalized monetary base (the dashed curve is a counterfactual I will discuss later):

![](<media/information transfer index norm monetary base.png>) This value minimizes the difference between the the equation above and the CPI (less food, energy), and creates a relatively good fit (blue is the equation above with empirically derived $\kappa$, gray is the [CPI](http://research.stlouisfed.org/fred2/series/CPILFESL)): ![](<media/information transfer index cpi.png>) This is actually a really good fit given that it has only a single parameter (normalization of the monetary base) and is a function of only the monetary base and nominal GDP. Note the normalized monetary base alone (shown in green below, with the CPI in gray) doesn't fit the CPI very well (nor does GDP/MB, except as combined as the equation at the top of this post): ![](<media/cpi and mb.png>)
I am trying to show that this model actually describes something non-trivial given its inputs. Additionally, the model (blue) fits the inflation rate (gray, derived from the CPI data) relatively well (I show  both the raw version and a LOESS smoothed version of both curves): ![](<media/inflation rate no smooth.png>)
![](<media/inflation rate.png>)
Now for the counterfactual I mentioned earlier. If we assume that $\kappa$ follows the quadratic fit in the first graph at the top of this post and that the Fed didn't engage in Quantitative Easing (the dashed green curve in the monetary base graph above), we get the dashed blue curve in the graph below: ![](<media/information transfer index cpi counter.png>) This is much more serious deflation than actually occurred.
One thing to we can see from this model is that the measured CPI may either be missing some deflation or there is another kind of inflation such as [here](http://informationtransfereconomics.blogspot.com/2013/05/rescaling-and-inflation.html). A second thing we can see is that the quantitative easing conducted by the Fed was insufficient (and needed to be roughly twice as big).
This is the first time I have believed the information transfer model may have some real capability beyond some notional aspects of supply and demand.
