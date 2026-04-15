---
title: "What do equations mean?"
date: 2018-09-13T18:00:00.000-07:00
updated: 2018-10-02T17:10:55.987-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2018/09/what-do-equations-mean.html
---

Arjun Jayadev and J.W. Mason [have an article out on INET](https://www.ineteconomics.org/perspectives/blog/mainstream-macroeconomics-and-modern-monetary-theory-what-really-divides-them) on what MMT purportedly is along with the basic fact that MMT policy prescriptions do not differ too much from that advised by the average macroeconomist in surveys. My post on this had been sitting around in my drafts since the day I read their article, but was boring (to me) and seemed likely to set off the MMT hive-mind. However, [Jo Michell put up a thread about it](https://twitter.com/JoMicheII/status/1040112709348544512) and there was [a subsequent discussion between he and  J. W. Mason](https://twitter.com/JWMason1/status/1040220682225938434) that brought up an interesting general question: _What do equations mean?_

Michell says that it looks like you can get the same results Jayadev and Mason give from a standard DSGE treatment — the resulting equations in both cases are formally similar. I agree with that entirely. After bristling from being told the results are formally equivalent to a DSGE model (the three equation New Keynesian DSGE model), Mason says:

> _“A can be derived from B (with various ancillary assumptions)” is not the same as “B is just a form of A”, any more than fact that a text can be translated into Latin means it was written in Latin all along._

In a sense, I agree with that as well! I'll get into it later — first I want to talk about what Mason said next (I added some brackets to add context back in because it's lost when quoting a single tweet out of a thread):

