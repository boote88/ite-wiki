---
title: Principal component analysis of state unemployment rates
date: 2017-05-19T12:48:00.005-07:00
updated: 2017-05-19T12:48:58.221-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2017/05/principal-component-analysis-of-state.html
---

One of my hobbies on this blog is to apply various principal component analyses (PCA) to economic data. For example, [here's some jobs data by industry](http://informationtransfereconomics.blogspot.com/2017/03/principal-component-analysis-of-jobs.html) (more [here](http://informationtransfereconomics.blogspot.com/2017/03/using-pca-to-remove-cyclical-effects.html)). I am not saying this is original research (many economics papers have used PCA, but a quick Googling did not turn up this particular version).



Anyway, this is based on seasonally adjusted FRED data (e.g. [here](https://fred.stlouisfed.org/series/WAUR) for WA) and I put the code up in the [dynamic equilibrium repository](http://informationtransfereconomics.blogspot.com/2017/02/information-equilibrium-code.html). Here is all of the data along with the US unemployment rate (gray):



![](<media/state unrate PCA 1.png>)

It's a basic [Karhunen–Loève](https://en.wikipedia.org/wiki/Karhunen%E2%80%93Lo%C3%A8ve_theorem) decomposition (Mathematica function [here](https://reference.wolfram.com/language/ref/KarhunenLoeveDecomposition.html)). Blue is the principal component (first principal component), and the rest of the components aren't as relevant. To a pretty good approximation, the business cycle in employment is a national phenomenon:



![](<media/state unrate PCA 2.png>)

There's an overall normalization factor based on the fact that we have 50 states. We can see the first (blue) and second (yellow) components alongside the national unemployment rate (gray, right scale): 



![](<media/state unrate PCA 3.png>)

Basically the principal component is the national business cycle. The second component is interesting as it suggests differences in different states based on the two big recessions of the past 40 years (1980s and the Great Recession) that go in opposite directions. The best description of this component is that it represents that some states did much worse in the 1980s and some states did a bit better in the 2000s (see the first graph of this post).



As happened before, the principal component is pretty well modeled by the [dynamic equilibrium model](http://informationtransfereconomics.blogspot.com/2017/01/dynamic-equilibrium-presentation.html) (just like the national data):



![](<media/state unrate PCA 4.png>)

The transitions (recession centers) are at 1981.0, 1991.0, 2001.7, 2008.8 and a positive shock at 2014.2. These are consistent with the national data transitions (1981.1, 1991.1, 2001.7, 2008.8 and 2014.4).
