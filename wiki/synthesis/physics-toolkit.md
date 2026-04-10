---
title: Physics and Mathematics Toolkit
type: synthesis
tags: [physics, mathematics, analogies, statistical-mechanics, information-theory]
created: 2026-04-07
last_updated: 2026-04-07
---

# Physics and Mathematics Toolkit

A running catalog of physics and mathematics concepts used in the ITM, organized by domain. Updated as new concepts appear during ingest.

## Information theory

| Concept | How it's used | First appears | Wiki page |
|---------|--------------|---------------|-----------|
| Shannon information / Hartley information | Foundation of the entire ITM: $I = K^s n$. Prices detect information flowing from demand (source) to supply (destination) | [Founding posts (2013-04)](../raw/2013/04/supply-and-demand-from-information.md) | [[information-transfer-model]] |
| Information transfer inequality | $I_S \leq I_D$ — information can only be lost, not gained. Produces sticky prices, recessions | [Founding posts (2013-04)](../raw/2013/04/supply-and-demand-from-information.md) | [[non-ideal-information-transfer]] |
| Channel capacity (Shannon-Hartley) | Money as bandwidth for economic information transfer. Growth requires increasing bandwidth (M0). Smith estimates ~200 Mbps theoretical capacity for a single price mechanism | [May 2013](../raw/2013/05/money-as-medium-of-information-exchange.md) | [[money-as-bandwidth]] |
| KL divergence | Wrong expectations → KL divergence → lower NGDP. Least informative prior (max ignorance) beats rational expectations on average | [2014 H1](../sources/2014-h1-theoretical-foundations.md) | [[information-equilibrium]] |
| Signal-to-noise ratio | Channel capacity depends on SNR; ~1% price fluctuations (20 dB) as baseline | [Apr 2015 primer](../raw/2015/04/information-theory-and-economics-primer.md) | [[money-as-bandwidth]] |
| Information bottleneck | Prices don't transmit info (Hayek wrong) — they destroy irrelevant info, preserving only state-space-relevant signal. Similar to GANs in deep learning. Market failure = bottleneck failure (private info gets amplified instead of destroyed) | [Oct 2017](../raw/2017/10/the-price-mechanism-and-information.md) | [[information-bottleneck]] |
| Self-similarity / ensemble averaging | Ensemble average of individual IE relationships has the same mathematical form as a single IE relationship: $\partial \langle A \rangle / \partial B = \langle k \rangle \langle A \rangle / B$. This is why AD-AS looks like micro S&D — mathematical self-similarity under partition function aggregation | [Jun 2017](../raw/2017/06/self-similarity-of-macro-and-micro.md) | [[information-equilibrium]], [[ad-as-model]] |

## Statistical mechanics & entropy

| Concept | How it's used | First appears | Wiki page |
|---------|--------------|---------------|-----------|
| Maximum entropy principle | Markets move toward max entropy (most likely macrostate), not utility optimization. IE assumes least informative prior consistent with data | [2013 H2](../sources/2013-h2-framework-maturation.md) | [[information-equilibrium]] |
| Entropic forces | Macro phenomena driven by statistical tendency toward most likely macrostate. Sticky prices, wage rigidity, recessions, money velocity — all entropic | [2014 H1](../sources/2014-h1-theoretical-foundations.md) | [[entropic-forces]] |
| Maxwell-Boltzmann distribution | Demand curve takes same shape as Maxwell velocity distribution — statistical, not behavioral. Classroom experiment produces inverse CDF of normal distribution | [Jan 2015](../raw/2015/01/is-demand-curve-shaped-by-human.md) | [[entropic-forces]] |
| Microstates vs macrostates | Individual prices (microstates) fluctuate wildly; aggregate price level (macrostate) is sticky. Like molecular velocities vs gas pressure | [Founding posts (2013-04)](../raw/2013/04/supply-and-demand-from-information.md) | [[sticky-prices]], [[microfoundations-critique]] |
| Boltzmann's approach | Don't need to know about atoms, just need ~10²³ of them. Macro doesn't need microfoundations, just "a lot" of S&D | [Founding posts (2013-04)](../raw/2013/04/supply-and-demand-from-information.md) | [[microfoundations-critique]] |
| Concentration of measure | In high-dimensional space, volume concentrates near polytope surface. Drives bank run analysis and [[emergent-representative-agent]] | [Apr 2015](../raw/2015/04/diamond-dybvig-as-maximum-entropy-model.md), [Sep 2015](../raw/2015/09/the-emergent-representative-agent-1.md) | [[entropic-forces]], [[emergent-representative-agent]] |
| MaxEnt vs game theory | Keynesian beauty contest: Nash predicts 0, MaxEnt predicts 33, actual 18-19 (MaxEnt closer). Dictator game: Nash predicts 99%, MaxEnt predicts 50%, actual ≈ 50%. MaxEnt consistently outperforms game-theoretic rationality | [Sep 2015](../raw/2015/09/maximum-entropy-better-than-game-theory.md), [Nov 2015](../raw/2015/11/maximum-entropy-better-than-game-theory.md) | [[information-equilibrium]] |
| Dissipative structures | Money as dissipative structure (like convection cells or life) existing to maximize entropy production. Loses value only at "heat death" — all resources equally allocated | [Jul 2015](../raw/2015/07/resolving-paradox-of-fiat-money.md) | [[fiat-money-paradox]] |
| Fluctuation theorem | Recessions violate the "second law of econo-dynamics" — human coordination reduces entropy. But violations are exponentially unlikely for large systems, matching observed recession distribution | [Nov 2015](../raw/2015/11/internal-devaluation-and-fluctuation.md) | [[entropic-forces]], [[plucking-model]] |
| Universality classes (phase transitions) | Near phase transitions, very different micro models look identical (Ising, percolation). One source of emergence: details don't matter near critical points | [Apr 2016](../raw/2016/04/different-types-of-emergence.md) | [[microfoundations-critique]] |
| Universality classes (probability) | Central limit theorem: complex agents produce normal distributions regardless of underlying micro distribution. Another source of emergence | [Apr 2016](../raw/2016/04/different-types-of-emergence.md) | [[emergent-representative-agent]] |

