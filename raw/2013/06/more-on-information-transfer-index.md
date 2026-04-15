---
title: More on the information transfer index
date: 2013-06-22T11:49:00.000-07:00
updated: 2013-06-22T11:50:55.990-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/06/more-on-information-transfer-index.html
---

The information transfer index is defined as 

$$
\kappa = \frac{K_0 \log \sigma^s}{K_0 \log \sigma^d}
$$ 

where we are measuring information in the same units (defined by $K_0$). Now we take the floating information source solution 

$$
\frac{Q^{d}}{Q^{d}_{ref}} = \left(\frac{Q^{d}}{Q^{d}_{ref}}\right)^{1/\kappa}
$$ 

and solve for $\kappa$ 

$$
\kappa = \frac{\log  Q^{s}/Q^{s}_{ref}}{\log Q^{d}/Q^{d}_{ref}}
$$ 

I believe we can make the identification 

$$
\sigma^x \sim Q^{x}/Q^{x}_{ref}
$$ 

i.e. the "number of demand symbols" is basically proportional to the size of the demand which makes intuitive sense (well, to me). We next plot how $\kappa$ behaves vs $\sigma^s$ and $\sigma^d$. The colors indicate high magnitude (in red) or low magnitude (meaning zero, in blue) of the gradient. The line across the figure show where $\log \kappa = 0$ i.e. $\kappa = 1$.


![](<media/information transfer index.png>)[here](http://informationtransfereconomics.blogspot.com/2013/06/what-role-does-information-transfer.html)[this information](http://www.themoneyillusion.com/?p=20216)
[empirical data](http://research.stlouisfed.org/fred2/)![](<media/information transfer index 2.png>)

This is somewhat close to $\kappa = 1$ as we might expect for a large economy (although any value of $\kappa$ can be acheived given any $\sigma^s$). It seems we should be approaching 1 more monotonically as the scale of the economy grows.

![](<media/information transfer index 3.png>)

If we use

With the empirically defined $\kappa$ we get the picture above for the equilibrium price level $P$ (in an [AD/AS model](http://en.wikipedia.org/wiki/AD-AS_model)).



Do these results make sense? I would say no. But I'm going to think about it some more.
