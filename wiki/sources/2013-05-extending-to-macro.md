---
title: "May 2013: Extending to Macroeconomics"
type: source
tags: [macro, ad-as, is-lm, inflation, sticky-prices, money]
sources:
  - raw/2013/05/sticky-prices.md
  - raw/2013/05/other-aspects-of-price-changes-under.md
  - raw/2013/05/what-picture-of-economics-is-emerging.md
  - raw/2013/05/what-is-arbitrary-here.md
  - raw/2013/05/macroeconomics-as-information-transfer.md
  - raw/2013/05/money-is-amoral-tool-and-other.md
  - raw/2013/05/rescaling-and-inflation.md
  - raw/2013/05/economics-as-counting-problem.md
created: 2026-04-07
last_updated: 2026-04-07
---

# May 2013: Extending to Macroeconomics

8 posts that take the [[information-transfer-model]] from micro supply-and-demand to full macroeconomics, while also stress-testing the framework's assumptions.

## Sticky price simulations (May 4)

Smith builds a **Wiener process** (random walk) model of price dynamics under [[non-ideal-information-transfer]]:

- Inside the uncertain region between supply curves, the price experiences no restoring force (like a broken pressure gauge on a container)
- Individual price paths look like random walks
- But averaging over many paths reveals **sticky prices**: the mean price resists moving after a demand shift
- Prices are sticky *downward* only — upward demand shifts produce immediate price responses
- This recovers the modern view without any micro-theory (menu costs, money illusion, signaling)

The analogy: "a pressure vessel with a broken pressure gauge. If the temperature drops, the equilibrium will move but the change may not register on the gauge."

## Self-critique: what is arbitrary? (May 10)

Smith lists the framework's non-mathematical assumptions:
1. Price as the "detector" of information transfer (fundamental assumption)
2. Demand must be the source (not destination) for signs to work out
3. Hartley definition of information (all states equally probable) — could use Shannon or Rényi instead
4. Observed price as lower bound on the supply curve ("rational expectations" of this theory)
5. No force inside the uncertain region

He notes the lower-bound assumption isn't stable — it leads to upward drift toward the center, which connects to [[inflation]].

## Extrapolation to AD-AS (May 20)

The ITM generalizes directly to **aggregate supply / aggregate demand**:
- Information source = aggregate demand, destination = aggregate supply
- "Price" = price level
- All previous results carry over: sticky prices, restoring forces, supply curve shapes

Key result: assuming the observed price is a lower bound leads to an **upward drift in the price level** — a possible source of low-level [[inflation]]. This "irreducible" inflation would only matter when monetary inflation (quantity theory) is small.

The model recovers the modern AD-AS picture: a sharp right angle at the current price level. Below equilibrium output → sticky prices, idle resources. Above equilibrium → inflation without output gain.

## Money as bandwidth and other implications (May 20)

A rich post applying ITM thinking broadly:

- **Money ≈ bandwidth**: monetary aggregates are channel capacity for information transfer, not a moral quantity. Economic growth requires increasing the "bandwidth" (money supply) — necessary but not sufficient. See [[money-as-bandwidth]].
- **IS-LM as information transfer**: IS (demand) transfers information to LM (supply) via the interest rate. The [[zero-lower-bound]] represents failure of this information channel.
- **Diminishing marginal utility is emergent**: it's a property of the ensemble, not individual agents. Assigning it to individuals is like saying "an atom's pressure falls due to diminishing marginal utility of volume."
- **Say's Law is false** in the ITM: supply (information destination) cannot create demand (information source). The destination cannot create the information to be received.
- **[[money-illusion]]**: connected to the lower-bound assumption — if agents use the current price as a lower bound, they can't simultaneously expect inflation, because the future deflated price would become a new lower bound estimate.
- **New market channels** (like NGDP futures) start with poor information transfer — like switching from voice calls to early text messages. A whole language develops around established channels (e.g., Fed interest rate targeting).

## Inflation from rescaling (May 30)

A speculative model: if the "real" price is rescaled to stay at the lower bound, random fluctuations produce a **systematic upward drift** in the nominal price level (because downward fluctuations get cut off). This gives exponential growth in the price level — one possible source of low-level inflation.

Smith connects this to **renormalization** in physics: the price level has a rescaling freedom (adding zeros to a dollar bill shouldn't matter), analogous to how the electron charge scales with energy but has no absolute value predicted by theory. A macro theory should describe *dynamics* of the price level, not its absolute value.

## Economics as counting (May 30)

A brief insight: the ITM is fundamentally a **counting problem**. An individual's allocation of money to goods over time resembles an **integer partition** (Ferrers diagram). As the number of elements → ∞, the ensemble becomes tractable — suggesting statistical mechanics / information theory can capture the macro phenomena.

## Emerging picture (May 5)

Smith summarizes what the framework says so far:
- The "invisible hand" is information transfer dynamics — no micro-theory needed
- Anything with supply, demand, and a price-like detector fits the framework (IS-LM, AD-AS, individual goods)
- $I_{Q^d} \sim I_{Q^s}$ is the condition for "economics" to exist — market failure may be the boundary where this breaks down, analogous to nonequilibrium systems lacking well-defined temperature
- Supply *can* uncover demand (information that was being transmitted "into empty space" finds a destination), but cannot create it
