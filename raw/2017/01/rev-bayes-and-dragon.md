---
title: Rev. Bayes and the Dragon
date: 2017-01-24T13:30:00.000-08:00
updated: 2019-11-01T18:51:45.369-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/01/rev-bayes-and-dragon.html
---

![Rev. Bayes is no St. George.](media/645px-Bernat_Martorell_-_Saint_George_Killing_the_Dragon_-_Google_Art_Project.jpg)



[Francis Diebold brought up](http://fxdiebold.blogspot.com/2017/01/bayes-stifling-creativity.html) Bayesian versus frequentist [interpretations of probability](https://en.wikipedia.org/wiki/Probability_interpretations) the other day and and I think Noah Smith retweeted it. It's actually a pretty funny framing of the argument. Diebold quotes a Bayesian econometrician who visited him in his office:

> _There must be something about Bayesian analysis that stifles creativity.  It seems that frequentists invent all the great stuff, and Bayesians just trail behind, telling them how to do it right._

I'm going to take issue with the last clause about doing it right. Now I've touched on this "debate" [before](http://informationtransfereconomics.blogspot.com/2016/04/entropy-and-uncertainty.html), and I don't think I could have put it more perfectly than I put it then:

> _I've never been one to get into the Bayesian-frequentist argument, which much like the interpretations of quantum mechanics, seem to be a waste of my time (and are basically the same underlying issue). That it's a waste of my time does not imply it is a waste of your time if you happen to be a masochist who's into philosophical arguments that never go anywhere._

The thing is that there really isn't such a person as a "frequentist" who excludes Bayesian methods. At least I've never heard of such a person. I am fine with "frequentist" interpretations (which are just [effective theories](https://en.wikipedia.org/wiki/Effective_theory)) as well "Bayesian" methods (which are just math). The issue as I see it is that there is just a subculture consisting of weird strict Bayesians versus everyone else.



When I read Diebold's post and Chris House's paper that he links called "Understanding Non-Bayesians", I thought I'd indulge my inner masochist and try to figure out exactly what Bayesians are on about.



The first thing to note is that Bayesian math is perfectly valid. The Bayesian approach is incredibly useful if you are updating pre-existing probabilities derived from older data using new data, or where you have a theoretical model of the prior probability. At least, that is how us "non-Bayesians" view it.



I think this probably falls under Chris House's description:

> _\[To non-Bayesians\] \[t\]he distinguishing feature of Bayesian inference then appears to be that Bayesians give explicit attention to non-flat priors that are based on subjective prior beliefs._

As I mentioned, I don't think the priors are always subjective. They can come from data that's been collected before or theoretical arguments. The weirdness (for me) comes in when the priors are subjective. What does it mean for a theory parameter to have a prior probability distribution before any data has been collected?



An excellent illustration of strict Bayesian weirdness is in a post I found in researching this topic called "[Are you a Bayesian or a Frequentist? (Or Bayesian Statistics 101)](http://www.behind-the-enemy-lines.com/2008/01/are-you-bayesian-or-frequentist-or.html)". In the example worked out, a possibly unfair coin is flipped 14 times, coming up heads 10 times. The not "weird strict Bayesian" approach is to say 10/14 is an estimate of the unfair coin's probability _p_ of coming up heads. The weird strict Bayesian approach is to stick in a prior probability distribution of that probability distribution parameter: _P(p)_.



Now _P(p)_ totally makes sense if you've encountered this coin before, or have some theoretical model of the center of mass of the coin (e.g. based on manufacturing processes). Even a so-called "frequentist" would approach the problem in exactly this way because [Bayes' theorem](https://en.wikipedia.org/wiki/Bayes'_theorem) is exactly what it says it is: a theorem.



However, imposing a non-uniform _P(p)_ out of [mathematical convenience](https://en.wikipedia.org/wiki/Conjugate_prior) or other subjective criteria effectively just increases the number of parameters in your model to include the parameters of the prior distribution. In the example, a [beta distribution](https://en.wikipedia.org/wiki/Beta_distribution) is used so now our model has two parameters (_α_ and _β_ giving us the distribution of _p_) instead of just one (_p_). If _α_ and _β_ summarize earlier data or our theoretical model gives us e.g. functions _α(x)_ or _β(x)_ of some parameter _x_ (e.g. location of the center of mass), that's a different story. However, if you just posit a beta distribution then you're just adding parameters — which should be judged on information criteria like the [AIC](https://en.wikipedia.org/wiki/Akaike_information_criterion). Adding a non-flat Bayesian prior distribution **_actually makes the AIC worse_** in the coin example above unless you collect a few dozen more data points. There is also the problem of what _P(p)_ even means if it is not derived from previous data or a theoretical model.



Chris House responds to this argument with _tu quoque_:

> _Though frequentist data analysis makes no explicit use of prior information \[ed. not true per above\], good applied work does use prior beliefs informally even if it is not explicitly Bayesian. Models are experimented with, and versions that allow reasonable interpretations of the estimated parameter values are favored. Lag lengths in dynamic models are experimented with, and shorter lag lengths are favored if longer ones add little explanatory power. These are reasonable ways to behave, but they are not “objective”._

In physics we have a heuristic we call "[naturalness](https://en.wikipedia.org/wiki/Naturalness_\(physics\))" with respect to theory parameters. However it is important to note that naturalness would never be used as a prior probability in estimating a parameter's likelihood, but rather as a rhetorical device hinting at a possible problem with the model. For example, the strong force is many orders of magnitude stronger than gravity. Physicists take that to mean there is probably something going on. We did not, however, incorporate a prior probability that the ratio should be natural in estimating the strengths of those forces.



Long lag lengths in House's hypothetical economic model that performs well against the empirical data (already requiring suspension of disbelief) might be "unnatural" based on the time scales in the theory (another thing economists [haven't come to terms with](http://informationtransfereconomics.blogspot.com/2015/11/on-limits.html)), but that does not mean we should use that information to construct a prior that emphasizes shorter lags \[1\].



I would like to point out a nice concise point House makes:

> _A Bayesian perspective makes the entire shape of the likelihood in any sample directly interpretable, whereas a frequentist perspective has to focus on the large-sample behavior of the likelihood near its peak._

This is basically true, but also illustrates the issues with calling this "objective". The shape of that likelihood away from the peak is strongly dependent on the tails of the prior probability distribution, and the tails of probability distributions are notoriously hard to estimate. That is to say the Bayesian perspective makes the entire shape interpretable, but also strongly model-dependent and highly uncertain \[2\]. The so-called "frequentist" perspective is the practical one you should have: don't trust likelihoods except when you have large samples and then only near the peak. The rest of a probability distribution should come with a sign: _Here be dragons_.


...

**Update 26 January 2017**

[This post](http://informationtransfereconomics.blogspot.com/2016/01/maybe-you-should-question-your.html) on a specific prior producing a "counterintuitive" result is relevant.


...



**Footnotes:**



\[1\] This is not an argument against e.g. using the length of the available data as a prior. There you have a genuine information source (and [Nyquist](https://en.wikipedia.org/wiki/Nyquist%E2%80%93Shannon_sampling_theorem)). I use the length of the available data to discount a lot of theories from [Steve Keen's nonlinear models](http://informationtransfereconomics.blogspot.com/2016/10/keen-chaos-and-equilibrium.html) to [Kondratiev waves](https://en.wikipedia.org/wiki/Kondratiev_wave) and [Minksy-like theories](https://en.wikipedia.org/wiki/Minsky_moment). Again, this is a rhetorical argument and I wouldn't compute a prior probability.



\[2\] This makes me think of the strange things that arise when economists talk about expectations at infinity ([here](http://informationtransfereconomics.blogspot.com/2016/04/angels-dancing-at-end-of-time.html), [here](http://informationtransfereconomics.blogspot.com/2015/11/temporal-shapes-of-discount-factors-and.html)) ‒ much like the tails of probability distributions, there be dragons in the infinite future.
