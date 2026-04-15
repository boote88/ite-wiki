---
title: Information equilibrium is an equivalence relation
date: 2015-03-01T11:23:00.001-08:00
updated: 2015-03-01T11:23:05.979-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/03/information-equilibrium-is-equivalence.html
---

Something for the math nerds. I've said it a couple times, but haven't actually shown the proof. However, it is true that information equilibrium is an equivalence relation. If we define the statement $A$ to be in information equilibrium with $B$ (which we'll denote $A \cong B$) by [the relationship](http://informationtransfereconomics.blogspot.com/2013/04/the-information-transfer-model.html) (i.e. ideal information transfer from $A$ to $B$):





for some value of $k$, then, first we can show that $A \cong A$ because







and we can take $k = 1$. Second we can show that $A \cong B$ implies $B \cong A$ by re-deriving the relationship (1), except moving the variables to the opposite side:





for some $k'$ (i.e. $k' = 1/k$). Lastly we can show that $A \cong B$ and $B \cong C$ implies $A \cong C$ via the [chain rule](http://en.wikipedia.org/wiki/Chain_rule):













with information transfer index $k = a b$. That gives us the three properties of an [equivalence relation](http://en.wikipedia.org/wiki/Equivalence_relation): _reflexivity_, _symmetry_ and _transitivity_.
