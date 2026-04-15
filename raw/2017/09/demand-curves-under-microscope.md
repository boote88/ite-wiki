---
title: Demand curves under the microscope
date: 2017-09-05T17:00:00.000-07:00
updated: 2017-09-06T09:43:50.087-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/09/demand-curves-under-microscope.html
---

John Handley [has a fun rant](http://jwhandley.blogspot.com/2017/09/econ-101-should-at-least-do-math-right.html) in favor of using calculus in "economics 101" (actually AP economics). He quotes the explanation of the demand curve

> _There are a lot of people who come to a market sells one item. Each person is willing to buy the item at any price lower than some arbitrary price, so if the owner of the market comes out and declares a high price, relatively few people will buy the item. Similarly, if the owner declares a low price, many people will buy it._

Handley correctly says this results in "a weird demand curve with 'steps' at different prices whose width is determined by the number of people will their maximum price at that level." In fact, here is one such demand curve:


![](<media/discrete derivative demand curve 1.png>)

Now [I've written about this explanation](https://informationtransfereconomics.blogspot.com/2015/01/is-demand-curve-shaped-by-human.html) really defining more of an inverse survival curve than a demand curve (i.e. in this case the agents really are defined some distribution over prices they will accept, which is amenable to random agent models). However, there's an interesting place we can take this "economics 101" explanation.



Handley continues:

> _This is entirely different from the smooth curves instructors like to draw to illustrate demand, and inconsistent with the math used when teaching firm behavior (marginal revenue doesn't make sense when the demand curve is a bunch of steps)._

Yes, the derivative (the marginal quantity) doesn't make sense for such a curve because it is basically zero everywhere except for a discrete set of points. It looks (sort of) like this:


![](<media/discrete derivative demand curve 2.png>)

The actual slope of the demand curve (if we fit a line to the data points) would be ‒1/5, indicated by the black dashed line. Now when I said "sort of", that's because I didn't compute the actual derivative —  I computed a finite approximation of a derivative.



The derivative of a curve in calculus is actually the result of a process where you measure the "rise" of the curve divided by the "run" of the curve (how far the curve goes up or down along the _y_\-axis divided by how far along you move along the _x_\-axis). The process that gives you the derivative has you decreasing the steps along the _x_\-axis (_Δx_) until the step size is basically zero (an infinitesimal referred to as _dx_). Note that _Δy_ will also decrease, but if the curve has any slope at all, then even as _Δx_ goes to zero the ratio _Δy/Δx_ will converge to some number. That number is the derivative. In this case, on average the demand curve falls by about 1 unit for every 5 you move across (hence ‒1/5), but "instantaneously" (for very short steps _Δx_) it actually falls a whole unit almost instantly resulting in those spikes in the graph above.



In that graph, I stopped before _Δx_ reached zero (the x-axis is people so _Δx_ is _Δpeople_). The result is a series of spike. If I had let _Δpeople_ go to zero, those spikes become infinitely tall. The marginal utility (or revenue) (i.e. the derivative) would just be a function with values of zero and infinity. It's not very illuminating, and totally disconnected from the way economics it taught with calculus.



However!



In physics we tend to think of that _Δx_ as a "scale": some sort of basis for measurement. As _Δx_ goes to zero, we can think of a microscope "zooming in" on whatever we're looking at. The "scale" of atoms is much more zoomed in than the scale of biological cells when _Δx_ is a distance measurement (in microns or meters).



In our example, our scale is the number of people. As we zoom in to a scale that is smaller than a single person (_Δpeople_ < 1), you get that spiky derivative picture. However, if we zoom out to a scale where we no longer resolve individual people (_Δpeople_ > 1), that derivative starts to converge \[1\] to the "slope" of that demand curve:


![](<media/discrete derivative demand curve 3.png>)

The spiky curves (colors) gradually melt away into the black solid line at _Δy/Δx_ = _Δprice/Δpeople_ = ‒1/5 (dashed line).



How do we interpret this? Well, it gives us [a scope condition](https://informationtransfereconomics.blogspot.com/2015/10/we-built-this-theory-on-scope-conditions.html). The marginal approach to economics doesn't make sense unless we're talking about more than one person (in this case, a marginal utility  is more a property of 16 people than a property of a single person).



If we try to resolve marginal quantities at a scale on the order of a single person, it vanishes into nonsense — as if it was an emergent concept.



...



**Footnotes:**



\[1\] What is interesting is that if our demand curve was actually curved, then we couldn't really zoom out too far because we'd stop resolving the curvature. This implies either that some curvatures of demand curves don't make sense, or that the curvature disappears as we look at bigger groups of people or whole economies.
