---
title: A summary of the information transfer model
date: 2013-07-28T14:49:00.003-07:00
updated: 2013-07-28T14:49:14.982-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/07/a-summary-of-information-transfer-model.html
---

Commenter evilsax asked for a summary of the information transfer model. Here is a first attempt (it is unfortunately a bit wordy at present):



The idea behind the [information transfer framework](http://informationtransfereconomics.blogspot.com/2013/04/the-information-transfer-model.html) is that an information source (identified with the demand in economics) is sending information to a destination (identified with the supply) with a gauge measuring the information transfer. The number measured on that gauge is the price. It turns out the math behind this gives you [supply and demand diagrams](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html) like the ones [frequently used in economics](http://en.wikipedia.org/wiki/Alfred_Marshall#Principles_of_Economics_.281890.29). There are a few parameters you can use to fit to the data you see but all of the basic structure is captured.



Now economists don't just apply this supply and demand reasoning to single goods; it's been applied to macroeconomics as well. For example, the [AD-AS model](http://en.wikipedia.org/wiki/AD-AS_model) and the [IS-LM model](https://en.wikipedia.org/wiki/IS%E2%80%93LM_model) use what appear to be supply and demand curves. What happens if you plug one of these models, say, the [quantity theory of money](http://delong.typepad.com/sdj/2011/10/the-tribal-dislike-of-john-hicks-and-is-lm-history-of-economic-thought-edition.html), into the information transfer framework?



If that were all there was to it, then most economists would say: "Who cares? The equations are [equivalent to the equation of exchange](http://informationtransfereconomics.blogspot.com/2013/07/the-information-transfer-model-and.html) so all you've done is re-label things." And the answer would be some mumbling about rigorous foundations. But that is not all there is to it.



One of the parameters mentioned above is called the information transfer index (I've usually labeled it $\kappa$ following the original [source](http://arxiv.org/abs/0905.0610) for the information transfer framework). In the basic supply and demand theory, $\kappa$ is a constant and is [related](http://informationtransfereconomics.blogspot.com/2013/04/the-previous-post-with-more-words-and.html) to the [price elasticities of supply and demand](https://en.wikipedia.org/wiki/Price_elasticity_of_demand). In the information theory, $\kappa$ counts the relative number of symbols used to hold the information in the demand (information source) and the supply (destination). One way to think about it is the number of digits in the number containing the information. Now the important point to recognize is that money is both the [unit of account](https://en.wikipedia.org/wiki/Unit_of_account) and the [medium of exchange](https://en.wikipedia.org/wiki/Medium_of_exchange). That means the money supply also measures the size of the set of symbols holding information, therefore $\kappa$ becomes a function of the money supply.



This is where the model goes from being just a relabeling of variables to a potentially useful theory:



-   It does a really good job of [calculating RGDP growth](http://informationtransfereconomics.blogspot.com/2013/06/real-growth.html) for a two-parameter model.
-   It [allows a quantity theory of money to explain](http://informationtransfereconomics.blogspot.com/2013/06/which-is-failing-itm-or-qtm.html) low inflation countries and high inflation countries at the same time. The traditional "long run inflation rate" = "long run monetary base growth" works really well for high inflation countries, but not low inflation. The information transfer model fixes that.
-   It [explains why](http://informationtransfereconomics.blogspot.com/2013/07/recovering-quantity-theory-from.html) high inflation countries follow the traditional quantity theory of money.

However, there is a hitch. Or maybe we'll call it a counterintuitive claim. In the model, as the monetary base increases, the price level increases ... but only to a point. After it reaches a certain point (based roughly on the size of the economy), increasing the monetary base decreases the price level. Here is the plot of the price level vs the monetary base for the year 1980 in the US:

![](<media/resolving the meaning of contractionary expansion.png>)

This result would likely get me laughed out of an economics conference. One of the reasons I haven't given up is that this effect allows the model to explain [the US since 2008](http://informationtransfereconomics.blogspot.com/2013/07/dotting-is-and-crossing-ts.html) and [Japan since the 1990s](http://informationtransfereconomics.blogspot.com/2013/07/dotting-and-crossing.html). In both linked cases I have a red curve that shows what a "normal" quantity theory would look like. There are more traditional (but not necessarily universally accepted) economic explanations of the US and Japan in terms of [a liquidity trap](https://en.wikipedia.org/wiki/Liquidity_trap).



Why does the model do this? Here is one way to think about it. Imagine you are given a (demand) number written in a series of 10 boxes. You have to copy down this information, but you are only given three (supply) boxes in which you can write the digits 0-9:

![](<media/resolving the meaning of contractionary expansion BOX1.png>)

Well, one way to do this is to put 2, 3 and 9 in the boxes and say that the number is $2.3 \times 10^{9}$, then you send 3, 3, and 7 so that you add $3.3 \times 10^{7}$ resulting in $2.333 \times 10^{9}$. And so on. Another way to code this is as 1, 2, 3 and then 3, 3, 3 and then 5, 2, 1 meaning "in box 1 and the next box put 2 and 3, in box 3 and the next box put 3 and 3", etc. There are lots of ways to code this number and send it in packets. Now if you are given more boxes, it takes fewer steps ...

![](<media/resolving the meaning of contractionary expansion BOX2.png>)

This could be sent in two steps as 2, 3, 3, 3, 2, 1, 9 and 2, 5, 6, 7, 0, 0, 3. However, as you add boxes, the _[marginal](http://en.wikipedia.org/wiki/Marginal_concepts)_ improvement in the number of packets that have to be sent goes down. Eventually you reach a point where adding boxes adds nothing to the ability to capture the information:

![](<media/resolving the meaning of contractionary expansion BOX3.png>)

So you will see a large improvement in the number of boxes that eventually slows and reaches a peak somewhere below the point where there are the same number of boxes for the supply and demand. Basically, the picture in the graph above.



One way to think about the price level then is as a measure of the marginal utility of adding money to the economy. As the economy gets bigger, the marginal utility also changes (the dashed curve is for 1990); you can see in this graph that having the same size monetary base as you did in 1980 in 1990 would lead to deflation (the dashed curve at the 1980 point falls below the solid curve):

![](<media/resolving the meaning of contractionary expansion 2.png>)

This is not an established "stylized fact" in economics; most mainstream economists believe that increasing the monetary base will always in the long run lead to inflation (related to the [neutrality of money](http://en.wikipedia.org/wiki/Neutrality_of_money) in the long run). In the short run, most economists believe that increasing the base too slowly can lead to deflation and some believe it is possible that increasing the base might not lead to inflation e.g. in a liquidity trap. The counterintuitive effect in this model is that increasing the base too much can lead to deflation (or reduced inflation, called disinflation) in both the short run and the long run. The low inflation environments of the US and Japan may be the evidence that backs up this claim in the information transfer model.
