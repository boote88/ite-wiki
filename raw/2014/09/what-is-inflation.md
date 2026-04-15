---
title: "What is inflation?"
date: 2014-09-13T16:08:00.002-07:00
updated: 2014-09-13T16:08:59.364-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/09/what-is-inflation.html
---

Everybody's talking about inflation.



Stephen Williamson [asks](http://newmonetarism.blogspot.com/2014/09/theories-of-inflation-and-european.html): "How do macroeconomists think about inflation?" and answers with a very long (and very interesting -- I plan on doing a post dedicated to it later) history of thought, ending with an analysis of the situation in the EU. According to Williamson, it's not obviously wage-price spirals (e.g. the Phillips curve) and its not directly linked to the money supply -- empirically, these seem to lack stable relationships.



Simon Wren-Lewis [says](http://mainlymacro.blogspot.com/2014/09/simplistic-theories-of-inflation.html): "The idea that we can take one variable, or one equation, and distill from that the future price level is a fantasy. What is surprising is that this fantasy has been, and still remains, so attractive for some economists."



Wren-Lewis cites [Frances Coppola](http://www.pieria.co.uk/articles/fiscal_pessimism), who says: "Empirically, it is abundantly clear that there is [no clear relationship](http://www.pieria.co.uk/articles/reserve_abundance_and_inflation_a_response_to_andrew_lilico) between the quantity of monetary base and the price level."



But [Nick Rowe disagrees](http://worthwhile.typepad.com/worthwhile_canadian_initi/2014/09/three-meanings-of-printing-money-causes-inflation.html), he believes that printing more money than you would have otherwise leads to higher inflation that otherwise would have been.



Scott Sumner thinks inflation is irrelevant. He [says](http://www.themoneyillusion.com/?p=27528): "When I say inflation is a meaningless concept I’m suggesting that the concept is not well defined, despite the BLS’s attempts to do so." He [also](http://www.themoneyillusion.com/?p=27497) says: "There is no such thing as a “true rate of inflation,” but there’s also no reason to assume that inflation has not averaged 2% in recent decades. It’s just as reasonable as any other number the BLS might pull out of the air." Sumner references the hedonic adjustments made by the BLS (adjusting for the quality of goods) -- which of course makes it seem very arbitrary. I got into a discussion with Sumner and commenter Dustin about it [awhile back](http://www.themoneyillusion.com/?p=27006).



Overall, there seem to be a lot of ideas of what inflation is or isn't without any rigorous definitions. I was reading Romer's Advanced Economics (also on my flight home last night) where he says economists don't even necessarily know if inflation is good or bad ([Nick Rowe](http://worthwhile.typepad.com/worthwhile_canadian_initi/2014/09/its-the-inflation-fallacy-duh.html) has a concise list of the mechanisms that make it bad: "Economists would instead talk about shoe leather costs, menu costs, relative price distortions, difficulties of indexing taxes, confused accountants, etc").



In short, there seems to be a lot of confusion.



In the information transfer model, however, the price level is pretty well defined:



$$<br />
P = \frac{dNGDP^{*}}{dM0}<br />
$$



The price level is the increase in NGDP given an infinitesimal increase in currency M0. These days you get about twice as much NGDP for the same amount of printed currency as you did in the 1980s (in the US) \[1\]. The inflation rate is just the time rate of change of this (the derivative of the log gives the fractional rate):



$$<br />
i = \frac{d}{dt} \log P = \frac{d}{dt} \log \frac{dNGDP^{*}}{dM0}<br />
$$


Now you may have noticed that I slipped an asterisk on NGDP -- that's because it's not really measured NGDP, but rather the theoretical shock-free NGDP I've [shown here](http://informationtransfereconomics.blogspot.com/2014/03/the-monetary-base-as-sand-pile.html). Here are the two compared (the blue curve is the shock-free NGDP and the red curve shows the empirical data that includes shocks):



![](<media/ite what is inflation dNdM0 -1-.png>)

Now the [price level model](http://informationtransfereconomics.blogspot.com/2014/06/the-information-transfer-model.html) in terms of the information transfer index $\kappa (NGDP, M0)$ [is an approximation](http://informationtransfereconomics.blogspot.com/2014/06/the-macroeconomic-partition-function.html), so the model isn't perfect, but it is pretty good (taking the derivative of the blue line above gives the points and the inflation data is the green line):



![](<media/ite what is inflation dNdM0 -2-.png>)

So inflation is the time rate of change at which the "friction-free" "ideal" $NGDP^{*}$ goes up for a given expansion in currency $M0$. In terms of equations we have \[2\]:



$$<br />
NGDP^{*} \simeq \beta \left( \frac{M0}{M_{0}} \right)^{1/\kappa (NGDP, M0)}<br />
$$

$$<br />
P = \frac{dNGDP^{*}}{dM0} \simeq \alpha \frac{1}{\kappa (NGDP, M0)} \left( \frac{M0}{M_{0}} \right)^{1/\kappa (NGDP, M0) - 1}<br />
$$


Why don't we include the shocks in $NGDP^{*}$? Here's one plausible story. Maybe that derivative is supposed to be a partial derivative -- the price level is the change in NGDP that is due to a rise in the supply of currency only, independent of other factors. If the shocks $\sigma$ are independent of currency M0 (or only weakly dependent, say on $\log M0$), and $NGDP(M0, \sigma) = NGDP^{*}(M0) + \sigma$ then we have:



$$<br />
P = \frac{\partial}{\partial&nbsp;M0} NGDP(M0, \sigma) = \frac{\partial}{\partial&nbsp;M0} NGDP(M0, \sigma = 0)<br />
$$

$$<br />
P \simeq \frac{\partial}{\partial&nbsp;M0} NGDP^{*}(M0) = \frac{dNGDP^{*}}{dM0}<br />
$$


Now how does the BLS measure CPI if it doesn't know about $NGDP^{*}$ -- I'm pretty sure they've never heard of the information transfer model. It is likely helpful that the individual prices the BLS measures won't be experiencing the same shocks at any given time, so on average a price for a typical good will give insight into $NGDP^{*}$. However, since NGDP (without the asterisk) measures all goods produced, it will be affected by the distribution of prices for a given good. BLS also drops the highly fluctuating food and energy from "core" inflation. There is no "core" NGDP. Both of these effects mean that the BLS CPI statistics may in fact be measuring $NGDP^{*}$ when they measure inflation.



PS I wrote this while I have a pretty serious cold, and am feeling a bit loopy; please excuse me if this doesn't make any sense.



Footnotes:


\[1\] Just because the price level is going up, it doesn't mean that the relative expansion of NGDP is getting bigger for a given expansion in M0 -- for that to happen the price level would have to go up at the same rate as NGDP -- ie. RGDP growth is zero.



\[2\] In the function $\kappa (NGDP, M0)$ we have the actual realized NGDP because that is what a dollar buys a fraction of.
