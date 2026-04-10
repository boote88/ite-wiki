---
title: "June 2013: Empirical Validation"
type: source
tags: [kappa, empirical, inflation, monetary-base, qtm, cpi]
sources:
  - raw/2013/06/does-multiplying-monetary-base-by-2-cut.md
  - raw/2013/06/what-role-does-information-transfer.md
  - raw/2013/06/more-on-information-transfer-index.md
  - raw/2013/06/even-more-on-information-transfer-index.md
  - raw/2013/06/inflation-rate-derived-from-information.md
  - raw/2013/06/this-is-getting-interesting-monetary.md
  - raw/2013/06/real-growth.md
  - raw/2013/06/deriving-price-level-from-ngdp-and.md
  - raw/2013/06/which-is-failing-itm-or-qtm.md
  - raw/2013/06/is-there-structure-to-behavior-of.md
created: 2026-04-07
last_updated: 2026-04-07
---

# June 2013: Empirical Validation

10 posts that transform the ITM from a theoretical curiosity into a quantitative model. Smith derives the price level, inflation rate, and real GDP growth from just NGDP and the monetary base with a single free parameter — and it works.

## The information transfer index κ (June 19–22)

The [[information-transfer-index]] $\kappa = K_0 \log \sigma^s / K_0 \log \sigma^d$ becomes the central variable:

- When $\kappa < 1$: demand information outpaces supply → prices rise
- When $\kappa > 1$: supply outpaces demand → prices fall
- Inflation occurs when $\langle \kappa \rangle < 1$ on average
- Recessions may occur when κ falls below its mean
- Empirically, $\sigma^x \sim Q^x / Q^x_{\text{ref}}$ — the number of symbols is proportional to quantity relative to a reference

Larger economies should approach $\kappa = 1$ more monotonically (supply and demand in balance).

## Deriving the price level from data (June 23–28)

**The breakthrough**: using empirically-derived κ (with a quadratic trend) plus NGDP and the monetary base, Smith fits the CPI with a single normalization parameter (~375 billion). This is described as the first time the ITM shows "real capability beyond notional aspects of supply and demand."

The model can be solved in multiple directions:
- **Forward**: NGDP + MB → price level (June 23, 28)
- **Inverse**: NGDP + CPI → monetary base (June 24)
- Both give remarkably similar results — a robustness validation

Key result: inflation rate derived from just two inputs (NGDP and MB) with one parameter. Smith calls this "a major success."

## Monetary base and QE (June 23–24)

The model reveals:
- If κ had followed its quadratic trend without QE, there would have been **much more serious deflation** post-2008
- QE was **insufficient** — the model suggests it needed to be roughly twice as large
- Major deviations between model and CPI occur during **unconventional monetary policy** (Volcker disinflation, QE periods)

## Money value is logarithmic, not linear (June 19)

Standard economics assumes doubling the monetary base halves cash value (1/x relationship). The ITM predicts a **logarithmic** relationship: doubling MB reduces cash value to ~$1/e \approx 0.37$, not 0.5. Doubling the "bits" available to describe the economy follows information-theoretic scaling.

## ITM subsumes the Quantity Theory of Money (June 29)

Testing against Barro textbook data on inflation vs. monetary base growth:
- Pure QTM predicts 1:1 relationship; breaks down at low inflation
- ITM + QTM works well even at low inflation where QTM alone fails
- QTM is effectively nested within the ITM framework as a special case

## Phase transition at ~7% inflation (June 29)

Analyzing κ behavior across different monetary base growth rates reveals a **structural phase transition**:
- Below ~7% MB growth: κ steadily declines over time
- Above ~7% MB growth: κ increases toward 1
- High-inflation economies naturally drive toward $\kappa = 1$ (ideal information transfer) in the long run
- Low-inflation economies maintain persistent $\kappa < 1$

## Real GDP growth (June 28)

Real GDP growth rate extracted from ITM (NGDP growth minus ITM-derived inflation) matches FRED data reasonably well — the framework naturally produces realistic real growth without specifically modeling it.

## CPI measurement concerns

The model suggests either:
- CPI is biased against recording negative inflation (deflation)
- There's an additional inflation mechanism not captured by the model
