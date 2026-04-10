---
title: Information Equilibrium
type: concept
tags: [core-framework, maximum-entropy, ignorance-equilibrium]
sources:
  - raw/2014/11/maybe-it-should-be-called-ignorance-equilibrium.md
  - raw/2014/12/information-equilibrium-theories-satisfy-lucas-critique.md
  - raw/2015/02/a-simple-example-of-information.md
  - raw/2015/02/do-different-market-models-work.md
  - raw/2015/03/information-equilibrium-is-equivalence.md
  - raw/2015/04/information-theory-and-economics-primer.md
  - raw/2015/01/solving-identification-problem-via.md
  - raw/2015/10/info-eq-101.md
  - raw/2015/10/the-smd-theorem-and-oh-no-not-another.md
created: 2026-04-07
last_updated: 2026-04-07
---

# Information Equilibrium

**Information equilibrium** (also called "ignorance equilibrium") is the state where the [[information-transfer-model]] operates at maximum entropy — assuming the *least informative prior* about which microstate exists, given macro constraints. It is really just a broadening of the concept of "equality" between two economic quantities:

- $A(t) = B(t)$ → two things are equal
- $A(t) = c \cdot B(t) + b$ → two things are proportional
- $\log A(t) = k \log B(t) + b$ → two things are in **information equilibrium**

If two quantities satisfy this log-linear relationship, a message encoded in one shows up faithfully in the other. If they don't, there's information loss — [[non-ideal-information-transfer]].

The simplest example: a gas pump display. Total sale and gallons pumped are in information equilibrium — squeezing the nozzle in a Morse code pattern transfers the signal faithfully to the total sale. The price per gallon is the constant "detector." Generalizing beyond constant price ($k \neq 1$) gives the full ITM with varying prices: $D = k(dD/dS) \cdot S$.

The framework is "unreasonably effective" — Smith himself remains surprised at how well it works. It's the macro analog of finding that gases under pressure all follow the ideal gas law and most of the deviations are just noise. The IT framework is a first-order theory that almost certainly is the limit of something more accurate, but to a remarkable degree, most quarter-to-quarter movements in NGDP and core CPI seem to *be* just noise around the simple IT trends. There are recessions, but those are sporadic. There are seasonal effects, but those derive from human reactions to the orbit of Earth. Beyond that, where are the other successes of macroeconomics that wouldn't be captured by marginal/supply-and-demand arguments? If they existed, they'd refute the IT framework. They mostly don't exist.

## Definition

A system is in information equilibrium when $I_S = I_D$ — all information from demand reaches supply. This corresponds to the maximum entropy macrostate consistent with observed macroeconomic variables. In non-equilibrium: $I_S < I_D$ — information is lost, producing [[sticky-prices]] and recessions.

## Why "ignorance equilibrium"

The ITM doesn't assume agents are rational, informed, or optimizing. It assumes **maximum ignorance** about the microstate — the exact opposite of rational expectations. This works because there are vastly more high-entropy microstates than low-entropy ones, so the economy overwhelmingly occupies high-entropy states. Macro patterns emerge from counting, not from individual behavior — just as gas laws work because there are ~$10^{23}$ molecules, not because each molecule optimizes.

## Mathematical properties