> _People like Cochrane, who \[r\]eally do believe the sacred texts \[i.e. microfoundations\], are appropriately scathing on this \[i.e. that it's not just the final form that matters\]_

with a link to [a blog post by John Cochrane](https://johnhcochrane.blogspot.com/2013/11/new-vs-old-keynesian-stimulus.html). Cochrane claims that Old Keynesian (OK) and New Keynesian (NK) models may have the same policy prescriptions, but have entirely different mechanisms leading to them. In the OK model, government spending increases income and each household's marginal propensity to consume means that increased income yields more output than the original government outlay (a "multiplier"). In the NK model, the additional output arises because government spending increases inflation and households spend now because their income in later periods is going to be worth less because of that inflation. It's essentially due to the equilibrating effect of the "Permanent Income Hypothesis" (PIE). The [best blog post on this kind of legerdemain was at Mean Squared Errors](https://meansquarederrors.blogspot.com/2016/09/houdinis-straightjacket.html), calling it "Houdini's Straitjacket":

> _Consider the macroeconomist.  She constructs a rigorously micro-founded model, grounded purely in representative agents solving intertemporal dynamic optimization problems in a context of strict rational expectations.  Then, in a dazzling display of mathematical sophistication, theoretical acuity, and showmanship (some things never change), she derives results and policy implications that are exactly what the IS-LM model has been telling us all along.  Crowd — such as it is — goes wild._

The NK DSGE model comes up with the same policy prescriptions as the OK model by essentially escaping the straitjacket of microfoundations.

Of course, John Cochrane is being disingenuous — the requirement for microfoundations was created explicitly to try and prevent fiscal policy from having any effect in macro models. The NK DSGE model comes along and says it can get the same results even if it plays his game. Cochrane complaining that the model doesn't get the same result for the same reasons is effectively admitting that the microfoundations weren't some hard-nosed theoretical approach but rather just a means to stop fiscal policy from having an effect.



When Mason says that it's the "various ancillary assumptions" or Cochrane says it's the mechanisms that make these theories different, they're right. That the OK model, the NK DSGE model, the IS-AS-MP model (per Michell), the [Information Equilibrium (IE) NK DSGE model](https://informationtransfereconomics.blogspot.com/2016/08/dsge-part-5-summary.html), and MMT say fiscal expansion can raise GDP doesn't mean they are the same theory.

It does mean they are the same [_effective_ theory](https://en.wikipedia.org/wiki/Effective_theory), though.

And that means that the "various ancillary assumptions" don't matter **_except_** for the [scope conditions](https://informationtransfereconomics.blogspot.com/2018/08/tractability-and-scope.html) (the limits of validity of the model) they imply, the empirical tests they suggest, as well as giving us a hint as to what might happen when a theory fails empirically. It only matters how you arrive at a result if you failed to fit the data or try to make further progress because you succeeded in fitting the data. How you arrive at a result tells you whether contrary empirical observations are out of scope, what the possible failure mechanisms are, what assumptions you can relax to get more general results, or address other questions. For example, DSGE approaches tend to make assumptions like the PIE. Failures of DSGE models will potentially show up [as deviations from the PIE](https://informationtransfereconomics.blogspot.com/2017/01/consumption-income-and-pih.html). The IE NK DSGE model I link to above contains assumptions about information equilibrium relationships and maximum entropy; the relationships will fail to hold if agents decide to correlate in the state space (opportunity set) — e.g. panic in a financial crisis.

This is all to say that the "various ancillary assumptions" **_don't matter_** unless you make _**empirical tests of your theory**_. And in this particular case, I want to show that those empirical tests have to be tests of the underlying assumptions, not the resulting policy conclusions. All of those models contain an equation that looks something like Jayadev and Mason's equation (2) relating interest rates, fiscal balance, and output — motivating the policy prescriptions. I'm going to show that equation (2) arises with really no assumptions about output or interest rates, or even what the variables $Y$, $i$, or $b$ mean at all. They could stand for yakisoba, iridium, and bourbon. _The only test of that theory would come from trying (and failing) to make yakisoba from iridium and bourbon in the real world._



This is where we get into my original draft post. Let's say I have an arbitrary function $Y = Y(i, b)$ where $i$ and $b$ are independent. It will turn out that the conclusion and policy prescriptions will depend entirely on choosing these variables (and not others) to correspond to the interest rate and fiscal balance. Varying $Y$ with respect to $i$ and $b$ gives me (to leading order in small deviations, i.e. the total differential):






These infinitesimals can be rewritten in terms of deviation from some arbitrary point $(i_{0}, b_{0} ,Y_{0})$, so let's rewrite the previous equation:










The first three terms are what they define to be $A$ (i.e. the value of $Y$ when $b$ and $i$ are zero). Let's add in $Y/Y \equiv 1$ (i.e. an identity):






As stated in their article, "$\eta$ is the percentage increase in output resulting from a point reduction in the interest rate", which means:






Likewise, the multiplier $\gamma$ is (based on the sign convention for $b$ with deficits being negative):










based entirely on the definition of the total differential and some relabeling. This is to say that this equation is entirely content-less \[1\] in terms of the real world aside from the assertion that the variables correspond to real world observables. It's usefulness (and ability to lead to MMT policy prescriptions) would come from not just estimating the values of $\gamma$ and $\eta$ empirically, but **_finding that they are constant and positive_**. Of course this is going to describe a relationship between $Y$, $i$, and $b$ for _changing_ $\gamma$ and $\eta$ because it essentially reiterates what we mean by functions that change (i.e. calculus). That's why all those models I listed above — such as the NK DSGE — come to a roughly isomorphic result. If you're trying to show fiscal expansion increases GDP you're going to arrive at something like this equation to leading order.

It's the assumption that output depends on fiscal balance and interest rates that leads us here, and so it's only useful if we find empirically that the coefficients are constant — otherwise we can always find some $\eta$ and some $\gamma$ that works. It's the same way $PY = MV$, the monetarist equation of exchange, would be useful if $V$ is constant. Otherwise, it is just a definition of $V$. This fiscal equation is actually a bit worse because it doesn't unambiguously identify $\eta$ and $\gamma$ (different values work for different values of $A$).



Defining terms is often a useful start of a scientific endeavor, but what we have here is a mathematical codification of the assumption that fiscal policy affects GDP of almost exactly the same form as the old school monetarist assumption that "printing money" affects GDP. The problem is that this is exactly the problem in question: How does a macroeconomy respond to various interventions? MMT prescribes deficit spending in the face of recession "because the output responds positively to fiscal expansion". [It's question begging](https://en.wikipedia.org/wiki/Begging_the_question) in the same way that people seem to [conduct research into recessions by assuming what a recession is](https://informationtransfereconomics.blogspot.com/2015/11/frameworks.html).



In MMT, there appears to be a lot of representing assumptions about how an economy works as math, and then using that math to justify policy prescriptions that is effectively equivalent to justifying policy prescriptions by assuming they are correct. I've discussed this before (e.g. [here](https://informationtransfereconomics.blogspot.com/2017/05/mathiness-in-modern-monetary-theory.html), [here](https://informationtransfereconomics.blogspot.com/2016/03/more-like-stock-flow-in-consistent.html), or [here](https://informationtransfereconomics.blogspot.com/2016/12/stock-flow-consistency-is-tangential-to.html)) — whether the "various ancillary assumptions" are that government expenditures are private income, that there is no money multiplier, or that the desired wealth to income ratio is reasonably constant, these assumptions are translated into math and then that math is said to justify the assumptions.



The point of Jayadev and Mason's article is that these assumptions are completely in line with mainstream assumptions and models in macroeconomics — and they are. That's the problem. Macro models like DSGE models also make a bunch of assumptions about how an economy works — some of the same assumptions — but then don't end up describing the data very well. But then the equations are formally similar, which implies the MMT model won't describe the data very well either. There's more parametric freedom in the MMT approach, so maybe it will do better. What we really need to see is some empirical validation, not arguments that "it actually has things in common with mainstream macro". Mainstream macro isn't very good empirically, so that's not very encouraging.

I have no problems with the policy prescriptions of MMT proponents (austerity is bad and deficits don't matter unless inflation gets crazy), but I do have a problem with the idea that these policy prescriptions arise from something called "Modern Monetary Theory" purported to be a well-defined theory instead of a collection of assumptions. It would go a long, long way towards being useful if it empirically validated some of those equations. Without that empirical validation, all the equations really mean is that you were able to find a way out of your own Houdini's straitjacket constructed from your own assumptions in order to arrive at something you probably already believed.





**Footnotes:**


\[1\] There's nothing wrong with content-less theory on the surface. Quantum field theory, one of the most successful frameworks in human history for explaining observations, is essentially content-less aside from analyticity and unitarity \[[pdf](http://www.sbfisica.org.br/~evjaspc/xviii/images/Burgess/Jan29/Aditional/Phenomenological-Lagrangians-Weinberg.pdf)\]. It's the particle content (electrons, photons, etc) you put in it that gives it its empirical power. A similar situation arises with Kirchoff's laws: [content-less accounting until you add real world circuit elements](https://informationtransfereconomics.blogspot.com/2016/12/stock-flow-consistency-is-tangential-to.html).
