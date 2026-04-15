---
title: Information equilibrium in agent-based models
date: 2016-11-22T14:00:00.000-08:00
updated: 2016-11-22T14:00:27.434-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/11/information-equilibrium-in-agent-based.html
---

In [response to this post](http://informationtransfereconomics.blogspot.com/2016/11/inequality-and-maximum-entropy.html) (or at least the link to it on Twitter), Ian Wright [directed me to his paper](http://www.economics-ejournal.org/economics/journalarticles/2009-19) using a Closed Social Architecture (CSA) agent-based model based on random agent actions that happily included Mathematica code that I was able to get up and running in no time. Here is the abstract:

> _A large market economy has a huge number of degrees of freedom with weak micro-level coordination. The "implicit microfoundations" approach considers this property of micro-level interactions to more strongly determine macro-level outcomes compared to the precise details of individual choice behavior; that is, the "particle" nature of individuals dominates their "mechanical" nature. So rather than taking an "explicit microfoundations" approach, in which individuals are represented as "white-box" sources of fully-specified optimizing behavior ("rational agents"), **we instead represent individuals as "black box" sources of unpredictable noise subject to objective constraints ("zero-intelligence agents").** To illustrate the potential of the approach we examine a parsimonious, agent-based macroeconomic model with implicit microfoundations. It generates many of the reported empirical distributions of capitalist economies, including the distribution of income, firm sizes, firm growth, GDP and recessions._

My emphasis. This is essentially the idea behind [the maximum entropy approaches](http://informationtransfereconomics.blogspot.com/2015/10/utility-maximization-and-entropy.html) that underlie the information transfer framework. I decided to test for information equilibrium (IE) relationships in the outputs of the model (I did a simple version with only 100 agents and 100 time steps) and found a few. Specifically:



_NGDP ⇄ W_
_NGDP ⇄ U_
_NGDP ⇄ P_


where _W_ are total wages of employees, _U_ is the total number of people unemployed and _P_ is the total profit of firms. In each case, I took the IT index to be 1 (allowing it to vary doesn't change much). The first two are IE relationships I've previously observed in macro data; the last one is new. The first one is not that surprising -- total output in this model is effectively _NGDP = W + P_, and since _P_ is small (_W_ ~ 70% of _NGDP_), _W ~ NGDP_. In the following, the IE model is blue while the data is yellow \[1\]:



![](<media/IT model -CSA wages-.png>)

The other two are non-trivial:



![](<media/IT model -CSA profit-.png>)![](<media/IT model -CSA unemployment-.png>)

One wouldn't expect high unemployment to be associated with high output, and I'm not sure of the mechanism generating it (note that unemployment is very noisy in this model). Note that since _NGDP_ _⇄_ _U_ is a reasonable description, this let's us define a price level _p ~ NGDP/U_ per the IE version of the model. Here is an example trajectory for output in terms of unemployment _NGDP = f(U)_ and the corresponding price level _p = f(NGDP, U) = dNGDP/dU_:



![](<media/IT model -CSA unemployment- 6 price level.png>)![](<media/IT model -CSA unemployment- 6.png>)

I plan on trying to add growth to the CSA model so that we can see some non-trivial IE relationships with IT index _k_ ≠ 1.






PS As I was exploring, I came up with different things to look at, and since the model is stochastic, I didn't have the same outputs each time because I didn't seed the random number generator. Basically, the first 3 graphs in the post above are a single economy, the next 2 are a different economy (but correspond to each other), and the last two profit graphs and the two unemployment graphs in the footnote correspond to each other.





**Footnotes:**


\[1\] I ran the model several times and here are some example outputs for profit:



![](<media/IT model -CSA profit- 2.png>)![](<media/IT model -CSA profit- 3.png>)

![](<media/IT model -CSA profit- 4.png>)![](<media/IT model -CSA profit- 5.png>)

And here are a couple of output-unemployment models (corresponding to the last two profit graphs above):



![](<media/IT model -CSA unemployment- 4.png>)![](<media/IT model -CSA unemployment- 5.png>)
