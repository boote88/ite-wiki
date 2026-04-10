---
title: Interest Rates
type: topic
tags: [interest-rates, yield-curve, monetary-base, currency, recession-prediction]
sources:
  - raw/2014/08/are-interest-rates-good-indicator-of.md
  - raw/2015/01/caught-between-3-month-and-10-year.md
  - raw/2015/01/mr-short-rate-risin.md
  - raw/2015/03/the-yield-curve-in-3d.md
created: 2026-04-07
last_updated: 2026-04-07
---

# Interest Rates

Interest rates in the [[information-transfer-model]] emerge from two distinct information equilibrium relationships, one for long rates and one for short rates. This dual structure explains the yield curve, predicts recessions, and clarifies why QE affected rates but not inflation.

## The two-rate model

The ITM distinguishes two rates determined by different monetary aggregates (see [[currency-vs-reserves]]):

| Rate | Model | Aggregate |
|---|---|---|
| Long-term (10-year) | r:NGDP→M0 | Currency in circulation |
| Short-term (3-month) | r:NGDP→MB | Full monetary base (currency + reserves) |

This immediately explains the post-2008 puzzle: QE massively expanded reserves (MB) without much affecting currency (M0), so short rates fell but long rates and inflation barely moved.

## The yield curve

The difference between long and short rates is entirely due to central bank reserves. In normal times, the 5-year rate tracks the 10-year almost exactly — both represent the economy's average equilibrium state. But during recessions, the 5-year drops below the 10-year. The ITM identifies these periods precisely: they're where the short rate falls well below the theoretical curve — periods of [[non-ideal-information-transfer]].

Visualized in 3D, the yield curve looks like a string fixed at the far end (long rate) and flapping in the wind at the near end (short rate). The "flapping" represents deviations from [[information-equilibrium]] — the [[plucking-model]] in action.

## Recession prediction

The short rate *rising above* the theoretical curve precedes recessions — the ITM's version of yield curve inversion as a recession signal. When the short rate exceeds the model's prediction, it signals an impending nominal shock. This is related to the "sand pile avalanche" model of recessions.

## Peak QE and rate normalization

If the monetary base has peaked ("peak QE"), then short-term rates are already rising mechanically — NGDP continues to grow while MB stays flat, so the ratio changes and rates increase. The Fed's "decision" to raise rates may be less a policy choice and more an acknowledgment of what the model already shows happening.

## Three regimes of interest rate dynamics

The response of interest rates to monetary expansion depends entirely on the [[information-transfer-index]] κ. DSGE simulations of the ITM show three qualitatively different regimes:

**κ > 1 (classical/monetarist regime)**: expanding the base raises interest rates, output, and inflation. The rise in inflation is proportional to base growth. Expansionary policy causes genuine expansion.

![κ > 1: expansion raises everything](<../media/2015-10/DSGE form ITE simulations 2.png>)

**κ ≈ 1 (IS-LM / current US regime)**: expansion lowers interest rates with only small inflation and output gains. This is the standard IS-LM result — monetary expansion lowers rates and modestly raises output.

![κ ≈ 1: expansion lowers rates, small output gain](<../media/2015-10/DSGE form ITE simulations 1.png>)

**κ < 1 (neo-Fisherite / Japan regime)**: expansion leads to **falling** inflation, **falling** interest rates, and **falling** nominal output. This is the neo-Fisherite result where inflation follows rates down — the [[information-trap]] at its most extreme.

![κ < 1: expansion lowers everything](<../media/2015-10/DSGE form ITE simulations 3.png>)

This resolves the seemingly contradictory observations that monetary expansion sometimes raises rates (1970s US) and sometimes lowers them (2010s US, Japan). It's the same mechanism producing different outcomes at different κ values.

## Interest rate forces

Multiple forces act on interest rates simultaneously:
- **Liquidity effect**: monetary expansion lowers rates (dominant in short run and at high κ)
- **Fisher effect**: inflation expectations raise rates
- **Income effect**: higher NGDP raises rates
- **κ trend**: the primary reason rates rose with the base pre-1980s but fell after — the inflection point around 1980 is when κ crossed a threshold

In the [[information-trap]], the liquidity effect dominates and rates stay low — this is expected, not "remarkably low" as many economists describe.
