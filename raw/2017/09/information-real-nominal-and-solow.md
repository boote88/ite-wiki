---
title: "Information, real, nominal, and Solow"
date: 2017-09-19T16:30:00.000-07:00
updated: 2017-09-20T15:01:25.540-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/09/information-real-nominal-and-solow.html
---

[John Handley has the issue](https://jwhandley.blogspot.com/2017/09/the-g7-productivity-puzzle.html) that anyone with a critical eye has about the Solow model's standard production function and total factor productivity: it doesn't make sense once you start to compare countries or think about what the numbers actually mean.



My feeling is that the answer to this in economic academia is a combination of "it's a simple model, so it's not supposed to stand up to scrutiny" and "it works well enough for an economic model". Dietz Vollrath essentially makes the latter point (i.e. the Kaldor facts, which can be used to define the Solow production function, aren't rejected) in his pair of posts on the balanced growth path that [I discuss in this post](https://informationtransfereconomics.blogspot.com/2016/09/the-kaldor-facts.html).



I think the Solow production function represents an excellent example of how biased thinking can lead you down the wrong path; I will attempt to illustrate the implicit assumptions about production that go into its formulation. This thinking leads to the invention of "total factor productivity" to account for the fact that the straitjacket we applied to the production function (for the purpose of explaining growth, by the way) makes it unable to explain growth.



Let's start with the last constraint applied to the Cobb-Douglas production function: constant returns to scale. Solow doesn't really explain it so much as assert it in his paper:

> _Output is to be understood as net output after making good the depreciation of capital. About production all we will say at the moment is that it shows constant returns to scale. Hence the production function is homogeneous of first degree. This amounts to assuming that there is no scarce nonaugmentable resource like land. Constant returns to scale seems the natural assumption to make in a theory of growth._

> Solow (1956)

But constant returns to scale is frequently justified by "[replication arguments](https://informationtransfereconomics.blogspot.com/2017/08/the-replication-argument.html)": if you double the factory machines (capital) and the people working them (labor), you double output.



Already there's a bit of a 19th century mindset going in here: constant returns to scale might be true to a decent approximation for drilling holes in pieces of wood with drill presses. But it is **_not_** obviously true of computers and employees: after a certain point, you need an IT department to handle network traffic, bulk data storage, and software interactions.



But another reason we think constant returns to scale is a good assumption also involves a bit of competition: firms that have decreasing returns to scale must be doing something wrong (e.g. poor management), and therefore will lose out in competition. Increasing returns to scale is a kind of "free lunch" that also shouldn't happen.



Underlying this, however, is that Solow's Cobb-Douglas production function is thought of in **_real_** terms: actual people drilling actual holes in actual pieces of wood with actual drill presses. But capital is bought, labor is paid, and output is sold with nominal dollars. While some firms might adjust for inflation in their forecasts, I am certain that not every firm makes production decisions in real terms. In a sense, in order to have a production function in terms of real quantities, we must also have rational agents computing the real value of labor and capital, adjusting for inflation.



The striking thing is that if we instead think in nominal terms, the argument about constant returns to scale falls apart. If you double the nominal value of capital (going from 1 million dollars worth of drill presses to 2 million) and the labor force, there is no particular reason that nominal output has to double.



Going from 1 million dollars worth of drill presses to 2 million dollars at constant prices means doubling the number of drill presses. If done in a short enough period of time, inflation doesn't matter. In that case, there is no difference in the replication argument using real or nominal quantities. But here's where we see another implicit assumption required to keep the constant returns to scale — there is a difference over a long period of time. Buying 1000 drill presses in 1957 is very different from buying 1000 drill presses in 2017, so doubling them over 60 years is different. But that brings us back to constant returns to scale: constant returns to scale tells us that doubling in 1957 and doubling over 60 years **_both_** result in doubled output.



That's where part of the "productivity" is supposed to come in: 1957 vintage drill presses aren't as productive as 2017 drill presses given the same labor input. Therefore we account for these "technological microfoundations" (that seem to be more about engineering than economics) in terms of a growing factor productivity. What comes next requires a bit of math. Let's log-linearize and assume everything grows approximately exponentially (with growth rates $\eta$, $\lambda$, and $\kappa$). Constant returns to scale with constant productivity tells us:






Let's add an exponentially growing factor productivity to capital:






Now let's re-arrange:






Note that $1 - \alpha + \alpha' \neq 1$. We've now just escaped the straitjacket of constant returns to scale by adding a factor productivity we had to add in order to fit data _because of our assumption of constant returns to scale_. Since we've given up on constant returns to scale when including productivity, why not just add total factor productivity back in:






let's arbitrarily partition TFP to labor and capital (in half, but doesn't matter). Analogous to the capital productivity, we obtain:










In fact, if we ignore constant returns to scale and allow nominal quantities (because you're no longer talking about the constant returns to scale of real quantities) you actually get a pretty good fit with **_constant_** total factor productivity \[1\]:



![](<media/itm solow growth model -take two- 2.png>)


Now I didn't just come by this because I carefully thought out the argument against using constant returns to scale and real quantities. Before I changed my paradigm, I was as insistent on using real quantities as any economist.



What changed was that I tried looking at economics using information theory. In that framework, economic forces are about communicating signals and matching supply and demand in transactions. People do not buy things in real dollars, but in nominal dollars. Therefore those signals are going to be in terms of nominal quantities.



And this comes to our final assumption underlying the Solow model: that nominal price and the real value of a good are separable. Transforming nominal variables into real ones by dividing by the price level is taken for granted. It's true that you can always mathematically assert:






But if $N$ represents a quantity of information about the goods and services consumed in a particular year, and $Y$ is supposed to represent effectively that same information (since nominal and real don't matter at a single point in time), can we really just divide $N$ by $P$? Can I separate the five dollars from the cup of coffee in a five dollar cup of coffee? The transaction events of purchasing coffee happen in units of five dollar cups of coffee. At another time, they happened in one dollar cups of coffee. But asserting that the "five dollar" and the "one dollar" can be removed such that we can just talk about cups of coffee (or rather "one 1980 dollar cups of coffee") is saying something about where the information resides: using real quantities tell us its in the cups of coffee, not the five dollars or in the holistic transaction of a five dollar cup of coffee.



Underlying this is an assumption about what inflation is: if the nominal price is separable, then inflation is just the growth of a generic scale factor. Coffee costs five dollars today rather than the one dollar it cost in 1980 because prices rose by about a factor of five. And those prices rise for some reason unrelated to cups of coffee (perhaps monetary policy). This might make some sense for an individual good like a cup of coffee, but it is nonsense for an entire economy. GDP is 18 trillion dollars today rather than 3 trillion in 1980 because while the economy grew by factor of 2, prices grew by a factor of 3 for reasons unrelated to the economy growing by a factor of 2 or changes in the goods actually produced?



To put this mathematically, when we assume the price is separable, we assume that we don't have a scenario where \[2\]








One thing I'd like to emphasize is that I'm not saying these assumptions are wrong, but rather that they are assumptions — assumptions that didn't have to be made, or made in a particular way.



The end result of all these assumptions — assumptions about rational agents, about the nature of inflation, about where the information resides in a transaction, about constant returns to scale — led us down a path towards a production function where we have to invent a new mysterious fudge factor we call total factor productivity in order to match data. And it's a fudge factor that essentially undoes all the work being done by those assumptions. And it's for no reason because the Cobb-Douglas production function, which originally didn't have a varying TFP by the way, does a fine job with nominal quantities, increasing returns to scale, and a constant TFP as shown above.



It's one of the more maddening things I've encountered in my time as a dilettante in economic theory. Incidentally, this all started when Handley asked me on Twitter what the information equilibrium approach had to say about growth economics. Solow represents a starting point of growth economics, so I feel a bit like Danny in _The Shining_ approaching the rest of the field:



![](<media/danny shock.png>)


**Update #1: 20 September 2017**

[has a response](https://jwhandley.blogspot.jp/2017/09/increasing-returns-to-scale-is-integral.html)

> _Namely, \[Smith\] questions the attachment to constant returns to scale in the Solow model, which made me realize (or at least clarified my thinking about the fact that) growth theory is really all about increasing returns to scale._

That's partially why it is so maddening to me. Contra Solow's claim that constant returns to scale is "the natural assumption", it is in fact the most _unnatural_ assumption to make in a theory of economic growth.



**Update #2: 20 September 2017**



[Sri brings up a great point on Twitter](https://twitter.com/teasri/status/910308095330484226) from the history of economics — that this post touches on the so-called "[index number problem](https://en.wikipedia.org/wiki/Index_\(economics\)#Index_number_problem)" and the "[Cambridge capital controversy](https://en.wikipedia.org/wiki/Cambridge_capital_controversy)". I actually have posts on resolving both using information equilibrium ([INP](https://informationtransfereconomics.blogspot.com/2015/01/how-do-you-measure-price-level.html) and [CCC](https://informationtransfereconomics.blogspot.com/2015/05/resolving-cambridge-capital-controvery.html), with the latter being a more humorous take). However, this post intended to communicate that the INP is _irrelevant_ to growth economics in terms of _nominal_ quantities, and that _empirically_ there doesn't seem to be anything wrong with adding up capital in terms of _nominal_ value. The CCC was about adding real capital (i.e. espresso machines and drill presses) which is precisely Joan Robinson's "adding apples and oranges" problem. However, using nominal value of capital renders this debate moot as it becomes a modelling choice and shifts the "burden of proof" to comparison with empirical data.



Much like how the assumptions behind the production function lead you down the path of inventing a "total factor productivity" fudge factor because the model doesn't agree with data on its own, they lead you to **_additional_** theoretical problems such as the index number problem and Cambridge capital controversy.





**Footnotes:**

\[1\] Model details and the _Mathematica_ code can be found [on GitHub in my **informationequilibrium** repository](https://informationtransfereconomics.blogspot.com/2017/02/information-equilibrium-code.html).

\[2\] Funny enough, the information equilibrium approach does mix these quantities in a particular way. We'd say:

$$<br />\begin{align}<br />N = &amp; \frac{1}{k} P Y\\<br /> = &amp; \frac{1}{k} \frac{dN}{dY} Y<br />\end{align}<br />$$
or in the notation I show $N = P(Y) Y$.
