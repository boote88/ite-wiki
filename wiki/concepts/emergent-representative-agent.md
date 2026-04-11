---
title: Emergent Representative Agent
type: concept
tags: [representative-agent, emergence, maximum-entropy, budget-constraint, utility]
sources:
  - raw/2015/09/the-emergent-representative-agent-1.md
  - raw/2015/09/stuff-measured-by-gdp-and-emergent.md
  - raw/2015/08/obviously-e-coli-is-rational-utility.md
created: 2026-04-08
last_updated: 2026-04-08
---

# Emergent Representative Agent

The standard approach in economics assumes agents have well-behaved preferences (transitivity, monotonicity) that can be measured by a utility function, and then builds macro theory on this "representative agent." The [[information-transfer-model]] inverts this: the representative agent **emerges** from high-dimensional geometry and the principle of indifference, without assuming rationality, transitivity, or utility.

## The construction

Start with a basket of consumption goods $C_1, C_2, \ldots, C_d$ subject to a budget constraint $\sum C_i \leq M$. Assume every consumption state is equally likely (the principle of indifference — the same assumption underlying [[information-equilibrium]]).

In low dimensions ($d = 2, 3$), points are spread throughout the allowed region:

![Budget constraint in 2D and 3D](<../media/2015-09/money 3d xi 2.png>)

![3D budget constraint](<../media/2015-09/money 3d xi 3.png>)

But as $d \to \infty$, the distribution of points becomes **highly concentrated** near the budget constraint surface $\sum C_i = M$:

![Distribution concentrates at budget constraint in high dimensions](<../media/2015-09/itm utility distribution.png>)

For a large number of goods and/or time periods, the average (representative) point approximately **saturates the budget constraint** — the emergent agent spends all its money. Individual agents can vary from spending all to saving all, but the ensemble average behaves "rationally."

## What emerges without being assumed

- **Budget constraint saturation**: the representative agent spends all its money (from concentration of measure, not from monotonicity assumptions)
- **Transitive preferences**: the manifold of high-dimensional consumption states has structure compatible with a utility ordering — not because agents are rational, but because the geometry imposes it
- **Consumption smoothing**: in intertemporal consumption, the representative agent smooths — not from explicit optimization but from the centroid of the high-dimensional simplex being at equal consumption in each period
- **Downward-sloping demand**: follows from the same geometry that produces the Maxwell-Boltzmann distribution — more states available at lower prices

## Why it matters

The standard critique of the representative agent (Kirman, SMD theorem) says you can't aggregate heterogeneous agents into a single representative. The ITM agrees — but shows you don't need to. The representative agent isn't a simplification of micro behavior; it's an **emergent statistical property** of the ensemble, like temperature is an emergent property of molecular motion. Individual agents can have non-transitive, unstable, random preferences and the aggregate still behaves "as if" rational.

This explains why *E. coli* bacteria appear to maximize utility in microbial "markets" — without a brain. The "rational" behavior is a property of the state space geometry, not of cognition. Monkeys, bacteria, and random agents all produce demand curves because the math is the same — high-dimensional budget constraints plus maximum entropy.

A telling counterexample: in the Marwell-Ames public goods experiment, lay subjects divided tokens nearly equally between public and private accounts (the maximum entropy result), while *economics students* invested only 20% in the public fund. Training in economic reasoning produces **coordination** (groupthink) — a lower-entropy state. Since [[entropic-forces|economic entropy is roughly output]], the "economist economy" would perform worse than the lay-human economy. Behaving like a textbook utility maximizer is a deviation from what naturally-coordinating humans actually do.

Utility maximization doesn't explain markets; it merely saves the phenomena. The actual explanation is [[entropic-forces]].

## Cognitive biases as Ptolemaic epicycles

The Wikipedia list of cognitive biases is over 165 entries long and growing. Behavioral economics treats each one as an additional correction to the rational-agent baseline — much as pre-Copernican astronomy added epicycles to save the geocentric model. The proliferation is itself the diagnostic. There aren't 165 human biases; there are 165 deviations from the wrong model.

The right baseline isn't a rational agent; it's the maximum-entropy distribution over the opportunity set. When you measure deviations from *that* baseline, most "biases" disappear because they were never deviations from anything real. The endowment effect, money illusion, and several other staples of behavioral economics aren't irrational once you stop pretending the baseline is rational maximization.

The diffusion analogy makes the point cleanly. From a macroscopic view, gas diffusion looks like the "rational behavior" of a gas — atoms spread to fill their container. From the perspective of an individual atom, the random Brownian motion would look like a "cognitive bias" — why doesn't this atom head straight for the lowest-density region? The answer is that there is no force on the individual atom; the apparent rationalization is an entropic effect that exists only at the macro scale. In behavioral economics, the same thing is happening: there is no "rational agent" at the micro level for biases to deviate from. The rationality is emergent.

## Two limits of human complexity

The utility approach and information equilibrium represent two opposite limits:
- **Utility**: agents are simple enough to model — a function $u(x)$ captures their choices. A sequence of choices looks like {5, 5, 5, 5, 4, 6, 5, 5} — low algorithmic complexity
- **Information equilibrium**: agents are so complex they're algorithmically random — no computer program can reproduce their choices except a list of those choices. A sequence looks like {4, 7, 3, 4, 1, 6, 6, 5, 4, 2} — maximum algorithmic complexity

With millions of algorithmically random agents, the aggregate distribution is uniform across the opportunity set. Economics becomes about the **shape of the opportunity set** (measured by information theory), not about what's inside agents' heads.

![Random agents in 2D opportunity set produce demand curves](<../media/2020-02/beckerideal.gif>)

As prices change (budget constraint rotates), the average allocation shifts — producing a downward-sloping demand curve from pure randomness. Non-equilibrium occurs when agents "bunch up" — make correlated choices and don't fully map the opportunity set:

![Non-equilibrium: agents bunch up in the opportunity set](<../media/2020-02/beckernonideal.gif>)

This turns economics on its head: instead of figuring out what choices people will make, it's about **measuring the set of choices made by people**.
