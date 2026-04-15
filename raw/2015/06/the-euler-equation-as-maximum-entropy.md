---
title: The Euler equation as a maximum entropy condition
date: 2015-06-30T17:00:00.000-07:00
updated: 2015-09-18T14:21:51.684-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/06/the-euler-equation-as-maximum-entropy.html
---

In the discussion of the RCK model on these [two](http://informationtransfereconomics.blogspot.com/2015/06/ramsey-model-and-unstable-equilibrium.html) [posts](http://informationtransfereconomics.blogspot.com/2015/06/the-importance-of-transversality.html) I realized the Euler equation could be written as a maximum entropy condition. It's actually a fairly trivial application of the [entropy maximizing version of the asset pricing equation](http://informationtransfereconomics.blogspot.com/2015/05/the-basic-asset-pricing-equation-as.html):





To get to the typical macroeconomic Euler equation, define $\alpha_{i}/\alpha_{j} \equiv \beta$ and re-arrange:






The price at time $t_{j}$ divided by the price at time $t_{i}$ is just (one plus) the interest rate $R$ (for the time $t_{j} - t_{i}$), so:








The intuition behind the traditional economic Euler equation is (borrowed from these [lecture notes](http://web.stanford.edu/~chadj/Consumption2009-11-25.pdf) \[pdf\])

> _The Euler equation essentially says that \[an agent\] must be indifferent between consuming one more unit today on the one hand and saving that unit and consuming in the future on the other \[if utility is maximized\]._

The intuition for the maximum entropy version is different. It does involve the assumption of a large number of consumption periods (otherwise the intertemporal budget constraint wouldn't be saturated), but that isn't terribly important. The entropy maximum is actually given by (Eq. 4 at the link, re-arranged and using $p_{j}/p_{i} = 1 + R$):






The form of the utility function $U$ allows us to transform it into the equation above, but this is the more fundamental version from the information equilibrium standpoint. This equation says that since you could be anywhere along the blue line between $c_{j}$ maximized and $c_{i}$ maximized on this graph:



![](<media/euler eq as entropy.png>)

the typical location for an economic agent is in the middle of that blue line \[1\]. Agents themselves might not be indifferent to their location on the blue line (or even the interior of the triangle), but a maximum entropy ensemble of agents is. Another way to put it is that the maximum entropy ensemble doesn't break the underlying symmetry of the system -- the interest rate does. If the interest rate was zero, all consumption periods would be the same and consumption would be equal. A finite interest rate transforms both the coordinate system and the location of maximum entropy point. You'd imagine deforming the n-dimensional simplex so that each axis was scaled by $(1 + r)$ where $r$ is the interest rate between $t_{i}$ and $t_{i + 1}$.



**Footnotes:**



\[1\] The graph shown is actually for a large finite dimensional system (a large, but finite number of consumption periods); the true entropy maximum would fall just inside the blue line/intertemporal budget constraint.
