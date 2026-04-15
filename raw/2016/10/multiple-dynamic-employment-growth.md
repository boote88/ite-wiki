---
title: Multiple dynamic employment growth equilibria
date: 2016-10-27T18:00:00.000-07:00
updated: 2016-11-03T13:21:17.632-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/10/multiple-dynamic-employment-growth.html
---

As part of looking at understanding something [John Handley showed me](https://twitter.com/jwhandley17/status/790362626416967680) on Twitter (that I am still looking at), I started to look at the employment level equilibria in the same way I looked at the unemployment rate equilibrium in [this series of posts](http://informationtransfereconomics.blogspot.com/2016/10/dynamic-unemployment-equilibrium-and.html).



Note there are three differences -- each word in the noun phrase ...



_employment vs unemployment_

> We are looking at people employed, rather than unemployed.

_level vs rate_

> We are looking at the number of people employed, rather than the fraction of people unemployed.

_equilibria vs equilibrium_

> In the most significant difference, we are looking at multiple "entropy minima" in the growth rates rather than a single growth rate (or decline in the case of unemployment).

When I started working on this, I found that no line with a single growth rate was parallel to the employment level for the entire time series. For example, a line that is parallel since the Great Recession isn't parallel for the 1980s or 1990s (see graph below). This reflects the observation that the growth rate of employment (or analogously RGDP) seems to take a hit after recessions -- falling to a lower value.


![](<media/test line.png>)

So I windowed the data and looked for the growth rate that best matched the data (I did this by partitioning the data into bins parallel to each possible growth rate, and finding the spikiest \[minimum entropy\] distribution in the same manner as [here](http://informationtransfereconomics.blogspot.com/2016/06/unemployment-equilibrium.html)).



It turns out that over the period 1955 to 2016, we have roughly three different rates. These were 3.8%, 2.6%, and 1.6% with transition points roughly at 1981 and 2000. For the politically inclined, these downshifts coincide with the elections of Ronald Reagan and George W. Bush -- coincidence? The 1980s recessions were serious, so understandably could have lead to a permanent downshift in the growth rate. However, it is sometimes debated whether the early-2000s recession was really a recession at all. Anyway, here are the results:



![](<media/employment growth min entropy 1.png>)

I fit them to the sum of  a pair of [logistic functions](https://en.wikipedia.org/wiki/Logistic_function). Inside of these periods -- 1955 to 1981, 1981 to 2000, and 2000 to 2016 -- we have roughly a constant growth rate. We can then look at recessions (declines in the employment level) as logistic functions relative to that constant growth rate. If we do that, we can organize the employment data into a series of constant growth rate periods punctuated by recessions:



![](<media/employment growth min entropy 2.png>)![](<media/employment growth min entropy -fixed-.png>)

\[**Update 3 Nov 2016:** I fixed the previous graph. Mathematica chopped off the 1990 dip for some reason.\]



I would like to stress my use of the word **_organize_**. This is one particular model-dependent understanding of the employment data. There is no reason this data couldn't be consistent with e.g. a continuously falling employment growth rate.
