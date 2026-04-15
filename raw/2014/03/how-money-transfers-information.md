---
title: How money transfers information
date: 2014-03-15T15:14:00.000-07:00
updated: 2014-03-15T17:08:14.255-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/03/how-money-transfers-information.html
---

[In this post](http://informationtransfereconomics.blogspot.com/2014/03/apples-bananas-and-information-transfer.html) I showed how the information flows in a simple market for apples, but here I'm going to show what I hinted at in the earlier post: _money is a tool to transfer information from the demand to the supply._



![](<media/price level 1.png>)![](<media/price level 2.png>)

Let's start with a simple system of $d$ buyers (green) and two suppliers of gray bundles of something. Each sale adds $+\log_{2} d$ bits of information \[1\] about the size of the market $d$ and the distribution of demand to a supplier. Or at least it would if the supplier had some knowledge of the size of $d$ in the first place. If there was only one supplier, that supplier could use the total amount of goods sold $s$ as an estimate since the total amount of information would have to be less than or equal to the information coming from the buyers (the source), i.e. (dropping the base of the $\log$'s):






You can't get more information from a message than the message contains! However, there is more than one supplier, so each supplier only sees a fraction of the total supply and a fraction of the total demand. If this were all there is to it, then while each transaction could transfer $\log d$ bits of information, the supplier would have no idea. Enter money; now with each sale a supplier acquires a few inherently worthless tokens:



![](<media/price level 3.png>)

How does this help? Well, because these tokens are available to everyone (either set up by some government or based on custom), the supplier has some idea of how many are out there (let's call it $m$):



![](<media/price level 4.png>)

Now each sale is accompanied by $n_{m}$ tokens of money, so that each token transfers $+&nbsp;\log m$ bits of information from the demand to the supply. This monetary system could potentially work well enough so that we can say the information captured by the supply is equal to the demand, thus equation (1) becomes:






We call this ideal information transfer when we use the equal sign. If we take $n_{s} = S/dS$ where $dS$ is the smallest/infinitesimal unit \[2\] of supply and likewise $n_{d} = D/dD$ for demand and assume $D, S \gg 1$ (a very large market), we can write:










where we've defined the _**information transfer index**_ $\kappa \equiv \log s/\log d$. The left hand side of equation (3) can be identified with the price $p$ because it is proportional to $dM/dS$, or the rate of change of money for the smallest increase in quantity supplied.



But wait, there's more! See, money can be exchanged for all kinds of goods and services:



![](<media/price level 5.png>)
[aggregate demand](http://en.wikipedia.org/wiki/Aggregate_demand)



where $P$ is an overall measure of the price of all goods and services ($AD$); it's called the [price level](http://en.wikipedia.org/wiki/Price_level). The rate of change of the price level over time is [inflation](http://en.wikipedia.org/wiki/Inflation). Now for the totally awesome part: we can solve equation (4) for aggregate demand in terms of the money supply. It's a differential equation that can be solved by integration. We re-arrange equation 4 like this:


















If $\kappa = 1/2$, then $P \sim M$, and the price level rises with the money supply, i.e. [the quantity theory of money](http://en.wikipedia.org/wiki/Quantity_theory_of_money). Awesome, huh? Except the quantity theory doesn't really work that well ($\kappa \sim 0.6$ works better for the US and other countries, except Japan where $\kappa \sim 1$ is a better model). But we left out a big piece: aggregate demand (e.g. NGDP) is measured in the same units as the money supply. And to top it off the money supply is adjusted by the central bank based on economic conditions! This is the picture of the macroeconomy:



![](<media/price level 6.png>)

What does it mean? It means that $\kappa = \log m/\log d$, or the amount of information transferred from the demand to the supply relative to the amount of information transferred by money, is changing! If we assume this happens somewhat slowly \[3\], we can transform equation (6) into:








where we've replaced M with the monetary base, AD with NGDP, grouped a bunch of constants as $\alpha$, and introduced a new constant $c_{0}$ since the units of money are arbitrary. We can fit this model to the price level (it works best, see the lower right graph, when the monetary base is actually just the currency component of the monetary base):



![](<media/basic us model m0 fit parameter tests.png>)

Pretty cool, huh? Using this model (the **_information transfer model_** or ITM), we seem to get less inflation from a given increase in the money supply as the money supply and the economy get bigger. In fact, it can even go the other way -- in Japan an increase in the money supply (blue) decreases the price level (brown):



![](<media/japan deflationary monetary expansion.png>)

The rest of this blog is devoted to exploring this model and the concept of information transfer in economic, even commenting on current events based on these ideas. Have a look around!



**Footnotes**



\[1\] You can think of it as a sale discovering the ID number of a buyer. If the ID number is a member of the set {1, 2, 3, 4, ... , d}, then you need $\log_{2} d$ bits to represent the ID number. Thus, a sale transfers $\log_{2} d$ bits from the buyer (demand) to the supplier (supply).  I will drop the subscript 2 for the binary log in the rest of the post.



\[2\] We are looking at infinitesimal units to see how supply and demand change with respect to each other. for those unfamiliar with this concept, it forms [the basis of calculus](http://en.wikipedia.org/wiki/Leibniz%27s_notation). And as a physicist, I am given to frequent [abuses of notation](http://en.wikipedia.org/wiki/Abuse_of_notation).



\[3\] Technically, integrating equation (5) as we did assumes $\kappa$ is independent of $AD$ and $M$. However, if we assume $\kappa$ doesn't change rapidly with $M$ or $NGDP$, then the integration can proceed as shown, but is only an approximation.
