---
title: Computing Nash equilibria is intractable
date: 2016-02-06T12:04:00.004-08:00
updated: 2016-02-06T12:17:41.095-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/02/computing-nash-equilibria-is-intractable.html
---

> _We show that computing a Nash equilibrium is an intractable problem. Since by Nash’s theorem a Nash equilibrium always exists, the problem belongs to the family of total search problems in NP, and previous work establishes that it is unlikely that such problems are NP-complete. We show instead that the problem is as hard as solving any Brouwer fixed point computation problem, in a precise complexity theoretic sense. The corresponding complexity class is called PPAD, for Polynomial Parity Argument in Directed graphs, and our precise result is that computing a Nash equilibrium is a PPAD-complete problem._
>
>
>
> __In view of this hardness result, we are motivated to study the complexity of computing approximate Nash equilibria, with arbitrarily close approximation. In this regard, we consider a very natural and important class of games, called **anonymous games**. These are games in which every player is oblivious to the identities of the other players; examples arise in auction settings, congestion games, and social interactions. We give a polynomial time approximation scheme for anonymous games with a bounded number of strategies.__

That is from the abstract of [Constantinos Daskalakis](http://news.mit.edu/2016/faculty-profile-constantinos-daskalakis-0204)'s thesis \[[pdf](http://people.csail.mit.edu/costis/thesis.pdf)\], underlining emphasis mine. I had a tweet about this earlier this week, but I wanted to say a bit more about it. Since we can view the market as an algorithm to solve a computational problem (I like [this blog post](http://crookedtimber.org/2012/05/30/in-soviet-union-optimization-problem-solves-you/) and there is also [this paper](http://arxiv.org/abs/1002.2284)), the market is probably not a Nash equilibrium. What is also interesting is that the Nash equilibrium problem is as hard as solving the [Arrow-Debreu equilibrium](https://en.wikipedia.org/wiki/Arrow%E2%80%93Debreu_model) problem (an application of the Brouwer fixed point theorem) ... although that shouldn't be surprising since the proof of existence of Nash equilibria [can also proceed via Brouwer's theorem](https://en.wikipedia.org/wiki/Nash_equilibrium#Alternate_proof_using_the_Brouwer_fixed-point_theorem).



Daskalakis proceeds to look at algorithms to find approximate Nash equilibria, but this result makes me think that economic equilibria may not be even _approximate_ Nash or Arrow-Debreu equilibria. The process of tâtonnement (an algorithm for finding approximate equilibria) would proceed until you reached either a satiation point (one all parties can live with) or simply the most likely point (the average of all possible system configurations) ... i.e. [the maximum entropy point](http://informationtransfereconomics.blogspot.com/2016/01/draft-paper-for-talk-this-summer.html) (see also [this](http://informationtransfereconomics.blogspot.com/2015/11/maximum-entropy-better-than-game-theory.html)).



Also, one of the ways to "break" intractability is with randomness -- that is the idea behind _Monte Carlo_ algorithms  -- see this [old _Scientific American_ article](http://www.cs.virginia.edu/~robins/Breaking_Intractability.pdf) \[pdf\]. Remember when _Scientific American_ was good?

Economists will probably just ignore this like they ignore the SMD theorem \[Kirman, [pdf](http://econ2.econ.iastate.edu/tesfatsi/WhomOrWhatDoesRepIndRepresent.AKirman1992.pdf)\], though.
