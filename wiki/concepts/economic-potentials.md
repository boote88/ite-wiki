---
title: Economic Potentials and Temperature
type: concept
tags: [thermodynamics, temperature, entropy, micro-macro, potentials, partition-function]
sources:
  - raw/2015/04/economic-potentials-or-how-to-define.md
  - raw/2014/09/the-economic-combinatorial-problem.md
  - raw/2014/10/coordination-costs-money-causes-recessions.md
  - raw/2016/07/an-ensemble-of-labor-markets.md
created: 2026-04-07
last_updated: 2026-04-09
---

# Economic Potentials and Temperature

Constructing the [[thermodynamic-analogies]] rigorously: defining thermodynamic potentials, economic temperature, and the separation of micro from macro forces.

## Definitions

| Thermodynamics | Economics |
|---|---|
| Energy | Nominal output $N$ |
| Pressure | Price level $P$ |
| Volume | Goods $X$ |
| Temperature $T$ | Economic temperature $\sim 1/\kappa$ |
| Entropy $S$ | Economic entropy (from combinatorics of market states) |

High [[information-transfer-index]] κ = low economic temperature (cold economy = [[information-trap]]). Low κ = high temperature (hot economy = [[quantity-theory-of-money]] regime).

## The thermodynamic potential

Using Stirling's approximation for large $N$:

$$dN = T \, dS + p \, dX + \sum_i p_i \, dx_i + P \, dM$$

where the sum is over individual market "generalized forces" (microeconomic forces). The $TS$ term represents [[entropic-forces]] (macroeconomic forces). The $PM$ term is the monetary component.

## Micro vs. macro forces

For an economy with aggregate goods market $A$ and labor market $L$:

$$dN = T \, dS + P \, dM + P_A \, dA + P_L \, dL$$

The key insight: **only $TS$ (entropic forces) should be considered truly macroeconomic**. The other terms ($PM$, $P_A dA$, $P_L dL$) are "microeconomic" generalized forces — they behave like individual market forces. However, $PM$ is so large and policy-relevant that it's grouped with macro.

This cleanly separates:
- **Micro forces**: individual market prices × quantities (including monetary policy)
- **Macro forces**: entropy-driven phenomena (recessions, [[sticky-prices]], [[secular-stagnation]])

Macro forces have no microeconomic representation — they are emergent, reinforcing the [[microfoundations-critique]].

## Partition function over labor markets

The temperature picture extends to a full statistical-mechanical treatment of [[labor-market|labor markets]]. Treat the economy as an ensemble of markets each with its own information transfer index $p_i$ ("productivity state"). Define the partition function $Z = \sum_i \ell^{p_i}$ and compute ensemble averages $\langle X \rangle = (1/Z) \sum X_i \ell^{p_i}$. The result reproduces NGDP-vs-employment data and reveals something striking: **as the labor supply grows, the average productivity falls.** A larger labor force means more ways to be organized as many low-growth markets than as a few high-growth ones — exactly the same counting argument that makes large monetary economies "cold." A bigger economy is a colder economy regardless of which side (money or labor) you count from.

This also gives a clean separation of general from partial equilibrium. The distribution of $p_i$ values *is* the macroeconomic general equilibrium. Partial equilibrium analysis (Econ 101) looks at moves *within* the distribution that don't change its shape. When the distribution itself shifts (as during recessions), partial equilibrium reasoning fails — you've moved to a new general equilibrium and the textbook tools don't work anymore.

The framework also unifies output gaps and unemployment: both are deviations from the same general equilibrium, with the output gap being the difference between actual and equilibrium NGDP, and the unemployment rate being the difference between actual and equilibrium price level (CPI). One coherent story for two of the most important macroeconomic measurements.

## Laser vs blackbody: balanced growth done right

Mainstream growth theory's "balanced growth path" assumption — that everything grows at the same rate to avoid one piece of the economy dominating — turns out to be the equivalent of insisting every atom in a gas must have the same energy in order for the gas to have a well-defined temperature. It's wrong. The macroeconomy can have a well-defined average growth rate $\gamma \langle k \rangle$ while individual markets occupy different growth states drawn from the maximum-entropy Gibbs distribution. The economists' picture is a **laser** (all photons in the same eigenstate, all markets growing at the same rate); the right picture is a **blackbody** (an ensemble of states with a well-defined temperature, an ensemble of markets with a well-defined average growth rate). Both have well-defined macro observables; only the second is consistent with what economies actually do.

This also clarifies the [[information-trap]] story. The Gibbs measure says high-$k$ states are exponentially less likely than low-$k$ states, and the suppression gets stronger as the factor of production grows. This is why mature economies trend toward the low-growth/low-inflation regime — not because of any policy failure, but because there are exponentially more configurations made up of many low-growth markets than a few high-growth ones. [[secular-stagnation]] is built into the partition function.
