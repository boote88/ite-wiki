---
title: "Parsing the macrohistory database: principal components"
date: 2016-10-25T17:00:00.000-07:00
updated: 2016-10-25T17:00:07.880-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/10/parsing-macrohistory-database-principal.html
---

In my [continuing adventures in parsing](http://informationtransfereconomics.blogspot.com/2016/10/parsing-macrohistory-database-interest.html) the [macrohistory database](http://www.macrohistory.net/data/#DownloadData) \[0\], I noticed that most of the interest rate data looks a bit like the US interest rate time series. So I did a principal component analysis (specifically a [Karhunen-Loeve decomposition](https://en.wikipedia.org/wiki/Karhunen%E2%80%93Lo%C3%A8ve_theorem)).



It turns out there are three basic features of world interest rates in the macrohistory database: the US, Japan, and Germany. Here are the component vectors:



![](<media/large database macrodata -principal component- 0.png>)

You can see the first three components are really the only ones with structure -- and they match up with the US, Germany (really only the Wiemar hyperinflation), and Japan:



![](<media/large database macrodata -principal component- 1.png>)
![](<media/large database macrodata -principal component- 2.png>)
![](<media/large database macrodata -principal component- 3.png>)

As a side note, the US and Japan are the countries for which the interest rate model works the best. Additionally, if you leave out Germany \[1\], the US and Japan describe most of the variation of the data (i.e. the German component is mostly used to describe the Weimar hyperinflation in the German data itself).



Another way to put this is that most of the variation in the interest rate data in the macrohistory database is explained by the US data. This makes some sense: the US has been the largest economy for most of the time that the interesting variation in interest rates has happened (post-WWII). Before WWII, interest rates are relatively constant across with the low rates in the Great Depression being the only major variation \[2\]. Since the US interest rate captures most of the variation in the interest rate data, that means the US IT model explains most of the interest rate data -- since it captures most of the US interest rate data.





**Footnotes:**


\[0\] Òscar Jordà, Moritz Schularick, and Alan M. Taylor. 2017. “Macrofinancial History and the New Business Cycle Facts.” in NBER Macroeconomics Annual 2016, volume 31, edited by Martin Eichenbaum and Jonathan A. Parker. Chicago: University of Chicago Press.





![](<media/large database macrodata -principal component- 4c.png>)
![](<media/large database macrodata -principal component- 4a.png>)![](<media/large database macrodata -principal component- 4b.png>)


![](<media/large database macrodata -principal component- 5a.png>)![](<media/large database macrodata -principal component- 5b.png>)
