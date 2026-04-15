---
title: The ISLM model (reference post)
date: 2017-01-05T16:00:00.000-08:00
updated: 2017-04-26T20:42:52.089-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/01/the-islm-model-reference-post.html
---

I've looked at the ISLM model as an information equilibrium model on multiple occasions, but I thought I'd develop a better reference post for it based largely on [this post](http://informationtransfereconomics.blogspot.com/2014/03/the-islm-model-again.html) and [the paper](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html) (which is [now on SSRN](http://ssrn.com/abstract=2894072)) with some updated notation conventions.



The ISLM model is based on two markets: the money market (LM piece, $M$) and the goods market (IS piece, $S$, for aggregate supply). There are additional information equilibrium relationships that relate the price of money $p$ to the interest rate $r$ and investment $I$ ([GPDI](https://fred.stlouisfed.org/series/GPDI)) to nominal output $N$ (NGDP). In the [compact information equilibrium notation](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html) we have:










Solving the second differential equation ($r = p^{k_{r}}$) and combining with the RHS of the first gives us (combining constants into new constants $c$ and $k$)






If we let $M$ be the monetary base (MB) and $r$ be the 3 month interest rate, we can determine the parameters $c$ and $k$ from the data:



![](<media/interest rates -investment- -3 month-.png>)

If we let $M$ be the monetary base minus reserves (M0) and $r$ be the 10 year interest rate, we can determine the parameters $c$ and $k$ from the data:



![](<media/interest rates -investment- -10 year-.png>)

It is also possible to solve these using the _**same**_ parameters $c$ and $k$ for **_both_** interest rates:



![](<media/interest rates -investment- -3 month- A.png>)![](<media/interest rates -investment- -10 year- A.png>)

This gives us the general trend in interest rates, but for the partial equilibrium model (the "traditional" ISLM model) we need to look at the case where $I$ moves slowly compared to changes in $S$ and quickly in response to changes in $M$ to obtain supply and demand curves in the two markets \[1\].



**Diagrams: the IS curve**


We can simplify our information equilibrium relationships if we assume that the relationship $r \rightleftarrows p$ is ideal \[2\] so that we can just replace $p$ with $r^{1/k_{r}}$ giving us






Well take the more traditional route to the ISLM diagram (which I did [here](http://informationtransfereconomics.blogspot.com/2013/08/deriving-is-lm-model-from-information.html)) than the approach [here](http://informationtransfereconomics.blogspot.com/2014/03/the-islm-model-again.html) where a more direct route is taken. This affects the derivation of the LM curve more than the IS curve which we will look at first. If we assume $I$ moves slowly with respect to changes in $S$, we can say that investment stays close to some value $I \approx I_{0}$ while $S$ changes, and therefore










where we define $\Delta I = \langle I \rangle&nbsp;- I_{ref}$. You can think of the angle brackets as representing the observed values (more discussion is [here](http://informationtransfereconomics.blogspot.com/2014/06/is-supply-curve-flat.html)). Substituting the price $r^{1/k_{r}} \approx k_{s} I_{0}/\langle S \rangle$ and a little bit of algebra we obtain a demand curve in the goods market:







![](<media/islm 1.png>)
**Diagrams: the LM curve**






However in this case we assume an equilibrium condition such that $\Delta I = \mu \Delta M$ effectively selecting a point on the money demand curve ‒ i.e. the point in the standard derivation where you assume money demand is equal to money supply with money demand (here given by aggregate demand for investment). We also look at shifts **_of_** (not along) the money demand curve by shifting the reference value $I_{0}$ by $\delta I_{0}$ (also following the standard derivation).







The effect is illustrated for $\Delta M = 0$ in the diagram below (which traces out the LM curve, first diagram), and if we then shift $\Delta M$, we can look at the new LM curve traced out by shifts of $\delta I_{0}$ (second diagram):



![](<media/islm 2.png>)![](<media/islm 6.png>)

In this picture we are effectively looking at the supply curve, but restricted to cases where the demand curve adjusts to it so we end up with effectively restoring the equation






We could actually just start from $I&nbsp;\sim M^{k_{m}}$, but doing this in terms of supply and demand diagrams requires a bit more of a circuitous route. 



**Diagrams: combining the curves**



![](<media/islm 3.png>)![](<media/islm 4.png>)

**Aside: Effective theory**


I do want to illustrate a bit about [effective theory](http://informationtransfereconomics.blogspot.com/2016/02/the-is-lm-model-as-effective-theory-at.html) and [scope](http://informationtransfereconomics.blogspot.com/2016/06/on-is-lm-and-scope.html) using the previous graph. If we show the lines for many possible changes $\Delta M$ as well as $\Delta I$ we get a "grid" of sorts covering the graph (first/left picture below). Well, mostly a grid; you can see that it makes a grid near the center (highlighted in blue), but you get different behavior for large (negative) changes in $\Delta I$ as well as for low interest rates (highlighted in orange). In fact, for some cases there aren't even solutions.



![](<media/islm 5.png>)![](<media/islm 5a.png>)

What this means is that the theory is breaking down for those cases: low interest rates or large negative shocks to investment (though, roughly on the order of complete collapse). Much like how Einstein's general relativity breaks down at the singularity (which involves a similar kind of lack of a "grid" for space and time) telling us we need a new theory (quantum gravity), the ISLM model breaks down for low interest rates (likely yielding something like the liquidity trap).



**Output**


The last piece of our model is the relationship between investment and output. We have $N \rightleftarrows I$ (call the IT index $\eta$) so that










Empirically, we have $\eta \simeq 0.98$ as we can see from the slope of $N$ vs $I$ on a log-log graph:



![](<media/output investment.png>)

So therefore (assuming this relationship holds, as it appears to do in the long run) we can say that boosting investment boosts output (and therefore unemployment via Okun's law which is just the relationship $P : N \rightleftarrows L$ where $P$ is the price level and $L$ is the labor supply \[4\]).



**_\*  \*  \*_**

**Footnotes**


\[1\] This becomes a major assumption that reduces the model's scope to cases where inflation is low because when inflation is high, large changes in the nominal values of $N$ and $I$ are at least [associated empirically](http://informationtransfereconomics.blogspot.com/2015/06/the-quantity-theory-of-money-as.html) with large changes in $M$ so that we can't assume it **_doesn't_** happen).

\[2\] This is another key assumption: that the interest rate ($r$) represents the price of money ($M$). It is theoretically possible these can become disconnected.

\[3\] There's an even easier way to do this but it has more limited scope. If we start from the equation:

$$<br />\begin{align}<br />p = r^{1/k_{r}} = &amp; \; k_{m} \; \frac{I}{M}\\<br />r^{1/k_{r}} = &amp; \; k_{m} \; \frac{I_{0} + \Delta I}{M_{ref} + \Delta M}<br />\end{align}<br />$$
we obtain the result immediately. However, the ISLM model graph looks a bit different:


![](<media/easy way.png>)
Essentially the scope is limited to a very narrow region around equilibrium.

\[4\] You can also use hours worked as I did in [the paper](http://informationtransfereconomics.blogspot.com/2015/08/information-equilibrium-as-economic.html) (or in draft form [here](http://informationtransfereconomics.blogspot.com/2015/02/information-equilibrium-paper-draft_23.html)).
