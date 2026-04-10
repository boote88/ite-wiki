---
title: Mathematical Techniques Toolkit
type: synthesis
tags: [mathematics, methods, curve-fitting, statistics, econometrics, diem]
created: 2026-04-09
last_updated: 2026-04-09
---

# Mathematical Techniques Toolkit

A running catalog of the analytical and computational techniques Smith uses to do the work, organized by category. Companion to [[physics-toolkit]] (which covers conceptual frameworks borrowed from physics) — this page covers the *methods* of the math: how the fitting, modeling, validation, and visualization actually get done.

Updated as new techniques appear during ingest.

## Core analytical machinery

| Technique | How it's used | First appears | Wiki page |
|-----------|--------------|---------------|-----------|
| Ordinary differential equations | The fundamental ITM equation: $p = dq/du \leq (1/\kappa)(q/u)$. Solved analytically and numerically throughout | [Founding posts (2013-04)](../raw/2013/04/supply-and-demand-from-information.md) | [[information-transfer-model]] |
| Log-linearization | Converting nonlinear IE relationships to tractable linear form via $\log A = k \log B + b$. Enables linear regression on transformed data | [Aug 2016](../raw/2016/08/log-linear-form-of-general-information.md) | [[information-equilibrium]] |
| Chain rule / partial derivatives | Deriving multi-market relationships from composed IE relations. Inflation defined as instantaneous derivative of log price level | [May 2013](../raw/2013/05/money-as-medium-of-information-exchange.md) | [[money-as-bandwidth]] |
| Gronwall's inequality | Bounds non-ideal information transfer curves as upper envelopes of observed prices | [Founding posts (2013-04)](../raw/2013/04/supply-and-demand-from-information.md), [Jun 2016](../raw/2016/06/gronwalls-inequality-and-information.md) | [[non-ideal-information-transfer]] |
| Lyapunov exponents | Characterize sensitivity to initial conditions; connect κ to system stability/chaos | [May 2016](../raw/2016/05/lyapunov-exponents-and-information.md) | [[information-transfer-index]] |

## Curve fitting & estimation

| Technique | How it's used | First appears | Wiki page |
|-----------|--------------|---------------|-----------|
| Nonlinear least squares | Primary tool for fitting price level, inflation, employment models to FRED data | [Mar 2014](../raw/2014/03/macroeconomic-predictions-for-2016.html), [Mar 2015 code](../raw/2015/03/price-level-model-code.md) | [[predictions]] |
| LOESS smoothing | Locally weighted regression for de-noising data prior to fitting | [Mar 2015 code](../raw/2015/03/price-level-model-code.md) | [[predictions]] |
| Quadratic extrapolation | Extending NGDP, M0, MB time series for forward forecasts | [Mar 2014](../raw/2014/03/macroeconomic-predictions-for-2016.html) | [[predictions]] |
| Piecewise function fitting | Different parameter regimes pre-1980s, 1980s, post-1980s — handles structural breaks in unemployment dynamics | [Jan 2017](../raw/2017/01/dynamic-equilibrium-unemployment-rate.md) | [[predictions]] |
| Mathematica / Wolfram Language | All curve fitting, ODE integration, and visualization. Code samples published | [Mar 2015 code](../raw/2015/03/price-level-model-code.md) | — |

## Model selection & uncertainty

| Technique | How it's used | First appears | Wiki page |
|-----------|--------------|---------------|-----------|
| Information criteria (AIC/BIC) | Bound "relevant complexity" of underlying model. Justify why 2 or 5 parameters can match models with 29+ | [Jan 2017](../raw/2017/01/curve-fitting-and-relevant-complexity.md) | [[predictions]] |
| Error propagation / confidence bands | 70% and 90% intervals on all forecasts; enables formal comparison with Fed/DSGE bands | [Jan 2015](../raw/2015/01/not-bad-for-five-parameters-take-two.md) | [[predictions]] |
| Out-of-sample validation | Fit progressively longer windows (1960–70, 1960–75, …) and extrapolate to test stability | [May 2014](../raw/2014/05/out-of-sample-predictions-with.md) | [[predictions]] |
| Vintage (ALFRED) data analysis | Apples-to-apples comparison against forecasts made at the same time, using only data available *then* | [2018](../raw/2018/08/validating-forecasts-unemployment-rate.md) | [[predictions]] |

## Stochastic methods & simulation

| Technique | How it's used | First appears | Wiki page |
|-----------|--------------|---------------|-----------|
| Monte Carlo simulation | "Monte Carlo economy" — generate stochastic paths under random shocks; check analytic approximations | [Apr 2014](../raw/2014/04/monte-carlo-economy.md) | [[microfoundations-critique]] |
| A thousand random markets | Ensemble of randomly initialized markets to derive macro behavior | [Jun 2014](../raw/2014/06/a-thousand-random-markets.md) | [[microfoundations-critique]] |
| Wiener process simulation | Random walk with broken-pressure-gauge feedback to demonstrate emergent stickiness | [May 2013](../raw/2013/05/how-money-transfers-information-part-3.md) | [[sticky-prices]] |
| Ensemble averaging | Compute macro relationships as averages over micro state space without agent-level detail | [2014 H2](../sources/2014-h2-entropy-and-universality.md) | [[entropic-forces]] |
| Numerical ODE integration | Runge-Kutta and similar for closed-form-unavailable cases | [Apr 2014](../raw/2014/04/monte-carlo-economy.md) | — |

