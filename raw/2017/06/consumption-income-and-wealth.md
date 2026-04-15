---
title: "Consumption, income, and wealth"
date: 2017-06-13T11:00:00.000-07:00
updated: 2017-06-13T15:35:03.757-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/06/consumption-income-and-wealth.html
---

John Handley has started up a new updated blog, and [the most recent post](http://jwhandley.blogspot.com/2017/06/modelling-consumption.html) asks an interesting question (in a way that should be lauded for both its use of data and making the code available): if disposable income predicts consumption so well (i.e. the traditional Keynesian consumption function), why did anyone start using the Euler equation with its "almost comical level of inaccuracy"? While we wait for the optimal answer to that question from [Beatrice Cherrier](https://twitter.com/Undercoverhist), my intuition says the answer is "microfoundations". John asked me to verify his regressions, which I did; the model he considered has the added benefit of being an information equilibrium model so I am writing it down here.



The basic Keynesian consumption function is essentially a linear model



_PCE_ \= _a DPI + c_



where PCE is personal consumption (FRED [PCEC](https://fred.stlouisfed.org/series/PCEC)) and DPI is disposable income (FRED [DPI](https://fred.stlouisfed.org/series/DPI)). However John discovered an excellent relationship between PCE, DPI and total net worth (FRED [TNWBSHNO](https://fred.stlouisfed.org/series/TNWBSHNO)) which I will call TNW for short:



log _PCE_ \= _a_ log _DPI_ + _b_ log _TNW_ \+ _c_



This has the form of [an information equilibrium relationship](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html) (as well as a Cobb-Douglas production function where income and wealth are both "factors of production" for consumption):



_PCE_ ⇄ _DPI_

_PCE_ ⇄ _TNW_



with information transfer indices _a_ and _b_. It also reduces to the basic Keynesian model in the limit where changes in _TNW_ and _DPI_ are small (in percentage terms). The model works pretty well \[1\]:


![](<media/IE consumption -Handley- 1.png>)
![](<media/IE consumption -Handley- 2a.png>)

We find _a_ = 0.82, _b_ = 0.18, and _c_ = -0.47. This result has several different implications. First, as John's says via Twitter, it means "consumers are way more hand to mouth than typical model\[s\] suggest". It also suggests that changes to income have a bigger impact on consumption than equivalent relative changes in wealth. Note that _a_ ~ 1 means that the permanent income hypothesis isn't a good approximation (which requires _a_ << 1) in line with [previous results using information equilibrium](http://informationtransfereconomics.blogspot.com/2017/01/consumption-income-and-pih.html) to describe lifetime income and shocks to income. Additionally, including different methods \[1\] as well as John's results, the result nearly always gave _a + b_ ≈ 1, i.e. constant returns to scale.



Overall, this is a pretty good model of consumption in terms of income and wealth.


...

**Update + 3 hours**

One thing to note is that the empirical finding that _a + b_ ≈ 1 implies that there is a constant wealth-to-income ratio (for the same reasons the labor share is constant in the Solow model). This lends credence to the frequent stock-flow consistent model assumption of a constant wealth-to-income ratio ([possibly subjected to stochastic shocks](http://informationtransfereconomics.blogspot.com/2017/02/a-desired-wealth-to-income-ratio-as.html) per the dynamic equilibrium model).

...

**Update + 4.5 hours**

Despite lauding John Handley above for making his code available, I forgot to upload the _Mathematica_ code for the model [to the repository](http://informationtransfereconomics.blogspot.com/2017/02/information-equilibrium-code.html) (information equilibrium). This has been rectified.




**Footnotes:**


\[1\] I tried multiple different ways of estimating the parameters and all give approximately comparable results (and comparable to John's results as well).



![](<media/IE consumption -Handley- 3.png>)![](<media/IE consumption -Handley- 4.png>)
