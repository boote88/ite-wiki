---
title: "Dotting i's and crossing t's"
date: 2013-07-19T11:36:00.002-07:00
updated: 2013-07-19T11:36:51.901-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/07/dotting-is-and-crossing-ts.html
---

Given that my primary source of pageviews is no longer a Russian indexing bot, I thought I should dot some i's and cross some t's. I realized I hadn't been completely rigorous in the fitting (and reporting of the fit parameters) in some of the previous posts. Specifically, the prescription that 



left out a normalization factor/units of measurement (effectively taken to be $C\_0 = 1 \\text{ G}\$$ in the previous results). There is an overall normalization to the CPI (and GDP deflator) that I mentioned before, as well as the reference constants $Q^s_{ref}$ (the reference constant $Q^d_{ref}$ can be subsumed into the CPI normalization). That means that there are effectively three degrees of freedom in the model.&nbsp;</div>
$$ P = \\frac{1}{\\kappa} \\left( \\frac{Q^d\_{ref}}{Q^s\_{ref}} \\right) \\left( \\frac{Q^s}{Q^s\_{ref}} \\right)^{1/\\kappa - 1} $$<br />
<div style="text-align: justify;">
The fit parameters with this form of the model are (using the FRED data sets for CPI less food, energy normalized to 1 instead of 100, the St. Louis Adjusted Monetary Base and the nominal GDP): $C_0 = 1.17 \text{ G}$$, $Q^d_{ref} / Q^s_{ref} = 1.38$, and $Q^s_{ref} = 732.3 \text{ G}\%%MATH_BLOCK_3%%? Well, one way to justify it is to invoke an anthropic principle: the reason these constants are what they are is because we are near the time when the quantity theory of money was discovered and so $\\kappa$ must be approximately $1/2$.

Additionally, the solution of the differential equation, Equation 19, [here](http://arxiv.org/pdf/0905.0610v2.pdf) left out mentioning the assumption that $\kappa$ was slowly varying, so that $\kappa$ can be taken outside the integral. The solution to the differential equation actually has a closed form with $\kappa$ taken to be the first equation in the post using this integral 

$$
\int \frac{dQ^s}{Q^s (c_0 + \log Q^s)} = \log (c_0 + \log Q^s)
$$

I will explore that in a future post.

Here are the graphs, as promised (the blue lines and the white surface are from the model, green is the empirical result using the CPI less food, energy and the red dashed line assumes $\kappa$ is constant from 1960 ... I also show the inflation rate and price level graph in both linear and log scale):
![](<media/price level best fit linear scale us.png>)
![](<media/price level best fit us.png>)
![](<media/price level inflation us.png>)
![](<media/price level surface 1.png>)
![](<media/price level surface 3.png>)

![](<media/price level surface 2.png>) Note that the results look essentially the same as before -- there are no changes to the previous conclusions.
