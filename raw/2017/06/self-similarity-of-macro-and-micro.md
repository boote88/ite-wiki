---
title: Self-similarity of macro and micro
date: 2017-06-28T12:06:00.000-07:00
updated: 2017-06-28T12:06:25.504-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/06/self-similarity-of-macro-and-micro.html
---

One of the things I first noticed when I started studying economics was the strange fact that the macroeconomic AD-AS model has some formal similarities to a simple microeconomic supply and demand model. In the AD-AS model, the sum of hundreds of markets for hundreds of goods behaves a bit like a single market for a single good with inflation representing the changes in price. The IS-LM model is another diagrammatic model that is formally similar supply and demand.



If you think about it, there is no real reason this has to be true. For example, DSGE models represent macro models that are not formally similar to supply and demand diagrams. Indeed, it is essentially the [fallacy of composition](https://en.wikipedia.org/wiki/Fallacy_of_composition) to assume the whole works the same way as the sum of its parts. But the other interesting thing is that complex systems frequently exhibit this kind of [self-similarity](https://en.wikipedia.org/wiki/Self-similarity) (just Google "[self-similarity in nature](https://www.google.com/search?q=self-similarity+in+nature&tbm=isch)" for a taste).



I was thinking about that while I was playing around with the partition function/ensemble equations for the information equilibrium model on a flight home from DC the other day. My original intent was to try to answer the question of which distribution of states preserves the scale invariance of the individual markets (so as to maybe suggest which distribution we should think about with regard to [statistical equilibrium](http://informationtransfereconomics.blogspot.com/2016/07/a-statistical-equilibrium-approach-to.html)), but I ended up deriving a fascinating result.



Most of the preceding was just to set the mood. Let's dive in to a short derivation. I will start from [here](http://informationtransfereconomics.blogspot.com/2016/09/balanced-growth-maximum-entropy-and.html) (which also goes into the justification of the starting point). Consider an ensemble of markets (information equilibrium relationship) $A_{i}$ with a single factor of production $B$ and IT indices $k_{i}$ so that










Now we use the partition function $Z(B)$ to aggregate the markets. The partition function itself is:






Again, this is justified in the previous link. However the main point is that we assume the economy has a measurable and meaningful growth rate. If economic growth is considered to be a reasonable thing to talk about in equilibrium, then this particular approach codifies that fact in terms of a unique maximum entropy distribution.



Now let's look at some pieces we'll need. First there's the ensemble average value of $A$:






where $\alpha$ is defined as the sum of the coefficients $A^{(i)}_{0}$. The average IT index is






Where I used the fact that $d \log B/B_{0} = dB/B$. Finally, the derivative of the average value of $A$ with respect to $B$ is:














That is to say the ensemble average (2) is formally similar to the individual markets (1). Equation (2) is much more complex (the IT index depends on $B$), but over short periods of time where $B$ doesn't change quickly the ensemble equation can be treated as a single information equilibrium relationship.



Since you can [derive a supply and demand diagram](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html) from the information equilibrium relationship ([under certain assumptions](http://informationtransfereconomics.blogspot.com/2017/04/its-production-input-no-its-market-good.html)), this could be seen as a short run AD-AS model. But more generally, we have a "self-similarity" in the behavior of individual micro markets and a macro ensemble of markets.



PS This basically solves something I was looking into almost exactly three years ago in these three posts: [here](http://informationtransfereconomics.blogspot.com/2014/06/towards-arrow-debreu-mckenzie.html), [here](http://informationtransfereconomics.blogspot.com/2014/06/towards-arrow-debreu-mckenzie_23.html) and [here](http://informationtransfereconomics.blogspot.com/2014/06/towards-arrow-debreu-mckenzie_27.html).



PPS I'm sorry about the slowdown in posting of late. I've become much busier with work (and I'm working on a really fun R&D effort).
