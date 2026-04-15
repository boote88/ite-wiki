---
title: "Unemployment equilibrium?"
date: 2016-06-11T20:51:00.004-07:00
updated: 2016-06-18T16:22:13.745-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/06/unemployment-equilibrium.html
---

Earlier today, Roger Farmer [tweeted](https://twitter.com/farmerrf/status/741753579535372288) a [post of his from a couple years ago](http://www.rogerfarmer.com/rogerfarmerblog/2014/02/faust-keynes-and-dsge-approach-to.html) that had a line that struck me as odd. It's just an example of something I've read many, many times in economics from papers to the blogs so I'm not singling out Farmer for this. The line was this:

> _For example, I have constructed [a DSGE model](http://rogerfarmer.com/NewWeb/PdfFiles/fa-con-cra.pdf) where 25% unemployment is an equilibrium._

There are other papers that refer to an unemployment equilibrium. However, is there any sense in which there is an equilibrium in unemployment? Take a look at the data:



![](<media/unemployment equilibrium 1.png>)



Which level would you choose to be the equilibrium? It looks to me like unemployment has never stayed at any particular level for more than a year or two (within error). That 25% unemployment equilibrium (or 5%, or whatever level you can construct with a DSGE model) does not seem to describe an actual macroeconomy.



There is another type of equilibrium in economics; many economies generally grow, sometimes at a roughly constant rate. That exponential growth path can be considered an equilibrium. Maybe we can consider employment growth (and thus unemployment reduction) as an equilibrium path? This is an idea [I'd had awhile ago](http://informationtransfereconomics.blogspot.com/2014/07/remarkable-recovery-regularity-and.html) when I noticed that recoveries had a remarkably regular slope. I've made it a bit more scientific for this post.



Imagine setting up a series of diagonal lines. The regions between those diagonal lines can be considered a bin -- if the unemployment rate falls in that bin, it adds to a histogram. You can visualize it like this (I did this by hand, so it doesn't match perfectly):



![](<media/unemployment equilibrium 4a.png>)



The question is: is there a slope of those lines (_α_) such that the histogram is very spiky (most points fall in a few bins)? Technically, I am minimizing the entropy of the distribution over _α_. It turns out there is:



![](<media/unemployment equilibrium 2.png>)



The value is _α_ = 0.49 (i.e. a 0.49 percentage point decrease in unemployment per year, or a 0.04 percentage point decline per month). Here are the histogram and the unemployment rate shown with lines at that slope shown:



![](<media/unemployment equilibrium 3.png>)
![](<media/unemployment equilibrium 4.png>)



It matches the best with the 1991 recession and the 2001 recession recoveries. Once we've established this slope, we can add the function _f(t) ~ α t_ to the unemployment rate; it causes the recoveries to become horizontal lines (that in the normal data would be falling at the rate _\-|α|_ per year) and the recessions transitions to become more vertical:



![](<media/unemployment equilibrium 5.png>)



I fit a series of step functions to this data (red) leaving out the 1980s (the Volcker recessions, which seem different -- both in the original data and in this view). Now we can transform the data and the red functions back to the original unemployment view:



![](<media/unemployment equilibrium 6.png>)



I wanted to note that pre-1980 recessions seem to have a bit larger initial overshoot relative to the post-1980 Great Moderation recessions.



So ... can we say the unemployment rate decline at 0.49 %/year is the unemployment equilibrium? Possibly -- at least if the unemployment rate is always large enough to handle it. A decline at 0.49 %/y couldn't be held up for more than 10 years at the current unemployment rate.



In any case, this is a definition of an unemployment equilibrium that makes sense to me.

...

**Update 18 June 2016**

Here's [Roger Farmer with his take](http://www.rogerfarmer.com/rogerfarmerblog/2016/6/18/forecasting-that-the-unemployment-rate-will-be-constant-is-a-bad-idea): unemployment has two "regimes": increasing and decreasing. This is largely similar to what I've said above, except I emphasized the decreasing regime because it tends to hold for longer periods of time.
