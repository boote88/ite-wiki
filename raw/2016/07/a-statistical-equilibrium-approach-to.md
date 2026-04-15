---
title: "\"A statistical equilibrium approach to the distribution of profit rates\""
date: 2016-07-13T12:30:00.000-07:00
updated: 2016-08-01T14:32:13.235-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/07/a-statistical-equilibrium-approach-to.html
---

That's the title of a paper \[[pdf](http://www.economicpolicyresearch.org/images/docs/research/political_economy/WP_2015-5_Statistical_Equilibrium_Profit_Rates.pdf)\] by Gregor Semieniuk (and his co-author) who tried to get a hold of me at the BPE meeting (which I was unfortunately unable to attend, but did make [some slides](http://informationtransfereconomics.blogspot.com/2016/02/slides.html)). The paper notes that the distributions of the rates of profit appear to have invariant distributions suggestive of statistical equilibrium; here's a diagram:


![](<media/stat eq.png>)


This diagram is reminiscent of the diagrams I've used when talking about the distribution of growth states in an economy, most colorfully illustrated at [this link](http://informationtransfereconomics.blogspot.com/2016/03/does-saving-make-sense.html) (and discussed [here](http://informationtransfereconomics.blogspot.com/2014/10/coordination-costs-money-causes.html) and [in my paper](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html); note that Gregor's diagram has a log scale for the y-axis).



![](media/Picture2.png)



In fact, it might be directly related. If we have a series of markets (or firms) where income $I_{k}$ is in information equilibrium with expenses $E_{k}$ with "price" $p_{k}$, i.e. $p : I \rightleftarrows E$, in general equilibrium we have










Therefore $p_{k}$ determines the rate of profit (difference between income and expenses). It determines how much bigger $I$ is given $E$. If $p = 1$, then profit is zero because income equals expenses. If $p &gt; 1$, the firm is profitable because $I &gt; E$; vice versa for $p &lt; 1$. In [the partition function approach](http://informationtransfereconomics.blogspot.com/2014/06/the-macroeconomic-partition-function.html) (also discussed in the paper and the link above), the "prices" represent growth states; here, the "prices" represent profit states. The distribution represents an equilibrium "temperature".



We'd also expect the profit states to have some distribution around a mean value, but have negative profit states to be over-represented due to non-ideal information transfer. This is as observed in the diagram from Gregor's paper. It is also observed in nominal growth data over time\*\* (figure from my paper linked above; also see [here](http://informationtransfereconomics.blogspot.com/2015/11/internal-devaluation-and-fluctuation.html)):



![](media/deval.png)



\*\* This implies a macroeconomy is ergodic: the distribution of temporal states are the same as distributions of ensembles of states.


...

**Update 01 August 2016**

Michael Williams sent me links to two of his (and co-authors') papers ([here](http://www.sciencedirect.com/science/article/pii/S0378437116301492) and [here](http://www.sciencedirect.com/science/article/pii/S0378437115002393)) where they look at the distribution of economic profit rates and firm growth rates. These appear to have well-defined distributions as in the paper from Semieniuk _et al_ above. The difference is that Williams _et al_ find that the distributions appear to be Cauchy distributions rather than Laplace distributions. I [noted](http://informationtransfereconomics.blogspot.com/2016/05/the-scales-of-sticky-wages.html) previously that the distribution of wage changes also appears (by eye -- I did no rigorous testing) to be Cauchy (plus perturbations).

Laplace distributions are maximum entropy distributions subject to the constraint on the absolute deviation _|Δ| = |x - μ|_ of the variable (profit rate in this case) from the mean. Semieniuk _et al_ also suggest the asymmetric Laplace distribution which is the maximum entropy distribution subject to a constraint on the average deviation (_Δ = x - μ_).

Cauchy distributions are "heavy-tailed" and are the maximum entropy distributions for random variables subject to a constraint on _log(1+Δ²)_ where _Δ = x - x₀_ (the Cauchy distribution has no mean, so there is a parameter _x₀_ that represents the "center").

In my view the Laplace distribution represents a "first order approximation" which is improved upon with the Cauchy distribution. However, I'd take a more agnostic view that what we have is some form of stable distribution (of which the Cauchy distribution is a particular example). Note that Mandelbrot showed that stable distributions appeared to fit various financial data. Here's a graph with a Cauchy (blue), stable (yellow), and skewed stable (green) distributions along with a Laplace distribution (gray dashed):

![](<media/cauchy and stable distributions.png>)
[Stable distributions](https://en.wikipedia.org/wiki/Stable_distribution) are stable in the sense that they have their own (more general) central limit theorem that doesn't require a finite variance.
