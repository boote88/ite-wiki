---
title: Some discussion of the information transfer traffic model
date: 2015-01-13T05:00:00.000-08:00
updated: 2015-01-13T05:00:06.265-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/01/some-discussion-of-information-transfer.html
---

A coworker of mine read a couple of the posts on the blog and had some good questions (in particular on [the traffic model post](http://informationtransfereconomics.blogspot.com/2014/12/an-information-transfer-traffic-model.html)). I'll paraphrase them (potentially incorrectly) and have a go at an an answer.



_Q: Doesn't the fall from the theoretical traffic velocity in the information transfer model indicate you have the wrong model?_



A: Yes! Traffic jams are a failure of the assumption of information equilibrium. After that, all the model says is that information received is less than the information coming from the source. This may or may not be a useful insight. In economics, though, I think it is (see e.g. [here](http://informationtransfereconomics.blogspot.com/2014/05/the-effect-of-expectations-in-economics.html)).



Using a thermodynamics analogy, the information equilibrium is something like a generalized isentropic process. However thermodynamics processes don't always conserve entropy. Even in the [ideal gas at higher pressures](http://informationtransfereconomics.blogspot.com/2014/09/insights-from-non-ideal-information.html), there are inter-molecular forces to consider.



It is possible the model is wrong (or worse, trivial) for "normal traffic" (information equilibrium) as well -- there is no reason why the information equilibrium has to lead to insight into the problem. Gasses could have never behaved like ideal gasses in any reasonable regime (a plasma -- e.g. an electron gas -- never behaves like an ideal gas).



In fact, the information equilibrium traffic model is pretty trivial. It doesn't lead to any insight not available from inspection: we find there is an average velocity and sometimes the velocity could fall below that average.



However! In economics knowing that an average price exists and that recessions represent a fall away from equilibrium is real progress. So it the ability to identify the trends of macro variables during "normal times" and see "recessions". In fact, the size of the so-called [business cycle is essentially a free parameter in economics](http://informationtransfereconomics.blogspot.com/2013/10/revealing-true-business-cycles.html) so I think this represents a step forward. Imagine if traffic modelers got to define "traffic jam"?


_Q: Aren't the speeds on the road actually coordinated?_


A: It's true that the speed limit does make our speeds coordinated in the sense of all possible speeds. Everyone has their own rule. Go the speed limit, or 5 or 10 mph over or 5 mph faster than the fastest other person. Go the average speed. Some people aren't paying close attention to their speed. Sometimes you have to slow down because you are approaching another car. Sometimes there is debris or a pothole. When you put all of this together and have enough people, it starts to look random -- like a (potentially skewed) normal distribution centered somewhere near the speed limit. Isn't this just the central limit theorem ... as my coworker asked? Well yes and no. The central limit theorem is about putting together random variables drawn from different kinds of distributions -- an in a sense this is happening.



However another way to look at this is as algorithmic complexity. You could imagine a really good agent-based simulation that could come up with the set of velocities and the sequence of averages you observe given the road conditions within some error. However, this algorithm might be so complex that it is difficult to distinguish its sequence of outputs from a random sequence -- that is to say the computer program required to come up with the sequence is of the order of the length of the sequence.



This second view is what is in my head when I look at the economic problem: the agent-based model that captures macroeconomics is sufficiently complex that it is indistinguishable from randomness ... and that maximum entropy approaches (assuming any state consistent with your macroscopic observations is possible) can shed some light.



Another way to say this is that I think the _N_\-dimensional economic agent problem [is dimensionally reduced](http://informationtransfereconomics.blogspot.com/2014/06/what-if-money-was-made-of-vinegar.html) to some dimension _m << N_. This is not a scientific fact (it doesn't have to be true) -- it is an article of faith. However, if you think you can describe economics with anything besides detailed agent-based models, it is an article of faith we share.





I'd liken the information transfer model -- when information sent from the source is approximately equal to the information received at the destination -- to a saturated queuing model that obeys [Kingman's formula](http://en.wikipedia.org/wiki/Kingman%27s_formula). The assumption here is that markets are operating at [peak information processing capacity](http://informationtransfereconomics.blogspot.com/2014/08/the-meaning-of-economies-without-humans.html) most of the time. Empirically, this turns out to be a pretty good assumption.
