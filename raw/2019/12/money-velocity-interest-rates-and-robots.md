---
title: "Money velocity, interest rates, and ... robots?"
date: 2019-12-07T14:33:00.001-08:00
updated: 2019-12-10T18:09:38.361-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2019/12/money-velocity-interest-rates-and-robots.html
---

I'd been ruminating on a question [from commenter Anti](https://informationtransfereconomics.blogspot.com/2019/12/information-transfer-economics-year-in.html?showComment=1575427392465#c7277674658285253476) on my end of the year wrap-up post:

> _I can't get past the idea that monetarism is legitimate, but you seem to have a point about women entering the workforce. How likely is it that such demographic changes change money velocity and that central banks seem to take a long time realizing such changes occur? Perhaps the surge in working women increased velocity in the 70s, making it easier to spur inflation, and we've seen the trend reverse since._

As a [recovering monetary model-curious](https://informationtransfereconomics.blogspot.com/2018/01/losing-my-vestigial-monetarism.html) person myself, and having looked at the correlations between money velocity and interest rates (like [here for MZM](https://informationtransfereconomics.blogspot.com/2015/09/an-mzm-quantity-theory.html), or money with zero maturity), I can agree that there is probably macro-relevant information in those relationships. In fact if you look at a long run interest rate series (like Moody's AAA corporate rate, which tracks the 10-year rate quite closely), it appears that money velocity and interest rates are basically measures of the same underlying thing \[click to enlarge\]:


![](<media/DIEM velocity and interest rates.png>)

That [dynamic information equilibrium model](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3094757) (DIEM) for the AAA rate was [the subject of a blog post from last year](https://informationtransfereconomics.blogspot.com/2018/06/rethinking-interest-rates.html), and true to the [information equilibrium relationship between rates and MZM velocity](https://informationtransfereconomics.blogspot.com/2015/09/an-mzm-quantity-theory.html), velocity is well-described by a log-linear transformation of the rate model with different non-equilibrium shock parameters.



And if you look closely at those shocks, you can see that a) the shock to interest rates comes well before velocity, and b) the shock to interest rates is actually earlier than the demographic shock to the level of women in the labor force (which is closer to the velocity shock).



Did rising interest rates cause the demographic shock and subsequent inflation ... and everything else? It's kind of a neo-Fisherite view that was the rage in the econoblogosphere a couple years ago. But let's look at the causality in terms of an economic seismogram \[click to enlarge\]:


![](<media/dynamic equilibrium history -women- book diagram -black and white- VIETNAM WAR plus VELOCITY.png>)

First, as a side note, this picture makes [the view that spending on the Vietnam war was a factor on interest rates](https://informationtransfereconomics.blogspot.com/2019/08/the-phillips-curve-and-narrative.html) and the Great Inflation look even sillier — the shock to interest rates begins in the late 50s or early 60s ... well before the acceleration in the war.



But does this cause problems for the view that demographics (more specifically, labor force size) are a controlling factor in inflation? Did the rising AAA rate cause velocity to increase, which then caused women to enter the workforce and subsequently inflation to rise?



The issue with this view of the causality between monetary measures and inflation comes down to some of the same problems with the Vietnam war view — specifically:



-   Inflation reaches its peak about 3.5 years after Civilian Labor Force (CLF) growth does, and when CLF declines in the Great Recession, inflation reaches its nadir (“lowflation”) about 3.5 years later in 2013.
-   Those two changes are of comparable magnitude — the smaller CLF decline in the Great Recession results in a commensurately smaller decline in the price level.
-   There is no visible shock to the velocity of MZM or AAA interest rates in the opposite direction ~ 12.5 or 6.5 years before the lowflation shock for AAA and MZM, respectively. These would have to be in June of 2000 and June of 2006 (again, for AAA and MZM, respectively). In fact, at those moments those metrics are at relative highs compared to the DIEM path.

As I talk about both in my post [on Granger causality and economic seismograms](https://informationtransfereconomics.blogspot.com/2018/11/i-dont-trust-granger-causality.html) and [in my book](https://www.amazon.com/dp/B07T8T9G93), due to the extremely limited nature of macroeconomic data (both in time series as well as in the number of macro-relevant events) we have to be extremely careful about claiming causality. The two shocks to the labor force are of different sizes and in opposite directions — which matches up with the two shocks of different sizes in opposite directions to inflation **_with almost exactly the same delay_**. 



I step on the accelerator and the car speeds up in the next couple seconds; I pull my foot off and it slows down over the next couple seconds. This is the situation we like to see in terms of causality. We don't want "long and variable lags" as Milton Friedman put it — that's just scientific nonsense. If I step on a pedal with the car accelerating a second later, it's hard to justify causality when I let off that pedal and the car accelerates more a few minutes later or worse ... does nothing.



That's the case we have with interest rates and velocity. That does not mean the shocks are unrelated to inflation — lowflation could have been caused by some other factor _X_. However, we'd then have the simple causal model with fixed lag _dt_ between CLF and CPI = _a_ log CLF(_t+dt_) + _b_  compared to a model where CPI = _f_(AAA, _X_) where we neither know what _X_ is nor have any other non-equilibrium data with shocks to figure it out. Occam comes to our rescue!



That's one of the major things I tied to get a handle on in my book — causality. Causality is hard, especially in time series \[1\]. I made sure that I wasn't just relying on a single shock (any two DIEMs with a single shock of comparable width can be transformed into each other), and frequently went to other historical data to make sure any claims I was making bore out. For example, did you know that male paper authors started citing themselves much more in the years after women started working in greater numbers?



...



So why do we have this shock to monetary observables in the 50s and 60s? What is it about?



My guess is that it's about something entirely different: [capital stock](https://fred.stlouisfed.org/series/RKNANPUSA666NRUG). There is a surge in capital stock around the same time period as the surge in interest rates. Post-war industrial automation resulted in a lot of investment in lots of new equipment to manufacture consumer goods — including the first robots. As I show on the economic seismogram, GMs first robot (that would show up on the _Tonight Show_ a couple years later) is right at the leading edge of that shock to corporate AAA interest rates.



That's just my guess — but it's where my intuition would take me.



...

**Addendum 10 December 2019**


Another interesting thing we can add to this timeline are the shocks to the S&P 500 (treated as one extended shock) in the 60s and 70s:



![](<media/dynamic equilibrium history -women- book diagram -black and white- SP500 plus VELOCITY.png>)

Interest rates and velocity go up, and the S&P 500 comes down ([link to more on the S&P 500 shocks](https://informationtransfereconomics.blogspot.com/2017/01/what-about-s-500.html)).



...



**Footnotes:**



\[1\] This is not a serious statement, but rather a play on "Prediction is hard, especially about the future." This being the internet, someone almost certainly would have read that straight.
