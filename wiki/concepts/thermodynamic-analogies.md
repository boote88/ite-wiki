---
title: Thermodynamic Analogies
type: concept
tags: [thermodynamics, ideal-gas, isoentropic]
sources:
  - raw/2013/04/the-previous-post-with-more-words-and.md
  - raw/2013/04/are-thermodynamic-analogies-useful.md
created: 2026-04-07
last_updated: 2026-04-07
---

# Thermodynamic Analogies

The [[information-transfer-model]] maps directly onto ideal gas thermodynamics via the [[fielitz-borchardt]] framework, which was originally developed for physical processes.

## Core mapping

| Economics | Thermodynamics |
|---|---|
| Price $P$ | Pressure $p$ |
| Demand $Q^d$ | Work / Energy (related to temperature) |
| Supply $Q^s$ | Volume $V$ |
| Price–supply–demand relation | Ideal gas law $pV = nRT$ |

## Thermodynamic processes in economics

- **Movement along the demand curve** (constant $Q_0^d$) ↔ **Isothermal process** (constant temperature)
- **[[sticky-prices]]** may correspond to **isoentropic processes** — the number of microstates consistent with the macrostate stays constant. Supply and demand still change, but the entropy of the market state doesn't.

## Speculative implications

If $\kappa \sim 1$ (as suggested by observed price elasticities), an isoentropic process could obey a specific power law relating price and supply changes. In the thermodynamic case, $\kappa = 1$ corresponds to a two-dimensional ideal gas (two degrees of freedom).

Smith's assessment (April 2013): "The short answer is: I have no idea [if the analogies are useful]. It is fun to think about."

## From analogy to rigor: [[economic-potentials]]

The analogy became rigorous with the construction of actual **thermodynamic potentials** for the economy:

$$dN = T \, dS + p \, dX + \sum_i p_i \, dx_i + P \, dM$$

This defines an **economic temperature** $T \sim 1/\kappa$: high κ = cold economy ([[information-trap]]); low κ = hot economy ([[quantity-theory-of-money]]). It cleanly separates micro forces (individual market prices × quantities) from macro forces (entropy-driven, emergent).

This resolves the 2013 question: the analogies are **not merely formal** — they reveal the actual mathematical structure of macroeconomics. The economy has a well-defined temperature, entropy, and thermodynamic potential.

## Philosophical connection

The thermodynamic analogy supports Smith's broader vision: macroeconomics as an *emergent* theory, analogous to how thermodynamics emerges from statistical mechanics without needing to know the details of individual particles. The [[microfoundations-critique]] follows naturally — if macro works like thermodynamics, building it up from individual agent behavior is as unnecessary as deriving gas pressure from individual molecular trajectories.

## References

- [The previous post with more words (2013-04-25)](../../raw/2013/04/the-previous-post-with-more-words-and.md)
- [Are the thermodynamic analogies useful? (2013-04-27)](../../raw/2013/04/are-thermodynamic-analogies-useful.md)
- [Economic potentials (2015-04-25)](../../raw/2015/04/economic-potentials-or-how-to-define.md)
