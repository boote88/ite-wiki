---
title: Price growth (i.e. inflation) state distribution
date: 2016-10-08T15:50:00.001-07:00
updated: 2016-10-08T15:50:19.709-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/10/price-growth-ie-inflation-state.html
---

I have started looking at some price data from [Cavallo 2016](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi%3A10.7910%2FDVN%2FIAH6Z6) (related to MIT's billion price project) in order to make a better version of the graph [at the bottom of this post](http://informationtransfereconomics.blogspot.com/2016/03/does-saving-make-sense.html): an animation of the distribution of CPI changes among the components of CPI. Effectively, I want to try and visualize the equilibrium price change distribution (the [price state space](http://informationtransfereconomics.blogspot.com/2016/09/the-economic-state-space-mini-seminar.html)) of individual prices. [This](http://informationtransfereconomics.blogspot.com/2016/02/flexible-micro-wages-does-not-disprove.html) is also some relevant background reading (hitting on zero price changes) -- I claim that although individual prices are not "sticky", there is an equilibrium distribution ([a statistical equilibrium](http://informationtransfereconomics.blogspot.com/2016/07/a-statistical-equilibrium-approach-to.html) per Gregor Semieniuk).



Unfortunately, the files are really huge and my six year old desktop is choking on them; I'm in the process of finding a workaround. I managed to look at part of the data (it is price data from supermarkets from 05/2008 to 07/2010) and it largely shows a stable bimodal distribution (i.e. unchanging, not the specific distribution called a "[stable distribution](https://en.wikipedia.org/wiki/Stable_distribution)") of non-zero price changes.



![](media/pricedistribution.gif)

In talking about "equilibrium" (e.g. [here](http://informationtransfereconomics.blogspot.com/2016/10/keen-chaos-and-equilibrium.html)), we can think of the these price changes existing in an equilibrium distribution of price changes while individual prices are changing (similar to atoms being [in an equilibrium velocity distribution](https://en.wikipedia.org/wiki/Maxwell%E2%80%93Boltzmann_distribution) even though each atom is changing its speed with every collision).



If you've looked at the animation, you might have noticed a big change in April of 2010. I am not sure if that is an artifact of the way that I grabbed the data (effectively the first million entries in a CSV file) or a real event where over 60% of prices went up by about 10%. [The major world events](https://en.wikipedia.org/wiki/2010#April) include a downgrade in the course of the Greek debt crisis and the Deepwater Horizon oil spill, but these come near the end of the month. Does anyone else know of an event in April of 2010 that would affect supermarket prices that could do this to the distribution:



![](<media/price distribution cavallo.png>)![](<media/price distribution cavallo 2.png>)

It is possible that since I only have part of the data, it could be that the data I am looking at consists of just one store that decided to raise their prices by 10%. Anyway, I'm still investigating. Besides this single month of data, this seems to be a qualitative success of the "statistical equilibrium" approach.
