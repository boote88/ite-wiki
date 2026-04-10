---
title: Quantity Theory of Labor
type: concept
tags: [labor, ngdp, growth, inflation, ie, capital]
sources:
  - raw/2016/01/is-cpi-information-theoretic-measure-of.md
  - raw/2016/01/its-people-economy-is-made-out-of-people.md
  - raw/2016/03/a-quantity-theory-of-labor-and-capital.md
created: 2026-04-09
last_updated: 2026-04-09
---
I 
# Quantity Theory of Labor

The **quantity theory of labor** is a model of long-run economic growth that the [[information-transfer-model]] discovered in early 2016: NGDP, the price level, and economic growth itself are determined primarily by the size of the **civilian labor force** rather than by money, technology, or capital. It's the most provocative reframing of macroeconomics in the wiki because, if right, it implies that nearly every standard explanation of growth and inflation is at best a side-effect of the underlying labor-force dynamics.

## The model

In information equilibrium notation:

$$\text{CPI} : \text{NGDP} \rightleftarrows \text{CLF}$$

CPI is the detector for the information equilibrium between nominal output and the civilian labor force. Solving the differential equation in general equilibrium:

$$\text{NGDP} = n \left(\frac{\text{CLF}}{c}\right)^k$$

$$\text{CPI} = \frac{n}{c} k \left(\frac{\text{CLF}}{c}\right)^{k-1}$$

with $n$ and $c$ constants and $k$ the [[information-transfer-index]] for this market. Empirically, $k \approx 4$.

The geometric interpretation: if the labor force is the radius of a 4-sphere, NGDP is proportional to its 4-volume and CPI is proportional to the 3-volume of its surface.

![Empirical fit: NGDP from CLF](<../media/2016-01/simpleNGDPmodel 1.png>)

![NGDP growth fit](<../media/2016-01/simpleNGDPmodel 2.png>)

![Inflation fit](<../media/2016-01/simpleNGDPmodel 3.png>)

The fits are remarkable for a one-parameter model. NGDP, inflation, and nominal growth all fall out of the labor force time series with a single index.

## A simpler version: just CPI from CLF

The minimal version is even sharper: $\text{CPI} \rightleftarrows \text{CLF}$, with inflation rate equal to $a$ times the labor force growth rate where $a \approx 2.67$. This works for the US, Japan, and Canada — same coefficient, same fit quality. See [[inflation]] for the cross-country version.

## What it implies

The quantity theory of labor has far-reaching consequences if taken seriously:

**Money is mostly irrelevant in normal times.** The Fed has little control over the economy except by occasionally crashing it. Monetary theories aren't causal in the traditional sense — they may matter through [[non-ideal-information-transfer]] (the mechanism of market failure), but during normal periods monetary policy is largely a coordinating ritual rather than a real lever.

**Technology growth is irrelevant except indirectly.** Robert Gordon's story of the "Great Inventions" driving the 20th-century growth miracle becomes a side-effect: technology mattered insofar as it allowed more people to participate in the labor force (mechanization freeing agricultural labor for industry; appliances freeing women from domestic work; transport allowing geographic mobility). The growth wasn't *caused* by inventions; it was caused by the resulting changes in labor force composition.

**Keynesian fiscal stimulus works through labor force expansion.** Public works create jobs that draw people into the labor force; that's the channel. Inflation-based fiscal mechanisms are red herrings.

**Immigration is the remaining growth engine.** With the women-entering-workforce transition complete and population growth slowing, immigration is the only remaining source of labor-force-driven GDP expansion in the US. A shock to the labor force produces an NGDP shock roughly 4–6 times larger. Restricting immigration by 2 million people over four years → ~$1 trillion lower NGDP by 2022 (~$500B per million people). This makes anti-immigration policy a self-inflicted macroeconomic wound of the first order.

An intriguing finding: unauthorized immigration data is consistent with a large inflow shock in the 1990s that **picks up exactly where women entering the workforce leaves off** — maintaining labor force growth after the demographic transition completed. The dot-com bubble, housing bubble, and financial crisis all follow the waning of that immigrant-driven growth wave.

![NGDP and CLF with immigration shock](<../media/2018-01/immigration3.png>)

**The Solow model degenerates.** In the [[solow-growth-model]] with this scaling, labor has an exponent of ~4 and capital has an exponent of 0. Capital does not enter the long-run growth equation in any meaningful way.

**The "Great Inventions" story has it backwards.** The economic boom of the industrial revolution wasn't about steam engines and railroads in themselves — it was about people leaving subsistence farming for the industrial labor force. The same explains China's recent boom (mass migration from rural subsistence to urban employment) and the US 1960s–70s inflation (women and African Americans entering the workforce, raising the participation rate faster than population). See [[inflation]] for the historical narrative.

