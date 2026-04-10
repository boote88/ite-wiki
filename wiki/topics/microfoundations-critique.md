---
title: Microfoundations Critique
type: topic
tags: [dsge, microfoundations, lucas-critique, emergent-macro]
sources:
  - raw/2013/04/the-philosophical-motivations.md
  - raw/2015/01/is-demand-curve-shaped-by-human.md
  - raw/2015/03/nominal-rigidity-is-entropic-force.md
  - raw/2015/03/entropy-and-walrasian-auctioneer.md
  - raw/2015/04/information-theory-and-economics-primer.md
  - raw/2015/07/assuming-complexity.md
created: 2026-04-07
last_updated: 2026-04-07
---

# Microfoundations Critique

The [[information-transfer-model]] is motivated partly by skepticism toward the microfoundations approach dominant in mainstream macroeconomics — but goes beyond philosophical skepticism to provide concrete evidence that microfoundations are not just unnecessary but invisible in macro data.

## The theoretical argument

**Microfoundations cannot survive aggregation into a macroeconomic model as anything other than a coefficient.** If they do, the resulting model is likely intractable. This is supported by repeated precedent in physics: thermodynamics works without knowing about atoms (Boltzmann needed only to know there were ~$10^{23}$ of them), quark details reduce to a factor of three at the hadron scale, and Galileo's law works regardless of shape or air resistance. In each case, micro-details collapse to a few numbers in the macro theory.

Smith positions DSGE models as economics' string theory — awesome mathematics, little connection to experiment, intractable except under simplifying assumptions, and "kind of a big deal for a limited reason." The ITM is analogous to Verlinde's entropic gravity: maybe we don't need micro-details to derive macro-laws.

## The SMD theorem as effective field theory

The Sonnenschein-Mantel-Debreu theorem — often called the "anything goes" theorem — states that aggregate market demand inherits only a few properties from individual demand: continuity, homogeneity of degree zero, Walras' law, and a boundary condition. Translated into physics: **the macro theory inherits only conservation laws and symmetry principles from the micro theory**. This is exactly the idea behind constructing an effective field theory.

The analogy is precise. In QCD, quarks and gluons at the micro scale produce hadrons (protons, pions) at the macro scale. The effective theory (chiral perturbation theory) has empirical parameters like $F_\pi$ that don't exist for individual quarks — they're properties of the aggregate. You can calculate pion scattering from $F_\pi$ far more easily than from a QCD lattice simulation. Similarly, the [[information-transfer-index]] κ is an empirical macro parameter that doesn't exist for individual agents. Demanding microfoundations is like demanding a lattice QCD calculation for every chiral perturbation theory result — tedious, unnecessary, and possibly misleading because the effective theory can look **entirely different** from the fundamental theory.

The call for microfoundations assumes the structure of the effective macro theory. It represents a massive limitation of the possibilities — and may exclude the real theory.

David Glasner's version of the same argument is sharper: "There is no theory describing the laws of motion leading from one equilibrium to another, so the whole exercise is built on the mere assumption that a general equilibrium is sufficiently stable so that the old and the new equilibria can be usefully compared. In other words, microeconomics is predicated on macroeconomic foundations, i.e., the stability of a general equilibrium. The methodological demand for microfoundations for macroeconomics is thus a massive and transparent exercise in question begging." Microfoundations rest on macrofoundations that the program refuses to acknowledge.

## The scope conditions problem

A related issue: mainstream macro models lack **scope conditions**. New Keynesian DSGE doesn't say "applies only in recessions"; RBC doesn't say "applies only in inflation-free booms"; Minsky's model claims to apply across the entire cycle. Yet practitioners increasingly say "use NK in recessions, use RBC in booms, use Minsky in financial crises" — applying scope conditions retroactively, after the data tells you which model worked. As Noah Smith pointed out, this is "Keynes works during recessions, therefore Keynes is the appropriate model for recessions" — circular and unfalsifiable in advance.

