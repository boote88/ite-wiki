---
title: The basic asset pricing equation as a maximum entropy condition
date: 2015-05-27T19:00:00.000-07:00
updated: 2015-09-18T14:21:51.613-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/05/the-basic-asset-pricing-equation-as.html
---

[Commenter LAL](http://informationtransfereconomics.blogspot.com/2015/05/frameworks-and-bohr-model-analogy.html?showComment=1432616783050#c1908048158619316583) has brought up the basic asset pricing equation a couple of times, and so I had a go at looking at it as a maximum entropy/information equilibrium model. Turns out it works out. In [Cochrane's book](http://www.amazon.com/Asset-Pricing-John-H-Cochrane/dp/0691121370) (updated with link) the equation appears as:






Where $p_{t}$ is the price at time $t$, $c_{t}$ is consumption at time $t$, $u$ is a utility function, and $\beta$ is a future discount factor. Now $x_{t}$ is also the price at time $t$ (although it's called the payoff) and of course there is the [funny business](http://informationtransfereconomics.blogspot.com/2014/12/what-does-et-pit1-mean.html) of the $E$ that essentially says all the terms at a time $t+1$ exist only in the minds of humans (and turns an $x$ into a $p$). Rational expectations is the assumption that the $E$ is largely meaningless on average (i.e. approximately equal to the identity function).



As a physicist, I'm not particularly squeamish about the future appearing in an equation (or [time dropping out](http://en.wikipedia.org/wiki/Wheeler%E2%80%93DeWitt_equation) of the model altogether), so I will rewrite equation (0) as:





It turns out much of the machinery is the same as [the Diamond-Dybvig model](http://informationtransfereconomics.blogspot.com/2015/04/diamond-dybvig-as-maximum-entropy-model.html), so I'll just adapt the beginning of that post for this one.



The asset pricing equation is originally a model of consumption in two time periods, but we will take that to be a large number of time periods (for reasons that will be clear later). Time $t$ will be between 0 and 1.



Let's define a utility function $U(c_{1}, c_{2}, ...)$ to be the information source in the markets






for $i = 1 ... n$ where $MU_{c_{i}}$ is the marginal utility (a detector) for the consumption $c_{i}$ in the $i^{th}$ period (information destination). We can immediately write down the main information transfer model equation:






Solving the differential equations, our utility function $U(c_{1}, c_{2}, ...)$ is






Where the $C_{i}$ and $a$ are constants. The basic timeline we will consider is here:



![](<media/itm diamond dybvig timeline.png>)

Period $i$ is some "early" time period near $t = 0$ with consumption $c_{i}$ while period $j$ is some "late" time period near $t = 1$ with consumption $c_{j}$. We'll only be making changes in these two time periods. The "relevant" (i.e. changing) piece of the utility function is (taking a logarithm):





where all the various $C_{i}$'s, $\alpha_{i}$'s and $a$ ended up in $\log U_{0}$.



Now the derivation of the asset pricing equation sets up a utility maximization problem where normal consumption in period $i$ (called $e_{i}$) is reduced to purchase $\xi$ of some asset at price $p_{i}$, and added back to consumption in period $j$ at some new expected price $p_{j}$. So we have:








Normally, you'd plug these into the utility equation (2), and maximize (i.e. take a derivative with respect to $\xi$ and set equal to zero). The picture appears in this diagram (utility level curves are in gray):



![](<media/asset pricing as entropy.png>)

The change in the amount $\xi$ of the asset held represents wiggling around the point $(e_{i}, e_{j})$ along a line with slope defined by the relative size of the prices $p_{i}$ and $p_{j}$ to reach the point labeled with an 'x': the utility maximum constrained to the light blue line.



Instead of doing that, we will use entropy maximization to find the 'equilibrium'. In that case, we can actually be more general, allowing for the case that e.g. you don't (in period $j$) sell all of the asset you acquired in period $i$ -- i.e. any combination below the blue line is allowed. However, if there are a large number of time periods (a high dimensional consumption space), the most probable values of consumption are still near the blue line (more on that [here](http://informationtransfereconomics.blogspot.com/2015/04/diamond-dybvig-as-maximum-entropy-model.html), [here](http://informationtransfereconomics.blogspot.com/2015/03/utility-in-information-equilibrium-model.html)). Yes, that was a bit of a detour to get back to the same place, but I think it is important to emphasize the generality here.



If the states along the blue line are all equally probable (maximum entropy assumption), then the average state will appear at the midpoint of the blue line. I won't bore you with the algebra, but that gives us the maximum entropy equilibrium:






If we assume we have an "optimal portfolio", i.e we are already holding as much of the asset as we'd like, we can take $\xi = 0$, which tells us $e_{k} = c_{k}$ via the equations (3) above, and we obtain the condition:






Not quite equation (1), yet. However, note that






So we can re-write (4) as (note that the $j$, i.e. the future, and $i$, i.e. the present, flip from numerator and denominator):






Which is formally similar to equation (1) if we identify $\beta \equiv \alpha_{i}/\alpha_{j}$. You can stick the $E$ and brackets around it if you'd like.



I thought this was pretty cool.



Now just because you can use the information equilibrium model and some maximum entropy arguments to arrive at equation (5) doesn't mean equation (1) is a correct model of asset prices -- much like how you can build the IS-LM model and the quantity theory of money in the information equilibrium framework, this is just another model with a information equilibrium description. Actually equation (4) is more fundamental in the information equilibrium view and basically says that the condition you'd meet for the optimal portfolio is simply that the ratio of the current to expected future consumption is equal to the ratio of the current to the expected price of that asset. Essentially if you think the price of some asset is going to go up 10%, you will adjust your portfolio so your expected future consumption goes up by 10%.
