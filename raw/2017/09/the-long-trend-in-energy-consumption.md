---
title: The long trend in energy consumption
date: 2017-09-15T14:17:00.002-07:00
updated: 2017-09-15T14:17:25.507-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/09/the-long-trend-in-energy-consumption.html
---

I came across [this](http://www.debtdeflation.com/blogs/2016/08/19/incorporating-energy-into-production-functions/) from Steve Keen on physics and economics, where he says:

> _... both \[neo­clas­si­cal economists and Post Keynesians\] ignore the shared weakness that their models of production imply that output can be produced without using energy—or that energy can be treated as just a form of capital. Both statements are categorically false according to the Laws of Ther­mo­dy­nam­ics, which ... cannot be broken._

He then quotes Eddington, ending with "But if your theory is found to be against the second law of thermodynamics I can give you no hope; there is nothing for it but to collapse in deepest humiliation." After this, Keen adds:

> _Arguably therefore, the production functions used in economic theory—whether spouted by mainstream Neoclassical or non-orthodox Post Keynesians—deserve to "collapse in deepest humiliation"._

First, let me say that the second law of thermodynamics applies to closed systems, which the Earth definitely isn't (it receives energy from the sun). But beyond this, I have no idea what Keen is trying to prove here. Regardless of what argument you present, a Cobb-Douglas function cannot be "false" according to thermodynamics because it is just that: _a function_. It's like saying the Riemann zeta function violates the laws of physics.



The Cobb-Douglas production functions also do not imply output can be produced without energy. The basic one from the Solow model implies labor and capital are inputs. Energy consumption is an implicit variable in both labor and capital. For example, your effective labor depends on people being able to get to work, using energy. But that depends on the distribution of firms and people (which in the US became very dependent on industrial and land use policy). That is to say





where $f_{1}$ and $f_{2}$ are complex functions of energy and time. Keen is effectively saying something equivalent to: "Production functions ignore the strong and weak nuclear forces, and therefore violate the laws of physics. Therefore we should incorporate nucleosynthesis in our equations to determine what kinds of metals are available on Earth in what quantities." While technically true, the resulting model is going to be intractable.



The real question you should be asking is whether that Cobb Douglas function fits the data. If it does, then energy must be included implicitly via $f_{1}$ and $f_{2}$. If it doesn't, then maybe you might want to consider questioning the Cobb-Douglas form itself? Maybe you can come up with a Cobb-Douglas function that includes energy as a factor of production. If that fits the data, then great! But in any of the cases, it wasn't because Cobb-Douglas production functions without explicit energy terms violate the laws of physics. They don't.



However, what I'm most interested in comes in at the end. Keen grabs a graph from this [blog post by physicist Tom Murphy](https://dothemath.ucsd.edu/2012/04/economist-meets-physicist/) (who incidentally is a colleague of a friend of mine). Keen's point is that maybe the Solow residual $A(t)$ is actually energy, but doesn't actually make the case except by showing Murphy's graph and waving his hands. I'm actually going to end up making a better case.



Now the issues with Murphy's post in terms of economics were pretty much [handled already by Noah Smith](http://noahpinionblog.blogspot.com/2012/11/murphys-law.html). I'd just like to discuss the graph, as well as note that sometimes even physicists can get things wrong. Muphy fits a line to a log plot of energy consumption with a growth rate of 2.9%. I've put his line (red) along with the data (blue) on this graph:



![](<media/simple dynamic equilibrium test -energy- 1.png>)

Ignore any caveats about measuring energy consumption in the 17th century and take the data as given. Now immediately we can ask a question of Murphy's model: energy consumption goes up by 2.9% per year regardless of technology from the 1600s to the 2000s? The industrial revolution didn't have any effect?



As you can already see, I tried the [dynamic equilibrium model](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html) out on this data (green), and achieved a pretty decent fit with four major shocks. They're centered at 1707.35, 1836.93, 1902.07, and 1959.69. My guess is that these shocks are associated with the industrial revolution, railroads, electrification, and the mass production of cars. YMMV. Let's zoom in on the recent data (which is likely better) \[1\]:



![](<media/simple dynamic equilibrium test -energy- 3.png>)

Instead of Murphy's 2.9% growth rate that ignores technology (and gets the data past 1980 wrong by a factor of 2), we have a equilibrium growth rate of 0.5% (which incidentally is about half the US population growth rate during this period). Instead of Muphy's _e_\-folding time of about 33 years, we have an _e_\-folding time of 200 years. Muphy uses the doubling time of 23 years in his post, which becomes 139 years. This pushes boiling the Earth in 400 years (well, at a 2.3% growth rate per Murphy) to about 1850 years.



Now don't take this as some sort of defense of economic growth regardless of environmental impact (the real problem is global warming which is a big problem well before even that 400 year time scale), but rather as a case study where your conclusions depend on how you see the data. Murphy sees just exponential growth; I see technological changes that lead to shocks in energy consumption. The latter view is amenable to solutions (e.g. wind power) while Murphy thinks alternative energy isn't going to help \[2\]. 



Speaking of technology, what about Keen's claim that total factor productivity (Solow residual) might be energy? Well, I [checked out some data from John Fernald](http://economistsview.typepad.com/economistsview/2011/04/about-that-tfp-stagnation.html) at the SF Fed on productivity (unfortunately I couldn't find the source so I had to digitize the graph at the link) and ran it through the dynamic equilibrium model:



![](<media/simple dynamic equilibrium test -energy- tfp.png>)

Interestingly the shocks to energy consumption and the shock to TFP line up almost exactly (TFP in 1958.04, energy consumption in 1959.69). The sizes are different (the TFP shock is roughly 1/3 the size of the energy shock in relative terms), and the dynamic equilibria are different (a 0.8% growth rate for TFP). These two pieces of information mean that it is unlikely we can use energy as TFP. The energy shock is too big, but we could fix that by decreasing the Cobb-Douglas exponent of energy. However, we need to **_increase_** the Cobb-Douglas exponent in order to match the growth rates making that already-too-big energy shock even bigger.





But the empirical match up between TFP and the energy shock in time is intriguing \[3\]. It also represents an infinitely better case for including energy in production functions than Keen's argument that they violate the laws of thermodynamics.



...

**Footnotes:**


\[1\] Here is the derivative (Murphy's 2.9% in red, the dynamic equilibrium in gray and the model with the shock in green):



![](<media/simple dynamic equilibrium test -energy- 4.png>)

\[3\] Murphy actually says his conclusion is "independent of technology", but that's only true in the worst sense that his conclusion **_completely ignores_** technology. If you include technology (i.e. those shocks in the dynamic equilibrium), the estimate of the equilibrium growth rate falls considerably.





\[2\] It's not really that intriguing because I'm not sure TFP is really a thing. [I've shown that if you look at nominal quantities](http://informationtransfereconomics.blogspot.com/2016/09/the-kaldor-facts.html), Solow's Cobb-Douglas production function is an excellent match to data with a constant TFP. There's no TFP function to explain.
