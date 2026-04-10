---
title: Information Transfer Model
type: concept
tags: [core-framework, information-theory, shannon, hartley]
sources:
  - raw/2013/04/an-informal-abstract.md
  - raw/2013/04/the-information-transfer-model.md
  - raw/2013/04/the-previous-post-with-more-words-and.md
created: 2026-04-07
last_updated: 2026-04-07
---

# Information Transfer Model (ITM)

The **Information Transfer Model** is the core framework of the blog. It applies Shannon information theory to economic processes, modeling prices as signals that transfer information from demand (source) to supply (destination).

## Origin

The ITM adapts a framework developed by [[fielitz-borchardt]] in their paper ["Information transfer model of natural processes"](http://arxiv.org/abs/0905.0610v2) (2009). Fielitz and Borchardt used information theory to derive known physical laws (ideal gas law, Fick's law, Hubble's law) without needing to choose specific constraints — a key advantage over standard maximum entropy approaches. Smith's insight was that this same framework could derive supply and demand in economics.

## Formalism

Following Shannon, we have a system transferring information $I_q$ from a source $q$ to a destination $u$. Information can only be lost, not gained:

$$I_u \leq I_q$$

Using the **Hartley definition** of information ($I = K^s n$, where $K^s = K^0 \log s$ and $s$ is the number of symbols), and defining the **information transfer index** $\kappa = K_u^s / K_q^s$:

$$\kappa \frac{u}{\delta u} \leq \frac{q}{\delta q}$$

The **price** is the process signal detector:

$$p = \left(\frac{\delta q}{\delta u}\right)_{\text{detector}}$$

In the continuum limit ($n_q, n_u \gg 1$, so $\delta q \to dq$):

$$p = \frac{dq}{du} \leq \frac{1}{\kappa} \frac{q}{u}$$

## Economic interpretation

| ITM concept | Economic meaning |
|---|---|
| Process source $q$ | Demand $Q^d$ |
| Process destination $u$ | Supply $Q^s$ |
| Process signal detector $p$ | Price $P$ |
| Information transfer index $\kappa$ | Market parameter (measurable from price elasticities) |
| Ideal transfer ($I_u = I_q$) | Perfect information, [[supply-and-demand]] equilibrium |
| Non-ideal transfer ($I_u < I_q$) | Information loss, [[sticky-prices]], [[non-ideal-information-transfer]] |

## Thermodynamic parallel

The ITM maps directly onto ideal gas thermodynamics:

| Economics | Thermodynamics |
|---|---|
| Price | Pressure |
| Demand | Work / Energy |
| Supply | Volume |

The price-supply-demand equation is analogous to the ideal gas law. See [[thermodynamic-analogies]].

## Key properties

- **Movement of** S&D curves: $Q^d$ is a "floating" information source
- **Movement along** S&D curves: $Q^d = Q_0^d$ is a "constant" information source
- The information transfer index $\kappa$ can be measured from price elasticities of supply and demand
- Linearization around equilibrium recovers the standard textbook model ($Q^d = \alpha - \beta P$, etc.)

## Condition for applicability

From Fielitz and Borchardt: the economic process must be sufficiently described by only two independent process variables (supply and demand) and must be able to transfer information.

## References

- [An informal abstract (2013-04-24)](../../raw/2013/04/an-informal-abstract.md)
- [The information transfer model (2013-04-24)](../../raw/2013/04/the-information-transfer-model.md)
- [The previous post with more words (2013-04-25)](../../raw/2013/04/the-previous-post-with-more-words-and.md)
- Fielitz & Borchardt, [arXiv:0905.0610](http://arxiv.org/abs/0905.0610v2)
