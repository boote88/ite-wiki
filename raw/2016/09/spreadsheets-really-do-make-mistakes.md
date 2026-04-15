---
title: Spreadsheets really do make mistakes
date: 2016-09-19T18:00:00.000-07:00
updated: 2016-09-19T18:00:08.797-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2016/09/spreadsheets-really-do-make-mistakes.html
---

> _Computers are stupid; they do exactly what we tell them to do. [Excel spreadsheets don't make mistakes](http://davegiles.blogspot.com/2016/09/spreadsheet-errors.html?spref=tw). I do. Like when I accidentally overwrote a number in a cell a few weeks ago. And that's not just in Excel. I have told computers to do stupid things with data in SAS, Visual Basic, Stata, Rats, R, etc. ... See a pattern? It's me. It's us. Not our algorithms._

That's from [Claudia Sahm](http://claudiasahm.postagon.com/9xngxrgw9). Actually if you follow the link to Dave Giles blog (and then the [first link](http://davegiles.blogspot.com/2011/08/beware-of-econometricians-bearing.html) Giles says to read), you will find out that: **no, spreadsheets really do make mistakes**. Here's [an abstract](https://www.jstatsoft.org/article/view/v034i04) from a paper Giles cites:

> _This paper discusses the numerical precision of five spreadsheets (Calc, Excel, Gnumeric, NeoOffice and Oleo) running on two hardware platforms (i386 and amd64) and on three operating systems (Windows Vista, Ubuntu Intrepid and Mac OS Leopard). The methodology consists of checking the number of correct significant digits returned by each spreadsheet when computing the sample mean, standard deviation, first-order autocorrelation, F statistic in ANOVA tests, linear and nonlinear regression and distribution functions. A discussion about the algorithms for pseudorandom number generation provided by these platforms is also conducted. We conclude that there is no safe choice among the spreadsheets here assessed: they all fail in nonlinear regression and they are not suited for Monte Carlo experiments._

This is not input errors, but rather actual errors in the software. Now it is true that the computers were told to do stupid things by the programmers of Excel, &c and as a general philosophy, human error is the source of lots of problems.



But really -- Excel computes things incorrectly even if you program it perfectly.



Now it is probably millions of times more likely that a given error you find is an error you yourself made, but every system out there has issues. Even Mathematica, my go-to math software (as you can probably tell [from my graphs](http://informationtransfereconomics.blogspot.com/2016/09/supply-and-demand-as-causal-entropic.html)), [has some bugs \[pdf\]](http://www.ams.org/notices/201410/rnoti-p1249.pdf).



As always, the solution is to be alert and test results.
