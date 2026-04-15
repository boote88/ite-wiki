---
title: The KL divergence as a price
date: 2018-04-24T12:30:00.000-07:00
updated: 2018-04-24T12:30:42.282-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2018/04/the-kl-divergence-as-price.html
---

As part of the five year anniversary of this blog, I went back and [re-read this blog post](https://informationtransfereconomics.blogspot.com/2017/04/should-left-engage-with-neoclassical.html) that re-derives the information equilibrium condition using some general scaling arguments (much in the manner that things are presented in e.g. _The Feynman Lectures on Physics_). Let me reproduce one of those arguments here (with a bit of mathjax) about the price as a "detector" of information flow:






If prices change, the two distributions \[of supply and demand\] would have to have been unequal. If they come back to the original stable price — or another stable price — the two distributions must have become equal again. That is to say prices represent information about the differences (or changes) in the distributions. Coming back to a stable means information about the differences in one distribution must have flowed (through a communication channel) to the other distribution. We can call one distribution $D$ and the other $S$ for supply and demand. The price is then a function of changes in $D$ and changes in $S$, or






Note that we observe that an increase in S that's bigger than an increase in $D$ generally leads to a falling price, while an increase in D that is bigger than the increase in $S$ generally leads to a rising price. That means we can try






for our initial guess. Instead of a price aggregating information, we have a price detecting the flow of information. Constant prices tell us nothing. Price changes tell us information has flowed (or been lost) between one distribution and the other.






I did want to note that we could have made a different choice — specifically the [Kullback-Leibler (KL) divergence](https://en.wikipedia.org/wiki/Kullback%E2%80%93Leibler_divergence) $D_{KL}(D, S)$ from information theory. For small perturbations $\Delta D$ and $\Delta S$ from an equilibrium $D_{0} = S_{0}$, we find







which reproduces the same properties above (prices go up for increasing demand, ceteris paribus, and down for increasing supply, ceteris paribus). The interesting piece is that the KL divergence is what is used as the "detector" in [Generative Adversarial Networks](https://en.wikipedia.org/wiki/Generative_adversarial_network), a class of machine learning algorithms that is formally similar to the information transfer framework — [as discussed in that same blog post](https://informationtransfereconomics.blogspot.com/2017/04/should-left-engage-with-neoclassical.html).
