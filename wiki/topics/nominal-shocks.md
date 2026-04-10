---
title: Nominal Shocks
type: topic
tags: [nominal-shocks, recessions, ngdp, monetary-base, sand-pile, methodology]
sources:
  - raw/2013/07/extracting-nominal-shocks.md
  - raw/2013/07/extracting-nominal-shocks-continued.md
  - raw/2014/02/extracting-shocks-again.md
  - raw/2014/03/the-monetary-base-as-sand-pile.md
  - raw/2014/09/the-emerging-story-of-great-recession.md
created: 2026-04-09
last_updated: 2026-04-09
---

# Nominal Shocks

A **nominal shock** in the [[information-transfer-model]] is the difference between actual NGDP and the NGDP that would be expected given monetary base growth alone. It is the central observable used to measure [[non-ideal-information-transfer]] in real time, and the connection between the abstract framework and concrete events like the 2008 financial crisis.

## Definition and methodology

Start from the basic ITM relationship — NGDP depends on the monetary base via the [[information-transfer-index]]. Solve the differential equation for the counterfactual where only the monetary base evolves (no exogenous disturbances). The result is the "expected" NGDP path: where the economy would be if all the variation came from the [[currency-vs-reserves|currency component]] of the base. Subtract this from actual NGDP and you have the nominal shock at each point in time.

Equivalently, in the MB-NGDP plane: a change in the monetary base traces an arrow representing a "pure monetary" move. The empirical path generally departs from where this arrow would put the economy. The nominal shock is the perpendicular departure from the expected position.

![Response to MP and FP along the empirical track](<../media/2013-07/response to mp and fp -along track-.png>)

The procedure can be inverted: feed observed NGDP and MB into the model, recover the implied shock at each step, then verify that running the differential equation forward with these shocks reproduces the data. It does — and when shocks are modeled as a random AR(2) process with parameters estimated from history, Monte Carlo runs reproduce the empirical NGDP path within two-sigma error over 50+ years.

![Monte Carlo NGDP paths driven by AR(2) nominal shocks](<../media/2014-03/ite numerical diffeq 7.png>)

## What the shocks look like

Plotting extracted shocks year by year from 1960 onward reveals the structure of macroeconomic history that the simple monetary model can't account for:

![Extracted nominal shocks 1960–2012](<../media/2013-07/price level best fit -extract shocks 1-.png>)

A few immediate observations:
- **Most years are quiet**, with shocks small relative to the trend
- **Negative shocks dominate** the visible activity — recessions show up as conspicuous downward deviations
- **The Great Recession is the largest shock in the series**, roughly 15% of NGDP, concentrated around September 2008
- Positive shocks exist but are smaller and rarer than negative ones — the **asymmetry** is empirical

This asymmetry is exactly what the [[entropic-forces|fluctuation theorem]] predicts: small "violations of the second law" (entropy decreases) are common, large ones rare, with exponential suppression. Recessions are the rare, large negative-entropy events.

## Sand pile dynamics

Smith frames the monetary base as a **sand pile**: as the base grows over time, the system accumulates "potential" for departures from equilibrium. Most of the time the pile is stable; occasionally a small addition triggers an avalanche — a large negative shock — that cascades through the system. The framework borrows directly from self-organized criticality in physics: the size distribution of avalanches follows a power law, with rare large events dominating the variance.

This naturally explains why recessions don't happen on a clock and why they're hard to predict. There is no "business cycle" in the periodic sense — the dynamics are aperiodic and avalanche-like. See [[recessions]] for the broader treatment of business cycle dynamics.

## The Great Recession through nominal shocks

Applying the methodology to 2008: the extracted shock is sharply negative, concentrated in the second half of the year, with a magnitude (~15% NGDP) that dwarfs everything in the post-WWII record. The story the shock tells is consistent with the [[interest-rates|Fed-tightened-pre-2008]] narrative: short-term rates rose above the [[information-equilibrium]] curve from 2005 onward, signaling the impending shock; when the avalanche came, the policy response was insufficient to absorb it.

The pre-2003 period shows no significant negative shocks — the "Great Moderation" was real, in the sense that the economy was operating close to the [[plucking-model|information efficiency ceiling]] — but the post-2008 shock dominates everything that came before. Recovery has been slow because the system is now well below the bound and re-thermalizing.

## Decomposition issues

The MB-NGDP coordinate system isn't orthogonal at most points, so a single observed departure can't be cleanly decomposed into "supply shock" vs "demand shock" components. This is why Smith uses the term **nominal shock** rather than committing to either label. The information-theoretic interpretation — *some* information was lost between source and destination — is more general and doesn't require taking sides in the AS-vs-AD debate.

The framework is also agnostic about the cause of any particular shock. A nominal shock could correspond to a supply disruption (oil shock), a demand collapse (financial panic), a productivity surprise, or anything else that breaks information equilibrium. The methodology measures the magnitude; explaining the cause requires additional inputs.

## Connection to other ITM concepts

Nominal shocks are the empirical handle on [[non-ideal-information-transfer]] — when $I_S < I_D$, the gap shows up as a measurable deviation from the ideal path. They drive the [[plucking-model]] (recessions are large negative shocks below the efficiency ceiling) and provide the signal that the [[recessions]] page synthesizes into the Great Recession narrative. They're also used in cross-model comparisons: any macro model can be evaluated by how well it explains the nominal shock series, which the ITM does with just two parameters.
