---
title: Dynamic Information Equilibrium Model (DIEM)
type: concept
tags: [diem, dynamic-equilibrium, logistic, jolts, unemployment, labor-market]
sources:
  - raw/2016/06/unemployment-equilibrium.md
  - raw/2016/10/dynamic-unemployment-equilibrium-and.md
  - raw/2017/01/a-dynamic-equilibrium-in-jolts-data.md
  - raw/2017/01/dynamic-equilibrium-unemployment-rate.md
  - raw/2017/01/dynamic-unemployment-equilibrium.md
created: 2026-04-10
last_updated: 2026-04-10
---

# Dynamic Information Equilibrium Model (DIEM)

The **Dynamic Information Equilibrium Model** is a framework that emerged in late 2016 and became Smith's primary empirical tool from 2017 onward. It's simpler than the full [[information-transfer-model]] but remarkably powerful: take two economic variables in [[information-equilibrium]], assume the logarithmic derivative is constant (the "dynamic equilibrium"), and model deviations from that constant as logistic-function shocks. The result is a framework that fits unemployment, JOLTS data, inflation, interest rates, wage growth, and more with just a few parameters per shock.

## The core idea

Two variables $A$ and $B$ are in information equilibrium with constant [[information-transfer-index]] $k$. If $B$ grows exponentially at rate $r$, then the logarithmic derivative of $A$ is a constant:

$$\frac{d}{dt} \log A = k \cdot r = \text{constant}$$

This is the **dynamic equilibrium**: a constant rate of change in log-space. Deviations from this constant are modeled as **logistic functions** — smooth step-like transitions centered at specific dates, with specific widths and amplitudes. Each logistic function represents a "shock" (recession, policy change, demographic transition).

The model for any given time series is then:

$$\log A(t) = \alpha t + \sum_i \beta_i \cdot \sigma\left(\frac{t - t_i}{\tau_i}\right) + c$$

where $\sigma$ is the logistic function and each shock has three parameters: amplitude $\beta_i$, center $t_i$, and width $\tau_i$.

## Why it works

The dynamic equilibrium isn't just a convenient fit; it has an information-theoretic foundation. When $A \rightleftarrows B$ with constant $k$, the log-derivative being constant follows directly from the IE differential equation. Recessions show up as departures from IE — periods of [[non-ideal-information-transfer]] where the system temporarily departs from the equilibrium trend. The logistic function is the simplest smooth transition between two states consistent with the shock arriving, propagating, and dissipating.

The key empirical observation behind the framework: for the US unemployment rate, recoveries proceed at a remarkably constant rate of ~0.49 percentage points per year ([[recessions]]). This constant slope is the dynamic equilibrium. Recessions are logistic shocks that temporarily spike unemployment above the trend. Once the shock dissipates, the system returns to the same slope. This is why all recoveries look the same — they're all the same process of returning to the same dynamic equilibrium from different starting points.

## Three centuries of dynamic equilibria

Applied to three centuries of UK price level data, the DIEM reveals two distinct dynamic equilibria with four major logistic shocks:

- **1600s–early 1900s**: gold standard equilibrium with inflation rate ≈ 0%
- **Post-WWII**: modern equilibrium with inflation rate ≈ 2.6%

The four shocks are centered at: 1780.7 (industrial revolution / population growth from improved sanitation), 1916.1 (WWI), 1945.5 (WWII), and 1976.1 (women entering the workforce). Each is a logistic transition between states — exactly the same mathematical form that describes post-war US recessions, but operating on century timescales.

![Three centuries of UK price level — two dynamic equilibria](<../media/2017-03/dynamic equilibrium three centuries uk data 1.png>)

![UK inflation rate — two regimes with four logistic shocks](<../media/2017-03/dynamic equilibrium three centuries uk data 2.png>)

This is the DIEM's longest historical validation for economics — the same framework that fits quarterly US unemployment data also describes century-scale structural transitions in the UK.

## World population since the Neolithic

