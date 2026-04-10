---
title: Sticky Prices
type: topic
tags: [sticky-prices, non-ideal-transfer, macroeconomics, nominal-rigidity]
sources:
  - raw/2013/04/sticky-prices-from-non-ideal.md
  - raw/2013/04/are-thermodynamic-analogies-useful.md
  - raw/2013/05/sticky-prices.md
  - raw/2013/05/other-aspects-of-price-changes-under.md
  - raw/2015/03/nominal-rigidity-is-entropic-force.md
  - raw/2015/01/is-demand-curve-shaped-by-human.md
created: 2026-04-07
last_updated: 2026-04-07
---

# Sticky Prices

Sticky prices — prices that resist changing in response to shifts in supply or demand — are central to several schools of macroeconomic thought (notably New Keynesian economics). The [[information-transfer-model]] offers a fundamentally different explanation from the mainstream: prices are sticky **in aggregate but not individually**, and the stickiness is an [[entropic-forces|entropic force]] rather than a micro-level phenomenon.

## The ITM mechanism

When information transfer is imperfect ([[non-ideal-information-transfer]]), the ideal [[supply-and-demand]] curves become upper bounds rather than exact solutions (via Gronwall's inequality). This creates a region where the observed price can sit without violating the information transfer conditions. Small demand shifts don't move the price — it stays within the valid region. Large shifts push it to the boundary, where normal S&D behavior resumes. Prices tend to be stickier downward than upward, consistent with the observed price sitting near the lower bound of the information gap.

A Wiener process (random walk) model confirms this: individual price paths look like random walks, but averaging over many paths reveals stickiness. Prices are sticky **downward only** — upward demand shifts produce immediate responses. This recovers the standard macro picture (a sharp right-angle AS curve at the current price level) without needing micro-theories like menu costs, money illusion, or signaling. The analogy: "a pressure vessel with a broken pressure gauge — if the temperature drops, the equilibrium moves but the change may not register on the gauge."

## The empirical reality: micro flexibility, macro stickiness

Data from 60,000 observed prices delivers a verdict that contradicts both mainstream micro explanations:

- **Menu costs** predict infrequent individual price changes biased toward large jumps — **wrong**: individual prices change frequently
- **Calvo pricing** predicts that only a fraction of firms can adjust prices each period — **wrong**: nothing stops individual prices from changing

The reality is that individual prices fluctuate wildly and freely, yet the aggregate price level barely moves. This is exactly what [[entropic-forces]] predict: thousands of molecules bouncing at high speed while average pressure stays constant. **There is no microeconomic explanation of nominal rigidity** — it is a purely emergent macro phenomenon, flying in the face of the microfoundations approach to the Lucas critique.

The same is true for wages. The SF Fed's data shows the "zero bin" (workers with no wage change) goes from 12% to 16% during a recession — a 4 percentage point shift that many economists cite as evidence of micro-level wage stickiness causing recessions. But the quantitative math doesn't work: the difference in total aggregate wage change between these two distributions is about **$15 billion** (0.2% × $7 trillion). The US economy loses several *percent* of GDP in a recession — hundreds of billions — because the market can't unstick $15 billion? The micro effect is trivially small. The real mechanism is **macro stickiness**: the inability to coordinate a change in the whole distribution simultaneously, which is an [[entropic-forces|entropy cost]].

![Wage distribution: recession vs non-recession](<../media/2015-11/Screen Shot 2015-04-12 at 9.15.35 AM.png>)

![Aggregate paths from the two distributions — hard to tell apart even over 200 years](<../media/2015-11/sticky 1.png>)

## The demand curve itself is statistical

Classroom experiments supposedly demonstrating demand curves actually produce **inverse survival curves of normal distributions** — the same shape brainless atoms in an ideal gas produce via the Maxwell velocity distribution. If you asked atoms to "sit down" as velocities higher than theirs were called out, you'd get an identical "demand curve." The downward slope has nothing to do with utility, preferences, or diminishing marginal returns — it's a statistical property of ensembles.

## Connection to thermodynamics

If $\kappa \sim 1$, sticky prices may correspond to **isoentropic processes** in the [[thermodynamic-analogies]] — the market's entropy stays constant even as supply and demand shift. The [[economic-potentials]] framework places nominal rigidity squarely in the $TS$ (entropic) term of the economic potential — a macroeconomic force with no microeconomic counterpart.

## Wage stickiness

Wage stickiness arises because nominal wage cuts require **coordinated information loss** comparable to unemployment — the entropy cost of coordination exceeds the optimization benefit. Cutting everyone's wages by 5% costs as much entropy as laying off 5%. The system prefers the higher-entropy state (some unemployed, rest at prior wage). The full ITM treatment of the labor side, including the two-market structure (wage market vs employment market) and the Okun's law identity, is at [[labor-market]].
