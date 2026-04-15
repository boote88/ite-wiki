---
title: Money is the aether of macroeconomics
date: 2018-01-21T14:04:00.003-08:00
updated: 2018-01-21T14:04:52.260-08:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2018/01/money-is-aether-of-macroeconomics.html
---

So I've never really understood Modern Monetary Theory (MMT). In some sense, I can understand it as a counter to the damaging "household budget" and "hard money" views of government finances. To me, it still cedes the equally damaging "money is all-important" message of monetarism and so-called Austrian school that manifests even today when a "[very serious person](https://krugman.blogs.nytimes.com/2012/02/12/very-serious-question/)" tells you it's really the Fed, not Congress or the President that controls the path of the economy and inflation when neither inflation nor recessions are well-understood in academic macroeconomics. People have a hard time giving up talking about money.



Austrian school? Yes. Austrian school. This dawned on me some time ago when I read [Noah Smith's steps](http://noahpinionblog.blogspot.com/2014/03/the-finance-macro-canon.html) for combating the monetary "hive mind" he says is pervasive in finance:

> _So how does one extract an individual human mind from this hive mind? That is always a tricky undertaking. But I've found two things that seem to have an effect:_ 

> _Method 1: Introduce them to [MMT](http://neweconomicperspectives.org/2013/04/modern-monetary-theory-overview-part-1.html). MMT is a great halfway house for recovering Austrians._

It does make sense to think of MMT as a way for an Austrian school devotee to wrap their head around quantitative easing not causing inflation without abandoning too many priors. They just have to nudge their target for the "right" amount of inflation a bit higher (or even just to the Fed's ostensible target of 2%).



I came [across a link](https://modernmoneybasics.com/facts/) in several places in my Twitter feed the other day (which is why I decided to write this post) that's actually a really good explainer of MMT. It also helps explain this connection to Austrian school economics. Read these two quotes; first: 

> _Money is created effortlessly every day on computers in large numbers. It’s our access to real resources that is limited._

and second:

> _As the issuer of the currency, governments have the ability to out-bid any private sector business or even control sectors of the economy, such as education, public infrastructure or health care (nations choose varying approaches). Governments should be held accountable to act responsibly when competing for certain scarce resources in the economy to avoid undesired levels of price escalation._ 

> _At the same time, governments have too often been guilty of the opposite problem – not managing the currency in a way that maintains domestic full employment and acceptable base living standards._

Now read Ludwig von Mises :

> _In theoretical investigation there is only one meaning that can rationally be attached to the expression Inflation: an increase in the quantity of money (in the broader sense of the term, so as to include fiduciary media as well), that is not offset by a corresponding increase in the need for money (again in the broader sense of the term), so that a fall in the objective exchange-value of money must occur._

In both cases, money is simply a tool to move real resources (i.e. the real goods and services money is needed for). The question of inflation then becomes a question of whether there are too many or not enough real resources to be moved with money, as well as a level of inflation we define as "right" (with traditional Austrians usually going for 0% and MMT-ers going for something like 4% or more). The other conclusions generally follow from this (e.g. a sovereign government can never run out of its own currency, only produce excessive inflation in MMT). And if inflation hit 10% or more, both MMT and Austrian economics could find themselves on the same page. To put in physics terms, the theories converge as inflation becomes large compared to the (inverse) length of business cycles.



I'm not saying these movements are politically aligned — Austrians tend to be more conservative and MMT-ers more liberal. The issue here is that where these theories converge (at high inflation) is also the only place where they're supported by empirical data. Inflation really seems to be proportional to whatever you might think of as money when inflation is high. As we'd say in physics, it's a great [effective theory](https://en.wikipedia.org/wiki/Effective_theory). But at moderate levels of inflation, the theory breaks down. As I wrote [in my post on what to do when your theory is rejected](https://informationtransfereconomics.blogspot.com/2018/01/what-to-theorize-when-your-theorys.html), we should set a scale (inflation ~ 10%/y or 10 years, remarkably comparable to the observed period between recessions) and let our imaginations run wild with whatever model fits the data, not blindly apply a high inflation theory to low inflation. Constraining us to thinking about "money" is tying our hands.



So instead of saying "money is just a tool for moving real resources, therefore money is all-important to the economy", what if we say "money is just a tool for moving real resources, therefore (except in extreme circumstances) _**money doesn't matter**_"?



Usefully, these views turn out to be transparently expressed in the [information equilibrium framework](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3094757). This framework allows me to more precisely write down what it means for something to move distributions of real resources around — which is equivalent to moving _the information specifying the distributions_ around. Claude Shannon invented the field that studies this specific subject (information theory), and I think the idea that "money" (whatever you mean by it) [is most fruitfully thought of as medium of information flow](https://informationtransfereconomics.blogspot.com/2017/09/my-introductory-chapter-on-economics.html). Let's consider aggregate demand and aggregate supply, assuming they match in equilibrium. We can then say:



(1) _P ≡ ∂AD/∂AS = k AD/AS_



We can introduce "money" _M_ by using the chain rule \[0\] in calculus plus _M/M_ = 1:



(2) _(∂AD/∂M) (∂M/∂AS) = k (AD/M) (M/AS)_



Here, "money" is simply functioning as a tool moving "real resources" _AS_. You could insert anything in that equation: _B_ for bonds or bitcoin. Or _G_ for government debt. If aggregate demand and aggregate supply are in information equilibrium, and money is in information equilibrium with demand, then money is in information equilibrium with supply, i.e.



(3a) _∂AD/∂M = k₁ AD/M_



Implies



(3b) _∂M/∂AS = k₂ M/AS_



By dividing Eq (2) by Eq (3a). Note that the left hand side of (1) is the exchange rate for a piece of the aggregate economy —  i.e. the price level _P_. Now Eq (1) tells us 



log _AD_ ~ _k_ log _AS_ 



as well as 



log _P_ ~ (_k −1_) log _AS_. 



If we define _AD_ ≡ _P Y_ to use a common symbol in economics for real output (_Y_), then we find — using the right hand side of Eq (1):



_

_AD ≡ P Y = k (AD/AS) Y_

_



so AS = k Y



That is to say "real output" is directly related to "real resources" in equilibrium. But Eq (3a) also tells us that log _AD_ ~ _k₁_ log _M_ which means that if "money" grows rapidly compared to real resources _AS_ (i.e. _Y_ is approximately constant), we also find



(4) log _P_ ~ _k₁_ log _M_



This latter relationship requires a disequilibrium between money and real resources (_AS_) because the equilibrium allowing us to write (3a,b) also implies log _Y_ ~ log _AS_ ~ _(1/k₂)_ log _M_ making



(5) log _P_ ~ _(k₁ − 1/k₂)_ log _M_



reducing the inflation rate in (4) — and in fact requiring some [strong restrictions](https://informationtransfereconomics.blogspot.com/2017/11/why-k-2.html) on the form of M (and the relationship between _k₁_ and _k₂_) if _AD_ and _AS_ are in equilibrium. Basically, the quantity theory of money as well as money being the source of inflation requires the disequilibrium between money and real resources both Austrian and MMT devotees claim. That's the nugget of truth. But empirically (4) is only roughly true for economies where inflation is well above 10% where M is identified with base money.



But since _M_ was arbitrary (it is introduced via two mathematical identities), the typical case of an economy near equilibrium —  i.e. not in recession or experiencing hyperinflation per Eq (4) —  should be independent of an arbitrary redefinition of the medium of information flow. Whether we say we exchange work for money and then money for goods, or we just exchange work for goods doesn't matter unless you're in hyperinflation or recession. You might say the latter is extremely important, but it turns out economies aren't in recession most of the time (a few quarters every ~ 8 years for the US \[1\]) so most of the inflation that happens isn't monetary \[2\]. 



Whatever you think money is, it doesn't really matter.



At least if you're not in hyperinflation or possibly right in the moment of a financial system seizing up as some theories of the financial crisis shock of 2008 propose.



That's the conclusion we should be drawing from the idea that money is "just a tool" to move information about real resources around. Much like how air doesn't really matter to the transmission of sound waves under typical conditions in a room (all the physics of molecules and thermodynamics is subsumed into a constant speed) —  it's just a tool to move vibration information from one point to another —  money appears to have little to do with the bulk of inflation from what empirical data is available. In fact, the inflation rate went right through the financial crisis with nary a blip right when commercial paper —  one of the major mechanisms by which large payrolls are funded —  lost its moneyness.



So what is inflation if it's not monetary? As Noah says in his post linked above that inflation is "one of the biggest mysteries of macroeconomics". My intuition is telling me that inflation is demographic —  [the shocks to inflation are contemporary with or follow shocks to the labor force size](https://informationtransfereconomics.blogspot.com/2017/07/a-dynamic-equilibrium-history-of-united.html) ([coupled with the structure of the fading Phillips curve](https://informationtransfereconomics.blogspot.com/2017/09/was-phillips-curve-due-to-women.html)). Shocks to the monetary base **_follow_** the shocks to inflation. You can also read [Steve Randy Waldman's account](http://www.interfluidity.com/v2/4706.html). Social factors leading to the baby boom and women entering the workforce were the likely real drivers of inflation (i.e. "real resources" like labor that money was just a tool to help move around), and money was just along for the ride.



Regardless of whether you like the information equilibrium take or whether you find it useful, the key fact is that inflation —  except in cases of hyperinflation —  empirically isn't related to "money" regardless of what you think money is \[3\]. The "money is all important" view —  regardless of your pet theory of money —  is based on a facile extrapolation from a completely different regime \[4\]. That view might be what's behind all these various measures of "money": money **_has_** to be important to unemployment and inflation, therefore some measure **_must_** exist that makes the correlation manifest. _M1? No, M2! Interest rates! No, it's government debt! No! It's NGDP expectations!_



It's all reminiscent of the aether in physics. _Something **must** be the medium in which light waves oscillate! Aether dragging! No, partial aether dragging! Really, the aether is just a tool to move electromagnetic energy around._



Money is the aether of macroeconomics \[5\].



**

**Footnotes**

**



\[0\] The [chain rule is](https://en.wikipedia.org/wiki/Chain_rule) _dy/dx_ = _(dy/dz) (dz/dx)_.



\[1\] I don't want to be flippant about the actual human suffering in recessions, but I think it is better for that suffering in the long run to have empirically accurate theory that can yield real solutions than dubious monetary maxims that claim to help.



\[2\] "Most" of the inflation in post-war US economic history was caused by [a large shock centered in the late 70s](https://informationtransfereconomics.blogspot.com/2018/01/is-low-inflation-ending.html). Aside from that period, inflation has been roughly constant at approximately 2.5% (CPI all items) or 1.7% ([core PCE](https://informationtransfereconomics.blogspot.com/2017/03/the-quantity-theory-of-labor-and.html)).



\[3\] Unless you think money is people, which is a slogan I could get behind —  at least in terms of empirical data.



\[4\] Some theories say that hyperinflation is actually a political phenomenon, meaning even there the correlation between money and inflation may be subordinate to the actual process.



\[5\] I am probably trolling here more than I should be, but it really doesn't put me that far from [Paul Romer](https://paulromer.net/the-trouble-with-macro/) who wrote up a menagerie of terms for economic concepts including aether and phlogiston.
