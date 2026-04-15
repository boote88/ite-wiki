---
title: "DSGE, part 1"
date: 2016-08-15T13:38:00.001-07:00
updated: 2019-08-02T15:38:12.650-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/08/dsge-part-1.html
---

Olivier Blanchard \[[pdf](https://piie.com/system/files/documents/pb16-11.pdf)\] both criticized and defended DSGE, which prompted several takes from [Simon Wren-Lewis](https://mainlymacro.blogspot.com/2016/08/blanchard-on-dsge.html), [Brad DeLong](http://www.bradford-delong.com/2016/08/must-read-the-thing-about-this-paper-that-surprises-me-is-in-its-last-paragraphs-that-olivier-blanchard-answers-the-que.html), [Paul Krugman](http://krugman.blogs.nytimes.com/2016/08/12/the-state-of-macro-is-sad-wonkish/), [Noah Smith](https://twitter.com/noahpinion/status/763515763802025984) (Twitter conversation with DeLong), and others. Since the resulting commentary was largely negative (and I have been negative about DSGE before: [here](http://informationtransfereconomics.blogspot.com/2013/04/the-philosophical-motivations.html), [here](http://informationtransfereconomics.blogspot.com/2016/03/is-dsge-framework.html)), let me \[[continue to](https://twitter.com/infotranecon/status/763563919843602434)\] be contrarian and defend DSGE in the only way I know how: by converting it into an information equilibrium model.



I put the IE model [in a DSGE form before](http://informationtransfereconomics.blogspot.com/2014/12/an-information-transfer-dsge-model.html), but my goal here is the converse: to reproduce a mainstream DSGE macro model in the language of information equilibrium -- or at least start the project. First let me collect several pieces I've already assembled:

-   [Solow model/Cobb-Douglas production functions](http://informationtransfereconomics.blogspot.com/2014/12/the-information-transfer-solow-growth.html) (the original RBC model is the genesis of the DSGE approach and it starts from a Solow model)
-   [Utility maximization](http://informationtransfereconomics.blogspot.com/2015/03/utility-in-information-equilibrium-model.html) (in IE we have entropy maximization which coincides with utility maximization for certain parameter choices)
-   [Euler equation](http://informationtransfereconomics.blogspot.com/2015/06/the-euler-equation-as-maximum-entropy.html)
-   [Log-linearization](http://informationtransfereconomics.blogspot.com/2016/08/log-linear-form-of-general-information.html) (this shows the general form of log-linear model equations that can be obtained with an information equilibrium model)

One thing to note is that information transfer economics allows for the information equilibrium relationships above to fail ([in a specific way](http://informationtransfereconomics.blogspot.com/2015/03/non-ideal-information-transfer-tail.html) -- generically as prices that fall below "equilibrium" prices).



My contribution for today is to set up a Taylor rule as an information equilibrium condition. This is actually somewhat trivial and involves two information equilibrium relationships





where $R \equiv e^{r} \approx 1 + r$ is the short term nominal interest rate, $\Pi \equiv e^{\pi} \approx 1&nbsp;+ \pi$ is the inflation rate, and $Y$ is real output (you could also specify consumption $C$). The general solution to the differential equations these information equilibrium relationships set up give us:






Where $R_{ref}$, $\Pi_{ref}$, $Y_{ref}$, $\lambda_{\Pi}$, and $\lambda_{Y}$ are parameters. The parameters $\lambda_{\Pi}$ and $\lambda_{Y}$ are the information transfer indices for the information equilibrium relationships above. Taking the log of this equation, we obtain






Interestingly, non-ideal information transfer means that the observed interest rate will generally fall below the "ideal" interest rate ($r_{obs} \leq r$).



The Taylor rule equation isn't the best information equilibrium model of interest rates, however (yes, I understand it is supposed to guide policy, but in DSGE models it tends to represent the central bank "reaction function" -- i.e. how the central bank will set rates given current conditions). The model [here](http://informationtransfereconomics.blogspot.com/2015/08/interest-rates-and-predictions.html) and [here](http://informationtransfereconomics.blogspot.com/2015/08/comparison-of-interest-rate-predictions.html) is a much better model on average. If we take the information equilibrium relationships







where $r$ is the short term interest rate, $P$ is the price level, $p$ is the "price of money", $N$ is nominal output ($= PY$), $MB$ is the monetary base, and $M0$ is the monetary base minus reserves. For short times (constant information transfer index $k$) we can apply some algebra to obtain



$$<br />
\log r = c_{1} \log Y + \frac{c_{1} (k-2)}{k-1} \log P + c_{1} \log \alpha + c_{0}<br />
$$



where $\alpha = M0/MB$. The equation for the long term interest rate can be obtained by taking $\alpha = 1$. If we take $Y \equiv e^{\tilde{y}}$ and $P \equiv e^{\tilde{\pi}}$ (I use tildes to distinguish from the formula above), then we can write this as:



$$<br />
\log r = c_{1}&nbsp;\tilde{y}&nbsp;+ \frac{c_{1} (k-2)}{k-1}&nbsp;\tilde{\pi}&nbsp;+ c_{1} \log \alpha + c_{0}<br />
$$


There are some key differences between this formula and the more traditional Taylor rule. However, if interest rates stay near some value $r_{0}$ (and $\alpha$ is approximately constant), then we can say (subsuming some extra constants into the new value $c_{0}'$)



$$<br />
\begin{align}<br />
&nbsp;\log r_{0}&nbsp;+&nbsp;\frac{\delta r}{r_{0}} &amp; \approx c_{1}&nbsp;\tilde{y}&nbsp;+ \frac{c_{1} (k-2)}{k-1}&nbsp;\tilde{\pi}&nbsp;+ c_{1} \log \alpha + c_{0}\\<br />
\delta r &amp; = c_{1}r_{0} \tilde{y}&nbsp;+ \frac{c_{1} r_{0} (k-2)}{k-1}&nbsp;\tilde{\pi} + c_{0}'<br />
\end{align}<br />
$$

We can make the identifications:

$$<br />
\begin{align}<br />
\lambda_{Y} &amp; \approx c_{1}r_{0}\\<br />
\lambda_{\Pi} &amp; \approx \frac{c_{1} r_{0} (k-2)}{k-1}\\<br />
c &amp; \approx c_{0}'<br />
\end{align}<br />
$$


For $k \gg 1$, which is the quantity theory limit of the information equilibrium model, we have $\lambda_{Y} \approx \lambda_{\Pi}$, which was true in Taylor's original 1993 version. Additionally, given $c_{1} \simeq 4$, we could take $r_{0} \simeq 10\%$ (which is where the short interest rate was in the late 80s and early 90s). \[This gives both $\lambda_{x} \sim 0.5$, which is where Taylor originally set the parameters.\]



Essentially, deviations from some interest rate $r_{0}$ have the same form as the Taylor rule above. Another way to put this is that in the eyes of an information equilibrium model, the Taylor rule is incorrectly shown as a formula for the value of the nominal interest rate; it should represent a deviation from some "typical" value $r_{0}$. This typical rate is subsumed into the values of the coefficients.

...

**Update 16 August 2016**

I do want to point out two things:


1.  Although the form of an existing DSGE model could potentially be obtained with a series of information equilibrium relationships, the interpretation of the equations is different and non-ideal information transfer means the IE versions of the DSGE models will occasionally fail in a way described by non-ideal information transfer. A good example is the Taylor rule above: it represents an equilibrium, not necessarily something achieved by the actions of a central bank.
2.  It is likely (probably definitely true) that not all DSGE models can be obtained from information equilibrium relationships. There is an overlap in the Venn diagram of DSGE models and IE models, but neither is a subset of the other.

...



**Update 17 August 2016**



One thing to note is that I am leaving off the "stochastic" bit and the $E$ operators for now. The interpretation of the information equilibrium version of the DSGE model will show how these pieces arise. They are deeply linked. In [the second installment](http://informationtransfereconomics.blogspot.com/2016/08/dsge-part-2.html), I begin the discussion of the $E$ operators. \[[Now added in part 3](http://informationtransfereconomics.blogspot.com/2016/08/dsge-part-3-stochastic-interlude.html).\]

...

**Update**

[Here's the summary with links to each part](https://informationtransfereconomics.blogspot.com/2016/08/dsge-part-5-summary.html).
