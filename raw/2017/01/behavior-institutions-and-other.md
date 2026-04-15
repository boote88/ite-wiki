---
title: "Behavior, institutions, and other modeling assumptions"
date: 2017-01-09T21:35:00.003-08:00
updated: 2017-03-13T09:26:21.202-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/01/behavior-institutions-and-other.html
---

[@Unlearningecon](https://twitter.com/UnlearningEcon) referred me [to a paper](https://www.aeaweb.org/conference/2015/retrieve.php?pdfid=67) \[pdf\] that tries to understand lifetime consumption based on a model of human behavior. Unfortunately, the model has 10+ parameters for ~ 40 data points meaning the [AIC](https://en.wikipedia.org/wiki/Akaike_information_criterion) is pretty bad (an indication of over-fitting). I challenged myself to do better and I will try to do so using an "institutional" model.



Let's say there are three "institutions" \[3\] (in physics, we might call these "states") in the culture under consideration we'll call **_childhood_**, **_working age_**, and **_retirement_**. As such, there will be two transitions that we'll take take to have some width (not every agent transitions at the same time). This gives us a model that is the sum of two [logistic functions](https://en.wikipedia.org/wiki/Logistic_function) with 7 parameters \[1\]. We'll fit these to the same data as the paper linked above.



This is the result:



![](<media/consumption by age 1.png>)



The transitions are at 25.1 and 67.6 years; the former has a width of 4.7 years, while the latter has a width consistent with zero (the actual value translates to about 51 minutes which I found entertaining ‒ you'd probably want to look deeper into that than not at all if you were publishing a paper). I did add one (hopefully uncontroversial) point: income equals zero at birth. This helps pin down the childhood-to-adulthood transition and even gives us a look at expected income for people younger than 25:



![](<media/consumption by age 2.png>)



I converted from log income to level (in thousands). The horizontal line shows full time employment at minimum wage (approximately 2000 hours at 3.35 per hour, minimum wage in 1984) as a scale reference.



My primary motivation here was not necessarily to say: _Look at me; I can do better!_ That was just my challenge to myself. My main motivation was to say that there are many ways to parse the data and different models that come out of those different "priors" are not necessarily distinguishable based on data alone. For example, you could view the institutional model as exactly a behavioral expectations model: our expectations and behavior are governed by social institutions. People in US society expect to be working between their 20s and 60s and base their consumption accordingly.



And there are even simpler models such as the [emergent consumption smoothing of random agents](http://informationtransfereconomics.blogspot.com/2015/09/the-emergent-representative-agent-1.html). This effectively fits the data to a constant, and is basically the approximation made in a lot of standard economic analysis.



At a certain level, these modeling choices are judgment calls. But on another level they represent priors we push onto the data. The criterion should come down to simplicity, and not our pre-existing feelings about what kind of models we ought to use (behavioral, nonlinear, evolutionary, institutional). Basically all claims that "economists should do _X_" or "models should include _Y_" should come alongside more agnostic and simplistic models where _X_ or _Y_ are shown to be an improvement over the simplistic explanation of the data \[2\].



**_\*  \*  \*_**



**

**Footnotes**

**



\[1\] Although one is an overall normalization degree of freedom (the scale of money) and another is used to explain the childhood state for which there is not much real data in the given dataset. The data given could actually be understood by 5 parameters. A simpler model with no transition width would have only 5 parameters including the normalization (three step functions).



\[2\] That's part of the mission statement of this blog and the information transfer framework. It represents taking that ethos to an almost ridiculous extreme where everything is built out of log-linear relationships (not exactly, but it's not a completely unfair characterization).

\[3\] Updated 13 March 2017: Steve Randy Waldman has [a really nice blog post](http://www.interfluidity.com/v2/6770.html) about the definition of "institutions" in social theories.
