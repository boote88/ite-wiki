---
title: "Information theory and economics, a primer"
date: 2015-04-11T15:03:00.002-07:00
updated: 2015-07-13T14:18:24.838-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/04/information-theory-and-economics-primer.html
---

This lowly blog was honored with [a link from Mark Thoma](http://economistsview.typepad.com/economistsview/2015/04/links-for-04-10-15.html) and a flood of new pageviews, so I thought I'd try my hand at a new summary of the basic ideas I'm presenting here.



The main idea is essentially to address the question of how much of economics can you describe by assuming as little as possible. The idea was sparked by one of the original drafts of [this paper by Peter Fielitz and Guenter Borchardt](http://arxiv.org/abs/0905.0610) where they stripped information theory to its bare essentials -- even abandoning the idea of bits for a concept they referred to as the natural information content. The result was a generic theory of information equilibrium between a pair of changing quantities that are made up of a very large number of constituent parts (importantly, what those parts are or how they behave is assumed to be unknown). 



Fielitz and Borchardt apply this framework to some problems in physics, including percolation and ideal gasses. I borrowed this information equilibrium framework and applied it to various problems in economics, coming up with some of the exact same models -- and some slightly different models -- as economists and comparing them to measured data with remarkable success for such a simple model.



One major divergence from mainstream economic approaches is the lack of assumptions about what it is that is mediating economic activity. You really don't need any economic agents, firms, households, rational expectations, or really any kind of human thought at all ... when markets are functioning properly. Market forces are like entropic forces in thermodynamics -- diffusion and osmosis are a couple of well known ones. Molecules in a gas don't know about their density at the other side of the room, but collectively they will distribute themselves to achieve an almost equal density across their container. People and prices can be described by the same information equilibrium framework that describes the behavior of molecules. The equilibrium states in this model are the ones with maximum entropy \[1\]. 



I think this actually solves a really tough philosophical problem. If humans have free will and don't behave perfectly rationally all the time, why does it seem that when markets are functioning properly, the mathematics of economics work so well  -- as if they were atoms in an ideal gas?



The physicist Eugene Wigner once referred to the "[unreasonable effectiveness of mathematics in the natural sciences](https://www.dartmouth.edu/~matc/MathDrama/reading/Wigner.html)". One comment I frequently see out there on the economics blogs is the economics equivalent: economists' equations and models don't have anything that looks like a real human in them. Some [economists actually defend this](http://newmonetarism.blogspot.com/2015/03/lucas-and-his-critics.html) -- they say they don't need realistic humans or assumptions (microfoundations).



What this information equilibrium framework seems to say is that when markets are functioning properly, this is ok. To turn Tolstoy upside down, _all functioning markets are alike; each market failure fails in its own way_. Those functioning markets represent a common Platonic ideal -- something that can be described by mathematics. Interestingly, the information equilibrium framework also has some suggestions for how to approach the problem when markets fail, too! It's called non-ideal information transfer and it allows us not only to see markets that are functioning (those well-described by ideal information equilibrium), but point out ones that are failing. This also represents a divergence from mainstream -- markets aren't assumed to be functioning unless they can be shown to be functioning.



The basics of the framework come down to a couple of equations and what is effectively a supply and demand diagram -- which should be thought of as an entropic force diagram. We start with two economic aggregates we'll call A and B. If information is flowing from A to B (and there is no other source), then all we can say is that the information received by B is less than the information transmitted from A, or \[2\]:



![](media/nonideal.png)

We can use this (as Fielitz and Borchardt did) to generate a differential equation for a tiny fluctuation of _A_ (we call _dA_) is received by _B_ and causes a tiny fluctuation (we call _dB_):



![](<media/CodeCogsEqn -3-.png>)

This equation tells us how two economic aggregates _A_ and _B_ move with respect to each other. We define the derivative _dA/dB_ to be an abstract price _P_. That is the general case -- it allows both ideal (equality aka information equilibrium) and non-ideal information transfer (the less than sign). If we look at ideal information equilibrium, we have:



![](<media/CodeCogsEqn -2-.png>)
![](<media/CodeCogsEqn -4-.png>)

I frequently use the notation _P:A→B_ to describe this system (the arrow helps you remember that A is the information source in the case of non-ideal information transfer). Some may note that this is a minor generalization of the equation [appearing in Irving Fisher's thesis](http://informationtransfereconomics.blogspot.com/2014/08/fishers-proto-information-transfer.html) and is also the simplest (interesting) model consistent with homogeneity of degree zero (to achieve e.g. [long run neutrality](http://en.wikipedia.org/wiki/Neutrality_of_money)).



There are two major cases of this last equation; in economics parlance, they are **partial equilibrium** and **general equilibrium**. Under partial equilibrium you effectively reconstruct a "supply and demand diagram" (or "B and A diagram"), which was [the genesis of this blog](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html). You have 1) A adjusting to changes faster than B or 2) B adjusting to changes faster than A. Confusingly, these represent a "B curve" and an "A curve", respectively. The key point is that if you have A and B in information equilibrium, you have an interaction that looks like a supply and demand diagram from economics -- additionally it can be used in a generalized way to e.g. derive the IS-LM model or the [AD-AS model](http://informationtransfereconomics.blogspot.com/2015/04/what-does-ad-as-model-mean.html) (the short run aggregate supply curve piece). Here is a generic diagram:



![](<media/ab system.png>)

Under general equilibrium, you have A and B adjusting together. This results in a relationship where _A ~ Bᵏ_, and has been used here to describe long run aggregate supply in the AD-AS model, the quantity theory of money, interest rates (the interest rate is posited to be in information equilibrium with the price of money) and the Solow growth model. The general equilibrium solution also can be used to come up with all kinds of things in economics that are described by Cobb-Douglas functions. I am in the process of writing all this up to be submitted to a journal, and the draft of the [section on macroeconomics](http://informationtransfereconomics.blogspot.com/2015/02/information-equilibrium-paper-draft_23.html) includes these models.



Let's return to the major divergence from mainstream economics. While the behavior of supply and demand curves (letting _A = demand_ and _B = supply_) is recovered by this model, it is agnostic about the details (the "microfoundations") of supply and demand. All that we assumed is that there are a lot of supply and a lot of demand.



So while mainstream economics would describe the increase in demand as the price falls (think of "Black Friday" shoppers rushing the stores for sale items) as a result of an incentive to consume ... that higher demand results from maximizing utility ... the information equilibrium view [looks at it differently](http://informationtransfereconomics.blogspot.com/2015/04/incentives-are-entropic-force.html).



The information equilibrium view doesn't preclude utility maximization or incentives, it just renders those explanations unnecessary. There are simply more possible states with higher demand at lower prices than there are at higher prices. People aren't necessarily incentivized to consume more because of subsidies or low prices -- on average people end up in the state where they have consumed more through some unknown and possibly very complicated process.



Here's a list of some posts that give a feel for what I'm doing ...

1.  [Some cool animations of supply and demand using the formalism above](http://informationtransfereconomics.blogspot.com/2015/03/supply-and-demand-as-entropy.html).
2.  [The conditions under which maximum utility and maximum entropy give the same results](http://informationtransfereconomics.blogspot.com/2015/03/utility-in-information-equilibrium-model.html).
3.  [How utility, Joseph Stiglitz and Claude Shannon fit together](http://informationtransfereconomics.blogspot.com/2015/03/the-price-system-as-communication.html).
4.  The information equilibrium model has what looks like a liquidity trap at low inflation, but looks like the quantity theory of money at high inflation. [This post shows](http://informationtransfereconomics.blogspot.com/2014/06/krugman-keynes-and-liquidity-trap.html) how those two different views are part of a continuum.
5.  Interest rates have several different forces acting at once: Fisher effect, liquidity effect, income effect. [This is how they fit together](http://informationtransfereconomics.blogspot.com/2014/03/the-effects-that-move-interest-rates.html).
6.  [The Great Stagnation and its demand-side counterpart Secular Stagnation](http://informationtransfereconomics.blogspot.com/2014/09/the-great-stagnation-information.html) are really just properties of large economies with fiat currencies that have been relatively stable for awhile.



Here's some empirical data and projections for the US and Japan (and comparing performance with the NY Fed's DSGE model)

1.  [http://informationtransfereconomics.blogspot.com/2015/03/most-recent-updates-to-core-cpi-and.html](http://informationtransfereconomics.blogspot.com/2015/03/most-recent-updates-to-core-cpi-and.html)
2.  [http://informationtransfereconomics.blogspot.com/2015/03/japan-inflation-update.html](http://informationtransfereconomics.blogspot.com/2015/03/japan-inflation-update.html)
3.  [http://informationtransfereconomics.blogspot.com/2015/02/the-fed-seems-over-optimistic-on.html](http://informationtransfereconomics.blogspot.com/2015/02/the-fed-seems-over-optimistic-on.html)





**Footnotes:**


\[1\] You can think of this as how the model sees the efficient markets hypothesis (EMH). Prices are "maximally uninformative" about the state of firms, households, goods and money that lead to the observed price. This doesn't mean completely uninformative (as [Robert Shiller](http://en.wikipedia.org/wiki/Robert_J._Shiller) has famously shown), but in general a price movement contains the least amount of information about the change in the underlying microeconomic state as it can.



\[2\] I am trying pictures instead of mathjax in this post to aid with display on RSS feeds.
