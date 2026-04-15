---
title: "What does the AD-AS model mean?"
date: 2015-04-05T12:18:00.000-07:00
updated: 2015-04-06T16:55:45.336-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/04/what-does-ad-as-model-mean.html
---

[Cameron Murray has a new post up](http://ckmurray.blogspot.com/2015/04/macroeconomics-fallacy-of-composition.html) about logical fallacies and contradictions involved in setting up the AD-AS model in macroeconomics. I personally like the AD-AS model as a toy model of how an economy works. It misses out on a bunch of details, but I think it forms a fine basis from which to depart with more detailed model.



The focus of the Murray's post is the [fallacy of composition](http://en.wikipedia.org/wiki/Fallacy_of_composition), which I've seen used as a rhetorical device in many instances (the sum of government spending effects on local spending doesn't mean there is an aggregate effect, or prudent increased saving by individuals isn't prudent for the overall economic situation in the paradox of thrift). As a physicist, I've always thought of it as a strange rhetorical device. In physics we have large numbers of examples where the fallacy applies, but it is _never_ used. I think the reason it is never used is that in general there is a specific effect at work and we'd refer to that effect instead of the "fallacy of composition" -- quark confinement, entropic forces, emergent dimensions in string theory, pretty much all of materials science.



I think the fallacy of composition would better be called the _warning of composition_ -- an idea that warns you of:

-   Effects that might go away at the macro scale (an example is the SMD theorem, and on this blog most of the details of how economic agents operate)
-   Effects that might not exist at the micro scale, but do at the macro scale ("entropic forces", emergent properties, and on this blog [nominal rigidity](http://informationtransfereconomics.blogspot.com/2015/03/nominal-rigidity-is-entropic-force.html))

The warning of composition can help prevent you from making unwarranted jumps in logic. But sometimes those jumps are warranted (or you have explicit machinery for adding the effects together).



So let's look at the AD-AS model in the information equilibrium framework. It essentially lives entirely on the macro scale, so there isn't any fallacy of composition. We instead have failures of information equilibrium, exceptions and other micro effects.



The basic set up starts with the main information equilbrium condition for the information in the aggregate demand in information equilibrium with aggregate supply I(AD) = I(AS), [so that we have the differential equation](http://informationtransfereconomics.blogspot.com/2013/04/the-information-transfer-model.html):



$$<br />
P = \frac{dAD}{dAS} = k \; \frac{AD}{AS}<br />
$$



Note that this is just the minimal (interesting) differential equation consistent with long run neutrality (homogeneity of degree zero in supply and demand functions). There are three solutions we look at here:



1.  Both AD and AS vary (general equilibrium; for example in a growth model)
2.  AD is held constant (partial equilibrium; the system is in contact with a "demand bath" -- a demand curve)
3.  AS is held constant (partial equilibrium; the system is in contact with a "supply bath" -- a supply curve)

The solution to the first case is given by (you can ignore the angle brackets -- they represent expectation values in an ensemble of agents \[1\])


$$<br />
\langle AD \rangle = a_{0} \left( \frac{\langle AS \rangle}{s_{0}}\right)^{k}<br />
$$
$$<br />
P = a_{0} k \left( \frac{\langle AS \rangle}{s_{0}}\right)^{k - 1}<br />
$$




The other two solutions are family of supply and demand curves (where we define $\Delta AS = AS - s_{0}$ and $\Delta AD = AD - a_{0}$ parameterized by $\beta$ and $\alpha$ respectively so that



$$<br />
P = \frac{a_{0}}{k \beta} \exp \left( + \frac{\Delta AS}{\beta k} \right)<br />
$$
$$<br />
P = \frac{\alpha}{k s_{0}} \exp \left( - k \frac{\Delta AD}{\alpha} \right)<br />
$$


Shifts in the supply and demand curves are shifts in $\beta$ and $\alpha$. Here are the resulting supply and demand diagrams (there are more details about this derivation [here](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html), the expectation values $\langle AD \rangle$ and $\langle AS \rangle$ parameterize the location along the supply and demand curves, respectively and drop out in the price functions above):





![](<media/-AD AS- 1.png>)![](<media/-AD AS- 2.png>)

So now let's try and address some of Cameron Murray's problems with AD-AS ... 





Let's start with his point 1:

> _The fallacy at play here is that there is an aggregate price level. As we saw in Chapter 8 on Inflation, price levels are not absolute but relative to some base year. In the economy as a whole there is no external price from which to determine a price level. Hence the idea of an economy-wide price level is in a given time period is a fallacy. > > Often the AD-AS model is interpreted as showing Real GDP related to the rate of inflation in a period (not the level, but the rate of change of price levels relative to a base year). This overcomes the fallacy of composition because it compares the price level with last year’s price level, but contradicts earlier discussions about anticipated vs unanticipated inflation. If inflation is anticipated at any reasonable level then there should be no economic effect, and hence no relationship (no curve, or a vertical line at best)._ >

A really good way to clearly see some of the properties of the information equilibrium version of the AD-AS model is to take $k = 1$. This is just a parameter, so we can set it to whatever we'd like and what is left should still express the fundamental properties of the model (as opposed to parameter dependent ones). In that case we have (I'll drop the angle brackets for now \[1\]):





$$<br />
\text{(1a) }\; AD = a_{0} \frac{ AS}{s_{0}}<br />
$$
$$<br />
\text{(1b) }\;&nbsp;P = a_{0}<br />
$$


Note that $P$ is a constant. The AD-AS model has nothing to do with trend inflation or the absolute price level. The absolute (level) version of the model is trivial \[2\]. If $k &gt; 1$ then all that adds is a trend growth and trend inflation. 



All of the real action is in the partial equilibrium (supply and demand curves) which do not materially change when $k = 1$



$$<br />
\text{(2a) }\;&nbsp;P = \frac{a_{0}}{\beta} \exp \left( + \frac{\Delta AS}{\beta} \right)<br />
$$
$$<br />
\text{(2b) }\;&nbsp;P = \frac{\alpha}{s_{0}} \exp \left( - \frac{\Delta AD}{\alpha} \right)<br />
$$

This prepares us for Murray's point 2:

> > > As income rises consumption will rise, and as income falls, consumption will fall (p269) ... _In aggregate the total consumption (or demand) in the economy is equal to the total incomes in the economy be definition, since someone’s consumption is somebody else’s income. This sentence, allowing from proper aggregation that avoids the fallacy of composition, merely says that aggregate incomes and consumption just rise and fall together since they are equal at any point in time by definition._ > >



There is a difference between a rise in a price in general equilibrium Eqs. (1a, b) and a rise in the price in partial equilibrium Eqs. (2a, b). The former case (which is the one referred to in the quote from p269) is essentially a change in $a_{0}$ in equation (1b) or trend inflation if $k &gt; 1$. 





Murray's subsequent comments involve combining the AD-AS model with some model of interest rates, beyond the scope of this one post ([here's an example in the IS-LM model](http://informationtransfereconomics.blogspot.com/2015/02/information-equilibrium-paper-draft_23.html)). He does at the top of his post say:

> _\[No economics professors\] could explain what the concept of the price level in the aggregate even is, nor what mechanism was meant to be at play in generating the relationship between price level and output._



Within the information equilibrium version of the AD-AS model we have an answer. But it completely ignores the "warning" of composition. The AD-AS model at its heart is a simple aggregation of millions of supply and demand diagrams for each product in a large economy. The price level in aggregate is simply the sum of all prices and the mechanism for the relationship between $P$, $AD$ and $AS$ is just supply and demand operating on the grand scale. If there is more demand for aggregate output than there is aggregate output that exists, prices in general will rise. If there is a fall in demand, prices in general will fall. 



It's a simple model! The mechanism is the same as supply and demand ... _now there may be [some issues](http://informationtransfereconomics.blogspot.com/2015/01/im-not-sure-economists-understand.html) with the reasoning behind that ..._ \[3\]




**Update 4/6/2015**



Cameron Murray was right that the AD-AS model presented above doesn't directly address the fallacy of composition; [I commented back on his blog](http://ckmurray.blogspot.com/2015/04/macroeconomics-fallacy-of-composition.html?showComment=1428350752305#c3090071948744220588) and I've attached the comment below for reference here ...



> I guess I wrote up the AD-AS model post a bit too quickly and really only addressed the fallacy of composition with a single sentence: 

> "\[the model\] essentially lives entirely on the macro scale, so there isn't any fallacy of composition." 

> That is to say the model makes no specific assumptions about the details of household or firm behavior. You could interpret that in a couple of ways, though 

> 1\. Micro behavior is approximately random
> 2\. Micro behavior is so complex it appears random
> 3\. Any detailed micro behavior is subject to the fallacy of composition -- after being filtered through the aggregation process, all that's left looks random 

> 'Random' here is being used in the thermodynamics sense -- I'm not saying households are irrational, increasing or decreasing their holdings of liquid assets at random month to month. Each atom in a gas obeys very strict physical laws like momentum and energy conservation. Likewise each economic agent could have some kind of deterministic micro behavior. Just like we don't know the history of collisions for an atom in a gas, we don't know the history of financial transactions of one household. Any given household will be increasing or decreasing its holdings of liquid assets at any given time because of that history. Most of the time these are in "detailed balance": households increasing equals households decreasing. 

> If e.g. inflation falls, there could be a tendency on average for those holdings to increase (based on millions of household decisions consistent with millions of financial histories) due to a small imbalance, aggregated up to the macro level. However, any individual household wouldn't point to the falling inflation. And it's not even true that inflation is influencing household behavior -- falling inflation is simply the most likely macro state where liquid asset holdings are increasing (in the AD-AS model). Since there are millions of households, the law of large numbers kicks in. 

> In that way, the AD-AS model I present at the link is a macro-only model. Higher inflation doesn't cause individual households to increase their demand for iPads. The higher inflation macro state is consistent (in the AD-AS model) with a macro state in which more iPads are being consumed.

**Update II 4/6/2105** 


I should also add that the general equilibrium solution -- #1 in the list at the top and equations (1a,b) -- essentially defines the "long run aggregate supply" (LRAS) curve while equation (2a) defines the "short run aggregate supply" (SRAS) curve, so the full diagram is:



![](<media/AD AS model -diagram-.png>)


**Footnotes**


\[1\] The angle brackets are a bit like how in thermodynamics one takes volume to be $V = \langle V \rangle$. Volume doesn't exist for an individual atom, but only makes sense as a property of an ensemble of atoms. The same goes for demand in the information equilibrium model -- it is not a property of an individual agent, but an ensemble of agents.



\[2\] If we say AS is made of components, like capital and labor, then it gets a bit more interesting and you arrive at [the Cobb-Douglas production function in the Solow growth model](http://informationtransfereconomics.blogspot.com/2014/12/the-information-transfer-solow-growth.html).





\[3\] Supply and demand seem to be entropic forces (and supply and demand diagrams are [entropic force diagrams](http://informationtransfereconomics.blogspot.com/2015/02/why-focus-on-supply-and-demand.html)) that may defy a microscopic description. For example, [here's one way to get something that looks like utility](http://informationtransfereconomics.blogspot.com/2015/03/utility-in-information-equilibrium-model.html) but really is just random behavior.
