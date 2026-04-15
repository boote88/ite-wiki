---
title: NAIRU and other connections between inflation and employment
date: 2017-02-27T14:00:00.000-08:00
updated: 2017-02-28T12:38:52.487-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/02/nairu-and-other-connections-between.html
---

The topic of the hour is NAIRU (Non-Accelerating \[1\] Inflation Rate of Unemployment). Simon Wren-Lewis [put forward the mainstream defense](https://mainlymacro.blogspot.com/2017/02/nairu-bashing.html) of the concept before I left on vacation. In general, the idea is plausible from a rational agent viewpoint: if labor is plentiful, then there is little pressure on wages. At some level of labor scarcity, the bargaining positions of prospective employees will be better leading (so the theory goes) to expectations of higher wages for the same level of productivity. With those higher wages chasing scarce output, prices could be expected to increase. Of course other "stories" are possible, but the basic idea is that unemployment below a certain level leads to higher inflation expecations, leading to higher inflation.



I think Simon accidentally gives us the real rationale:

> _But few of these attempts to trash the NAIRU answer a very simple and obvious question - how else do we link the real economy to inflation?_

That is to say, it seems to me to be a post hoc narrative developed out of the original desire to link the real economy and inflation (i.e. monetary policy). The problem is that we have two completely unobservable variables interacting: NAIRU and inflation expectations. This should raise eyebrows to say the least.



But as I said: NAIRU appears to be an attempt to understand theory, not data. What does the data look like?



To that end, I thought I'd introduce a new "model": the dynamic equilibrium picture of the price level. I've previously shown how prices in information equilibrium models [should also manifest dynamic equilibria](http://informationtransfereconomics.blogspot.com/2017/01/housing-prices-and-dynamic-equilibrium.html) subjected to shocks (just like ratios of variables in information equilibrium with each other such as [the unemployment rate](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html)). Applying the same procedure as in the previous link, we obtain a pretty good first order description of the core PCE price level and inflation:


![](<media/dynamic equilibrium -inflation- 1.png>)
![](<media/dynamic equilibrium -inflation- 2.png>)

There's a single transition centered around 1978.7; all of the other shocks are dwarfed by this one. However, this one major shock doesn't really match up with any [shocks to unemployment](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-unemployment-rate.html):



![](<media/unemployment ratio -log version- 1960s.png>)

What this broad shock does line up with is the [non-equilibrium process of women entering the workforce](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-employment.html):



![](<media/unemployment ratio -log version- EPOP ratio women.png>)

This view of the data is exactly the same demographic story of 1970s inflation as the "[quantity theory of labor](http://informationtransfereconomics.blogspot.com/2016/01/its-people-economy-is-made-out-of-people.html)" (as well as [Steve Randy Waldman's account](http://www.interfluidity.com/v2/4706.html) in terms of baby boomers and women together) \[2\].



Let's return to our discussion of NAIRU above. The data more plausibly connects the employment-population ratio and inflation than unemployment. In fact, it does not appear (from the data, at least) that the unemployment rate dynamic equilibrium technically has to stop its downward path -- it could proceed towards zero independent of the inflation rate:



![](<media/no nairu.png>)

This is of course very unlikely because a recession would almost certainly intervene (happening randomly with a time constant of about 8 years). This is a silly counterfactual, but the main point is that unemployment and inflation do not appear to be connected. Based on the dynamic equilibrium view of the existing data, unemployment could head to zero and inflation would remain constant.


\[I would like to add that at some low unemployment rate we might run into a "noise floor" of people changing jobs for non-macroeconomic reasons, as I mention [in the presentation](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html) where this graph originally appears (28 Feb 2017)\]


Therefore, while there is a plausible connection between employment and inflation (changes in the employment-population ratio), it's not the story told by NAIRU (inflation and unemployment).



PS See also [this Twitter thread](https://twitter.com/infotranecon/status/832996617707888642).




**Update 27 Feb 2017**


If you squint, you might be able to convince yourself of some residual (anti-)correlation between the unemployment rate and the difference between the dynamic equilibrium model and the data:



![](<media/dynamic equilibrium -inflation- 3.png>)

However, it is not statistically significant. Even if it did exist, the primary component of 70s inflation would still have nothing to do with the unemployment rate.


**Update 27 Feb 2017, the second**

Added the code to the [GitHub dynamic equilibrium repository](http://informationtransfereconomics.blogspot.com/2017/02/information-equilibrium-code.html).




**Footnotes**


\[1\] Some Wynne Godley fans seem to think this term is some kind of misnomer, saying "prices" are accelerating. I don't understand it. First off, Godley has explicitly used the inflation acceleration terminology to mean inflation is increasing or decreasing. This is also perfectly in alignment with the terminology in physics: price is a position, inflation is a velocity. We say "velocity accelerates" (for a rate of change of velocity), not "position accelerates".



\[2\] Now even though women entering the workforce appears to be the best candidate for an explanation of 1970s inflation, that doesn't necessarily nail down the mechanism behind it. Women entering the workforce could have produced a big aggregate demand shock (sort of an AD-AS model explanation). In thinking about the mechanism, I also came up with a sexism theory of inflation: women entering the workforce made men demand to be paid more than women, driving up wages and prices. That is to say the connection between inflation and the employment-population ratio could be entirely sociological (i.e. different in different societies), not economic (i.e. the same for any demographic transition).
