---
title: "ITM Explainer FAQ"
type: synthesis
tags: [explainer, faq, overview, information-equilibrium]
sources:
  - raw/2015/01/i-have-no-idea-what-you-are-talking.md
created: 2026-04-07
last_updated: 2026-04-07
---

# ITM Explainer FAQ (2015-01-16)

[Original post](../../raw/2015/01/i-have-no-idea-what-you-are-talking.md)

Smith's clearest Vox-style explainer of the entire framework, written because "the most common response from people with economics backgrounds is that they have no idea what I'm talking about."

## What is information transfer economics?

Based on [[fielitz-borchardt]]'s paper "Information transfer model of natural processes." They developed a generalized thermodynamics connecting physics to information theory. Smith derived [[supply-and-demand]] from their equations, assuming demand is an information source and supply is an information destination.

## What does it have to do with information theory?

The information theory mostly motivates a set of equations for an abstract **diffusion process**. Money is like time; output is like distance. The blog explores consequences of those equations. Occasionally the information theory provides insight — e.g., observed prices fall below a theoretical maximum because you can't extract more information than a signal contains.

## Isn't this just the quantity theory of money?

Pretty much. Instead of $MV = PY$, write:

$$P \sim \frac{1}{k} \frac{N}{M}$$

The big difference: $k$ changes **deterministically**, not as a free "velocity" parameter. The formula for $k$ comes from information theory — a ratio of Hartley information from two sets:

$$k = \frac{\log N/c_0}{\log M/c_0}$$

This is the [[information-transfer-index]] κ (inverted). It represents the **unit of account effect**: the units in which we measure everything in economics. The proper money aggregate M is determined empirically — it's **physical currency (M0)**, not M2 or the monetary base. See [[currency-vs-reserves]].

## How does it describe Japan so well?

$k$ tends to fall over time because M grows faster than NGDP. Eventually $k$ gets close to 1 and you get something that looks exactly like a liquidity trap — the [[information-trap]].

## What about inflation expectations?

Expectations might wiggle inflation around a bit, but the price level ultimately comes from $k$ and $M$. One interpretation: information flows from expected futures to realized present. But instead of a central bank setting expectations, the ITM takes the **average over all expectations consistent with macro conditions** — like thermodynamics taking the most likely pressure given volume and temperature. See [[information-equilibrium]].

## Where does it differ from thermodynamics?

The biggest difference: **there is no second law**. A fall in entropy is linked to recessions. Humans can coordinate (panic together) in a way atoms cannot. Most of the time humans are uncoordinated, but sometimes mass coordination causes a recession. See [[entropic-forces]].

## How deep is the thermodynamics connection?

Very deep. There may be a way to define an **economic temperature** (proportional to $1/\log M$). [[secular-stagnation]] and the [[information-trap]] may be emergent properties that don't exist for individual markets — no amount of individual market models will capture them.

## DSGE connection

In the log-linearized DSGE form, the different κ limits drop out simply:
- $\kappa = 1$: "liquidity trap" → inflation = constant
- $\kappa = 1/2$: "quantity theory" → inflation = money growth rate
