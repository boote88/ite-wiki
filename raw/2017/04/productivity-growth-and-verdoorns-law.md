---
title: "Productivity, growth, and Verdoorn's law"
date: 2017-04-04T13:45:00.002-07:00
updated: 2017-04-04T13:45:22.421-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/04/productivity-growth-and-verdoorns-law.html
---

... or rather, _We know nothing about productivity, growth, or Verdoorn's law_.



Reading [Chris Dillow's post](http://stumblingandmumbling.typepad.com/stumbling_and_mumbling/2017/04/wages-productivity.html) on wages and productivity (and especially the accompanying graph) inspired me to take at look at UK output and productivity data. I also wanted to bring in some insights from [my previous post](http://informationtransfereconomics.blogspot.com/2017/04/macroeconomics-has-no-equilibrium-data.html) about the major transitions in our macroeconomies obscuring the relationships between macro variables.



First, let's discuss [Verdoorn's law](https://en.wikipedia.org/wiki/Verdoorn%27s_law) which originally said that productivity rises with the square root of output. This is actually a very simple [information equilibrium relationship](http://informationtransfereconomics.blogspot.com/2016/09/basic-definitions-in-information.html) _RGDP ⇄ P_ with information transfer index _k = 2_. Rather straightforwardly, this implies:



log _P_ ~ 0.5 log _RGDP_



or



_P_ ~ √_RGDP_



Since _RGDP_ \= _NGDP/DEF_ (where _DEF_ is the _GDP_ deflator), we can look at the long run [dynamic equilibrium](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html) for _NGDP_ and _DEF_ and find what the dynamic equilibrium for _RGDP_ is. Here are the results (solid lines) for _NGDP_ and _DEF_ followed by _RGDP_:


![](<media/verdoorn and dynamic equilibrium 1.png>)![](<media/verdoorn and dynamic equilibrium 2.png>)

So we'll use this dynamic equilibrium to fit to the productivity data. The actual function I fit was



log _P_ = _a_ log _NGDP_ \- _b_ log _DEF_ \+ _c_



But the best fit parameters found that _a_ = 0.57 and _b_ = 0.47 (and _c_ = 3.3) which is pretty close to what would be expected for Verdoorn's law (a = b = 0.5). So does that mean Verdoorn's law is true? And if so, what of the post-financial crisis productivity drop in the UK? In order to try and understand the data, I also posited a dynamic equilibrium model for productivity. The two models are shown in the following graph of [the UK productivity index](https://www.ons.gov.uk/employmentandlabourmarket/peopleinwork/labourproductivity):


![](<media/verdoorn and dynamic equilibrium 3.png>)

Where we have data, these are not too different from each other. However outside of the data, they are very different. First, let's look at where we have data. We can see the fit Verdoorn's law (equation above, blue dashed below) is pretty closely approximated by √_RGDP_ (gray dashed). The vertical lines represent the centers of the shocks to the _NGDP_ and _DEF_ data above. However the dynamic equilibrium model works just as well and also closely follows √_RGDP_ within the noise of the data.



![](<media/verdoorn and dynamic equilibrium 4.png>)![](<media/verdoorn and dynamic equilibrium 5.png>)


![](<media/verdoorn and dynamic equilibrium 6.png>)

The dynamic equilibrium model hints at a long process of a productivity growth surge across the 20th century (centered at 1949.7) and that "normal" productivity growth is zero. The Verdoorn's law frame sees the productivity data as part of a more recent surge associated with the high inflation of the 70s. Going forward, the dynamic equilibrium frame sees continued falling productivity growth while the Verdoorn's law frame sees constant, but lower, productivity growth.



The recent fall in productivity growth is part of the dynamic equilibrium picture. In the Verdoorn's law picture, it is anomalously low (a productivity "puzzle").



Which is correct?



The data doesn't tell us! The dynamic equilibrium view is definitely more speculative (we are estimating a peaked function where we don't have any data from the peak). The high correlation between productivity growth and RGDP growth definitely lends credence to the Verdoorn's law picture, but that correlation seems to be fading with the more recent data. We could imagine the dynamic equilibrium model with the stochastic innovation term coming from the same source as the one for the RGDP data.



Overall, we have the same problem I pointed out [in the previous post](http://informationtransfereconomics.blogspot.com/2017/04/macroeconomics-has-no-equilibrium-data.html): our macroeconomic data comes from periods that are still strongly affected by major shocks or transitions. It is really hard to say what is "normal" or what is a "normal" correlation. Is log _P_ ~ 0.5 log _RGDP_? Or is log _P_ ~ constant + 20th century industrialization? Since the only quality data comes from a limited post-war time period, we can barely start to address these questions scientifically.
