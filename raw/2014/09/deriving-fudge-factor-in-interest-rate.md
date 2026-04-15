---
title: "Deriving the \"fudge factor\" in the interest rate market"
date: 2014-09-30T16:36:00.000-07:00
updated: 2014-10-03T10:41:27.137-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/09/deriving-fudge-factor-in-interest-rate.html
---

![](<media/ite interest rates us.png>)
Here's a possible solution to one of the [unsolved problems](http://informationtransfereconomics.blogspot.com/2014/03/unsolved-problems-in-information.html) of information transfer economics: the fudge factor $c$ in the interest rate market.



In the (long term \[2\]) interest rate market there was an unexplained constant $c$ so that the market was (in my shorthand _Price:Demand → Supply_)





So that the final equation relating the interest rate to NGDP and the currency base M0 was





And the best fit is graphed in the graph above. This is a weird way of using the information transfer model (ITM). We're not describing the interest rate market in terms of the supply and demand for bonds. The interest rate has an inverse relationship with the price of bonds, so the price (the $r^{1/c}$ \[1\]) in the interest rate market defined by _Price:Demand → Supply_ is actually a price for money (not bonds) and the supply is the money supply (not the supply of bonds).



The key to understanding why we ended up with this backwards way to go about making an information transfer model for the interest rate lies in [the ISLM model](http://informationtransfereconomics.blogspot.com/2013/08/deriving-is-lm-model-from-information.html). And that also gives us the solution for whence the constant $c$.



In the ISLM model, we have the LM market where there is a function $L(i, Y)$ that represents the demand for money \[3\]. Here's a diagram from Wikipedia:


[![](media/500px-Money_Market_diagram.svg.png)](http://upload.wikimedia.org/wikipedia/commons/thumb/d/d2/Money_Market_diagram.svg/500px-Money_Market_diagram.svg.png)

Well, basically, the slope of $L(i, Y)$ (in log space) is $c$. If we write down the [ITM version of the function](http://informationtransfereconomics.blogspot.com/2013/08/deriving-is-lm-model-from-information.html) $L$ we get:









If we do a Taylor series of equation (3) around $M_{ref}$, keeping only the linear terms, we get











and a normaliztion factor out front (that will depend on NGDP). So now we can see what $c$ is





This makes me feel much more comfortable with the interest rate model since the constant $c$ isn't so much of a "fudge factor" anymore.



\[1\] Note that whether you have _c_ or _1/c_ depends on which side you put the constant on in equation (1), and I haven't necessarily been consistent throughout the blog.

\[2\] It's in the short term interest rate market as well, I am just referring using the long term market as an example in this post -- for the short term market, replace M0 with MB.

\[3\] **Added 10/3/2014:** I am using _r = i_ here and the generic ISLM model doesn't make a distinction between real and nominal rates -- I am referring to nominal rates.
