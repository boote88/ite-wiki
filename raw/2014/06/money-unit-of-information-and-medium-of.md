---
title: "Money: the unit of information and the medium of information exchange"
date: 2014-06-04T19:13:00.000-07:00
updated: 2014-06-14T14:25:41.842-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2014/06/money-unit-of-information-and-medium-of.html
---

![](<media/information transfer.png>)

We're all familiar with "bits" as units of information and "bits" as the medium of information exchange. We intuitively understand how a 1 GB SD card is a medium for exchanging 1 GB, or 8 billion bits of information. Why, then, is the medium of exchange and unit of account functions of money such a hotly debated topic on the econ blogs? For example, these posts by [Sumner](http://www.themoneyillusion.com/?p=17368) and [Rowe](http://worthwhile.typepad.com/worthwhile_canadian_initi/2012/10/medium-of-account-vs-medium-of-exchange.html) have over 100 comments each as of last check



First, I don't think I have to convince you that money is a medium for exchanging information. By giving you 5 dollars, I am sending you the information "you need to give me 5 dollars worth of goods and services and we're square" or as Narayana Kocherlakota would say "remember to give me 5 dollars worth of goods and services later" in his paper _[Money is Memory](http://www.minneapolisfed.org/research/sr/sr218.pdf)_ \[2\]. The money in your bank account is essentially a record of the work you've done. Actually, one of the oldest ways of storing information in the world was [likely a form of economic transaction](http://www.dailymail.co.uk/sciencetech/article-2460692/Are-clay-spheres-containing-Mesopotamian-code-data-storage-devices.html). Accounting is just a very specific form of recording history.



When money is just the medium of exchange, for most practical purposes it really doesn't matter if someone gives you some MZM, M1, M2, MB or even short term treasury bonds (these days); we seem to understand that intuitively. Where I think this gets confusing is when we think of money as defining the unit of information. This messes with our minds in two ways: 1) when money defines the unit of information, it is dependent on how much medium of exchange is out there and 2) what do we mean by money (M1, MZM, M2, etc)?



Let's attack the first question first. I think it's fairly easy for us to see how money can be a varying unit of measurement. A pound sterling doesn't mean the same thing in 1700s as it does today -- that is we have to go back and covert the weird units British people used in the 1700s called "pounds sterling" into the rather practical units British people use today call "pounds sterling". That is to say, we adjust for inflation. But that adjustment requires knowing a lot about the value of goods and services that were available in the 1700s and today.



The information we're familiar with doesn't work this way. A bit today is a bit in a billion years. We don't have to adjust for infor-flation because there are gazillions of GB out there on the internet. The basic unit of information, the bit = $\ln 2$ "nats", or the information in a flip of a fair coin, is as static as mathematics. We can exchange 8 billion bits and the result is the same the same way we exchange 8 bits \[1\].



In the transfer of economic information, the total amount of money does define the unit of information. To be precise, both the total amount of money and the size of the economy come together to define the unit of information we refer to colloquially as "value". And actually, it's "nominal value", since we'd say a pound of bacon is worth a dollar (money units) in the 1970s and 5 dollars (money units) today.



With constant units of information, changing units is pretty easy. We have





or 1 bit = (ln 2 nat)/(ln 2 nat/bit). To deal with variable units of information we need some tools. The base of the logarithm determines the unit of information and we have the relationships





If the base of the logarithm $b = 2$ we're measuring information in bits. If it's $b = 8$, we're measuring in bytes. We'd like to measure information in terms of money. That means, if $M$ is the amount of money out there and $NGDP$ defines the size of the economy, the unit of information defined by money is





I call this the information transfer index  [here](http://informationtransfereconomics.blogspot.com/2014/03/how-money-transfers-information.html) (or actually its inverse$1/\kappa$), but really it just defines the units of information (i.e. "value") and is connected to the price level (which is how you adjust for inflation). I've referred to the changing value of $\kappa$ as the "unit of account effect"; we could call the basic mechanism in the quantity theory where approximately $P \sim M$ the "medium of exchange effect" analogously.



As for my second question above: _which monetary aggregate?_ Let's leave that up to [observational evidence](http://informationtransfereconomics.blogspot.com/2014/02/models-and-metrics.html). It seems $M$ is the [currency component of the monetary base](http://research.stlouisfed.org/fred2/series/MBCURRCIR) (physical currency including printed bills and coins).



\[1\] At least if are well below the [Bekenstein bound](http://en.wikipedia.org/wiki/Bekenstein_bound). When we start transferring information on the order of the number of bits defined by the causal horizon of the exchange, we'll need to take general relativity into account.



One interesting side note: if we measure information in terms of a fraction of the information in the causal horizon defined by the Hubble volume instead of bits, the Bekenstein bound would become:



$$<br />
I \leq -\frac{RM}{2 \log \ell_{p}H_{0}}<br />
$$


where the constants are the Planck length and the (inverse) Hubble time. This makes the information time dependent in these "natural" units since the Hubble length c/H0 is based on the age of the universe.


\[2\] Actually, a better way to describe _Money as Memory_ is to say that "I have 5 dollars because I did something worth 5 dollars in the past that the community owes me for, and I'm discharging the community's obligation because you are giving me 5 dollars worth of goods or services in return".


**Update (6/8/2014):** Reworded a couple sentences above, added a few lines for clarity and added the second paragraph to the footnote.

**Update (6/14/2014):** Added the second footnote.
