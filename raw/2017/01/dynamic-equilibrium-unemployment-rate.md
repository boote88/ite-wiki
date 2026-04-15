---
title: "Dynamic equilibrium: unemployment rate"
date: 2017-01-11T17:40:00.002-08:00
updated: 2017-01-22T10:15:35.340-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-unemployment-rate.html
---

In last night's [post](http://informationtransfereconomics.blogspot.com/2017/01/a-dynamic-equilibrium-in-jolts-data.html), I looked at the ratio of the level of unemployment $U$ to job vacancies $V$ in terms of the "naive dynamic equilibrium" model. There was a slight change from [the original version](http://informationtransfereconomics.blogspot.com/2016/10/dynamic-unemployment-equilibrium-and.html) describing the unemployment rate $u$ where instead of taking the dynamic equilibrium to be:










This latter form is more interesting (to me) because it can be directly related to a simple information equilibrium model $V \rightleftarrows U$ (vacancies in information equilibrium with unemployment) as shown in last night's post. Can we unify these two approaches so that both use the logarithmic form? Yes, it turns out it works just fine. Because $u$ doesn't have a high dynamic range, $\log u(t)$ is directly related via linear transform to $u(t)$ such that basically we end up with a different constant.



If we have an information equilibrium relationship $U \rightleftarrows L$ where $L$ is the civilian labor force such that $u = U/L$, and we posit a dynamic equilibrium:






Then we can apply the same procedure as [documented here](http://informationtransfereconomics.blogspot.com/2017/01/a-dynamic-equilibrium-in-jolts-data.html) and come up with a better version of the dynamic equilibrium model of the unemployment rate data:



![](<media/unemployment ratio -log version-.png>)
![](<media/unemployment ratio -log version- derivative.png>)

\[**Update:** added derivative graph.\] The transition points are at 1991.0, 2001.7, 2008.8, and 2014.3 (the first three are the recessions, and the last one is the "[Obamacare boom](http://informationtransfereconomics.blogspot.com/2016/10/defining-recessions.html)"). The improvements are mostly near the turnaround points (peaks and valleys). Additionally, the recent slowing in the decrease in the unemployment rate no longer looks as much like [the leading edge of  a future recession](http://informationtransfereconomics.blogspot.com/2017/01/an-updated-unemployment-rate-projection.html) (the recent data is consistent with the normal flattening out that is discussed [here](http://informationtransfereconomics.blogspot.com/2017/01/a-dynamic-equilibrium-in-jolts-data.html)).



I just wanted to repeat the calculation I did in the previous post for the unemployment rate. We have an information equilibrium relationship $U \rightleftarrows L$ with a constant IT index $k$ so that:






therefore if the total number of people in the labor force grows at a constant rate $r$, i.e. $L\sim e^{rt}$ (with, say, $r$ being population growth)






which is a constant (and $u \equiv U/L$).

...

**Update +4 hours:**


I went back and added the recessions through the 1960s. Because the logarithm of the unemployment rate is much better behaved, I was able to fit the entire series from 1960 to the present with a single function (a sum of 7 logistic functions) instead of the piecewise method I had used for the non-logarithmic version that fit the pre-1980s, the 1980s, and the post-1980s separately. Here is the result:



![](<media/unemployment ratio -log version- 1960s.png>)
![](<media/unemployment ratio -log version- 1960s derivative.png>)

The recession years are: 1970.3, 1974.8, 1981.1, 1991.1, 2001.7, and 2008.8 ‒ plus the positive ACA shock in 2014.4. And except for one major difference, the model is basically within ± 0.2 percentage points (20 basis points). That major difference is the first half of the 1980s when Volcker was experimenting on the economy ...



![](<media/unemployment ratio -log version- 1960s error plot.png>)
It's possible that we need to resolve what may actually be multiple shocks in the early 1980s.

**Update 14 January 2017**

Later posts examine [the EU](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-unemployment-equilibrium.html) and [Japan](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-unemployment-equilibrium-japan.html). First the EU:

![](<media/unemployment ratio -log version- EU 2.png>)
![](<media/unemployment ratio -log version- EU 3.png>)
The recession centers are at 2003.1, 2009.1, and 2012.2. And for Japan:



![](<media/unemployment ratio -log version- japan 1.png>)
![](<media/unemployment ratio -log version- japan 2.png>)




**Update 17 January 2017**



![](<media/employment level 1960s.png>)
**Update 22 January 2017**

[the model for the UK](http://informationtransfereconomics.blogspot.com/2017/01/the-economy-of-united-kingdom.html)

![](<media/uk unemployment dynamic equilibrium.png>)![](<media/uk unemployment dynamic equilibrium 2.png>)
