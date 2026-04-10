---
title: The Unobservables Problem
type: topic
tags: [unobservables, natural-rate, nairu, velocity, inflation-expectations, circularity]
sources:
  - raw/2015/09/the-unobservables.md
  - raw/2015/09/the-classical-mechanics-of-wicksell.md
created: 2026-04-08
last_updated: 2026-04-08
---

# The Unobservables Problem

Mainstream macroeconomics relies heavily on quantities that cannot be directly measured — and whose values are determined from the very data they're supposed to explain. The [[information-transfer-model]] replaces each of these circular constructs with calculable information-theoretic quantities.

## The phlogiston analogy

The standard framework works like this: "We get fire when temperature is above the natural temperature of phlogiston. How do we determine the natural temperature? We observe fire." This circularity pervades macro:

| Unobservable | Linked to | How "measured" | The circularity |
|---|---|---|---|
| Natural rate of interest | Interest rates too low → inflation | Observed inflation | Rate is "below natural" when you see inflation |
| NAIRU | Unemployment too low → wage-price spiral | Observed inflation | NAIRU = unemployment consistent with stable inflation |
| "Stance" of monetary policy | Expansionary → inflation | Observed NGDP growth | "Tight" money defined by lower future NGDP |
| Inflation expectations | Agents expect inflation → inflation | TIPS spreads / surveys | Expectations turn out to be backward-looking |
| Velocity of money | Money supply × velocity = spending | Observed spending | Velocity = residual (whatever makes MV = PY work) |

[[scott-sumner]]: "Tight money leads to lower expected future NGDP growth. I don't think that can be disputed." Smith: "It can't be disputed — because you define 'tight' money by lower future expected NGDP growth."

The only unobservable with even a theoretical measurement method — inflation expectations via TIPS spreads — turns out to be entirely backward-looking when inflation isn't high. So either expectations don't strongly affect inflation, or TIPS don't measure expectations correctly. Either way, the measurement is phlogiston.

## The ITM replacement

The ITM is the analog of the Schrödinger equation for these unobservables — it provides actual calculable values rather than circular definitions:

| Unobservable | ITM replacement |
|---|---|
| Natural rate of interest | [[information-equilibrium]] interest rate value from r:NGDP→MB |
| NAIRU | Calculated from labor supply [[information-transfer-index]] — see [[phillips-curve]] |
| "Tight" money | Interest rates above the information equilibrium value, or economy above the NGDP-M0 path |
| Inflation expectations | Unnecessary — price level follows from κ and M0 |
| Velocity | $\kappa P$ (or equivalently, the [[information-transfer-index]] determines it) |

The key distinction: the ITM's quantities are **calculable from observables** (NGDP, M0, MB) without referencing the inflation data they're supposed to predict. The wavefunction in quantum mechanics is also unobservable — but you don't determine it by measuring an interference pattern and taking its square root. There's a specific equation (Schrödinger) for calculating it. The ITM provides the economic analog.

The velocity case is illustrative. Mainstream cash-in-advance and cash-credit models can match the empirical *fluctuations* in velocity by tuning the relative weight on cash-vs-credit goods (the parameter α tracks the interest rate, which makes velocity track interest rates by construction). But matching fluctuations is not the same as having a model: the basic CIA model produces a velocity standard deviation of ~0.09% against an empirical 4.5%, off by a factor of fifty. Tuning gets you closer at the cost of "very high levels of risk aversion" and breaking other features of the data. The ITM matches both levels and rates with one parameter. The relationship $V = \kappa P$ — or equivalently $\log i = c \log(\text{NGDP}/\text{MZM}) + k$ — falls out of the [[information-equilibrium]] structure without any tuning.

## Implications

This critique cuts at the heart of mainstream monetary economics: if every major concept is defined circularly through the inflation it's supposed to explain, then the entire edifice is unfalsifiable. Falling estimates of the natural rate, falling velocity, and "tight since 2008" monetary policy are all symptoms of trying to make phlogiston theory work by adjusting the natural temperature.
