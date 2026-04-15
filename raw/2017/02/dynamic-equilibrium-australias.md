---
title: "Dynamic equilibrium: Australia's unemployment rate"
date: 2017-02-15T14:30:00.000-08:00
updated: 2017-02-15T14:30:13.849-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/02/dynamic-equilibrium-australias.html
---

I applied the [dynamic equilibrium model](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html) to the Australian unemployment rate, and it works out fairly well. However one of the interesting things is that [FRED only has data up until February 2015](https://fred.stlouisfed.org/series/LRHUTTTTAUM156S) (as of 15 Feb 2017), so fit and the forecast to 2018 was based on data up until then. This showed a strange feature of steadily rising unemployment starting in 2012 which doesn't necessarily fit with the model. The parameter fit said that it was the middle piece of a broad shock that was ending so that the forecast projected a decline in the unemployment rate through the rest of 2015 and 2016. I then went back and scraped the data from [the ABS website](http://www.abs.gov.au/AUSSTATS/abs@.nsf/allprimarymainfeatures/F756C48F25016833CA25753E00135FD9?opendocument) up until December 2016 and the forecast does remarkably well \[1\] (shown in black).



![](<media/unemployment ratio -log version- australia 1.png>)
![](<media/unemployment ratio -log version- australia 2.png>)



The shock locations are 1982.6, 1991.2, 2009.0 (the global financial crisis), and 2013.5. Although there is no "recession" between 1991 and 2009, there are some fluctuations in the unemployment rate (possibly Scott Sumner's [missing mini-recessions](http://www.themoneyillusion.com/?p=12362)?) – I could probably change the bin size on the entropy minimization and the code would recognize those as recessions as well. However as a broad brush view of the Australian economy the four shocks seem sufficient.



I do wonder about the source and explanation of the shock centered at 2013.5 ‒ it appears broader than the typical recession. Possibly a delayed response to the ECB-caused [Eurozone recession](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-unemployment-equilibrium.html) of 2011-2012?


**Footnotes**


\[1\] Instead of being a true "blind" out-of-sample forecast, the data was really just "inconvenient" out-of-sample. \[Ha!\]
