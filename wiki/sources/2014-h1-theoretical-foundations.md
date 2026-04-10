---
title: "2014 H1: Theoretical Foundations"
type: source
tags: [m0-vs-mb, efficiency, entropic-forces, counterfactuals, field-theory, predictions]
sources:
  - raw/2014/01/
  - raw/2014/02/
  - raw/2014/03/
  - raw/2014/04/
  - raw/2014/05/
  - raw/2014/06/
created: 2026-04-07
last_updated: 2026-04-07
---

# 2014 H1: Theoretical Foundations (120 posts)

The first half of 2014 deepens the [[information-transfer-model]] from empirical pattern-matching to theoretical rigor. Key themes: distinguishing currency from reserves, formalizing information transfer efficiency, connecting to physics (effective field theory, entropic forces), and empirical validation via counterfactuals and cross-country data.

## Currency vs. reserves: M0 and MB (Jan–Feb)

A critical discovery: **use M0 (currency in circulation) for the price level model**, but **MB (monetary base = currency + reserves) for interest rates**.

- P:NGDP→M0 determines price level and inflation
- r:NGDP→MB determines short-term interest rates
- Long-term rates (10-year) relate to M0; short rates (3-month) relate to MB

This explains why QE's massive reserve injections had minimal inflation impact — reserves don't enter the price level equation. Only M0 matters for prices. Model residuals confirm: M0 gives mean error 0.03, MB 0.04, constant κ 0.10, QTM 0.37.

See [[currency-vs-reserves]].

Key chart: M0 vs MB correlation collapse 2008–2014, showing reserves causally irrelevant to inflation (raw/2014/11/media/).

## Information transfer efficiency ε (Mar)

Define ε such that realized information transfer = ε × ideal:

$$\varepsilon \cdot I_D = I_S$$

Fluctuations in ε at the macroeconomic level correspond to all markets sharing a common efficiency factor — providing the [[plucking-model]] with a formal mechanism. The interest rate market adjusts via price (interest rate changes); the unemployment market adjusts via quantity (employment changes). Both responses are consistent with common underlying ε fluctuations.

## Counterfactual analysis: ARRA and QE (Jan)

Using the ITM framework for counterfactual analysis:

- **ARRA fiscal stimulus** reduced unemployment peak from ~13% to 10% (2.5pp effect)
- **Fiscal multiplier** ≈ 1.25, consistent with CBO/IMF estimates
- **Monetary offset** of fiscal policy was minimal (~2%) — Fed couldn't sterilize fiscal expansion near the [[information-trap]]
- If QE hadn't occurred, deflation would have been much more severe

Key visualizations: counterfactual NGDP/unemployment paths with and without ARRA (raw/2014/01/media/).

## Two kinds of stickiness (Jan)

- **Relative stickiness**: κ-dependent, path-dependent, visible in money market. Standard [[sticky-prices]] from [[non-ideal-information-transfer]]
- **Absolute stickiness**: invariant over time, visible in labor market. P:NGDP→L determines employment; P:NGDP→NW is nearly constant. Result: NGDP shocks channeled through employment *quantity*, not wage *price*

This explains why unemployment adjusts rather than wages — a micro-independent mechanism.

## Effective field theory approach (Feb)

Long-run neutrality of money (homogeneity of degree zero) + lowest-order differential equation consistency → κ = log(S)/log(D). Higher-order terms suppressed by factors involving monetary base size (multi-party transaction complexity). This provides theoretical justification for why the simple ITM equations work despite the economy's complexity.

## How money transfers information (Mar)

Step-by-step mechanistic explanation:
- Buyers (d) send log₂(d) bits per transaction
- Sellers capture I_s = n_s·log₂(s) bits
- Money (m tokens) allows sellers to estimate market size: each token carries log₂(m) bits
- Price level emerges as P ~ dM/dS
- κ = log(m)/log(d) accounts for unit of account effect

Key diagram: step-by-step information flow from buyers→sellers→price formation (raw/2014/03/media/).

## IS curve regime transitions (Jun)

IS curves evolved over decades:
- **Early 1960s** (low κ): steep downward slope → monetarist regime, monetary policy effective
- **1970s–80s**: moderate slope → transitional
- **2008 onward** (high κ): vertical/backward-bending → liquidity trap, monetary policy ineffective

Key visualization: IS curve evolution in normalized ±30% windows showing regime transitions (raw/2014/06/media/). "Spaghetti" bending away from countertop at ZLB.

## Predictions (Mar)

Quadratic extrapolation of 2013–2014 data predicts for 2016:
- Inflation ~1.8% (undershooting 2% target)
- RGDP growth ~2.9%
- Unemployment stabilization Q3 2014–Q1 2015
- Long rates near 2.5%

*[2017 update notes: predictions were successful]*

## Entropic forces and causality (May)

No "mechanical" causality in the ITM — only **statistical inevitability**. If macrostate r₁ → r₂, then m₁ → m₂ is overwhelmingly probable (law of large numbers). Reverse causality equally valid. Like diffusion: smell fills a house regardless of where the cooking happens.

## Expectations as information loss (May)

Wrong expectations cause **KL divergence** (information loss). Simulations show:
- Long tail of large losses when expectations are severely wrong
- Least informative prior (maximum ignorance) performs best on average
- Supports the ITM's maximum entropy approach over rational expectations

Key chart: KL divergence histogram comparing perturbation vs. random vs. least informative prior (raw/2014/05/media/).

## Neo-Fisherite mechanism (May)

The [[information-trap]] provides a mechanism for the neo-Fisherite position: holding interest rates low causes *faster* entry into the deflationary regime. Lower rates run into the ∂P/∂M0 = 0 line at a lower monetary base than higher rates.

Key visualization: 3D P(M0, NGDP) with red interest rate level curves showing how low rates approach information trap earlier (raw/2014/05/media/).

## Lakatosian research program (Jun)

Smith frames the ITM as a Lakatosian research program:
- **Hard core**: demand = information source, supply = destination, price = detector; dynamics via p = (1/κ)(D/S)
- **Auxiliary hypotheses**: macro = micro scaling, varying κ, interest rate exponent
- **Two approaches**: macro as aggregate of S&D, or macro as ensemble average of micro markets
