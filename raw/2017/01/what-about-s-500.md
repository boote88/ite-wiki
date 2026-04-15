---
title: "What about the S&P 500?"
date: 2017-01-31T18:12:00.002-08:00
updated: 2017-02-01T13:45:17.499-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/01/what-about-s-500.html
---

The S&P 500 is [a price index](http://informationtransfereconomics.blogspot.com/2017/01/housing-prices-and-dynamic-equilibrium.html), right? How well does the dynamic information equilibrium approach (previous link) describe the S&P 500? Remarkably well, actually:



![](<media/dynamic equilibrium SP500 info eq 1.png>)
![](<media/dynamic equilibrium SP500 info eq 2.png>)



There are only four major "shocks". Three are negative: 1971.9,  2001.7, and 2008.5. The former is a very broad slow shock that may well be related to the high inflation of the 1970s (that's pure speculation on my part at this point). The latter two are the so-called "dot-com bust" and the global financial crisis.



There is one positive shock associated with the dot-com boom: 1997.6.



The second graph smooths the S&P 500 data slightly (a local average derivative) since the index is noisy and well-resolved (daily measurements).



But really, the stock market is highly complex \[1\].




**Update 1 February 2017**

[geometric random process](https://en.wikipedia.org/wiki/Geometric_Brownian_motion)

![](<media/dynamic equilibrium SP500 info eq forecast 1.png>)

As expected, it passes all the unit root tests (although they have low power). What if we use this series to estimate a process? _Mathematica_ chooses a second order [ARMA process](https://en.wikipedia.org/wiki/Autoregressive%E2%80%93moving-average_model) ‒ ARMA(2,1) to be precise ‒ if you use **TimeSeriesModelFit** with default options on the last 7 years of data \[2\]. Taking that forecast into the future we basically figure out that the S&P 500 should return to the dynamic equilibrium trend:



![](<media/dynamic equilibrium SP500 info eq forecast 2.png>)

So now we have a test. Since I only grabbed _Mathematica_'s financial data up to 1 January 2017, we actually have a few data points (black, above) to show against the forecast already. Here's a zoomed-in version:



![](<media/dynamic equilibrium SP500 info eq forecast 3.png>)


**Update 1 February 2017, the second**

[unemployment shocks](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-unemployment-rate.html)[Case-Shiller shocks](http://informationtransfereconomics.blogspot.com/2017/01/housing-prices-and-dynamic-equilibrium.html)

![](<media/dynamic equilibrium SP500 info eq -subset- just to 1965.png>)

Around 1970, 1974, 2001 and 2008 we have pretty good alignment of an NBER recession, an unemployment shock, and an S&P 500 shock. The 1980s and 90s show unemployment shocks associated with NBER recessions but not S&P 500 shocks.



The sizes also don't match up completely. The 1974, 2001 and 2008 S&P 500 shocks are "large", but all of the unemployment shocks are of comparable size. Basically, the 1980s and 90s recessions happen without a large signal in the S&P 500. Therefore it's hard to say there is causality happening in either direction, but rather just a loose association.



However the 1980s and 90s recessions (as well as the one in 2008) are associated with shocks to housing prices (1974 probably would be as well [given the longer Case-Shiller time series](https://commons.wikimedia.org/wiki/File:Case%E2%80%93Shiller_Index.svg)).



There's no real conclusion to be drawn from so few events. We can just generally say that most recessions are associated with falling housing prices, rising unemployment, and a falling S&P 500. This is not very illuminating. 



I should also show the derivative picture for the additional shocks:



![](<media/dynamic equilibrium SP500 info eq -subset- just to 1965 2.png>)





**Footnotes:**

\[1\] See [here](http://informationtransfereconomics.blogspot.com/2017/01/complex-systems-versus-complicated.html) and [here](http://informationtransfereconomics.blogspot.com/2017/01/curve-fitting-and-relevant-complexity.html).

\[2\] The results are pretty robust to fiddling around with the length of data used to estimate as well as restricting to ARMA processes.
