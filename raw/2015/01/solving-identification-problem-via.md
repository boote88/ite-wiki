---
title: Solving the identification problem via information equilibrium
date: 2015-01-16T12:13:00.001-08:00
updated: 2015-01-16T12:13:31.555-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/01/solving-identification-problem-via.html
---

[David Glasner](http://uneasymoney.com/2014/12/23/forget-the-monetary-base-and-just-pay-attention-to-the-price-level/) mentions [the identification problem](http://en.wikipedia.org/wiki/Parameter_identification_problem) as a rationale for disregarding the quantity theory of money (in the course of an otherwise interesting post on the uselessness of monetary aggregates for monetary policy). In my continuing effort to [win Glasner over](http://informationtransfereconomics.blogspot.com/2014/12/an-information-transfer-traffic-model.html) to this blog's approach to complex economic systems through information equilibrium -- which produces a theory that has the quantity theory as its high inflation limit (see [here](http://informationtransfereconomics.blogspot.com/2014/05/limits-of-information-transfer-model.html), [here](http://informationtransfereconomics.blogspot.com/2013/07/recovering-quantity-theory-from.html)) -- I thought I'd target the identification problem.



The [identification problem in economics](http://www.sjsu.edu/faculty/watkins/identification.htm), in its simplest form, is the statement that a series of changing prices cannot be uniquely identified as a series of moves along supply and demand curves (basically you can't get two slopes -- elasticities of supply, demand -- from a series of two variables P, Q -- the price and equilibrium quantity supplied).



In the information transfer/equilibrium model, the relationship between the price (P), supply (S) and demand (D) is given by






This relationship can be thought of as coming from a several different lines of argument (a tiny modification to [an equation that appears in Irving Fisher's thesis](http://informationtransfereconomics.blogspot.com/2014/08/fishers-proto-information-transfer.html), the [simplest theory that obeys long run neutrality](http://informationtransfereconomics.blogspot.com/2014/02/i-quantity-theory-and-effective-field.html), or -- as [Fielitz and Borchardt arrived at it](http://informationtransfereconomics.blogspot.com/2013/04/the-information-transfer-model.html) -- [an information equilibrium argument](http://informationtransfereconomics.blogspot.com/2014/03/apples-bananas-and-information-transfer.html), including [a temporal version](http://informationtransfereconomics.blogspot.com/2014/12/how-money-transfers-information-from.html)). The information transfer index $\kappa$ appears as it does as a reference to Fielitz and Borchardt's original paper. This relationship allows you to [derive supply and demand diagrams](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html), holding either demand or supply 'constant' (I [like to think of it](http://informationtransfereconomics.blogspot.com/2014/06/is-supply-curve-flat.html) as in contact with the supply and demand equivalents of a thermal bath).



The key to overcoming the identification problem is the fact that this equation has effectively one parameter ($\kappa$) from which both slopes (elasticities) of the supply and demand curves follow (see [here](http://informationtransfereconomics.blogspot.com/2013/08/what-is-supply-and-demand-diagram-anyway.html) and [here](http://informationtransfereconomics.blogspot.com/2013/04/the-previous-post-with-more-words-and.html)). It is helpful to think of it as a 3D surface, like this one (in terms of NGDP, the currency component of the base and the price level):



![](<media/basic us price level m0 1.png>)

Now the source of the identification problem helps you! As long as your data represents movement of both the supply and demand curves, the price measurements (samples of the LHS of the equation above) constrain the curvature of this 3D surface. And if they don't represent moves of both curves, well, you're back to the [reduced form](http://en.wikipedia.org/wiki/Reduced_form) -- you're fitting just a supply or demand curve. The quantity supplied then gives you the relative level of the quantity supplied to the price (there is still an overall scale freedom -- if you moved the decimal place on every dollar, you haven't done anything).



The essence of how information equilibrium solves the identification problem is by relating the slopes of the supply and demand curves through $\kappa$.



In monetary economics, though, $\kappa$ changes -- which might make you think we've re-introduced the identification problem! And that would be true if you allowed $\kappa$ to be a general function. This is where information theory comes to the rescue again because $\kappa$ has a specific meaning. It measures [the relative size of the information units](http://informationtransfereconomics.blogspot.com/2014/06/money-unit-of-information-and-medium-of.html) for D and S, or in monetary economics, NGDP and 'the money supply'. Since a 'dollar' of NGDP (N) and a 'dollar' of money aren't equivalent units of information (especially at different times), we need to let $\kappa = \kappa (N, M)$. I admit the functional form I use is an ansatz (fancy word for guess) based on the [definition of the information transfer index](http://informationtransfereconomics.blogspot.com/2013/06/more-on-information-transfer-index.html), but it works empirically and can be [motivated through a thermodynamics-based approach](http://informationtransfereconomics.blogspot.com/2014/06/the-macroeconomic-partition-function.html):








This changing $\kappa$ [allows the model](http://informationtransfereconomics.blogspot.com/2014/11/the-information-transfer-model-and.html) to behave like the quantity theory of money at times as well as demonstrate many properties of the liquidity trap at others. It isn't wishy-washy about it though: it specifically shows when each regime is valid ($\kappa \sim 1/2$ means the QTM is a good approximation and $\kappa \sim 1$ means something like the IS-LM model is a good approximation).



The other benefit of this model is that it solves the perennial problem of which monetary aggregate is relevant to inflation empirically -- [we choose the aggregate that fits inflation best](http://informationtransfereconomics.blogspot.com/2014/02/models-and-metrics.html). And it turns out the answer is the simplest possible one: currency in circulation. Not M2, not MZM, not the monetary base (that includes central bank reserves).



![](<media/basic us model m0 fit parameter tests.png>)

The result is a darn good model not just for the US (the graph below uses smoothed inputs), but for Japan and other countries:



![](<media/inflation smoothed pce -1-.png>)![](<media/japan price level -simple-.png>)
