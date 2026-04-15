---
title: Curve fitting and relevant complexity
date: 2017-01-15T16:11:00.001-08:00
updated: 2017-01-15T16:11:57.442-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/01/curve-fitting-and-relevant-complexity.html
---

A continuing exchange with [UnlearningEcon](https://twitter.com/UnlearningEcon/status/820744382160785408) prompted me to revisit [an old post](http://informationtransfereconomics.blogspot.com/2014/06/what-if-money-was-made-of-vinegar.html) from two and a half years ago. You don't need to go back an re-read it because I am basically going to repeat it with updated examples; hopefully my writing and explanation skills have improved since then.



The question UnlearningEcon asked was what good are fits to the (economic) data that don't come from underlying explanatory (behavior) models?



The primary usefulness is that fits to various functional forms ([ansatze](https://en.wikipedia.org/wiki/Ansatz)) bound the _relevant_ complexity of the underlying explanatory model. It is true that the underlying model may be truly be incredibly complex, but if the macro-scale result is just log-linear (_Y = a log X + b_) in a single variable then the _relevant_ complexity of your underlying model is about two degrees of freedom (_a, b_). This is the idea behind "information criteria" like the [AIC](https://en.wikipedia.org/wiki/Akaike_information_criterion): more parameters represent a loss of information.



My old post looks at an example of thermodynamics. Let's say at constant temperature we find empirically that pressure and volume have the relationship _p ~ 1/V_ (the ideal gas law). Since we are able to reliably reproduce this macroscopic behavior through the control of a small number of macroscopic degrees of freedom _even though we have absolutely no control over the microstates_, the microstates must be largely irrelevant.



And it is true: the quarks and gluon microstate configurations (over which we have no control) inside the nucleus of each atom in every molecule in the gas are incredibly complicated (and not even completely understood ‒ it was the subject of [my Phd thesis)](https://inspirehep.net/record/690305). But those microstates are irrelevant to understanding an ideal gas. The same applies to nearly all of the information about the molecules. Even vibrational states of carbon dioxide are irrelevant at certain temperatures (we say those degrees of freedom are frozen out).



The information equilibrium framework represents a way to reduce the relevant complexity of the underlying explanatory model even further. It improves the usefulness of fitting to data by reducing the potential space of the functional forms (ansatze) used to fit the data. As Fielitz and Borchardt put it [in the abstract of their paper](https://arxiv.org/abs/0905.0610): _Information theory provides shortcuts which allow one to deal with complex systems_. In a sense, the DSGE framework does the same thing in macroeconomics. However, models with far less complexity [do much better at forecasting](http://informationtransfereconomics.blogspot.com/2016/10/forecasting-it-versus-all-comers.html) ‒ therefore the complexity of DSGE models is probably largely irrelevant.



A really nice example of an information equilibrium model really bounding the complexity of the underlying explanatory model is the [recent series](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-unemployment-rate.html) I did looking at unemployment. I was able to explain most of the unemployment variation across several countries (US and EU shown) in terms of a (constant) information equilibrium state (dynamic equilibrium) and shocks:



![](<media/unemployment ratio -log version- 1960s.png>)![](<media/unemployment ratio -log version- EU 2.png>)

Any agent based model that proposes to be the underlying explanatory model can't have much more relevant complexity than a single parameter for the dynamic equilibrium (the IT index restricted by information equilibrium) and three parameters (onset, width, magnitude) for each shock (a Gaussian shock ansatz). Because we can reliably reproduce the fluctuations in unemployment for several countries with no control over the microstates (people and firms), then those microstates are largely irrelevant. If you want to explain unemployment during the "Great Recession", anything more than four parameters is going to "integrate out" (e.g. be replaced with an average). A thirty parameter model of the income distribution is going to result in at best a single parameter in the final explanation of unemployment during the Great Recession.



This is not to say coming up with that thirty parameter model is bad (it might be useful in understanding the effect of the Great Recession on income inequality). It potentially represents a step towards **_additional_** understanding. Lattice QCD calculations of nuclear states is not a bad thing to do. It represents additional understanding. It is just not relevant to the ideal gas law.



Another example is [my recent post](http://informationtransfereconomics.blogspot.com/2017/01/consumption-income-and-pih.html) on income and consumption. There I showed that a single parameter (the IT index _k_, again restricted by information equilibrium) can explain the relationship between lifetime income and consumption as well as shocks to income and consumption:



![](<media/consumption model 2.png>)![](<media/consumption model 3.png>)

Much like how I used an ansatz for the shocks in the unemployment model, I also used an ansatz for the lifetime income model (a simple three state model with Gaussian transitions):



![](<media/consumption model 1.png>)

This description of the data bounds the relevant complexity of any behavioral model you want to use to explain the consumption response to shocks to income or lifetime income and consumption (e.g. short term thinking in the [former](http://pages.stern.nyu.edu/~xgabaix/papers/brNK.pdf) \[pdf\], or expectations-based loss aversion in the [latter](https://www.aeaweb.org/conference/2015/retrieve.php?pdfid=67) \[pdf\]).



That adjective "relevant" is important here. We all know that humans are complicated. We all know that financial transactions and the monetary system are complicated. However, how much of that complexity is relevant? One of the issues I have with a lot of mainstream and heterodox economics (that I discuss at length [in this post](http://informationtransfereconomics.blogspot.com/2017/01/complex-systems-versus-complicated.html) and several posts linked there) is that the level of relevant complexity is simply **_asserted_**. You need to understand the data in order to know the level of relevant complexity. Curve fitting is the first step towards understanding relevant complexity. And that is the purpose of the information equilibrium model, as I stated in [the second post on this blog](http://informationtransfereconomics.blogspot.com/2013/04/an-informal-abstract-addition-why-now.html):

> _My plan is to produce an economic framework that captures at least a rich subset of the phenomena in a sufficiently rigorous way that it could be used to eliminate alternatives._

Alternatives there includes different models, but also different relevant complexities.



The thing that I believe UnlearningEcon (as well as many others that disparage "curve fitting") miss is that curve fitting is a major step between macro observations and developing the micro theory. A good example is blackbody radiation ([Planck's law](https://en.wikipedia.org/wiki/Planck's_law)) in physics \[1\]. This is basically the description of the color of objects as they heat up (black, red hot, white hot, blue ... [like stars](https://en.wikipedia.org/wiki/Stellar_classification)). Before Planck derived the shape of the blackbody spectrum, several curves had been used fit the data. Some had been derived from various assumptions about e.g. the motions of atoms. These models had varying degrees of complexity. The general shape was basically understood, so the relevant complexity of the underlying model was basically bounded to a few parameters. Planck managed to come up with a one-parameter model of the energy of a photon (_E = h ν_), but the consequence was that photon energy is quantized. A simple curve fitting exercise lead to the development of quantum mechanics! However, Planck probably would not have been able to come up with the correct micro theory (of light quanta) had others (Stewart, Kirchhoff, Wien, Rayleigh, Rubens) not been coming up with functional forms and fitting them to data.



Curve fitting is an important step, and I think it gets overlooked in economics because we humans immediately think we're important (see footnote \[1\]). We jump to reasoning using human agents. This approach hasn't produced a lot of empirical success in macroeconomics. In fact ‒ also about two and a half years ago ‒ [I wrote a post](http://informationtransfereconomics.blogspot.com/2014/08/against-human-centric-macroeconomics.html) questioning that approach. Are human agents _relevant_ complexity? We don't know the answer yet. Until we understand the data with the simplest possible models, we don't really have any handle on what relevant complexity is.



...



**Footnotes**



\[1\] I think that physics was lucky relative to economics in its search for better and better understanding in more than one way. I've talked about one way extensively [before](http://informationtransfereconomics.blogspot.com/2015/09/whats-wrong-with-dani-rodriks-view-of.html) (our intuitions about the physical universe evolved in that physical universe, but we did not evolve to understand e.g. interest rates). More relevant to the discussion here is that physics, chemistry, and biology were also lucky in the sense that we could not see the underlying degrees of freedom of the system (particles, atoms, and cells, respectively) while the main organizing theories were being developed. Planck couldn't see the photons, so he didn't have strong preconceived notions about them. Economics may be suffering from "can't see the forest for the trees" syndrome. The degrees of freedom of economic systems are readily visible (humans) and we evolved to have a lot of preconceptions about them. As such, many people think that macroeconomic systems must exhibit the similar levels of complexity or need to be built up from complex agents ‒ or worse, effects need to be expressed in terms of a human-centric story. Our knowledge of humans on a human scale forms a prior that biases against simple explanations. However, there is also the problem that there is insufficient data to support complex explanations (macro data is uninformative for complex models, aka the identification problem). This puts economics as a science in a terrible position. Add to that the fact that money is more important to people's lives than quantum mechanics and you have a toxic soup that makes me surprised there is any progress.
