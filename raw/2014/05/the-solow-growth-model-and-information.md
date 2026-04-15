---
title: The Solow growth model and information transfer
date: 2014-05-27T16:12:00.000-07:00
updated: 2014-05-27T16:12:04.292-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/05/the-solow-growth-model-and-information.html
---

Since Piketty has been in the news about economic growth and its relationship with the return on capital, I thought an information-theoretic take on the [Solow growth model](http://en.wikipedia.org/wiki/Solow%E2%80%93Swan_model) would be in order.



The Solow growth model basically posits that output is given by a Cobb-Douglas form equation





I previously applied [the information transfer model to Cobb-Douglas form models](http://informationtransfereconomics.blogspot.com/2014/03/information-transfer-and-cobb-douglas.html) in matching theory. The same math at that link gives us the information transfer model version of the Solow growth model:





The matching theory gives us an interpretation: labor ($L$) is matched with capital ($K$) and creates NGDP. In the information transfer model that becomes: _capital transfers information to labor that is detected by NGDP_. Let's see how this model does empirically.



I used the real capital stock data from FRED and adjusted it by the CPI (less food, energy) to give the nominal capital stock. Labor is simply the total non-farm employees. The fit parameters for the duration of the data (1957 to 2011, set by the CPI and capital stock data limits, respectively) are $\kappa = 1.51$ and $\lambda_{ref} = 1081$ billion dollars. This means that the exponents don't exactly fit the "constant returns to scale" assumption $\alpha + \beta = 1$. We have $\alpha = 0.51$ and $\beta = 0.34$. The model doesn't do too badly for such a simple model:


![](<media/itm solow growth model 2.png>)

It does better on shorter time scales -- here it is fit to 1980-2010:


![](<media/itm solow growth model 3.png>)

In the real Solow growth model, $L$ is actually $A \cdot L$ where $A$ represents phlogiston aether technology and knowledge. If we assume that $A$ is reponsible for the deviation from the constant returns to scale between $K$ and $L$, the imputed value of $A$ is given in this graph (normalized to 1 in 1957):


![](<media/itm solow growth model 1.png>)
