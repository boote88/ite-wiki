---
title: Expectations
type: topic
tags: [expectations, rational-expectations, market-monetarism, methodology]
sources:
  - raw/2015/02/expectations.md
  - raw/2015/01/i-have-no-idea-what-you-are-talking.md
created: 2026-04-07
last_updated: 2026-04-07
---

# Expectations in the ITM Framework

Smith diverges from mainstream economics in two ways on expectations: their **arbitrariness** and their **centrality**.

## Arbitrariness

While physics has the Schrödinger equation to constrain unobservable wavefunctions, economics has no universally accepted constraints on what expectations are allowed to be. Macroeconomists typically make up plausible-sounding assumptions, put them in the theory, and see what happens. This leads to "chameleon models" (Pfleiderer) — models built on dubious assumptions whose conclusions are uncritically applied.

Rational expectations (model-consistent expectations) shift the arbitrariness from expectations to the model itself. This is fine if you test against data, but most don't.

## Centrality — the T0/TK thought experiment

Smith's sharpest argument against expectations-centered economics. Assume a true fundamental theory T0 exists but is unknown, and the market believes a wrong theory TK. What happens?

- Expectations based on TK can only have **limited impact** — they cause volatility but T0 governs the long run
- To escape this, economists must assume one of four things:

| Option | Assumption | Problem |
|---|---|---|
| 1. Markets always right | T0 is known | Assumes you already know the answer |
| 2. Rational expectations | TK is right | Any model can be right; only data can decide |
| 3. Expectations are central | T0 = whatever markets believe | Convincing markets Keynesianism is right *makes* it right; no reason to prefer monetarism |
| 4. Markets right + expectations central | T0 known AND T0 = expectations | [[scott-sumner]]'s position: assumes you're right *and* everyone knows it |

All four "are excellent options if you are extremely confident you are correct and don't care about comparing your model to empirical data."

## The ITM position

In [[information-equilibrium]], expectations are the **average over all expectations consistent with macro conditions** — like thermodynamics taking the most likely pressure given volume and temperature. There are so many people with so many different inflation expectations that the final result depends entirely on how big M is. See [[entropic-forces]].

Expectations have real effects (they can cause volatility/information loss), but they cannot override the fundamental information-theoretic relationships. A central bank cannot hold inflation at 2% indefinitely — economies that try will eventually fail.

The key question to [[scott-sumner]]: **"What happens to your theory if markets don't believe market monetarism?"**

## The limits of rational expectations — quantified

The ITM provides the first macroeconomic estimate of when rational expectations breaks down, without comparing to an alternative model of expectations. The KL divergence between the true distribution A and the learned approximation B measures information loss:

$$D(A \| B) = \Delta I \sim P - dN/dM$$

This compares how much the economy *should* grow from monetary expansion (ideally) to how much it *actually* grows. The information loss ΔI is proportional to **nominal shocks** — the difference between actual NGDP and what it would be based on M0 growth alone. Since nominal shocks are basically the size of the business cycle, this means **rational expectations are not a useful approximation when analyzing the business cycle** — precisely the domain where they're most commonly deployed.

Rational expectations work fine in stable periods (small ΔI), just as Newton's laws work at low velocities. They fail badly during recessions, when information loss is large. The analog: trying to apply Newtonian mechanics at relativistic speeds.
