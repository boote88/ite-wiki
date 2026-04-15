---
title: "When is an intertemporal budget constraint a true budget constraint?"
date: 2015-10-15T20:00:00.000-07:00
updated: 2015-10-15T20:00:05.429-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/10/when-is-intertemporal-budget-constraint.html
---

![](<media/money3d a.png>)

David Glasner cautioned me about the use of an intertemporal budget constraint (since it is based on expectations that could be thwarted) in my emergent representative agent argument (that parallels Gary Becker's argument that even irrational agents can behave rationally). If you have no idea what I am talking about, you should start [here](http://informationtransfereconomics.blogspot.com/2015/10/gary-beckers-emergent-rational-agents.html). At that link, I said I would address this issue in a future post -- this is that post.



The question is whether we can pretend the intertemporal budget constraint is a true budget constraint analogous to a single period budget constraint for the purpose of constraining the (intertemporal) opportunity set (as Becker puts it). I called the opportunity set the simplex. The issue is that recessions happen and output falls below its expected value (plans are thwarted). That means that expected value isn't a true constraint (actual output is much less) and therefore the most likely state of the economy might not:

-   Manifest consumption smoothing
-   Saturate the intertemporal budget constraint
-   Have downward sloping demand curves
-   (Approximately) maximize utility

The crux of the argument showing these hold (if we ignore recessions) with random consumption is that the most likely point of a high-dimensional simplex is on its surface, rather than in the interior. The downward sloping demand curves hold as long as the centroid of the simplex isn't close to any particular axis.



Let's take the opportunity set defined by the intertemporal budget constraint _Σ ci ≤ M_ (see the picture at the top of this post). For _d_ dimensions (time periods) we have



_Σ ci ~ M d/(d + 1)_


If _d_ >> 1, then we have _Σ ci ~ M_ and the above properties hold: we have emergent rational agents.



What happens if we introduce recessions? Let's take a set of {_ci_} of size _n_ to be zero: all plans are thwarted in those periods and there is no income ... a 100% recession. Note that for even a bad recession, you're really looking at 20%, not 100%, so this will be a conservative calculation. We can show



_Σ ci ~ M (d - n)/(d + n + 1)_


However, if _d_ \>> _n_ and _d_ \>> 1, we still recover _Σ ci ~ M_. In fact, we still recover all of the properties listed above (if _d_ \>> _n_, then the centroid isn't close to a typical axis and you have downward sloping demand curves almost always). Basically, as long as the economy isn't in a recession most of the time, the intertemporal budget constraint can be treated as an ordinary budget constraint.



Note that the properties hold even if the consumption sets are of different size (i.e. there is economic growth) as long as there is no _cj_ \>> _ck_ for most _k_ (in which case _Σ ci ~ cj_). That case is a lopsided simplex (the opportunity set would be more like a spike along the dimension _j_).  Can growth make our simplex lopsided? The [Euler equation](http://informationtransfereconomics.blogspot.com/2015/06/the-euler-equation-as-maximum-entropy.html) says that successive consumption periods are related by the rate of interest  and we have:



_ci ~ β (1 + R) cj_


This means that the rate of interest can't be too large. Large here though is a bit extraordinary; we'd need



_β c0 (1 + R)^d_ _c0 (1 + R)^(d - 1)_



_β (1 + R)__1_




So the final takeaway is that we **can** treat the intertemporal budget constraint like a true budget constraint in order to demonstrate emergent rationality from random behavior. The caveats are:



-   The economy is not in a recession in most time periods
-   Consumption isn't concentrated in a few time periods



It is true that when you look at time periods near recessions, things are more interesting. However that is the point of [non-ideal information transfer](http://informationtransfereconomics.blogspot.com/2015/03/non-ideal-information-transfer-tail.html). In the [information equilibrium model](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html), information equilibrium is taken to hold most (but only most) of the time.
