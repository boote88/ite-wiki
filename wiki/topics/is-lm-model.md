---
title: IS-LM Model
type: topic
tags: [is-lm, monetary-policy, interest-rates, liquidity-trap, regimes]
sources:
  - raw/2013/08/deriving-is-lm-model-from-information.md
  - raw/2013/08/on-krugmans-models-and-mechanisms.md
  - raw/2014/06/krugman-keynes-and-liquidity-trap.md
  - raw/2014/06/how-does-liquidity-trap-work.md
  - raw/2015/04/information-theory-and-economics-primer.md
created: 2026-04-09
last_updated: 2026-04-09
---

# IS-LM Model

The IS-LM model is the workhorse macroeconomic framework taught in undergraduate textbooks — Keynesian goods market (IS) and money market (LM) intersecting to determine output and interest rates. The [[information-transfer-model]] derives IS-LM directly from information equilibrium, showing it's not an ad-hoc construction but a natural consequence of two markets sharing a common price (the interest rate). More importantly, the ITM derivation reveals **how the IS curve changes shape over decades** as the [[information-transfer-index]] κ evolves — explaining why monetarist, Keynesian, and liquidity trap interpretations all describe the same economy at different times.

## Derivation from information equilibrium

In the information equilibrium framing, IS-LM is two markets running off a common information source:

- **IS** is a goods market: aggregate demand transferring information to investment, with the interest rate as the price
- **LM** is a money market: aggregate demand transferring information to the money supply, also with the interest rate as the price

The interest rate functions as the shared "price" (detector) coupling the two markets. The standard IS-LM diagram emerges from looking at the locus of (interest rate, output) points consistent with both markets being in [[information-equilibrium]]. There's nothing ad-hoc about it — given the information-theoretic structure and a shared interest rate, the IS-LM diagram is what you get.

The same is true for the [[ad-as-model]], which is essentially the price-level analog: instead of the interest rate as detector, the price level serves the same role. AD-AS and IS-LM are two views of the same underlying ITM machinery, distinguished only by which "price" you're tracking.

## IS-LM as the low-inflation effective theory of AD-AS

