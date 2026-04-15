---
title: "Maybe Paul Romer would be interested in information equilibrium?"
date: 2015-07-18T17:26:00.001-07:00
updated: 2015-07-18T17:26:28.851-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/07/maybe-paul-romer-would-be-interested-in.html
---

![Cesar Hidalgo's Why Information Grows.](media/IMG_0012.PNG)

[Paul Romer](http://paulromer.net/why-information-grows/) has recently read _Why Information Grows_ by Cesar Hidalgo and cites it approvingly as an example of how to think like a physicist. I actually learned of the book from [Diane Coyle's review](http://www.enlightenmenteconomics.com/blog/index.php/2015/06/the-information-economy/) and was both interested and a bit afraid that Hidalgo might have scooped me (so I immediately bought a copy). In some really general ways he does say some similar things (q.v. my [post here](http://informationtransfereconomics.blogspot.com/2015/06/34-of-knife-34-of-fork-and-34-of-spoon.html)), but he doesn't go as far as the information transfer framework/information equilibrium.



This blog post is intended to see if Romer is interested in going a bit further down the rabbit hole of information theory ...



**A short introduction**


The original idea behind _information equilibrium_ is from the physicists [Peter Fielitz and Guenter Borchardt](http://arxiv.org/abs/0905.0610); I have applied it to economics -- thinking out loud with this blog (and likely making many mistakes as my training is in physics, not economics).



The basic idea is that if you want to say two quantities _A_ and _B_ are related to each other (interest rates and the money supply; capital and output) at a bare minimum the two quantities must obey a pretty simple condition based on a communication channel from _A_ (information source) to _B_ (information destination):






At best, _B_ can only receive all of the information _A_ sends. This is the basis of the information transfer framework and it has two regimes: non-ideal (greater than sign) and ideal (equal sign). Ideal information transfer is also called information equilibrium and is related to the various meanings of equilibrium in economics. From the above condition, Fielitz and Borchardt motivated the differential equation:






that effectively says in equilibrium fluctuations in A have to produce informationally equivalent fluctuations in B. On the left hand side, we define the derivative (the quantity that 'detects' the flow of information in Fielitz and Borchardt's paper) as an abstract price. On this blog, I've written this information transfer relationship with the shorthand $p : A \rightarrow B$ (detector/price : source → destination). Equality represents the case of information equilibrium ('economic equilibrium'), but the equilibrium solution also represents a bound on the non-ideal information transfer case (via [Gronwall's inequality](https://en.wikipedia.org/wiki/Gr%C3%B6nwall%27s_inequality)).



As a mathematical formalism, information equilibrium allows you to come up with a bunch of standard results in economics fairly simply (for example, [this derivation of the Euler equation](http://informationtransfereconomics.blogspot.com/2015/06/the-euler-equation-as-maximum-entropy.html) is pretty cool, and [non-ideal information transfer](http://informationtransfereconomics.blogspot.com/2015/06/eulers-theorem-and-non-ideal.html) let's you escape Vollrath's trilemma on Euler's theorem that Romer discussed on his blog). The intuition behind it however, that human behavior is so complex that it is indistinguishable from randomness except in situations of large scale coordination (like the panics in stock market crashes), does take a bit of getting used to given the dominant paradigm of human decision-making in traditional economics.



As a teaser, here are a few posts that assemble the Solow growth model as an information equilibrium model:

-   _[More on Cobb-Douglas functions and information transfer](http://informationtransfereconomics.blogspot.com/2014/05/more-on-cobb-douglas-functions-and.html)_: Second half of this post derives Cobb-Douglas production function from information equilibrium
-   _[The information transfer Solow growth model is remarkably accurate](http://informationtransfereconomics.blogspot.com/2014/12/the-information-transfer-solow-growth.html)_: Compares the Cobb-Douglas production function to data
-   _[The rest of the Solow model](http://informationtransfereconomics.blogspot.com/2015/05/the-rest-of-solow-model.html)_: Adding the dynamics of capital at the heart of the Solow model
-   _[Dynamics of the savings rate and Solow + IS-LM](http://informationtransfereconomics.blogspot.com/2015/05/dynamics-of-savings-rate-and-solow-is-lm.html)_: Adds the savings rate and interest rate