## Thermodynamics

| Concept | How it's used | First appears | Wiki page |
|---------|--------------|---------------|-----------|
| Ideal gas law mapping | P↔pressure, Qᵈ↔energy, Qˢ↔volume. The S&D relation maps to pV = nRT | [Founding posts (2013-04)](../raw/2013/04/information-transfer-economics.md) | [[thermodynamic-analogies]] |
| Isothermal / isoentropic processes | Movement along demand curve ↔ isothermal process. Sticky prices may be isoentropic | [Founding posts (2013-04)](../raw/2013/04/information-transfer-economics.md) | [[thermodynamic-analogies]] |
| Thermodynamic potentials | $dN = T\,dS + p\,dX + \sum_i p_i\,dx_i + P\,dM$ — separates macro (entropic), micro (individual markets), and monetary forces | [Apr 2015](../raw/2015/04/economic-potentials-or-how-to-define.md) | [[economic-potentials]] |
| Economic temperature | $T \sim 1/\kappa$. High κ = cold (information trap). Low κ = hot (QTM regime) | [Apr 2015](../raw/2015/04/economic-potentials-or-how-to-define.md) | [[economic-potentials]] |
| Thermalization | Money injection thermalizes through exchanges until new average is reached. Hot potato effect is thermalization | [Mar 2015](../raw/2015/03/the-hot-potato-effect-is-entropic-force.md) | [[entropic-forces]] |
| Phase transitions | US economy underwent transition around WWII. Structural transition at ~7% MB growth. Liquidity trap as κ-driven regime change | [2013 H2](../sources/2013-h2-framework-maturation.md) | [[information-trap]] |
| Crowding out as entropy decrease | Fiscal expansion can't be offset by spontaneous coordination — that would require entropy decrease, which is thermodynamically absurd | [Jan 2015](../raw/2015/01/keynesian-economics-in-three-graphs.md) | [[fiscal-policy]], [[entropic-forces]] |
| Fermi surface | When everyone in a class owns the same product (all college students with Macbooks), the action happens at the boundary — only marginal decisions carry information. A filled "Fermi sphere" of consumption stops being a market signal | [Mar 2016](../raw/2016/03/coordination-and-complexity.md) | [[entropic-forces]] |
| Algorithmic randomness | Complex agent behavior is "random" in the Kolmogorov sense — the program required to produce the transaction string is nearly as long as the string itself. This justifies treating complex agents as random for max-entropy purposes | [Mar 2016](../raw/2016/03/coordination-and-complexity.md) | [[entropic-forces]], [[emergent-representative-agent]] |

## Stochastic processes

| Concept | How it's used | First appears | Wiki page |
|---------|--------------|---------------|-----------|
| Wiener process / Brownian motion | Sticky price dynamics as random walk with broken pressure gauge. Individual prices are Brownian; averaging reveals emergent stickiness | [May 2013](../raw/2013/05/how-money-transfers-information-part-3.md) | [[sticky-prices]] |
| Gronwall's inequality | Non-ideal information transfer curves become upper bounds on observed prices. From ODE/stochastic theory | [Founding posts (2013-04)](../raw/2013/04/supply-and-demand-from-information.md) | [[non-ideal-information-transfer]] |
| Diffusion length / random walk PPF | Production possibilities frontier emerges as the level curve of average random-walk endpoints — diffusion length $D \sim \sqrt{N}$. Bowed-out PPFs are the *default* without invoking opportunity cost | [Feb 2016](../raw/2016/02/production-possibilities-and-brownian.md) | [[supply-and-demand]] |
| PPAD-completeness / Brouwer fixed points | Computing Nash and Arrow-Debreu equilibria is intractable (PPAD-complete). Markets cannot be computing these even approximately — they must be doing something simpler, like settling into the maximum entropy state | [Feb 2016](../raw/2016/02/computing-nash-equilibria-is-intractable.md) | [[information-equilibrium]] |
| Lyapunov exponents | The IT index κ is mathematically the Lyapunov exponent of the information equilibrium system: $\lambda = 1/(k A_0)$. Positive λ (typical in economics) means the system is chaotic in the technical sense. Hyperinflation under pegged rates is the maximum-chaos limit | [May 2016](../raw/2016/05/lyapunov-exponents-and-information.md) | [[information-transfer-index]], [[information-trap]] |

