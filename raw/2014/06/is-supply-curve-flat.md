---
title: "Is the supply curve flat?"
date: 2014-06-28T17:12:00.000-07:00
updated: 2014-06-28T17:12:28.606-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/06/is-supply-curve-flat.html
---

Answering the question in the title, no, but during the course of writing the past few posts, I'd looked at the wikipedia article on [general equilibrium](http://en.wikipedia.org/wiki/General_equilibrium). I saw this random bit about Sraffa:

> _Anglo-American economists became more interested in general equilibrium in the late 1920s and 1930s after [Piero Sraffa](http://en.wikipedia.org/wiki/Piero_Sraffa)'s demonstration that Marshallian economists cannot account for the forces thought to account for the upward-slope of the supply curve for a consumer good._

What follows is a just-so story mechanism about how changes in output should affect the price. It appears as though Sraffa's argument entirely ignores the premise of Marshallian supply and demand diagrams (there is a single good in a single market) by asserting that there are other goods and factors of production. The use of "first order" in the wikipedia explanation of the mechanism is also pretty laughable since [Sraffa didn't include a single equation](http://pchen.ccer.edu.cn/homepage/Homepage%20Chinese/AED2003/readingpapers/DDSS/SraffaReturn26.pdf) much less any scales which we could use to say that anything is "first order". I tried to read Sraffa but was instantly filled with a grim sense of philosophers talking about [what change is](http://en.wikipedia.org/wiki/Four_causes). I then Googled around and found [this](https://unlearningeconomics.wordpress.com/2012/12/11/whichever-way-you-paint-it-the-supply-curve-is-flat/), which helped a bit. I concluded that information theory is the proper way to deal with the entire situation.



What are we talking about when we draw supply and demand curves anyway? Let's go back to [the beginnings of this blog](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html). Supply (S) and demand (D) are related by the equation:






where P is the price. The general solution (general equilibrium) to this is:



$$\text{(2) }&nbsp;\frac{D}{D_{ref}} = \left( \frac{S}{S_{ref}} \right)^{1/\kappa} $$


A demand curve is what you get when you look at the partial equilibrium by holding demand constant $D = D_{0}$ (an "exogenous" constant information source) and relating it back to the price to get a pair of equations:



$$&nbsp;P&nbsp;= \frac{1}{\kappa} \; \frac{D_{0}}{\langle S \rangle}$$



$$ \Delta D \equiv D - D_{ref} = \frac{D_{0}}{\kappa} &nbsp;\log \frac{\langle S \rangle}{S_{ref}} $$



Symmetrically, a supply curve is what you get when you look at the partial equilibrium by holding supply constant (an "exogenous" constant information destination)



$$&nbsp;P&nbsp;= \frac{1}{\kappa} \; \frac{\langle D \rangle}{S_{0}}$$



$$ \Delta S \equiv S - S_{ref} =&nbsp;\kappa S_{0}&nbsp; \log \frac{\langle D \rangle}{D_{ref}} $$



What are the angle brackets for? They're there to remind us that the variable is "endogenous" (the expected value inside the model) while the other variable is exogenous. These angle bracket variables are important to the discussion above because they parameterize our position along a supply or demand curve. Here are the supply (red) and demand (blue) curves along with the "fully endogenous" general equilibrium solution (gray dotted):



![](<media/ite supply and demand diagrams new.png>)



The demand curve seems to make intuitive sense -- at least at first. If the price goes up, the quantity of a good demanded goes down. But you get into trouble if you try this reasoning the other way: if the price goes down, the quantity demanded goes up? Maybe. Maybe not. If you weren't getting enough at the current price, it might. That depends on your utility, though. Sometimes this is referred to as the diminishing marginal utility of a good: the price you are willing to pay goes down the more widely available a good is. But there we've gone and switched up the independent variable again. The first half (effect of a price change) looks at price as independent, while the second half (diminishing marginal utility) looks at $\langle S \rangle$ as the independent variable \[1\]. 



Both of these get the partial equilibrium analysis in the wrong order mathematically. What we have is an exogenous (independent) change in demand. If demand increases and is satisfied (which we assume by taking $\langle S \rangle$ as endogenous/dependent), the price goes down.



This seems like a totally non-intuitive way to think about it. What is really going on here?



What we have is a system in contact with a "demand bath" \[2\] (or better yet, an "aggregate demand bath"). You could also call it an "information bath". If that bath didn't exist, adding (satisfied) demand would make the price go up, per equation (2) above (and it would move along the gray dotted curve in the figure above). What the bath is doing is sucking up any extra demand (source information) that we are creating by moving along the demand curve, so that "demand" is the same before and after the shift. Since there is "no change" in demand (any change is mitigated by the bath), the next variable in the chain, $\langle S \rangle$ effectively becomes the changing independent variable. This means the explanation is that decreasing/increasing the supply increases/decreases the price at constant demand (in the presence of a demand bath).



So why does the supply curve slope upwards? This time we're in contact with a "supply bath", so "the supply" is basically the same after we move along the curve. Moving along the supply curve is a change in $\langle D \rangle$. This means the explanation is that decreasing/increasing the demand decreases/increases the price at constant supply (in the presence of a supply bath).



Therefore there is no actual change in the supply along a supply curve so there is no bidding up factors of production or lack thereof per Sraffa. What we're doing is increasing the demand, so the price goes up.



That is to say supply and demand curves are kind of misnomers. A supply curve is the behavior of the price at constant supply, but is parameterized by increasing or decreasing demand. A demand curve is the behavior of the price at constant demand, but is parameterized by increasing or decreasing supply. \[3\]



\[1\] Yes, economists take price to be the independent variable, but in the formulation above it is more natural that either supply or demand (or both) are the independent variable(s). The price is the derivative of the demand with respect to the supply (the marginal change in demand for a marginal change in supply).



\[2\] This whole description is based on an [isothermal expansion/compression](http://en.wikipedia.org/wiki/Isothermal_process) of an ideal gas in contact with a thermal bath.


\[3\] Shifts "of" the supply and demand curves (as opposed to shift "along") are effectively changes in the information bath
