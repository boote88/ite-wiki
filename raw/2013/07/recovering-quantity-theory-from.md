---
title: Recovering the quantity theory from information transfer
date: 2013-07-02T10:55:00.000-07:00
updated: 2013-07-02T10:55:34.618-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/07/recovering-quantity-theory-from.html
---

In this post, I see where the information transfer model of the quantity theory of money (ITM + QTM) reduces to the traditional QTM. I will take $ P = P_0 e^{i t}$, $ Q^{d} = Q^{d}_{ref} e^{r t}$, and $ Q^{s} = Q^{s}_{ref} e^{r_0 t}$ where $i$ is the growth rate of the price level (inflation), $r$ is the NGDP growth rate and $r_0$ is the growth rate of the monetary base. Using the [equations here](http://informationtransfereconomics.blogspot.com/2013/06/this-is-getting-interesting-monetary.html), we obtain 





Taking the limit as $t \rightarrow \infty$ (the long run) one can show that the leading terms are 





For $\kappa = 1/2$, the rate of the price level increase is $ i \approx r_0$, which is the main result of the traditional [quantity theory of money](http://en.wikipedia.org/wiki/Quantity_theory_of_money). I would like to point out here that the quantity theory of money in the information transfer framework does not require $\kappa = 1/2$, hence the ITF + QTM [can describe the observed deviation for low inflation economies](http://informationtransfereconomics.blogspot.com/2013/06/which-is-failing-itm-or-qtm.html). 



More interestingly, if we look at the ratio of NGDP growth rate to the growth rate of the price level $r/i$, with $r = i + R$ where $R$ is the real growth rate for large $i$, we find that 





such that $\kappa = 1/2$ for economies with high growth in the price level -- and since $\kappa = 1/2 $, we find that $i \approx r_0$ and recover the traditional quantity theory of money.



The ITM + QTM approach has an additional result that says that for countries well-approximated by the traditional quantity theory of money, $r \approx 2 r_0$, or $r/r_0 \approx 2$, which is roughly true for the US since the depression (data are from FRED, I used GNP for years before the 1950s, and by $\Delta_y$ I mean the continuously compounded annual rate of change):

![](<media/Quantity Theory information transfer testing some stuff.png>)

The gray line is $r/r_0 = 2$, the average of $r/r_0 = 1.87$ is shown as the red line and the dashed red line is the post-1980 average $r/r_0 = 1.31$. This lower value explains the deviation from the diagonal line (the traditional QTM) in the graphs in [this post](http://informationtransfereconomics.blogspot.com/2013/06/which-is-failing-itm-or-qtm.html). It is not that countries with lower inflation rates don't obey the QTM. Countries with lower inflation rates apparently tend to have monetary policies that are too tight for a traditional QTM, but they can be described by a ITM + QTM theory with larger $\kappa$. From the ratios above, the average $\kappa = 0.53$ over the entire period shown, but the post-1980 average has been  $\kappa = 0.76$. Why this happens is not determined by the model, which only says that if $r/r_0 \approx 2$, then the traditional QTM is a good theory and that for high inflation rates, $r/r_0 \rightarrow 2$ so the traditional QTM works for countries with high growth in the price level. (But the traditional QTM does not necessarily follow for countries with high monetary base growth rates! Large $i \implies$ QTM, but large $r_0$ requires other knowledge about the economy like $r$ in order to see if $i$ is large and the QTM applies, or $\kappa \sim r_0/r \approx 1/2$ and the QTM applies.)



Note also that even the (shown) seasonally adjusted ratio is highly volatile -- likely illustrating one of the reasons the Fed doesn't target e.g. M2. It is also ironic that the point when Milton Friedman's ideas supposedly were at their peak was the point when the US started deviating more from the traditional quantity theory of money.
