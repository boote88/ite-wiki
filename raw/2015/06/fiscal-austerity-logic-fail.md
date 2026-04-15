---
title: Fiscal austerity logic fail
date: 2015-06-18T19:31:00.002-07:00
updated: 2015-06-18T21:53:54.800-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/06/fiscal-austerity-logic-fail.html
---

I'm still sufficiently angry about [the total analytical garbage](http://informationtransfereconomics.blogspot.com/2015/06/scott-sumner-fails-to-read-third.html) that is [this post by Scott Sumner](http://www.themoneyillusion.com/?p=29692) that I want to write it as pedantic logic:

> **Proposition:** Fiscal austerity is contractionary at the zero bound regardless of whether you have an independent central bank.

Let's get some symbols in here.

_A(X) = ∀x ∈ X, x_ has engaged in fiscal austerity

_I(X) =_ _∀x ∈ X, x_ has an independent central bank

_Z(X) =_ _∀x ∈ X, x_ is at the zero lower bound

_C(X) =_ _∀x ∈ X, x_ has experienced economic contraction



So Sumner's Keynesian view is:



**Proposition**

1\. _A ∧I  ∧ Z → C_

2\. _A ∧¬I ∧ Z → C_



He wants to set out to disprove this pair of statements (i.e. show the proposition is false). One thing he does is throw out all of the countries without independent central bank:



_X = {x | I(x)}_



That basically assumes that _¬I = F₀_ so we have



_A ∧¬I ∧ Z → C_

_A ∧ F₀ ∧ Z → C_

_F₀→ C_

_T₀_



So now statement 2 is a tautology. Remember, Sumner wanted to prove statement the proposition was false! It gets better. Statement 1 becomes:



_A ∧ I ∧ Z → C_

_A ∧ T₀ ∧ Z → C_

_A ∧ Z → C_



But note that in the data we have some countries not at the zero lower bound, i.e.



_{x | ¬Z(x)} ⊆ X_



_Z = F₀_



_A ∧ Z → C_

_A ∧ F₀ → C_

_F₀ → C_

_T₀_



So statement 1 is now a tautology on the set _X_ and Sumner's Keynesian view is:



**Proposition**

1\. _T₀_ _∀x ∈ X_

2\. _T₀_ _∀x ∈ X_

_∴ T₀_ _∧_ _T₀ =_ _T₀_

_QED_



Both statements Sumner set out to show were false are now tautologically true on the data set he selected. Either Sumner is a Keynesian now, he's not convinced by his own logic, or he wasn't using logic.



I'm going with the last one.


**Update:**

There's also the monetarist part:

> **Proposition:** Fiscal austerity is contractionary if you lack an independent central bank. Fiscal austerity would not be expected to have much effect if you have an independent central bank, due to monetary offset.


In symbols:

1\. _A ∧_ _¬__I  → C_
2\. _A ∧_ _I  →_ _¬_ _C_
Now the set _X = {x | I(x)}_ so:

1. _A ∧_ _F₀_  _→ C_
2. _A ∧_ _T₀_  _→_ _¬_ _C_
Simplifying
1. _T₀_
2. _A_  _→_ _¬_ _C_
We've reduced Sumner's statement to whether or not 2 is true. Back in English:

> All countries kept in the data set _X_ engaged in fiscal austerity do no experience economic contraction.

 This means that for all countries exhibiting austerity, there should be no contractionary economic effect. That is (H/T to Tom Brown below for some corrections **in bold**, I said it in words but got sloppy with the symbols):

_∀x_ _∈ X,_ _A(X)_ **_∧_ _¬_ _C(X)_**
Which means that to show monetarism is false, all you need to show is there is one point in the data set that engaged in austerity and experienced contraction, i.e.

_∃ x ∈ X,_ _A(x)_ _**∧**_ **_C(X)_**

_EU_ _∈ X_
_∴_ _∃ x ∈ X |_ _A(x)__**∧**_ **_C(X)_**
_∴ F₀_ 
for statement 2.
_∴ T₀_ _∧_ _F₀_ (statements 1 and 2)

_∴_ _F₀_ (statements 1 and 2)

_QED_


So Sumner not only proved Keynesianism is tautologically true on the set of points he shows (_X_), but that market monetarism is tautologically false. [I guess it is falsifiable](http://informationtransfereconomics.blogspot.com/2015/06/falsifiabilite-simplicite-succes-ou-la.html)!



Sumner's framing of the problem actually backs him into this corner. His assumption that all the data points have independent central banks means that any country engaging in austerity can't experience contraction. It only takes one case! You can weasel your way out through the "would not be expected" qualifier. However, that basically makes statement 2 useless (austerity with an independent central bank may or may not be contractionary) and then you're left with statement 1: fiscal austerity is contractionary if you don't have an independent central bank. Which is exactly the Keynesian view! You'd get no argument from Krugman about that!



Maybe Sumner can throw the EU out of the data set.
