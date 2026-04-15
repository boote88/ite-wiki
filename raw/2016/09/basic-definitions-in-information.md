---
title: Basic definitions in information transfer economics (reference post)
date: 2016-09-23T16:59:00.002-07:00
updated: 2019-01-15T11:36:32.320-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html
---

I thought it might be a good idea to put a bunch of definitions I use frequently into a single reference post. All of this stuff is discussed in [my paper](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html) as well. Let's start with two macroeconomic observables $A$ and $B$.


Information

This is information entropy in the Shannon sense, not "meaningful knowledge" like knowing the fundamental theorem of calculus or how to play bridge. See [here](http://informationtransfereconomics.blogspot.com/2015/12/information-theory-101-information.html) for an introduction to information theory specific to this blog.


Information equilibrium


The notation $p : A \rightleftarrows B$ represents an information equilibrium (IE) relationship between $A$ and $B$ with price $p$. I also refer to this as a market (it should be thought of as the $A$ and $B$ market, with $p$ being the $B$ price of $A$). It stands for the differential equation






which is derived from assuming the fluctuations in the information entropy of two uniform distributions have equal information content. These fluctuations register as fluctuations in the "price" $p$. The differential equation is a generalization of one Irving Fisher wrote in [his thesis](http://informationtransfereconomics.blogspot.com/2014/08/fishers-proto-information-transfer.html). It has the solution






I will occasionally write the relationships without the "detector" $p$ or explicitly calling out the information transfer (IT) index:




Information transfer index


Frequently shortened to IT index, the parameter $k$ in the information equilibrium relationship above, or the information transfer (IT) relationship below.

Log-linear form

See [this post](http://informationtransfereconomics.blogspot.com/2016/08/log-linear-form-of-general-information.html) for the log-linear form of an information equilibrium relationship.

Dynamic equilibrium

An information equilibrium relationship implies that

$$<br />
\frac{d}{dt} \log \frac{A}{B} = (k - 1) r<br />
$$


if $B$ is growing at a rate $r$, i.e. $B \sim e^{rt}$. More about this [here](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-unemployment-rate.html) or in [this presentation](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html). Essentially, $A/B$ grows (or decreases) at a constant rate on a logarithmic scale (a constant continuously compounded annual rate of change).

Because $A/B$ is proportional to the right hand side of the information equilibrium condition above, [the same thing goes for prices](http://informationtransfereconomics.blogspot.com/2017/01/housing-prices-and-dynamic-equilibrium.html):

$$<br />
\frac{d}{dt} \log \frac{A}{B} = \frac{d}{dt} \log \frac{p}{k} = \frac{d}{dt} \log p = (k - 1) r<br />
$$


Non-ideal information transfer


The notation $p : A \rightarrow B$ represents an information transfer (IT) relationship between $A$ and $B$ with price $p$. It is basically an information equilibrium relationship with information loss such that the information in fluctuations in $A$ are only partially registered in changes in $B$. The differential equation becomes a differential inequality






Via Gronwall's inequality (see [here](http://informationtransfereconomics.blogspot.com/2016/06/gronwalls-inequality-and-information.html)), the information equilibrium relationship defined above is a bound on this information transfer relationship. The observed price $p^{*}$ will fall below the information equilibrium price, $p^{*} \leq p$. The same applies to the observable $A$; we will see the observed value fall below the information equilibrium value, $A^{*} \leq A$.



Partition function approach


The information equilibrium partition function approach starts with an ensemble of markets $p_{i} : A_{i} \rightleftarrows B$ with common factor of production $B$ and defines the [partition function](https://en.wikipedia.org/wiki/Partition_function_\(statistical_mechanics\))






where $\beta \equiv \log (b + 1)$ and $b \equiv (B - B_{ref})/B_{ref}$. The normal application of the partition function in e.g. thermodynamics follows. It is derived from assuming a maximum entropy distribution of $B$ among the markets $A$ where the macrostate (the collection of all the markets $\{ A_{i}\}$) has a well defined ensemble average $\langle k \rangle$ (see [here](http://informationtransfereconomics.blogspot.com/2016/09/balanced-growth-maximum-entropy-and.html) for more details).



Entropic force


Entropic forces are essentially the same in information transfer economics as in thermodynamics. They are "emergent" forces that do not have a description in terms of individual agents (e.g. atoms in thermodynamics). They arise from a tendency to maintain or achieve a particular maximum entropy distribution, or to keep two distributions in information equilibrium.

Economic state space

Refers to the set of IT indices making up the partition function above. Entropic forces can maintain a particular distribution of IT indices. More about this [here](http://informationtransfereconomics.blogspot.com/2016/09/the-economic-state-space-mini-seminar.html).

I will also refer to the set of all available baskets of goods (region constrained by a budget constraint) as the economic state space. Gary Becker called this the opportunity set. It is discussed more in [these presentation notes](http://informationtransfereconomics.blogspot.com/2016/01/draft-paper-for-talk-this-summer.html) (with slides).
