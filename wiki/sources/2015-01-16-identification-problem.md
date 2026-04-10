---
title: "Solving the identification problem via information equilibrium"
type: source
tags: [identification-problem, information-equilibrium, kappa, econometrics, price-level]
sources:
  - raw/2015/01/solving-identification-problem-via.md
created: 2026-04-07
last_updated: 2026-04-07
---

# Solving the identification problem via information equilibrium (2015-01-16)

[Original post](../../raw/2015/01/solving-identification-problem-via.md)

A major theoretical contribution: the [[information-equilibrium]] framework solves the **identification problem** — the classic econometric challenge that a series of price-quantity observations can't uniquely determine both supply and demand elasticities.

## The identification problem

In its simplest form: you observe a series of prices P and quantities Q, but can't tell whether you're seeing moves along supply curves, demand curves, or both. You can't get two slopes from two variables.

## ITM solution

In the information equilibrium model:

$$P = \frac{1}{\kappa} \frac{D}{S}$$

Both supply and demand elasticities follow from a **single parameter** κ. This means:
- If data represents movement of both curves → price measurements constrain the 3D surface curvature
- If data represents movement of just one curve → you're fitting a reduced form (supply or demand curve)
- The identification problem *helps* you because diverse price movements constrain κ better

### The 3D price level surface P(NGDP, M0)

![3D price level surface](<../media/2015-01/basic us price level m0 1.png>)

## The changing κ problem

In monetary economics κ changes over time, which might reintroduce the identification problem. But κ has a specific information-theoretic meaning — it measures relative information unit sizes:

$$\kappa = \frac{\log(N/c_0)}{\log(M/c_0)}$$

This constrains κ to a specific functional form rather than being a free function. It allows the model to behave like the [[quantity-theory-of-money]] when κ ~ 1/2, and like IS-LM / [[information-trap]] when κ ~ 1.

## Which monetary aggregate?

The model solves this empirically: use whichever fits inflation best. The answer is the simplest: **currency in circulation (M0)**. Not M2, MZM, or the full monetary base. See [[currency-vs-reserves]].

### Model fit comparison across aggregates

![Aggregate comparison](<../media/2015-01/basic us model m0 fit parameter tests.png>)

### US and Japan price level model fits

![US inflation fit (smoothed PCE)](<../media/2015-01/inflation smoothed pce -1-.png>)

![Japan price level fit](<../media/2015-01/japan price level -simple-.png>)

## Significance

This post synthesizes several threads: the [[information-transfer-index]] κ simultaneously solves the identification problem, determines when different economic schools apply (QTM vs. IS-LM), and selects the correct monetary aggregate — all from one parameter with an information-theoretic interpretation.
