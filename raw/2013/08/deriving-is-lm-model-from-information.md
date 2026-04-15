---
title: Deriving the IS-LM model from information theory
date: 2013-08-08T17:11:00.000-07:00
updated: 2013-08-25T18:42:11.066-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/08/deriving-is-lm-model-from-information.html
---

I would like to use this derivation to illustrate a point: the information transfer framework is more general than the specific application to a quantity theory of money that has made up the bulk of the blog posts over the past month or so. The framework allows you to build [supply-and-demand based models](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html) in a rigorous way. I will use it here to build the [IS-LM model](http://en.wikipedia.org/wiki/IS%E2%80%93LM_model).



The IS-LM model attempts to explain the macroeconomy as the interaction between two markets: the Investment-Savings (goods) market and the Liquidity-Money Supply (money) market. The former effectively models the demand for goods with the interest rate functioning as the price (with what I can only guess is "aggregate supply" acting as the supply). The latter effectively models the demand for money with the interest rate functioning as the price (with the money supply acting as the supply). In the most basic version of the model, there is no real distinction made between the nominal and real interest rate.



Economists might find my "acting as the supply" language funny. I am only using it because in the information transfer framework, we have to know where the information source is transferring information: "the supply" is the destination. In our case, we are looking at two markets with a single **constant information source** (the aggregate demand) transferring information to the money supply (in the LM market) and the aggregate supply (in the IS market) via the interest rate (a single information transfer detector). The equation that governs this process is given by Equations (8a,b) in [this post](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html):





However, each market employs these equations differently. The IS market is a fairly straightforward application. The price $P$ is replaced with the interest rate $r$, and the constant information source $Q^{d}_{0}$ becomes the equilibrium aggregate demand/output $Y^0$ (although we will also take it to be $Y^0 \rightarrow Y^0 + \Delta G$ in order to show the effects of a a boost in government spending, which shifts the IS curve outward). The expected aggregate supply is put in the place of $\langle Q^s \rangle$ is the variable used to trace out the IS curve. It can be eliminated to give a relationship between the interest rate and the change in $Y$ ($\Delta Y$ put in the place of $\Delta Q^d$). Thus we obtain




The LM market employs an equilibrium condition in addition to Equations (8a,b), setting $\Delta Q^s = \Delta Q^d$ via the money supply $\Delta Q^s = \Delta M$ (this selects a point on the money demand curve). The constant information source $Q^{d}_{0}$ is still the equilibrium aggregate demand/output $Y^0$, but in the LM market we look at the curve traced out by the equilibrium point for shifts in the money demand curve (changing the "constant" information source, $Y^0 \rightarrow Y^0 + \Delta Y$). These two pieces of information allow us to write down the LM market equation:



Plotting both of these equations we obtain the IS-LM diagram which behaves as it should for monetary and fiscal expansion:



![](<media/simple islm.png>)![](<media/simple islm shift.png>)

In both cases, $\kappa_{xx}$ and $XX_{ref}$ are constants that can be used to fit the model to data (I basically set them all to 1 because all I want to show here is behavior). The interest rate and output are in arbitrary units (effectively set by the constants).



As an aside, there is an interesting effect in the model. It basically breaks down if $r = 0$ (in the [thermodynamic analogy](http://informationtransfereconomics.blogspot.com/2013/04/the-previous-post-with-more-words-and.html), it is like trying to describe a zero pressure system -- it doesn't have any particles in it). As it approaches zero, the LM curve (and the IS curve) flatten out, producing the [liquidity trap effect in the IS-LM model as popularized by Paul Krugman](http://krugman.blogs.nytimes.com/2011/10/09/is-lmentary/). Here is the graph for a close approach to zero:



![](<media/simple islm ZLB.png>)



This is not to say the zero lower bound problem is "correct" anymore than the IS-LM model is "correct". The results here only say that the IS-LM model is a perfectly acceptable model in the information transfer framework, which serves more to validate the framework (since IS-LM is an accepted part of economic theory ... economists may disagree whether it describes economic reality, but they agree that it e.g. belongs in economic textbooks).



What use is couching the IS-LM model in information theory? In my personal opinion, this is far more rigorous than how the model appears in economics. It is also possible information theory could help give a new source of intuition. To that end, let me describe the IS-LM model  in the language of information theory:

> Aggregate demand acts as a constant information source sending a signal detected by the interest rate to both the aggregate supply and the money supply. Changes in aggregate demand are registered as changes in the information source in the LM market, but are registered in the response of the aggregate supply in the IS market \[1\]. Aggregate supply shifts to bring equilibrium to the IS market (the supply reads the information change), but M is set by the central bank and so does not automatically adjust. This creates a disequilibrium situation in which $I_{AD} = I_{AS}$ but $I_{AD} \neq I_{M}$; in order to restore equilibrium, either AD must return to its previous level or M must adjust (adjusting the interest rate) \[2\]. This defines what a recession is in the IS-LM model: a failure of the central bank to receive information (in information theory, we must have $I_{M} \leq I_{AD}$, i.e. the central bank cannot receive more information than is being transferred). A shift in output (e.g. by increasing government spending) is registered as a change in the information source in both the IS market and LM market so we can maintain $I_{AD} = I_{AS}$ and $I_{AD} = I_{M}$ by letting the interest rate adjust to the new equilibrium (e.g. crowding out).

\[1\] This difference is due to a modeling choice in order to represent empirically observed behavior.

\[2\] In a more complicated model there may be other possibilities.
