---
title: Random odds and ends from December
date: 2019-12-24T15:39:00.000-08:00
updated: 2019-12-24T15:39:02.160-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2019/12/random-odds-and-ends-from-december.html
---

I thought I'd put together a collection of some of the [dynamic information equilibrium models](https://informationtransfereconomics.blogspot.com/2018/01/new-paper-up-at-ssrn.html) (DIEMs) that only went out as tweets over the past couple weeks.



I looked at life expectancy in the US and UK (for all these, click to enlarge):


![](<media/DIEM life expectancy UK.png>)![](<media/DIEM life expectancy US.png>)

The US graph appears to show discrete shocks for antibiotics in the 40s & 50s, seatbelts in the 70s, airbags in the 90s & 2000s along with a negative shock for the opioid crisis. At least those are my best guesses! In the UK, there's the English Civil War (~ 1650s) and the British agricultural revolution (late 1700s). Again — my best guess.



Another long term data series is [share prices in the UK](https://fred.stlouisfed.org/series/SPPUKQ):


![](<media/DIEM share prices UK.png>)

Riffing on [a tweet from Sri Thiruvadanthai](https://twitter.com/teasri/status/1209214895096549376?s=20) I made this DIEM for truck tonnage data — it shows [the two phases of the Great Recession](https://informationtransfereconomics.blogspot.com/2019/03/two-phases-of-2008-housing-crisis.html) in the US (housing bubble bursting and the financial crisis):



![](<media/DIEM truck tonnage.png>)

There's also PCE and PI (personal consumption expenditures and personal income). What's interesting is that [the TCJA shows up in PCE](https://informationtransfereconomics.blogspot.com/2019/05/tcja-and-pce-growth.html) but not PI — though that's likely due to the latter being a noisier series.



![](<media/simplified dynamic equilibrium test -PCE-.png>)![](<media/simplified dynamic equilibrium test -PI-.png>)


![](<media/simplified dynamic equilibrium test -PCE- 2.png>)![](<media/simplified dynamic equilibrium test -PI- 2.png>)

Bitcoin continues to be something well-described by a DIEM, [but with so many shocks it's difficult to forecast with the model](https://informationtransfereconomics.blogspot.com/2018/07/wage-growth-and-finishing-out-bitcoin.html):



![](<media/bitcoin dynamic equilibrium 4.png>)

We basically fail the sparseness requirement necessary to resolve the different shocks — the logistic function stair-step fails to be an actual stair-step:



![](<media/bitcoin dynamic equilibrium STEPS.png>)

A way to think about this is that the slope of this time series (the "shocks") are a bunch of Gaussians. When they get too close to each other and overlap, it's hard to resolve the individual shocks.



That's all for now, but I might update this with additional graphs as I make them — I'm in the process of a terrible cold and distracting myself with fitting the various time series I come across.