## Business cycles

How does this generate recessions and short-run fluctuations? The same way other ITM models do — through [[non-ideal-information-transfer]]. When information transfer breaks down, the equilibrium relationships become inequalities:

$$\text{NGDP} > n (\text{CLF}/c)^k$$
$$\text{CPI} < (n/c) k (\text{CLF}/c)^{k-1}$$

A fall in the labor force (or a coordination failure that effectively reduces it) leads to a fall in nominal output and a temporary shock to the price level. The Fed could play the role of Roger Farmer's "Mr. W" in his sunspot model — a coordinating signal that occasionally produces pessimistic expectations and triggers downturns. But the more agnostic ITM view is that coordination failures arise spontaneously in open markets and the Fed is at most one trigger among many.

## Connections

The quantity theory of labor is a major refinement that connects to many existing pages. It's the structural foundation underneath the [[phillips-curve]] (the apparent inflation-unemployment relationship was just the side-effect of rising participation), [[inflation]] (replaces the QTM as the dominant mechanism in normal times), [[labor-market]] (the two-market structure with NGDP-CLF as the most fundamental relationship), [[solow-growth-model]] (capital exponent of zero is a strong test), and the [[information-trap]] story (the Fed's ineffectiveness at high κ is consistent with monetary policy never having been the true driver). It also reframes [[secular-stagnation]] as a demographic phenomenon — slow population growth means slow inflation and slow nominal GDP growth, period.

The strongest claim: if this model is right, central bank inflation targeting is essentially a cargo cult. Demographics will determine the inflation rate, and central bankers performing rituals associated with that outcome will get credit (when participation rates align) and blame (when they don't) — but the underlying signal is the population pyramid, not the policy rate.

## Adding capital: the quantity theory of labor and capital

The labor-only model has two empirical problems: it underestimates RGDP (an across-the-board offset), and it doesn't fit the UK well. Both go away when you add capital as a second information source. The model becomes a Cobb-Douglas form derived from two simultaneous information equilibrium relationships:

$$\text{CPI} : \text{NGDP} \rightleftarrows L$$
$$X : \text{NGDP} \rightleftarrows K$$

Solving in general equilibrium:

$$\text{NGDP} = n_0 \left(\frac{L}{l_0}\right)^{\beta} \left(\frac{K}{k_0}\right)^{\gamma}$$

$$\text{CPI} = \frac{n_0}{l_0} \beta \left(\frac{L}{l_0}\right)^{\beta-1} \left(\frac{K}{k_0}\right)^{\gamma}$$

This is the [[solow-growth-model]] form, but emerging from information equilibrium rather than from a production function assumption — and crucially, $\beta + \gamma$ is not constrained to equal 1.

![Quantity theory of labor and capital fit](<../media/2016-03/simpleNGDPmodel -SOLOW 2- 1.png>)

![NGDP growth fit with capital](<../media/2016-03/simpleNGDPmodel -SOLOW 2- 2.png>)

![Inflation fit with capital](<../media/2016-03/simpleNGDPmodel -SOLOW 2- 3.png>)

The country-by-country exponents tell a story about economic structure. The US has $\beta \approx 0.8, \gamma \approx 0.7$ — labor-dominant but with capital making a real contribution. The UK has $\beta \approx 0.5, \gamma \approx 1.0$ — much more capital-intensive, which is exactly why the labor-only model fit the UK poorly. The original UK puzzle was diagnostic information about the structure, not an indictment of the framework.

The exponents in this picture are also the closest the ITM gets to a "production function" interpretation, but with a critical difference from textbook Solow: the framework imposes no constant-returns-to-scale assumption. The empirical exponents simply are what they are, and they do not in general sum to one. See [[solow-growth-model]] for the Cambridge capital controversy and Gibbs-paradox arguments for why this is the right framing.

## Two models held simultaneously

Smith holds both this and the monetary [[information-equilibrium]] model in his head at once. Both are empirically successful at explaining liquidity traps, but with different mechanisms — the monetary model says monetary policy fails because κ → 1; the labor model says monetary policy never controlled inflation in the first place. They're not necessarily incompatible. The labor force size might be what makes large economies "colder" (high κ), or the monetary model might be what determines the labor force size. The Fed's [[information-trap]] in the monetary model and the Fed's irrelevance in the labor model could be the same phenomenon viewed from different angles.

The fact that the labor model was put forward as a reductio ad absurdum and turned out to be empirically successful is itself the point. It's an Occam's razor challenge: if your model of inflation is more complicated than "labor force growth times 2.67" and isn't more empirically accurate, then it doesn't get to claim the additional structure. The labor model is the new floor — anything fancier needs to do better, and most established macro models cannot.
