---
title: "Adam Smith's circular logic and path dependence in economic theory"
date: 2015-06-08T21:05:00.001-07:00
updated: 2015-06-10T20:20:55.935-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/06/adam-smiths-circular-logic-and-path.html
---

> _The way economics is today has much to do with the way the discipline got its start. Economists call this overall effect “path dependence,” meaning that its interpretations of the world today are determined by choices that others made in the past. This has to do with the various inquiries that economists have adopted over the years._

David Warsh has a great essay on the history of economics (don't forget to read the rest of the series); [the most recent one](http://www.economicprincipals.com/issues/2015.06.07/1753.html), the one from which the quote above was taken, is about Adam Smith and how his Wealth of Nations came to be written.



One of the major developments of the Wealth of Nations is the invention of what we'd call now an equilibrium price around which there are market fluctuations. Smith takes Book 1, Chapter 7 to develop this concept:

> _When the price of any commodity is neither more nor less than what is sufficient to pay the rent of the land, the wages of the labour, and the profits of the stock employed in raising, preparing, and bringing it to market, according to their natural rates, the commodity is then sold for what may be called its natural price._

Here, the natural price of X depends on the natural price of Y and Z, so this doesn't pin it down by itself. It's a difficult concept! Mathematically speaking, without setting up a scale p₀, so that the price of any given good is _p = k p₀_ for some _k_, there is really nothing stopping a price from being 0 or ∞. Sure relative prices _p₁/p₂ = (k₁ p₀)/(k₂ p₀) = k₁/k₂_ are independent of this fundamental scale, but some unknown mechanism must come along and gives us an idea of where the decimal place is in a typical price \[1\]. Back to Smith:

> _The natural price, therefore, is, as it were, the central price, to which the prices of all commodities are continually gravitating._

The natural price is the price to which the price of X is converging. The rest of book 1 chapter 7 details how self-interested action could plausibly cause the price of X to converge to the natural price of X. Essentially, Adam Smith is saying:



-   Self-interested choices cause the price of X to converge on the natural price
-   The natural price of X is the price to which prices converge due to self-interested choices



That is to say the definition of the natural price is entirely circular. Now I'm in no way the first person to notice this (it appears from a cursory Google search that Marxian and Austrian economists are ONIT), and the circularity itself is not my point. The charitable view I am taking says that this is an implicit definition of the natural price -- the natural price being the solution of this self-consistent system of human choices. This self consistent system generates the fundamental price scale _p₀_.



The interesting part is how economists solved this self-consistent system -- by introducing an auxiliary field called utility. When we introduce utility we can restate the definitions like this:

-   Self-interested choices maximize utility
-   Natural prices are the prices at which utility is maximized



It's no longer a circular definition, but at some cost. It's not just utility of X, you need (at least) the utility of Y (so there is a possibility of choice) as well as some limitation (scarcity, e.g. the budget constraint M). A typical two-good maximization problem looks like this:



![](<media/utility max diagram.png>)

The price scale is introduced via the budget constraint (_p₀ = M_); all prices are _p = k M_ for some _k_.



But you can see built in from the start, whether in Adam Smith or in marginal utility, we build our first prices from human decisions -- the price of X is the fixed point of a self-consistent set of human behaviors or teased out of an optimization problem, optimized by human agents. This path dependence entrenching human choices in the evolution of economic thought has left out the possibility that prices are just the most likely prices if all states are seen as equally likely (entropy maximization). In the graphs below, the shaded area under the budget constraint is the set of possible price states. In one, we have a two dimensional system (_D = 2_) with the price in the middle; in the other, we have a large dimensional system (_D >> 2_) with the price appearing near the surface of the polytope since most points in a high dimensional convex solid are near its surface \[2\].



![](<media/utility max diagram 2a.png>)![](<media/utility max diagram 2b.png>)

For that mechanism, we'd have to accept collectively irrational, complex behavior of humans making decisions towards different, even conflicting, ends looking to all the world like randomness.





**Update 6/10/2015:**

[Another interesting take](http://ckmurray.blogspot.com/2015/06/adam-smiths-pin-factory-capital-vs.html) on Adam Smith (and the division of labor) from Cameron Murray.





**Footnotes:**


\[1\] This is a serious issue. It takes some complicated mathematics to generate a scale from nothing.  In particle physics, this kind of scale usually comes from what is called a conformal anomaly -- (explicit) scale symmetry breaking by the theory itself. This is where (most of) the mass of a proton comes from: the QCD scale that is generated by a conformal anomaly. This is almost certainly not what is happening in economics, but it gives a possible mechanism.



\[2\] Probably an easier way to see the centroid of the _D >> 2_ dimensional polytope approach the budget constraint is to look at the formula for the average of the vertices of the triangle (for _D = 2_) and the polytope (_D >> 2_). There are D points for D dimensions, plus the origin for a total of _D + 1_ points, so the budget satisfaction will go as _D/(D + 1)_ -- _D_ non zero prices and one zero price divided by the number of points _D + 1_. The limit as _D → ∞_ is 1, i.e. saturation of the budget constraint.
