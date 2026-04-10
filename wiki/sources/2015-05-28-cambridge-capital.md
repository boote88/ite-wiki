---
title: "Resolving the Cambridge capital controversy with abstract algebra"
type: source
tags: [cambridge-capital-controversy, abstract-algebra, group-theory, capital, solow]
sources:
  - raw/2015/05/resolving-cambridge-capital-controvery.md
created: 2026-04-07
last_updated: 2026-04-07
---

# Resolving the Cambridge capital controversy with abstract algebra (2015-05-28)

[Original post](../../raw/2015/05/resolving-cambridge-capital-controvery.md)

The famous Cambridge capital controversy (Cambridge MA vs Cambridge UK on whether you can aggregate different capital goods) resolved via [[information-equilibrium]] and abstract algebra.

## The result

IE is a **group** under multiplication but **not a ring** (not closed under addition):

- If $A \rightleftarrows K$ and $B \rightleftarrows K$, then $AB \rightleftarrows K$ (product is in IE with K)
- But $A + B$ is NOT in IE with K (unless A and B are the same thing)

This is exactly **Joan Robinson's point**: you can't just add up different capital goods. Cambridge UK wins.

## Sensible definitions of capital

Two alternatives that work within the IE framework:

1. **Geometric mean**: if $A, B, C, ...$ are all in IE with $K$, then $A^a \cdot B^b \cdot C^c \cdots \rightleftarrows K$ — a Cobb-Douglas aggregate. This is why Cobb-Douglas production functions work empirically.

2. **Money-denominated capital**: measure everything in dollars. But then relative prices of capital goods matter — introducing the complications Robinson warned about.

## Significance

This connects the [[information-equilibrium]] framework's mathematical structure (equivalence relation + group under multiplication) to one of the most contentious debates in the history of economics. The answer falls out of the algebra: addition is the wrong operation for aggregating capital.

Updates [[solow-growth-model]] — the ITM's Cobb-Douglas form with α+β≠1 is the natural result of using geometric means (the algebraically correct aggregation) rather than addition.
