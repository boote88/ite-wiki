---
title: Different unemployment rates do not contain different information
date: 2017-09-26T11:30:00.000-07:00
updated: 2017-10-13T19:30:23.045-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/09/different-unemployment-rates-do-not.html
---

I saw [this tweet today](https://twitter.com/NickTimiraos/status/912697042258014208), and it just kind of frustrated me as a researcher. Why do we need yet another measure of unemployment? These measures all capture exactly the same information.



I mentioned this [before](https://informationtransfereconomics.blogspot.com/2017/02/heterogeneous-labor-supply-shocks.html), however I thought I'd be much more thorough this time. I used the dynamic equilibrium model on the U3 (i.e. "headline"), U4, U5, and U6 unemployment rates and looked a the parameters.



Here are the model fits along with an indicator of where the different centers of the shocks appear as well as a set of lines showing the different dynamic equilibrium slopes (which are -0.085/y, -0.084/y, -0.082/y, and -0.078/y, respectively):



![](<media/dynamic equilibrium -different unemployment rates- 0.png>)

Within the error of estimating these parameters, they are all the same. How about shock magnitudes? Again, within the error of estimating the shock magnitude parameters, they are all the same:



![](<media/dynamic equilibrium -different unemployment rates- 1.png>)

Basically, you need one model of one rate plus 3 scale factors to describe the data. There appears to be no additional information in the U4, U5, or U6 rates. Actually in information theory this is explicit. Let's call the U3 rate random variable _U3_ (and likewise for the others). Now _U6 = f(U3)_, therefore:



_H(U6) ≤ H(U3)_

**...**

**Update 13 October 2017**



The St. Louis Fed just put out a tweet [that contains another alternative unemployment measure](https://fred.stlouisfed.org/series/NEIM156SFRBRIC). It also does not contain any additional information:



![](<media/alt unemployment index dynamic equilibrium.png>)
