---
title: "A simple example of information equilibrium"
type: source
tags: [information-equilibrium, pedagogy, supply-demand, gas-pump]
sources:
  - raw/2015/02/a-simple-example-of-information.md
created: 2026-04-07
last_updated: 2026-04-07
---

# A simple example of information equilibrium (2015-02-06)

[Original post](../../raw/2015/02/a-simple-example-of-information.md)

The clearest pedagogical introduction to [[information-equilibrium]]: a gas pump display.

## The gas pump analogy

Two quantities on a gas pump display are in information equilibrium: **total sale** (dollars) and **gallons pumped**.

- Squeeze the nozzle in a pattern (Morse code) → the signal in gallons is faithfully transferred to the total sale
- The price is constant and variables are linearly related — a trivial information transfer process
- For every tiny amount gallons go up, total sale goes up proportionally: the ratio = **price per gallon**

$$\text{(total sale)} = \text{(price per gallon)} \times \text{(gallons sold)}$$

$$D = p \times S$$

## Deriving supply and demand

- **Fix the total sale** (constant demand) → price goes down as gallons increase → **demand curve**
- **Fix the gallons** (constant supply) → price goes up as total sale increases → **supply curve**

Supply and demand follow directly from information equilibrium. No human behavior needed.

## Generalizing

The gas pump is the trivial case ($k = 1$, constant price). The general case:

$$D = k \frac{dD}{dS} \cdot S$$

which gives you any shape of supply and demand curves via the [[information-transfer-index]] $k$.

When $k \neq 1$, the derivative $dD/dS$ changes — the price changes. Map $D$ → NGDP, $S$ → currency (M), $p = dD/dS$ → price level. Adding money is like adding gas: NGDP goes up, but by a larger percentage than the money added (until the [[information-trap]]).

## The key insight

Information equilibrium is just a broadening of "equality":
- $A(t) = B(t)$ → two things are equal
- $A(t) = c \cdot B(t) + b$ → two things are proportional
- $\log A(t) = k \log B(t) + b$ → two things are in **information equilibrium**

If two quantities satisfy this log-linear relationship, a message encoded in $B(t)$ shows up faithfully in $A(t)$. If they don't, there's information loss ([[non-ideal-information-transfer]]).

This is "an incredibly useful tool to sort out some of the bullshit ad hoc theories out there!" — any economic model relating two quantities must satisfy this minimal condition, or it's wrong or incomplete.
