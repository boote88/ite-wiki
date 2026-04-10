---
title: "Diamond-Dybvig as a maximum entropy model"
type: source
tags: [diamond-dybvig, bank-runs, maximum-entropy, financial-crisis, utility]
sources:
  - raw/2015/04/diamond-dybvig-as-maximum-entropy-model.md
created: 2026-04-07
last_updated: 2026-04-07
---

# Diamond-Dybvig as a maximum entropy model (2015-04-19)

[Original post](../../raw/2015/04/diamond-dybvig-as-maximum-entropy-model.md)

The Diamond-Dybvig bank run model — usually presented as a game theory problem — reinterpreted as a maximum entropy / [[information-equilibrium]] model. Bank runs emerge from the geometry of budget constraints in high-dimensional consumption space, not from strategic behavior.

## Setup

Utility is a Cobb-Douglas function derived from the ITM (information source = utility, destinations = consumption in each period, detectors = marginal utilities). The bank's budget constraint creates an n-dimensional polytope of allowed states.

### Timeline

![Diamond-Dybvig timeline](<../media/2015-04/itm diamond dybvig timeline.png>)

### Budget constraint polytope (3D example)

![Consumption polytope](<../media/2015-04/itm diamond dybvig polytope.png>)

### State density — nearly all points near the surface in high dimensions

![State density in 50D polytope](<../media/2015-04/itm diamond dybvig states.png>)

In high-dimensional space, nearly all points cluster near the surface — so the most likely state is just inside the center of that surface.

## The key diagram

![Diamond-Dybvig equilibrium diagram](<../media/2015-04/itm diamond dybvig.png>)

- **NB** (no bank): consumption in early period ≈ 1, no smoothing
- **B** (bank exists): maximum entropy solution where all consumption smoothing states are possible
- **E**: equal consumption every period (social optimum)
- Banks bring you closer to E than NB — higher utility

## Bank runs

When people move consumption forward in time, the solution can pass beyond the no-bank utility curve:

### No run

![No bank run](<../media/2015-04/itm diamond dybvig no run.png>)

### Run

![Bank run](<../media/2015-04/itm diamond dybvig run.png>)

In the maximum entropy version, utility curves are unnecessary — a run happens when early-period consumption equals the no-bank level.

### Simplified diagrams (without utility curves)

![Simplified no run](<../media/2015-04/itm diamond dybvig a.png>)
![Simplified transition](<../media/2015-04/itm diamond dybvig b.png>)
![Simplified run](<../media/2015-04/itm diamond dybvig c.png>)

## Key insight

The Diamond-Dybvig mechanism derives mostly from the **bank budget constraint**, not from strategic behavior or game theory. In any model where banks have a budget constraint $c_i + c_j/R \leq 1$, you can get bank runs. Deposit insurance works by alleviating the constraint. "No amount of bells and whistles can help you understand this basic message better."

The maximum entropy approach is **agnostic about how consumption is mediated** — it's valid across a wide array of banking models.
