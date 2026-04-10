---
title: Economic Seismogram
type: concept
tags: [seismogram, diem, visualization, causal-ordering, shocks]
sources:
  - raw/2017/07/a-dynamic-equilibrium-history-of-united.md
  - raw/2018/02/women-in-workforce-and-solow-paradox.md
  - raw/2018/02/economic-seismographs-labor-and.md
  - raw/2018/03/dynamic-equilibrium-model-fertility-as.md
  - raw/2018/11/an-information-equilibrium-history-of.md
created: 2026-04-10
last_updated: 2026-04-10
---

# Economic Seismogram

The **economic seismogram** is a visualization and analytical tool that emerged from the [[dynamic-information-equilibrium]] framework. It plots the logistic shocks from multiple independently-fitted DIEM models on a single timeline, revealing causal ordering, clustering, and the multi-year anatomy of macroeconomic events.

## How it works

Each macro time series (unemployment, labor force participation, employment-population ratios by gender and race, inflation measures, housing prices, JOLTS components, wages, conceptions, etc.) is independently fitted with its own DIEM — a constant log-derivative plus logistic shocks. No cross-series constraints are imposed; each fit is done on its own data. The shocks are then plotted as bars on a shared timeline, with bar width proportional to shock duration. Positive shocks in blue, negative shocks in red.

The power comes from what emerges when you put independently-fitted shocks side by side: **temporal ordering reveals causality** (or at least Granger-causal precedence). Shocks that consistently lead other shocks across multiple recessions point toward causal mechanisms. Shocks that consistently lag point toward consequences.

## What the seismograms reveal

### Women entering the workforce (1960s–1990s)

The single most striking feature of the US seismogram: a long positive shock to female employment-population ratio **precedes** positive shocks to male EPOP, which precede shocks to output, which precede shocks to inflation. The causal chain is demographic → labor → output → prices. Monetary base shocks *follow* inflation shocks, not the other way around.

![Causal ordering seismogram: women → men → output → inflation](<../media/2018-02/dynamicInformationEquilibriumHistory.png>)

This temporal ordering is the strongest evidence for the [[quantity-theory-of-labor]] and against monetary explanations of the Great Inflation.

### The Great Recession (2006–2010)

The complete causal timeline revealed by the seismogram:
1. Construction hires drop (mid-2006) — first signal, over a year before the NBER recession
2. Conceptions drop (social indicator) — precedes all economic indicators
3. Housing starts decline, Case-Shiller falls, Fed cuts rates
4. Stock market crash, GDP decline, unemployment spike — all come *late*
5. Debt shocks — *follow* the recession (consequence, not cause)

The seismogram shows the Great Recession was a **multi-year process** beginning with a labor supply shock in construction, not a sudden financial crisis.

### Recession shocks cluster but don't perfectly synchronize

Across recessions, shocks to different time series cluster around similar dates but don't perfectly align. JOLTS hires lead JOLTS openings; unemployment lags both; wage growth shocks come even later. The imperfect synchronization is itself informative — it shows which channels transmit the shock first and which markets adjust last.

## The seismogram as a tool

The seismogram works because it treats the economy as a **set of independent channels**, each with its own dynamic equilibrium, all potentially affected by common underlying events. By fitting each channel independently and then comparing, you avoid the circularity of models that impose cross-variable constraints (like DSGE models where the relationships between variables are assumed, not discovered).

The seismogram is to macroeconomics what the actual seismograph network is to geology: a distributed array of independent detectors that, by comparing arrival times across stations, reveals the location and character of the underlying event. Individual detectors can't tell you much; the network can tell you everything.

## Connection to other concepts

- Built on [[dynamic-information-equilibrium]] — each channel is a separate DIEM fit
- Reveals causal ordering for [[recessions]] — the Great Recession timeline and the demographic inflation story
- Supports [[quantity-theory-of-labor]] — demographic shocks lead monetary shocks temporally
- Connected to [[nominal-shocks]] — the seismogram visualizes the same departure-from-trend that nominal shocks measure, but across many variables simultaneously
- The conception rate finding strengthens the view of [[recessions]] as social phenomena ([[entropic-forces]]) rather than purely economic ones
