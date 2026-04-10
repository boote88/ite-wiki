---
title: Inflation
type: topic
tags: [inflation, price-level, rescaling, quantity-theory, labor-force, demographics]
sources:
  - raw/2013/05/macroeconomics-as-information-transfer.md
  - raw/2013/05/rescaling-and-inflation.md
  - raw/2013/05/money-is-amoral-tool-and-other.md
  - raw/2016/01/is-cpi-information-theoretic-measure-of.md
  - raw/2016/01/the-slope-of-phillips-curve-is-roughly.md
created: 2026-04-07
last_updated: 2026-04-09
---

# Inflation

Inflation is one of the central explananda of macroeconomics, and the [[information-transfer-model]]'s account has evolved through several layers as the framework matured. The current picture combines a deterministic monetary component, an irreducible entropic drift, and — most strikingly — a strong link to **labor force growth** that may be more fundamental than either.

## The monetary picture

In the basic ITM, inflation comes from changes in the price level $P$, which depends on $\log P \sim (k-1) \log M_0$ where $M_0$ is currency in circulation (see [[currency-vs-reserves]]). At low [[information-transfer-index]] κ, this reduces to the [[quantity-theory-of-money]]: inflation tracks money growth. At high κ, the dependence weakens and inflation becomes insensitive to monetary policy ([[information-trap]]).

This gives a deterministic monetary component to inflation, with the predicted strength depending on κ. The irreducible drift comes from the asymmetry of [[non-ideal-information-transfer]] near the lower-bound — random fluctuations get cut off downward, producing systematic upward bias in nominal prices even without monetary expansion.

## The labor force connection

The most striking result, surfacing in early 2016: inflation in CPI tracks the **civilian labor force** even more closely than it tracks money. The information equilibrium relationship $\text{CPI} \rightleftarrows \text{CLF}$ produces a very good fit for the US, Japan, and Canada with a single coefficient $a \approx 2.67$:

$$\frac{d}{dt} \log \text{CPI} = a \cdot \frac{d}{dt} \log \text{CLF}$$

Inflation rate is roughly 2.67 times the labor force growth rate.

![CPI fit to civilian labor force, US](<../media/2016-01/ite model for cpi -us- 1.png>)

![CPI vs CLF rates, US](<../media/2016-01/ite model for cpi -us- 2.png>)

This works for Japan and Canada too — the same coefficient and the same fit quality across countries. Whatever is going on, it's structural rather than country-specific.

The geometric interpretation: with $a \approx 3$, inflation grows like the volume of a sphere whose radius is the labor force size. Any signal in the radius shows up amplified in the volume.

## A new story of US inflation history

If inflation is driven by labor force growth rather than monetary policy, the standard narrative of US postwar macroeconomics needs to be rewritten. Compare the labor force growth rate to the population growth rate:

![Labor force vs population growth, US](<../media/2016-01/clfpop.png>)

The 1960s and 1970s — the era of "Great Inflation" — were exactly the period when the **labor force grew faster than the population**. Women, African Americans, and other previously-excluded groups were entering the workforce, raising the participation rate. Once that catch-up was complete (early 1980s), labor force growth slowed to population growth, and inflation fell. The Volcker Fed gets credit for ending the Great Inflation, but the timing aligns just as well with the demographic story.

Two possibilities follow:
1. **The Volcker Fed was superfluous** — inflation was going to fall anyway as the participation rate stabilized
2. **Volcker worked through a different channel** — the recessions he caused suppressed labor force entry, locking in the new equilibrium participation rate sooner

Recent low inflation in the developed world has the same explanation. US population growth is now below 0.75% per year, exactly when central banks have struggled to maintain a 2% inflation target (given $a \approx 2.67$, you'd need labor force growth of roughly $2\%/2.67 \approx 0.75\%$ to hit 2% inflation). The "lowflation" in the EU, US, and Japan is mostly demographic, and it's unlikely to be moved by anything central banks do.

This puts a very sharp point on the question of whether central bank inflation targeting is real. If labor force growth is doing all the work, then central banks targeting 2% inflation are something like Feynman's cargo cultists — performing rituals associated with an outcome they don't actually cause. Rate decisions might still cause recessions (by acting as coordinating signals — "sunspots" in Roger Farmer's terminology), but the inflation effect is the demographic wave underneath, not the central bank ceremony on top.

## Dynamic equilibrium confirmation

The [[dynamic-information-equilibrium]] model applied to the core PCE price level makes the demographic story even sharper. The DIEM finds only **one major shock** in the entire post-war inflation record — a single logistic transition centered at 1978.7. All other fluctuations are dwarfed by it. This single transition doesn't align with any unemployment shock (so it's not a Phillips curve trade-off); it aligns precisely with **women entering the workforce** — the same demographic story as the quantity theory of labor, now confirmed as a single clean transition rather than a series of events.

## How this fits with the rest of the framework

The labor force result is not a replacement for the [[currency-vs-reserves|M0]] story or the [[information-trap]] story. They're consistent: at low κ (when the QTM regime applies), money does affect inflation. At high κ (the trap), the M0 mechanism shuts down and the labor force mechanism may be all that's left. The deeper story may be that labor force is in [[information-equilibrium]] with NGDP, and NGDP is in IE with M0, and the whole chain produces the observed inflation pattern with the dominant transmission shifting between the money channel and the labor channel as κ evolves.

The connection to [[phillips-curve]] becomes explicit. The era of the apparent Phillips curve (1960s–1990s) is exactly the era of rising labor force participation. Once participation peaks, both the inflation-unemployment correlation *and* the labor-force-driven inflation taper off together. The Phillips curve was always a side-effect of demographic transition, not a structural relationship.

## Rescaling and renormalization

Smith draws a parallel to **renormalization in physics**: the absolute price level is arbitrary (like the electron charge), and a good macro theory should describe its *dynamics* without predicting its level. You measure it at one point and the theory tells you how it evolves. The analogy extends to Feynman diagrams: summing up expectations and transactions in the economy is like summing diagrams, and things work if you use nominal values in tree-level calculations.

## Connection to AD-AS

In the AD-AS version of the ITM, the model recovers the modern view:
- Below equilibrium: sticky prices, idle resources (unemployment, empty storefronts)
- At/above equilibrium: AD boosts produce inflation without output gains
- This gives a "sharp right angle" at the current price level
