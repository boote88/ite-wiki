---
title: A desired wealth to income ratio as a dynamic equilibrium
date: 2017-02-02T16:00:00.000-08:00
updated: 2017-02-02T16:22:33.314-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/02/a-desired-wealth-to-income-ratio-as.html
---

Part of stock-flow consistent modeling that doesn't actually have much to do with stock-flow consistency (see [here](http://informationtransfereconomics.blogspot.com/2016/12/stock-flow-consistency-is-tangential-to.html)) is positing that agents have a desired ratio of wealth $W$ to income $I$. Some unknown source with a Mark Thoma- or Scott Sumner-scale following recently linked to that post and that has suddenly made it the second most viewed post on my blog ever. It's not clear whether it was in a positive or negative context (regardless: thanks for the link!), but in any case it reminded me of the wealth to income ratio at a time when I've been looking at several different applications of the [information equilibrium/dynamic equilibrium approach](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html).








Note that the constant would have units of time: \[dollars\]/\[dollars/time\] = \[time\]. You can think of it as a "time horizon". For example a $1/t_{0}$ = 0.05/year (5% growth) represents a time horizon of 20 years. We can solve this differential equation:













[information equilibrium](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html)








making it a special case of [dynamic equilibrium/information equilibrium](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html). So what happens if we try to fit the data ([this](https://fred.stlouisfed.org/series/HNODPI), [this](https://fred.stlouisfed.org/series/TABSHNO), and [this](https://fred.stlouisfed.org/series/TLBSHNO)) to a dynamic equilibrium plus a series of shocks? We don't need to do the entropy minimization process since we already know the slope should be zero. The result involves a lot of shocks:


![](<media/dynamic equilibrium wealth to income ratio.png>)
![](<media/dynamic equilibrium wealth to income ratio 2.png>)

What is interesting is if we overlay the positive and negative [shocks to the stock market](http://informationtransfereconomics.blogspot.com/2017/01/what-about-s-500.html) (SP500 shocks, blue) and the positive and negative [shocks to housing prices](http://informationtransfereconomics.blogspot.com/2017/01/housing-prices-and-dynamic-equilibrium.html) (Case-Shiller index shocks, orange), a general picture emerges (positive shocks come up from the bottom, negative down from the top):



![](<media/dynamic equilibrium wealth to income ratio 3.png>)

If there is a desired wealth to income ratio, it tends to be afloat on a sea of markets. The decline from the 1960s to the 70s is associated with the general stagnation of the stock market. The boom and bust of the late 90s and early 2000s is the dot-com bubble. And finally, the boom and bust of the later half of the '00s is the boom and bust of the housing bubble (and subsequent financial crash). The 2013 rise in W/I might be associated with a rise in Case-Shiller index relative to the dynamic equilibrium around the same time. There is also a hint of a stock market rise around the same time. It could be a bit of both. I didn't think either of these were significant enough in the individual time series to warrant inclusion, but the additional evidence from the wealth to income ratio makes me re-think that.



However, the data appears to show that the causal mechanism is that fluctuations in asset markets (housing, stocks) cause the wealth to income ratio to change. There does not appear to be a "restorative force" keeping it at a specific level (a desired W/I ratio).



Additionally, this is written entirely in terms of information equilibrium rather than as a stock-flow consistent model. The only time I used any accounting is when I calculated net wealth to be assets minus liabilities. However, even this isn't necessary as the same story can be told using assets instead of wealth (A/I):



![](<media/dynamic equilibrium asset to income ratio -not wealth-.png>)

I am sure I will get comments from the SFC club that say the data series I am using is wrong (it includes non-profit organizations, and income is just disposable income) or that income includes revaluations of assets (note that I actually wrote it out that way first, but it reduces to the form above). Feel free to point me to the correct data sources -- but at least see how well the "correct" W/I ratio corresponds to the W/I ratio I show above first.



Aren't we looking for pluralism, anyway? Isn't it interesting you can analyze the macro effects and the wealth to income ratio with a completely different approach?

...

**Update**

I wanted to note that the [information equilibrium condition](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html) is less restrictive than the wealth-to-income ratio equation (first equation at the top of this post). The former effectively allows any function $I(t)$:

$$<br />
W(t) = c I(t)<br />
$$

where

$$<br />
I(t) = \frac{W_{0}}{t_{0}} e^{t/t_{0}}<br />
$$

is a special case.