The string theory analogy: there are five different string theories, each thought to be a fundamental theory of everything until S- and T-dualities revealed they were all aspects of an underlying M-theory. Macro is in the pre-dualities phase: many models, no clear framework relating them, no way to know which applies until after the fact. The ITM provides what macro is missing — a framework with explicit scope conditions (the κ regimes) that says in advance when each "school" applies. See [[is-lm-model]] for the IS-curve regime story, and [[information-transfer-index]] for how κ controls which approximation is valid.

## The dimensional reduction argument

A million agents with 1,000 variables each is a billion-dimensional problem. If the macroeconomy can be described by a handful of aggregates (NGDP, a couple of interest rates, inflation, money supply) and parameters — let's be generous and say 1,000 — then there has been **massive dimensional reduction**. This isn't unusual; an ideal gas reduces from $3N$ dimensions to 4 (P, V, T, N). The onus is on those claiming complexity to demonstrate dimensional reduction *doesn't* happen — to tell us what the millions of additional relevant macro aggregates are.

Common arguments for complexity are all flawed: economists can't predict well (maybe the theory is *wrong*, not the problem hard — Aristotelian physics didn't predict gravity well either), humans are complex (irrelevant without showing the complexity survives aggregation), we haven't figured it out (failure of imagination, like intelligent design arguments). The correct approach: start with what you know for sure (conservation of information) and move out from there, without assuming either simplicity or complexity.

A related objection — "the economy is a human construct, so there's no natural order to it" — also fails. The internet is also a human construct, yet has a natural order described by [[money-as-bandwidth|information theory]] and queueing theory. In the limit of many transactions and no panic, the **state space** (the opportunity set) determines macroeconomic behavior more than the properties of individual agents. Constructed systems can have natural laws; the "natural rate of interest" associated with a given NGDP and monetary base in the ITM is one example. See [[unobservables]] for the alternative-to-circular-definitions story.

## The agent-based modeling contradiction

Agent-based modeling (ABM) "fundamentalists" claim that only simulation from units to wholes can explain macro regularities. The position contradicts itself. To make a million-agent simulation tractable, ABM practitioners must impose dimensional reduction at the *micro* scale (simplified agent behavior, fewer parameters per agent). But once you grant that dimensional reduction happens at the micro scale, you're committed to the principle. There is no consistent reason to accept it there and reject it at the macro scale.

Worse, the ABM fundamentalist position contains a hidden contradiction. The way to be confident your particular agent assumptions don't accidentally distort the macro outcome is to show that **many different agent specifications produce the same aggregate behavior** — i.e., that the agents don't matter. But "the agents don't matter" is precisely the position the ABM fundamentalist denies. If your modeling choices about agents are load-bearing, then your macro results depend on assumptions you cannot justify; if they're not load-bearing, then you didn't need agents in the first place. The whole project is incoherent in either direction.

The same critique applies to demands for microfoundations. Tractable macro requires dimensional reduction. The microfoundations program either lets that reduction happen (in which case the micro details don't matter) or refuses to (in which case the resulting models can't be tractable). There is no consistent middle ground.

## Four mechanisms of emergence

If macro details don't depend on micro details, what mechanisms make this happen? Physics provides at least four well-understood routes by which large systems become tractable in ways their components are not:

1. **Universality classes of phase transitions.** Near a phase transition, different microscopic systems (Ising model, percolation, magnetism) collapse to identical critical exponents. The micro theory becomes irrelevant; what matters is which universality class you're in. This is why simple toy models near critical points generalize to wildly different real systems.

2. **Universality classes of probability distributions.** The central limit theorem says that sums of many independent random variables produce normal distributions regardless of the underlying distribution (provided it has well-defined mean and variance). Other limit theorems give other universality classes. Aggregation washes out micro detail.

3. **Effective field theory near equilibrium.** Most theories look like a harmonic oscillator near an energy equilibrium — from plasmons to pogo sticks. The "rational agent" of mainstream economics is the analog: a first-order effective theory near an economic equilibrium, valid in the same way a pendulum is valid as a description of a pogo stick (which is to say, locally and approximately).

