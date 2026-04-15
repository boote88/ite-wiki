---
title: "Walras' law"
date: 2013-09-13T18:20:00.002-07:00
updated: 2013-09-14T21:45:32.982-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/09/walras-law.html
---

[Paul Krugman](http://krugman.blogs.nytimes.com/2013/09/13/tobin-and-the-taper-wonkish/) made a reference to [Walras' law](http://en.wikipedia.org/wiki/Walras'_law) today which inspired me to try and figure out what the "law" is in the information transfer framework. In this first attempt, I managed to force the [incompressible fluid condition](http://en.wikipedia.org/wiki/Incompressible_flow) (divergence is zero) into something resembling Walras' law and tentatively declared success. Start with a series of markets: 














If we consider that the markets are independent (the goods supplied are not close substitutes so that the demand for $i$ is not _directly_ \[1\] changed by a change in the supply of $j$), then it is reasonable to assume 









[definition of the price](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html)




This is one half of Walras' law where the sum of the values of the excess supplies ($dQ^{s}$) is zero. To get the other half (the sum of the values of the excess demand is zero) involves a little more work. This is because in the information transfer model we have the relationship $P_{i} dQ^{s}_{i} = dQ^{s}_{i}$; effectively, the units in Walras' law as written are wrong. Demand has units of value already (price times number supplied). However, if we have floating information sources and destinations, the [solution to the differential equation](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html) relating the supply and demand is:





[elasticities of supply and demand](http://informationtransfereconomics.blogspot.com/2013/04/the-previous-post-with-more-words-and.html)








Which mostly recovers Walras' law. The aspect about the excess supply adding to zero is a direct result of the assumption of a divergenceless demand vector $\text{(1)}$, while getting the demand side involves some additional assumptions about the elasticity of demand. However! If we don't care about getting Walras's law exactly right, we can start from the differential of the supply 














And is related to $\mathbf{Q}^s$ and $\mathbf{Q}^d$ being incompressible vector fields (with can then be related to conservation of mass).



\[1\] By directly changed, I mean via and explicit dependence $Q^{d}_{i} = f(Q^{s}_{i}, ... Q^{s}_{j} ... )$. We have all the markets interacting with each other via the divergenceless condition, but absent that, the markets would not depend on each other.
