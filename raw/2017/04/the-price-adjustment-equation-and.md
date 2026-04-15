---
title: The price adjustment equation and information equilibrium
date: 2017-04-09T15:22:00.002-07:00
updated: 2017-04-09T15:22:28.743-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/04/the-price-adjustment-equation-and.html
---

Ian Wright and I share a love of Mathematica, but after reading his \[1\] [recent post](https://ianwrightsite.wordpress.com/2017/04/08/supply-and-demand-in-historical-time/) and one that it references I think we might share a framework. In fact, I may want to rewrite the derivation of the information equilibrium relationship using his derivation of his \[2\] [price adjustment equation](https://ianwrightsite.wordpress.com/2017/04/04/setting-prices-in-the-chaos-of-the-market/). Here is Ian's derivation (that I LaTeX-ed up a bit):

> We need to translate this price adjustment strategy into something a bit more precise. Let $\Delta s$ be the change in the stock of corn (during a short period of time). And let $\Delta p$ be the change in the price of corn. We want to define $\Delta p$ (the price adjustment strategy) in terms of $\Delta s$ (the indicator of market demand relative to our level of production). 

> Clearly, if our prices are huge, in absolute terms, we should make bigger price adjustments compared to when our prices are tiny. So we want $\Delta p$ to be proportional to $p$. We write this as (i) $\Delta p \propto p$. 

> And, if our stock decreases then we should raise our prices (and vice versa); or, in other words, (ii) $\Delta p \propto - \Delta s$. 

> Finally, we should set the price of corn astronomically high if we’re completely running out of stock; that is, (iii) $\Delta p \propto 1/s$. (This implies that, in the hypothetical situation that our stock reaches zero, then the price of corn is infinity — meaning, quite correctly, that no amount of money can buy corn.) 

> Putting (i), (ii) and (iii) together we get the price adjustment equation: 

>  $\Delta p = - \eta \Delta s (p/s)$

> where $\eta$ is a constant of proportionality. We should give $\eta$ a name. Call it the elasticity of price with respect to excess supply ...

This price adjustment equation can be derived from the information equilibrium condition. I went through this derivation before [here](http://informationtransfereconomics.blogspot.com/2015/09/price-as-stochastic-process.html) in the context of stochastic processes, but just let me repeat it here with the notation changed a bit to match up with Ian's. Let's start with the information equilibrium condition



$$<br />
p \equiv \frac{\Delta d}{\Delta s} = k \; \frac{d}{s}<br />
$$


where $s$ is the stock, and $d$ is the demand for that stock. In the compact [information equilibrium notation](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html) I sometimes use, I write this condition as $p : d \rightleftarrows s$ (where $p$ is the "detector"). I also usually take the continuous limit $\Delta x \rightarrow dx$. Varying $p$ we obtain:



$$<br />
\Delta p = k \left( \frac{\Delta d}{s} - \frac{d}{s^{2}} \Delta s&nbsp;\right)<br />
$$

$$<br />
\frac{\Delta p}{p} = \frac{\Delta d}{d} - \frac{\Delta s}{s}<br />
$$


In the last line, I re-used the information equilibrium condition (i.e. $p = k \; d/s$). If demand is constant or at least large compared to changes (i.e. $d \gg \Delta d$), then the last line becomes:



$$<br />
\Delta p = - \Delta s \frac{p}{s}<br />
$$


which is Ian's price adjustment equation with $\eta = 1$. The information equilibrium version has $\eta = 1$ because of the original [scale invariance it manifests](http://informationtransfereconomics.blogspot.com/2016/10/invariance-under-inversion.html). However, Ian's equation follows from a slightly more general information equilibrium condition:



$$<br />
p \equiv \frac{\Delta d}{\Delta s} = k \; \frac{d^{\zeta}}{s^{\eta}}<br />
$$

which becomes:

$$<br />
\frac{\Delta p}{p} = \zeta \; \frac{\Delta d}{d} - \eta \; \frac{\Delta s}{s}<br />
$$

so that with $\Delta d \ll d$, we have

$$<br />
\Delta p = - \eta \Delta s \frac{p}{s}<br />
$$


Ian's price adjustment equation is both more general (it doesn't require $\eta = 1$) and less general (it doesn't account for changing demand $d$ for stock $s$, i.e. that $\Delta p = f(\Delta d, \Delta s)$). Also, whether or not scale invariance is an important aspect of economics is not known, so the more general equilibrium condition may be better empirically. Ian's derivation points to at least one way the information equilibrium condition may be generalized. 



Actually, [Ian asked via Twitter](https://twitter.com/ianpaulwright/status/851172240066564097) while I was writing this post:

> _One of the problems when specifying dynamic adjustment is there are too many reasonable equational forms. Does your approach help here?_

One could say the information equilibrium approach helps by connecting to underlying information theory thereby restricting the number of possible equation forms. The scale invariance is doing a similar thing (and could be used to build [generalizations a la effective field theory](http://informationtransfereconomics.blogspot.com/2016/03/effective-information-equilibrium-theory.html) (or see [here](http://informationtransfereconomics.blogspot.com/2014/02/i-quantity-theory-and-effective-field.html))). It does involve viewing the communication channel the market represents [slightly differently](http://informationtransfereconomics.blogspot.com/2015/03/the-price-system-as-communication.html). In the traditional view, the price contains information received from supply and demand; in the information transfer view, [the "communication" is between supply and demand](http://informationtransfereconomics.blogspot.com/2016/08/is-information-equilibrium-silly.html) (usually I put demand as the transmitter and supply as the receiver).



Do we believe in scale invariance or that the market represents an information processing system? If yes, the information equilibrium approach does help control the reasonable forms of equations (actually, this was part of [this blog's mission statement](http://informationtransfereconomics.blogspot.com/2013/04/an-informal-abstract-addition-why-now.html)). But if we think these other considerations aren't important, then they're just _ad hoc_ restrictions.



I personally believe the information theory framing is very useful and that scale invariance may be one of the [most important (defining, even) properties of economics](http://informationtransfereconomics.blogspot.com/2017/02/invariance-and-deep-properties.html) as a dynamical system (actually, "money" might be [abstractly viewed](http://informationtransfereconomics.blogspot.com/2015/12/money-is-that-which-is-conserved-via.html) as something that exists to maintain that scale invariance). However I understand this is probably a minority view. Still, it's not like Ian and I are on completely different pages here. (His simulations also manifest some [information](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-in-agent-based-model.html) [equilibrium](http://informationtransfereconomics.blogspot.com/2016/11/information-equilibrium-in-agent-based.html) relationships, and I think we have some of the same ideas about [statistical equilibrium](http://informationtransfereconomics.blogspot.com/2017/02/classical-econophysics.html).)



**_\*  \*  \*_**



A quick aside: Ian's price adjustment equation could be seen as an information equilibrium relationship in its own right where price is in information equilibrium with (one over) the stock. Ian's equation is:



$$<br />\frac{\Delta p}{\Delta s} = - \eta \; \frac{p}{s}<br />$$



which [we can say is](http://informationtransfereconomics.blogspot.com/2017/02/a-bit-more-on-it-index-technical.html) (taking $s \rightarrow 1/s'$):



$$<br />
\frac{\Delta p}{\Delta s'} = \eta \; \frac{p}{s'}<br />
$$



Which I'd write as $p \rightleftarrows 1/s$ or $p \rightleftarrows s'$ in [the compact notation](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html). Dealing with the minus sign is necessary because $\eta$ here represents an information transfer index and is necessarily positive as it the the ratio of the information content of a selection from the distribution of $p$-states to the information content of a selection from the distribution of $s'$ states.



**_\*  \*  \*_**



Ian also says in the post \[2\] above



> _There’s a simple moral to this story: **price adjustment alone does not solve the coordination problem.**_



Emphasis in the original. This something I agree with. In the information equilibrium view, and in an ideal market, prices simply measure changing demand and changing supply (we call it a "detector" of information flow and it's a ratio of the changing information in the demand distribution to the changing information in the supply distribution). However, the overall story is much more complex because there is no real guarantee e.g. all of the information in the signal sent by a change in the demand distribution is received by the supply distribution. This results in our information equilibrium condition being only a bound:



$$<br />
p \equiv \frac{\Delta d}{\Delta s} \leq k \; \frac{d}{s}<br />
$$


This is still useful via [Gronwall's inequality](http://informationtransfereconomics.blogspot.com/2016/06/gronwalls-inequality-and-information.html), but leads to [a much more nuanced take](http://informationtransfereconomics.blogspot.com/2015/01/is-market-intelligent.html) on the "information aggregation" problem the market is used to solve versus the "allocation" (coordination) problem the market is used to solve. It also leads to viewing supply and demand diagrams as "bounds" with the real price falling somewhere in the lower triangle:



![](media/sandd3.png)


and (for example) price time series being seen as [stochastic paths constrained by the bounds](http://informationtransfereconomics.blogspot.com/2015/09/price-movements.html).



**_\*  \*  \*_**



PS On a more speculative topic, information equilibrium [might be related to Generative Adversarial Networks](http://informationtransfereconomics.blogspot.com/2017/02/generative-adversarial-networks-and.html) in machine learning.