4. **Entropic forces.** Macro degrees of freedom that don't exist at the micro level — solid-state physics has electron holes that don't exist without a filled Fermi sphere; thermodynamics has entropy that doesn't exist for a single atom. [[entropic-forces|Nominal rigidity]] is the same kind of thing — a force that emerges only at aggregate scale and has no micro counterpart.

The ITM uses all four. The first explains why crisis dynamics in different countries look so similar (same universality class). The second explains why the [[emergent-representative-agent]] works without assuming individual rationality. The third explains why mainstream economic models are sometimes correct (as effective theories near equilibrium). The fourth is the key mechanism behind [[sticky-prices]], [[recessions]], and the [[information-trap]].

These mechanisms also constrain what microfoundations can possibly do. Each is a route by which the macro theory becomes structurally independent of the micro theory. Insisting on microfoundations is insisting that *none* of these mechanisms apply to economics — a strong claim that would need an argument, and that the empirical track record of macroeconomics does not support.

## The empirical evidence

The philosophical argument gained teeth as empirical evidence accumulated:

**Nominal rigidity has no micro explanation.** Data from 60,000 prices shows individual prices change frequently and freely, yet aggregate prices are sticky. Both menu costs and Calvo pricing predict individual stickiness — both are flatly contradicted. Only [[entropic-forces]] explain how micro flexibility produces macro stickiness. There is no microeconomic explanation of nominal rigidity; it is purely emergent.

**The demand curve isn't shaped by human behavior.** Classroom experiments that supposedly demonstrate demand curves actually produce inverse survival curves of normal distributions — identical to what brainless atoms produce via the Maxwell velocity distribution. The downward slope comes from statistics, not from utility functions or preferences.

**The Walrasian auctioneer is entropy.** The theoretical construct ensuring no single agent affects prices in perfect competition is just entropy maximization. In the large-N limit, no individual agent impacts the outcome — the auctioneer is unnecessary because entropy does the same job.

**All major ITM results hold without behavioral assumptions.** The [[information-equilibrium]] framework requires only that there are "a lot" of supply and "a lot" of demand — not what the agents are or how they behave. The entire edifice of supply/demand, IS-LM, AD-AS, interest rates, and inflation can be derived without a single behavioral assumption.

## The emergent macro vision

"What would we say about macroeconomics if we didn't know about the existence of people, the same way Boltzmann didn't know about atoms?" Imagine aliens measuring CO2 fluctuations from a distant observatory — they'd see patterns (exponential growth, shocks, structural changes) and might propose a "civilization" whose components interact and exchange information. The CO2 measurement would be a proxy for information exchange — essentially the price level.

If humans have free will and don't behave perfectly rationally, why does economics math work so well when markets function? Because the same reason thermodynamics works: maximum entropy, not maximum utility. The agent-based model of economics is so complex it's indistinguishable from randomness — exactly the regime where maximum entropy approaches shine.

"To turn Tolstoy upside down: *all functioning markets are alike; each market failure fails in its own way.*"

The ultimate reductio: a community of *E. coli* bacteria appears to rationally maximize utility in a microbial "economy" — without a brain. The mathematical model in the research paper uses a utility-maximizing framework, but entropy maximization produces equivalent results. If brainless bacteria can exhibit "rational" market behavior, then rational decision-making doesn't explain markets — it merely saves the phenomena.

![E. coli "rational" market behavior](<../media/2015-08/ecoliutility.PNG>)

## Policy implications

Micro-details do matter for *policy* — tax incentives, healthcare economics — where you're trying to understand how micro changes affect macro outcomes. This is genuinely hard, even in physics: "the applicability of the degrees of freedom in the macrotheory usually breaks down before the applicability of the degrees of freedom in the microtheory really kick in." The ITM doesn't invalidate microeconomics; it says the macro theory doesn't need it as a foundation.
