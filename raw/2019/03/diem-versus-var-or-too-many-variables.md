---
title: "DIEM versus VAR or: Too Many Variables Spoil the Broth"
date: 2019-03-01T14:30:00.000-08:00
updated: 2019-03-01T14:30:02.255-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2019/03/diem-versus-var-or-too-many-variables.html
---

Sorry I haven't been updating my blog as frequently lately — with only 2 posts in February and 3 in January,  I'm well below my previous low of 7 posts in April of 2014 (vacation + business trip) and September of 2018 (prepping for the ["Outside the Box" workshop](https://informationtransfereconomics.blogspot.com/2018/10/outside-box-workshop.html)). This time, it's due to being massively busy at my real job and [devoting most of my spare time to my forthcoming book](http://www.arandomphysicist.com/2019/02/a-workers-history-update-february-2019.html). There's a bit of being bored with comparing the latest data with my forecasts in there as well — a topic that accounts for a sizable fraction of posts for each month.



This is one of those posts, but it's a more interesting one because we get to close out [a head-to-head comparison between](https://informationtransfereconomics.blogspot.com/2018/04/comparing-my-forecasts-to-vars.html) a dynamic information equilibrium model (DIEM, [see my paper here](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3094757)) and a vector autoregression (VAR) from the Minneapolis Fed — originally requested by @unlearningecon on Twitter. The data being forecast is real GDP growth data for the US (e.g. [here](https://fred.stlouisfed.org/series/A191RO1Q156NBEA)). While the data is consistent with both forecasts, the DIEM had considerably tighter confidence as well as a bias consistent with zero while the MF VAR was biased low:



![](<media/MF VAR vs DIEM.png>)

Note that the DIEM unemployment forecast [already significantly outperformed the MF VAR](https://informationtransfereconomics.blogspot.com/2018/08/validating-forecasts-unemployment-rate.html) under the same metrics (tighter confidence, much lower bias).



The thing is that a VAR model is pretty agnostic — it's basically a regression. Really, the only thing that would make the error larger than the DIEM model would be which variables you decide to include in the VAR. In particular, including too many irrelevant variables effectively adds noise and reduces your confidence. Consider a hypothetical scenario: if you think interest rates affect RGDP growth — but in real life they don't — your VAR is going to have a larger error due to adding in irrelevant interest rates.



To bring this back out to a more general discussion, I think this is a big problem with a lot of macro models. There are a lot of assumptions about how an economy works that go into the choice of the variables used in the model. You might think that irrelevant variables would usually get zero coefficients in a regression if there's no dependence on that variable, but this isn't true for an over-determined system with correlated data. In that situation, weird things like the order of variables in the regression algorithm can become important. There are of course ways to test for these things (such as regressing on subsets of your variables), but I'd be surprised to hear that mainstream macro modelers drop e.g. interest rates from their models. A lot of non-mainstream economists seem to be as wedded to their ideas of which variables are important, making this a problem across the board.



I've mentioned before that I think this might be one useful byproduct of using machine learning in macro modeling (e.g. [here](https://informationtransfereconomics.blogspot.com/2018/05/macro-criticism-but-not-that-kind.html)) since one thing that machine learning tends to do [is destroy irrelevant information](https://informationtransfereconomics.blogspot.com/2017/10/the-price-mechanism-and-information.html). However, [curation of your data sets is an issue for machine learning as well](https://informationtransfereconomics.blogspot.com/2015/09/machine-learning-and-implicit-theorizing.html), so it's not a panacea. It's still a judgment call, and really the only thing we have to go on is the data.
