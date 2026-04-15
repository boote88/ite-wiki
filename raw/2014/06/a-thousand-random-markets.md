---
title: A thousand random markets
date: 2014-06-25T12:24:00.000-07:00
updated: 2014-06-25T12:24:20.778-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/06/a-thousand-random-markets.html
---

In [this post](http://informationtransfereconomics.blogspot.com/2014/06/towards-arrow-debreu-mckenzie.html) \[1\], I set up a framework with a large number of markets $p_{i}: n_{i} \rightarrow s_{i}$ mediated by money so that we obtain (for the individual markets) the differential equations









In  \[1\], I made the approximation that the $a_{i}$ could be replaced by their average $\bar{a}$ and therefore the sum of the markets obeyed the approximate differential equation









Now I ask the question: _how well does this work?_ First, here is the sum of 10 random markets (with 10,000 random evaluations, blue points) where we take $n_{i} \sim m^{a_{i}}$ with a uniformly distributed $a_{i} \in [0,1]$. The approximate aggregate differential equation has solution $N \sim m^{\bar{a}}$ (shown in red):


![](<media/itm random markets 0.png>)

A region that represents 10% variation is shown in gray. We can see that this solution works pretty well, but I found that if we summed up 1000 random markets a systematic deviation for higher values $a_{i}$ and higher/lower values of $m$ begin to show up. Here are the results for $a_{i} \in [0, 0.5]$, $a_{i} \in [0,1]$, $a_{i} \in [0,2]$, and $a_{i} \in [0,4]$ which have $\bar{a} = $ 0.25, 0.5, 1.0 and 2.0, respectively.


![](<media/itm random markets 1a.png>)![](<media/itm random markets 1b.png>)

![](<media/itm random markets 1c.png>)![](<media/itm random markets 1d.png>)

A systematic deviation appears for small/large values of $m$ that is more apparent for larger values of $a_{i}$.  The source of this is not mysterious: for larger values of $m$, $m^{\text{max } a_{i}}$ tends to dominate while for smaller values of $m$, $m^{\text{min } a_{i}}$ tends to dominate. Still, for 10% shifts from the reference point $(m^{ref}, N^{ref})$, it remains a remarkably good approximation.



The markets with high values of $a_{i}$ would, in the long run, come to dominate the economy (e.g. if the market for apples went as $n_{apples} \sim m^{4}$, the entire economy would quickly become just apples). This doesn't appear to happen in diversified economies \[2\] (it might be true of e.g. oil-based economies), which implies there is a constraint on the values of the $a_{i}$. The interesting thing is that this constraint appears to make the macro formulation (the aggregate market) more accurate than the sum of individual markets -- i.e. there is an enforcement mechanism that makes the individual markets behave more like the average in diversified economies.











instead? Does that then have a relationship with $\kappa (M, N)$? A uniform logarithmic distribution is related to e.g. Benford's law. I will look into all of this in a future post.



\[2\] This is almost a circular definition: diversified economies are economies that haven't had one commodity or product take over their economy. However, it seems that diversified economies stay diversified -- that is the sense of the statement.
