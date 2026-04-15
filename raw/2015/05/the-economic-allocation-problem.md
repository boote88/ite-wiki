---
title: The economic allocation problem
date: 2015-05-11T19:08:00.004-07:00
updated: 2015-10-25T13:17:50.118-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/05/the-economic-allocation-problem.html
---

I've done a little bit of site redesign changing out some of the graphics, the blog description and adding a set of random posts instead of popular posts to the sidebar. This post serves mainly as an explanation of the new diagram appearing in the upper right of this blog when viewed with a desktop browser (and appears schematically in miniature as the favicon).



Imagine supplying pints of blueberries to various stores (our "space" coordinate). Blueberries go bad if left on the shelf too long, so each unit of supply and each unit of demand represents a single square on space-time grid. A person shows up at store #4 (space grid point 4) at time t = 2 (time grid point 2) wanting to buy blueberries, represented on the grid as a white translucent box. If there are blueberries available (represented by a blue cube), then blue cube and white box match up and a transaction occurs. If not, the blueberries go to waste or some demand goes unsatisfied. Here is a basic picture:



![](<media/allocation problem 3D.png>)

This is an allocation problem where we are trying to match up the blue cubes with the white boxes. I labeled the blue and white boxes destination and source respectively because they represent an information source and an information destination ... what does this have to do with information you ask?



I'm going to simplify this picture a bit by saying the blueberries don't go bad ... so we can add up all the boxes along the time direction (integrate over time) like this:



![](<media/allocation problem 3D 2.png>)

This creates a bar chart that is essentially a probability distribution:



![](<media/allocation problem 3D 5.png>)

Matching these two probability distributions is the least restrictive constraint on the solution to the allocation problem. In communication systems, one effectively tries to build a channel that gets the distribution of symbols (e.g. letters in the English alphabet or binary 1's and 0's) right on the input side and the output side; this is the basis of [information theory](http://en.wikipedia.org/wiki/Information_theory) \[1\].



Now you can't sell blueberries if no one comes to the store to buy them, so any difference in the destination distribution (blue) from the source distribution represents a loss ... a loss of information available in the source distribution. In information theory, this loss can be measured via the [Kullback-Leibler divergence](http://en.wikipedia.org/wiki/Kullback%E2%80%93Leibler_divergence) (calculated in the graph). In general, _I(destination) ≤ I(source)_. Assuming equality is called ideal information transfer or information equilibrium. It turns out to be equivalent to assuming ideal markets where there is no excess supply or demand -- the probability distributions are equal.



You may be asking where the price comes into this. Well, if the blue (_B_) and white (_W_) boxes stay the same, then the framework is completely agnostic as to what the price is. All we can say is that the price is some constant value, call it _p0_, that we'd have to measure empirically. But if the allocations change by small amounts _dB_ and _dW_, we can look at how the price fluctuates with changes in supply and demand. In this framework, _p = dW/dB_ ... the change in demand given a change in supply.



Now you can change some of the details, but the general principle of looking at the information in the distributions that solve the allocation problem -- and how they have to change when either the source or destination changes -- is the framework set up by the information equilibrium (information transfer) model.



The framework is a somewhat more general (i.e. less restrictive) take on utility maximization and search/matching theory where one tries to solve for the optimal allocation (more on that [here](http://informationtransfereconomics.blogspot.com/2015/05/utility-maximization-matching-and.html)).



**Footnotes:**

\[1\] **Added 5/12/2015**: Borrowing from Shannon (1948), the probability distribution of letters in English evolves as we add dimensions:

Symbol frequency in English (1D categorical distribution)



OCRO HLI RGWR NMIELWIS EU LL NBNESEBYA TH EEI ALHENHTTPA OOBTTVA NAH BRL



Trigram structure (3D categorical distribution, 3-symbol combinations)



IN NO IST LAT WHEY CRATICT FROURE BIRS GROCID PONDENOME OF DEMONSTURES OF THE REPTAGIN IS REGOACTIONA OF CRE



You can see that matching the distribution of English letters is a necessary, but not sufficient condition for creating sentences in English -- however it can be a sufficient condition to faithfully reproduce a message transmitted through your communication channel.
