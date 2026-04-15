---
title: "Random agents: one tool in the toolbox"
date: 2017-09-07T15:00:00.000-07:00
updated: 2017-09-07T15:00:15.452-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/09/random-agents-one-tool-in-toolbox.html
---

Cameron Murray directed me to two papers ([links at Cameron's tweet](https://twitter.com/DrCameronMurray/status/905564326047518720)) on so-called "zero intelligence" agents (i.e. random agents) that are relevant to the work I present on this blog. I believe these papers, like Gary Becker's 1962 paper (which both cite), seem to be working within the traditional economic framework because of the terminology. I tweeted:

> Still don't like the framing: "irrational", "zero-intelligence". I prefer thinking people are "[inscrutably algorithmically complex](https://en.wikipedia.org/wiki/Algorithmic_information_theory#Precise_definitions)".

Both "irrational" and "zero-intelligence" are a judgmental comparison to agents that are "rational" or "intelligent". As I said in my tweet, I prefer to think of myself (or other economic theorist) as the one with "zero-intelligence" or at least coming from a place of complete ignorance of human behavior.



That said, [the first paper](http://www.agsm.edu.au/bobm/KER/FinalDrafts/Ladley-final.pdf) \[pdf\] "Zero Intelligence in Economics and Finance" by Dan Ladley is a great survey of the use of random agents from 1962 to 2009. [David Glasner originally pointed me to Gary Becker's 1962 paper](https://informationtransfereconomics.blogspot.com/2015/10/gary-beckers-emergent-rational-agents.html), and I used it [extensively in my book](https://www.amazon.com/dp/B0754X3PYF/ref=as_li_ss_il?ie=UTF8&linkCode=li3&tag=arandomphysic-20&linkId=79d6e4519fd861a01943a39af714600d) to argue against trying to get inside the heads of agents to tell stories. Ladley similarly sees it as opening up the possibilities of economics without rationality:

> _The Zero Intelligence approach can trace its roots to prior to the advent of agent based computational economics. The Nobel Laureate Gary Becker employed this technique in an early paper (Becker, 1962) to analyse a model of markets in which participants behaved irrationally and in some areas at random. Using this model he found that features such as the downward slope of market demand curves and the upward slope of market supply curves typically associated with rational trader behaviour arose without any individual rationality. As a consequence he was able to deduce that these features were a result of the market mechanism that governed the interaction of the traders. In effect the market was creating system level rationality._

> _Although Becker managed to demonstrate certain results of market structure using this model, little further progress was made using this approach, as even without trader strategy the model is still very difficult to analyse. It was not until individual based computational simulation techniques became available that this research area made rapid progress._

Ladley's paper continues to discuss an experiment and simulation by Gode and Sunder from 1993 that is effectively what I did [here](https://informationtransfereconomics.blogspot.com/2016/04/list-2004-field-experiments-with-random.html) (with John List's paper containing the human experiment) and [here](https://informationtransfereconomics.blogspot.com/2016/11/the-scope-of-introductory-economics.html) (in comparison with Vernon Smith's experiments) more than 20 years later.



The interesting finding (to me) of Gode and Sunder as relayed by Ladley is this:

> _Strikingly they found that markets populated by Zero Intelligence constrained traders behaved very similarly to those populated by human traders, both markets converged and achieved allocative efficiencies close to 99%. In contrast markets populated by Zero Intelligence Unconstrained traders did not converge and achieved efficiencies of approximately 90%._

The "constrained" traders were traders bounded inside the appropriate state space (opportunity set in Gary Becker's paper), where as the unconstrained ones weren't. This means you can make a case that the "economic forces" at work are more properties of this state space than the agents (which are just a mechanism to explore that state space, like an indicator dye or smoke in a wind tunnel). Again, this is a point [I've made before](https://informationtransfereconomics.blogspot.com/2015/10/economics-as-and-versus-social-science.html) and make [more extensively in my book](https://www.amazon.com/dp/B0754X3PYF/ref=as_li_ss_il?ie=UTF8&linkCode=li3&tag=arandomphysic-20&linkId=79d6e4519fd861a01943a39af714600d). (I'd also like to note that [Wissner-Gross's causal entropy](https://informationtransfereconomics.blogspot.com/2016/09/causal-entropic-forces-as-economic.html) is another constraint on the state space that makes it look like random agents are "intelligent".)



I'd like to return to a point Ladley made in my first quote from his paper, however. He mentions how progress using random agents essentially stagnated until computational resources became more widely available, the models being "very difficult to analyse". While I have made much of random agents myself, my primary work here is on the information equilibrium framework. This framework can be motivated by random agents as one way to achieve maximum entropy, but information equilibrium is more about relationships between different state spaces — regardless of how they are explored. I wrote [a brief post about this](https://informationtransfereconomics.blogspot.com/2016/11/how-do-maximum-entropy-and-information.html) that has a good diagram:



![](<media/max ent.png>)

Random agents (i.e. Maximum Entropy or MaxEnt in the figure above) are one way those state spaces are fully explored, but intelligent agents or other kinds of deterministic algorithms can also explore those state spaces (including causally random agents per Wissner-Gross). This includes inscrutably algorithmically complex agents as well.



This is to say that while random agents are a great tool, they're not the end-all and be-all of the information theory approach [which aims to develop a calculus of state spaces](https://informationtransfereconomics.blogspot.com/2017/05/explore-more-about-information.html) (and per [Fielitz and Borchardt](https://arxiv.org/abs/0905.0610), "provide shortcuts" to deal with complex systems).



**\*  \*  \***



The other paper Cameron sent me is by [Doyne Farmer _et al_](http://tuvalu.santafe.edu/~jdf/papers/science2.pdf) \[pdf\] also discusses Becker and Gode and Sunder:

> _Traditionally economics has devoted considerable effort to modeling the strategic behavior and expectations of agents. While no one would dispute that this is important, it has also been pointed out that some aspects of economics are independent of the agent model. For example, Becker showed that a budget constraint is sufficient to guarantee the proper slope of supply and demand curves, and Gode and Sunder demonstrated that if one replaces the students in a standard classroom economics experiment by zero-intelligence agents, price setting and other properties match better than one might expect. In this paper we show that this principle can be dramatically more powerful, and can make surprisingly accurate quantitative predictions._

This paper is more a specific application to financial markets. They find the state space they use for the price formation mechanism plays "a more important role than the strategic behavior of agents". However, while this is characterized as a simple model after some digging [I found the actual model description](https://arxiv.org/abs/cond-mat/0210475) and it is far from simple. I believe simple here is relative (again) to a framing in terms of rational strategic agents.



I am trying to understand this paper in more detail. However at this point I am uncertain of the connection between the theory and the conclusions made in the paper. There is a lot of discussion of theory, but the results are mostly fitting some nebulously described functions to data. As they say:



> _The nondimensional coordinates dictated by the model are very useful for understanding the average market impact function. There are five parameters of the model and three fundamental dimensional quantities (shares, price, and time), leading to only two independent degrees of freedom._



But then the paper simply posits a log-linear function with two degrees of freedom:$\phi (\omega) = K \omega^{\beta}$. Why that one? I assume because the data looks log-linear. In fact, you can recover the basic results of their paper without much more [than the information equilibrium condition](https://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html), which tells us that $\beta$ can be anything between 0 and 1 (Farmer _et al_ find $\beta \sim 0.25$ and cite Gabaix's theoretical calculation of $\beta = 0.5$). Equating orders with demand, the log price is:






so that the log difference is (for a given order size $\omega \equiv \Delta D$)






and we can identify the slope $\beta = (k - 1)/k$ in terms of the information transfer index $k$. Their finding of $\beta \sim 0.25$ corresponds to an information transfer index of $k \sim 1.3$. (Note that Gabaix's $\beta = 0.5$ means $k = 2$, which gives us the quantity theory of money in another context.) However, the information equilibrium version can allow much more to happen. For example, we can think of this [as an ensemble average](https://informationtransfereconomics.blogspot.com/2017/07/dynamic-equilibrium-and-ensembles-and.html) allowing $\langle k \rangle$ to change slowly over time (and allow e.g. different company stocks to have different values of $k$).



In any case, I plan on looking into this a bit more.
