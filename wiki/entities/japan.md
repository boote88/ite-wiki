---
title: Japan
type: entity
tags: [japan, information-trap, deflation, abenomics, boj]
sources:
  - raw/2013/09/the-mystery-of-japanese-monetary-base.md
  - raw/2013/09/japan-interest-rates-and-liquidity-trap.md
  - raw/2013/09/modeling-interest-rates-in-japan.md
  - raw/2014/09/update-on-japanese-inflation.md
  - raw/2014/12/japans-new-recession.md
  - raw/2015/01/updates-for-japan-and-major-correction.md
created: 2026-04-09
last_updated: 2026-04-09
---

# Japan

Japan is the canonical [[information-trap]] case in the [[information-transfer-model]] — the country that crossed the κ ≈ 1 ridge first, around 2000, and has spent the subsequent decades demonstrating in real time what happens when a developed economy enters the high-κ regime. Anything the ITM has to say about Eurozone deflation, US "secular stagnation," or the long-run failure of monetary targeting can be checked against Japan, which has been running the experiment longer than anyone else.

## The mystery the ITM resolves

The puzzle Japan presents to mainstream macroeconomics: the Bank of Japan expanded the monetary base by roughly 3.5x over the 1990s and 2000s, yet inflation stayed near zero (and often went negative). The CPI tangents at different points in the data are nearly horizontal — sometimes negatively sloped — even as the base climbs. This is supposed to be impossible. The standard reconciliation requires either that the BoJ will eventually cut the base by ~80% (which it has not done) or that hyperinflation is imminent (which it is not).

![Japanese CPI vs monetary base — direct relationship clearly broken](<../media/2013-09/japan mystery.png>)

The ITM resolves the mystery without invoking expectations or "credibility": Japan's [[information-transfer-index]] κ rose toward 1, putting the economy in the regime where $\partial P / \partial \text{MB} \approx 0$. Adding more monetary base just doesn't move the price level when you're at the top of the [[information-trap|information trap ridge]]. The fit using the model — including the unit of account effect — reproduces the entire post-1970 Japanese price level with the same equations that work for the US.

![ITM fit to Japanese price level 1970–2013](<../media/2013-09/japan information transfer model 2.png>)

## Why Japan crossed first

Japan got to high κ ahead of other developed economies because it accumulated monetary base faster relative to NGDP. The 1990s asset price collapse and the BoJ's response (large-scale liquidity injection that didn't show up in the price level) pushed the economy across the ridge by around 2000. After that point, conventional monetary policy lost its grip. Subsequent expansions (early-2000s QE, mid-2000s QE, and eventually Abenomics) were operating in a regime where monetary stimulus has at best a weak effect on prices and output.

This isn't a unique pathology of Japanese institutions or culture — it's a structural feature of being far enough into the high-κ regime. The US in 2010s and the [[ecb-eurozone|EU]] in 2015 are following the same path, just behind on the timeline.

## Abenomics and the mean-reversion correction

Abenomics, launched in 2013, was a deliberate attempt to break out of the deflation regime through aggressive monetary expansion combined with fiscal stimulus and structural reforms. Initial inflation numbers looked promising and a wave of commentary treated Abenomics as evidence that an aggressive enough central bank can always escape the trap.

The ITM's first reading of the early Abenomics data was equivocal — the model suggested the inflation uptick was real but might or might not be sustained. Then, in January 2015, Smith discovered a fitting error in his Japan model. The original fit had used only 2005–2013 data; refitting to the full 1994–2013 period showed that **Abenomics started at the largest negative deviation in the entire model**. The subsequent inflation was almost exactly the size and timing you'd expect from mean reversion alone — no policy success required. The corrected fit is one of the most striking examples in the wiki of the model surviving its own creator's mistake. See [[2015-01-12-japan-correction]] for the correction.

The implication: most of the "Abenomics worked" commentary mistook mean reversion for policy effectiveness. Japan remained in the [[information-trap]]; the brief inflation was a fluctuation, not an exit.

## The 2014 recession

The ITM also predicted Japan's 2014 recession in real time using [[nominal-shocks]] extraction. Most observers were surprised when GDP turned down, since the conventional narrative held that Abenomics was succeeding. The ITM had been showing negative shocks accumulating for several quarters before the contraction officially showed up, illustrating how the framework provides a leading indicator that mainstream models miss.

## Japan as natural experiment

Japan's importance to the ITM goes beyond confirming model predictions. It's a natural experiment for what the rest of the developed world might face. The ITM's claim that monetary policy eventually fails as κ rises toward 1 is testable on Japanese data spanning ~30 years and three major QE programs. The result is consistent: nothing the BoJ has tried has restored monetary policy effectiveness. This is the strongest available evidence that the [[information-trap]] is a real structural phenomenon, not a temporary post-2008 condition that will resolve itself.

The implication for the US and EU is sobering: there's no reason to expect a different outcome. The [[plucking-model]] / [[recessions]] dynamics are still operative, [[fiscal-policy]] still works inside the trap (because $\partial P/\partial \text{NGDP}$ remains nonzero), but the conventional monetary transmission mechanism is gone. Japan has been adapting to this for two decades. Other developed economies will either have to do the same or find one of the [[information-trap|exit mechanisms]] — none of which are gentle.

The [[quantity-theory-of-labor]] sharpens this further. Japan's deflation persistence has a demographic explanation: with a shrinking labor force, the labor-driven inflation rate is structurally negative or near zero. To hit 2% inflation, Japan would need substantially higher labor force growth — essentially impossible given the demographics. The BoJ's negative interest rate policy (announced January 2016) is operating against a labor force trend that no monetary action can reverse. The "experiment" was always going to fail because the underlying signal was demographic, not monetary.

## Connections

Japan is referenced across the wiki: [[cross-country-comparisons]] uses it as the canonical high-κ case, [[information-trap]] cites it as the longest-running real-world example, [[expectations]] notes that Japanese inflation expectations have been weak for decades without producing the deflationary spiral that expectations-based models predict, [[predictions]] tracks the ITM's Japan-specific calls. The Japan story is one of the wiki's biggest validations and one of its most important warnings.
