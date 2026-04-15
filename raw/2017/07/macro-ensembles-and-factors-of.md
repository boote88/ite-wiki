---
title: Macro ensembles and factors of production
date: 2017-07-27T14:30:00.000-07:00
updated: 2017-07-28T10:15:56.456-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/07/macro-ensembles-and-factors-of.html
---

I was inspired by Dietrich Vollrath's [latest blog post](https://growthecon.com/blog/Constraints/) to work out the generalization of [the macro ensemble version of the information equilibrium condition](http://informationtransfereconomics.blogspot.com/2017/06/self-similarity-of-macro-and-micro.html) \[1\] to more than one factor of production. However, as it was my lunch break, I didn't have time to LaTeX up all the steps so I'm just going to post the starting place and the result (for now).



We have two ensembles of information equilibrium relationships $A_{i} \rightleftarrows B$ and $A_{j} \rightleftarrows C$ (with two factors of production $B$ and $C$), and we generalize the partition function analogously to [multiple thermodynamic potentials](http://informationtransfereconomics.blogspot.com/2015/04/economic-potentials-or-how-to-define.html) (see also [here](http://informationtransfereconomics.blogspot.com/2016/09/balanced-growth-maximum-entropy-and.html)):






Playing the same game as worked out in \[1\], except with partial derivatives, you obtain:






This is the same as before, except now the values of $k$ can change. If the $\langle k \rangle$ change **slowly** (i.e. treated as almost constant), the solution can be approximated by a Cobb-Douglas production function:






And now you can read Vollrath's piece keeping in mind that using an ensemble of information equilibrium relationships implies $\beta$ (e.g. $\langle k^{(1)} \rangle$) can change and we aren't required to maintain $\langle k^{(1)} \rangle +&nbsp;\langle k^{(2)} \rangle = 1$.



...

**Update 28 July 2017**


I'm sure it was obvious to readers, but this generalizes to any number of factors of production using the partition function



$$<br />Z = \sum_{i_{n}} \exp \left( - \sum_{n} k_{i_{n}}^{(n)} \log B^{(n)}/B_{0}^{(n)} \right)<br />$$

where instead of $B$ and $C$ (or $D$), we'd have $B^{(1)}$ and $B^{(2)}$ (or $B^{(3)}$). You'd obtain:



$$<br />
\frac{\partial \langle A \rangle}{\partial B^{(n)}} = \; \langle k^{(n)} \rangle \frac{\langle A \rangle}{B^{(n)}}<br />
$$
