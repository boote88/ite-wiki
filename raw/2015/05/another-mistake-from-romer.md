---
title: Another mistake from Romer
date: 2015-05-18T11:58:00.001-07:00
updated: 2015-05-18T11:59:03.040-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/05/another-mistake-from-romer.html
---

I found another mistake in Romer's "proof", but I also got some (wrong-headed) [pushback on the econ job rumors forum](http://www.econjobrumors.com/topic/paul-romer-irate-as-fk) about my take on Paul Romer's mathiness. Here's the comment:

> _Yeah, \[[this post](http://informationtransfereconomics.blogspot.com/2015/05/the-irony-of-paul-romers-mathiness.html)\] is complete garbage. Mathematically, it's an issue of pointwise vs. uniform convergence, plain and simple. Economically, Romer says that Lucas + Moll don't get endogenous growth because of diffusion. Rather, they get endogenous growth because the "knowledge frontier" is already unbounded. Any empirical observations (which necessarily occur at finite T) depend critically on the rate of knowledge arrival. This guy just does not get it._

I think this shows us a bit where economics has gone off the rails with the mathiness. Economics should never refer to uniform vs pointwise convergence. This is a topic from real analysis \[0\]. If uniform vs pointwise convergence matters in economics, _**you're doing it wrong**_.



And it's not even a correct assessment -- it's actually a case of _almost uniform convergence_ (the set of points where the limit doesn't converge uniformly has measure zero, and is in fact exactly the point $\beta = 0$).



An example from physics might help make this a bit clearer. Let's say we have a model of all possible collections of nuclei that decay via $\alpha$ decay with time constant $\tau$ so that the number of your original nuclei left at time t is given by






This function has the essential properties of Lucas and Moll's growth function $g_{\beta}(t)$ where basically $1/\beta$ is now $\tau$.










1.  If the nuclei are stable, they never decay.
2.  Unstable nuclei always eventually decay.



Lucas and Moll (2014) essentially is a model of decaying nuclei and their limit is the second one. They don't care about stable nuclei (economies where nothing happens), they care about something else (economies where everything has already happened \[1\]). Probably why they ignored Romer's comment! I'd ignore it too. And send back a pithy comment.





>  _"Any empirical observations (which necessarily occur at finite T) depend critically on the rate of knowledge arrival."_

That is exactly my point! They also critically depend on finite $\beta$, so why are you taking any limits at all? The whole concept of choosing T only makes sense relative to $\beta$. And the model only exists at finite $\beta$, what ever limit you are taking has to be relative to $\beta$.



This entire argument might have been avoided by a simple $\beta &gt; 0$ statement. But then, we get to Paul Romer's second mistake. He apparently notices that $\beta &gt; 0$. He takes a limit that depends critically on a point he himself says doesn't exist as a point in the space!



His mathy proposition says that $\beta \in (0, \tilde{\beta})$, not $\beta \in [0, \tilde{\beta})$, so the limit $\beta \rightarrow 0$ takes $\beta$ to be arbitrarily small, but not zero. One notation for that is $0^{+}$ and that limit is uniformly convergent. You can exchange the order of limits under this condition:






All of this nonsense could have been avoided by lightening up on the real analysis and not forgetting that we are trying to describe a real-life system!





**Footnotes:**


\[0\] I know. In addition to physics, I have a math degree too. I've been though that punishment.



\[1\] Not sure why they want to do this -- the interesting bit is where $T \sim 1/\beta$. And if this is what Romer is objecting to, why do it with the silly proof and the argument about limits? Just say the economy Lucas and Moll describe doesn't make economic sense -- not that they didn't properly account for the order of limits.
