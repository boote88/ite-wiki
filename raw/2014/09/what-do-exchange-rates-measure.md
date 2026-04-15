---
title: "What do exchange rates measure?"
date: 2014-09-04T16:01:00.000-07:00
updated: 2014-09-04T16:01:08.311-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/09/what-do-exchange-rates-measure.html
---

[Scott Sumner says](http://www.themoneyillusion.com/?p=27438) that because the ECB lowered interest rates and reduced IOR -- and since the Euro fell on that news -- the ECB (i.e. monetary policy) is capable of producing inflation and that the zero lower bound/liquidity trap is incorrect.



That sure sounds like a coherent theory, but is it the only one? And what does a falling price of a Euro in terms of e.g. dollars mean? This sounds like a perfect opportunity to take on exchange rates with the information transfer model.



I first looked at a naive model where the exchange rate is based on the ratio \[1\] of the supply of each currency and got a not entirely terrible fit (exchange rate data is in orange and the ratio is in blue):


![](<media/what are exchange rates the price of -question-.png>)

However this model only works with the supply of Euros in the numerator! This is weird because it means if the supply of Euros goes up, the dollar price of a Euro also goes up. Or in terms of macro, if the exchange rate (dollar price of a euro) goes up it means the supply of base money Euros increased implying inflation. That would mean (when Sumner reasons from a price change above) that if the exchange rate falls on an ECB announcement (meaning Fed policy can be taken as constant) we should expect a fall in the supply of base Euros and deflation -- _on news of expansionary monetary policy, no less!_



How do we make sense of this? The dollar price of Euro goes up when there are more Euros -- that must mean demand for Euros has gone up. That's the key insight here. Let's start from the basic information transfer model:





where $D_{EU}$ is the demand for Euros, $M0_{EU}$ is the amount of Euro currency in circulation and $P_{EU}$ is the "price" of a Euro (the Platonic ideal price that we'll later compare to another price to determine an exchange rate). We can solve this differential equation to obtain:









We can solve the analogous model for the dollar demand and obtain:





The exchange rate is then the ratio of these prices





where $\alpha$ is a constant fit to the data like $k_{EU}$ and $k_{US}$. This now makes sense of exhange rate price movements -- if the dollar price (exchange rate) of a Euro goes up it means that the price (value) $P_{EU}$ of a Euro has gone up (supply has decreased or demand has increased) or the price (value) of a dollar $P_{US}$ has gone down (supply has increased or demand has decreased).



In addition to making sense, it also fits the data pretty well (with nice Gaussian residuals):


![](<media/what are exchange rates the price of -question- euro m0.png>)

And not just for the Euro -- here is the Yen-Dollar exchange rate:


![](<media/what are exchange rates the price of -question- japan m0.png>)

The other key takeaway from this analysis is that **exchange rate moves are not always relevant to inflation**. Since $X$ is a function of $M0$ \[2\] and moves in $M0$ [do not always lead to inflation](http://informationtransfereconomics.blogspot.com/2014/09/annihilation-and-sterilization.html) (especially in a [liquidity trap/information trap](http://informationtransfereconomics.blogspot.com/2014/06/krugman-keynes-and-liquidity-trap.html)), moves in $X$ do not indicate monetary policy effectiveness or inflation. Long term interest rates will probably fall in the Eurozone, which may help the fiscal situations of several member states, but there does not appear to be any monetary impact from the ECB's announcement.



Another way to say this is that printing money will impact exchange rates, but may not impact inflation if you are in a liquidity trap. One could say that exchange rates and inflation _**decouple**_ in a liquidity trap.



It's also important to note that the fluctuations in the exchange rates are large, so any particular move is unlikely to be very informative ... never reason from a price change.





Footnotes:



\[1\] We could imagine this as a purely exogenous information transfer model where _P = k D/S_ (where P is the price or exchange rate, D is the demand and S is the supply).



\[2\] The other measures of money are also decent models, for example, here are the M2 versions:


![](<media/what are exchange rates the price of -question- euro m2.png>)![](<media/what are exchange rates the price of -question- japan m2.png>)

But [I've shown before](http://informationtransfereconomics.blogspot.com/2014/05/do-monetary-aggregates-measure-money.html) that _log M2 ~ k log M0_ so this doesn't actually add information (we can just re-write the M2 versions of the equations in terms of M0).
