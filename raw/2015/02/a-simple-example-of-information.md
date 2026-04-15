---
title: A simple example of information equilibrium
date: 2015-02-06T18:48:00.001-08:00
updated: 2015-02-06T18:48:20.724-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/02/a-simple-example-of-information.html
---

![Gas pump. From wikimedia commons.](media/Gas_pump_display,_Jacksonville,_FL.jpg)



In the information transfer model/information equilibrium approach to economics we start with two quantities A(t) and B(t) and ask whether they are in information equilibrium (meaning information is flowing from A to B or B to A).



What is a simple example of two quantities in information equilibrium? The display on a gas pump like the one pictured above. In particular the "total sale" and the "gallons" (or liters) are two quantities in information equilibrium.



You can see the direct relationship with the underlying information theory of communication by squeezing the nozzle in a pattern, say Morse code. The signal you send in gallons pumped is faithfully (i.e. ideally) transferred to the total sale and someone could read that off.



This is actually not just a _simple_ information transfer process, but rather a _trivial_ information transfer process. The price is constant and the variables are linearly related. There isn't much going on here, but it's a great starting point to explore the information transfer model.



So let's imagine your squeezing of the pump nozzle isn't stable and that gas can sometimes be pulled back out of your tank Let's also say the amount of the total sale has an error. The result will look something like this video:




For every tiny (infinitesimal, even) amount the gallons go up, the total sale goes up a tiny amount. The ratio of those two tiny amounts gives you the price at that moment (i.e. the exchange rate of gallons of gas for dollars):





Since the total sale number has an error in it, the price fluctuates a bit (yes, it's a bit expensive for gas in the US). Now let's do a couple of thought experiments.



If you could fix the total sale at some point during your fill-up, the price would go down as the gallons went up. This traces out a demand curve.



If you could fix the gallons at some point during your fill-up, the price would up as the total sale went up. This traces out a supply curve.



So you see how the logic of supply and demand follows from information equilibrium. You can capture it in the formula



_(total sale) = (price per gallon) x (gallons sold)_



_(demand) = (price) x (supply)_



Now some economists out there and even some non-economists are probably writing up angry or dismissive comments -- mostly centering on the fact that this completely ignores any aspects of human behavior. It must be wrong!



There are a couple objections we can dismiss right now \[1\]:

> **The supply curve is limited to being a line and the price elasticity of supply is always equal to 1!** The above used a simple example where the price is constant and the "information transfer index" _k_ is equal to 1. We actually have:
>
>
>
> _(D) = k (dD/dS) S_
>
>
>
> Which allows you to get pretty much any shape of supply and demand curves you'd like.
>
>
>
> **What about units?!** We typically measure demand (especially aggregate demand) in dollar amounts, so I don't see the issue here. Supply and demand diagrams are plotted so that the x-axis is quantity supplied/demanded, but at the equilibrium price, they are just proportional to each other -- and scales are rarely shown on a supply and demand diagram.
>
>
>
> **Supply and demand curves are a lot more complicated than this!** Maybe they are. But I can't seem to find any experiments that show what is wrong with the framework described above. See more here [\[link\]](http://informationtransfereconomics.blogspot.com/2015/01/is-demand-curve-shaped-by-human.html). The fact that _D = p S_ is all you need to get supply and demand troubled me too (at the link).
>
>
>
> **What about shifts in the supply or demand curves?!** Take your constant variable _D0 → D0 + D1_ (for demand curve movement) or _S0 → S0 + S1_ (for supply curve movement) keeping the other variable constant. The price goes up and down, respectively.

_k ≠ 1_




In this case the derivative _dD/dS_ is changing, so our price is changing. In this case we can associate _D_ with NGDP, _S_ with the amount of currency (M) and _p = dD/dS_ with the price level. The rate of change of the price level is inflation



Also note that you can think of adding money to an economy like adding gas and making the demand for gas (the sale price) go up. In the case of money, NGDP goes up by a larger percentage than the amount of money you added, though (until you end up in a liquidity trap).



I am under the impression that many people who say they don't understand what I am talking about may be thinking that the information equilibrium approach is a lot more complicated than it really is. We are essentially broadening the definition of what it means for two things to be equal. You could start with two functions being equal, _A(t) = B(t)_, and move from there to two functions being proportional, _A(t) ~ B(t)_, so that _A(t) = c B(t) + b_. Information equilibrium goes another step so that two functions are in information equilibrium if, heuristically, _log A(t) = k log B(t) + b_.



If you have two functions related by _log A(t) = k log B(t) + b_, then it is possible to send a message by modulating _B(t)_ and have it show up (faithfully) in _A(t)_ \[2\]. If they are not, then the message will be diminished (you could lose some SNR) or you might not be able to faithfully reconstruct the original message (e.g. ambiguities)



Why is this useful in economics? Because there are lots of times when economists want to relate two quantities (like the [price level and the money supply](http://informationtransfereconomics.blogspot.com/2013/07/recovering-quantity-theory-from.html), [interest rates and NGDP](http://informationtransfereconomics.blogspot.com/2014/08/are-interest-rates-good-indicator-of.html), or [hourly wages and the unemployment rate](http://informationtransfereconomics.blogspot.com/2015/02/scott-sumners-contentless-theory.html)) in order to understand the macroeconomy. The relationship _log A ~ k log B_ is a minimal condition that must be met, otherwise there is information loss (non-ideal information transfer) or some piece of your model that you haven't accounted for. Another way, if you can't relate _A_ and _B_ via _log A ~ k log B_, then your theory is wrong or incomplete. There is also the additional check of the equations involving the price -- you have _A = k p B_ or more generally _A = k (dA/dB) B_, but also _log p ~ (k -1) log B_ (using the solution to the differential equation). I've found that things with [trivial prices](http://informationtransfereconomics.blogspot.com/2014/02/sticky-wages-information-transfer-and.html) (where _p_ is constant or approximately constant) are not terribly useful models.



This is an [incredibly useful tool](http://informationtransfereconomics.blogspot.com/2013/12/useful-ratios.html) to sort out some of the bullshit _ad hoc_ theories out there!


**Footnotes**


\[1\] I started writing up a few paragraphs that attempt to field some of the more obvious objections, but ended up with another Socratic dialog. It'll be in a future post.



\[2\] Before you ask "what about radio waves?", just take your function to be _exp(i A(t))_.
