---
title: Solow Growth Model (ITM Version)
type: topic
tags: [growth, solow, capital, labor, tfp]
sources:
  - raw/2014/12/the-information-transfer-solow-growth-model.md
  - raw/2015/05/resolving-cambridge-capital-controvery.md
  - raw/2015/06/eulers-theorem-rival-inputs-and.md
created: 2026-04-07
last_updated: 2026-04-07
---

# Solow Growth Model in the ITM

The [[information-transfer-model]] produces a version of the Solow growth model where the factor exponents **do not sum to one** (α + β ≠ 1).

## ITM Solow model

Using information equilibrium between output and inputs:
- κ₁ = 1.18 (labor contribution)
- κ₂ = 2.50 (capital contribution)

The asymmetry arises because heterogeneous job types and capital types have **different information entropies** — there are more meaningfully different ways to deploy capital than labor, leading to unequal factor contributions.

The cleanest formulation comes from running two simultaneous information equilibrium relationships through NGDP — one for labor and one for capital — and solving them together:

$$\text{CPI} : \text{NGDP} \rightleftarrows L$$
$$X : \text{NGDP} \rightleftarrows K$$

where $X$ is the capital deflator. The general equilibrium solution is the Cobb-Douglas form $\text{NGDP} = n_0 (L/l_0)^{\beta} (K/k_0)^{\gamma}$, which fits empirical data extremely well — and the exponents differ across countries depending on how capital-intensive each economy is. The US has $\beta \approx 0.8, \gamma \approx 0.7$; the UK has $\beta \approx 0.5, \gamma \approx 1.0$ (much more capital-intensive). This is the [[quantity-theory-of-labor]] (with capital) — the most comprehensive ITM model of long-run macroeconomic dynamics, and the one that resolves the puzzles left by the labor-only version.

## Total factor productivity and the Solow paradox

TFP (the Solow residual) is reinterpreted as real NGDP growth "unlocked" by labor force expansion — and the "great stagnation" is simply the exhaustion of that labor force growth source.

The **Solow paradox** ("You can see the computer age everywhere but in the productivity statistics") gets a clean explanation in this framework: household technology (washing machines, dishwashers) allowed new people **to enter** the labor force, while computers were mostly used by people **already in** the labor force. Technologies that expand who participates show up in GDP; technologies that make existing participants more efficient may not, because GDP doesn't measure what's not counted.

This can be pushed further: the "great inflation" of the 1970s may partly be a **measurement artifact**. Household production (not counted in GDP) was automated by labor-saving appliances, freeing people for labor-market work (counted in GDP). If household production were counted, there might not have been a "great inflation" at all — just a reclassification of activity from uncounted to counted categories.

The parallel extends to the **Industrial Revolution itself**: DIEM analysis of UK income data from 1250 to present shows a growth shock that matches the slave trade timeline. The IR arrives *as the income growth surge from slavery fades* — just as computers arrived as the growth surge from women entering the workforce faded. Neither the IR nor the IT revolution shows up in macro growth metrics. Two Solow paradoxes, same pattern, centuries apart. The technologies that matter for measured growth are the ones that change *who participates*, not the ones that change *how efficiently existing participants work*.

## A more radical reframing

The [[quantity-theory-of-labor]] pushes the Solow framework even further. If NGDP is in information equilibrium with the civilian labor force alone (with index $k \approx 4$), then capital's exponent in the production function is **zero** and labor's is 4 — far from the constant-returns assumption (α + β = 1) and even further from a balanced contribution. Capital, in this picture, doesn't enter long-run growth at all. Technology growth (Robert Gordon's "Great Inventions") matters only insofar as it changes who participates in the labor force. The Solow residual (TFP) becomes a measurement artifact rather than a fundamental driver — what looks like "productivity growth" is actually changing labor force participation patterns.

Key visualization: nominal capital-labor-output model fit vs. data (raw/2014/12/media/).

## Cambridge capital controversy resolved

The ITM resolves the Cambridge capital controversy using abstract algebra. [[information-equilibrium]] is a **group under multiplication but not a ring** — not closed under addition. This means you **can't** add up different capital goods (Joan Robinson was right), but you **can** take geometric means, which produce Cobb-Douglas aggregation. This is why Cobb-Douglas production functions work empirically: they use the algebraically correct aggregation method. The ITM Solow model's α+β≠1 follows naturally — it's the result of using geometric means rather than assuming constant returns to scale.

## Why α + β > 1: Gibbs paradox and distinguishable inputs

The standard assumption of constant returns to scale (α + β = 1) requires that inputs are effectively **indistinguishable** — like identical atoms in a gas. But economic inputs (workers, capital goods) are distinguishable: Amy is different from Bill, and you can tell who works where after a merger splits up. This matters because entropy depends on distinguishability.

The Gibbs paradox from physics illustrates: combining two boxes of indistinguishable gas produces entropy $2S$, but combining distinguishable particles produces $(2+\delta)S$. In physics, the resolution is that particles *are* indistinguishable (and the energy cost of distinguishing them restores extensivity). In economics, distinguishing inputs is cheap — names are free.

The entropy function $\log N! \approx N \log N - N$ shows increasing returns at economically relevant scales (~$10^6$), only approaching constant returns at physically large scales (~$10^{23}$):

![Entropy showing increasing returns at economic scales](<../media/2015-06/entropy and eulers theorem.png>)

This connects to [[secular-stagnation]]: perhaps it's simply the economy approaching the extensivity limit — the scale where constant returns finally kick in and growth from adding more inputs halts. Growth economists may be studying the eventual equilibrium of an entropic process.

## References

- [The information transfer Solow growth model (2014-12-04)](../../raw/2014/12/the-information-transfer-solow-growth-model.md)
- [Resolving the Cambridge capital controversy (2015-05-28)](../../raw/2015/05/resolving-cambridge-capital-controvery.md)
- [Euler's theorem, rival inputs and distinguishable particles (2015-06-12)](../../raw/2015/06/eulers-theorem-rival-inputs-and.md)
