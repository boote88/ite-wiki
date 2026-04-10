---
title: Minimum Wage
type: topic
tags: [minimum-wage, labor-market, supply-demand, econ-101, scope-conditions]
sources:
  - raw/2014/06/seattles-new-minimum-wage-and.md
  - raw/2015/07/implicit-models-minimum-wage-and.md
  - raw/2015/10/we-built-this-theory-on-scope-conditions.md
  - raw/2015/11/the-minimum-wage-in-info-econ-101.md
created: 2026-04-09
last_updated: 2026-04-09
---

# Minimum Wage

The Econ 101 textbook story about minimum wage is simple: set a wage floor above the equilibrium price, and the quantity of labor demanded falls below the quantity supplied. Result: unemployment. The [[information-transfer-model]] gives a different answer that turns out to match the data better — and the disagreement reveals something important about how supply-and-demand diagrams are usually misused.

## The Econ 101 picture

The standard textbook treatment uses a supply-demand diagram with the minimum wage drawn as a horizontal line above the equilibrium price $P^*$. The new "equilibrium" is taken to be the intersection of the demand curve and the minimum wage line, with the gap between this intersection and the supply curve interpreted as unemployment.

![Standard Econ 101 minimum wage diagram](<../media/2015-11/demand curve min wage 2.png>)

This involves several unstated assumptions. *Why the demand-curve intersection?* This implicitly assumes employers are at their hiring limit, rather than (say) workers leaving the labor force because a low-wage job isn't worth pursuing. *What do the curves below the minimum even mean?* They represent illegal supply and demand for labor at sub-minimum wages — the desire to employ people for less than legal. Smith's analogy: "I'd really like to drive over the speed limit, but that piece of the solution space doesn't enter into my speed decisions, which are based on traffic and road conditions."

The Econ 101 picture is also empirically wrong — the data doesn't show the unemployment effects it predicts (a long-running and well-documented finding in labor economics).

## The Info Econ 101 picture

Starting from the same information equilibrium framework that derives [[supply-and-demand]] in the first place, you can introduce a finite minimum wage as a constant shift in the labor-price equation. Solve the differential equation again. The result:

![ITM minimum wage analysis](<../media/2014-06/itm min wage 1.png>)

The original information-equilibrium solution (which assumes a minimum wage of zero) is no longer a valid solution when a finite minimum wage applies. The intersection point of the original demand curve with the minimum wage line is **not a meaningful point** — that curve was the solution to a different equation. What the framework actually predicts is that **both supply and demand go up** under a minimum wage increase (in the simplified ITM picture). The number of jobs doesn't necessarily fall.

![Info Econ 101 minimum wage diagram](<../media/2015-11/demand curve min wage.png>)

The contrast:
- **Econ 101**: simple but inconsistent with data
- **Info Econ 101**: simple and consistent with data

## Scale invariance and the deeper point

The cleanest way to see why the Econ 101 view is wrong: a number $p > 7.5$ and a number $p > 15$ carry the same amount of information. Inside the market itself, there's no difference between them. Just as moving the decimal place on all prices (a scale factor) has no impact on the economy — the [[fiat-money-paradox|homogeneity of degree zero]] symmetry — shifting all minimum-wage workers' hourly wages by a constant has no impact *on its own*. The impact lies entirely in the **interaction** of the labor market with the markets for goods and services.

This is exactly what the information-equilibrium analysis captures. In the simplified one-market picture, the minimum wage doesn't do much. In a coupled multi-market analysis, the effects flow through the connections between markets — and these are not the effects the Econ 101 diagram predicts.

## The same pattern in housing markets

Minimum wage isn't the only place where the Econ 101 partial-equilibrium intuition fails for the same reason. Housing markets follow the same pattern: build more housing in a city and the textbook story says prices should fall. Empirically and in the general-equilibrium ITM picture, this doesn't happen because the timescales for supply and demand to adjust are comparable. A rising housing stock attracts more residents, which increases demand at almost the same rate it increases supply. The system stays in general equilibrium and prices barely respond. This isn't a refutation of "supply matters" but a refutation of the partial-equilibrium reasoning that ignores how fast demand responds to changes in the supply side. The same applies to minimum wage: increasing pay raises spending, which raises demand for the things minimum-wage workers produce, which feeds back into employment. The single-market diagram never captures any of this.

## Scope conditions matter

A broader theme in the ITM: every economic model has scope conditions, and the Econ 101 minimum wage diagram silently assumes its scope conditions hold. They often don't. The supply-and-demand diagram is a partial-equilibrium tool that assumes everything outside the labor market stays constant. But changing minimum wages changes incomes, which changes spending, which changes demand for the goods that minimum-wage workers help produce, which feeds back to the labor market. None of this is captured in the textbook picture.

The ITM's framing makes the scope conditions explicit: information equilibrium is a relationship between two specific quantities, and you can't apply it outside its domain without checking that the assumptions still hold. This is the same critique Smith levels at "Econ 101" reasoning more broadly — see [[microfoundations-critique]] for the parallel argument about how textbook intuitions hide implicit model assumptions.

## Connection to the labor market

The minimum wage analysis sits naturally inside the broader [[labor-market]] picture in the ITM. The two-market structure (wage market and employment market with different κ) means quantity adjustments dominate price adjustments — employment changes are how the labor market responds to shocks, not wage changes. This gives a deeper reason why minimum wage increases need not cause large employment effects: the labor market's price ($P_1 \approx 2.1$) is *already* approximately invariant. Forcing an increase in *some* wages doesn't break the structural relationship between NGDP and total nominal wages, so the system can absorb the change without throwing many people out of work.

This is consistent with the broader observation in the ITM: most of what mainstream macro attributes to wage rigidity is actually macro coordination behavior, not micro-level price stickiness. The data on minimum wage is one more piece of evidence pointing the same direction.
