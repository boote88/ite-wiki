---
title: Strange new monetary worlds
date: 2014-01-24T14:51:00.000-08:00
updated: 2014-01-24T14:51:54.802-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/01/strange-new-monetary-worlds.html
---

[Scott Sumner](http://www.themoneyillusion.com/?p=26030) and [Nick Rowe](http://worthwhile.typepad.com/worthwhile_canadian_initi/2014/01/another-weird-monetary-world.html) are blogging about what Sumner refers to as _"a central puzzle of monetary economics—the fact that easy money both lowers and raises interest rates"_. I had previously discussed an older Sumner post on this subject [here](http://informationtransfereconomics.blogspot.com/2013/09/interest-rates-and-monetary-policy-or.html); it included market reactions as way of reconciling the difference between long run and short run. This time, I'm just going to show actual results of the information transfer model (ITM) based on a somewhat idealized version of the US economy split into two domains: 1960-1980 and 1980-2000.



Sumner breaks monetary expansion into four scenarios (his A, B, C, D with some shorthand notation for his arguments with _i_ being inflation rate, _n_ being NGDP growth rate, _r_ being nominal interest rates and _P_ being the price level -- which of course has growth rate _i_):

-   A: Increase in the rate of expansion of the money supply (i ↑, n ↑, r ↑)
-   B: Increase in the rate of expansion of the money supply with sticky prices (long run i ↑, r ↑)
-   C: One time increase in the money supply (P ↑, NGDP ↑, r →)
-   D: One time increase in the money supply with sticky prices (P →, r ↓, long run = P, r)

I broke the scenarios up in a way that was more relevant to the information transfer model:

1.  Increase in the rate of expansion of the monetary base with small base (1970s)
2.  Increase in the rate of expansion of the monetary base with large base (1990s)
3.  One time increase in the monetary base with small base (1970s)
4.  One time increase in the monetary base with large base (1990s)

For 1 and 2, here are the results (baseline are the dotted lines, _n_ is red, _r_ is dark blue, _i_ is green ... real rates are also shown in light blue but are not relevant for our discussion here):


![](<media/rates - rate increase.png>)

We can see that an increase in the rate of expansion raises nominal interest rates _r_ (dark blue) when the base is small, but lowers them when the base is larger. In both cases it raises the rate of inflation as well as the rate of NGDP growth, but by a smaller amount for both metrics when the base is large. In the long run we have a fall in inflation and NGDP growth (because increasing the base growth rate makes the base even larger, making the price level even "stickier" in the information transfer model). The one time increase has less strange long run behavior. Here are the results for 3 and 4 (baseline are the dotted lines, _n_ is red, _r_ is dark blue, _i_ is green):


![](<media/rates - one time.png>)

A one-time increase in the base has the effect of lowering the inflation rate even though the price level increases. This may seem odd, but it makes sense if you think of the previous rate of growth was a percentage increase of the lower base level, thus the same magnitude increase would be a smaller percentage increase of a larger number \[1\]. The interesting thing is that nominal interest rates again go in opposite directions in the 1970s (up) and the 1990s (down), so there isn't much difference between the increase in rate (1, 2) and the one-time increase (3, 4) scenarios.



I'll summarize the effects using the notation above (I **bolded** the differences between the model and Sumner's arguments):

1.  i ↑, n ↑, r ↑
2.  short run i ↑, n ↑, **r  ↓**
3.  P ↑, NGDP ↑, **r ↑**
4.  **P ↑**, r ↓, long run = P, r

Let's discuss the differences:



-   **Scenario 2/B** Sumner is vaguest about this scenario. He effectively adds and then removes the sticky prices assumption ("assume that prices are sticky ... Trend rates by definition involve long periods of time, and prices are flexible over long periods of time"). Additionally he makes the identification of this scenario with the "great inflation" -- which is paradoxical with the sticky prices assumption since prices are increasing at the fastest rate in the post-war economy. Overall, the ITM says that this scenario is similar to scenario 4/D.
-   **Scenario 3/C** Sumner says nominal interest rates are unchanged. The ITM says they increase because the increase in NGDP is not proportional to the increase in the base (it is somewhat greater). There is some point between 1970 and 1990 where the effect goes from an increase to a decrease in interest rates because the size of the NGDP increase goes from being larger to being smaller in proportion to the size of the base increase. Sumner goes from unchanged rates to a fall in rates as stickiness is turned on (4/D), the ITM goes from a rise to a fall as "stickiness" is turned on.
-   **Scenario 4/D** Sumner says that the price level is unchanged (sticky prices) while the ITM says they go up a bit. I think this comes down to a question of how sticky prices are. Sumner has absolute stickiness, the ITM has just 'some' stickiness.

Overall, I'd say the ITM captures a lot of what Sumner is saying. Sticky prices can be mapped onto the large monetary base/low inflation/high information transfer index scenario of the period 1980-2000 in the ITM. Especially if you consider his core aim: _to understand how easy money can both raise and lower interest rates_. The information transfer model allows both to happen. One key difference is that this effect is path dependent in the information transfer model. It depends in part on the size of the monetary base relative to the size of the economy. 



While Sumner likely believes all four scenarios could have occurred any time between 1960 and 2000, the ITM reserves more traditional quantity theory reasoning (easier money raises rates) to the first half of that period and more IS/LM-based reasoning (easier money lowers rates) to the second half. The key parameter is again the [information transfer index](http://informationtransfereconomics.blogspot.com/2013/09/the-liquidity-trap-and-information-trap.html) (see also [here](http://informationtransfereconomics.blogspot.com/2013/07/recovering-quantity-theory-from.html)).



\[1\] It is certainly possible to have a one time increase that keeps the inflation rate continuous. I don't know if this is what Sumner meant by a one-time increase, but he rather carefully shifts to talking about the price level instead of the inflation rate when he discusses scenarios C and D so I believe he really did mean a one-time lump sum addition to the base time series (which is what I implemented above).
