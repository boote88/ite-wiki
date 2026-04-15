---
title: Overview
type: synthesis
tags: [overview]
created: 2026-04-07
last_updated: 2026-04-07
---

# Information Transfer Economics — Overview

**Information Transfer Economics** is a research program by [[jason-smith]] (blogged 2013–2023) that applies information theory and statistical mechanics to macroeconomics. The core thesis: economic transactions are information transfer processes, and the laws of supply and demand emerge naturally from this framework without requiring behavioral microfoundations.

## The framework in brief

The [[three-ideas]] formulation:

1. **Supply and demand as information transfer**: price detects information flowing from demand (source) to supply (destination). Derives the standard S&D diagram from Shannon information theory via [[fielitz-borchardt]]'s framework.

2. **Multiple interacting markets**: the same structure applies to IS-LM, [[ad-as-model]], labor markets, and any system with a price-like detector between supply-like and demand-like variables.


3. **Unit of account effect**: the [[information-transfer-index]] κ is endogenous to the monetary base and NGDP, creating the [[information-trap]] — a regime where monetary policy becomes ineffective. This is more general than the [[zero-lower-bound]] and can occur at any interest rate.

The framework rests on [[information-equilibrium]] — a maximum-entropy ("ignorance") approach that assumes the least informative prior consistent with the data. Because it makes no assumptions about agent behavior, it satisfies the Lucas critique by construction: there are no behavioral parameters to shift when policy changes.

A key distinction is [[currency-vs-reserves]]: M0 (currency in circulation) controls the price level, while MB (monetary base including reserves) controls interest rates. QE expanded reserves without expanding currency, which is why it moved rates but not inflation. See [[quantitative-easing]].

By 2015, the framework acquires formal thermodynamic structure: [[economic-potentials]] define temperature as T ~ 1/κ, separating micro-level forces (individual transactions) from macro-level forces (aggregate outcomes). [[expectations|Expectations]] are shown to be unnecessary — the ITM reproduces macro regularities without them, and a thought experiment (T₀/Tₖ) reveals that expectations-based models smuggle in the very equilibrium they claim to derive.

## Framework organization

By 2017, the full framework spans multiple levels, all derived from the basic [[information-equilibrium]] condition:

![Information equilibrium framework organization](<media/2017-04/info eq organization.png>)

From the center (information equilibrium) outward: [[supply-and-demand]] and single-factor production (via scope conditions on adjustment timescales), multi-factor production ([[solow-growth-model]]), matching models ([[labor-market]]), [[dynamic-information-equilibrium]] (time-dependent IE with logistic shocks), ensembles (partition function approach giving [[economic-potentials]]), and statistical equilibrium with k-states (distributions of growth states).

Two additional major insights from 2017:
- The price mechanism works as an [[information-bottleneck]] that *destroys* irrelevant private information, not as a Hayekian information transmitter
- The [[quantity-theory-of-labor]] suggests that demographics — not money or technology — drive long-run growth and inflation

## The complete macro model (2019)

By 2019, the separate pieces are assembled into a single preliminary macro model connecting labor markets, output, wages, and prices:

![Complete information equilibrium macro model](<media/2019-03/models.png>)

Blue double arrows = [[information-equilibrium]] relationships. Purple single arrows = [[dynamic-information-equilibrium]] relationships. Two exogenous inputs drive the system: **business cycle shocks** (possibly triggered when wage growth reaches NGDP growth, degrading firm profitability) and **social/demographic shocks** (women entering workforce, baby boomers, immigration changes). The [[economic-seismogram]] reveals the causal ordering of shocks across these channels. Money and the Fed are conspicuously absent from the core model — consistent with the conclusion that [[money-as-bandwidth|money is the aether of macroeconomics]].

## Key predictions and results

