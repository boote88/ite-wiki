---
title: Parsing the macrohistory database ... for meaning
date: 2016-10-27T14:00:00.000-07:00
updated: 2016-10-27T14:36:51.989-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/10/parsing-macrohistory-database-for.html
---

![](<media/large database macrodata -principal component- 0.png>)![](<media/large database macrodata -principal component- long 1.png>)
Adding to my expanding series ([here](http://informationtransfereconomics.blogspot.com/2016/10/parsing-macrohistory-database-interest.html), [here](http://informationtransfereconomics.blogspot.com/2016/10/parsing-macrohistory-database-principal.html), [here](http://informationtransfereconomics.blogspot.com/2016/10/parsing-macrohistory-database-more.html)) on the [macrohistory database](http://www.macrohistory.net/data/#DownloadData), I thought I'd discuss the possible meanings behind the principal components (pictured above) of the long and short term interest rate time series from the 1870s to the present being approximately equal to the US time series over that period. Let me begin a (probably not exhaustive) list:



**Theory 1:** _The US has dominated the (Western) global economy since the 1870s_



It is true that [the US has played a large role](https://infogr.am/Share-of-world-GDP-throughout-history) in the (Western) global economy, but it doesn't have its commanding lead until the post-WWII period.



**Theory 2:** _The principal component is actually a combination of the pre-WWII Europe and the post-WWII US_



We'll use the UK in our example. Before WWII, the UK dominates interest rates; after, the US does. Since the UK dominates before WWII, the pre-WWII US interest rates are basically the UK rates. Since the post-WWII rates are dominated by the US, the UK's post-WWII rates are basically the US rates. Therefore either the US or UK would work as the principal component.

**Theory 3:** _The principal component is actually just the post-WWII US_



Before WWII, interest rates in the database seem to be fluctuations around a roughly constant level and the global Great Depression. Since there's nothing differentiating them, the only feature we're extracting is the rise and fall of interest rates in the post-WWII period when the US dominates the economy. The algorithm had to choose a country for the pre-WWII piece and the US works just as well as any.

**Theory 4:** _There is a "global economy", and the principal component gives us its interest rate_



This theory says that there is some underlying global signal and each nation's interest rate represents a particular measurement of it. Each nation taps into the global "pulse" in a different way, so the time series differ. However, looking at all the data you can get a glimpse of the economic heart beat. This theory could be interpreted as a generalization of theory 2 where no one economy dominates for very long.



...



These theories are all generically related by saying that the principal component PC is a linear combination of different numbers of pieces.



1: _PC = A + ε_



2: _PC = a A + b B + ε_



3: _PC = a A + X + ε_



4: _PC = a A + b B + c C + ... + ε_



In a sense, this isn't saying much. This is practically a definition of what a principal component analysis is. It organizes our thinking, though. And this allows us to make a surprising conclusion. Interest rates in a country we'll call _D_ are explained by factors not domestic to _D_. Basically,



_D = d PC + ε_



Where PC is primarily other countries (and might even be just one). Therefore, if demographic factors are the cause of high interest rates in your model, they are demographic factors in _A_ (using theory 1). If monetary factors are the cause, they are monetary factors in _A_.



Another way to put this is that the mechanism of interest rate "importation" (i.e. how the interest rate of _A_ becomes the interest rate of _D_ \[1\], and if/how the factors domestic to _D_ have an effect) is almost more important than the mechanism for understanding the principal component interest rate. It also means that domestic factors are usually unimportant, except when you are looking at the principal component, in which case they are very important.



I can make this more clear using the IT model as an explicit model (just imagine your favorite stand-in model if you don't like it). Let's use theory 1 above (I'll leave it as an exercise to the reader how to generalize is). In country _A_, interest rates are given by



log_(rA) = a1_ log_(NA/MA) + a0_



However, in country _D_, they are given by



log_(rD) = d0 (a1_ log_(NA/MA) + a0) + f(ND, MD, ...)_



In country _D_, interest rates will seem to be governed by entirely different mechanisms than those in country _A_.



Speculation: Does this translate into economic theories in different countries? Does country _A_ have more attempts at "scientific"/"fundamentals" -based theories (e.g. a purely monetary model), while other countries have more "social"/"relationships" -based theories? Does country _A_ think economics is explainable while country _D_ thinks economics is ineffable?



...



**Footnotes**



\[1\] An example of such a mechanism would be a country having lots of foreign currency denominated debt, such as [Australia with US dollar-denominated debt](http://informationtransfereconomics.blogspot.com/2013/10/resolving-australian-interest-rate.html).
