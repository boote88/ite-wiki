---
title: "April 2013: Founding Posts"
type: source
tags: [founding, information-transfer-model, supply-demand, sticky-prices]
sources:
  - raw/2013/04/an-informal-abstract.md
  - raw/2013/04/an-informal-abstract-addition-why-now.md
  - raw/2013/04/the-information-transfer-model.md
  - raw/2013/04/supply-and-demand-from-information.md
  - raw/2013/04/the-previous-post-with-more-words-and.md
  - raw/2013/04/the-philosophical-motivations.md
  - raw/2013/04/sticky-prices-from-non-ideal.md
  - raw/2013/04/are-thermodynamic-analogies-useful.md
created: 2026-04-07
last_updated: 2026-04-07
---

# April 2013: Founding Posts

The blog launches with 8 posts in 4 days (April 24–27, 2013), establishing the entire foundation of the [[information-transfer-model]].

## Context and motivation

Jason Smith, a physicist working in industry, encounters two ideas that collide productively:

1. **[[fielitz-borchardt]]'s information transfer model** — a paper applying information theory to natural processes (ideal gas law, Fick's law, Hubble's law) without needing to choose specific constraints. Smith sees potential to apply this to economics.
2. **Hayek's description of the price system** as an information-communicating mechanism — combined with Krugman's observation that supply and demand curves are hard to derive from first principles but everyone uses them anyway.

The catalyst: [Noah Smith's post](http://noahpinionblog.blogspot.com/2013/04/the-reason-macroeconomics-doesnt-work.html) arguing macroeconomics doesn't work well because there's limited empirical information to choose between alternatives.

Smith's goal: derive supply and demand from information theory, producing a framework rigorous enough to *eliminate* alternative models. The blog is conceived as a "working paper" — thinking out loud rather than formal publication.

**Key distinction:** "Information" here means Shannon information (signal transmission), not "information economics" (Akerlof, Stiglitz).

## The information transfer model formalism

Using [[fielitz-borchardt]]'s framework and the Hartley definition of information:

- A **process source** $q$ (demand) transmits information to a **process destination** $u$ (supply)
- Information transfer satisfies $I_u \leq I_q$ (you can lose but not gain information)
- The **price** $p$ is the "detector" measuring the signal: $p = dq/du$
- The **information transfer index** $\kappa = K_u^s / K_q^s$ parameterizes the system
- In the continuum limit: $p = dq/du \leq \frac{1}{\kappa} \frac{q}{u}$

See [[information-transfer-model]] for details.

## Deriving supply and demand

From the formalism, holding one side constant and varying the other:

- **Demand curve** (constant demand source $Q_0^d$): traces out downward-sloping curve, recovering diminishing marginal utility
- **Supply curve** (constant supply destination $Q_0^s$): traces out upward-sloping curve
- **Linearization** recovers the textbook $Q^d = \alpha - \beta P$, $Q^s = \gamma + \delta P$

See [[supply-and-demand]] for the derivation.

## Sticky prices from non-ideal transfer

When information transfer is imperfect ($I_{Q^s} < I_{Q^d}$), the ideal supply/demand curves become *upper bounds* on observed prices (via Gronwall's inequality). This creates a region where prices can "stick":

- Small demand shifts don't move the price — it stays within the allowed region
- Large shifts push the price to the boundary, where normal S&D behavior resumes
- Prices tend to be stickier downward than upward, implying the observed price sits nearer the lower bound of the information gap

This is speculative — Smith notes the sticky trajectory is *consistent with* but not *required by* the equations.

See [[non-ideal-information-transfer]] and [[sticky-prices]].

## Thermodynamic analogies

The ITM maps directly onto thermodynamic concepts:
- Price ↔ Pressure
- Demand ↔ Work/Energy (related to temperature)
- Supply ↔ Volume

Movement along the demand curve is analogous to an isothermal process. Sticky prices may correspond to isoentropic (reversible) processes where the number of microstates stays constant.

See [[thermodynamic-analogies]].

## The philosophical vision

Smith draws an explicit parallel between his project and physics:
- **DSGE models** are to economics what **string theory** is to physics — beautiful mathematics, limited empirical contact
- Just as Verlinde proposed gravity as an emergent entropic force, Smith aims to describe macroeconomics as *emergent* — without needing to know the details of individual human behavior
- Boltzmann didn't need to know about atoms; he just needed to know there were a lot of them (~$10^{23}$)
- Microfoundations likely don't survive aggregation as anything more than a coefficient (slope and intercept of a line)

## Open questions raised

1. What causes the information gap (non-ideal transfer)? Possibly: goods that are hard to assess, or markets assessed infrequently
2. How does the price trajectory actually behave in the sticky region? Stochastic models (Markov information sources) might help
3. Are the thermodynamic analogies merely formal, or do they reveal real structure?
4. How does inflation fit into the framework?