Taking the scope even further: the DIEM applied to world population over ~5,000 years reveals four logistic transitions with an equilibrium growth rate of **zero**:

- **~2390 BCE**: neolithic revolution following the Holocene Climate Optimum
- **~500 BCE**: dawn of the Roman Republic (narrow transition, ~0–100 years)
- **~1424 CE**: post-Medieval Warm Period agricultural revolution (~300-year width); rise of nation-states
- **~1954 CE**: modern medicine and urbanization (~50-year width)

![World population DIEM with four transitions](<../media/2017-11/popModel.png>)

![Growth rate over history — typically zero](<../media/2017-11/popModel2.png>)

The "exponential growth" we consider normal is just a local approximation around the most recent transition. The equilibrium rate is zero; populations plateau after each logistic transition. This predicts ~12.5 billion by 2100 with an equilibrium at ~13.4 billion. Technology bursts (writing, money, heavy plow, computers) appear on the leading edge of these transitions — possibly responses to the social stress of rapid population change rather than causes of the growth.

## Applications

### Unemployment rate

The original application. The dynamic equilibrium in unemployment drops at ~0.05 pp/month. Recessions are negative logistic shocks. The model fits the entire post-war US record and extends cleanly to [[japan]], the Eurozone, and other countries. The Volcker recessions look slightly different (possibly Fed-induced rather than spontaneous), but everything else follows the pattern.

### JOLTS data

Job openings vs unemployment ratio ($V/U$) follows the same structure: $V \rightleftarrows U$ with constant $k$. The 2001 and 2008 recessions appear as negative logistic shocks; the Affordable Care Act (Obamacare) appears as a *positive* logistic shock starting around mid-2014 that pushed job openings higher and may have reduced unemployment by ~1 percentage point.

![JOLTS U/V ratio with dynamic equilibrium fit](<../media/2017-01/jolts job openings unemployment ratio 1.png>)

![JOLTS with three shocks including ACA positive shock](<../media/2017-01/jolts job openings unemployment ratio 2.png>)

### Beveridge curve as parametric DIEM

The Beveridge curve (the observed hyperbolic U-V relationship) is not a behavioral relationship — it's a **parametric consequence** of unemployment and vacancies each following their own independent dynamic equilibria. Fit each series with its own logistic shocks, then parametrically plot one against the other; the result reproduces the observed Beveridge curves including the shifts between different hyperbolas during recessions. The shifts happen because shocks to U and V don't perfectly match in timing or magnitude.

![Beveridge curve from independent DIEM fits](<../media/2017-10/dynamic equilibrium -beveridge- data updates.png>)

Gray lines show potential dynamic equilibria (parallel hyperbolas in U-V space). Without shocks, the economy climbs one hyperbola toward low-U/high-V. Recessions send it to a different hyperbola. The 2014 Obamacare positive shock produces a shift back. Three hyperbolas suffice to describe the entire 2001–2020 period.

### Inflation

The DIEM applied to the core PCE price level reveals a striking result: there is only **one major shock** to the inflation dynamic equilibrium in the entire post-war US record, centered around 1978.7. All other shocks are dwarfed by this single transition. And it doesn't match any unemployment shock — it aligns instead with **women entering the workforce**, the same demographic story from the [[quantity-theory-of-labor]].

![Dynamic equilibrium fit to core PCE price level](<../media/2017-02/dynamic equilibrium -inflation- 1.png>)

![Dynamic equilibrium fit to core PCE inflation rate](<../media/2017-02/dynamic equilibrium -inflation- 2.png>)

The employment-population ratio for women shows the same logistic transition:

![Women's employment-population ratio — same transition timing](<../media/2017-02/unemployment ratio -log version- EPOP ratio women.png>)

This reinforces the view that the Great Inflation of the 1970s was a demographic phenomenon, not a monetary one. [[inflation]] in the DIEM is connected to labor force participation, not to monetary policy or [[expectations]]. NAIRU becomes "two unobservable variables interacting" — a post hoc narrative invented to link the real economy to inflation, not a data-driven relationship.

### Civilian labor force

The DIEM applied to the civilian labor force reveals that only **two major events** have disrupted the dynamic equilibrium in the last 70 years: women entering the workforce (positive shock, ~1965–1990) and the Great Recession (negative shock, 2008–2012). Everything else is fluctuation around the trend. This extreme parsimony — two shocks in seven decades to explain the entire labor force history — is what makes the DIEM framework so powerful as a descriptive tool.

![Civilian labor force DIEM — just two shocks in 70 years](<../media/2017-05/dynamic equilibrium -clf- 1.png>)

### Other applications

The same framework extends to housing prices (Case-Shiller index), JOLTS data, nominal wage growth, interest rates, gold prices, stock indices, rental vacancy rates, and more. In each case, a constant log-derivative with identifiable logistic shocks at recession dates produces a good fit with very few parameters. The same shock dates appear across multiple independent time series, providing cross-validation.

## Validation in agent-based models

The dynamic equilibrium structure isn't just an empirical pattern in US data — it emerges in **agent-based simulations** with random agent actions. Smith tested the DIEM against Ian Wright's Closed Social Architecture (CSA) model — a simulation with no rational agents, no optimization, just random interactions. The CSA produces unemployment dynamics that follow the same dynamic equilibrium + logistic shock pattern. This validates the framework's claim: the dynamic equilibrium is a structural feature of many-agent economies, not an artifact of US institutional history or policy regimes.

## Relationship to the full ITM

The DIEM is not a replacement for the full [[information-transfer-model]]; it's a simplification that holds when $k$ is approximately constant (or slowly varying) and you care about medium-run dynamics rather than the long-run evolution of κ. The full ITM tells you *why* κ changes over decades; the DIEM tells you what the economy does between changes in κ.

Think of it as: the ITM is the theory of the equilibrium, and the DIEM is the theory of the shocks on top of it. In practice, the DIEM has been more immediately useful for empirical work because most macro time series show clear dynamic equilibria with identifiable shocks, and the model produces quantitative predictions with very few parameters.

## The comprehensive picture

By mid-2017, Smith compiled all DIEM results into a single infographic timeline — a "dynamic equilibrium history of the United States" showing shocks across multiple time series: unemployment, civilian labor force participation, employment-population ratios (by gender), PCE, CPI, housing prices (Case-Shiller), S&P 500, and the adjusted monetary base.

![Dynamic equilibrium history of the United States — full timeline](<../media/2017-07/dynamic equilibrium history 1.png>)

![Post-war detail with women entering workforce highlighted](<../media/2017-07/dynamic equilibrium history 3.png>)

Blue bars = positive shocks, red bars = negative shocks, beige = recessions. The widths are proportional to shock duration. The dominant feature is the long positive shock of women entering the workforce (~1960s–1990s), which precedes and likely causes the inflation shocks of the Great Inflation era. Recession shocks appear as synchronized red bars across unemployment, employment, and to a lesser extent, inflation and housing.

The stunning thing about this picture is its **parsimony**. Across all these time series spanning decades, the structure is a handful of logistic shocks superimposed on constant log-derivative trends. There is no complex dynamics, no nonlinear feedbacks, no regime switches — just the dynamic equilibrium plus shocks.

## Connection to other concepts

- The constant log-derivative is the ITM's [[information-equilibrium]] condition applied to time-series data
- Recessions as logistic shocks are the [[nominal-shocks]] / [[non-ideal-information-transfer]] story in a more empirically tractable form
- The [[plucking-model]] maps onto the DIEM: the ceiling is the dynamic equilibrium, and plucks are the negative logistic shocks
- Recovery regularity ([[recessions]]) has a clean DIEM explanation: all recoveries follow the same dynamic equilibrium slope
- The [[labor-market]] two-market structure carries over: unemployment and wages each have their own dynamic equilibria with the same shock dates