Information equilibrium is an **equivalence relation**: reflexive ($A \cong A$ with $k=1$), symmetric ($A \cong B \implies B \cong A$ with $k'=1/k$), and transitive ($A \cong B, B \cong C \implies A \cong C$ with $k=ab$, via chain rule). This is essential: it means the ITM's separate models — price level, interest rates, labor market, Solow growth — form a consistent system when they share NGDP as a common information source, rather than being independent ad-hoc fits.

Information equilibrium also forms a **group under multiplication** but is **not closed under addition** — a fact that resolves the Cambridge capital controversy (you can't add different capital goods, but you can take geometric means).

The basic IE equation $dA/dB = k A/B$ has a **conformal symmetry** ($A \to \alpha A$, $B \to \beta B$ leaves it invariant). Treating IE as an effective theory and writing all terms compatible with this symmetry to lowest order adds a constant: $dA/dB = k A/B + c$. This is one of the oldest differential equations in mathematics (Bernoulli, 1694), and its solution behaves like $A \sim B$ for small $B$ and $A \sim B^k$ for large $B$. The linear regime is what makes things like minimum wage and minimum costs of production tractable in the framework — they live in the small-$B$ limit where the leading correction matters. The original solution is recovered in the large-$B$ limit, so this is a strict generalization.

## Self-similarity: why macro looks like micro

A proof that resolves a long-standing puzzle: why does the macroeconomic [[ad-as-model]] look formally similar to a single-market [[supply-and-demand]] diagram? The answer: the ensemble average of individual information equilibrium relationships **has the same mathematical form** as a single relationship:

$$\frac{\partial \langle A \rangle}{\partial B} = \langle k \rangle \frac{\langle A \rangle}{B}$$

which is formally identical to the individual $dA_i/dB = k_i A_i/B$, just with the ensemble-average IT index $\langle k \rangle$ replacing the individual $k_i$. Over short periods (where $B$ doesn't change quickly), the ensemble equation can be treated as a single information equilibrium relationship.

This is mathematical self-similarity between micro and macro: the whole really does look like the parts, not by accident or by the fallacy of composition, but because the partition function preserves the form of the equation under aggregation. AD-AS is a supply-and-demand diagram because it *must be* — the math requires it. The [[ad-as-model]], the [[is-lm-model]], and micro S&D are all instances of the same equation at different scales.

## Satisfies the Lucas critique

Information equilibrium theories satisfy the Lucas critique *without* microfoundations. The relationships are derived from information theory, not behavioral assumptions, so they hold regardless of how agents change their behavior. Policy changes can shift κ but the information-theoretic relationships still govern the dynamics.

## Solving the identification problem

The classic econometric identification problem — you can't determine both supply and demand elasticities from price-quantity data alone — is solved because both elasticities follow from a **single parameter** κ. The 3D price surface P(NGDP, M0) is constrained by data points sampling its curvature. Diverse price-quantity movements *help* rather than hinder identification, because they constrain κ from multiple directions.

## Relationship to expectations

[[Expectations]] are probability distributions over future states. When they diverge from reality, the KL divergence measures information loss: wrong expectations → information loss → lower NGDP than ideal. Crucially, the least informative prior (maximum ignorance) performs *best on average* — rational expectations *destroy information* unless very accurate.

## Markets as allocation, not information aggregation

Markets don't aggregate information — they solve an allocation problem with a maximum entropy solution. This has consequences. Adding up everyone's rational intuitions and getting a rational counterintuitive result is itself counterintuitive (Arrow's impossibility theorem: aggregated preferences can be non-transitive even when individual preferences are transitive). So-called "counterintuitive" economic results (price gouging is good, imports are beneficial) are actually **immoral** results — they violate moral heuristics like "good begets good" — not logically counterintuitive ones.

Whether the market solution is "optimal" according to any utility function is unknowable because the economic linear programming problem is intractable. As Cosma Shalizi showed, planning for the whole economy is intractable under the most favorable assumptions. The ITM's answer: the market outcome isn't optimized. It just *is* — the maximum entropy state.

The intractability has been formalized in computational complexity terms. Daskalakis showed that computing a Nash equilibrium is **PPAD-complete** — as hard as finding a Brouwer fixed point. Computing an Arrow-Debreu equilibrium has the same complexity (Arrow-Debreu existence is also proved via Brouwer). This means markets cannot be computing Nash or Arrow-Debreu equilibria, even approximately, because no realistic algorithm can. What markets actually do is much weaker: tâtonnement until they reach a satiation point (one all parties can live with) or — what amounts to the same thing — the most likely point, the average of all configurations consistent with macro constraints. The maximum entropy point. Randomness is one of the standard ways to break intractability (see Monte Carlo methods), and the market's "randomness" is exactly the diverse, uncoordinated behavior of millions of agents making the maximum entropy state easy to reach.

A famous "wisdom of crowds" anecdote turns out to be consistent with this picture. After the Challenger disaster, Morton Thiokol's stock dropped more than the other NASA contractors, which the efficient-markets story interprets as the market identifying the culprit within minutes. But Thiokol's IT index (calibrated from prior daily returns) is roughly three times higher than Lockheed's. The same information shock applied to companies with different IT indices produces exactly the observed differential drops, with no special wisdom required. The market reaction is consistent with everyone receiving the same "something bad happened" signal and no one identifying which company was at fault. The "wisdom of crowds" interpretation is an artifact of comparing companies with different sensitivities to a common shock.

Maximum entropy also resolves another classical indeterminacy: when an Arrow-Debreu economy admits multiple equilibria (the Edgeworth box can have several intersection points of the offer curves), traditional theory has no way to pick which one is selected. The IE answer is the highest-entropy point — the maximum-entropy equilibrium subject to the same utility-maximization constraints. This is consistent with how markets actually behave: when several outcomes are technically possible, you observe the most likely one, not an arbitrary one. It's also one of the few cases where the IE framework gives a *prediction* in a context where mainstream theory shrugs.

A corollary: economics is **not about well-being**. The greatest trick economists ever pulled was conflating the allocation problem with welfare. Measures like GDP don't capture quality of life, and they shouldn't be expected to — they describe how an algorithm allocates information, not how happy people are. The ~400-fold income difference between New Yorkers and "primitive" tribes versus the ~10⁸ difference in product variety is a red herring once you take logarithms (the natural scale for information): $\log 400 \approx 6$ vs $\log 10^8 \approx 20$. Each new product adds only $1/n$ to $\log n$ — innovation has dramatically diminishing informational returns. Politics and philosophy are about human well-being; economics is about the mechanics of an allocation algorithm. Conflating them is a category error that has done significant damage.

## Reconciling economic schools

At information equilibrium, the ITM simultaneously agrees with Keynes (κ ~ 1.0, [[information-trap]]), Friedman (κ ~ 0.5, [[quantity-theory-of-money]] regime), and Sumner/Rowe (κ < 1.0, monetary policy effective). All schools were correct for their respective κ regimes. The ITM explains when and why each applies.
