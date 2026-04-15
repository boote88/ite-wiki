---
title: "Scott Sumner's Model (Part 2)"
date: 2013-08-30T17:25:00.000-07:00
updated: 2013-08-30T17:25:39.269-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/08/scott-sumners-model-part-2_30.html
---

After the dramatic failure that was the "[nominal hourly wage model](http://informationtransfereconomics.blogspot.com/2013/08/scott-sumners-model-part-1.html)" in the previous post, I decided to try and build Sumner's model (which he [asked for](http://www.themoneyillusion.com/?p=14826) over a year ago) from the more vague instruction in his recent post on [a third way](http://www.themoneyillusion.com/?p=23152):

> _... I greatly prefer a third approach; labor and money._

Following the [information transfer framework approach to the IS-LM model](http://informationtransfereconomics.blogspot.com/2013/08/deriving-is-lm-model-from-information.html), and reading into [Sumner's use](http://www.themoneyillusion.com/index.php?s=okun) of [Okun's law](http://en.wikipedia.org/wiki/Okun's_law), I wrote down two markets (in my new notation for describing an information transfer market, $\text{detector }: \text{ source } \rightarrow \text{ destination}$):




The price level ($P$, using FRED CPI less food, energy) is detecting the signal from the aggregate demand ($NGDP$) to both the labor supply $LS$ (where I use FRED's all employees measure [PAYEMS](http://research.stlouisfed.org/fred2/series/PAYEMS)) and the money supply (or monetary base $MB$). I will now build the two markets: the **labor market** and the **money market**.

**The Labor Market**

Like the IS-LM model, I took the labor market to have aggregate demand ($NGDP$) as a constant information source, hence (using Equations $\text{(8a,b)}$ from [here](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html)):




where $NGDP_0$ is the constant information source and $\Delta NGDP$ measures deviations from the equilibrium value. $L_0$ and $\kappa_L$ are arbitrary constants that will be used to fit to empirical data. Values of the expected labor supply $\langle LS \rangle$ move you along a labor supply (LS) curve. To that end, we can re-write these equations as an explicit curve in $P$, $\Delta NGDP$ space (by eliminating $\langle LS \rangle$):





This equation is analogous to the IS curve [here](http://informationtransfereconomics.blogspot.com/2013/08/deriving-is-lm-model-from-information.html). This allows us to draw a labor supply (LS) curve versus real output (RGDP) $Y = NGDP/P$ (with the price level normalized to 1995 dollars and output shown in 1995 dollars):



![](<media/sumner model ls1.png>)

The LS curve slopes slightly downward like the AD curve in the [AD-AS model](http://en.wikipedia.org/wiki/AD_AS_model) and the IS curve in the [IS-LM model](http://en.wikipedia.org/wiki/IS/LM_model). You can think of it as the diminishing marginal utility of labor (at fixed money supply, which we will treat later). We can also show the model fit (blue) to the price level (green) via Equation $\text{(1)}$:



![](<media/sumner model ls2.png>)

The constants are $\kappa_L = 0.041$ and $L_0 = 112 \text{ million people}$ (PAYEMS is given in units of thousands of people). Additionally, we can derive a version of Okun's law starting from Equation $\text{(1)}$:



$$<br />
P = \frac{1}{\kappa_L}\frac{NGDP}{LS}<br />
$$
$$<br />
LS = \frac{1}{\kappa_L}\frac{NGDP}{P} = \frac{1}{\kappa_L} RGDP<br />
$$
Taking the time derivative (and then dividing the equation by $LS = RGDP/\kappa$):
$$<br />
\frac{d}{dt} LS(t) = \frac{d}{dt} \frac{RGDP(t)}{\kappa_L}<br />
$$
$$<br />
\frac{1}{LS} \frac{d}{dt} LS =\frac{\kappa_L}{RGDP}&nbsp;&nbsp;\frac{d}{dt} \frac{RGDP}{\kappa_L}<br />
$$
So that finally
$$<br />
\frac{d}{dt} \log LS(t) = \frac{d}{dt} \log RGDP(t)<br />
$$
Which allows us to plot this rather remarkable fit (at least for economics):

![](<media/sumner model okun.png>)



Or in the way Okun's law is usually presented (as a plot of a set of points with one axis being change in the labor supply and the other being the change in output):



![](<media/sumner model okun2.png>)

This defines the labor market (LS market); it already delivers some empirical success describing the price level and Okun's law. To build a (simplified) complete economy however, we must include the effect of the money supply (I will use the monetary base here) on the price level. Changes in monetary policy that affect the price level will cause effects in the labor market since both use the price level as the measure that detects a signal from the aggregate demand.



**The Money Market**


Unlike the labor market (and the money market in the IS-LM model) I will build the model using a "floating information source". This assumption is where the purported power of monetary policy (in the monetarist view) enters into the model as will be made clear later. In that case the solution to the differential equation Eq. $\text{(5)}$ from [here](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html) no longer has the form Eq. $\text{(2)}$ above, but instead:



$$<br />
NGDP \sim MB^{1/\kappa}<br />
$$


Here we use $\kappa$ without a subscript since it is different free parameter from $\kappa_L$. Starting from the price equation for the money market



$$<br />
P = \frac{1}{\kappa}\frac{NGDP}{MB}<br />
$$


and substituting the equation above it, we can write the price level in terms of the monetary base or NGDP:



$$<br />
\text{(4a) } P = \alpha \frac{1}{\kappa} \left( \frac{NGDP}{N_0} \right)^{1 - \kappa}<br />
$$

$$<br />
\text{(4b) }&nbsp;P = \alpha \frac{1}{\kappa} \left( \frac{MB}{M_0} \right)^{1/\kappa-1}<br />
$$


where $\alpha$ is an arbitrary overall normalization (the magnitude of the "price level" is arbitrary). Basically, we have a quantity theory of money with an equation that [can be rewritten as the equation of exchange](http://informationtransfereconomics.blogspot.com/2013/07/the-information-transfer-model-and.html). These fits do a bit worse than the information transfer model where $\kappa$ becomes a function of the base (which is the [successful version](http://informationtransfereconomics.blogspot.com/2013/07/dotting-is-and-crossing-ts.html) of the quantity theory of money I put together a couple of months ago) but are reasonable over some fraction of the time domain:



![](<media/sumner model mb2.png>)![](<media/sumner model mb1.png>)

Note that in the picture using the monetary base, the recent QE appears to have been irrelevant (this is fixed in the information transfer quantity theory and the effect I refer to as an [information trap](http://informationtransfereconomics.blogspot.com/2013/08/the-liquidity-trap-and-information.html)). However, during normal times we can plot a money supply (MS) curve (vs real output $Y = NGDP/P$) using Equation $\text{(4a)}$ above (on a graph with the LS curve in blue, again choosing 1995 as the reference year):



![](<media/sumner model ls-ms.png>)

The resulting **LS-MS model** (for labor supply, money supply)  is similar to the "[Keynesian cross](http://en.wikipedia.org/wiki/Keynesian_cross)" AD-AS model with the MS curve analogous to the "45 degree" $AD = Y$ equilibrium line which does not shift (you can only move along it, as it represents a fixed relationship between the price level, NGDP and MB given by equations $\text{(4a,b)}$). Shifts in the LS curve (increases/decreases in aggregate demand) cause the price level to rise or fall, respectively (**_if_** it is supported by a change in the monetary base). An increase is shown with the dashed curve. However, increasing the monetary base causes the equilibrium point on the MS curve to move up and to the right, causing a shift in the information source in the LS market  ($NGDP_0$ in Equation $\text{(3)}$), causing the LS curve to shift up from the solid blue curve to the dashed blue curve. 



**Discussion**



In Sumner's version of this LS-MS model, he concentrates on _**expectations**_ of what monetary policy will be in the future (large shifts that the market believes will vanish via e.g. "tapering" or inflation targeting won't cause the LS curve to move). That implies that the "transmission mechanism" from the MS market to the LS market is only approximately $P_{LS} \approx P_{MS}$ instead of the $P_{LS}= P_{MS} = P$ in the set up of the model at the top of this post.



Note that this model includes monetary offset (you can't move along the MS curve unless the central bank lets you, and in Sumner's expectations language, you can't expect to move along the MS curve unless the you expect the central bank to let you). Fiscal stimulus that directly employed people (e.g. the WPA) might break model and therefore break the relationship between these markets. In that case, the price level will not be what detects a signal from the aggregate demand to the labor supply ($P : NGDP \rightarrow LS$), but instead it will be set by government fiat.



Additionally note that these models assume ideal information transfer i.e. the information in the AD is equal the information detected at the LS and MS markets ($I_{AD} = I_{LS} = I_{MS}$). Deviations from the ideal (likely!) will result in $I_{AD} \geq I_{LS}$ and $I_{AD} \geq I_{MS}$. In those cases solutions usually fall at prices [below those indicated by the ideal price](http://informationtransfereconomics.blogspot.com/2013/04/sticky-prices-from-non-ideal.html).



And finally (note) the empirical success of the LS-MS model is comparable to the [IS-LM model](http://informationtransfereconomics.blogspot.com/2013/08/the-interest-rate-in-information.html). The liquidity trap seems like a robust empirical result of the latter (it is an explicit breaking of the "$P$ transfers information" assumption when the interest rate is at the zero lower bound) while the former seems to break down and requires additional assumptions beyond a simple price mechanism like "expectations" \[1\]. I'd count that as a strike against LS-MS. It does do a good job describing the price level and Okun's law. While my [modified quantity theory](http://informationtransfereconomics.blogspot.com/2013/07/dotting-is-and-crossing-ts.html) is the best (of course), the final outcome of this exercise is that both models are of similar power. The LS-MS model includes a strong prior (monetary policy roolz) that has some empirical evidence, but it is not overwhelming enough to discount e.g.  fiscal policy or the liquidity trap. When you use it, you are **_assuming_** monetary policy is powerful.

> \[1\] I put this is scare quotes on purpose. These expectations are like [superluminal signals](http://en.wikipedia.org/wiki/Superluminal_communication) in physics. It is important to point out that in this model (and the IS-LM model) the price level is detecting **_all signals_** from the AD to the markets. It is inconsistent to say that some of the information transferred from the AD to the MB is detected by the price level, but some (i.e. superluminal expectations) isn't. The information being transferred necessarily **_includes_** expectations. Therefore the [more likely solution](http://en.wikipedia.org/wiki/Occam%27s_razor) (IMHO) isn't that some additional channel of communication from the demand to the supply is disrupting the normal channel but that the normal channel you have is breaking down (e.g. the zero lower bound mechanism in IS-LM).
