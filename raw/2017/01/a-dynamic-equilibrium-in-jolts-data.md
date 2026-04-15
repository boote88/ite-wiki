---
title: "A dynamic equilibrium in JOLTS data?"
date: 2017-01-10T23:09:00.002-08:00
updated: 2017-01-11T16:29:43.696-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/01/a-dynamic-equilibrium-in-jolts-data.html
---

[Steve Roth linked](https://twitter.com/asymptosis/status/818849123071733764) to Ben Casselman in a Tweet about [the latest JOLTS data](https://www.bls.gov/charts/job-openings-and-labor-turnover/unemp-per-job-opening.htm#), and both brought attention to the fact that the ratio of unemployed to job openings appears to have flattened out; Steve also made the observation that it doesn't seem to go below 1.



I thought that the JOLTS data might make a good candidate for my new favorite go-to model ‒ the [naive dynamic equilibrium](http://informationtransfereconomics.blogspot.com/2016/10/dynamic-unemployment-equilibrium-and.html) that I recently used to make an [unwarranted forecast of future unemployment](http://informationtransfereconomics.blogspot.com/2017/01/an-updated-unemployment-rate-projection.html). However, in this case, I think the framing of [the same data from voxeu.org](http://voxeu.org/article/new-models-macroeconomic-policy) in terms of the logarithm might be the better way to look at the data.



We will assume that the logarithmic derivative of the inverse ratio (i.e. openings over unemployed) is a constant






where $\exp \; (- \log (V/U)) = U/V$ which is the ratio Ben graphs. Using [the same entropy minimization procedure](http://informationtransfereconomics.blogspot.com/2016/06/unemployment-equilibrium.html), fitting to a sum of [logistic functions](https://en.wikipedia.org/wiki/Logistic_function), and finally converting back to the $U/V$ variable Ben and Steve were talking about, we have a pretty decent fit (using two negative shocks):



![](<media/jolts job openings unemployment ratio 1.png>)

The shocks are centered at 2000.6 and 2008.6, consistent with the NBER recessions [just like the unemployment model](http://informationtransfereconomics.blogspot.com/2016/10/defining-recessions.html). There's a bit of overshooting after the recession hits just like in the unemployment case as well. I've also projected the result out to 2020. If there weren't any shocks, we'd expect the ratio to fall below 1 in 2018 while spending approximately three to four years in the neighborhood of 1.3. And I think that explains why we haven't seen a ratio below 1 often: the economy would have to experience several years without a shock. A ratio near 2 requires a shorter time to pass; a ratio near 4 requires an even shorter time. Also in this picture, Ben's "stabilization" is not particularly unexpected.



However, there's a bit more apparent in this data that is not entirely obvious in the $U/V$ representation shown above. For example, Obamacare pushed job openings in health care higher, likely even reducing the unemployment rate by a percentage point or more (as I showed [here](http://informationtransfereconomics.blogspot.com/2016/08/did-aca-decrease-unemployment.html)). This also has a noticeable effect on the JOLTS data; here's the fit with three shocks ‒ two negative and one positive:



![](<media/jolts job openings unemployment ratio 2.png>)

With the positive Obamacare shock (onset of 2014.3 or about mid April 2014 is consistent with the unemployment findings and the negative shocks are in the nearly the same places at 2000.8 and 2008.7). We can see what originally looked like mean reversion in the past year now looks a bit like the beginning of a deviation. As I asked in my unwarranted forecast at the link above, what if we're seeing the early signs of a future recession? The result hints at a coming rise, but is fairly inconclusive:



![](<media/jolts job openings unemployment ratio 3.png>)

I wanted to keep the previous three graphs in order for you to be able to cycle through them on a web browser and see the subtle changes. This graph of the logarithm of $V/U$ that I mentioned at the top of the post allows you to see the Obamacare bump and the potential leading edge of the next recession a bit clearer:



![](<media/jolts job openings unemployment ratio 4.png>)

It's important to note that leading edge may vanish; for example, look at 2002-2005 on the graph above where a leading edge of a recovery and recession both appeared to vanish.



Now is this the proper frame to understand the JOLTS data? I don't know the answer to that. And the frame you put on the data can have [pretty big impacts](http://informationtransfereconomics.blogspot.com/2015/08/explicit-implicit-models.html) on what you think is the correct analysis. The dynamic equilibrium is at least an incredibly simple frame (much like my discussion of consumption smoothing [here](http://informationtransfereconomics.blogspot.com/2017/01/behavior-institutions-and-other.html)) that's pretty easy to generate with a matching model ($U$ and $V$ grow/shrink at a constant relative rate). Even better, an information equilibrium model because the equation at the top of this page essentially says that $V \rightleftarrows U$ with a constant IT index $k$ so that:






therefore if the total number of unemployed grows at a constant rate $r$, i.e. $U\sim e^{rt}$ (say, with population growth)






which is a constant (which is about 0.21, or about 21% of unemployed per year or 1.7% per month, at least since 2000 ‒ [multiple equilibria are possible](http://informationtransfereconomics.blogspot.com/2016/10/multiple-dynamic-employment-growth.html)).

**Update 11 January 2017**

In case you are interested, here is the code (click to expand):

![](<media/jolts job openings unemployment ratio -code-.png>)
