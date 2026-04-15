---
title: Partitions of an economy
date: 2015-11-04T18:42:00.002-08:00
updated: 2015-11-07T10:17:57.966-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/11/partitions-of-economy.html
---

I am working towards quantifying something I've said several times (e.g. [here](http://informationtransfereconomics.blogspot.com/2014/02/ii-entropy-and-microfoundations.html) or [here](http://informationtransfereconomics.blogspot.com/2015/05/what-is-economic-growth.html) or [here](http://informationtransfereconomics.blogspot.com/2014/09/the-great-stagnation-information.html)) -- that [the trend towards lower growth as economies](http://informationtransfereconomics.blogspot.com/2014/06/output-and-price-level-behavior-across.html) grow is a result of there being more ways an economy can be composed of many low growth industries than a few high growth industries, the former being a higher entropy state. This was an analogy with thermodynamics: there are more ways to emit several low energy photons than a few high energy ones, hence hot things are red, not blue (unless you get really hot ... )



Essentially, I am trying to derive the "economic temperature" _~ log M_ in a more rigorous way. See the section of [the paper](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html) on "statistical economics" for a starting point.



Let's say nominal ouptut (NGDP) is given by



_N(t) = N0 exp ρ t_


with growth rate _ρ_. Let's say that output consists of several industries (or firms), each with their own growth rate _rᵢ_ so that



_N(t) = A₁ exp r₁ t + A₂ exp r₂ t + ..._


If the growth rates are small and we keep ourselves focused on the short run, then we can say _ρ t_ << 1 and _rᵢ t_ << 1 so that



_N0 ~ A₁ + A₂ + ..._
_ρ ~ (1/N0) (A₁ r₁ + A₂ r₂ + ... )_


Let's say _N0_ is an integer, but very large. Then the _Aᵢ_ represent a partition of _N0_. For example, here's a partition of _N0_ \= 1000:



![](<media/partitions 1.png>)


These partitions have a smooth distribution for _N0_ \>> 1 (the red line, the Vershik-Kerov-Logan-Shepp limit shape). Note, I mentioned Ferrers diagrams at [the very beginning of this blog](http://informationtransfereconomics.blogspot.com/2013/05/economics-as-counting-problem.html). Here are several partitions together:



![](<media/partitions 2.png>)


The red curve represents the most likely paritition of an economy of nominal output _N0_ into various industries -- so we have the distribution of _Aᵢ_. The overall growth rate is then proportional to the dot product _Σ Aᵢ rᵢ_ ... note that _Aᵢ rᵢ_ is itself another partition, this time of _N0 ρ_.



So if _Aᵢ_ has the VKLS distribution and _Aᵢ rᵢ_ also has the VKLS distribution, we should be able to work out the distribution of rᵢ (under the assumption that _rᵢ_ and _Aᵢ_ are independent, [Gibrat's law](https://en.wikipedia.org/wiki/Gibrat%27s_law)) ...







**Update 11/5/2015:**


The last statements aren't really true because of the possibility for negative growth rates _rᵢ_. The terms _Aᵢ rᵢ_ are not a partition of _N0 ρ._
