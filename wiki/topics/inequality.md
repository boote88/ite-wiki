---
title: Inequality
type: topic
tags: [inequality, pareto, ubi, dimensionality, instability]
sources:
  - raw/2016/11/inequality-and-maximum-entropy.md
created: 2026-04-09
last_updated: 2026-04-09
---

# Inequality

The [[information-transfer-model]] gives an unusual angle on inequality: high inequality reduces the **effective dimensionality** of the economic state space, making the system more susceptible to coordination failures and macroeconomic instability. The argument is structural rather than ethical, and it produces concrete (and surprising) policy implications.

## Pareto vs uniform: same maximum entropy, different stability

Income is empirically Pareto-distributed (especially in the tail) — Vilfredo Pareto's original observation. This is sometimes interpreted as evidence that inequality is somehow optimal, since Pareto distributions are themselves maximum-entropy distributions (under a specific constraint: fixed $\langle \log x \rangle$). But uniform distributions are *also* maximum-entropy distributions, under a different constraint ($x$ bounded). Both are perfectly valid maxent solutions; which one you get depends on which constraint binds.

The interesting question isn't whether Pareto is "natural" — it is, in the sense that it's the easiest distribution to achieve via random processes. The interesting question is what consequences each distribution has for macroeconomic dynamics.

## Inequality reduces effective dimensionality

Take an economy with $N$ agents, each with income drawn from a Pareto distribution, each able to choose how to allocate consumption. Total consumption is bounded by total resources, so the allowed states form an $N-1$ simplex. But here's the catch: the Pareto distribution is so skewed that only a small number of high-income agents matter for the dynamics. The rest of the simplex, containing the low-income agents, has tiny resource weight. Effectively the high-dimensional region collapses to an $n \ll N$ dimensional region.

Compare this to a uniform-income economy with the same total resources. The state space is an evenly-weighted simplex; all $N$ agents matter equally; the effective dimensionality is the full $N$.

![Uniform vs Pareto-bounded simplices](<../media/2016-11/inequality and maxent 4.png>)

What happens when you run random walks in these two regions? Given the **same set of shocks**, the Pareto-bounded economy shows much **larger total variance** in consumption than the uniform-bounded one. Fewer effective dimensions means each shock has a bigger relative effect on the aggregate.

![Time series: Pareto (blue) vs uniform (yellow), same shocks](<../media/2016-11/inequality and maxent 1.png>)

## Why this matters for coordination

The dimensionality reduction has a second consequence: it makes coordination failures easier. Coordinating $n$ agents into a panic is much easier than coordinating $N$ agents — the relevant probability scales as something like $1/n$ vs $1/N$. So a Pareto-distributed economy is more vulnerable to the kind of [[entropic-forces|spontaneous coordination]] that produces [[recessions]]. High-income agents move together more easily than the full population would; a financial crisis triggered among the top 1% can drag the whole economy down because those are the dimensions that carry the macroeconomic variance.

The connection to inequality and stability isn't moral — it's geometric. A more equal economy has more effective dimensions, which makes it both **less variable** under random shocks and **more resistant** to coordination panics.

## Policy implications

The framework gives a clean geometric picture of how progressive taxation and a universal basic income work to restore dimensionality:

- **Progressive income tax** acts as a soft upper bound on the high-income dimensions, pulling the Pareto simplex closer to the uniform one.
- **Universal basic income (UBI)** acts as a lower bound on every dimension, ensuring no agent has effectively zero economic weight.

Together, these two policies "sandwich" the Pareto region into a smaller and more symmetric shape — closer to uniform, with higher effective dimensionality and more macroeconomic stability. This is a structural argument for redistribution that doesn't depend on any particular ethical premise. Even if you don't care about fairness, you should care about the variance.

## Connection to other ITM concepts

Inequality fits naturally into the maximum-entropy / [[entropic-forces]] picture. The argument echoes the [[fiat-money-paradox]] story (money as a dissipative structure that exists to maximize entropy production — heat death is the equal allocation) and the [[emergent-representative-agent]] story (high dimensionality is what makes the law of large numbers work). It's another instance of the broader pattern: macro behavior depends on the *geometry* of the state space, not on agent psychology. Inequality changes the geometry, and the dynamics follow.
