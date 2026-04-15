---
title: Randomly generated economies (a work in progress)
date: 2017-02-05T23:27:00.003-08:00
updated: 2017-02-05T23:27:58.193-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/02/randomly-generated-economies-work-in.html
---

I have been in the process of constructing randomly generated unemployment time series based on the [dynamic equilibrium model](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html) (partially inspired by writing my [qualitative analysis post](http://informationtransfereconomics.blogspot.com/2017/02/qualitative-economics-done-right-part-1.html)). I'm still in the process of working out the parameters (or rather, the distributions the parameters are drawn from). However, the work in progress looks neat on its own.



Here's what I mean by a randomly generated time series: effectively a series of Gaussian shocks with random centers, amplitudes, and widths. 



Here is the actual unemployment rate time series (red) alongside a randomly generated path (blue):


![](<media/random economy 0.png>)

In constructing the model (still in progress), I came across some interesting mistakes. For example, if you (accidentally) use a Poisson distribution to yield integer recession transitions:



![](<media/random economy 2.png>)

If you run it for 500 paths you get this:



![](<media/random economy 4.png>)

And here is what happens if you use quarters:



![](<media/random economy 3.png>)

It would be fascinating if there was some resonance with the annual cycle ... Again, this is a work in progress. I will keep you updated.
