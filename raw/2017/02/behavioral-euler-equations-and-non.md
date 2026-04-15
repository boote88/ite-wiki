---
title: Behavioral Euler equations and non-ideal information transfer
date: 2017-02-15T18:00:00.000-08:00
updated: 2017-02-15T18:00:06.416-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/02/behavioral-euler-equations-and-non.html
---

I read through [Noah Smith's question and answer session](http://noahpinionblog.blogspot.com/2017/02/my-ama-on-rbadeconomics.html) on Reddit. I liked this quote:

> _But I doubt the Post-Keynesians will ever create their own thriving academic research program, and will keep on influencing the world mainly through pop writing and polemics. I think they like it that way._

But on a more serious note, Noah linked (again) to a paper \[[pdf](http://pages.stern.nyu.edu/~xgabaix/papers/brNK.pdf)\] by Xavier Gabaix about a "behavioral" New Keynesian model. One of the things Gabaix introduces is an "attention parameter" $M$ in the Euler equation as a way of making it conform to reality more.



Let's quote Noah's response to a question about [his post](http://noahpinionblog.blogspot.com/2014/01/the-equation-at-core-of-modern-macro.html) on the Euler equation:

> _An Euler equation is a mathematical relationship between observables - interest rates, consumption, and so on._ 

> _There are actually infinite Euler equations, because the equation depends on your assumption about the utility function._ 

> _The problem is that standard utility functions don't seem to work. Now, you can always make up a new utility function that makes the Euler equation work when you plug in the observed consumption and interest rate data. Some people call this "utility mining" or "preference mining". One example of this is Epstein-Zin preferences, which have become popular in recent years._ 

> _The problem with doing this is that those same preferences might not work in other models. And letting preferences change from model to model is overfitting. So another alternative is to change the constraints - add liquidity constraints, for example. So far, there's lots of empirical evidence that liquidity constraints matter, but very few macro models include them yet._ 

> _Another, even more radical alternative is to change the assumptions about how agents maximize. This is what Gabaix does, for example, in a recent paper \[linked above\] ..._

Gabaix comes up with a modified Euler equation (log-linearized):






Now I derived [this piece](http://informationtransfereconomics.blogspot.com/2016/08/dsge-part-2.html) of the [New Keynesian model](http://informationtransfereconomics.blogspot.com/2016/08/dsge-part-5-summary.html) from [information equilibrium](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html) (and maximum entropy) a few months ago. However, let me do it again (partially because this version has a different definition of $\sigma$ and is written in terms of the output gap).



I start with the [maximum entropy condition](http://informationtransfereconomics.blogspot.com/2015/06/the-euler-equation-as-maximum-entropy.html) for intertemporal consumption with a real interest rate $R$ such that:






If we have the information equilibrium relationship $Y \rightleftarrows C$ (output and consumption) with IT index $\sigma$, we can say $Y \sim C^{\sigma}$ and therefore, after log-linearizing (and substituting the nominal interest rate and inflation):






where in the last step we rewrote output in terms of the output gap and deviation from the interest rate $r^{n}$.



You may have noticed that the $E$'s are missing. That's because the derivation was done assuming information equilibrium. As I show [here](http://informationtransfereconomics.blogspot.com/2016/08/dsge-part-3-stochastic-interlude.html), this means that we should include an "information equilibrium" operator $E_{I}$ (think of it as an expectation of information equilibrium):






Under conditions of [non-ideal information transfer](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html), we'd actually expect that






(you cannot receive more information than is sent). Therefore, in terms of rational expectations (model-consistent expectations), we'd actually have:






with $M \leq 1$. Back to Gabaix:

> _In the Euler equation consumers do not appear to be fully forward looking: M < 1. The literature on the forward guidance puzzle concludes, plausibly I think, that M < 1._

We recover a "behavioral" model that can be understood in terms of non-ideal information transfer.
