---
title: Beware implicit modeling
date: 2014-07-24T17:55:00.001-07:00
updated: 2014-07-24T20:59:10.945-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/07/beware-implicit-modeling.html
---

One of the difficulties you have when you are steeped in a subject for a long time is that you forget when you are making implicit modeling assumptions. [Nick Rowe claims](http://worthwhile.typepad.com/worthwhile_canadian_initi/2014/07/new-keynesian-neo-fiscalists-for-increasing-austerity.html) that the accounting identity _Y = C + I + G + NX_ is useless, in opposition to the "first-order Keynesian" view that if government spending _G → G + δG_ during a recession we will get real output _Y → Y + δG_. He's making a claim for the null hypothesis, but it's really hard to say which is a less informative prior. Does a signal from G make it to Y or does it get absorbed by C, I and NX?



I probably didn't make it exactly as clear as I would have liked in my comment on the page, but the idea was that the identity is useless is as much a modeling assumption as the first-order Keynesian view. If _G → G + δG_, then



_Y → C + (∂C/∂G) δG  + I + (∂I/∂G) δG + G + (∂G/∂G) δG + NX + (∂NX/∂G) δG_



_\= Y + δG + (∂C/∂G) δG  + (∂I/∂G) δG + (∂NX/∂G) δG_





_|∂C/∂G| , |∂I/∂G| , |∂NX/∂G| << 1_





_|∂C/∂G| , |∂I/∂G| , |∂NX/∂G| ~ 1_



The only way you can't know what happens if _G → G + δG_ is if it is possible for some offsetting effect or some amplifying effect of equal magnitude that makes _δY < δG_ or _δY > δG_, respectively. Note that these are structurally similar assumptions about the dependence of the other variables on changes in G.



Nick also says that the first-order Keynesian view could be used to say that because _Y = C + S + T_, we could raise taxes (T) to get more real output. However, that is not what that equation states; it states that increasing tax _**revenue**_ \[1\] would lead to more real output. Does raising taxes increase tax revenue in a recession? That becomes a modeling assumption. "Raising taxes" is analogous not to increasing government spending but rather to e.g. increasing the number of fixed-price [RFP](http://en.wikipedia.org/wiki/Request_for_proposal)'s the government puts out. While increasing the number of fixed price RFP's could lead to more businesses submitting bids and an increase in government outlays so that _G → G + δG_, it may be such that no business considers any of the potential contracts to be a good deal.





_|∂C/∂T| , |∂S/∂T| ~ 1_





_|∂C/∂T| , |∂S/∂T| << 1_





Rowe believes it is "warped" not to assume the same general dependence of C, I and NX on G as you do for C and S on T.

**Update 7/24, 9pm PDT:** I think I'd like to make this a little stronger. Rowe's claim is that e.g. consumption C depends to first order on government spending G, i.e.


_C = a + b G + ..._



_b ~ 1_


For taxes T, _C ~ a + b T_ makes sense: my personal consumption is basically _C = a - S - T_ (consumption is what is left over after savings and taxes). But for government spending? I'm pretty sure when the stimulus passed, I didn't change my behavior. Maybe I "expected" it to pass and priced it in already.



Another way of putting this is that Rowe is saying the basket of goods comprising C isn't actually at a local maximum or minimum with respect to the given level of government spending. Maybe that is true, but then, that's a model assumption. Consumption isn't utility, but if you take consumption to be proportional to utility, then Rowe is assuming that utility isn't maximized at a given fixed level of government spending. It's still implicit modeling whatever you call it.



\[1\] More tax revenue could mean we have more output (hence causality went the other way), or that the market took raising taxes as a sign that the recession is over, creating expectations of an improved economy. All kinds of theories could be at work.

\[2\] It is possible that _C = a + c G^2 + ..._ with an [unnatural](http://en.wikipedia.org/wiki/Naturalness_\(physics\)) coefficient _c >> 1_, but that is an unnatural assumption.
