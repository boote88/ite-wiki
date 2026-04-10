---
title: Information Transfer Index (κ)
type: concept
tags: [core-framework, kappa, information-theory, empirical]
sources:
  - raw/2013/04/the-information-transfer-model.md
  - raw/2013/06/what-role-does-information-transfer.md
  - raw/2013/06/more-on-information-transfer-index.md
  - raw/2013/06/even-more-on-information-transfer-index.md
  - raw/2013/06/is-there-structure-to-behavior-of.md
created: 2026-04-07
last_updated: 2026-04-07
---

# Information Transfer Index (κ)

The **information transfer index** $\kappa$ is a central parameter of the [[information-transfer-model]], governing the relationship between supply and demand information encoding.

## Definition

$$\kappa = \frac{K_u^s}{K_q^s} = \frac{K_0 \log \sigma^s}{K_0 \log \sigma^d}$$

where $\sigma^s$ and $\sigma^d$ are the number of symbols used by supply and demand respectively. Empirically, $\sigma^x \sim Q^x / Q^x_{\text{ref}}$ — the number of symbols scales with quantity relative to a reference.

## Economic interpretation

| κ value | Meaning |
|---|---|
| $\kappa < 1$ | Demand information outpaces supply → prices tend to rise ([[inflation]]) |
| $\kappa = 1$ | Ideal balance — supply and demand symbol counts match |
| $\kappa > 1$ | Supply outpaces demand → prices tend to fall |

- κ can be measured from **price elasticities** of supply and demand
- Larger economies should approach $\kappa = 1$ more monotonically
- κ fluctuations may drive **business cycles** — recessions when κ falls below its mean

## Empirical results

Using NGDP and the monetary base as inputs, κ follows a roughly **quadratic trend** over time for the US economy. Combined with a single normalization parameter (~375 billion for the monetary base), this fits the CPI remarkably well.

The model can be solved multiple ways:
- NGDP + MB → price level and κ
- NGDP + CPI → monetary base and κ

Both approaches give consistent results.

## Regime change across the 2008 crisis

A monetarist analysis (fitting $\log P \sim k \log \text{MB}$) inadvertently produces an information transfer model — but one where k dropped sharply from 0.763 to 0.125 during the financial crisis. Converting: k = 0.763 corresponds to κ = 0.57 (near the [[quantity-theory-of-money]] limit of 1/2), while k = 0.125 corresponds to κ = 0.89 (near the [[information-trap]] limit of 1). Monetary policy became **six times less effective** overnight. Before 2008, doubling the monetary base would produce a 70% price increase; after 2008, only 9%.

Using M0 (currency, not the full base) instead of MB, the regime change is not sudden but gradual — κ has been rising steadily since the 1960s. The 2008 "sudden onset" is an artifact of using the wrong aggregate.

## Phase transition

At ~7% monetary base growth rate, κ behavior undergoes a structural change:
- **Below ~7%**: κ steadily declines over time (persistent information mismatch)
- **Above ~7%**: κ increases toward 1 (economy self-corrects toward ideal information transfer)

This suggests high-inflation economies naturally drive toward ideal information transfer, while low-inflation economies maintain a persistent gap.

## Connection to thermodynamics

In the [[thermodynamic-analogies]], $\kappa \sim 1$ corresponds to a two-dimensional ideal gas. The value of κ relates to the effective "degrees of freedom" of the economic system.

## κ as a Lyapunov exponent

A deeper mathematical observation: rewriting the IE solution in exponential form makes clear that κ is the **Lyapunov exponent** of the information equilibrium dynamical system, with $\lambda = 1/(k A_0)$. A positive λ — which is the empirically typical case in economics — means the system is **chaotic** in the technical sense: trajectories with similar initial conditions diverge exponentially in phase space.

This isn't just metaphor. It explains why precise long-run predictions are intrinsically difficult (you're integrating a chaotic system) and why hyperinflation under pegged interest rates exhibits maximum chaos (the peg breaks the IE structure that would otherwise damp the dynamics — see [[information-trap]]). It also gives a route to applications outside economics: the same scale-dependent Lyapunov exponent shows up in EEG analysis and other neuroscience contexts where the IE framework can be reused.

## References

- [What role does the information transfer index play? (2013-06-19)](../../raw/2013/06/what-role-does-information-transfer.md)
- [More on the information transfer index (2013-06-22)](../../raw/2013/06/more-on-information-transfer-index.md)
- [Even more on the information transfer index (2013-06-23)](../../raw/2013/06/even-more-on-information-transfer-index.md)
- [Is there structure to the behavior of MB growth rates? (2013-06-29)](../../raw/2013/06/is-there-structure-to-behavior-of.md)
