---
title: "The irony of Paul Romer's mathiness"
date: 2015-05-16T17:36:00.000-07:00
updated: 2017-04-09T17:05:03.233-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/05/the-irony-of-paul-romers-mathiness.html
---

![From Paul Romer's extended mathiness appendix [pdf].](media/mathiness.png)



I apparently [completely misunderstood](http://informationtransfereconomics.blogspot.com/2015/05/mathiness-and-solow-production-function.html) Paul Romer's comment about "mathiness". My original interpretation was that Romer was upset about obfuscating political assumptions that aren't substantiated empirically by using fancy math. But then I started reading some of his appendix (pictured above). I was completely wrong.



Paul Romer is upset about the _technical rigor_ of those political assumptions. If the function Lucas and Moll (2014) used allowed you to exchange the order of the limits everything apparently would have been fine! Unfortunately, it turns out that Romer's takedown of Lucas and Moll is the true mathiness.



Lucas and Moll (LM) put forward some economic growth function $g_{\beta}(t)$ where $\beta$ is the "rate of innovation". LM then tell us:






which is independent of $\beta$. Fine. But Romer objects! He shows (somewhere -- couldn't find the comment on LM he was referring to on his website)







Oh noes! We have a case where the limit depends on the order you take it:



$$<br />
\lim_{\beta \rightarrow 0} \; \lim_{T \rightarrow \infty} \; g_{\beta}(T) \neq \lim_{T \rightarrow \infty} \; \lim_{\beta \rightarrow 0} &nbsp;\; g_{\beta}(T)<br />
$$

He even goes on to state this in a mathy "proposition" form (pictured above).


Now if $g$ represented the average polarization of an Ising model, this might be interesting (even lending itself to the possibility of a topological solution). But infinity is not readily encountered in a real economy and the situation being described is the idea observing the economy at a date $T$ when the typical time until "knowledge arrives" (_I know!_) is $1/\beta$. What do these two limits mean in real life?



1.  You are observing an economy in which knowledge never arrives ($\beta \rightarrow 0$ first)
2.  You are observing an economy after which the knowledge has arrived ($T \rightarrow \infty$ first)



The second one is the sensible limit of Lucas and Moll (2014).



Now what does the time of observation $T$ mean in real life? I am assuming economists don't really pay attention to the big bang or eventual heat death of the universe and that an economy can happen at any time in the lifetime of the universe. That is to say -- economics has a [time translation invariance](http://en.wikipedia.org/wiki/Time-invariant_system) where you could relabel the year 1991 as 10191 and it wouldn't make a bit of difference. Relative times matter, but not absolute times. Which means that I could shift $T$ to any finite, but large value arbitrarily ... in particular I can choose $T \gg 1/\beta$. I can't choose $\beta$ as it represents a real thing: the time between two "knowledge" events. 



That is to say there is an existing scale in the model $1/\beta$, the time difference between "knowledge" events. There is no such scale for $T$ unless it is $1/\beta$ and therefore the only sensible limit is:



$$<br />
T \gg 1/\beta<br />
$$

which is situation 2 above.


Romer is turns out to be ironically wrong because he uses too mathematical a description in a physical theory. You can discard the second first limit as a mathematical curiosity that doesn't represent a real life economy.



I don't have any particular fondness for Lucas, but I think in his zeal to take him down Romer falls for the exact mathiness he purports to dislike!

**Update 9 April 2017**

[I later discussed this more generally](http://informationtransfereconomics.blogspot.com/2015/11/on-limits.html). Economists do not appear to understand the physical meaning behind limits, using them only as mathematical procedures.
