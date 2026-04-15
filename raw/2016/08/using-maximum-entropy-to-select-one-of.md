---
title: Using maximum entropy to select one of multiple equilibria
date: 2016-08-23T16:00:00.000-07:00
updated: 2016-08-23T16:00:18.079-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/08/using-maximum-entropy-to-select-one-of.html
---

Some time ago, [I mentioned the idea](http://informationtransfereconomics.blogspot.com/2014/06/great-review-of-big-ideas-in.html) \[1\] that maximum entropy could select a particular Arrow-Debreu equilibrium when there are many available; I thought I'd work through a specific example where that could work using a simple 2D Edgeworth box. Let's assume a utility function for agent 1 (borrowed from [here \[pdf\]](http://coin.wne.uw.edu.pl/jhagemejer/wp-content/uploads/2013_micro_lecture6_exchange.pdf)):



11212\-8


with g1 and g2 exchanged for the other agent. The offer curves (blue, yellow for the two agents) in the 2D Edgeworth box look like this (for an initial endowment given in the pdf link above):



![](<media/edgeworth and offer curves 1.png>)

These curves intersect in 4 points, three of which are very close to each other (and hard to see). Which equilibrium relative price (slope through the initial endowment and the point) does the market select? Traditional economics lacks a solution to this problem -- all three are viable equilibria. However, the point in the center of the triplet of points has higher entropy (consider the joint entropy of the distributions with a probability of finding an infinitesimal unit of good 1 with agent 1 versus agent 2 and likewise for good 2). You can see that if you zoom in on those points; I show an information entropy level curve (unconstrained maximum in the center of the Edgeworth box) as a dotted gray line.



![](<media/edgeworth and offer curves 2.png>)

The point in the middle is the maximum entropy point, subject to all the constraints in the utility maximization problem.

...

**Footnotes**

\[1\] I also mentioned it [here](http://informationtransfereconomics.blogspot.com/2014/06/towards-arrow-debreu-mckenzie_23.html). At that link, I also mentioned a potential solution to the so-called [aggregation problem](https://en.wikipedia.org/wiki/Aggregation_problem) where one looks at [traces](https://en.wikipedia.org/wiki/Trace_\(linear_algebra\)) (differential volume elements) -- those volume elements would be related to the [state space volumes I use to look at maximum entropy](http://informationtransfereconomics.blogspot.com/2015/10/when-is-intertemporal-budget-constraint.html). This footnote is intended mostly as a note to myself.
