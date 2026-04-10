---
title: Entropic Forces in Economics
type: concept
tags: [entropy, thermodynamics, causality, wage-stickiness, recessions]
sources:
  - raw/2014/05/causality-in-information-transfer.md
  - raw/2014/08/rationality-and-entropic-forces.md
  - raw/2014/10/wage-stickiness-is-entropic-force.md
  - raw/2014/10/coordination-costs-money-causes-recessions.md
  - raw/2015/01/keynesian-economics-in-three-graphs.md
  - raw/2015/03/the-hot-potato-effect-is-entropic-force.md
  - raw/2015/03/nominal-rigidity-is-entropic-force.md
  - raw/2015/03/entropy-and-walrasian-auctioneer.md
  - raw/2015/03/supply-and-demand-as-entropy.md
  - raw/2015/04/diamond-dybvig-as-maximum-entropy-model.md
created: 2026-04-07
last_updated: 2026-04-07
---

# Entropic Forces in Economics

The [[information-transfer-model]] reframes macroeconomic phenomena as **entropic forces** — patterns driven by statistical mechanics rather than optimization or rational choice. This is arguably the ITM's deepest insight: the "forces" that economists attribute to incentives, expectations, and rational behavior are actually the same kind of forces that drive diffusion, osmosis, and pressure in physics.

"Utility maximizing agents? *I have no need of that hypothesis.*"

## The core idea

There is no "mechanical" causation in the ITM — only **statistical inevitability**. If a macrostate changes, the corresponding economic variables follow not because agents optimized, but because there are overwhelmingly more microstates consistent with the new equilibrium. A smell fills a house not because molecules "want" to spread out, but because there are vastly more configurations where they're spread out than where they're bunched up. Reverse causality is equally valid mathematically — the directionality comes from entropy, not mechanism.

Markets work the same way. Molecules in a gas don't know about density at the other side of the room, but collectively they achieve near-equal density. People and prices follow the same information equilibrium framework. The equilibrium price is an **emergent quantity** made from millions of individual price changes, none of which individually matter — just as pressure emerges from trillions of molecular collisions.

