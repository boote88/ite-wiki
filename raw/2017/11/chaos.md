---
title: "Chaos!"
date: 2017-11-02T15:00:00.000-07:00
updated: 2018-04-23T16:02:54.709-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/11/chaos.html
---

_Like the weather, the economy is complicated._



_Like the weather, the economy obeys the laws of physics._



_Like the weather, the economy is aggregated from the motion of atoms._



Doyne Farmer only said the first one, but inasmuch as this is some kind of argument in favor of any particular model of the economy so are the other two. [Sure, it's complicated](https://informationtransfereconomics.blogspot.com/2017/01/complex-systems-versus-complicated.html). But that doesn't mean we can assume it is a complex system like weather without some sort of evidence. [Farmer's post](https://www.rebuildingmacroeconomics.ac.uk/business-cycles-chaotic-part/) is mostly just a hand-waving argument that the economy might be a chaotic system. It's the kind of thing you write before starting down a particular research program path — the kind of thing you write for the suits when asking for funding.



But it doesn't really constitute **_evidence_** that the economy is a chaotic system. So when Farmer says:

> _So it is not surprising that simple chaos was not found in the data.  That does not mean that the economy is not chaotic.  It is very likely that it is and that chaos can explain the patterns we see._

The phrase "very likely" just represents a matter of opinion here. I say its "very likely" chaos is not going to be a useful way to understand macroeconomics. I have a Phd in physics and have studied economics for some time now, with several empirically successful models. So there.



To his credit, Farmer does note that the initial attempts to bring chaos to economics didn't pan out:

> _But economists looked for chaos in the data, didn’t find it, and the subject was dropped.  For a good review of what happened see Roger Farmer’s blog._

I went over [Roger Farmer's excellent blog post](http://www.rogerfarmer.com/rogerfarmerblog/2016/10/4/nho932exasra0c2a2amkvdmovcy9rz?rq=chaos), and added to the argument in [my post here](https://informationtransfereconomics.blogspot.com/2016/10/keen-chaos-and-equilibrium.html).



Anyway, I have several issues with Doyne Farmer's blog post besides the usual "don't tell us chaos is important, show us" via some empirical results. In the following, I'll excerpt a few quotes and discuss them. First, Farmer takes on a classic econ critic target — the four-letter word DSGE:

> _Most of the  Dynamic Stochastic General Equilibrium (DSGE) models that are standard in macroeconomics rule out chaos from the outset._

To be fair, it is the _log-linearization_ of DSGE models that "rules out" chaos, but then it only "rules out" chaos in regions of state space that are _out of scope for the log-linearized versions of DSGE models_. So when Farmer says:

> _Linear models cannot display chaos – their only possible attractor is a fixed point._

it comes really close to a bait and switch. An attractor is a property of the entire state space (phase space) of the model; the log-linearization of DSGE models is a description valid (in scope) for a small region of phase space. In a sense, Farmer is extending the log-linearization of a DSGE model to the entire state space. 



However, [Eggertsson and Singh](http://www.nber.org/papers/w22784) show that the log-linearization doesn't actually change the results very much — even up to extreme events like the Great Depression. This is because in general most of the relevant economic phenomena we observe appear to be perturbations: recessions impact GDP by ~ 10%, high unemployment is ~ 10%. In a sense, observed economic reality tells us that we don't really stray far enough away from a local log-linearization to tell the difference between a linear model and a non-linear one capable of exhibiting chaos. This is basically the phase space version of the argument [Roger Farmer makes in his blog post](http://www.rogerfarmer.com/rogerfarmerblog/2016/10/4/nho932exasra0c2a2amkvdmovcy9rz?rq=chaos) that we just don't have enough data (i.e. we haven't explored enough of the phase space).



The thing is that a typical nonlinear model that can exhibit chaos (say, the predator-prey model defined by the [Lotka–Volterra equations](https://en.wikipedia.org/wiki/Lotka%E2%80%93Volterra_equations)) has massive fluctuations. The chaos is not a perturbation to some underlying bulk, but is rather visiting the entire phase space. You could almost take that as a definition of chaos: a system that visits a large fraction of the potential phase space. This can be seen as a consequence of the "[butterfly effect](https://en.wikipedia.org/wiki/Butterfly_effect#Theory_and_mathematical_definition)": two initial conditions in phase space become separated by exponentially larger distances over time. Two copies of the US economy that were "pretty close" to start would evolve to be wildly different from each other — e.g. their GDPs would become exponentially different. Now this is entirely possible, but the difference in GDP growth rates would probably be only a percentage point or two at best which would take a generation to become exponentially separated. Again, this is just another version of Roger Farmer's argument that we don't have long enough data series.



Another way to think of this is that the non-trivial attractors of a chaotic system visit some extended region of state space, so you'd imagine that a general chaotic model would produce large fluctuations in its outputs representative of the attractor's extent in phase space. For example, [Steve Keen's dynamical systems exhibit massive fluctuations compared to those observed](https://informationtransfereconomics.blogspot.com/2017/02/qualitative-economics-done-right-part-2.html).



Now this in no way rules out the possibility that macroeconomic observables can be described by a chaotic model. It is just an argument that a chaotic model that produces the ~ 10% fluctuations actually observed would have to result from either some fine tuning or a bulk underlying equilibrium \[1\].



In a sense, Farmer seems to cedes all of these points at the end of his blog post:

> _In a future blog post I will argue that an important part of the problem is the assumption of equilibrium itself.  While it is possible for an economic equilibrium to be chaotic, I conjecture that the conditions that define economic equilibrium – that outcomes match expectations – tend to suppress chaos._

It is a bit funny to begin a post talking up chaos only to downplay it at the end.  I will await this future blog post, but this seems to be saying that we don't see obvious chaos (with its typical large fluctuations) because chaos is suppressed via some bulk underlying equilibrium (outcomes match expectations) — so that we essentially need longer data series to extract the chaotic signal.



But then after building us up with a metaphor using weather which is notoriously unpredictable, Farmer says:

> _Ironically, if business cycles are chaotic, we have a chance to predict them._

_Like the weather, the economy is predictable._



??!



Now don't take this all as a reason not to study chaotic dynamical systems as possible models of the economy. At best, it represents a reason I chose not to study chaotic dynamical systems as possible models of the economy. I think it's going to be a fruitless research program. But then again, I originally wanted to work in fusion and plasma physics research.



Which is to say arguing in favor of one research program or another based on theoretical considerations tends to be more philosophy than science. Farmer can argue in favor of studying chaotic dynamics as a model of the economy. David Sloan Wilson [can argue in favor of biological evolution](https://informationtransfereconomics.blogspot.com/2016/01/complexity-without-purpose-evolution-as.html). It's a remarkable coincidence that both of these scientists see the macroeconomy not as economics, but rather as a system best described using their own field of study they've worked in for years \[2\].



What would be useful is if Farmer or Wilson just **_showed_** how their approaches lead to models that better described the empirical data. That's the approach I take on this blog. One plot or table describing empirical data is worth a thousand posts about how one intellectual thinks the economy should be described. In fact, how this scientist or that economist thinks the economy should be properly modeled is no better than how a random person on the internet thinks the economy should be properly modeled without some sort empirical evidence backing it up. Without empirical evidence, science is just philosophy.



...



PS



I found this line out of place:

> _Remarkably a standard family of models is called “Real business cycle models”, a clear example of Orwellian newspeak._

Does Farmer not know that "real" here means "not nominal"? I imagine this is just a political jab as a chaotic model could easily be locally approximated by an RBC model.



...



**Footnotes**



\[1\] For example _NGDP ~ exp(n t) (1 + d(t))_ where the leading order growth "equilibrium" is given by exp(n t) while the chaotic component is some kind of business cycle function _|d(t)| << 1_.



\[2\] Isn't that what I'm doing? Not really. My thesis was about quarks. I also hated thermodynamics, and my current job is more signal processing.
