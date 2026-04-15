---
title: "Nick Rowe's model of the money stock"
date: 2014-03-16T20:33:00.000-07:00
updated: 2014-04-05T10:45:10.303-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/03/nick-rowes-model-of-money-stock.html
---

> _Suppose, just suppose, that the central bank does target an exogenously fixed rate of interest, and ignore the Wicksellian indeterminacy this creates, and ignore the fact that this is incompatible with targeting inflation or anything vaguely sensible. That interest rate target is the central bank's supply function, and a change in that interest rate target supply function will cause a change in the stock of money._ 

> _Will it be true that the actual stock of money will always be equal to and determined by the quantity of money demanded at that target rate of interest? ... "no"._

That's from [Nick Rowe's post today](http://worthwhile.typepad.com/worthwhile_canadian_initi/2014/03/the-sense-in-which-the-stock-of-money-is-supply-determined.html). This is basically true if you set up an inverted version of the information transfer model. Previously, I had taken the monetary base as input (exogenous, in economic language), so that: 



rs = r(NGDP, MB)

rl = r(NGDP, M0)

P = P(NGDP, M0)



(That's not a typo, the function r is the same for the long term, say 10-year, rate rl and short run, say 3-month rate rs.) NGDP is exogenous, and as it is set up, P, rs and rl are endogenous.



Rowe sets up a system with an endogenous monetary base, effectively inverting the first two equations above:



MB = M(NGDP, rs)

M0 = M(NGDP, rl)

P = P(NGDP, M0)



with the same function M. Allowing non-ideal information transfer, the actual monetary base should be less than the quantity demanded (the solution to the equations) at the target rate of interest, answering the question at the end of the quotation above. What happens if we insert the effective Fed funds rate (this is approximately equal to [the Fed target rate](http://research.stlouisfed.org/fred2/graph/?g=tae)) for rs and the empirical 10-year rate for rl? Here is the Fed funds rate:



![](<media/ite nick rowes model 1.png>)



Here is the resulting monetary base (including reserves); the model is the solid line, while the actual value of the base is the dashed line:



![](<media/ite nick rowes model 2.png>)



Here is the resulting currency component of the monetary base (excluding reserves); the model is the solid line, while the actual value of the base is the dashed line:



![](<media/ite nick rowes model 3.png>)



It is in this last graph that the actual currency component is smaller than the quantity demanded. However, if we were to fit the model parameters to the short term interest rate, then the previous graph would show that the base including reserves demanded was always less greater than the actual monetary base. In fact, here it is (using the model fit to the short term interest rate to set the parameters):



![](<media/ite nick rowes model 2a.png>)

For fun, here are the plots of the price level fit to these endogenous monetary bases (using the original fit to the long run interest rate):



![](<media/ite nick rowes model 4.png>)![](<media/ite nick rowes model 5.png>)



It works reasonably well for the price level, but does show that an interest rate inflation target is nigh impossible due to the fluctuations.



Update 4/5/2014: the "less than" crossed out above should have been "greater than". H/T Tom Brown.