IS-LM can be derived as the **effective theory** of AD-AS in a specific scope: low inflation, low interest rates. Start from $N \rightleftarrows M \rightleftarrows S$ with $P : N \rightleftarrows M$. The general solution is $N \sim M^k$ and $P \sim k M^{k-1}$. When $k \approx 1$ (one way of stating the scope condition), $N \sim M$ and $P \approx \text{constant}$ — inflation is approximately zero. In this limit, $N \approx Y$ (nominal output equals real output because there's no inflation gap), and the basic ITM relations reduce to the IS-LM equations directly.

The scope condition can be made quantitative: the model is valid when both inflation and the real interest rate are small compared to the average growth rate of M0 (~7%/year for the US). When $\pi \ll \mu$ and $r \ll \mu$, the IS-LM approximation works to ~10% accuracy. When $\pi$ or $r$ become comparable to $\mu$, you're outside the IS-LM regime and need to use the full AD-AS / ITM machinery.

This is the same kind of statement Newton's gravity makes: the inverse-square law works fine for slow speeds and weak fields, even though general relativity is the more fundamental theory. **Any model that describes low-inflation data will be approximated by IS-LM**, regardless of its underlying mechanism — because IS-LM is what falls out of the data in that regime.

![Monetary expansion in the IS-LM regime](<../media/2016-02/ISLM -diagram-.png>)

![Fiscal expansion and monetary offset](<../media/2016-02/ISLM 2 -diagram-.png>)

The first diagram shows monetary expansion (interest rate falls, base expands, output rises later as the system re-equilibrates). The second shows the central bank "moving last" — fiscal expansion can be offset by central bank action. This is the basic monetary offset story, and it's exactly what IS-LM predicts.

At the zero lower bound, the same diagrams change shape:

![Monetary expansion at the ZLB](<../media/2016-02/ISLM -diagram- zero 1.png>)

![Fiscal expansion at the ZLB](<../media/2016-02/ISLM -diagram- zero 2.png>)

At $r \approx 0^+$, large monetary expansion barely moves output (monetary policy is ineffective) and large fiscal expansion happens without significant base movement (no monetary offset). The mechanics of the liquidity trap fall out of the diagrams without any new assumptions.

## The IS curve evolves over decades

The most striking result of the ITM derivation is that the **shape of the IS curve changes systematically over time**, driven by changes in κ. Smith generates IS curves at different points in the post-war US economy by simulating how the interest rate and output respond to monetary expansion/contraction at each point on the price surface. The result is a sequence of curves, each one centered on a different decade:

![IS curve evolution from 1960s to 2010s — three regimes visible](<../media/2014-06/basic us price level m0 interst rates -krugman 1998 liquidity trap- big.png>)

Three qualitative regimes are visible:

**1960s monetarist regime (purple/violet curves):** the IS curve slopes *upward*. Higher interest rates are a sign monetary policy has been *loose* — the central monetarist intuition. Low κ; the [[quantity-theory-of-money]] regime applies; monetary policy is highly effective.

**1970s–80s Keynesian regime (green curves):** the IS curve slopes downward, the textbook orientation. Lowering interest rates boosts output. Moderate κ. The standard IS-LM story works exactly as undergraduate textbooks describe.

**Post-2008 liquidity trap regime (orange/red curves):** the IS curve becomes nearly **vertical**. Output is almost independent of interest rates. Raising or lowering rates has little or no effect. High κ; the [[information-trap]] is in force; monetary offset is impossible.

The same economy, the same fundamental information-theoretic mechanics — but qualitatively different IS curves at different times. This explains the ongoing arguments between monetarists, Keynesians, and post-Keynesians: each school is correctly describing the IS curve in its own preferred regime, and incorrectly generalizing it to all times.

## Spaghetti at the zero lower bound

What does the IS curve look like when interest rates approach zero? Smith plots the [[zero-lower-bound]] regime on a linear scale and discovers something striking: pushing the rate toward zero produces a **deflationary monetary expansion** — the output peak occurs at a rate above zero, and forcing rates lower actually reduces nominal output.

![IS curve at the ZLB: the spaghetti bend](<../media/2014-06/basic us price level m0 interst rates -krugman 1998 liquidity trap- 3a.png>)

![Linear scale view of the ZLB regime](<../media/2014-06/basic us price level m0 interst rates -krugman 1998 liquidity trap- 3b.png>)

The visual is "like pushing a piece of uncooked spaghetti against the countertop with the spaghetti bending away." This is exactly Krugman's "point 2" in his 1998 Brookings paper on liquidity traps — the point where additional monetary expansion stops increasing output. The ITM reproduces this peak naturally without any of the rational-expectations machinery Krugman used.

## Liquidity traps don't require the ZLB

A direct consequence of the IS curve regime analysis: **the economy doesn't need to be at the zero lower bound to experience a liquidity trap.** All it needs is to be near the [[information-trap]] criterion ($\partial P/\partial \text{MB} = 0$) where κ approaches 1. The IS curve becomes vertical at high κ regardless of the level of nominal interest rates.

This is the connection back to Keynes's original definition of the liquidity trap, which made no reference to zero rates. Keynes described a regime where additional monetary expansion fails to lower interest rates further or stimulate output. In the ITM, that's the high-κ regime, which can occur anywhere on the rate spectrum. The Eurozone in 2011–2015, with rates at 1–2%, was in a liquidity trap (see [[ecb-eurozone]]) — the standard "ZLB-or-bust" framing missed this entirely.

The ITM unifies what Krugman and Keynes were saying with what monetarists were saying: monetarists are right when κ is low; Keynes-Krugman are right when κ is high; the same model produces both.

## Implications

- **Monetary offset** of fiscal policy works in the upward- and downward-sloping IS regimes (low to moderate κ) but fails in the vertical IS regime. Sumner's market-monetarist position depends on the IS curve having a particular shape, which it does — but only sometimes
- **Yield curve inversion** as a recession signal has an IS-LM interpretation: the NGDP-MB path approaching the NGDP-M0 trend line corresponds to the ZLB end of the IS curve, where small disturbances produce large output movements
- **The "neutral" interest rate** is not a fixed quantity but a moving point on the time-varying IS curve. See [[unobservables]] for why this means standard "natural rate" estimates are circular
- **Standard IS-LM teaching is regime-specific**: textbooks generally present the downward-sloping (Keynesian) version, but this is a special case of a much richer family of curves
