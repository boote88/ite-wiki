---
title: "Universalizing the model: $\\kappa$-$\\sigma$ space"
date: 2013-07-24T18:14:00.000-07:00
updated: 2013-07-24T18:14:21.651-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/07/universalizing-model-kappa-sigma-space.html
---

[In the last post](http://informationtransfereconomics.blogspot.com/2013/07/fiscal-and-monetary-stimulus.html) I mentioned I wanted to try and look at a way to see model results from different countries on the same graph. Here is the process I went through. First, I set up the variables 







![](<media/comparison in normalized kappa sigma space -TEST-.png>)[Japan](http://informationtransfereconomics.blogspot.com/2013/07/dotting-and-crossing.html)[US](http://informationtransfereconomics.blogspot.com/2013/07/dotting-is-and-crossing-ts.html)

Calculating the derivative above (after dividing by $\alpha$), one obtains 




The bracketed term must be zero since the piece outside the bracket is positive, so therefore, after some substitutions 





Note that this function is only of $\sigma$, $\kappa$ and $C_0/Q_{\text{ref}}^s \equiv \gamma$. This means if I use the parameters for the US to find $\gamma$, I can then constrain the subsequent fits for Japan (and other countries) to maintain $C_0 = \gamma Q_{\text{ref}}^s$ (reducing one degree of freedom). This constrains the fits so that the ridge lines coincide. 



I used the US data to fix $\gamma$ and then fit data for the EU, Japan, Mexico and Indonesia to the two parameters $\alpha$ and $Q_{\text{ref}}^s$. The former parameter is only an overall normalization that depends on the reference year for the price level, so once $\gamma$ is fixed, all subsequent fits are effectively one-parameter fits. Here are the graphs of the fits to the price level:  


![](<media/normalized kappa sigma space -fits-.png>)

The next graph shows the final "universal" results with all of the countries in the same $\kappa\sigma$-plane along with the location of the ridge line (dashed curve, monetary multiplier = 0):



![](<media/normalized kappa sigma space.png>)

Some notes:

-   This is really cool if I do say so myself.
-   It looks like the US, Japan and the EU have entered the space where monetary policy is ineffective (or has the opposite of the intended effect).
-   Mexico has recently entered into a [period of relative stagnation](http://www.minneapolisfed.org/publications_papers/pub_display.cfm?id=4797) that may correlate with the country nearing the multiplier = 0 line.
-   The traditional quantity theory of money, which I define as the inflation rate being equal to the growth rate of the monetary base, applies when $\kappa = 1/2$, shown on the graph.
-   All the data is from the FRED data base, using M1, Nominal GDP and the GDP deflator (except the EU data which uses the Euro Area CPI, less food and energy). The US data uses the Adjusted monetary base and the US CPI.
