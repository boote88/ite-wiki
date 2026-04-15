---
title: "Labor day! ... and declining union membership"
date: 2018-09-03T17:31:00.005-07:00
updated: 2018-09-04T13:56:57.618-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2018/09/labor-day-and-declining-union-membership.html
---

Not everyone has today off, but I do — probably at least in part due to the fact that I'm among the declining fraction of the US population represented by a private sector union ([this one](https://en.wikipedia.org/wiki/Society_of_Professional_Engineering_Employees_in_Aerospace)). Inspired by [John Handley's tweet](https://twitter.com/jwhandley17/status/1036681518171602944) proposing a possible mechanism behind declining union membership in the US (transition to low union density sectors like service from manufacturing), I thought I'd have a look at the data using the [dynamic information equilibrium model](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3094757). I used data via EPI appearing in [the graph in this blog](https://enlights.org/2018/02/27/supreme-court-to-hear-case-and-probably-damage-u-s-public-sector-unions/). Here is the result:



![](<media/us labor union dynamic equilibrium.png>)

We have two major shocks centered in 1938.2 ("beginning" in 1934.4) and 1987.7 ("beginning" in 1979.9) with widths computed using the measure discussed [in the footnote here](https://informationtransfereconomics.blogspot.com/2018/01/canadas-below-target-inflation.html). There's an overall "equilibrium" decay rate of 1% per year (the "dynamic equilibrium").



So how does this compare to the shock structure of manufacturing employment? Luckily, I already looked into this a few months ago in [my post on "robots versus shipping containers"](https://informationtransfereconomics.blogspot.com/2018/05/robots-versus-shipping-containers.html) — here's the model and data:



![](<media/man2 -1-.png>)

Manufacturing employment shows a large shock from roughly 1970 to the early 90s (with a second, smaller "shipping container" shock in the early 2000s). So John's story holds up against the data (interpreted with this model): a decline in manufacturing causing a decline in unions is consistent with the data. The cause of this decline in manufacturing isn't nailed down by this data — if could be e.g. a shift towards the service sector or moving manufacturing overseas (or both).



However, besides the shocks there is a general decline in union membership rate. This could be an ambiguity in the data because there's a second local entropy minimum near 0.0%/year. If we force a 0.0% per year dynamic equilibrium, we get a comparable model fit:



![](<media/us labor union dynamic equilibrium 0.png>)

I was able to improve it a bit more by dividing the initial positive shock into two with a pause during WWII:



![](<media/us labor union dynamic equilibrium 0a.png>)

This gets us very close to the decline in the rate of union employment being essentially coincident with the two shocks to manufacturing.



So we have two possible stories: 

1.  An "equilibrium" decline in union employment (1%/year) with a shock that "begins" in the late 70s lagging behind the shock to manufacturing employment
2.  An "equilibrium" constant rate of union employment (0%/year) that essentially tracks manufacturing employment, with a shock to both beginning in roughly 1970

Story (1) has some consistency with the "deregulation"/"anti-union" narrative of the late 70s and the Reagan era, but still leaves a question of why union employment generally declines.



Story (2) has a better fit with the data, and is consistent with an Occam's razor "single explanation" approach to manufacturing and union employment. It makes sense of the data in [Noah Smith's original tweet](https://twitter.com/Noahpinion/status/1036650184078323712) that John was responding to: union decline happens in many European countries as well. It also kind of obviates the "anti-union" narrative \[1\]. However, story (2) effectively shifts the question to why manufacturing employment declined in the first place (and also why service sector unions didn't organize in their place \[2\]). \[Per the update below, maybe the manufacturing decline is due to employers being anti-union.\]



I like story (2) from a scientific perspective, but story (1) isn't completely ruled out by the data (as interpreted by this model). Oh, uninformative macro data ...



Happy labor day everyone!

...

**Update 4 September 2018**

[John Handley saw](https://twitter.com/jwhandley17/status/1037060068078833664) that unionization **_within_** manufacturing fell to 10-15%, meaning that sector shift out of manufacturing doesn't explain much of the decline. It could still be shift within manufacturing. That is to say a greater loss of unionized manufacturing jobs over non-union ones — i.e. employers facing unionized employees disproportionately moved manufacturing overseas or anti-union states. This would makes sense in the light of the "union derangement syndrome" that causes employers to try and move jobs to so-called "right to work" (i.e. anti-union) states regardless [of whether it makes sense](https://www.seattletimes.com/opinion/hold-boeing-accountable-for-job-losses/) — surely highly educated researchers would just love [to live in Oklahoma City](https://newsok.com/article/5436914/boeing-breaks-ground-on-80-million-facility-in-okc).




**Footnotes:**



\[1\] Maybe causality actually goes the other way? Did declining manufacturing jobs cause declining union membership — weakening unions politically — so that politicians could enact anti-union policy?



\[2\] Maybe the story in Footnote \[1\] is really 1) decline in manufacturing → 2) decline in unions → 3) decline in political power of unions → 4) politicians enacting anti-union policy → 5) service sector unions prevented from forming.
