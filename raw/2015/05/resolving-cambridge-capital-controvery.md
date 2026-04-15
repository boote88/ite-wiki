---
title: Resolving the Cambridge capital controvery with abstract algebra
date: 2015-05-28T16:00:00.000-07:00
updated: 2018-10-14T11:35:22.005-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/05/resolving-cambridge-capital-controvery.html
---

The title is a bit of a joke, and for the controversy see [here](http://en.wikipedia.org/wiki/Cambridge_capital_controversy). Looking into the [Solow model](http://informationtransfereconomics.blogspot.com/2015/05/the-rest-of-solow-model.html) bumps you into the question of what "capital" (K) is, and that met with the titular controversy awhile back where Cambridge, MA said you could add up different stuff in a sensible way while Cambridge, UK said you couldn't.



The information equilibrium (IE) model calls the argument for the UK (and Joan Robinson), but allows (at least) two possibilities for definitions of capital that are sensible. These sensible definitions weren't advocated by Solow/Samuelson at MIT, hence why I say that the UK won the debate: you can't just add stuff up and get a sensible answer.



First, two quick "proofs". I already showed IE is an [equivalence relation](http://informationtransfereconomics.blogspot.com/2015/03/information-equilibrium-is-equivalence.html) (you can use it to define a set of things in IE with some economic aggregate), but I need a bit more: IE is a [group](http://en.wikipedia.org/wiki/Group_\(mathematics\)) under multiplication.



If $A \rightleftarrows K$ (with IT index $a$), then $A^{x} \rightleftarrows K$ (with IT index $a x$) because:






(I show this because it applies for real exponents rather than just natural numbers and that might be important for some reason in the future; for natural numbers $x$ the following result would suffice.)



If $A \rightleftarrows K$ and $B \rightleftarrows K$ (with IT indices $a$ and $b$), then $A B \rightleftarrows K$ (with IT index $a + b$) because:






So we have the set of all things that are in IE with $K$, and the product of any two of those things is another thing in the set — therefore it's a group. It is not, however, a [ring](http://en.wikipedia.org/wiki/Ring_\(mathematics\)) — the set isn't closed under addition:








This basically was Joan Robinson's point — unless $A$ and $B$ are the same thing, you're comparing apples and oranges. Money doesn't help us either and if you introduce it, the relative prices of the capital goods become important \*\*.



**Sensible definitions of capital**



Of course, this points to the first sensible solution to the capital controversy: instead of adding up capital items, use the geometric mean. Using the two results above, you can show that if $A \rightleftarrows K$, $B \rightleftarrows K$, $C \rightleftarrows K$, etc, then






The geometric mean is also the only sensible mean for capital goods measured either as indices or in terms of money.



The second sensible solution to the controversy is a [partition function](http://en.wikipedia.org/wiki/Partition_function_\(mathematics\)) approach (as I've done [here](http://informationtransfereconomics.blogspot.com/2014/06/the-macroeconomic-partition-function.html)) where we simply define capital to be the expected value of the capital operator, which is just the sum of the individual capital goods operators:










**\*\* Update 29 May 2015**

I thought I'd add in the details of the sentence I marked with \*\* above. We assume two goods markets (information equilibrium conditions) $p_{a} : N \rightleftarrows A$ and $p_{b} : N \rightleftarrows B$ where $N$ is aggregate demand/nominal output measured in money and the $p_{i}$ are prices. That gives us:










which basically shows that $K$ is in information equilibrium with aggregate demand. Note the appearance of the prices in the information transfer index.

...

**Update 14 October 2018**

Changed the old notation $A \rightarrow B$ to the better notation for an information equilibrium relationship: $A \rightleftarrows B$. Added "measured in money" to 29 May 2015 update.
