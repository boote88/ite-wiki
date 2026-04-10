---
title: Non-Ideal Information Transfer
type: concept
tags: [core-framework, information-loss, gronwall-inequality, entropy, recessions]
sources:
  - raw/2013/04/sticky-prices-from-non-ideal.md
  - raw/2014/03/modeling-macroeconomic-fluctuations.md
  - raw/2014/10/wage-stickiness-is-entropic-force.md
  - raw/2015/03/non-ideal-information-transfer-tail.md
  - raw/2015/10/info-eq-101.md
created: 2026-04-07
last_updated: 2026-04-09
---

# Non-Ideal Information Transfer

In the [[information-transfer-model]], information equilibrium is the special case where all the information from a source reaches its destination ($I_S = I_D$). The general case is **non-ideal information transfer**: $I_S < I_D$. Information can be lost but never gained, and this asymmetry is the engine behind nearly every "imperfection" in macroeconomics — sticky prices, recessions, market failures, the [[information-trap]] itself.

It's no exaggeration to say that ideal information transfer describes the exception and non-ideal describes the rule. The whole field of macroeconomics could be reframed as the study of the gap between $I_S$ and $I_D$.

## The inequality formalism

In information equilibrium, the basic ITM differential equation is

$$P = \frac{1}{\kappa} \frac{D}{S}$$

When transfer is non-ideal, the equality becomes an inequality:

$$P \leq \frac{1}{\kappa} \frac{D}{S}$$

Via **Gronwall's inequality** (from the theory of differential inequalities), the ideal solutions to the ITM equation become **upper bounds** on the non-ideal trajectories. The ideal [[supply-and-demand]] curves no longer trace out the observed price — they bound a region below themselves where the observed price is allowed to live.

## The orange triangle

The simplest way to visualize this comes from the chalkboard derivation in [[2015-10-24-info-eq-101]]: the three solution branches of the ITM equation (general equilibrium plus the two partial equilibrium curves) bound a triangular region. Under ideal information transfer, the price sits exactly on the curves; under non-ideal transfer, it can sit anywhere inside the orange triangle.

![The orange triangle: non-ideal price can sit anywhere inside the bound](<../media/2015-10/3c8bf976-bd39-4e1e-85e8-c35cb725fd0f.jpg>)

A typical price trajectory looks like normal growth (close to the bound) punctuated by both bouts of more serious non-ideal transfer (recessions — the price drops away from the boundary) and brief shocks where supply or demand jumps suddenly. The wider the gap between the price and the bound, the further from information equilibrium the system is.

## Information loss as entropy decrease

In the [[entropic-forces]] view, $I_S < I_D$ corresponds directly to a **decrease in economic entropy**. The system is occupying fewer microstates than it could — agents have coordinated, distributions have narrowed, and the macroeconomic state has become less probable than the maximum entropy state. In molecular terms: the gas has somehow gotten cooler than it should be.

This is why [[sticky-prices]] are an entropic force, why recessions involve coordination failure, and why wage rigidity emerges in the aggregate even though individual prices are flexible. All of these are different facets of the same underlying phenomenon: the information transferred from demand to supply is less than the information demand was sending.

## Where it shows up

Non-ideal information transfer is the mechanism behind a wide range of macro phenomena:

- **[[sticky-prices]]**: prices sit below the ideal curve in the allowed region. Small demand shifts don't move the price (it stays inside the bound); only large shifts force it to the boundary, where normal S&D behavior resumes. Stickiness is most pronounced downward — the observed price tends to sit near the lower bound.
- **The labor market**: see [[labor-market]]. Employment quantity adjusts where wages would be expected to, because the wage market is more deeply non-ideal than the employment market. Macro-level wage rigidity is a coordination failure, not a micro property.
- **[[recessions]]**: spikes in non-ideal information transfer, where the price (or output) departs from the bound by a large amount. The "plucks" of the [[plucking-model]] are exactly these departures.
- **[[information-trap]]**: a structural form where the bound itself is flat ($\partial P / \partial \text{MB} \approx 0$), making monetary policy ineffective regardless of how much information you try to push through.
- **[[nominal-shocks]]**: extracted by measuring the gap between actual NGDP and the M0-predicted ideal path — i.e., the magnitude of the non-ideal information transfer at any given time.
- **Asset bubbles**: defined precisely as a surge in demand that outpaces supply, followed by non-ideal information transfer (panic, coordinated selling). This distinguishes a "bubble" from a normal price surge. A surge that decays back to equilibrium gradually isn't a bubble; only one followed by panic-driven non-ideal collapse counts. The 1987 crash and other "bubble" episodes match the pattern, while non-bubbly demand surges (e.g., 10-year Treasury rate movements) don't show the post-peak coordination collapse.

## Causes of the information gap

Why doesn't all the demand information reach supply? Smith identifies several potential mechanisms:

- **Complexity of the goods**: difficult to assess accurately (many variables), so the price signal is noisy
- **Infrequent assessment**: markets assessed only periodically, so information arrives in chunks
- **Coordination/panic**: the most consequential cause. Humans can spontaneously coordinate (mass pessimism), correlating their behavior in a way that reduces the entropy of the macroeconomic state. This is the [[entropic-forces|entropic origin of recessions]].
- **Structural mismatch**: in employment markets, wages are reviewed annually rather than continuously, salaries don't reflect productivity changes, etc.

## Tail behavior

Most of the time, non-ideal information transfer is small — the price sits close to the bound and the framework reduces to ideal information equilibrium. But the **tail** of large deviations is where the action is. Recessions, financial crises, structural breaks all live in this tail. The fluctuation theorem from statistical physics provides a quantitative bound: large violations of the "second law of econo-dynamics" (entropy spontaneously decreasing) become exponentially less probable as the system grows. This matches the observed distribution of recessions: rare but real.

## Open questions

- The sticky trajectory is *consistent with* the equations but not *required by* them — like a pencil that *can* fall west but needn't. What additional constraints determine the actual trajectory?
- Does the information gap shrink over time as markets become more efficient, or does it remain constant? Cross-country comparisons suggest the latter.
- Markov information sources might further constrain the dynamics, but the connection hasn't been fully worked out.
