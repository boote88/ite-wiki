---
title: "What does $E_{t} \\pi_{t+1}$ mean?"
date: 2014-12-08T18:38:00.000-08:00
updated: 2014-12-08T18:38:17.396-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/12/what-does-et-pit1-mean.html
---

![Figure from NY Fed [pdf] modified using excerpts from Lena Nyadbi's dayiwul lirlmim barramundi.](media/expectations.png)



Sorry for the $\LaTeX$ in the title but I'm currently trying to decipher some DSGE models and there is a lack of a clear answer in various economics papers as to what e.g. the term




[pdf](http://www.socsci.uci.edu/~fmilani/survey.pdf)

> The expectations are typically modeled as being formed according to the rational expectations hypothesis. The notation $E_{t}$ in the model denotes model-consistent rational expectations, i.e., the mathematical conditional expectation based on time-t information set and derived from the model ... itself.






Are economists embarrassed to have terms from the future in their equations so they invent a new notation that says "oh, no, this term isn't really future inflation in our model that's trying to predict the future"? Now that's a bit uncharitable and this is really (where the vertical bar means evaluated with/at)





where $\sigma^{i}_{t+1}$ is whatever random process(es) or shocks that generate the fluctuations (in the original RBC model this is TFP). I personally like that notation because it makes the rational expectations assumption $\sigma^{i}_{t+1} = 0$ explicit. The best notation would probably be (in fact, has been used in the past)

$$<br />
\pi^{E}_{t+1} <br />
$$



where the $E_{t}$ represents just a label for whatever model of expectations you are using -- as there are different models of expectations besides rational expectations. For example, as best I can tell, the [model independent expectations](http://informationtransfereconomics.blogspot.com/2014/08/zen-koan-inflation-targeting.html) that happen in e.g. market monetarism where the central bank, if credible, can target any price level path (see e.g. [Nick Rowe here](http://worthwhile.typepad.com/worthwhile_canadian_initi/2014/12/principal-agent-problems-and-level-path-targeting.html)) it chooses look like this





where $\Pi (t)$ is a price level path function that sets the price level for each time period $t$. You could get fancy here and have the expectations follow a smooth path over more than a single time period to get back on track (mechanisms like sticky prices could slow adjustment from any given shock).



One issue with this model is that it sometimes seems to be used to go the wrong way. [David Beckworth](http://macromarketmusings.blogspot.com/2014/08/about-fed-not-trying-hard-enough-to-hit.html) has said (paraphrasing) "Yes, the central bank may say that the price level has path $\Pi_{1} (t)$, but really it has path $\Pi_{2} (t)$" where empirical values $\pi_{t}$ are used to infer $\Pi_{2} (t)$. The specific issue with this is that a path $\Pi_{2} (t)$ that matches up with empirical data likely exists for pretty much any model. The inferred path $\Pi_{2} (t)$ becomes a universal fudge factor that instead of explaining the empirical data decouples your theory from the empirical data.



Neither of these views escape the fact that a potentially rapidly changing (and possibly counterfactual) future \[1\] is directly coupled to an otherwise concrete theory. Now this isn't necessarily incorrect per se -- maybe things really are that uncertain and subjective. Who knows? But it gets weirder. Let's hand the floor over to [Scott Sumner](http://econlog.econlib.org/archives/2014/03/did_the_rate_in.html):

> At first glance my hypothesis \[that the (future) interest rate increase of 2015 caused the Great Recession\] seems absurd for many reasons, primarily because effect is not suppose to precede cause. So let me change the wording slightly, and suggest that expectations of this 2015 rate increase caused the Great Recession. Still seems like a long shot, but it's actually far more plausible than you imagine (and indeed is consistent with mainstream macro theory.)

Yes, this is totally consistent with mainstream macro -- the two equations above show how information (and changing information) about the future can potentially propagate backwards into the past. All you need to do is couple a $t+1$ term to a $t$ term. That may be why economists sheepishly write those $E_{t}$ terms.



But I have an additional critique beyond the basic structure of expectations-based macroeconomic theories that might seem a bit strange and it's related to the causality problems with Sumner's hypothesis. What keeps expectations in the future? What prevents expectations of $\pi_{t+1}$ from becoming the value of $\pi_{t}$? What keeps the dreamtime from becoming all time? \[2\]



In a sense, expectations can travel from a point the future to the present instantaneously -- a kind of temporal 'action at a distance' \[3\]. There are two things that appear to stop this in macro models:

1.  **Sticky prices/wages**: the empirically observed fact that some prices are slow to change
2.  **Uncertainty**: because the future is uncertain, the full impact of expectations is reduced

Interestingly, both of these ideas have interpretations in terms of [entropic forces](http://informationtransfereconomics.blogspot.com/2014/10/wage-stickiness-is-entropic-force.html). Prices are sticky because the price distribution cannot spontaneously organize itself (destroy uncertainty information about the microstates) in a way that allows prices to change and the very definition of an entropic force is a force that serves to preserve or restore uncertainty about the microstate (increase entropy).



Can we therefore interpret the information transfer model as a model of economic dreamtime? In the information transfer model, we assume all possible microstates consistent with current macro observations are not only possible, but equally probable. That includes all possible future paths of the price level. Is modeling a macroeconomy with expectations no different than assuming you know nothing about how macroeconomics works?



With expectations, we decouple the the bulk of the DSGE model (the concrete theory) from the data. Maybe that is a good thing, and instead of the various boxes in the diagram at the top of this post and the blob of economic dreamtime expectations that includes all possible futures and the empirical data all we need is the blob (which we model by assuming ignorance of what it is) and the empirical data. The information transfer model is the model of expectations that instantly propagates expectations of the future to the present and completely dominates the concrete theory.





\[1\] I like to imagine it visually as aboriginal dreamtime paintings.

\[2\] I think the dreamtime metaphor is especially useful here because dreamtime represents the past and future holistically.

\[3\] It's funny that action at a distance is associated with a violation of special relativity (the constant speed of light) which is in turn associated with causality violation.
