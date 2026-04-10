---
title: Labor Market
type: topic
tags: [labor-market, unemployment, wages, okun-law, stickiness]
sources:
  - raw/2013/08/scott-sumners-model-part-2_30.md
  - raw/2013/10/sticky-wages.md
  - raw/2013/10/more-on-sticky-wages.md
  - raw/2014/01/two-kinds-of-stickiness.md
  - raw/2014/02/sticky-wages-information-transfer-and.md
  - raw/2014/07/remarkable-recovery-regularity-and.md
  - raw/2015/04/micro-stickiness-versus-macro-stickiness.md
  - raw/2015/11/is-micro-stickiness-enough.md
created: 2026-04-09
last_updated: 2026-04-09
---

# Labor Market

The [[information-transfer-model]] treats the labor market not as a single market but as **two markets** running in parallel — one for wages and one for employment quantity — and the relationship between them produces nearly all the puzzles that mainstream macro tries to explain with sticky-wage stories. Once you see the two markets, Okun's law is mechanical, the recovery regularity is mechanical, and the micro-vs-macro stickiness paradox dissolves.

## Two markets, one labor force

The ITM models the labor side of the economy as two distinct information equilibrium relationships:

- **$P_1 : \text{NGDP} \to \text{NW}$** — the nominal wage market. Aggregate demand transfers information to nominal wages via a "price" $P_1$ which is approximately constant ($\sim 2.1$ over the entire post-war US sample).
- **$P_2 : \text{NGDP} \to L$** — the employment market. Aggregate demand transfers information to the labor supply $L$ via a price $P_2$ which is *not* constant — it tracks the price level.

Empirically, $P_1$ is nearly flat: NGDP and nominal wages grow together at a near-fixed ratio. $P_2$ varies — it's responsive to monetary conditions in the same way the price level is.

![Two stickinesses: wage market (constant) vs labor market (responsive)](<../media/2014-01/wage stickiness -and other kinds- 2.png>)

This is the empirical signature of two markets with different κ values feeding off the same demand source. The wage market is so close to information equilibrium that variations are noise; the employment market lives in the same regime as the rest of the economy.

## Okun's law as identity

Once you accept the two-market structure, Okun's law falls out as an identity. Since $P_1 \approx 2.1$ is constant, $\text{NGDP} \approx 2.1 \cdot \text{NW}$ — total nominal wages always sum to NGDP/2.1. When NGDP falls, total nominal wages must fall by the same fraction. But wages don't fall (because $P_1$ is constant). So the only way for total nominal wages to fall is for **fewer workers to be employed**. Each unemployed worker contributes zero to NW; the wage market clears not by adjusting the price, but by adjusting the count.

This is what Okun's law observes empirically — a roughly fixed ratio between output gaps and unemployment gaps. In the ITM it isn't a behavioral relationship to be explained; it's a mechanical consequence of the two-market structure.

## Two kinds of stickiness

The labor market makes vivid a distinction that's harder to see in other markets — the difference between **relative** and **absolute** stickiness.

**Relative stickiness** is what [[sticky-prices]] usually refers to: prices respond less to monetary changes when κ is high. It's path-dependent and shows up in the price level. The same nominal shock produces a smaller price response in 2010 than in 1970 because κ has risen.

![Relative stickiness in the price level over time](<../media/2014-01/wage stickiness -and other kinds-.png>)

**Absolute stickiness** is what nominal wages display: $P_1$ is approximately *constant* over the entire post-war record, regardless of κ, regardless of monetary regime. There is no "less sticky" period to compare against. It's not that wages respond less than prices to monetary shocks — it's that the wage *market* is structurally different. The detector itself is invariant.

The mechanism: in markets with absolute stickiness, the *quantity* adjusts to clear the market rather than the *price*. There is always NGDP/2.1 worth of wages to go around; the market finds the number of workers that makes things consistent. Other markets work the opposite way (N widgets exist; the market finds the price). The labor market is one of the few major markets with this structure.

## Why the standard sticky-wage story is wrong

The mainstream story attributes recessions to micro-level wage rigidity — the "zero bin" of workers with no nominal wage change goes from 12% to 16% in a recession, and this 4-percentage-point shift causes the unemployment surge. The numbers don't work. The total aggregate wage-change effect of that shift is about $15 billion (0.2% × $7 trillion). The US economy loses several percent of GDP — hundreds of billions — in a recession. The micro stickiness is trivially small compared to the macro effect.

The real mechanism is **macro stickiness**: the inability to coordinate a change in the whole wage distribution simultaneously. This is an [[entropic-forces|entropy cost]] that has no microeconomic counterpart. Cutting everyone's wages by 5% requires the same amount of coordination entropy as laying off 5% of the workforce. The system prefers the higher-entropy state (some unemployed, rest at prior wages) over the lower-entropy state (everyone takes a coordinated cut). The math is the same as for any coordination failure — see [[non-ideal-information-transfer]] and [[entropic-forces]].

