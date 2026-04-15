---
title: "Department of Huh? Rent control edition"
date: 2015-11-28T18:28:00.003-08:00
updated: 2015-11-29T14:19:32.385-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/11/department-of-huh-rent-control-edition.html
---

![From Wikimedia Commons.](media/apt.jpg)


I got a couple paragraphs into [this post at _Project Syndicate_ by Brad DeLong](https://www.project-syndicate.org/commentary/the-trouble-with-interest-rates-by-j--bradford-delong-2015-11) and hit a stumbling block:

> _The reason that rent control is disliked is that it forbids transactions that would benefit both the renter and the landlord. When a government agency imposes a rent ceiling, it prohibits landlords from charging more than a set amount. This distorts the market, leaving empty apartments that landlords would be willing to rent at higher prices and preventing renters from offering what they are truly willing to pay._

Huh? DeLong is usually quite good at this sort of thing, so it's possible I'm missing something.

Why would a landlord choose zero rent and an empty apartment over renting at the rent ceiling? It's possible upkeep costs more than the rent ceiling with a renter rather than leaving the apartment empty, but I thought this was [Econ 101 analysis](http://informationtransfereconomics.blogspot.com/2015/11/the-minimum-wage-in-info-econ-101.html).



And why would getting an apartment at the rent ceiling rate be worse for the renter than getting an apartment at the market rate? Sure [Veblen goods](https://en.wikipedia.org/wiki/Veblen_good) come to mind (a thousand dollar a month NY loft apartment isn't as 'impressive' as a ten thousand dollar one ... to those who care about such things), as well as the ability to outbid someone else for the apartment.



I was under the impression that the reason price ceilings were bad in the Econ 101 sense is that they discouraged the building of new supply and acted as an implicit subsidy (basically producing shortages). If you can only get five hundred dollars a month for a one bedroom, it doesn't necessarily make as much sense to build a new building as it would if you could get a thousand. But additionally, more people are able to afford apartments, so fewer would be available. The result isn't empty apartments, but no apartments. And that's also [what Wikipedia says](https://en.wikipedia.org/wiki/Price_ceiling).



**So what does Info Econ 101 have to say about price ceilings?**


In the case of a price minimum _p0_, there's a pretty simple solution. You basically restrict the price to _p ∈ \[p0, ∞)_ rather than _p ∈ (0, ∞)_. However as the two spaces  _(0, ∞)_  and  _\[p0, ∞)_ are diffeomorphic to each other (except for the single point _p0_), you really end up with the same solution, just shifted. We can ignore the tiny detail of the single point at _p0_.



Taking the price to have a maximum value _p0_ is basically restricting the price to the domain _(0, p0\]_, which is more complicated. However there is a great function for mapping the space  _(0, ∞)_ to _(0, p0)_ where we'll again ignore the detail of including _p0_. We'll use an arctangent map so that the differential equation for the price with a price ceiling is the same as the differential equation without a price ceiling after the map _arctan: (0, ∞) → (0, p0)_. This introduces an extra scale parameter (the "width" of the arctangent transition), but it can essentially be absorbed into the information transfer index. Now there are three regimes for the price ceiling. The first is where the ceiling is well above the equilibrium price:



![](<media/price ceiling 1.png>)

The dashed line represents the demand curve with no price ceiling and the solid curves are the supply and demand curves with the price ceiling. For small shifts, this case is not very different than the original solution where the equilibrium price is marked with a black dot.



If the ceiling is comparable to (and below) the equilibrium price, you get a new equilibrium that is below -- but close to -- the ceiling:



![](<media/price ceiling 2.png>)


And finally, if the price ceiling is well below the equilibrium, you get the standard Econ 101 result where the price is basically at the ceiling and the market is unresponsive to supply or demand shocks:



![](<media/price ceiling 3.png>)


**Update 11/29/2015**


I just want to add that I am not advocating rent control, but rather the naive Info Econ 101 approach to understanding the effects that is more well-defined than the naive Econ 101 approach -- best would be a much more complex model.



Generally, my intuition is that a subsidy (or progressive taxation) would probably be the optimal approach. But it's also just a complex problem since space/land is genuinely limited.
