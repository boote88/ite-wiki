---
title: "Tractability for tractability's sake?"
date: 2018-04-23T16:00:00.000-07:00
updated: 2018-04-24T00:26:45.814-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2018/04/tractability-for-tractabilitys-sake.html
---

![](<media/brownian PPF pic.png>)



Beatrice Cherrier has [a great blog post](https://beatricecherrier.wordpress.com/2018/04/20/what-price-did-economists-pay-for-tractability/) ([and follow up](https://beatricecherrier.wordpress.com/2018/04/20/how-tractability-has-shaped-economic-knowledge-a-follow-up/)) about the (macro)economic methodologies chosen for reasons of tractability and their continued use and influence on theories and models. A couple of core examples are the representative agent and log-linearization. The latter is just a very good numerical approximation of the type made all the time in science and engineering (and [Eggertsson and Singh show](http://www.nber.org/papers/w22784) that it is in fact a good approximation), but the former is more complex in its ramifications.



Sure, the representative agent makes some models computationally tractable but it also abstracts the concept of exchange fundamental to economics \[1\], and prohibits the study of economic inequality. More dangerously, the representative agent is a bit of sleight of hand that gets around the [SMD theorem](https://en.wikipedia.org/wiki/Sonnenschein%E2%80%93Mantel%E2%80%93Debreu_theorem) (q.v. [Kirman](https://www.aeaweb.org/articles?id=10.1257/jep.6.2.117)). Cherrier politely refers to these as "aggregation problems" \[2\], but I think there are enough issues that I devoted [a chapter of my book to it](http://www.arandomphysicist.com/2017/09/a-free-version-of-book.html). In fact, most tractability choices for the microfoundations (agents) \[3\] in the case of economics (which lacks symmetry principles) cannot be assumed to map the tractable micro theory to the "true" (i.e. an accurate) macro theory. [I tell this story in more detail in an imagined "dialog"](https://informationtransfereconomics.blogspot.com/2016/03/the-irony-of-microfoundations.html) with a microfoundations fundamentalist.



As a physicist and in my work building simulations of systems, I've encountered and made lots of choices in order to make models tractable. A famous example, the [Monte Carlo method](https://en.wikipedia.org/wiki/Monte_Carlo_method), was designed to break the intractability of complicated integrals; different methods work better for different cases \[4\]. However it is important to understand that there are only a few ways to justify tractability choices: 1) directly showing the choices themselves are mathematically justified (e.g. the log-linearization above, Monte Carlo and the work in footnote \[4\]), 2) showing the resulting model is [empirically useful](https://informationtransfereconomics.blogspot.com/2016/07/ceteris-paribus-and-method-of-nascent.html)/accurate, 3) for pedagogical purposes \[5\], or 4) it is the first time you are looking at this model you're making some educated guesses \[6\]. No other reason is justifiable from a scientific perspective \[7\]. 



It is important to recognize that _tractability itself_ is not a sufficient justification for making tractability assumptions. Saying you assume a representative agent to make a model tractable just shifts the burden to the model — what makes this model so important that it needs to be made tractable? Is it empirically accurate when made tractable? When tractability itself is given as a justification — tractability for tractability's sake — that's usually a sign that the theory (model) is being seen through the lens of bias. _This theory is too important to not obtain results from it_ \[8\]_._ Important here could mean politically — national politics because of macro's topics, but even just academic politics. Whatever the reason, [it is not a scientific one](https://informationtransfereconomics.blogspot.com/2017/04/is-economics-scientific-short-play-in.html). And that's what makes Cherrier's questions about the influence of tractability assumptions so interesting from a history of economic thought perspective. Since so few macro models are empirically accurate, rendering the scientific reasons for making them moot, tractability assumptions often could be a window on motivations other than science \[9\].



...



**Footnotes:**



\[1\] While I find this hilarious in a discipline devoted to the study of transactions between two or more people, it is not as problematic mathematically as it is similar to looking at a [mean field approximation](https://en.wikipedia.org/wiki/Mean_field_theory) with a "[dressed particle](https://en.wikipedia.org/wiki/Dressed_particle)". In the language of [Wilson renormalization](https://en.wikipedia.org/wiki/Kenneth_G._Wilson#Work), one can "integrate out" the microeconomic scale interactions, replacing it with a new effective degree of freedom (agent). The unfortunate part about macro's representative agent assumption is that it is just that: instead of being careful handling the micro interactions, it's just **_assumed_**. In a discussion with Jo Michell [I go through in quite a bit more mathematical detail](https://informationtransfereconomics.blogspot.com/2016/11/integrating-out.html) of actually integrating out the micro details of heterogeneous agents. The other aspect of not making that 



\[2\] I immediately thought of the scene in _The Big Lebowski_ where a man in an iron lung is said to have "health problems".



\[3\] I find the regularity with which agent-based modeling (ABM) is proffered as a solution to the "unrealistic assumptions" of DSGE models, but then goes on to ignore the fact that the ABM made different but still unrealistic assumptions in order to make the model tractable. For example, [this](https://informationtransfereconomics.blogspot.com/2016/12/why-dont-you-just-show-us-why-its-better.html).



\[4\] I picked up [this issue of _Scientific American_](https://www.scientificamerican.com/magazine/sa/1994/01-01/) when I was in high school. [This article \[pdf\]](http://www.cs.virginia.edu/~robins/Breaking_Intractability.pdf) on tractability in simulations strongly influenced me over the years, including its idea about an "incompleteness theorem" for computation asking whether some questions might be intractable for any feasible amount of computational resources making their answers unknowable. I have a hunch that in the real world when these macro scale computations with micro scale degrees of freedom become intractable, new "emergent" macro degrees of freedom arise that are tractable. I discussed the issues around this at length when [I talked about Erik Hoel's causal emergence](https://informationtransfereconomics.blogspot.com/2017/06/emergence-and-over-selling-information.html).



\[5\] There are some artificial "toy" models in physics that are set up because they are more tractable for students. But it should always be clear that [toy models that demonstrate principles come **_after_** empirical successes of those principles](https://informationtransfereconomics.blogspot.com/2017/02/qualitative-economics-done-right-part-2a.html).



\[6\] Typically, these kind of tractability assumptions are made in the privacy of your own notebook, and only ever get published if they lead to an empirically accurate model.



\[7\] I have on occasion encountered the "but we need _**some**_ answer" defense: a model is made tractable via possibly dubious assumptions in order to give some answer in the face of uncertainty. E.g. one could think of creating a model made tractable through some _ad hoc_ assumptions to justify some course of policy in the midst of a global financial crisis. While this kind of decisiveness is emblematic of leadership (frequently used as a story device on _Star Trek_, where e.g. Captain Picard had to make a decision on the basis of speculative theory) and can be rational, it should be made clear that this is not a _**scientific**_ approach.



\[8\] This is closely related to: "[your likelihood ratio tests are rejecting too many good models](http://delong.typepad.com/sdj/2011/10/calibration-and-econometric-non-practice.html)".



\[9\] These are not necessarily nefarious; it could be as simple as really believing a theoretical approach will eventually yield results. But given the topics macroeconomics covers, there are countless ways for ideology to enter — especially given the lack of empirical support for a lot of macro models.
