---
title: On using Taylor expansions in economics
date: 2016-09-26T22:19:00.001-07:00
updated: 2016-11-02T09:53:35.570-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/09/on-using-taylor-expansions-in-economics.html
---

> Just told a theoretical chemist that macro econs dump all but first term of Taylor expansion. Initial disbelief then uproarious laughter.
>
> — Jo Michell (@JoMicheII) [September 25, 2016](https://twitter.com/JoMicheII/status/780036490453803010)



I'm fairly sure that the chemist's response must have been based on little other information about macroeconomics because after immersing myself in the subject this physicist doesn't see anything wrong with keeping just linear order terms.



One possibility is that the chemist misunderstood first term to mean just the zero-order polynomial (i.e. a constant), but I will take this to mean the first non-constant term (which may in fact be the quadratic one for reasons I'll go into below). For those unfamiliar with the idea, a [Taylor expansion](https://en.wikipedia.org/wiki/Taylor_series) is a polynomial approximation to a more complex function, and the 'terms' are the pieces proportional to the powers of the variable. Basically, for any smooth enough function _f(x)_ near _x = a_, we can say



_f(__x_ _≈_ _a__) ≈ f(a) + (df/dx|x=a) (x − a) + (1/2)(d²f/dx²|x=a) (x − a)² + ..._



where "_F|x=a_" means "_F_ evaluated at _x = a_". This shows the zero order, first order and second order terms. Note that the first and second derivatives are evaluated at the point _a_ that you are approximating the function near, and can therefore be considered constants:



_f(x) ≈ c₀ + c₁ (x − a) + c₂ (x − a)² + ..._



At a given order, this approximation is usually only good inside a limited region where _x ≈ a_. Taylor expansions are used in lots of places -- and are typically useful if the variable _x_ stays in some neighborhood of _a_ or _x_ itself is small. In the case where _x_ ≈ 0, it is technically called a Maclaurin series, which I only mention in order to post my picture of Colin Maclaurin's memorial in Greyfriar's Kirkyard in Edinburgh ([again](http://informationtransfereconomics.blogspot.com/2015/01/scottish-enlightenment-photoblogging.html)).



![](media/IMG_3020.JPG)



Anyway, a few really useful Taylor (Maclaurin) series expansions (to order _x²_) are

_sin(x) ≈  x_

_cos(x) ≈ 1 − x²/2_

_log(1+x) ≈ x - x²/2_



That last one crops up in economics all the time; if you express your variable as a deviation from 100% (i.e. 1) and keep only the linear term, then the logarithm is approximately equal to that percent difference: _log(100% + x%) ≈ x%_. This is the basic idea behind log-linearization \[[pdf](https://www3.nd.edu/~esims1/log_linearization_sp12.pdf)\]. That also tells us that keeping only the linear terms isn't that big of a problem. For example, a bad recession involves a 10% shock to output or employment. The error in _log(1+x)_ from keeping the linear term only is _~ x²/2_, or about 0.1²/2 = 0.005 = 0.5%. Not bad. If you compound growth over many years, this starts to become an issue, though. For example, 2% inflation over 50 years leads to 50% error in the log-linear approximation.



In addition to not being numerically useful to go beyond leading order in macroeconomics, there are also a couple of other issues that might give you pause when using Taylor expansions.



**We usually choose _f(x = a)_ near an equilibrium in sciences**



In economics, equilibrium isn't necessarily well defined (and even worse, just assumed), and the higher order terms in the Taylor expansion represent parameter space that is even further from that ill-defined equilibrium. Tread lightly in those dark corners! In physics, chemistry, and other sciences, this equilibrium is well-defined via some maximization/minimization principle (maximum entropy, minimum energy, etc) with an interior optimum and one can use that fact to your advantage. Being near an optimum means the linear term is _c₁ ≈ 0_, leaving only the second order term. You may think that the utility maximum in economics is a local optimum, however it is usually a utility maximum over a bounded region (e.g. budget constraint) meaning the optimum is on the edge so the linear term doesn't necessarily vanish (why I mentioned the interior optimum above).



Also, in the sciences, you degrees of freedom might change when you move away from the linear zone near _x ≈ a_. I am under the impression that rational agents [are really only valid in a narrow region near macroeconomic equilibrium](http://informationtransfereconomics.blogspot.com/2016/02/one-more-physics-analogy.html). In an ideal gas, the rotational or vibrational modes of your molecules might become important, or the thermal wavelength may become on the order of the deBroglie wavelength (quantum effects become important).



**The function _f(x)_ is usually** **_ad hoc_ in economics**



The function _f(x)_ in macroeconomics is usually some guess ([ansatz](https://en.wikipedia.org/wiki/Ansatz)) like a Cobb-Douglas function or [CES function](https://en.wikipedia.org/wiki/Constant_elasticity_of_substitution). Taylor expanding an _ad hoc_ function is really just choosing the _c₁_'s and  _c₂_'s to be some arbitrary parameters. This contrasts with the case in physics, chemistry, and other sciences where the function _f(x)_ is usually not _ad hoc_ (e.g. [expanding the relativistic energy](https://en.wikipedia.org/wiki/Energy%E2%80%93momentum_relation#Correspondence_principle) gives you the classical kinetic energy term at second order in _v/c_), or you are near an equilibrium in which case  _c₁ ≈ 0_ and adding _c₂_ doesn't lead to your problem having more parameters than a general linear case.



**It makes the identification problem even worse in economics**



Identification at linear order already has _m²_ versions of the coefficient _c₁_ for _m_ macroeconomic observables (an _m×m_ matrix). Going to second order adds another _m²_ parameters (the _c₂_'s). As mentioned [by Paul Romer in the case of adding expectations](http://informationtransfereconomics.blogspot.com/2016/09/of-phlogiston-and-frameworks.html), adding second order (nonlinear) terms makes the identification problem twice as bad (because the functions are _ad hoc_ as mentioned above). The reason you have so many parameters is that the original m equations don't come from some theoretical framework like you have in physics and chemistry (where symmetries or conservation laws constrain the possible parameters).



And last but not least ...



**Macroeconomics doesn't have a working linear theory yet**



Some people might say there isn't a working linear theory yet because those second order terms are important. However given that a major recession is a 10% fall in RGDP growth this seems unlikely. In fact, RGDP per capita is a a fairly straight line (log-linear). [There are some exceptions](https://growthecon.com/blog/BGP-Empirics/), but they are not frequent (e.g. France and Japan transitioned from one log-linear path to a different one after WWII). That is to say, unless you are dealing with a WWII-level disruption, the data is pretty (log-)linear. Once we get that down, we can start to try to understand a more complicated nonlinear theory.



...



Anyway, that is why I think it's fine to keep only those first terms. It has nothing to do with the mathematics, but rather the theoretical and empirical state of macroeconomics. The field still needs its linear training wheels, so let's not laugh.



...

**Update 2 November 2016**

[Gauti Eggertsson and Sanjay Singh demonstrate this explicitly](http://www.nber.org/papers/w22784) with a New Keynesian model.
