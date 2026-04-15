---
title: Accounting identities and conservation laws
date: 2019-05-14T15:00:00.000-07:00
updated: 2019-05-14T17:31:44.227-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2019/05/accounting-identities-and-conservation.html
---

[David Glasner brought me into a twitter thread](https://twitter.com/david_glasner/status/1128268277703237633) that resulted in a disagreement between Noah Smith and myself which is unfortunate because I think we're saying the same thing regarding "accounting identities" in economics being arbitrary definitions. Noah just seems to think that conservation laws aren't also (direct consequences of) definitions. First, let me get all relativistic (in [both](https://en.wikipedia.org/wiki/Theory_of_relativity) [senses](https://en.wikipedia.org/wiki/Relativism)).



Newton's laws are basically a series of definitions that say "I am defining a quantity called momentum (1st and 2nd laws) that is conserved by definition (3rd law)" \[1\].  This turned out to be one of the most useful definitions in science — though it was counterintuitive at the time. Imagine people reading the 1st law about objects tending to stay in motion when everything in their life usually ground to a halt due to friction.



This definition of momentum led to being able to predict the orbits of comets and the paths of projectiles pretty well. [Emmy Noether eventually discovered the reason](https://en.wikipedia.org/wiki/Noether%27s_theorem): it's because the universe has an approximate translational symmetry such that laws of physics at a point _x_ is the same as the laws of physics at a point _x_ \+ _dx_. It gets a few things wrong, like the orbit of Mercury — that's because the actual symmetries are [Lorentz invariance](https://en.wikipedia.org/wiki/Lorentz_covariance) and [general covariance](https://en.wikipedia.org/wiki/General_covariance). But by "actual" here, we mean that they dynamics that result from the definition of momentum that arises from assuming Lorentz invariance ([4-momentum](https://en.wikipedia.org/wiki/Four-momentum)) gives the results we measure. We also often arbitrarily separate the momentum conserved due to rotational symmetries (angular momentum) from the momentum conserved due to translational ones.



But the universe doesn't care about momentum or its conservation — we humans defined it based on a way we decided to decompose the universe that we found useful. And in the end, it comes down to the definition of what a derivative is. That _x_ + _dx_ is directly related to the momentum operator _d/dx_ and the better definitions of momentum that are conserved have [covariant derivative](https://en.wikipedia.org/wiki/Covariant_derivative) momentum operators. So, it's really our human definition of calculus.



As we found issues with the definition of momentum, we've expanded it and made it more nuanced — because the purpose of the definition of momentum is to get empirically accurate theories, not hold on to Newton's definition.



Now not being an economist I may get this wrong but Simon Kuznets' original definition of GNP/GDP as the market value of final goods and services produced in a quarter (or year, or other time period) was so defined because people thought it would be useful as a measure of production related to the current level of employment. If a Starbucks barista made you a coffee this morning, it'll be in this quarter's GDP. If I sell you [my vintage 1980s Dougram collection](http://www.collectiondx.com/toy_review/1981/mackerel_h404s_soltic), it doesn't employ anyone in the current period so it's not in GDP.



Just like how momentum was defined in order to try and produce a useful theory of motion ("physics"), GDP was defined in order to try and produce a useful theory of employment ("macro"). It's just a definition:

> GDP = (your cup of Starbucks Coffee) + (my cup of Starbucks Coffee) + ... (other Non-Coffee final goods and services produced in 2019 Q2)

We can also arbitrarily group (partition) them:

> _GDP = C + NC_

That arbitrary grouping is probably not useful. But this one has stuck around for a long time:

> _GDP = C + I + G + NX_

We call this arbitrary grouping a national income accounting identity. Now just because it has stuck around doesn't make it right, but it does capture one useful aspect of modern economies — _G_ tends to move all at once with changes in government fiscal policy and can move in the same or opposite direction relative to e.g. _C_. Empirical data appears to show that changing _G_ can be used to offset the collapse in _C_ during a recession, for example. [In a long-ago blog post](https://informationtransfereconomics.blogspot.com/2015/04/do-macro-models-need-financial-sector.html), I discussed how it might be useful to think of an additional financial sector (which redefines C, I, and NX a bit) so that:

> _GDP = C + I + F + G + NX_

That's another arbitrary grouping that's purely a definition. But like our evolving definition of momentum that's been found wanting on occasion, we can evolve our definition of the national income accounting identity to pick out a financial as well as a government sector. Why? Because the financial sector is also large and may move in the same direction all at once like in 2008. If we think of the distribution of growth rates of various companies and government entities in terms of their contribution to GDP, the whole collection will have some average growth rate based on the average of that distribution:


![](media/distribution0.png)

GDP growth will be the ensemble average. Like partitioning down to the individual coffee level, this may or may not be useful. However, if we group the financial sector into one big box (gray) and the government sector into another (blue), we instead have maybe something like this:



![](media/distribution1.png)


![](media/distribution2.png)

and the new ensemble average growth rate results in a GDP that declined in that quarter. Shifting the government sector up could potentially offset that a bit. Again, maybe this arbitrary grouping is useful and maybe it isn't — a lot depends on the interactions of the various pieces (I talk about that a bit more [here](https://informationtransfereconomics.blogspot.com/2016/03/does-saving-make-sense.html)).



The main point is that definition of GDP and the accounting identity partition of it are both completely arbitrary, but like the arbitrary definition of momentum (which is based on our calculus-based approach to physics) they might be **_useful_**.



It's true per Noah's original tweet in the thread that we don't want to put too much weight on what is essentially an arbitrary definition that might not be useful. And you definitely want to be careful about reasoning from the identity _alone_ — also because calculus:


![](<media/accounting id.png>)

This graphic lays out the possibilities for the interaction of those sectors (including the little boxes) in the distribution pictures above (but this graphic is for levels, while the distribution is for growth rates). The picture I showed in the distributions is the upper right where the change in the financial box doesn't do anything to the other boxes.



Macroeconomics is a nascent science compared to physics — Newton's definition of momentum is from 1687 while Kuznets' definition of GDP is from 1934. So yes, by all means recognize that the definition of GDP and its various accounting identities are arbitrary definitions. GDP seems to be a useful macro definition for studying employment and fiscal policy does seem to have an effect on the economy warranting a separate _G_ term. Maybe there are better — [more useful](https://informationtransfereconomics.blogspot.com/2018/02/women-in-workforce-and-solow-paradox.html) — definitions. But don't go too far in the other direction and think that the enormously successful definition of momentum as a conserved quantity makes it not arbitrary. It's still just a label we humans applied to the universe.




**Footnotes:**



\[1\] Actually Newton's Lex II was a bit vague:

> _Lex II: Mutationem motus proportionalem esse vi motrici impressae, et fieri secundum lineam rectam qua vis illa imprimitur._

A somewhat direct translation is:

> _Second Law: The alteration of motion is ever proportional to the motive force impressed; and is made in the direction of the right line in which that force is impressed._

The modern understanding is:

> _Second Law: The change of momentum of a body is proportional to the impulse impressed on the body, and happens along the straight line on which that impulse is impressed._

Where momentum and impulse now have very specific definitions as opposed to "motive force" and "motion". This is best interpreted mathematically as



_**I** ≡ Δ**p**_



where _**I**_ is impulse and _**p**_ is the momentum vector. The instantaneous force is (via the fundamental theorem of calculus, therefore no assumptions of relationships in the world)



_**I** = ∫ dt **F**_



_**F** ≡ d**p**/dt_



where p is the momentum vector. The alteration of "motion" (i.e. momentum) is Δp (or infinitesimal dp), and the rest of the definition says that the **_F_** vector (and impulse vector **_I_**) is parallel to the **_p_** vector. Newton would have written in his own notes something like _f = ẋ_ using his fluxions (i.e. _f = dx/dt_).
