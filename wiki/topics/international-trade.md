---
title: International Trade
type: topic
tags: [trade, gravity-model, cobb-douglas, cross-country, comparative-advantage]
sources:
  - raw/2015/09/information-equilibrium-and-gravity.md
  - raw/2016/04/comparative-advantage-from-maximum.md
created: 2026-04-08
last_updated: 2026-04-09
---

# International Trade

The [[information-transfer-model]] derives the **gravity model of trade** — one of the most empirically successful relationships in international economics — directly from [[information-equilibrium]].

## The gravity model from information equilibrium

Trade volume $T$ between two countries is in information equilibrium with both countries' aggregate demand:

$$T \to N_1 \quad \text{and} \quad T \to N_2$$

This produces a Cobb-Douglas form: $T \sim N_1^{a} N_2^{b}$, which is exactly the gravity model. The derivation is essentially [[paul-krugman]]'s own intuitive argument formalized: the probability that a buyer in country A finds a seller in country B with something they want is proportional to B's population (information source size), and the number of such buyers is proportional to A's population (information destination size).

Krugman's "principle of insignificant reason" is literally the maximum entropy / maximum ignorance principle that underlies [[information-equilibrium]].

![Gravity model illustration](<../media/2015-09/get_event_image.png>)

## The distance puzzle

Both the effect of distance and the effect of borders on trade seem larger than concrete costs can explain. Smith raises a fundamental issue: the Earth's nation-states have highly **spatially correlated** wealth distributions (rich Europe, poor Africa). Distance is therefore correlated with partner NGDP, and if trade contributes to NGDP, this creates a feedback that makes it difficult to separate the distance effect from the wealth effect. The exact samples needed (countries with equal GDP at different distances) don't exist in nature.

If distance $D_{12}$ is itself in information equilibrium with NGDP, then the distance term in the gravity model may be an artifact of spatial correlation rather than a genuine trade friction.

## Comparative advantage from maximum entropy

The other "crown jewel" of trade theory — Ricardo's comparative advantage — also falls out of a maximum entropy argument. Take two countries (Portugal, England) with different absolute productivities for two goods (wine, cloth). Each country's production possibility set is bounded by its labor constraint. Under autarky, the maximum entropy production point for each country is somewhere in the interior of its own constraint set.

When trade is allowed, the joint **consumption** opportunity set expands beyond the production set of either country alone. The maximum entropy expected consumption is on the new joint frontier — and this implies that the most likely production points shift toward the goods each country has a comparative advantage in. Portugal (with absolute advantage in both goods) ends up specializing more in wine, England more in cloth. The result is **probabilistic** rather than deterministic: it's only marginally more likely that England specializes in cloth than the reverse.

The probabilistic version is more empirically accurate than Ricardo's deterministic version. Ricardo predicts a slope-1 relationship between relative productivity and relative trade share; empirical work finds the slope is positive and significant but smaller than 1. The maximum-entropy version naturally produces this attenuated effect because there's nontrivial probability mass on the "wrong" specializations.

The probabilistic framing also gives an evolutionary mechanism for **agglomeration**: a slight initial advantage gets reinforced over time as trade tilts production toward the comparative-advantaged good. And it explains why bacteria can trade metabolites (see [[emergent-representative-agent]]) without any rational-agent machinery — the math is exactly the same.

## Significance

This demonstrates the ITM's scope extends beyond domestic macroeconomics. The gravity model and comparative advantage — which economists use as workhorses for trade policy analysis and which Krugman called "crown jewels" of economic insight — both emerge from the same information-theoretic principles as [[supply-and-demand]], [[inflation]], and [[interest-rates]]. No trade-specific assumptions are needed; the same maximum-entropy argument that produces demand curves produces both gravity flows and comparative advantage.
