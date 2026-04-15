---
title: The mystery of the Japanese monetary base
date: 2013-09-14T12:35:00.001-07:00
updated: 2013-09-14T12:35:52.451-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/09/the-mystery-of-japanese-monetary-base.html
---

[quote](http://www.themoneyillusion.com/?p=23593)

> _Just to be clear, in this post I’m treating QE \[Quantitative Easing\] as temporary, as does \[Paul\] Krugman. We both believe that permanent QE is highly effective (at least I think we both do.)_



Since Krugman and Sumner agree, I will take this view as some kind of consensus view. It does allow you to make some sense of, say, the US monetary base (MB) and the US CPI (less food, energy). You see MB chugging along and the price level following suit until, boom, in 2009 as the Fed conducts some QE. The base shoots up and and the price level just sits there. The graph at the end of [this post](http://informationtransfereconomics.blogspot.com/2013/09/an-information-transfer-history-of.html) shows what I mean. Obviously, the economy thinks the QE is temporary and so is experiencing inflation based on the expected base after the QE (which is based on inflation guidance from the Fed and therefore the expected path of the monetary base ex-QE). It seems like a logical argument, doesn't it?






Let's take a look at the Japanese monetary base to see how insane this view is. In the graph below I plot the Japanese CPI (green) and the Japanese monetary base (dark blue) along with the latter's trend (dashed blue); both are normalized to 2005.



![](<media/japan mystery.png>)


Why is the consensus view insane? Well I've taken three tangents to the CPI at different times. We can see the first one roughly parallel with the MB trend. But the next one is almost horizontal. And the third tangent has a negative slope. To me, it is obvious the direct relationship between the monetary base and inflation is breaking down. The consensus view instead believes either the Bank of Japan will eventually cut the monetary base by about 80% to the location marked with a blue asterisk **or** what can only be described as hyperinflation will take hold leading to a five-fold increase in the CPI at some undetermined point in the future as the markets realize the trend increases since the 1990s are going to stick around.



There is a third possibility: the Bank of Japan has convinced everyone that it is so good at fighting inflation it can grow the MB at any rate it desires and inflation will stay the same. But if they're so good at controlling inflation then why has inflation gone negative and they've struggled to hit their targets? Yes, Abenomics, but the markets think monetary policy has some effect (remember the consensus view above). Of course [markets will react positively](http://informationtransfereconomics.blogspot.com/2013/09/the-useless-power-of-expectations.html) to Abenomics.



Now I believe expectations are part of the invisible hand, that is to say, I see no reason to [separate them out](http://informationtransfereconomics.blogspot.com/2013/09/the-artificial-separation-of.html) as different information processed by the market. I have [previously showed](http://informationtransfereconomics.blogspot.com/2013/07/all-your-m1.html) that Japan's situation can be explained with the information transfer model; I am going to expand on that here and show how the changing relationship between the base and the CPI can still come from a purely monetary theory. In the previous work, I only looked at the period since 1994 because that was the only data that exists of sufficient quality in the FRED database. There was some data from before 1994, but it was in US dollars which does not work because the [data needs to be in the same units](http://informationtransfereconomics.blogspot.com/2013/09/the-unit-of-account-effect-and-number.html). Therefore I used exchange rate data to try and figure out what the Japanese GDP was before 1994. In this graph I show the 1994 data (dark red), the GDP in dollars converted to yen (gray) and the estimate of the Japanese GDP since 1970 derived from that (light red):



![](<media/japan gdp.png>)

If I use this extrapolated GDP data in the [information transfer model](http://informationtransfereconomics.blogspot.com/2013/07/dotting-is-and-crossing-ts.html) (along with the monetary base) use the fit to the CPI (green) for the post 1994 data, I get a pretty good fit (blue, the "out of sample fit" is dashed blue):



![](<media/japan information transfer model 1.png>)

If I do the fit over the entire range (1970-2013), it is even better (I show the exchange rate derived data in gray):



![](<media/japan information transfer model 2.png>)

With this graph I show how the changing relationship between the monetary base and the price level can be incorporated in a quantity theory without expectations. The key difference from the quantity theory is the inclusion of the [unit of account effect](http://informationtransfereconomics.blogspot.com/2013/09/the-unit-of-account-effect-and-number.html) that comes from building the model in information theory.



**Addendum: Do we need GDP data?**


Actually, this fit was so good I wondered what the result would be if I used the monetary base and the CPI to extract the GDP data over the entire range. This unfortunately didn't work all that well as the numerical method failed to find a solution for the 1980s (literally, 1980-1989, so the results before and after that period are just connected with an interpolated line):



![](<media/japan information transfer model extrap 1.png>)

It is quite noisy and the best that can be said about it is that it is generally of the right order of magnitude. Here is the numerical solution (blue) evaluated for the CPI (data in green) with the linear interpolation (the only region it doesn't match) included:



![](<media/japan information transfer model extrap 2.png>)


The [equation involves](http://informationtransfereconomics.blogspot.com/2013/09/market-monetarism-falls-in-liquidity.html) GDP inside a logarithm and in the exponent, so numerically this is a difficult situation and I should stick to the fit with the extrapolated data.
