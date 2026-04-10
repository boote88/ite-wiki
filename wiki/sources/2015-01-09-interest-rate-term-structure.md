---
title: "Caught between the 3-month and 10-year interest rate"
type: source
tags: [interest-rates, yield-curve, term-structure, plucking-model, recessions]
sources:
  - raw/2015/01/caught-between-3-month-and-10-year.md
created: 2026-04-07
last_updated: 2026-04-07
---

# Caught between the 3-month and 10-year interest rate (2015-01-09)

[Original post](../../raw/2015/01/caught-between-3-month-and-10-year.md)

Analysis of how the ITM's interest rate model explains the term structure — specifically the behavior of the 5-year rate relative to the 3-month and 10-year rates.

## Key insight

The ITM only distinguishes two rates:
- **Long rate** (10-year): determined by P:NGDP→M0 (see [[currency-vs-reserves]])
- **Short rate** (3-month): determined by r:NGDP→MB

The 5-year rate normally tracks the 10-year almost exactly — both represent the "equilibrium" average state. But during recessions, the 5-year drops below the 10-year. The ITM identifies these periods: they're where the short rate falls well below the theoretical curve — periods of [[non-ideal-information-transfer]] (information loss).

## Charts

### Full history: 3-month, 5-year, and 10-year rates with ITM theoretical curves

![Interest rate term structure overview](<../media/2015-01/ite interest rates us -3 month 5 year and 10 year-.png>)

Green band = difference between 10-year and 5-year rates. Beige = 3-month actual. Blue = ITM theoretical curves.

### Zoomed views showing yield curve widening during recessions

![Recession period 1](<../media/2015-01/ite interest rates us -3 month 5 year and 10 year- 1a.png>)

![Recession period 2](<../media/2015-01/ite interest rates us -3 month 5 year and 10 year- 1d.png>)

![Recession period 3](<../media/2015-01/ite interest rates us -3 month 5 year and 10 year- 1c.png>)

![Recession period 4](<../media/2015-01/ite interest rates us -3 month 5 year and 10 year- 1b.png>)

The green band widens when the beige (3-month) curve falls well below the blue (theoretical) curves. How far the 5-year drops below the 10-year is proportional to how far the 3-month drops below theory (in logarithm).

## Connections

- **[[plucking-model]]**: large negative deviations of short rates from theory represent "plucks" — non-ideal information transfer with $I(D) > I(S)$
- **Yield curve inversions**: the short rate *rises above* the theoretical curve just before recessions — a known recession predictor, here given an information-theoretic interpretation
- **Low long-term rates** (Brad DeLong's "remarkably low" rates): expected in the ITM — monetary expansion doesn't generate [[inflation]] in the [[information-trap]] and lowers rates via the liquidity effect
