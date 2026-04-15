---
title: Sleight of hand with the regulator
date: 2016-06-10T10:55:00.000-07:00
updated: 2016-06-10T11:04:50.095-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/06/sleight-of-hand-with-regulator.html
---

Just to make explicit the switch from the ordinary mean for the ensemble average to the geometric mean in the time average in [Ole Peters paper](https://arxiv.org/abs/1011.4404) on the resolution of the St Petersburg paradox ([that I talked about yesterday](http://informationtransfereconomics.blogspot.com/2016/06/regulators.html)), compare equations (5.2) and (5.7)








The probabilities $p_{i}$ of each $r_{i}$ are inserted (there is a tiny subtlety here, but the result is as if one had just mapped $r_{i} \rightarrow N p_{i} r_{i}$ in one case and $r_{i} \rightarrow &nbsp;r_{i}^{T p_{i}}$ in the other) as one would for an ordinary mean and a geometric mean (absorbing the $1/N$ and $1/T$, respectively):









There is a notational difference designating the time average, but we could re-write (5.7a) as






Note that $T$ is a dummy index (it is taken to dimensionless infinity later just like $N$), so WOLOG we can take $T \rightarrow N$ and the previous equation can be rewritten:






Peters takes the logarithm of both (5.2) and (5.7) and $N \rightarrow \infty$ to obtain the final result










The first sum diverges. The second sum converges because the infinity has been regulated






The regulator entered at the beginning -- by taking the geometric mean.
