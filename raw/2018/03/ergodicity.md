---
title: "Ergodicity!"
date: 2018-03-12T10:00:00.000-07:00
updated: 2018-03-13T11:27:23.703-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2018/03/ergodicity.html
---

Roger Farmer [has an interesting summary](http://www.rogerfarmer.com/rogerfarmerblog/2018/3/12/ergodicity) of the meeting he had as part of the Rebuilding Macroeconomics project. Several points were great. First, a couple of quotes:

> _At each level of aggregation, natural scientists have learned that they must use new theories to understand emergent properties that arise from the interactions of constituent parts._

I would only say that instead of "they must use", I would write "it is more efficient to use". The people that do direct aggregation are doing valuable work, and there are zero cases in natural science where they have given up aggregation for emergent theories. Lattice QCD has been validating the effective nuclear theories, and neuroscientists haven't given up on explaining brain function in terms of neurons. Roger probably makes the statement the way he does because of the "hegemony of microfoundations" in macro that seemed to invalidate aggregate approaches that weren't derived from 'rational' individual behavior.



I liked this quote as well:

> _Some have argued that the social world, like the weather, is obviously governed by chaotic processes; the so-called butterfly effect. What I have learned in my discussions with the applied mathematicians and physicists who attended our meeting, is that the natural world is far less predictable than that. It is not just the variables themselves that evolve in non-linear chaotic ways; it is the probabilities that govern this evolution._

One thing to note is that the chaos in dynamical systems is a kind of "precision chaos" that differs from the colloquial use of the word chaos. You can't necessarily cobble together a nonlinear circuit that automatically manifests it without some fine tuning \[1\], and adding noise can easily disrupt any patterns.



Roger says that the theme of the meeting seemed to be that macroeconomics needs to think about non-ergodicity. Ergodicity has a slightly different meaning in statistics (Roger's sense) than in physics, but the basic idea is that it is an assumption about the representativeness of samples (i.e. that they are representative) in forming aggregate measures. The specific sense Roger's using it is that obesrvation of a random process over a long enough time will produce an estimate of the random process's parameters (that can be used for e.g. forecasting). As a slogan, non-ergocity is inherent in the statement that past performance is not guarantee of future returns.



Ergodicity is not always a good assumption, but Roger's characterization is a bit of an exaggeration:

> _... agent-based modellers and the econo-physicists are perplexed that anyone would imagine that ergodicity would be a good characterization of the social world when it was abandoned in the physical sciences decades ago._

We still make assumptions of ergodicity, just not in all problems. That's the key, and that's where I differ from Roger's opinion.



First, a bit of philosophy. Ergodicity is a property of aggregating the underlying degrees of freedom (agents, process states, etc), but not a property of the aggregate itself. Ergodicity is used to aggregate atoms in statistical mechanics to derive the ideal gas law. The statistical mechanics is ergodic, not the emergent ideal gas law. If we have that emergent economic theory Roger mentions in the quote at the top of this post, the theory is neither ergodic nor non-ergodic (unless it is further aggregated at a higher level ... e.g. ergodic neurons aggregate to brains which are non-ergodic when aggregated to an economy).

Since ergodicity is a property of the agents and the aggregation process, we really have only one of two ways to determine whether non-ergodicity is important:

1.  Aggregate some non-ergodic processes/theory into an empirically successful macro theory
2.  Have a really good (empirically accurate) theory of the underlying process or agents that shows to be non-ergodic

In the first case, the agents or processes don't even have to be realistic (macro success is sufficient). The second case is the one used in a lot of natural sciences where we tend to have really good "agent" models (e.g. atoms in physics).



The problem with Roger saying macro "needs to deal with" non-ergodicity is that we have neither good agent models nor a successful macro theory made up of non-ergodic processes. Therefore we have no idea whether macro is non-ergodic or not. Our inability to forecast could just be because we are wrong about how economies work. If you can't predict inflation, you shouldn't jump to inflation being a non-ergodic process. Sure, someone can and should try that, but others should question whether more basic aspects of the model are correct (such as the correct input variables).



Like "complexity" (or any other ingredient you might think "needs" to be in macroeconomic theory), the proof of the relevance of non-ergodicity is in empirically successful models that incorporate it.



...



PS In his post, Roger [cites Mark Buchanan](https://medium.com/the-physics-of-finance/whats-the-use-of-econo-physics-dae83e0d7d8a) as an econophysicist who has questioned ergodicity. I don't know if Buchanan was at the meeting or is any part of the source of this emphasis on non-ergodicity. Regardless, Buchanan cites Ole Peters as his impetus for thinking about non-ergodicity ([a collection of links here](http://lml.org.uk/press/ergodicity-the-biggest-mistake-in-economics-by-mark-buchanan/)).



However Peters paper on non-ergodicity represents a mathematical slight of hand, and not an actual demonstration of non-ergodicity. It's an apples to oranges comparison of a geometric mean to a arithmetic mean that I talk about in these two posts:



[_Regulators_](https://informationtransfereconomics.blogspot.com/2016/06/regulators.html)

[_Sleight of hand with the regulator_](https://informationtransfereconomics.blogspot.com/2016/06/sleight-of-hand-with-regulator.html)



If you enjoy math jokes, you might like the first post. The second post goes into more detail about how the infinity is made to magically vanish in the case of a geometric mean.

...



**Footnotes**



\[1\] [An implementation here](https://www.researchgate.net/publication/274566110_Chua%27s_Circuit_for_Experimenters_Using_Readily_Available_Parts_from_a_Hobby_Electronics_Store) of Chua's circuit requires humans to fine-tune a couple of resistors to achieve chaotic behavior. The models developed by Steve Keen are basically nonlinear circuits like this — I am highly doubtful macroeconomies run with this kind of precision.
