---
title: "Parsing the macrohistory database: interest rates"
date: 2016-10-24T18:00:00.000-07:00
updated: 2016-10-25T17:42:13.928-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/10/parsing-macrohistory-database-interest.html
---

**Update 25 October 2016:** _check out [this follow up](http://informationtransfereconomics.blogspot.com/2016/10/parsing-macrohistory-database-principal.html) using principal component analysis._

I was directed to [this long time series macro data](http://www.macrohistory.net/data/#DownloadData) \[1\] by a reader via email, and so thought I'd try the IT interest rate model:



_log(r) = a log(NGDP/MB) + b_



Only a few series fit over the entire time period with one set of parameters _{a, b}_, but this should be expected because e.g. several European countries are now on the Euro. So I attempted to look for a natural way to break up the data using cluster analysis to find linear segments -- finding clusters associated by a given range of years, _log(r)_ and _log(NGDP/M0)_. Here are the clusters for the USA and DEU:



![](<media/large database macrodata cls3.png>)![](<media/large database macrodata cls2.png>)



Note these are 2D representations of a 3D graph (imagine time going into the page).



I'm still looking at the fit methodology. Some of the data doesn't need to be broken up (particularly the Anglophone countries: USA, CAN, AUS, and GBR -- though I broke up USA and AUS in the graphs below). Many of the European countries do -- and the best place to break tends to be around World War II. Some preliminary results are listed below:



![](<media/large database macrodata 1.png>)
![](<media/large database macrodata 2.png>)
![](<media/large database macrodata 3.png>)
![](<media/large database macrodata 4.png>)
![](<media/large database macrodata 5.png>)
![](<media/large database macrodata 6.png>)
![](<media/large database macrodata 7.png>)

NOR and DEU (Norway and Germany) don't work very well unless you break up the data into many segments (about 4-5).



![](<media/large database macrodata 8.png>)
![](<media/large database macrodata 9.png>)



Nearly all of the countries that don't work well are currently on the Euro, or had pegged their currencies to some other currency at some point.



Anyway, this is a work in progress. I am going to try and map the break points to details of monetary history of the various countries.



...



**Footnotes:**



\[1\] Òscar Jordà, Moritz Schularick, and Alan M. Taylor. 2017. “Macrofinancial History and the New Business Cycle Facts.” in NBER Macroeconomics Annual 2016, volume 31, edited by Martin Eichenbaum and Jonathan A. Parker. Chicago: University of Chicago Press.
