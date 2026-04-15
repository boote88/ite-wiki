---
title: Resolving the Australian interest rate conundrum
date: 2013-10-04T14:06:00.001-07:00
updated: 2013-10-04T14:06:24.124-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/10/resolving-australian-interest-rate.html
---

[mentioned something](http://krugman.blogs.nytimes.com/2013/10/04/the-virtues-of-adding-hoc-wonkish/)

> _... that as long \[a country doesn't\] have large amounts of foreign-currency debt it’s very hard to tell any story in which interest rates surge and the economy slumps ..._



which made me think about [yesterday's problem](http://informationtransfereconomics.blogspot.com/2013/10/australia-australia-australia-australia.html) with modeling the 3-month Australian interest rate. Was Australia's interest rate controlled by its own monetary policy during the 1980s? Sure enough, [I found some data](http://www.aph.gov.au/About_Parliament/Parliamentary_Departments/Parliamentary_Library/pubs/rp/rp0809/09rp30#_Toc228933528) on the amount of foreign currency debt held by the Australian government and it turns out a large fraction was US dollar denominated:


![](<media/australia interest rate conundrum.png>)

If we plot the previous fit alongside the US 3-month rate, the correlation jumps out at you (AUD 3-month in green, USD 3-month in dotted green and the model based on AUD monetary base in blue):



![](<media/australia interest rate conundrum 3.png>)

Taking even an oversimplified picture with an extended model that is the larger of the original AUD model interest rate and the USD 3-month rate data (dotted dark blue, and the curve using the USD model is solid dark blue), you can see that the deviation is no longer that mysterious:



![](<media/australia interest rate conundrum 2.png>)

Eventually I might want to go back and do a better model where the two pieces are weighted by the fractions shown in the graph at the top of this post, but I think this is good enough for now.
