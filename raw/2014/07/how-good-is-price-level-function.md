---
title: "How good is the price level function approximation?"
date: 2014-07-04T13:48:00.002-07:00
updated: 2014-07-04T15:35:20.421-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/07/how-good-is-price-level-function.html
---

In [this post](http://informationtransfereconomics.blogspot.com/2014/06/the-macroeconomic-partition-function.html) I defined the partition function approach and noted that the "ansatz" (i.e. fancy guess)










which I intend to explore further in this post. First, I needed to see how the expected valueof $NGDP \sim \langle m^{a} \rangle$ (in 100 random markets again) worked against the empirical data. In the following plot I show the equation (black) along side the data (blue) in both log scale and linear scales:



![](<media/ite partition function -1a-.png>)![](<media/ite partition function -1b-.png>)

This was a two parameter fit: and overall normalization of $NGDP$ and the relative normalization of $m$ so that 






This fit was then used in the price level ansatz equation (1) and compared with the numerical evaluation of the expectation value equation (2). What I am doing here is trying to figure out how well the functional form (1) approximates the "true" solution (2). It turns out it fits pretty well:



![](<media/ite partition function -2b-.png>)![](<media/ite partition function -2a-.png>)

The ansatz (blue dashed), which was motivated through some squishy arguments \[1\], is a pretty good approximation to the exact solution (black), both of which fit pretty well to the data (green), again shown in log and linear scales. This means that the [approach to macroeconomics](http://informationtransfereconomics.blogspot.com/2014/06/the-information-transfer-model.html) taken on this blog has some pretty solid grounding.



\[1\] Equation (1) uses the definition of the information transfer index as counting the number of symbols and posits that the number of symbols in the demand is proportional to NGDP, while the number of symbols in the supply is proportional to the money supply. Additionally, there is an assumption that [changes in the information transfer index are slow](http://informationtransfereconomics.blogspot.com/2014/03/how-money-transfers-information.html) (compared to changes in the size of the economy or the money supply) so it can be taken out the integral.