The labor market also illustrates the broader [[microfoundations-critique]] point: SF Fed data shows individual wages change frequently (about 80% of workers see annual wage changes), but the *aggregate* wage level is stuck. Just as with prices, micro flexibility coexists with macro rigidity. There is no individual-level mechanism that explains the aggregate behavior.

A subtler version: even when wage changes are sticky on a quarterly basis (5-18% probability of any change in a given quarter), the **timescale matters**. Over four quarters, the probability of at least one wage change rises to 19-55% by the birthday-problem logic. And iterating the wage-change distribution forward by the central limit theorem, downward nominal wage rigidity (which is real and ~20% in size on a quarterly basis) gets washed out over a few quarters: anything with finite mean and variance approaches a normal distribution under summation. So micro DNWR matters for quarter-to-quarter dynamics but vanishes on annual timescales. What persists is **macro** stickiness, which is structural rather than individual.

## Recovery regularity

A related observation: post-recession employment recoveries follow remarkably similar trajectories across decades and policy regimes. Different recessions hit at different speeds and depths, but the *shape* of the recovery is consistent. This is hard to reconcile with stories that attribute recessions to specific micro mechanisms (search costs, matching frictions, technology shocks) — those mechanisms vary across decades, but the recovery pattern doesn't.

In the ITM, the regularity is expected. Recovery is the system thermalizing back toward maximum entropy after a coordination failure. The destination (the [[plucking-model|efficiency ceiling]]) is the same across decades; only the magnitude and timing of the initial pluck vary. The journey looks similar because it's the same physical process every time.

## The labor force as the fundamental aggregate

The deepest implication of the two-market structure: if NGDP and the civilian labor force are themselves in [[information-equilibrium]] (with $k \approx 4$), then the labor force isn't just one input to the economy — it's the **fundamental aggregate** from which NGDP, inflation, and growth all flow. This is the [[quantity-theory-of-labor]]. Money and capital may be largely irrelevant in normal times; what determines long-run nominal output is just how many people are in the labor force. The two-market structure is the local mechanism, and the quantity theory of labor is the macroeconomic consequence.

## Race, gender, and hysteresis

The [[dynamic-information-equilibrium]] model applied to demographic subgroups reveals two major findings that require including race and gender in macroeconomics:

**Women entering the workforce caused the Great Inflation.** The timing is precise: positive shocks to female labor force participation and employment-population ratios *precede* the inflation shocks in every measure. The causal ordering is demographics → inflation, not monetary policy → inflation.

![Demographic shock timing: women's participation precedes inflation](<../media/2017-07/dynamic equilibrium history -women-.png>)

**Racial unemployment disparities are hysteresis, not ongoing discrimination in hiring.** Black and white unemployment follow the **same DIEM dynamics** — same slope, same recession shocks, same recovery rate. The only difference is the starting level (~10% vs ~5%). The DIEM for black unemployment, applied to white data with a different initial condition, describes both series equally well.

![Black DIEM applied to white unemployment — same dynamics, different initial conditions](<../media/2017-07/simple dynamic equilibrium test -eq black-.png>)

The implication: the racial unemployment gap is **initial conditions** from slavery and Jim Crow producing persistent hysteresis, not present-day discrimination in hiring dynamics. Both groups decline at the same relative rate and experience the same macro shocks. This argues for compensation/reparations rather than policy interventions targeting current-day hiring processes.

## Matching function from information equilibrium

The standard Mortensen-Pissarides search-and-matching model is replaced in the ITM with a matching function derived from first principles: if the information content of the state specified by hires ($H$) equals that specified by vacancies ($V$), the IE condition gives $dH/dV = k_v H/V$. The general equilibrium solution with unemployment $U$ as a second factor:

$$H(U, V) = a \cdot U^{k_u} \cdot V^{k_v}$$

This is the empirically-standard Cobb-Douglas matching function, but derived from information conservation and scale invariance rather than assumed. During [[recessions]], the shocks disrupt the matching function itself — the efficiency parameter $a$ drops, not just the levels of $U$ and $V$. This explains Beveridge curve shifts: coordination failure degrades the matching process.

The advantage: the IE approach compresses the micro complexity (heterogeneous search behavior, institutional details, bargaining solutions) into just 2–3 macro parameters. This is exactly the dimensional reduction the [[microfoundations-critique]] predicts — the heterogeneous agents "integrate out" to κ values at the macro scale.

## NAIRU as a κ ratio

The natural rate of unemployment emerges from the model as a ratio of information transfer indices:

$$u^* \approx \frac{\kappa_{LS}}{\kappa_U}$$

where $\kappa_{LS}$ comes from the labor supply market and $\kappa_U$ from the unemployment market. This makes NAIRU **endogenous** to the model rather than a free parameter to be estimated by observing the very inflation it's supposed to predict (see [[unobservables]]). Maximum entropy considerations alone — finite labor supply combined with many possible consumption periods — also produce a natural rate without any reference to wage rigidity. See [[phillips-curve]] for the reinterpretation of the Phillips curve as mean reversion around this natural rate.
