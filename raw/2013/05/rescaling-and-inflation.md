---
title: Rescaling and inflation
date: 2013-05-30T13:36:00.000-07:00
updated: 2013-05-30T13:36:47.331-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/05/rescaling-and-inflation.html
---

As [mentioned](http://informationtransfereconomics.blogspot.com/2013/05/what-is-arbitrary-here.html), the assumption that the observed price forms a lower bound on the information transfer leads to a steady drift towards the center of the area between the observed supply curve and the ideal supply curve. I decided to see what you get if you took that price as a "real" price and posited that the nominal price is "rescaled" such that the real price remains at the lower bound. The absolute value of the price level is somewhat arbitrary and most economists believe that simply adding zeros on a dollar bill should have no effect (more on this later).



Here I rescaled a fluctuating price level such that it was always at the lower bound curve. This changes the average effect of fluctuations: sticking near the lower bound means that fluctuations downward are cut off, hence a tendency for the price to rise instead of simply a drift towards the center of the red band in the image below.

![](<media/inflation ad as rescaling 2.png>)

A sample path is in light green, the mean path is in dark green, and the rescaled (real) quantities are shown in light gray and dark gray respectively. The "real" price level is stuck at the lower bound by construction:

![](<media/inflation ad as rescaling.png>)

The resulting mean output (dark gray) stays at a roughly constant level (interestingly, a sample path in light gray oscillates randomly back and forth between a high and low level, corresponding to the width of the red band -- business cycles?):

![](<media/inflation ad as rescaling 3.png>)

The required rescaling values per time step for all the 100 sample paths look like this (the mean is shown in green in the second graph):

![](<media/inflation ad as rescaling 5.png>)

If we perform the [product](http://en.wikipedia.org/wiki/Compound_interest) on each time step, we get an exponential curve (the first graph shows a zoomed in version to emphasize the difference from the linear change shown as a dashed gray curve):

![](<media/inflation ad as rescaling 6b.png>)

I'm just playing around here, but maybe this is one source of inflation. I originally just wanted to try and design a system that would be stable in some sense (here, the real price level). I referred to this drift as [the "irreducible" part of inflation earlier](http://informationtransfereconomics.blogspot.com/2013/05/macroeconomics-as-information-transfer.html); there is a "direct" piece that comes from [simply increasing the money supply](http://www.themoneyillusion.com/?p=20216) (quantity theory of money) that dominates for high levels of inflation. I will have to work through these in more detail in the future. 



However! During the course of running these models, I got interested in a new idea related to [renormalization](http://en.wikipedia.org/wiki/Renormalization) in physics. The thing is that the "price level" is actually a somewhat arbitrary definition -- you can rescale the nominal value of currency and it should have no effect. Similarly, we don't really know what the charge of an electron is -- the theory tells us how it scales with energy but it doesn't tell us what the absolute value is. We measure the charge at one energy and QED tells us what it is at all energies. It seems to me to be likely that a macroeconomic theory should similarly tell you the dynamics of the price level, but not its absolute value (due to a rescaling freedom). You'd measure it at one point and then know how it behaves. (Not determining the price level is considered a flaw, e.g. [here](http://www.themoneyillusion.com/?p=915); however the IS-LM model does not determine the price level and seems [relatively successful](http://krugman.blogs.nytimes.com/2011/10/09/is-lmentary/)).



The adding up of Feynman diagrams is my intuitive picture of adding up expectations and transactions in the economy -- and it turns out that things work if you use the "nominal" values (the measured electron charge) in the tree-level diagrams (no loop) in calculating amplitudes. Again, IS-LM doesn't even take into account the difference between real and nominal interest rates! Maybe [money illusion](http://en.wikipedia.org/wiki/Money_illusion) is the result of summing up all possible interactions. 



FYI, I am just "thinking out loud" here and I would like to put this all in a much more rigorous framework eventually. The rescaling here is not necessarily consistent with the previous talk of sticky prices or a vertical supply curve, either. Slowly working the details ...
