---
title: Phillips Curve
type: topic
tags: [phillips-curve, unemployment, inflation, mean-reversion, nairu]
sources:
  - raw/2013/10/the-phillips-curve.md
  - raw/2015/06/maximum-entropy-and-natural-rate-of.md
  - raw/2016/01/the-slope-of-phillips-curve-is-roughly.md
created: 2026-04-07
last_updated: 2026-04-09
---

# Phillips Curve in the ITM Framework

The [[information-transfer-model]] treats the Phillips curve as "real but barely useful." The apparent inverse relationship between [[inflation]] and unemployment is not a structural trade-off but an artifact of **mean reversion** — and the "natural rate" of unemployment it implies has a surprisingly simple entropic origin.

## Why it looks real but isn't structural

After recessions cause sharp unemployment spikes, the recovery involves unemployment falling while inflation rises — creating the *illusion* of a causal trade-off. The real story is just unemployment reverting to its natural rate while inflation independently reverts to its information-equilibrium-determined trend. The correlation is coincidental timing, not causation.

Different historical "regimes" of the Phillips curve (the shifting loops observed in data) represent different values of the [[information-transfer-index]] κ, not different economic structures. In a 3D plot of inflation vs. unemployment vs. time, there is no stable surface — the Phillips curve "doesn't exist" as a structural relationship.

By 2016, this view has become close to mainstream consensus. A working paper by Olivier Blanchard, Eugenio Cerutti, and Lawrence Summers (IMF, November 2015) plotted the Phillips curve slope from the 1960s to the present and concluded that "the Phillips curve slope today is not only small, but statistically insignificant." The slope has been declining toward zero for decades. The ITM had been saying the same thing since 2013 — a "real but barely useful" relationship that was always going to dissolve as κ rose.

A more pointed conjecture: the era of the apparent Phillips curve (1960s–1990s) corresponds exactly to the era when the labor force was growing **faster** than the population — the rising labor force participation rate. If inflation is connected to labor force growth (which the ITM allows), then the apparent Phillips curve was always a temporary artifact of demographic alignment. Once participation peaked and started reversing in the early 2000s, the apparent inflation-unemployment relationship dissolved with it. There may never have been a structural Phillips curve at all — just a coincidence of trends that lasted long enough to look like a law.

## The natural rate of unemployment

NAIRU emerges from the ITM in two complementary ways:

**As a κ ratio**: the natural rate is approximately $u^* \approx \kappa_{LS}/\kappa_U$ where $\kappa_{LS}$ is from the labor supply market and $\kappa_U$ is from the unemployment market. This makes NAIRU endogenous to the model rather than an exogenous assumption that must be estimated.

**As maximum entropy**: a large number of consumption periods ($D \gg 1$) combined with a finite labor supply constraint ($L$) produces a natural rate ($L' < L$) purely from counting states. The maximum entropy distribution over employment states generates unemployment without any behavioral assumptions — no search costs, no wage rigidity, no matching frictions. Just a constraint and entropy.

![Maximum entropy unemployment states](<../media/2015-06/itm minimac states.png>)

![Natural rate diagram](<../media/2015-06/unrate diagram.png>)

Policy shapes the tails of this distribution — stimulus when unemployment is too high, tight money when too low — but the central tendency emerges from entropy alone.

## Was the Phillips curve caused by women entering the workforce?

The [[dynamic-information-equilibrium]] model provides the sharpest version of the demographic Phillips curve hypothesis. The "strong Phillips curve" signal in the data (anti-correlation between PCE inflation shocks and unemployment shocks) **follows exactly the non-equilibrium process of women entering the workforce** in the employment-population ratio. Once the female EPOP ratio reaches its new equilibrium and becomes highly correlated with the male ratio (showing identical recession shocks), the Phillips curve signal disappears.

This suggests the Phillips curve wasn't about "inflation resulting from increasing employment" generically — it was about inflation resulting from **new people entering the labor force**. The curve vanishes when the demographic transition completes and the employment-population ratio stabilizes.

A speculative mechanism: sexism. As women entered the workforce, men may have negotiated higher raises to stay ahead of women in similar roles. During recoveries (tight labor markets), this amplification turned an otherwise undetectable Phillips-curve effect into a strong signal. The mechanism has attenuated as gender pay gaps have (partially) narrowed, but the structural change (women reaching equilibrium participation) is the dominant cause of the Phillips curve's disappearance.

Whether or not the sexism mechanism is correct, the demographic connection is robust. The Phillips curve fading is likely **permanent** — it won't return without another demographic shock of comparable magnitude.
