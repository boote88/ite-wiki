---
title: Stock flow accounting with calculus
date: 2016-06-20T11:00:00.000-07:00
updated: 2016-06-20T13:06:00.332-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/06/stock-flow-accounting-with-calculus.html
---

Commenter [Peiya took issue](http://informationtransfereconomics.blogspot.com/2016/06/what-does-it-mean-when-we-say-money.html?showComment=1466374799851#c3738769931635698916) with my comments on stock-flow analysis in the previous post. This post is mostly a response to point (3) that needed a bit more space and mathjax to be properly addressed.








First, let's say $S(t-\Delta t) = 0$ (you're starting from zero), then this equation asserts $S(t) = F(t)$, i..e stock is equal to a flow. This doesn't make sense unit-wise (a flow represents a change in something and therefore has to happen over a period of time, hence there is a time scale associated with the right hand side, but not the left). Per Peiya, $F(t)$ is defined on an interval $[t, t + \Delta t)$, this allows us to define a function $\phi$ (assuming $F \in C^{2}$ except on a countable subset) with the same support such that






Thus we can actually see that $F$ is really a stock variable made from a change in stock over some time scale. Assuming a short interval where $\phi$ is approximately constant, we can see the time scale $\Delta t$ pop out:






So how do we treat stock-flow analysis in a way that is consistent with mathematics? Let's start from $t = 0$ in that first equation. We have (taking a constant revaluation $\alpha$ per time period for simplicity, but can be handled in the general case as long as $\alpha$ isn't pathological)



















we obtain (assuming $S \in C^{2}$ except on a countable subset)



$$<br />
S(t) = \int_{0}^{t} dt'&nbsp;\tilde{\phi}&nbsp;(t') \equiv \Phi (t) - \Phi (0)<br />
$$


We're back to the case where the initial stock was zero. Essentially a change in stock over a time scale ($t$) is equivalent to a flow, and everything I said about scales and metrics and free parameters in [this post](http://informationtransfereconomics.blogspot.com/2016/06/what-does-it-mean-when-we-say-money.html) follows.



I do not understand the resistance to the idea that calculus can handle accounting. There are no definitions of stocks, flows, time intervals or accounting rules that are logically consistent that cannot be represented where a stock is an integral of a flow over a time scale. Attempts to do so just introduce logical inconsistencies (like stocks being equal to flows above).
