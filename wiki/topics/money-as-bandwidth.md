---
title: Money as Bandwidth
type: topic
tags: [money, information-theory, bandwidth, shannon-hartley]
sources:
  - raw/2013/05/money-is-amoral-tool-and-other.md
  - raw/2015/05/money-defined-as-information-mediation.md
created: 2026-04-07
last_updated: 2026-04-07
---


# Money as Bandwidth

In the [[information-transfer-model]], money (including short-term treasuries and other monetary aggregates) is analogous to **bandwidth** in information theory — channel capacity for economic information transfer.

## Implications

- Money is an **amoral tool** for moving information from one place to another, not imbued with moral significance around thriftiness or "hard money"
- From the Shannon-Hartley theorem: economic growth (more information transferred) requires increasing the money supply (bandwidth) — necessary but not sufficient
- Other ways to increase information transfer: increase SNR, improve coding, make markets more "ideal" ($I_{Q^d} = I_{Q^s}$)
- Making markets more transparent corresponds to making information transfer more ideal

## Channel capacity bound

Smith calculates a theoretical upper limit: with ~1% price fluctuations (20 dB SNR), single-precision numbers, and microsecond-scale HFT, a single price mechanism can transfer at most ~200 Mbps of information.

## Money as information mediation

A precise mathematical definition: money is a **mediating variable** in the information transfer from aggregate demand to aggregate supply. Starting from the [[ad-as-model]] P:N→S, introduce money M via the chain rule:

$$\frac{dN}{dS} = \frac{dN}{dM} \cdot \frac{dM}{dS}$$

If N is in [[information-equilibrium]] with M, and M with S, then the price level goes as $P \sim (N/M)^{1/\kappa}$ — the quantity theory of money with deterministic κ.

Key insight: the composite index $k_n = k/k_s$ is the ratio of the demand→money and supply→money conversion factors. A [[information-trap|liquidity trap]] economy has $k_s \approx k$ (i.e. κ ≈ 1), while a [[quantity-theory-of-money]] economy has $k > k_s$ (i.e. κ < 1).

Out of equilibrium, supply shocks (supply out of IE with money) tend to produce inflation (e.g., 1970s oil shocks), while demand shocks tend to produce disinflation.

## Money is unimportant

The most provocative conclusion: in modern moderate-inflation economies, **money doesn't matter** for macroeconomic dynamics. Three arguments:

1. **Mathematical identity**: inserting money $M$ that mediates transactions into an IE condition is just a chain rule: if $A \rightleftarrows B$ then $A \rightleftarrows M \rightleftarrows B$ is $M/M = 1$ away. Money adds nothing to the structure.

2. **Indicator dye during non-ideal transfer**: recessions and other shocks involve [[non-ideal-information-transfer]] caused by agent correlation in state space. Money in these situations is just an "indicator dye" — iron filings conforming to the field, smoke in a wind tunnel. It shows you what's happening but doesn't cause anything.

3. **Trivial high-inflation role**: in a multi-factor model with money $M$, labor $L$, and other factors, the inflation equation is $\pi \sim \langle \alpha - 1 \rangle \lambda + \ldots + \langle \beta - 1 \rangle \mu$. When money growth $\mu$ is large, the money term dominates and you get the [[quantity-theory-of-money]]. But this is a trivial relationship that only holds over 10% inflation. For modern economies, the demographic and supply terms dominate.

The conclusion: $\partial R / \partial M \approx 0$ for any macroeconomic variable $R$ in policy-relevant modern scenarios. Money doesn't need to be understood, defined, or tracked to predict inflation, output, or employment in normal times. Only in truly extreme cases (hyperinflation, or removing money entirely) does it make a difference.

## Money is the aether of macroeconomics

The strongest version of this argument: the endless search for the "right" monetary aggregate (M1? M2? MZM? NGDP expectations? Government debt?) is the macroeconomic equivalent of searching for the luminiferous aether. Something *must* be the medium in which inflation waves propagate! M1 didn't work, so M2! Interest rates! No, it's expectations of monetary expansion! No, it's expectations of monetary expansion *that might be taken away!*

This parallels the history of physics exactly. Aether dragging → partial aether dragging → the realization that the medium doesn't exist and electromagnetic waves propagate through the geometry of spacetime itself. In economics: money dragging (QTM) → partial money dragging (expectations-augmented QTM) → the realization that inflation is demographic and money is just along for the ride.

MMT and Austrian economics both start from the premise "money is a tool for moving real resources" — they just disagree on how much inflation is acceptable. But both are empirically supported only in the high-inflation regime where the [[quantity-theory-of-money]] holds. At moderate inflation, neither has empirical traction. The ITM shows why: money enters through a mathematical identity (chain rule + M/M = 1) and is therefore arbitrary. Whatever you think money is, it doesn't matter — unless you're in hyperinflation or a financial system seizure.

The real driver of post-war US inflation was **demographic** — shocks to the labor force size precede and predict shocks to inflation, while shocks to the monetary base *follow* them. Money was the iron filings; labor force change was the magnet. See [[quantity-theory-of-labor]] and [[inflation]].

## New channels problem

When existing information channels fail (e.g., [[zero-lower-bound]] on interest rates), switching to a new channel (e.g., NGDP futures) is costly — the new channel starts with highly non-ideal information transfer. Like switching from voice calls to early text messages: the full expressive language (emoticons, abbreviations) hasn't developed yet. The Fed has built up a "language" around interest rate targeting over decades; a new channel would need time to develop equivalent information transfer capacity.
