---
title: More on Cobb-Douglas functions and information transfer
date: 2014-05-30T14:21:00.001-07:00
updated: 2014-05-30T14:24:30.205-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/05/more-on-cobb-douglas-functions-and.html
---

Here's a bit more on Cobb-Douglas (CD) functions (previous posts [here \[1\]](http://informationtransfereconomics.blogspot.com/2014/05/the-solow-growth-model-and-information.html) and [here \[2\]](http://informationtransfereconomics.blogspot.com/2014/03/information-transfer-and-cobb-douglas.html)). In Ref \[1\], I was looking at the Solow growth model which uses a Cobb-Douglas functional form (at least asymptotically):



$$<br />
\text{(1) }Y = c K^{\alpha} L^{\beta}<br />
$$

In Ref \[2\], I was looking at matching theory which frequently uses a CD ansatz. In my original derivation of a quasi-CD form in the information transfer model in \[2\], I came up with a function that made a prediction about the exponents in CD forms, i.e.



$$<br />
\text{(2) }Y \sim K^{\kappa - 1} L^{1 - 1/\kappa}<br />
$$


The question is: **_is this true?_** If I look at fits to CD production functions or growth models, do they obey Eq (2)? So I went out and tried to do some literature searches and plot the exponents $\alpha$ and $\beta$ ([WOLOG](http://en.wikipedia.org/wiki/WOLOG), I took the larger exponent to be $\alpha$). There were several papers on the original Cobb-Douglas work from the 1920s (large blue point at $(0.75, 0.25)$ in the graph below for US capital/labor output model), along with several papers on production functions in various industries in different countries. However, the resulting points are by no means exhaustive. In the graph below, $\alpha$ and $\beta$ can fall anywhere in the plot; some models assume constant "returns to scale" such that $\alpha + \beta = 1$, which means the results must fall along the gray line. The information transfer model result (2) above implies that the points must fall along the red line and the red dot at $(0.62, 0.38)$ is the only solution consistent with constant returns to scale. Here is the graph (on the left):



![](<media/cobb doug data 1.png>)![](<media/cobb doug data 2.png>)



This doesn't look very good. The graph on the right looks a little better, but simply represents plotting $\alpha + \beta$ vs $\alpha$. The most charitable interpretation would be that the information transfer model is predictive of the returns to scale (increasing, constant, diminishing). 



However! During the course of reading a bunch of papers, I came across the "derivation" of the Cobb-Douglas form (it originally comes from the mathematician Cobb who sort of guessed the form based on Euler's theorem, see e.g. [here](http://eurodos.chez-alice.fr/docu/econ/hagendorf-2004-2.html)). The derivation posits the basic information transfer model equation I derived in two ways ([here](http://informationtransfereconomics.blogspot.com/2014/02/i-quantity-theory-and-effective-field.html) and [here](http://informationtransfereconomics.blogspot.com/2014/02/ii-entropy-and-microfoundations.html)) as its starting point\*\*. So let's proceed starting from the [basic differential equations](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html) (we're assuming two markets $p_{1}:Y \rightarrow K$ and $p_{2}:Y \rightarrow L$):



$$<br />
\text{(3a) }\frac{\partial Y}{\partial K} = \frac{1}{\kappa_{1}}\; \frac{Y}{K}<br />
$$

$$<br />
\text{(3b) }\frac{\partial Y}{\partial L} = \frac{1}{\kappa_{2}}\; \frac{Y}{L}<br />
$$


The economics rationale for equations (3a,b) are that the left hand sides are the marginal productivity of capital/labor which are _assumed_ to be proportional to the right hand sides -- the productivity per unit capital/labor. In the information transfer model, the relationship follows from a model of aggregate demand sending information to aggregate supply (capital and labor) where the information transfer is "ideal" i.e. no information loss. The solutions are:



$$<br />
Y(K, L) \sim f(L) K^{1/\kappa_{1}}<br />
$$

$$<br />
Y(K, L) \sim g(K) L^{1/\kappa_{2}}<br />
$$

and therefore we have

$$<br />
\text{(4) } Y(K, L) \sim&nbsp;&nbsp;K^{1/\kappa_{1}}&nbsp;L^{1/\kappa_{2}}<br />
$$


Equation (4) is the generic Cobb-Douglas form in equation (1). In this case, unlike equation (2), the exponents are free to take on any value. Equation (2) makes more sense when describing matching theory (i.e. a single market $p:V \rightarrow U$), while equation (4) makes more sense when describing multiple interacting markets (or production factors).



\*\* I'd like to point out that assuming a well-known partial differential equation is not very different from assuming its well-known solution -- something I refer to as "ad hoc in the worst way" in an [earlier post](http://informationtransfereconomics.blogspot.com/2014/05/the-effect-of-expectations-in-economics_5.html).