A refinement: **causal entropic forces** (Wissner-Gross and Freer, 2013) are entropic forces with a *causal* dimension — they don't immediately undo a state change, which gives them a restoring rather than purely random character. The math is the same maximum-entropy story but with a temporal asymmetry: states evolve toward the centroid of the opportunity set rather than randomly walking through it. This gives mindless particles behavior that looks intelligent — tool use and social cooperation can spontaneously emerge from causal entropic forces alone. In economics, this explains several things at once: why unemployment returns to a recovery slope rather than wandering, why the endowment effect looks like loss aversion (it's a reluctance to undo state changes), and why prices in repeated markets show monotonically declining variance over time (a feature that purely random transactions can't reproduce). The system isn't just "near the centroid on average" — causal entropy is actively pushing it there.

The framework is a tremendous blow to anyone who thinks rational utility-maximizing agents are a prerequisite for market behavior. Whatever economic puzzle you think requires rational agents, causal entropic forces are something you have to consider as an alternative.

## Where entropic forces appear

### Prices: sticky in aggregate, flexible individually

Empirical data from 60,000 observed prices reveals something that contradicts both mainstream micro explanations of [[sticky-prices]]: individual prices change frequently and freely, yet aggregate prices barely move. Menu costs predict infrequent individual changes; Calvo pricing predicts individual stickiness. Both are wrong. The reality is thermodynamic: thousands of prices fluctuate wildly, but the aggregate is stable — just as gas molecules bounce at high speed while average pressure stays constant. There is no microeconomic explanation of nominal rigidity; it is purely emergent.

### Wages: coordination entropy

Nominal wage cuts require **coordinated information loss** equivalent to unemployment. Cutting everyone's wages by 5% costs as much entropy as laying off 5%. The system prefers the higher-entropy state (some unemployed, rest at prior wage) over the lower-entropy state (everyone takes a coordinated cut). This derives wage stickiness without any appeal to menu costs, money illusion, or fairness norms. The full ITM treatment of the wage/employment split is at [[labor-market]].

### Recessions: spontaneous coordination

[[recessions]] result from **spontaneous human coordination** — the one thing humans can do that atoms cannot. Mass pessimism/panic temporarily correlates behavior, reducing the economy's entropy. Lower entropy → lower NGDP → idle resources. No external shock is needed; the coordination is its own cause. Recovery occurs when coordination breaks down and entropy rises again. A traffic jam forms from coordinated deceleration with no external cause, then dissolves when drivers stop coordinating. The fluctuation theorem from statistical physics provides quantitative bounds — large coordinated entropy decreases are exponentially rare for large systems, matching observed recession frequencies.

### Money injection: thermalization, not portfolio rebalancing

The monetarist "hot potato effect" — where injections of high-powered money cascade through the economy — is thermalization. The standard story says agents are "thrown off equilibrium" and "want to get rid" of excess money. The entropic view: additional money randomly moves through exchanges until the new most likely configuration is reached. Nobody wants anything; agents with above-average holdings just tend to reduce them through random exchanges, the way added energy opens up higher-momentum phase space and the system thermalizes to a new temperature.

### Supply and demand: entropy maximization

The forces driving supply and demand curves are entropic. After a shock (adding or removing supply/demand), the system returns to maximum entropy — the price adjusts because the new equilibrium has a different most-likely price, not because agents re-optimize. All four standard S&D shock cases (increase/decrease in supply/demand) can be visualized as animated entropy dynamics.

### Fiscal policy: government as a single large particle

Government spending works because government is a single large entity not subject to the entropic forces maintaining the distribution of market growth states. A fiscal expansion shifts the entire distribution's mean. Crowding out would require the rest of the economy to spontaneously coordinate toward lower growth — a spontaneous entropy decrease, which is thermodynamically absurd. The Keynesian multiplier is the rest of the economy re-thermalizing to the new average. Ricardian equivalence, in this picture, is "the silly argument that other molecules decide to get colder out of spite."

### Bank runs: budget constraint geometry

The Diamond-Dybvig bank run model works without game theory or strategic behavior. A bank's budget constraint creates an n-dimensional polytope of allowed consumption states. In high dimensions, nearly all points cluster near the surface (concentration of measure). A bank run occurs when forward-shifted consumption pushes the solution to the no-bank boundary. The mechanism is geometric and statistical, not behavioral.

### The Walrasian auctioneer: unnecessary

The theoretical construct ensuring no single agent affects prices in perfect competition is just entropy maximization in disguise. Walras' tâtonnement (iterative search for equilibrium) is entropy climbing to maximum. In the limit of many agents, no single one affects the outcome — the desired property of the auctioneer, achieved without one.

## Connection to the [[plucking-model]]

The information efficiency bound ($I_S = I_D$) is the maximum-entropy state. The [[plucking-model]] says RGDP is bounded from above by this ceiling, with recessions as downward "plucks" — temporary entropy reductions. The Great Moderation (1984–2007) represents the US economy operating near maximum entropy.

## The philosophical resolution

If humans have free will and don't behave perfectly rationally, why does economics math work so well when markets function? Because the same reason thermodynamics works: maximum entropy, not maximum utility. The agent-based model of economics is so complex it's indistinguishable from randomness — and that's exactly the regime where maximum entropy approaches shine.

"To turn Tolstoy upside down: *all functioning markets are alike; each market failure fails in its own way.*"

A speculative coda: perhaps humans evolved a **sense of fairness** because uniform distributions maximize entropy. In every behavioral game where game theory predicts extreme self-interest (dictator games, ultimatum games), people reliably choose closer-to-uniform outcomes — the maximum-entropy answer. If fairness is partly a built-in entropy preference, then markets work as well as they do because they're a "hack" of this sense: human institutions that channel entropy-seeking behavior into efficient resource allocation. When the entropy preference is overridden — by fashion, advertising, or coordinated panic — markets fail in exactly the ways the framework predicts.

A related observation: complex agent behavior is "random" in the algorithmic sense — the program required to produce a long string of transactions is nearly as long as the string itself. Complex behavior is, in the Kolmogorov sense, indistinguishable from randomness. This is what justifies treating complex agents as random for max-entropy purposes; you don't need agents to actually be random, only complex enough that their behavior has high algorithmic complexity. Complex agents, random agents, and rational agents all converge on the same macro behavior — which is why no test can tell them apart.
