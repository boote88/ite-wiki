---
title: "The labour supply, part 1"
date: 2013-11-03T19:49:00.000-08:00
updated: 2013-11-03T19:52:06.795-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/11/the-labour-supply-part-1.html
---

I am continuing to work with [this rather excellent data set](http://informationtransfereconomics.blogspot.com/2013/11/the-long-run-in-uk.html) from the UK. In some previous posts, I looked at the models [P:NGDP→LS](http://informationtransfereconomics.blogspot.com/2013/08/scott-sumners-model-part-2_30.html) and [P:NGDP→U](http://informationtransfereconomics.blogspot.com/2013/10/the-phillips-curve.html) (where P is the price level, LS is the total number of employed aka the labor supply, and U is the total number of unemployed \[1\]). I wanted to see what I could glean from using these models with the UK data.



First I looked at [P:NGDP→LS](http://informationtransfereconomics.blogspot.com/2013/08/scott-sumners-model-part-2_30.html) with fit parameter κLS, and like in the case for the US, the model works to some degree (model in blue, price level data in green and in the second graph the ratio of these two functions is shown in red):



![](<media/uk long run labor 1.png>)![](<media/uk long run labor 2.png>)


This result appears similar to the US result, the slight deviation being related at least in part to [nominal wage stickiness.](http://informationtransfereconomics.blogspot.com/2013/10/sticky-wages.html) If you are watching carefully, you'll notice I pulled a selective-windowing fast one. If you cover the entire range of available data (1855-2009), you can see that there's quite a large divergence:



![](<media/uk long run labor 3.png>)![](<media/uk long run labor 4.png>)

Still, it's a pretty good model for having a single fit parameter. As comes as no surprise, small amount of nominal wage flexibility over the course of 150 years can accomplish a lot. Note the shape of that red curve; besides indicating wages became more flexible after WWII, it will be relevant later.



How about the model [P:NGDP→U](http://informationtransfereconomics.blogspot.com/2013/10/the-phillips-curve.html) with fit parameter κU? Well in the results for the US, the model is actually not a terribly good one -- there are large fluctuations in the model solution for the price level P around the empirical data. In those results I did ask the question whether the result could be used to define the "natural rate" of unemployment (or at least a mean level). The UK data gives us a somewhat worse result than the data for the US, but this may come back to help us figure out what's really going on. Here is the fit to the price level (model in blue, empirical data in green):



![](<media/uk long run labor 6.png>)

If I try to use the green line to defining the "natural rate" as I did in the link above (I used the unemployment rate given in the BOE data and the number of unemployed to define a "civilian labor force"), I get a mess:



![](<media/uk long run labor 7.png>)

Yikes. But! Check out the red line two graphs prior ... it looks remarkably similar. The deviation of the red line from 1 is at least in part due to nominal wage flexibility, but whatever the source of the effect it must be removed from the unemployment model in order to see the "natural rate". This means we need to remove it from [the US unemployment model](http://informationtransfereconomics.blogspot.com/2013/10/the-phillips-curve.html) as well. This effect would have been largely invisible had we not had the three centuries of data aggregated by the BOE from economic researchers cited in the spreadsheet.

**UPDATE** I forgot in the original post to add this graph of [Okun's law derived from the labor supply model](http://informationtransfereconomics.blogspot.com/2013/08/scott-sumners-model-part-2_30.html) of the price level [P:NGDP→LS](http://informationtransfereconomics.blogspot.com/2013/08/scott-sumners-model-part-2_30.html):

![](<media/uk long run labor 5.png>)



\[1\] The model p:x→y means that p = (1/κ) x/y which follows from the [information transfer model of supply and demand](http://informationtransfereconomics.blogspot.com/2013/04/supply-and-demand-from-information.html).
