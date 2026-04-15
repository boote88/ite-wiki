---
title: "What role does the information transfer index play?"
date: 2013-06-19T16:56:00.000-07:00
updated: 2013-06-19T16:56:40.598-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/06/what-role-does-information-transfer.html
---

Other than the solutions to the ODE (see Eqs. 8 and 9 [here](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html)) for constant information source/destination, there is the [solution](http://informationtransfereconomics.blogspot.com/2013/04/are-thermodynamic-analogies-useful.html) for "floating" source/destination where: 


and

Let's assume $Q^s(t) \sim \exp r_0 t $ so that we have

and


I plotted these functions for $\kappa = 0.5, 1.0 and 2.0$ (Green, blue and red in the picture -- I orignally used a Wiener process with drift in place of the $r_0 t$, but then turned down the variance so it would be easier to see).

![](<media/solution 1.png>)

The dashed lines show $P$ and the solid lines show $Q^d$. The black dashed line (coinciding with the solid blue line) is $Q^s$. We basically get the story that when demand outpaces supply ($\kappa \lt 1$), the price level goes up. The opposite happens when $\kappa \gt 1$. My next thought, based on the idea that [no one knows where economic growth comes from](http://www.slate.com/blogs/moneybox/2012/08/06/nobody_knows_where_economic_growth_comes_from.html) (i.e. total factor productivity), was to ask: what if $\kappa$ controls the fluctuations of the economy from recessions to growth rates? So I fixed $Q^s(t) \sim \exp r_0 t $ and let $\kappa$ be a function of time (this time an [autoregressive process](https://en.wikipedia.org/wiki/Autoregressive_model); I'm all over the stochastic map):

![](<media/solution 2.png>)

Here we have the demand (blue solid) outpacing the supply (gray dashed) since $\kappa&lt; 1$ on average and the price level rising (blue dashed). Here is $\kappa$

![](<media/solution 2a.png>)

Now $\kappa = K_{\sigma}^{Q^s}/K_{\sigma}^{Q^d}$ where $K_\sigma \sim\log \sigma$ where $\sigma$ is the number of symbols used to encode information in the source/destination. This allows us venture a few hypotheses:

-   "Inflation" is when $\langle \kappa \rangle &lt; 1$, i.e. $\langle \sigma^s \rangle &lt; \langle \sigma^d \rangle$, or the number of symbols used in the demand information source is on average greater than the number in the supply information destination. ([This mechanism](http://informationtransfereconomics.blogspot.com/2013/05/rescaling-and-inflation.html) could still be involved.)
-   "Recessions" occur when $\sigma^d$ increases and/or $\sigma^s$ decreases such that $\kappa$ falls below its mean.
-   The selection rate of symbols must be lower for higher $\sigma$ in order for information transfer to remain "ideal" $I_{Q^d} = I_{Q^s}$; a recession in this sense is a slowdown in the selection rate of an increasing number of demand symbols (or an increase in the selection rate of a decreasing number of supply symbols).
-   For small amounts of inflation in a normal economy, this would imply the selection rate for supply symbols is typically slightly faster than the selection rate for demand symbols.

I don't currently know what the deeper meaning is here or if this will lead anywhere. It is interesting, though!
