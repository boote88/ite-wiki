---
title: Information Trap
type: concept
tags: [core-framework, information-trap, monetary-policy, liquidity-trap]
sources:
  - raw/2013/08/the-liquidity-trap-and-information-transfer.md
  - raw/2013/09/the-liquidity-trap-and-the-information-trap.md
  - raw/2013/09/market-monetarism-falls-in-the-liquidity-trap.md
  - raw/2013/11/three-ideas.md
  - raw/2015/01/targeting-ngdp-is-awesome-if-only-it.md
  - raw/2015/01/eurozone-deflation.md
  - raw/2015/01/switzerland-depreciated-their-currency.md
  - raw/2015/01/powerful-evidence-for-information.md
created: 2026-04-07
last_updated: 2026-04-07
---

# Information Trap

The **information trap** is a central prediction of the [[information-transfer-model]]: a regime where monetary policy becomes ineffective regardless of interest rates. It is more general than the textbook liquidity trap and has been repeatedly confirmed by data.

## Definition

When the [[information-transfer-index]] κ approaches 1, the derivative of the price level with respect to the monetary base goes to zero:

$$\frac{\partial P}{\partial \text{MB}} = 0$$

This creates a "ridge" on the 3D price surface P(MB, NGDP). Beyond this ridge, further monetary expansion can actually *decrease* the price level.

## Formal theorem

Given a market P:NGDP→MB with floating source/destination and endogenous $\kappa(\text{NGDP}, \text{MB})$, there exists an MB* where $\partial P/\partial \text{MB} = 0$. This means **any** open-market monetary policy targeting (interest rates, inflation, NGDP level, NGDP growth) will eventually hit an information trap.

## Distinct from the zero lower bound

| | Zero Lower Bound | Information Trap |
|---|---|---|
| Mechanism | Interest rates can't go below zero | MB as unit of account limits monetary transmission |
| Can occur at | Only at ~0% nominal rates | Any interest rate level |
| Examples | US 2009 (0% rates) | EU 2013 (1-2% rates, still trapped); Switzerland (deflation despite currency peg) |
| Keynes' view | Special case at ZLB | Closer to Keynes' original claim that traps can occur at any rate |

## Why it happens

When the monetary base approaches the scale of NGDP, adding more money doesn't add more information capacity — it's like adding digits to a number system that already has enough precision. The MB *is* the number system the economy uses (base ~283 in 2013 US). As κ → 1, the base approaches the number itself.

## Empirical evidence

The information trap is not a theoretical curiosity — it has been confirmed across multiple countries:

- **[[japan]]**: the canonical case. Crossed the κ = 1 ridge around 2000, then expanded MB by ~3.5x, moving further into the trap. Monetary stimulus worsened the situation. Smith's 2015 correction showed that even the apparent Abenomics inflation success was mean reversion, not a policy effect.
- **[[ecb-eurozone]]**: the trap caught in real time. The ITM predicted Eurozone deflation in November 2013; it arrived on schedule in early 2015. The ECB's trillion-euro QE in January 2015 produced **no change** in the model's inflation predictions. Trapped at 1–2% interest rates, well above the ZLB.
- **Switzerland**: the SNB pegged the franc to the Euro to depreciate it — but still got deflation. Abandoned the peg in January 2015. Exchange rates decouple from inflation in the trap.
- **US**: approaching the trap post-2008; QE insufficient and possibly counterproductive past the ridge. The oscillations in M0 growth rates (widening like a bifurcation fractal) are empirical evidence the Fed is struggling to steer.
- **Australia/Sweden**: low κ, not in the trap — monetary policy effective.

Plotting actual M0 growth vs NGDP growth data on the ITM's theoretical curves produces a striking triangle pattern: data points fade chronologically from purple (1965) to red (2015) along curves with declining slopes — direct visual evidence of κ increasing over time and the trap approaching.

## All targeting eventually fails

The ITM is an existence proof that both NGDP targeting and inflation targeting eventually require **exponentially more money printing**. The relationship $\log P \sim k \log M0$ has a slope $k$ that decreases over time. By 2015, achieving 2% US inflation requires >15% M0 growth — unprecedented outside WWII. A 5% NGDP target is achievable today but will become harder and harder without printing more money in the future. There is a practical wall around ~10% annual currency growth that the Treasury has almost never breached.

## Onset and nature

The information trap has **no well-defined start** — it approaches gradually as κ increases over decades. The US started on this path in the 1980s, but it became obvious only when the 2008 shock hit and monetary policy couldn't handle it. The early 2000s recession was light enough to mask the problem.

The trap has **no microfoundations** — it doesn't exist for a single market. It's tied to [[economic-potentials|economic temperature]] ($T \sim 1/\log \text{MB}$): a large monetary base means a cold economy. Just as temperature doesn't exist for a few atoms, economic temperature doesn't exist for a few markets. The standard story (DeLong, Krugman) — that people don't distinguish 0% cash from 0% bonds — is a micro explanation for a macro phenomenon.

US history can be read as **two monetary regimes**: a gold standard regime that hit its information trap after centuries (producing the Great Depression) and a fiat currency regime that hit its trap after only ~80 years (producing the post-2008 stagnation). The "omega point" question — when does monetary policy return to normal? — may have no answer within the current regime.

## Exit mechanisms

All historical exits involved discontinuous regime changes, not gradual policy adjustments:

1. **Redefine the currency** — leaving the gold standard for fiat. Can't keep doing this. Electronic money with truly negative rates might be a future option.
2. **Wartime/peacetime hyperinflation** — a command economy pushes $\log \text{NGDP}$ up faster than $\log \text{M0}$. The WWII-era interest rate peg and loss of Fed independence may have been the mechanism. Buys decades but you eventually fall back in.
3. **Massive fiscal expansion** — pushing NGDP up while keeping M0 growth normal raises $\log \text{NGDP}/\log \text{M0}$. Same temporary effect.
4. **Interest rate peg** — the UK appears to have achieved regime change via pegs (twice), with an initial burst of inflation.

The mechanism behind options 2 and 4 is the same: **pegging a rate (interest or exchange) breaks an information transfer channel.** When you fix one of the prices in the IE system, the differential equations become chaotic in the technical sense — exponential separation of phase-space trajectories, Lyapunov-like behavior. Hyperinflation episodes historically all involve pegged rates or pegged exchange rates rather than uncontrolled M0 growth or deficits per se. Money-printing and deficits *accompany* hyperinflation but aren't the trigger; the trigger is breaking the information channel by fixing a price. This is one of the few ITM claims about hyperinflation that distinguishes it from the standard "too much money chasing too few goods" story, and it has implications for how to (or how not to) escape an information trap.

## Do we want the trap to end?

A liquidity-trapped world has low interest rates and low inflation. Retirement insurance is cheaper. Infrastructure is cheap to build at 0%. The main cost is losing monetary policy as a macroeconomic lever — but perhaps [[fiscal-policy]] (unemployment insurance, UBI) is a better lever anyway, since it doesn't rely on devaluing currency and tricking people with money illusion. Japan has lived with the trap for decades. Perhaps developed economies should adapt rather than try to escape.

## Implications

- Market monetarism (NGDP targeting) cannot escape the trap
- [[fiscal-policy]] *can* work in the trap because $\partial P/\partial \text{NGDP} \neq 0$ even when $\partial P/\partial \text{MB} \approx 0$
- [[secular-stagnation]] is a natural consequence of being in/near the trap
- Countries' proximity to the trap is predicted by their [[information-transfer-index]] κ
