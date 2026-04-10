---
title: Standard Economic Results Derived from Information Equilibrium
type: synthesis
tags: [reference, derivations, scope, mainstream-economics]
sources:
  - raw/2016/07/list-of-standard-economics-derived-from.md
created: 2026-04-09
last_updated: 2026-04-09
---

# Standard Economic Results Derived from Information Equilibrium

A reference catalog of mainstream economic models, results, and relationships that fall out of the [[information-equilibrium]] framework. The point isn't that these results are "correct" — they're approximate, regime-dependent, and sometimes wrong — but that the IE framework **subsumes** them. Mainstream economics is recovered as a special case in the same way Newtonian mechanics is recovered from general relativity at low velocities. The list serves as both empirical evidence that the framework is connected to mainstream economics and as a guide to which approximations apply when.

This list grows over time as Smith finds new mainstream results to derive. It's organized by topic for navigation.

## Microeconomics

- **[[supply-and-demand]]** — derived from $P : D \rightleftarrows S$ with constant or floating sources
- **Price elasticities** — fall out of the IE differential equation; κ relates to elasticity values
- **Utility maximization** — emerges as the first-order effective theory near an economic equilibrium ([[emergent-representative-agent]])
- **Cobb-Douglas production functions** — the natural form for two simultaneous IE relationships sharing a common variable
- **"Econ 101" effects of price ceilings and floors** — derivable, but with the important caveat that they're partial-equilibrium results that often don't survive general equilibrium (see [[minimum-wage]])

## Aggregate macroeconomics

- **[[ad-as-model]]** — directly from $P : N \rightleftarrows S$ with $P$ as the price level
- **[[is-lm-model]]** — derived as the effective theory of AD-AS at low inflation; multiple IE relationships through the interest rate
- **[[quantity-theory-of-money]]** — the limit of the price level model when κ ≈ 1/2
- **[[solow-growth-model]]** — Cobb-Douglas form with $\beta + \gamma \neq 1$ from two IE relationships through NGDP
- **Kaldor facts** — express directly as IE relationships
- **Cagan model** of hyperinflation — recovered as a limit
- **DSGE models** — the IE framework can be written in DSGE form (without expectations). The full **three-equation New Keynesian DSGE model** (Taylor rule + IS curve + Phillips curve) is derivable from a chain of IE relationships plus a maximum-entropy condition on intertemporal consumption. The IE versions of "model-consistent expectations" and "stochastic innovation" terms emerge from the maximum-entropy structure rather than being assumed; the Phillips curve term acquires a slight bias toward closing the output gap because the maximum entropy state is "the most likely" outcome

![DSGE flow diagram from IE relationships](<../media/2016-08/flowdiagram.png>)
- **Lucas Islands model** — recoverable in a multi-market IE setup

## Money and finance

- **Diamond-Dybvig** bank runs — from maximum entropy in a high-dimensional polytope (no game theory needed; see [[entropic-forces]])
- **Asset pricing equation** — basic asset pricing as an IE relationship
- **Euler equation** — emerges from maximum entropy with appropriate constraints
- **Mundell-Fleming model / Metzler diagrams** — derivable in the IE framework

## International

- **[[international-trade|Gravity models of trade]]** — the standard gravity equation falls out of $T \to N_1$ and $T \to N_2$
- **Comparative advantage** — from maximum entropy over consumption sets when trade is allowed (see [[international-trade]])

## Toy and pedagogical models

- **MINIMAC** — recovered as an IE model
- **Random walks → demand curves** — see [[supply-and-demand]] and the diffusion-length PPF result

## What this means

The breadth of derivations is itself the diagnostic. Mainstream economics has many separate models, each with its own assumptions and motivations, each treated as standalone. The IE framework derives all of them from the same starting point — two quantities in information equilibrium with a price as detector — varying only in which quantities are involved and what scope conditions apply. This is what it looks like when a framework actually unifies a field, as opposed to merely collecting results.

The contrast with the [[microfoundations-critique|microfoundations]] program is sharp. Microfoundations says "build everything up from rational agents." Information equilibrium says "the framework is much simpler than that, and most of what we already think we know follows from a single principle." Many of the items on this list — comparative advantage, utility maximization, Diamond-Dybvig bank runs — are usually derived through agent-based reasoning. The IE versions don't need agents.
