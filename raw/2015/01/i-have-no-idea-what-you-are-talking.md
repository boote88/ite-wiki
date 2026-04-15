---
title: I have no idea what you are talking about
date: 2015-01-16T17:55:00.003-08:00
updated: 2015-01-19T10:19:47.430-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/01/i-have-no-idea-what-you-are-talking.html
---

By far, the most common response to the work I've been doing on this blog from people with a background in economics is that they have no idea what I am talking about. It's nice being noticed by Scott Sumner, Nick Rowe, David Glasner and Stephen Williamson, but they all have said at one time or another they don't understand what this blog is all about. At least that's better than Noah Smith's response (deleting my comments\*\*). [Mike at Free Radical](http://realfreeradical.com/2014/08/06/taking-the-people-out-of-economics/) disagreed with the philosophical approach (I am skeptical that economics can tractably model human behavior). Robin Hanson thought I was using the word 'information' in a different way than I am (in the [Shannon information entropy](http://en.wikipedia.org/wiki/Entropy_\(information_theory\)) sense, not in _[The Market for Lemons](http://en.wikipedia.org/wiki/The_Market_for_Lemons)_ or [game theory](http://en.wikipedia.org/wiki/Perfect_information) sense). I'd say the major issues are my explanatory writing skills, my background in physics (I use the word [isentropic](http://en.wikipedia.org/wiki/Isentropic_process) way too much) and the lack of formal education in economics (I have worked my way through most of Romer's [Advanced Macroeconomics](http://www.amazon.com/Advanced-Macroeconomics-McGraw-Hill-Series-Economics/dp/0073511374)_,_ but all that has helped me to do is write [the information transfer model as a DSGE model](http://informationtransfereconomics.blogspot.com/2014/12/an-information-transfer-dsge-model.html)\*\*\*).



So let me try to do another _Vox_\-style explainer post ... on the right side of the blog there are a series of posts under the heading "Information transfer economics for beginners", so those are some more resources.



**Where does the name _information transfer economics_ come from?**


It is based on the first title of [this paper](http://arxiv.org/abs/0905.0610) by Fielitz and Borchardt that I saw: _Information transfer model of natural processes: from the ideal gas law to the distance dependent redshift_. They have since changed from "information transfer" to "natural information equilibrium" and I have followed suit, more frequently referring to information equilibrium than information transfer. In that paper, Fielitz and Borchardt come up with a kind of generalized thermodynamics and connected a couple of different things in physics to information theory that hadn't been connected before. [I derived supply and demand](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html) (or at least something that looks exactly like supply and demand diagrams) from their equations assuming demand was an information source and supply was an information destination. I thought that was pretty cool, so I started a blog to see if anything more could come out of it.



**What does this have to do with information theory?**


In truth, the information theory mostly serves as a motivation for a set of equations, and then the blog is mostly about the consequences of those equations. The equations the information theory sets up are for an abstract [diffusion process](http://en.wikipedia.org/wiki/Fick%27s_laws_of_diffusion). (In [the model](http://informationtransfereconomics.blogspot.com/2013/07/a-diffusion-analogy-for-quantity-theory.html), money is like time and output is like distance.) I do sometimes go back to the information theory for insight -- for example observed prices will tend to fall below a theoretical maximum price because you can't get more information out of a signal than it contains.



**Isn't your theory just the quantity theory of money?**


Pretty much. Instead of writing $MV = PY$, I would write:








The big difference is not only that $k$ changes (yes, like velocity), but changes deterministically. The deterministic formula for $k$ comes from the underlying information theory: it is a ratio of the [Hartley information](http://en.wikipedia.org/wiki/Hartley_function) from two sets of given size. However, you can rewrite that ratio [in an interesting way using the properties of logs](http://informationtransfereconomics.blogspot.com/2014/06/money-unit-of-information-and-medium-of.html). A set $A$ has $|A|$ elements and the Hartley function is 






where the information is measured in units based on base $b$. Our deterministic $k$ above is











That's why I've called the changing $k$ the unit of account effect in the past. It represents the units which which we measure everything in economics ... and $PY$ is just NGDP. The proper money aggregate $M$ is determined empirically. It's not M2 or the monetary base. The answer turned out to be strikingly simple: physical currency.



**Wait. If it's just the quantity theory, how do you describe Japan's price level so well?**


Well, $k$ has a tendency to fall over time in economies because $M$ grows faster than NGDP (and NGDP has recessions). Eventually $k$ gets close to 1 (from above) and you have something that looks pretty much exactly like a liquidity trap.



**What about inflation expectations?**


This is where I have in the past gone full heterodox with all due respect to the field of economics. Expectations might be able to wiggle inflation around a bit, but in the end the price level comes from $k$ and $M$ through the equations above.



However, I have since lightened up on this and in fact consider one possible interpretation of the information transfer model is as information flowing from [an expected future to a realized present](http://informationtransfereconomics.blogspot.com/2014/12/how-money-transfers-information-from.html). Instead of considering all possible levels of aggregate supply and aggregate demand consistent with a given price level, we consider all possible expected futures consistent with present macro conditions. That is still different from typical expectations models in economics. A credible central bank sets an inflation target and expectations will center around that target -- it determines $\pi_{t+1}$ from a model (e.g. the central bank can hit its target). In our case, we are agnostic about how expectations are set and take the result to be the average over the entire set of expectations consistent with macro conditions -- it determines $\pi_{t+1}$ from the set of all $\pi_{t+1}$ consistent with e.g. $\pi_{t}$, $m_{t}$, etc\*\*\*\*.



This is like thermodynamics. The pressure of an ideal gas is the most likely pressure given its volume, temperature, etc. The actual value of pressure will vary -- but since there are so many molecules, the variance is small and you get a deterministic result. In the information transfer model, there are so many people with so many different inflation expectations that effectively, the final result depends entirely on how big $M$ is.



**Where does the model differ from thermodynamics?**



Probably the biggest difference is that there is no second law and in fact, a fall in entropy [is linked to recessions](http://informationtransfereconomics.blogspot.com/2014/10/coordination-costs-money-causes.html). This is where human behavior matters. Humans can coordinate themselves in a way that atoms cannot. Most of the time humans are uncoordinated (maybe an economist would say coordinated by the market here), but sometimes we panic together and that results in a recession.



**How deep does the connection with thermodynamics go?**



Really deep. In fact, there may be a way to apply [partition functions](http://informationtransfereconomics.blogspot.com/2014/06/the-macroeconomic-partition-function.html) and define an economic temperature (proportional to $1/\log M$). Secular stagnation and liquidity traps may be emergent properties of economies that don't exist for individual markets -- so no amount of models that just put together separate markets will capture these emergent properties.



**Are there more ordinary applications of this approach?**



Yes. [Here's an example of a two-good market](http://informationtransfereconomics.blogspot.com/2014/05/equilibrium-in-two-good-market.html) that basically gets the standard result. And [here's how to derive the ISLM model](http://informationtransfereconomics.blogspot.com/2013/08/deriving-is-lm-model-from-information.html).



**Additional questions?**







Footnotes:



\*\* It's his blog; he can do what he wants.

\*\*\* A neat takeaway is that the different information transfer index ($\kappa = 1/k$) limits drop out simply in the DGSE model. You get either a "liquidity trap" _inflation = constant_ ($\kappa$ = 1) or "quantity theory" _inflation = money growth rate_ ($\kappa$ = 1/2).

\*\*\*\* The $m$'s and $\pi$'s here are the log-linear versions of $M$ and $P$ such as you would see in a DSGE model.