## Time series & econometrics

| Technique | How it's used | First appears | Wiki page |
|-----------|--------------|---------------|-----------|
| Granger causality | Shown to be equivalent to log-linear IE regression; reframes "causality testing" as IE detection | [Aug 2015](../raw/2015/08/granger-causality-is-information.md) | [[information-equilibrium]] |
| Principal component analysis (PCA) | Extract cyclical components from multi-sector employment data; remove correlated variation | [Mar 2017](../raw/2017/03/using-pca-to-remove-cyclical-effects.md) | — |
| VAR comparison | Benchmark DIEM against vector autoregressions; show DIEM has tighter confidence bands | [Apr 2018](../raw/2018/04/comparing-my-forecasts-to-vars.md) | [[predictions]] |
| Nonlinear signal detection | Identify large shocks (QE, Volcker disinflation) that violate linearity assumptions | [Aug 2015](../raw/2015/08/nonlinear-signals-of-unusual-size-nsuss.md) | — |
| Regime switching / structural breaks | Identify monetary regime changes; recession onset/offset dates | [Apr 2017](../raw/2017/04/determining-recessions-with-algorithm.md) | [[information-trap]] |

## Dynamic Information Equilibrium Model (DIEM)

The DIEM framework, introduced 2017, has its own characteristic mathematical toolkit:

| Technique | How it's used | First appears | Wiki page |
|-----------|--------------|---------------|-----------|
| Logistic / sigmoid step functions | Model recession transitions as smooth S-curves with onset, width, magnitude parameters | [Jan 2017](../raw/2017/01/dynamic-equilibrium-unemployment-rate.md) | [[predictions]] |
| Gaussian shock ansatz | Parameterize recession shocks as normal distributions in time | [Jan 2017](../raw/2017/01/curve-fitting-and-relevant-complexity.md) | [[predictions]] |
| Log-linear equilibrium + shock superposition | Decompose series into a log-linear dynamic equilibrium path plus discrete shock events | [Jan 2017](../raw/2017/01/dynamic-equilibrium-unemployment-rate.md) | [[predictions]] |
| Recession detection algorithm | Automated identification of recession center dates from unemployment / GDP series | [Apr 2017](../raw/2017/04/determining-recessions-with-algorithm.md) | [[predictions]] |
| Step response analysis | System response to unit shock; understanding policy transmission | [Nov 2017](../raw/2017/11/unemployment-rate-step-response-over.md) | [[predictions]] |

## Counterfactuals & visualization

| Technique | How it's used | First appears | Wiki page |
|-----------|--------------|---------------|-----------|
| Counterfactual construction | Modify model inputs to answer policy questions ("what if QE were permanent?", "what if 2% inflation since 1960?") | [Jun 2015](../raw/2015/06/counterfactuals-and-second-derivative.md) | [[fiscal-policy]] |
| 3D phase-space visualization | Plot price level surface P(M0, NGDP); 3D yield curves; 3D Phillips curves | [Jan 2014](../raw/2014/01/three-dimensional-thinking.md), [Feb 2014](../raw/2014/02/the-phillips-curve-in-3d.md) | [[information-trap]], [[phillips-curve]] |
| Animated S&D dynamics | Visualize entropy-driven supply/demand shocks as time-evolving animations | [Mar 2015](../raw/2015/03/supply-and-demand-as-entropy.md) | [[entropic-forces]] |

## Probability distributions

| Distribution | How it's used | First appears | Wiki page |
|--------------|--------------|---------------|-----------|
| Maxwell-Boltzmann | Demand curve shape derived as inverse CDF of normal price-estimate distribution | [Jan 2015](../raw/2015/01/is-demand-curve-shaped-by-human.md) | [[entropic-forces]] |
| Power laws | Income distributions, productivity scaling | [Feb 2016](../raw/2016/02/power-laws-and-information-equilibrium.md) | — |
| Log-normal | Modeling positive economic quantities with multiplicative noise | various | — |
| KL divergence (cross-entropy) | Measure information loss when expectations diverge from reality; quantifies limits of rational expectations | [May 2014](../raw/2014/05/expectations-destroy-information.md), [Aug 2015](../raw/2015/08/rational-expectations-and-information.md) | [[expectations]] |

## Data sources & infrastructure

| Resource | How it's used | First appears |
|----------|--------------|---------------|
| FRED (St. Louis Fed) | Primary data source for all US macro fitting | [Mar 2015 code](../raw/2015/03/price-level-model-code.md) |
| ALFRED (vintage FRED) | Real-time / vintage data for fair forecast comparisons | [2018](../raw/2018/08/validating-forecasts-unemployment-rate.md) |
| Mathematica notebooks | Published code for reproducibility | [Mar 2015 code](../raw/2015/03/price-level-model-code.md) |
