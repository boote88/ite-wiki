---
title: "Consumption, income, and the PIH"
date: 2017-01-14T13:45:00.001-08:00
updated: 2017-03-13T09:27:15.989-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/01/consumption-income-and-pih.html
---

Noah Smith [writes about](https://www.bloomberg.com/view/articles/2017-01-12/milton-friedman-s-cherished-theory-is-laid-to-rest) the [Permanent Income Hypothesis](https://en.wikipedia.org/wiki/Permanent_income_hypothesis) (PIH) failing to match the data at Bloomberg View. He also has [a great follow up on his blog](http://noahpinionblog.blogspot.com/2017/01/the-30k-hypothesis.html) that takes the "it's good for certain cases" school of modeling to task.



On Twitter (and [in a blog post](https://everydayecon.wordpress.com/2017/01/13/on-why-it-is-important-to-distinguish-between-consumption-and-expenditures-when-testing-the-permanent-income-hypothesis/)), the paper Noah cited got some pushback because it measured _expenses_ rather than _consumption_. [Claudia Sahm](https://twitter.com/Claudia_Sahm/status/819946758310686720) got a good pwn in:

> _"because PIH is \[about\] smoothing marginal utility of consumption ... not market expenses"_

But as she also says:

> _"\[Milton\] Friedman & \[Gary\] Becker were masters at writing down unfalsifiable/irrefutable \[consumption\] models ... "_

That's the issue. If expenses do not reveal consumption utility, then that utility ‒ and thus the PIH ‒ is basically unobservable. However I think the information equilibrium model can shed a bit of light on this subject and reconcile not only the paper Noah cites, but [a paper I discussed](http://informationtransfereconomics.blogspot.com/2017/01/behavior-institutions-and-other.html) a few days ago. And we'll do it without utility.



First we'll start with [Gary Becker's "irrational agents"](http://informationtransfereconomics.blogspot.com/2015/10/gary-beckers-emergent-rational-agents.html) with an intertemporal budget constraint. As I [showed in this post](http://informationtransfereconomics.blogspot.com/2015/09/the-emergent-representative-agent-1.html), agents with random consumption will not only saturate the budget constraint (as long as there are many time periods), but will manifest consumption smoothing (i.e. the consequence of the PIH) in aggregate. And if income _I_ is in [information equilibrium](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html) with consumption _C_ (i.e. $C \rightleftarrows I$, imagine [the diagram at this link](http://informationtransfereconomics.blogspot.com/2016/11/how-do-maximum-entropy-and-information.html) with _A_ being _C_, and _B_ being _I_) then both will be approximately constant.



In the paper discussed [in this post](http://informationtransfereconomics.blogspot.com/2017/01/behavior-institutions-and-other.html), the reality is a bit more complex over the lifetime of agents. I put together a "social institution" \[4\] model where there are **_three_** approximately constant states: _childhood_, _working adult_, and _retirement_. In this view there are actually three metastable constant states of income (set by the scales zero, NGDP per capita, and Social Security, for example). I fit the a pair of logistic functions (representing the two transitions) to the income as a function of age data (the transitions are at 16.3 years and 68.1 years shown in the figure below in blue). This means $I = I(t)$ is a function of age. Now if consumption and income are in information equilibrium (IE) with information transfer (IT) index $k$, we can say







Therefore $C(t) \sim I(t)^{k}$. Fitting the IT index and the constants $I_{0}$ and $C_{0}$ to the data, we get a pretty good description of the consumption data (yellow points):



![](<media/consumption model 1.png>)

The blue points are the income data. The blue line is the logistic model. The yellow points are the consumption data. And finally, the yellow line is the IE model with the three-state logistic model (fit to the income data) as input. We find $k \sim 0.53$ \[1\]. This is important because $k &lt; 1$ means that the (fractional) change in consumption will be smaller than the (fractional) change in income since



$$<br />
\frac{dC}{C} = \; k \; \frac{dI}{I}<br />
$$


Note that the PIH could be considered to be the approximation that $k \ll 1$; in that case $C$ doesn't react to any changes in income. However, we found $k \sim 0.5$ so the PIH's scope condition is not met and the PIH isn't even an effective theory unless you are dealing with a scenario where both income and consumption are constant ‒ essentially where you want the PIH it apply (changing income), it fails. But $k &lt; 1$, so consumption does have a smaller reaction than income does in the presence of shocks. Additionally, the emergent consumption smoothing (linked above) relies on an assumption of no shocks. In the presence of shocks, the [intertemporal budget constraint](http://informationtransfereconomics.blogspot.com/2015/10/when-is-intertemporal-budget-constraint.html) is not saturated, and therefore the PIH would in general be violated.



Can we use this IT index value to explain the consumption (expense) and income data in Noah's BV post? If $k &lt; 1$, then $C(t)$ will move much less than $I(t)$, which gives us a picture that looks exactly the data Noah shows. In fact, fitting the income data \[2\] to the consumption (expense) data gives us almost the exact same IT index of $k \simeq 0.55$



![](<media/consumption model 2.png>)

Here, the yellow line is the IE model shown above with the (interpolated) income _data_ as the input function $I(t)$. Basically, consumption moves more slowly than income, so a large income shock leads to a smaller consumption shock. The PIH (if it is observable, i.e. expenses reveal consumption utility) would be the case where consumption doesn't move at all. What we have is a case somewhat between the $C = I$ case (i.e. $k = 1$) and the $C = \text{ constant}$ case (i.e. $k = 0$).



The information equilibrium model is able to capture both sets of data (lifetime consumption and consumption in the presence of shocks); it tells us that since $k \sim 0.5$ (empirically), the PIH is generally a bad approximation whenever income is dynamic (not constant). If $k$ had been closer to 0.1 or even smaller, the PIH would be a good approximation. But the $k \sim 0.5$ result means we should listen to Noah:

> _This means Friedman’s theory doesn’t just need a patch or two ‒ it needs a major overhaul._

...

**Update 15 January 2017**


[@unlearningecon is "not convinced"](https://twitter.com/UnlearningEcon/status/820589201460699136) \[3\] by fitting logistic curves to the income data above. As that step is actually incidental to the primary conclusion (that the information equilibrium model $C \sim I^{k}$ with $k \sim 0.5$ describes the data), let me do the lifetime model in the same way I did the shock model: by using an interpolation of the income data as the function $I(t)$. We obtain the same result:



![](<media/consumption model 3.png>)
...

**Footnotes**


\[1\] Also note that consumption is greater than income in in childhood, less than income as a working adult, and again greater than income in retirement.



\[2\] In this case I just used the $I(t)$ data as the model, however I could probably fit the income data [to a shock like this](http://informationtransfereconomics.blogspot.com/2015/07/updated-graphics-for-entropic-hot.html).



\[3\] Realistically, who is ever "convinced" of something which they don't already believe by anything they read on the internet ? I think the originators of the (public) internet believed it would be an open forum for the exchange of ideas. A good behavioral model would have possibly "convinced" them that all that really happens is confirmation bias and the reinforcement of priors. Ah, but who am I kidding?

\[4\] Updated 13 March 2017: Steve Randy Waldman has [a really nice blog post](http://www.interfluidity.com/v2/6770.html) about the definition of "institutions" in social theories.
