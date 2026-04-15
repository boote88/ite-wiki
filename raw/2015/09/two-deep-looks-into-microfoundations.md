---
title: Two deep looks into microfoundations
date: 2015-09-18T16:59:00.003-07:00
updated: 2015-09-19T16:51:47.676-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/09/two-deep-looks-into-microfoundations.html
---

This post represents some theoretical musings on my part ... so it's probably a bit "out there" from a typical social science or economics background. I make no claim to originality either.



Here are two recent looks into the idea of microfoundations (in economics and sociology). 

> [_The Neoclassical Synthesis and the Mind-Body Problem_](http://uneasymoney.com/2015/09/18/the-neoclassical-synthesis-and-the-mind-body-problem/) (David Glasner) 

> [_Microfoundations and mechanisms_](http://understandingsociety.blogspot.com/2015/09/microfoundations-and-mechanisms.html) (Daniel Little)

Both writers delve into what microfoundations mean. 



Little's main point is about the relationship between microfoundations and mechanisms and his "preliminary answer" is that microfoundations are mechanisms acting on micro states. Mathematically, this is an expansion of the macro operator expectation in the macro state |Ω⟩ in a micro basis |i⟩



⟨Ω|Ô|Ω⟩ =  Σi ⟨Ω|Ô|i⟩⟨i|Ω⟩



Little then says there are some issues with this, that maybe mechanisms don't imply a level. And in the formulation above, they don't. The basis |i⟩ doesn't have to be micro states. It could be any sort of intermediate state (agents, firms, institutions)



⟨Ω|Ô|Ω⟩ =  Σx ⟨Ω|Ô|x⟩⟨x|Ω⟩



The key requirement for this to be generally true is that |x⟩ is a _complete_ basis. To me, individual agents seems like a complete basis relative to e.g. firms because while firms may buy and sell from each other, firms also produce goods that individual agents consume. That is to say the entirety of economic activity can be stated as a bunch of data about individuals but not necessarily a bunch of data about firms \[2\]. 



Glasner takes issue with the representative agent model that simply asserts the equivalence of macro observables and the outcomes of micro mechanisms acting on micro degrees of freedom. If you do this, he says, you leave out the fact that macro observables might emerge from the interactions between micro degrees of freedom. Mathematically, Glasner's point is that the representative agent implies the ensemble average of an operator is no different from the single agent expected value, that



⟨Ω|Ô|Ω⟩ ~ ⟨1|Ô|1⟩



where ⟨1|Ô|1⟩ = ⟨2|Ô|2⟩ = ... which obviates the difference between the n-agent macro state |Ω⟩ and the single agent micro states |1⟩, |2⟩, ... and e.g. "unintended consequences" from the interaction between |1⟩ and |2⟩ are left out. Basically, the representative agent approach assumes the macro observable determined by the operator Ô is [diagonal](https://en.wikipedia.org/wiki/Diagonal_matrix#Operator_theory). Actually, we can derive the representative agent model from my formulation of Little's definition of microfoundations:



⟨Ω|Ô|Ω⟩ =  Σi⟨Ω|Ô|i⟩⟨i|Ω⟩



⟨Ω|Ô|Ω⟩ =  Σi ⟨i|Ω⟩⟨Ω|Ô|i⟩



\[_correction_\] The representative agent model is that the macro states are exactly the same as (identified with \[1\]) some micro state (the representative agent) so we can change out Ω for some j (the representative agent)



⟨Ω|Ô|Ω⟩ =  Σi ⟨i|j⟩⟨j|Ô|i⟩


⟨Ω|Ô|Ω⟩ =  Σi  δij ⟨j|Ô|i⟩


⟨Ω|Ô|Ω⟩ =  ⟨j|Ô|j⟩


\[_end correction_\]


In contrast, the information equilibrium approach can be seen as a different application of my formulation of Little's microfoundations



⟨Ω|Ô|Ω⟩ =  Σi ⟨i|Ω⟩⟨Ω|Ô|i⟩



⟨Ω|Ô|Ω⟩ =  tr |Ω⟩⟨Ω|Ô = tr Ô|Ω⟩⟨Ω| 



⟨Ω|Ô|Ω⟩ =  tr Ô exp(- Â log m)



where I identified the operator |Ω⟩⟨Ω| ≡ exp(- Â log m) where Â picks off the information transfer index of a micro market. This is the [partition function approach](http://informationtransfereconomics.blogspot.com/2014/06/the-macroeconomic-partition-function.html). And we are saying the macro state Ω is directly related to a maximum entropy distribution (partition function):







The partition function approach is basically a weighted sum over (Walrasian) micro markets that produces macro observables ... borrowing Glasner's words, we are: "reconciling the macroeconomic analysis derived from Keynes via Hicks and others with the neoclassical microeconomic analysis of general equilibrium derived from Walras."



What about the [emergent representative agent](http://informationtransfereconomics.blogspot.com/2015/09/the-emergent-representative-agent-1.html)? Well, if Â is diagonal in its representation in terms of microstates, then



⟨Ω|Ô|Ω⟩ =  tr Ô exp(- Â log m)



⟨Ω|Ô|Ω⟩ =  Σi ⟨i|Ô exp(- Â log m)|i⟩



⟨Ω|Ô|Ω⟩ =  Σi ⟨i|Ô|i⟩ exp(- ai log m)



If we take m >> 1 (a large economy) the leading term is min {ai} that we'll call a₀ so that



⟨Ω|Ô|Ω⟩ ≈ ⟨0|Ô|0⟩ exp(- a₀ log m)



⟨Ω|Ô|Ω⟩ ~ ⟨0|Ô|0⟩



This has the analogy of the ground state (at zero temperature) in physical system \[3\].



...


**Footnotes:**



\[1\] For example, as Glasner says, "the business cycle is not the product of the interaction of individual agents, but is simply the optimal plan of a representative agent"



\[2\] As an aside, the idea of having consumers and firms seems like a strange basis that isn't necessarily complete (and actually includes two different levels as firms are made of consumers).



\[3\] For bosons, this would be a Bose-Einstein condensate. So the representative agent is like a bunch of molecules in the same state behaving as a single entity.
