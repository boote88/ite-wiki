---
title: Economic temperature functions
date: 2016-07-30T13:01:00.002-07:00
updated: 2016-09-22T09:46:41.367-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/07/economic-temperature-functions.html
---

There has been something that has bothered me about the temperature function in the partition function approach last used [here](http://informationtransfereconomics.blogspot.com/2016/07/an-ensemble-of-labor-markets.html) \[1\]: $f(\ell) = \log \ell &lt; 0$ for $\ell &lt; 1$ (or in [the original application](http://informationtransfereconomics.blogspot.com/2014/06/the-macroeconomic-partition-function.html) \[2\] in terms of money supply $m$). Typically the labor supply $\ell$ is large (millions of people employed), so this isn't a big deal. However it is possible for the "temperature" to go negative, which is a theoretical problem for small $\ell$. In thermodynamics, the analogous function is $f(T) = 1/T$, which is always positive.



Therefore I tried a different function $f(\ell) = \log (\ell + 1)$ (solid) which stays positive and approaches the original function (dashed) for $\ell \gg 1$:



![](<media/ite partition function labor market 1 -different model for temp-.png>)

The impact was fairly small on the results of \[1\] -- the largest difference comes in the ensemble average productivity $\langle p \rangle$ (right/second is from \[1\], left/first is new calculation):



![](<media/ite partition function labor market 7 -different model for temp-.png>)![](<media/ite partition function labor market 7.png>)

There was negligible impact on the other results -- the unemployment rate even showed a slight improvement (first is new calculation, second is from \[1\]):



![](<media/ite partition function labor market 5a -different model for temp-.png>)
![](<media/ite partition function labor market 5.png>)

Overall, a minor impact empirically, but fairly important theoretically.

...

**Update 22 September 2016**

I should note that if $A \rightleftarrows L$ with IT index $p$, we have

$$<br />
A = A_{ref} \left( \frac{L}{L_{ref}} \right)^{p}<br />
$$

If $L \equiv L_{ref}&nbsp;+ \ell$, then we can rewrite the previous statement as

$$<br />
A \sim \exp \left( p \log (\ell + 1) \right)<br />
$$

so that the original motivation for the partition function (in \[2\] above) would tell us that $f(\ell) = \log (\ell + 1)$.