- **[[sticky-prices]]** emerge from [[non-ideal-information-transfer]] without microfoundations
- **[[inflation]]** has two components: an "irreducible" drift from information loss + monetary expansion (which subsumes the [[quantity-theory-of-money]])
- **The [[information-trap]]** explains why QE didn't cause inflation, why Japan stagnated for decades, and why [[secular-stagnation]] afflicts developed economies
- **The [[plucking-model]]** frames business cycles as deviations from an information-efficiency ceiling
- **The [[phillips-curve]]** is mean reversion, not a structural trade-off
- **[[cross-country-comparisons]]** using κ predict which countries' monetary policy will be effective
- **Fiscal policy works** in the information trap — crowding out requires a spontaneous entropy decrease, which is thermodynamically absurd. Monetary offset (Sumner) is impossible when ∂P/∂MB ≈ 0. See [[entropic-forces]].
- **NGDP and inflation targeting eventually fail** — maintaining a target requires exponentially increasing M0 growth as κ rises toward 1
- **Eurozone and Swiss deflation predicted** — the information trap predicted Eurozone deflation (from Nov 2013) and that Switzerland's currency depreciation would fail to produce inflation

## Empirical track record

The ITM is parsimonious and empirically competitive:

- **5 parameters, 6 variables**: a single model with 5 fitted parameters simultaneously tracks interest rates, inflation, unemployment, RGDP growth, and the price level
- **2 vs 29**: the ITM (2 parameters) outperformed the NY Fed's DSGE model (29 parameters) in an ongoing inflation prediction contest
- **Better than the Fed**: ITM predictions outperformed the Federal Reserve Board's own published forecasts for inflation and GDP
- **κ solves the identification problem**: one parameter determines both supply and demand elasticities, resolving a fundamental econometric challenge
- **Information equilibrium is an equivalence relation**: IE satisfies reflexivity, symmetry, and transitivity — giving the framework algebraic structure, not just analogy

## Philosophical stance

The ITM is explicitly **non-normative** — it doesn't assume utility maximization or rational agents. Like thermodynamics, it works without knowing the micro-details (see [[microfoundations-critique]]). The [[thermodynamic-analogies]] (price↔pressure, demand↔energy, supply↔volume) are formal but may reveal real structure.

The demand curve itself is statistical, not behavioral — it takes the same shape as the Maxwell-Boltzmann distribution for the same reason: entropy maximization over many agents. Individual preferences wash out at scale, just as individual molecular velocities wash out in a gas. See [[entropic-forces]].

## Key debates

The ITM engages with several major figures in macroeconomics, often finding partial agreement but deeper disagreement:

- **[[scott-sumner]]** and market monetarism: NGDP targeting is correct in principle but impossible to sustain as κ → 1; monetary offset fails in the information trap
- **[[paul-krugman]]**: agrees on the liquidity trap but the ITM shows it's more general than Keynesian framing
- **[[milton-friedman]]**: QTM vindicated at low κ, plucking model adopted, but wrong about Japan and the permanence of monetary policy effectiveness
- **[[nick-rowe]]**: the "concrete steppes" debate — Rowe insists on expectations as transmission mechanism; ITM says the concrete mechanism (money → transactions → prices) is sufficient

## Ingest Progress

All ~1,555 blog posts (2013–2023) have been processed and synthesized into this wiki.

- [x] 2013 (125 posts) — framework foundations through maturation
- [x] 2014 (231 posts) — theoretical foundations, entropy, universality
- [x] 2015 (375 posts) — peak output, broad application
- [x] 2016 (302 posts) — quantity theory of labor, partition functions, inequality
- [x] 2017 (242 posts) — dynamic information equilibrium, information bottleneck, self-similarity
- [x] 2018 (173 posts) — money as aether, Great Recession timeline, DIEM applied to epidemiology
- [x] 2019 (82 posts) — 1990s phase transition, complete macro model, Workers' History book
- [x] 2020 (14 posts) — COVID as twig crack, DIEM for COVID-19
- [x] 2021 (5 posts) — entropic shocks, recession of 2027 prediction
- [x] 2022 (3 posts) — COVID DIEM outbrief, credibility revolution critique
- [x] 2023 (3 posts) — transition to Substack (blog era ends)

The blog continues as [Information Equilibrium on Substack](https://infoeqm.substack.com/).
