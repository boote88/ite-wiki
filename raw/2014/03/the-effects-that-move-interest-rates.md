---
title: The effects that move interest rates
date: 2014-03-18T18:24:00.001-07:00
updated: 2014-03-19T16:56:10.580-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/03/the-effects-that-move-interest-rates.html
---

[Scott Sumner](http://www.themoneyillusion.com/?p=26378) laid out the primary forces acting on interest rates (from a monetarist perspective) in a convenient piece of a paragraph:

> _The short run effect of monetary policy is called the liquidity effect. A change in the money supply causes interest rates to move in the opposite direction, in the short run. The long run effects of monetary policy are called the income effect, the price level effect and the expected inflation (Fisher) effect. These three effects all cause interest rates to move in the same direction as the money supply._

How do these components look in the information transfer model?

We'll call the liquidity effect the effect on interest rates of taking _MB → MB + dMB_ holding NGDP constant

We'll call the income/inflation effect (price level effect) the effect on interest rates of taking _MB → MB + dMB_ accounting for inflationary effects on NGDP and subtracting out the liquidity effect (I will also show this without subtracting out the liquidity effect and call it the combined monetary effects).

Both of these effects act simultaneously if your temporal resolution is quarterly (as we will consider here); the liquidity effect would likely happen on an even shorter time scale -- almost instantly in the interest rate market. This is effectively assuming "the long run" is a quarterly time scale.

There is an additional piece of the model that affects interest rates that I'll call exogenous NGDP effects (or shocks, essentially the difference between the effect of _MB → MB + dMB_ on NGDP and the actual NGDP in the next period).

We leave out the Fisher effect (expected inflation) as the information transfer model does not contain "expectations" as such. The difference between this "expected" inflation and the inflation in the income/inflation effect is that the latter is essentially derived from a quantity theory of money so that locally _log NGDP ~ α log MB_. In some sense the Fisher effect represents a failure of the interest rate market: it is an incorrect assessment of future inflation that causes interest rates to rise above (or fall below) the value realized a quarter later.

Here are the model baselines:

![](<media/interest rate effects 0.png>)![](<media/interest rate effects 1.png>)
And we'll jump right to the take-away graph:

![](<media/interest rate effects 2.png>)
We can see that the combined effect of the different components (green) fits nicely to the actual data (black dotted line, LOESS smoothed). The liquidity effect (blue) appears to dominate the total monetary effects (dark purple) after the 1980s as the income/inflation effect (price level effect, light purple) fades away. The major deviations of the data from the model are here tentatively attributed to the Fisher effect (shaded gray).

The allocation to the Fisher effect makes some intuitive sense; fears of inflation plagued the 1970s (recall the WIN campaign). After inflation died down, there was a subsequent correction towards the "expectation-less" effect of monetary policy. However, other than the late 1970s and early 80s, the "Fisher effect" appears to be of negligible importance.

Let's look at the income and liquidity effects as a function of the change in the monetary base:

![](<media/interest rate effects 3.png>)![](<media/interest rate effects 4.png>)
In the left graph above, we see the liquidity effect (blue) moves in the opposite direction as the change in the base while the income/inflation effect (purple) moves in the same direction -- exactly as described by Sumner in the quote above.

If we look at the combined monetary effects in the right graph above, another pattern emerges. The period before the early 1980s (blue) has a sizable contribution from the income/inflation effect, while data afterwards (purple) shows the liquidity effect dominating interest rates. This is broadly in line with the general path of interest rates over the post-war period: rising before the 1980s and falling afterwards.




![](media/diagram.png)
