---
title: The ISLM model (again)
date: 2014-03-20T18:54:00.000-07:00
updated: 2015-05-22T21:14:40.813-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/03/the-islm-model-again.html
---

The economist [John Hicks](http://en.wikipedia.org/wiki/John_Hicks) wrote out Keynes' prose as an economic model that came to be known as the [IS-LM model](http://en.wikipedia.org/wiki/IS/LM_model). I [already derived this model](http://informationtransfereconomics.blogspot.com/2013/08/deriving-is-lm-model-from-information.html) before in a way that followed the way it is introduced in macroeconomics classes (as an IS and LM market). This derivation will acheive the same result, but approached fundamentally as an information transfer market system. The basis for the IS-LM model is that there are two markets: the real economy (IS) and the money market (LM) that couple to each other through the interest rate. As an information transfer system, we'll take a more direct route. We will posit that aggregate investment (demand) is a source of information that sends signals into the market that are detected by interest rate changes. The aggregate investment supply (the money supply) receives this information. See [this post](http://informationtransfereconomics.blogspot.com/2014/03/how-money-transfers-information.html) for a more detailed description of how information moves around the economy.



Let's start with the market $r : I \rightarrow M$, with interest rate $r$, nominal investment $I$ and money supply $M$ so that





from the basic information transfer model. Looking at constant information source $I = I_{0}$, we have





where $\langle M \rangle$ is the expected level of the money supply.  Solving the differential equation (1), we obtain





where $ref$ refers to reference values of the variables $I$ and $M$. We can combine the previous two equations into a single function that defines the IS curve:





We can also look at constant $M = M_{0}$ so that we have, solving the differential equation (1) again:











Equations (2) and (3) represent how the market adjusts the interest rate to changes in the money supply given fixed investment demand and to changes in the investment demand given fixed money supply, respectively.



One more piece -- we need to relate output $Y$ to investment $I$ and money $M$. I'll add a simple market $p : N \rightarrow I$ where $N$ is NGDP (aggregate demand, sending information to aggregate investment) so that









It turns out empirically (see below), $\eta \simeq 1$ so that $\log N$ is proportional to $\log I$. If we hold the price level constant (we are looking at short run effects \[1\]), then we can say that $Y = N/P$ is proportional to $I$. This is the first part. To get the relationship with $M$, we'll match first order shifts of the IS and LM curves. If we have a small change in $r = r_{0} + \delta r$, then we have for the IS curve:













So that we have (after taking the absolute value as a postitive shift of the LM curve causes the interest rate to fall, but a positive shift in the IS curve causes the interest rate to rise)





Which means $\Delta Y \sim \Delta I \sim \Delta M$ are all proportional to each other and we can scale the IS and LM curves such that they become functions of $Y$. This allows us to plot them on the same graph, like the ISLM model. On the left, we have the relationship between $I$ and $Y$ and on the right, we have the IS-LM model graph (IS curve in blue, LM curve in red):


![](<media/itm empirical islm 1.png>)

Empirically, it works best if we take $r \rightarrow r^{c}$ where $c \simeq 1/3$ \[2\] ($M$ is taken to be the monetary base):


![](<media/itm empirical islm 2.png>)


![](<media/itm empirical islm 3.png>)

\[1\] This is effectively where economists' complaint about the IS-LM model not incorporating inflation (by not differentiating real and nominal interest rates) comes in.



\[2\] This is a fudge that [I have yet to figure out](http://informationtransfereconomics.blogspot.com/2014/03/unsolved-problems-in-information.html). The empirical results for the 10-year and 3-month interest rates are a pretty good motivation. It fits the data. Additionally, it is basically a re-labeling of the interest rates. There is no a priori reason that the "information price" $p_{i}$ that goes into Equation (1) and the real world price represented by the interest rate $r$ need to be related by $r = p_{i}$; any bijective relationship is possible. We encounter this all the time e.g. decibels give us a more intuitive linear feeling of loudness than power. The market treats the cube root of the interest rate as a linear measure of information.



**UPDATE 5/22/2015**


Fixed the fudge factor. See [here](http://informationtransfereconomics.blogspot.com/2015/02/information-equilibrium-paper-draft_23.html). Basically introduced another information equilibrium relationship between $r$ and the price of money $p$ so that the market at the top of the page becomes:
