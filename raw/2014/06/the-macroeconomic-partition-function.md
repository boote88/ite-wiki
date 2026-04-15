---
title: The macroeconomic partition function and the information transfer index
date: 2014-06-27T13:26:00.000-07:00
updated: 2014-06-27T13:26:10.783-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/06/the-macroeconomic-partition-function.html
---

I've made [some remarks in the past](http://informationtransfereconomics.blogspot.com/2014/04/economics-is-neither-physics-nor.html) about how analogies between physics and economics only have merit inasmuch as they are useful. You might think: _here he goes down the rabbit hole with partition functions_. And that may be so. However, this is going to be a very useful analogy. Continuing from [this post](http://informationtransfereconomics.blogspot.com/2014/06/random-markets-and-partition-functions.html) where I realized that the sum (defining nominal output or NGDP)




[partition function](http://en.wikipedia.org/wiki/Partition_function_%28statistical_mechanics%29)




If you check out the link to the previous post, you'll realize there is a change to the first equation (I traded $-\log 1/m$ for $\log m$). The reason for this was because $N(m)$ should be the expectation value of an operator, not the partition function itself. I'll define the macroeconomic partition function to be:






Where the $n_{i}$ are the demands in the individual markets and $m$ is the money supply (it doesn't matter which aggregate at this point). The individual markets are the solutions to the equations:







as was shown in [this post](http://informationtransfereconomics.blogspot.com/2014/06/towards-arrow-debreu-mckenzie.html). One interesting thing is that the defining quality of these micro markets -- equation (3) leads [to supply and demand diagrams](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html) -- is homogeneity of degree zero in the supply and demand functions, which is one of the few properties that survive aggregation in the [Sonnenschein-Mantel-Debreu](http://en.wikipedia.org/wiki/Sonnenschein%E2%80%93Mantel%E2%80%93Debreu_theorem) theorem (see [my notes here](http://informationtransfereconomics.blogspot.com/2014/06/towards-arrow-debreu-mckenzie_23.html)).









which is related to the [information transfer index](http://informationtransfereconomics.blogspot.com/2013/04/the-information-transfer-model.html) $\kappa = 1/\langle a \rangle$. Additionally, the nominal economy will be the number of markets $N_{0}$ \[1\] times the expectation value of an individual market $m^{a_{i}}$, i.e.









First there is an interesting new analogy with thermodynamics: $\log m$ is playing the role of $\beta = 1/kT$. As $m$ gets larger the states with higher $a_{i}$ (high growth markets) become less probable, meaning that a large economy (with a large money supply) is more like a **_cold_** thermodynamic system. As an economy grows, it cools, which leads to slower growth (["the great stagnation"](http://informationtransfereconomics.blogspot.com/2014/02/phlogiston-economics-is-information.html) or ["secular stagnation"](http://informationtransfereconomics.blogspot.com/2013/11/secular-stagnation-and-eu.html)) and as we shall see a [bending of the price level vs money curve](http://informationtransfereconomics.blogspot.com/2014/02/it-really-does-seem-to-be-about-size-of.html) (low inflation in economies with large money supplies).



Let's take $N_{0} =$ 10 (left) and 100 (right) random markets with uniformly distributed $a_{i} \in [0,2]$ (this basically allows any $\kappa \geq 1/2$, see for instance [here](http://informationtransfereconomics.blogspot.com/2014/06/reconciling-expectation-and-information.html)) and plot the information transfer index $1/\langle a \rangle$, the price level $\langle a m^{a -1}\rangle$ and the nominal output $\langle N(m) \rangle$:



![](<media/ite partition function 1a.png>)![](<media/ite partition function 2a.png>)
![](<media/ite partition function 1b.png>)![](<media/ite partition function 2b.png>)
![](<media/ite partition function 1c.png>)![](<media/ite partition function 2c.png>)

In the first pair of graphs we can see the economies start out well described by the quantity theory ($\kappa = 1/2$) and move towards higher $\kappa$ as the money supply increases. However, the first part of that observation is because the lowest value of $\kappa$ allowed was 1/2 (i.e. $a_{max} = 2$); the move toward higher $\kappa$ is a more robust observation. We can see the bending of the price level vs money supply in the second pair of graphs. In the third pair of graphs, we can see the trend towards lower growth relative to the growth in the money supply.



The question I had was: _how well does this oversimplified picture work with real data?_ We have $N_{0}$ markets of equal size at $m = 1$ (arbitrary units), how well could it possibly work? **Pretty well, actually.** In fact, after normalizing the price level and scaling the money supply, the function $P = \langle a m^{a-1} \rangle$ almost exactly matches "the" [information transfer model](http://informationtransfereconomics.blogspot.com/2014/06/the-information-transfer-model.html) I've been using that incorporates an information transfer index that was [only "motivated" by information theory](http://informationtransfereconomics.blogspot.com/2014/03/how-money-transfers-information.html), not actually derived from it. In the current post, $\kappa$ arises out the individual microeconomic markets.



Here is the price level with the basic information transfer model and the partition function version:



![](<media/ite partition function 00.png>)

There is only a small deviation in the 1960s. Finally, here is the information transfer index:



![](<media/ite partition function 01.png>)

The green line represents "data", i.e. if we assume the functional form of $P(NGDP,M0)$, what value of $\kappa$ gives us the exact CPI.



With the partition function approach, we can see that reduced inflation with a large money supply (a thermodynamically colder system) as well as reduced growth are **_emergent_** properties. They do not exist for the individual markets. An economy with a larger money supply is more likely to be realized as a large number of lower growth states (higher entropy) than a smaller number of high growth states. This approach also resolves some of the issues at the end of [this post](http://informationtransfereconomics.blogspot.com/2014/06/a-thousand-random-markets.html) (the relationship between $\kappa$ and the exponents $a_{i}$).



\[1\] In the future, I might want to try to treat and economy where the number of markets is changing -- much like in the case of particle number in a quantum field.
