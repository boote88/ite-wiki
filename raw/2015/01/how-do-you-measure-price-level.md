---
title: "How do you measure the price level?"
date: 2015-01-26T18:30:00.000-08:00
updated: 2015-01-27T10:54:31.878-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/01/how-do-you-measure-price-level.html
---

> econ: PCE or CPI? Core or headline?
>
> info: \[Sigh\] ...
>
> econ: What?
>
> info: They're barely different from each other!
>
> econ: Isn't there a joke about a physicist and a spherical chicken?

That's from me a [few days ago](http://informationtransfereconomics.blogspot.com/2015/01/a-socratic-dialog-on-information.html). I've been on an [anti-utility kick lately](http://informationtransfereconomics.blogspot.com/2015/01/im-not-sure-economists-understand.html) and the process, I've been looking at a bunch of stuff on preferences, total orderings and ... [differential geometry](http://arxiv.org/abs/0902.4274). Smolin's paper mentioned Malaney and Weinstein's gauge theory approach to price indices. I plan doing a bit more thinking about what Smolin says -- he thinks a non-equilibrium statistical mechanics approach to economics may be useful (like the one I am advocating on this blog), saying: _Nonetheless, once one gets past this confusion \[about thermodynamic equilibrium\], there is still a cogent claim that non-equilibrium statistical mechanics may be a basis for a model of an economy._ But for now, I'm going to concentrate on the gauge theory approach to the so-called index number problem.



I seriously dislike the name, because it makes me think of some kind of deep problem in number theory or the [Atiyah-Singer index theorem](http://en.wikipedia.org/wiki/Atiyah%E2%80%93Singer_index_theorem). Oh, well. I don't have much of a choice there. Let's start with [Wikipedia](http://en.wikipedia.org/wiki/Index_%28economics%29#Index_number_problem):

> _The "index number problem" refers to the difficulty of constructing a valid index when both price and quantity change over time. For instance, in the construction of price indices for inflation, the nature of goods in the economy changes over time as well as their prices._

Wikipedia continues: _"There is no theoretically ideal solution to this problem."_



In fact there may be, based on Malaney and Weinstein's differential geometry approach. In her thesis, she motivates an 'economic derivative' that is a covariant derivative. You may remember that this gauge theory approach was part of [Chris House's rant](https://orderstatistic.wordpress.com/2014/03/21/why-are-physicists-drawn-to-economics/) about physicists in economics. I [opined on this blog](http://informationtransfereconomics.blogspot.com/2014/04/economics-is-neither-physics-nor.html), and asked the question that should be asked of any mathematical approach to a problem: _what is it good for?_



Well, Malaney's approach allows you a way to solve the index number problem ... assuming you buy into the other assumptions. The idea is that a salary $S(t)$ that is always proportional to the 'correct' price index $P(t)$ (with constant of proportionality $\alpha$) should have the same purchasing power, which allows the construction of a covariant derivative










This choice what you mean by 'constant' (i.e. derivative equal to zero) solves the index problem, because it essentially makes all of the price indices equivalent to a so-called Divisia index. Don't let the Divisa terminology worry you. Essentially, various chained indices or indices with changing baskets of goods are [approximations to a Divisia price index](http://en.wikipedia.org/wiki/Divisia_index#Uses).



The problem economic theorists would have with this is that a Divisia price index is path dependent brought about by changing preferences. Basically, what makes the Divisia price index problematic is the issue of mapping it to utility in the sense that John Kay discusses [here](http://www.ft.com/intl/cms/s/0/2d1bb8ca-6412-11e4-bac8-00144feabdc0.html?siteedition=intl#axzz3PrHomSNA).



Would you rather be the richest person in history or live in a time of antibiotics? Divisia answers with the former if you equate the 'inflation adjusted' value of goods with utility as defined in ethical philosophy. The path dependence is obvious here -- because Rothschild would likely value antibiotics today. Malaney argues that this path dependence may be a desireable property in her thesis, but overall, the question of how money equates to utility will probably always be a philosophical one.



As an aside, Noah Smith talks about [unstable preferences here](http://noahpinionblog.blogspot.com/2014/01/what-if-preferences-are-unstable.html). However, the mapping of money and price indices to information lacks these philosophical issues. I've [talked about this before](http://informationtransfereconomics.blogspot.com/2014/12/inflation-is-information-theory-not.html) -- inflation is better understood as an information theoretical construct rather than a utilitarian philosophical one.



The new bit here is that I want to show that the Divisia price index is the proper measure in the information transfer model, just like in the differential geometry approach of Malaney and Weinstein. The underlying assumption is different, though. In our case, a price index isn't measuring 'constancy' (in Malaney's thesis), but rather 'meaningful aggregation'.



The question we ask is whether there exists a consistent price level $P$ that allows us to treat the economy as aggregate supply $Q$ and aggregate demand $N$ when $P$ is made up of individual prices $p_{i}$ (and likewise $q_{i}$ and $n_{i}$).



If we start with (taking $\kappa = 1$ WOLOG)






Then taking the logarithmic time derivative (this gives a percentage rate when multiplied by 100), we get








However, if we take the individual markets (I'll use vector notation to simplify the equation a bit)












The Divisa price index $P$ is defined by separately equating the two terms of (1) and (2) and solving the differential equations:








In the information transfer model, that means $P$ allows you convert between _informationally equivalent_ baskets of goods. That is to say that a basket from 2014 that includes an iPad and one from 1980 that does not can potentially be equivalent in information.



However, an intervening redefinition of money or a monetary regime change will break the direct equivalence between $P$ for different times. That is to say Rothschild's and Kay's utility cannot be compared because they lived in different monetary regimes (a gold standard and fiat currency regime), even if both used 'pounds sterling'.



Interestingly, non-ideal information transfer where $N \geq Q P$ does not affect this derivation -- we are equating the RHS of equations when we equate (1) and (2); both are on the same side of that inequality.



Anyway, more on the Smolin article to come.

**Update:**

I kind of glossed over the role of the changing information transfer (IT) index (κ) in the more accurate model of the price level in terms of the money supply. In this post, we used an aggregate supply (Q) rather than the money supply (M), so I don't think there should be a time changing IT index in that case. In a sense, PQ = N represents both the expenditure method and income method of calculating NGDP which should be equal (and should have κ = 1).
