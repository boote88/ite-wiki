---
title: "Defining recessions?"
date: 2016-10-02T17:43:00.003-07:00
updated: 2016-10-07T12:43:40.377-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/10/defining-recessions.html
---

I noted [in comments here](http://informationtransfereconomics.blogspot.com/2016/10/thinking-about-equilibrium-and.html) that there is no real definition of a recession. [The NBER "defines"](http://www.nber.org/cycles/recessions_faq.html) the beginnings and ends of recessions for the US ... using multiple indicators and a general heuristics like "a significant decline in activity". Since the discussion of recessions came in the course of talking about equilibrium, it made me think of [this definition of unemployment equilibrium](http://informationtransfereconomics.blogspot.com/2016/06/unemployment-equilibrium.html) I played around with. Does it define when recessions are?



Since it is made of a series of fits to Fermi-Dirac functions ([logistic functions](https://en.wikipedia.org/wiki/Logistic_function)) that have the form






Where the $t_{0}$'s define the transition time and $\tau$ defines the width (slope) of the transition -- larger $\tau$ meaning wider transition. Can the fit parameters be used to determine recessions? Sort of. At least the $t_{0}$'s are associated with the recessions -- in fact, they are almost exactly the middle of recessions post-1985:



![](<media/unemployment equilibrium recession definition.png>)

The gray vertical lines indicate the beginning and end of recessions per NBER. The green rectangles are the region $( t_{0} - \tau, &nbsp;&nbsp;t_{0} + \tau)$. The width $\tau$ doesn't seem to have a relationship with the duration, however. The transition times work for all of the post-war recessions that I fit in that earlier post (I didn't do the 1980s ones because they seem different -- I'd just connect the two red lines with a straight line and treat it as a single recession, but I'm too lazy at this point to re-work the fit):



![](<media/unemployment equilibrium recession definition 2.png>)

Like the post-1985 recessions, the transition time $t_{0}$ still happens during the NBER recession. However, it doesn't appear in the center of those recessions. For reference, this model identifies the center of the recessions as (with the center of NBER recessions afterward and difference in months)

> 1953 (Mid-December) ............ 1953 Dec (+0 m)
>
> 1957 (Late-November) ........... 1957 Dec (+1 m)
> 1960 (Mid-November) ............ 1960 Sep (-2 m)
> 1970 (March 1) ...................... 1970 Jun (+3 m)
> 1974 (Mid-November) ............ 1974 Jul (-4 m)
> 1981 (Early February) ............. 1981 Jun (+4 m)\*\*
> 1991 (Late-January) ................ 1990 Nov (-2 m)
> 2001 (Late-August) ................. 2001 Jul (-1 m)
> 2008 (Mid-October) ................. 2008 Sep (-1 m)

The model here has center of recession times that are on average 1.3 months later (not including the 1980s recessions; including them but considering them only one recession, the average error goes down to 0.7 months later). RMS error is 2.3 months (without 1980s) and 2.6 months (with 1980s).

\*\* Center of both recessions combined

...

**Update 3 October 2016**

Since I'm home with a cold today, I thought I'd overcome my laziness and fit the 1980s recession(s). I've updated the table above. Here are the graphs:

![](<media/unemployment equilibrium -recession definition-.png>)
![](<media/unemployment equilibrium -recession definition- 2.png>)
...

**Update 7 October 2016**

This is getting much more speculative, but I thought I'd add two pieces. First, can we model Obamacare as a positive shock? Second, can we extrapolate a recession from the uptick in unemployment in recent months?

The answers are yes and no, respectively. Here's Obamacare (aka the ACA) as a positive shock (the piece from 2012 to 2016, with transition time in November 2013):

![](<media/unemployment equilibrium -future recession question- 1.png>)
And here is the "prediction", which is completely uncertain:

![](<media/unemployment equilibrium -future recession question- 2.png>)