## Abstract algebra

| Concept | How it's used | First appears | Wiki page |
|---------|--------------|---------------|-----------|
| Equivalence relation | IE satisfies reflexivity ($k=1$), symmetry ($k'=1/k$), transitivity ($k=ab$ via chain rule). Ensures consistency across markets | [Mar 2015](../raw/2015/03/information-equilibrium-is-equivalence.md) | [[information-equilibrium]] |
| Group under multiplication | IE closed under multiplication ($A \rightleftarrows K, B \rightleftarrows K \Rightarrow AB \rightleftarrows K$) but NOT under addition. Resolves Cambridge capital controversy: can't add heterogeneous capital, but geometric means (Cobb-Douglas) work | [May 2015](../raw/2015/05/resolving-cambridge-capital-controvery.md) | [[solow-growth-model]] |

## Symmetries & conservation laws

| Concept | How it's used | First appears | Wiki page |
|---------|--------------|---------------|-----------|
| Noether's theorem | Money is the conserved quantity of homogeneity of degree zero (scale invariance), just as energy is conserved from time-translation symmetry | [Dec 2015](../raw/2015/12/money-is-that-which-is-conserved-via.md) | [[fiat-money-paradox]] |
| Homogeneity of degree zero | The fundamental symmetry: doubling S and D doesn't change P. From this flows the basic ITM equation and the definition of money | [Founding posts](../raw/2013/04/supply-and-demand-from-information.md), [Dec 2015](../raw/2015/12/money-is-that-which-is-conserved-via.md) | [[information-transfer-model]], [[fiat-money-paradox]] |
| Walras' law as conservation law | Aggregate budget balance ~ conservation of "economic charge". One of few properties inherited from micro to macro (per SMD theorem) | [Sep 2013](../raw/2013/09/walras-law.md), [Oct 2015](../raw/2015/10/the-smd-theorem-and-oh-no-not-another.md) | [[information-equilibrium]], [[microfoundations-critique]] |

## Scaling & renormalization

| Concept | How it's used | First appears | Wiki page |
|---------|--------------|---------------|-----------|
| Renormalization group | Price level has rescaling freedom (adding zeros to currency), like electron charge scaling with energy in QED. Macro theory describes dynamics, not absolute values | [May 2013](../raw/2013/05/how-money-transfers-information-part-3.md) | [[information-transfer-model]] |
| Effective field theory | Higher-order terms suppressed by factors of MB size. SMD theorem = macro inherits only conservation laws and symmetries from micro (exactly EFT). κ is like $F_\pi$ — a macro parameter that doesn't exist for individual agents | [2014 H2](../sources/2014-h2-entropy-and-universality.md), [Oct 2015](../raw/2015/10/the-smd-theorem-and-oh-no-not-another.md) | [[information-transfer-model]], [[microfoundations-critique]] |
| Chiral perturbation theory analogy | QCD→hadrons as microeconomics→macro aggregates. Representative agent = representative quark (nonsensical). Microfoundations = demanding lattice QCD for every ChPT result | [Oct 2015](../raw/2015/10/the-smd-theorem-and-oh-no-not-another.md) | [[microfoundations-critique]] |
| Gibbs paradox / Stirling's approximation | Entropy scales as $\log N! \approx N\log N - N$. Economy at ~10⁶ agents shows increasing returns; only approaches constant returns at ~10²³. Explains why Solow's constant-returns assumption breaks | [2014 H2](../sources/2014-h2-entropy-and-universality.md) | [[solow-growth-model]] |

## Combinatorics & geometry

| Concept | How it's used | First appears | Wiki page |
|---------|--------------|---------------|-----------|
| Integer partitions / Ferrers diagrams | Individual's allocation of money to goods resembles integer partition. As N → ∞, ensemble becomes tractable for statistical treatment | [May 2013](../raw/2013/05/how-money-transfers-information-part-3.md) | [[information-transfer-model]] |
| Budget constraint polytope | Bank's budget constraint creates n-dimensional polytope. Bank runs occur when forward-shifted consumption crosses the no-bank boundary | [Apr 2015](../raw/2015/04/diamond-dybvig-as-maximum-entropy-model.md) | [[entropic-forces]] |
