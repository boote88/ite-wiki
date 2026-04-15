---
title: The urban environment as information equilibrium
date: 2016-06-13T20:24:00.001-07:00
updated: 2016-06-13T20:27:48.863-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/06/the-urban-environment-as-information.html
---

[Cameron Murray](http://www.fresheconomicthinking.com/2016/05/time-to-throw-out-standard-urban.html) wrote a post a couple weeks ago that made me think about applying information equilibrium to urban economics. Cameron tells us "\[t\]he workhorse model of urban economics is the Alonso-Muth-Mills (AMM) model of the mono-centric city" and then goes on to look at some of its faults. Here's his picture:



![](<media/planConcept -1-.png>)

Let's tackle this with the information equilibrium framework.



Let's set up the information equilibrium system (market) $h : R \rightleftarrows S$ where $h$ is building height (proxy for density), $R$ is distance (range) from the center and $S$ is the supply of housing (housing units). And let's assume $R$ varies slowly compared to $S$ -- i.e. transportation improvements and new modes (that fundamentally change the city's relationship with distance) happen slowly compared to adding housing supply. This puts us in the partial equilibrium regime with $R$ as a "constant information source" (see [the paper](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html)). Height $h$ is the detector of information flowing from the distance from the center to the housing supply; in economics, we think of this as a "price".



The "market" above is shorthand for the information equilibrium condition (with information transfer index $k$)






which we can solve for slow changes in $R$ relative to $S$ (and then plug into the "price" $h$) to obtain (with free parameters $R_{0}$ and $S_{ref}$ are model parameters):







![](<media/urban econ.png>)

You could of course substitute housing price $p$ or density $\rho$ for $h$ (or more rigorously, set up information equilibrium relationships $p \rightleftarrows h$ or $\rho \rightleftarrows h$ so that e.g. $p \sim h^{\alpha}$ so that $p \sim \exp \; -\alpha \Delta R$).



Now markets are not necessarily ideal and therefore information equilibrium does not hold exactly. In fact, it fails in a specific way. The observed height $h^{*} \leq h$ (because the housing supply $S$ can only at best receive all of the information from $R$, i.e. $I(R) \geq I(S)$, a condition called non-ideal information transfer), so what we'd see in practice is something like this:



![](<media/urban econ 1.png>)

Here's a logarithmic scale graph:



![](<media/urban econ 2.png>)

This is not too different from what is observed (assuming price is in information equilibrium with building height $p \rightleftarrows h$) from [here \[pdf\]](http://www.sas.upenn.edu/~holgers/urban/muth_mills.pdf):



![](<media/prices nyc.png>)

In short, information equilibrium provides a pretty good first order take as an urban economic model. You can see that height restrictions and other zoning ordinances or preserved green space end up impacting the observed height negatively -- i.e. non-ideal information transfer.
