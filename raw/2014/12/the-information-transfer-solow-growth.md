---
title: The information transfer Solow growth model is remarkably accurate
date: 2014-12-04T19:51:00.000-08:00
updated: 2014-12-05T12:24:01.568-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/12/the-information-transfer-solow-growth.html
---

I wanted to jump in (uninvited) on this conversation (e.g. [here](http://macromarketmusings.blogspot.com/2014/12/are-we-mismeasuring-productivity-growth.html), [here](http://delong.typepad.com/sdj/2014/12/over-at-equitable-growth-cato-institute-economic-growth-conference-panel-i.html)) about [total factor productivity](http://en.wikipedia.org/wiki/Total_factor_productivity) (TFP, aka [phlogiston](http://informationtransfereconomics.blogspot.com/2014/02/phlogiston-economics-is-information.html)) using some previous work I've done with [the information transfer model](http://informationtransfereconomics.blogspot.com/2014/05/the-solow-growth-model-and-information.html) and the Solow growth model.



In using the Solow growth model, economists assume the Cobb-Douglas form





as well as assume $\alpha + \beta = 1$ to enforce [constant returns to scale](http://en.wikipedia.org/wiki/Returns_to_scale) and then assign the remaining variation to $A$, the Solow residual aka TFP.



The conversation linked at the top of this post is then about why TFP seems to have slowed down (e.g. the Great Stagnation or whatever your model is). This is all a bit funny to me because it is effectively asking why the fudge factor is going away (if TFP is constant then $A$ is just a constant in the formula above).



Well, my intended contribution was to say "Hey, what if $\alpha$ and $\beta$ are changing?". In the information transfer model, [the Solow growth model follows from a little bit of algebra](http://informationtransfereconomics.blogspot.com/2014/05/more-on-cobb-douglas-functions-and.html) and gives us





where $\kappa_{i}$ are the information transfer indices in the markets $p_{1} : Y \rightarrow K$ and $p_{2} : Y \rightarrow L$.



The first step in looking at changing $\kappa$ is to look at constant $\kappa$ (and constant $A$). That threw me off my original intent because, well ... because the information transfer Solow growth model with constant TFP and constant $\kappa_{i}$ is a perfect fit:


![](<media/itm solow growth model -take two- 1.png>)

It's so good, I had to make sure I wasn't implicitly using GDP data to fit GDP data. Even the derivative (NGDP growth) is basically a perfect model (for economics):


![](<media/itm solow growth model -take two- 2.png>)

Of course, in the information transfer model $\kappa_{1}$ and $\kappa_{2}$ have no _a priori_ relationship to each other and in fact we have





or individually $\kappa_{1} = 1.18$ and $\kappa_{2} = 2.50$. So there aren't "constant returns to scale".



In the information transfer model, this is not a big worry. The two numbers represent the relative information entropy in the widgets represented by each input (dollars of capital and number of employees, respectively) relative to the widgets represented in the output (dollars of NGDP) -- why should those things add up to one in any combination? That is to say the values of $\kappa$ above simply say there are fewer indistinguishable types of jobs than there are indistinguishable types of capital investments so adding a dollar of capital adds a lot more entropy (unknown ways in which it could be allocated) than adding an employee. A dollar of capital is interchangeable for a lot of different things (computers, airplanes, paper) whereas a teacher or an engineer tend to go into teaching and engineering slots\*\*. Adding the former adds more entropy, and [entropy means economic growth](http://informationtransfereconomics.blogspot.com/2014/09/the-economic-combinatorial-problem.html).

PS **Added 12/5/2014 12pm PST**:  The results above use nominal capital and nominal GDP rather than the usual real capital and real output (RGDP). The results with 'real' (not nominal) values don't work as well. I am becoming increasingly convinced that "real" quantities may not be very meaningful.



\*\* This is highly speculative, but it lends itself to a strange interpretation of salaries. [Economists may make more money than sociologists](http://newmonetarism.blogspot.com/2014/12/economics-view-from-sociology.html) because they are interchangeable among a larger class of jobs; CEO's may make the largest amount of money because they are interchangeable among e.g. every level of management and probably most of the entry level positions. A less specific job description (higher information entropy in filling that job) corresponds with a bigger contribution to NGDP and hence a higher salary.
