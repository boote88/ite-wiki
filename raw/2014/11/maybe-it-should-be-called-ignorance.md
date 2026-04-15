---
title: "Maybe it should be called the ignorance equilibrium model?"
date: 2014-11-04T17:22:00.002-08:00
updated: 2014-11-04T17:22:48.858-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/11/maybe-it-should-be-called-ignorance.html
---

In a brief email exchange about the information transfer model with Robin Hanson, one of the more original and insightful thinkers around today (I read [his blog](http://www.overcomingbias.com/) regularly, though I expect roughly a 50/50 chance of disagreeing with a given post -- maybe we disagree on the process of developing our priors \[1\]), is understandably skeptical and asked a very good question. I am paraphrasing (these are my words, not his), but the essence of the question was: _economists have been using information theory for 50+ years, so do you really think you have something new?_



This post is going to be an open response to that question and hopefully serve as notes for a future conversation. Please add your comments or criticisms!



I can probably sum up the reason I think I have something different (and as I mentioned to Hanson, the difference may be that it is wrong) in a single sentence: traditional economics puts fathomable human minds at the center of the enterprise whereas information transfer economics assumes humans are inscrutable.



Now I was aware of the importance of information in economics -- my [second post](http://informationtransfereconomics.blogspot.com/2013/04/an-informal-abstract-addition-why-now.html) on this blog mentions [information economics](http://en.wikipedia.org/wiki/Information_economics) in a postscript:

> PS -- While it might eventually be related, the work presented here has nothing immediately to do with "information economics" a la Akerlof, Stiglitz, etc. "Information" is being used in the Shannon sense: a price is communicating a signal from the demand to the supply.

I should have said the price is detecting a signal sent from the demand to the supply, but otherwise that postscript stands up pretty well. The Nobel prize-winning authors I cited are the big names in information asymmetry, where either the seller (usually) or the buyer has more information about the quality of the good being sold. Akerlof showed in his _The Market for Lemons_ that information asymmetry typically drives the value of goods down (or may lead to a lack of any sales at all) and I originally thought this had something to do with non-ideal information transfer where the non-ideal price P\* ≤ P (the ideal price) that derives from I(S) ≤ I(D) -- the information received by the supply is at best equal to the information transmitted by the demand.



In the information transfer framework, information asymmetry is a form of non-ideal information transfer. However, in that sentence, the word "information" is being used in two distinct ways. In information asymmetry, a large amount of information about the quality of a good selects a more specific economic state (e.g. quality Q, price P) and thus represents a small amount of information (a small number of possible states consistent with the macroscopic parameters) transferred by the market. A market operating where the demand has a complete lack of knowledge about the quality of a good (i.e. a uniform distribution over Q) has the potential to transfer a large amount of information (a large number of possible states consistent with the macroscopic parameters) ... as long as the supply has an equal uniform distribution.



Ideal information transfer in this case is where the expected distribution over Q on the demand side (call it Qd) the distribution over Q on the supply side (Qs) are equal, Qd = Qs. If they differ, there is information loss -- measured by e.g. the Kullback–Leibler divergence D so that D(Qd || Qs) = D(Qd || Qd) = 0 in the ideal case.



The information asymmetry argument is then that Qs is some tight distribution around the actual quality Q0 while Qd is more diffused (and may not even cover Q0). In this case 0 ≤ D(Qd || Qs), and, in this toy model, I(D) ~ I(S) – D(Qd || Qs) so that P\* ≤ P. In the information transfer picture, however, the value Q0 is not relevant and Qs could be narrow around Q1 ≠ Q0 and the result would be the same. What matters is the difference between Qs and Qd, _not the accuracy of either estimate_.



What is interesting is that in the information transfer model the approximation I(D) ~ I(S) on average, meaning Qd and Qs are on average effectively \[2\] the same, is a really good approximation for macroeconomic variables (here we've changed Q to mean any relevant metric, e.g. expected NGDP).



Information asymmetry is not important in the generic scenario: it is either always present (see footnote \[2\]) or always absent. It may have relevance to the dynamics of recession (e.g. it may suddenly change) -- I don't know. However, information loss not important to first order.



Hanson pointed me to [Robert Aumann](http://en.wikipedia.org/wiki/Robert_Aumann) \[1\] and [John Harsanyi](http://en.wikipedia.org/wiki/John_Harsanyi), Nobel prize-winners for their research in game theory, specifically on repeated games and Bayesian games, respectively.



The information transfer model in no way invalidates the many insights into microeconomics from game theory, and in fact has little to do with game theory. How do I know? Game theory is a representation of economic microfoundations; the information transfer framework makes as few assumptions about microfoundations as possible. We are assuming we don't know any game theory.



The following is a rough sketch, but one way to think about the information transfer model is as an ensemble of games with random payoff matrices \[3\] (zero-sum and not) with players repeating games, switching between games and possessing some correct and/or potentially incorrect information about the payoff matrix (or its probability distribution). The only "constraint" is that all of the realized payoffs sum up to a macroeconomic observable like NGDP \[3\].



The information transfer approach assumes maximum ignorance (maximum entropy) about the players, payoff matrices and strategies (let those define the microstates), that each microstate consistent with the macroeconomic observable (e.g. NGDP) is [equally probable](http://en.wikipedia.org/wiki/Principle_of_maximum_entropy).



You could imagine that in such a model, a spreading malaise where investors feel they have insight into the payoff matrices such that the optimal strategy [is not to play](http://en.wikipedia.org/wiki/WarGames). Other possible [correlated equilibria](http://en.wikipedia.org/wiki/Correlated_equilibrium) could appear. A correlation in strategies would represent a fall in entropy (less ignorance about the microstates) [and a fall in NGDP](http://informationtransfereconomics.blogspot.com/2014/10/coordination-costs-money-causes.html) (a recession).



This illuminates how the information transfer model differs from game theoretic takes -- regardless of whether they use perfect information, complete information or incomplete information. A correlated equilibrium or Nash equilibrium where there is some optimal strategy that maximizes the payoff (imagine tit-for-tat as applied to the prisoner's dilemma) represents selecting a particular microstate (or set of microstates) which represents a massive loss of ignorance (entropy) of the microstates. That equates to a loss of NGDP relative to players having a random strategy.



One of the issues with the word "information" in information theory is that it is sometimes confused with news or facts, but what is being equated on either side of I(D) = I(S) is the ignorance of the microstates. That ignorance is what is being transferred from demand to the supply. I(D) = I(S) then represents an "ignorance equilibrium". In this model, money is about moving ignorance around.



In searching through the internet, the primary association between economics and information theory the way I am using it is though statistical measures. For example, the [Theil index](http://en.wikipedia.org/wiki/Theil_index) uses information in the same way the information transfer model does. But that is a construction of a particular metric and teasing out the dependence of macroeconomic outcomes on inequality may well be outside the scope of informaiton transfer economics.



The biggest reason I think this is different from previous work in economics -- and maybe some of you out there can help me with this since Google will skew its results based on who is searching -- is that when I do a google image search on **_"information theory" GDP_** I mostly get back my own graphs. Have a go yourself:


[http://www.google.com/search?q=%22information+theory%22+GDP&tbm=isch](http://www.google.com/search?q=%22information+theory%22+GDP&tbm=isch)



[http://scholar.google.com/scholar?q=%22information+theory%22+GDP](http://scholar.google.com/scholar?q=%22information+theory%22+GDP)


An additional reason for believing I am approaching economics in an entirely different way is found in this quote from [the textbook (from 2008) linked here](http://books.google.com/books?id=80yfbPxYHx4C&pg=PA39&lpg=PA39&dq=%22derive+supply+and+demand%22&source=bl&ots=RtPw6ZvJU2&sig=zRoYV-cb9jz2N0XOcomL_f8-vQ0&hl=en&sa=X&ei=6m9ZVNX2Icf2iQL-rYCoBw&ved=0CDAQ6AEwAw#v=onepage&q=%22derive%20supply%20and%20demand%22&f=false) (I chose this quote because it puts the idea so concisely):

> It is important to note that any definition of supply and demand functions should satisfy two conditions. It should reflect the concrete decision-making of producers and consumers, and it should be founded empirically.

I think this sums up the mainstream view. However, according to information transfer economics, the first condition is not just unnecessary -- it is totally wrong. You assume complete ignorance of the concrete decision-making of producers and consumers. The fact that you give this up -- a deeply held belief that human decision-making is important -- makes me think few economists, if any, have tried this approach. It's a bit like asking if physicists have ever considered a theory where energy isn't conserved. You don't really have to know the literature to say that such theories probably fall outside the mainstream -- even if it was empirically accurate.



Yet another reason is that it has been [nigh impossible to find models of the price level](http://informationtransfereconomics.blogspot.com/2014/07/a-challenge-to-macroeconomists.html) -- there are a couple out there, but none use information theory.



If anyone else out there knows of some work that closely resembles information transfer economics, let me know!


**Footnotes:**


\[1\] [Aumann's agreement theorem](http://en.wikipedia.org/wiki/Aumann%27s_agreement_theorem) is quite useful if you find yourself disagreeing with someone you suspect of being a Bayesian.



\[2\] Note this may mean that I(D) ~ I(S) + C or a I(D) ~ I(S), where C is some unknown information scale or a is some unknown dimensionless parameter a < 1 that is characteristic of economic processes. We don't necessarily know what the absolute value is for I(D). However, we could just redefine I\*(D) = I(D) – C or I\*(D) = a I(D) and proceed as if we did know.



\[3\] Random payoff matrices have been treated in the literature; here are two papers I've found \[pdf\]:



[http://people.hss.caltech.edu/~miaryc/PEW/Michael\_Chwe\_PEWCaltech.pdf](http://people.hss.caltech.edu/~miaryc/PEW/Michael_Chwe_PEWCaltech.pdf)

[http://www.ssc.wisc.edu/~whs/research/rdp.pdf](http://www.ssc.wisc.edu/~whs/research/rdp.pdf)



Neither are related to information transfer economics.



\[4\] One could put expected payoffs and expected NGDP here as well.
