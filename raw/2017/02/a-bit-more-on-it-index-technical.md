---
title: A bit more on the IT index (technical)
date: 2017-02-15T12:00:00.000-08:00
updated: 2017-02-15T12:00:13.884-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/02/a-bit-more-on-it-index-technical.html
---

There are a couple of loose ends that need tying up regarding the IT index. One of which is the [derivation of the information equilibrium condition](http://informationtransfereconomics.blogspot.com/2013/04/the-information-transfer-model.html) (see also [the paper](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html)) with non-uniform probability distributions. This turns out to be relatively trivial and only involves a change in the IT index formula. The information equilibrium condition is










with $\sigma_A$ and $\sigma_B$ being the number of symbols in the "alphabet" chosen uniformly, we have






where $p_{i}^{(A)}$ and $p_{j}^{(B)}$ represent the probabilities of the different outcomes. The generalization to continuous distributions is also trivial and is left as an exercise for the reader.



However, while it hasn't come up in any of the models yet, it should be noted that the above definitions imply that $k$ is positive. But it turns out that we can handle negative $k$ by simply using the transformation $B \rightarrow 1/C$ so that:






That is to say an information equilibrium relationship $A \rightleftarrows B$ with a negative IT index is equivalent to the relationship $A \rightleftarrows 1/C$ with a positive index.
