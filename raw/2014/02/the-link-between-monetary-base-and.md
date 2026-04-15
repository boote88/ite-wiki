---
title: The link between the monetary base and interest rates
date: 2014-02-04T20:52:00.000-08:00
updated: 2014-03-21T11:05:54.089-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/02/the-link-between-monetary-base-and.html
---

When I [made the discovery](http://informationtransfereconomics.blogspot.com/2014/02/the-role-of-central-bank-reserves-in.html) (or, corrected the error) that only the currency component of the monetary base ("M0", rather than MB) was used to determine the price level I was initially pretty excited: it improved the fit to price level data substantially after 2008. Lurking unmentioned in the background, however, was a terrible blow. Using M0 meant that one of the most interesting aspects of the information transfer model would have to be scrapped: the path of the economy, interest rates and the price level surface could no longer be [combined into a single plot in _(MB, NGDP)_ space](http://informationtransfereconomics.blogspot.com/2013/09/the-liquidity-trap-and-information-trap.html) that enabled one-plot economic situational awareness.



In less than 24 hours, the sadness has been replaced by excitement, and I feel like the failure has lead to new understanding. Let's start with the new 3D graph of the price level surface using just the currency component of the base:



![](<media/basic us price level m0 1.png>)

We can see that the US economy is on the good side of the information trap criterion (dark line where _∂P/∂MB = 0_) as opposed to having crossed it (see e.g. [here](http://informationtransfereconomics.blogspot.com/2013/07/dotting-is-and-crossing-ts.html), which leads to [deflationary monetary expansion](http://informationtransfereconomics.blogspot.com/2013/12/deflationary-monetary-expansion.html)). It is still close enough to the line that liquidity trap-like conditions are present. This graph forms the basis of the _(MB, NGDP)_\-space diagram, but first we need to address interest rates.



Previously, the monetary base including reserves (i.e. the "QE" component) was used to fit short term interest rates rather well (for several countries). "M0" doesn't work as well with the 3-month rate. What could be the difference? [Scott Sumner](http://www.themoneyillusion.com/?p=10888) frequently likes to point out that things like QE boosting central bank reserves are seen as temporary, whereas printing currency would be seen as more permanent. This gave me an idea: what if the currency component of the base controlled long term interest rates while currency + reserves controlled short term rates? Let's say we have two markets _rl:NGDP→M0_ and _rs:NGDP→MB_ with the same information transfer index (κ) where _rl_ is the long run interest rate (10 year treasury rate) and _rs_ is the short run interest rate (3 month rate). I fit κ to the 10 year treasury rate _rl:NGDP→M0_ and then looked at how well the MB data fit the 3-month rate in the same function. **The result was pretty amazing:**



![](<media/basic us price level m0 2.png>)
**both**  _log r = c log  (1/κ) (NGDP/Mx)__κ__c__c__Mx_
_(MB, NGDP)__P(M0, NGDP)__r(M0, NGDP)__M__∂P/∂MB = 0_
![](<media/basic us price level m0 3.png>)
