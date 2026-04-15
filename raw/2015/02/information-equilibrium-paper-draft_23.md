---
title: Information equilibrium paper (draft) (macroeconomics) 
date: 2015-02-23T19:05:00.000-08:00
updated: 2015-03-05T08:41:54.780-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/02/information-equilibrium-paper-draft_23.html
---

> Since I apparently can't seem to sit down and write anything that isn't on a blog, I thought I'd create a few posts that I will edit in real time (feel free to comment) until I can copy and paste them into a document to put on the arXiv and/or submit to the economics e-journal (H/T to Todd Zorick for helping to motivate me).
>
>
> _WARNING: DRAFT: This post may be updated without any indications of changes. It will be continuously considered a draft._

**Macroeconomics**


Since the information equilibrium framework depends on a large number of states for the information source and destination, it ostensibly would be better applied to the macroeconomic problem. Below are some classic macroeconomic toy models (and one macroeconomic relationship): AD-AS model, Okun's law, the IS-LM model, and the Solow growth model. 



\[To be added, the price level/quantity theory of money\]


**AD-AS**


The AD-AS model uses the price level $P$ as the detector, aggregate demand $N$ (NGDP) as the information source and aggregate supply $S$ as the destination, or $P:N \rightarrow S$, which immediately allows us to write down the aggregate demand and aggregate supply curves







Positive shifts in the aggregate demand curve raise the price level along with negative shifts in the supply curve. Traveling along the aggregate demand curve lowers the price level (more aggregate supply at constant demand).


![](<media/ad as basic.png>)
**Labor market and Okun's law**


The labor market uses the price level $P$ as the detector, aggregate demand $N$ as the information source and total hours worked $H$ (or total employed $L$) as the destination. We have the market $P:N \rightarrow H$ so that we can say:













where $R$ is RGDP. The total hours worked (or total employed) fluctuates with the change in RGDP growth (Okun's law).


![](<media/sumner 2.png>)
**IS-LM**


The IS-LM model uses two markets along with an information equilibrium relationship. Let $p$ be the price of money in the money market (LM market) $p:N \rightarrow M$ where $N$ is aggregate demand and $M$ is the money supply.







We assume that the interest rate $i$ is in information equilibrium with the price of money $p$, so that we have the information equilibrium relationship $i \rightarrow p$ (no need to define a detector at this point). Therefore the differential equation is:









And we can write \[note: this is a new take ([here's the old take](http://informationtransfereconomics.blogspot.com/2014/09/deriving-fudge-factor-in-interest-rate.html)) on the constant $k_{i}$ that I've called $c$\]:






![](<media/ite interest rates us.png>)

We can now rewrite the money (LM) market and add the goods (IS) market as coupled markets with the same information source (aggregate demand) and same detector (interest rate, directly related to -- i.e. in information equilibrium with -- the price of money):






Where $S$ is the aggregate supply. The LM market is described by both increases in the money supply $M$ shifts as well as shifts in the information source $N_{0} \rightarrow N_{0} + \Delta N$, so we write the LM curve as a demand curve, with shifts:








![](<media/simple islm shift.png>)
**Solow growth model**










The economics rationale for equations (3a,b) are that the left hand sides are the marginal productivity of capital/labor which are _assumed_ to be proportional to the right hand sides -- the productivity per unit capital/labor. In the information transfer model, the relationship follows from a model of aggregate demand sending information to aggregate supply (capital and labor) where the information transfer is "ideal" i.e. no information loss. The solutions are:












Equation (4) is the generic Cobb-Douglas form. In this case, unlike equation (2), the exponents are free to take on any value (nor restricted to constant returns to scale, i.e. $1/\kappa_{1} + 1/\kappa_{2} = 1$). The resulting model is remarkably accurate:


![](<media/itm solow growth model -take two- 2.png>)

It also has no changes in so-called total factor productivity ($A$ is constant). The results above use nominal capital and nominal GDP $N$ rather than the usual real capital and real output (RGDP, $R$).


**Summary**


We have shown that several macroeconomic relationships and toy models can be easily represented using the information equilibrium framework, and in fact are remarkably accurate empirically. Below we list a summary of the information equilibrium models in the notation



_detector : source → destination_, 



i.e. _price : demand → supply_. Also the information equilibrium models that do not require detectors are shown as 



_source → destination._



The models shown here are:



**AD-AS model**





**Labor market** (Okun's law)




or





**IS-LM model**






**Solow growth model**
