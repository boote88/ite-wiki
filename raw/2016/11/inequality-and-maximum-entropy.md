---
title: Inequality and maximum entropy
date: 2016-11-20T10:35:00.001-08:00
updated: 2016-11-20T10:35:22.349-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/11/inequality-and-maximum-entropy.html
---

What does maximum entropy have to say about economic inequality? I am going to put forward a possible understanding of how inequality impacts macroeconomic fluctuations (aka the business cycle).



First we have to be precise with what we mean. One could say that the [maximum entropy distribution](http://informationtransfereconomics.blogspot.com/2016/04/maximum-entropy-distributions-reference.html) of income should be a Pareto distribution, which can be highly unequal. However, the uniform distribution is also a maximum entropy distribution of income. How can that be? Constraints. The Pareto distribution is the maximum entropy distribution of _x_ given a constraint on the value of ⟨log _x_⟩ (the average value of log _x_). The uniform distribution is the maximum entropy distribution given _x_ is (for example) constrained to be 0 ≤ _x_ ≤ _c_.



It is true that income appears to be Pareto distributed (at least in the tail, per [Pareto's original investigations](https://en.wikipedia.org/wiki/Vilfredo_Pareto)). Does this mean that inequality is an optimal equilibrium (i.e. maximum entropy)? Not exactly; it really just means that Pareto distributions of income are probably easiest to achieve given random processes. Let's build a simple model to look at the effects of inequality.



Let's say each agent (in the simulations below, I use _N_ \= 100 agents) has an income \[1\] that is drawn from a Pareto distribution, and can choose to spend some fraction of it in each time period on consumption. However, total consumption is limited (limited resources). This creates a bounded region in N-dimensional space. For three agents (_N_ = 3), it might look something like this:


![](<media/inequality and maxent 3.png>)

Over time, people adjust their consumption by a few percent (I used Brownian motion with σ = 5%), so the economy follows some random walk (blue squiggly line) bounded by this _N_–1 simplex (2-simplex for _N_ = 3). You could add recessions (correlated motion among the dimensions) or growth (expanding the region as a function of time), but these are not necessary for my point here. We will compare the Pareto distributed income with uniform income which would be bounded by a symmetric simplex (yellow):



![](<media/inequality and maxent 4.png>)

If we look at random walks inside each _N_\-dimensional space bounded by these simplices ([as I did here](http://informationtransfereconomics.blogspot.com/2015/09/a-random-walk-inside-simplex.html)), we can see a key difference in the instability (variance) in the total consumption. Here is a typical time series path (blue is Pareto, yellow is uniform):



![](<media/inequality and maxent 1.png>)

Note that these two time series were given the exact same set of log-linear shocks. It also manifests in a larger variation in the growth rate (average here is zero by construction, but as mentioned above, it could be positive), again blue is Pareto, yellow is uniform, and gray is the actual set of shocks applied to both series (which closely matches the uniform distribution):



![](<media/inequality and maxent 2.png>)

What is happening here? Well, the Pareto distribution effectively turns the _N_\-dimensional region into an _n << N_ dimensional region. The variation in a few of the large-income dimensions becomes much more important. We could also imagine they'd become more susceptible to coordination (e.g. panic/financial crisis) since it is easier to obtain a correlation among _n << N_ agents than _N_ agents.



What is also interesting is that one can easily visualize a couple of policies that address inequality in this framework. A progressive income tax or a progressive consumption tax would act as a uniformly-distributed (soft) bound on the allowed consumption states (income tax affects the bound itself, while consumption tax impacts the realized values of consumption). A universal basic income (UBI) would act as a lower bound. With these two policies, you could create an allowed region for the Pareto bound, making it more likely to be close to a uniform distribution sandwiched between the two. The figure below shows this with a 100% marginal income tax rate (red bound) and a universal basic income (green bound); the constrained Pareto bound is in blue.



![](<media/inequality and maxent 5a.png>)

I am not saying this is exactly what is happening in reality. This is just a possible understanding in terms of the maximum entropy/information equilibrium framework.



**Footnotes**



\[1\] This could easily be reconstructed in terms of wealth inequality or whatever form of economic inequality you prefer.
