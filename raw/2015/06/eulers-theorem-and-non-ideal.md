---
title: "Euler's theorem and non-ideal information transfer"
date: 2015-06-13T18:52:00.001-07:00
updated: 2015-06-13T18:52:52.600-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2015/06/eulers-theorem-and-non-ideal.html
---

![Leonhard Euler and Claude Shannon.](media/euler-shannon.jpg)

[Dietrich Vollrath has a handy framework](https://growthecon.wordpress.com/2015/06/13/what-assumptions-matter-for-growth-theory/) for looking at the issues I looked at [here](http://informationtransfereconomics.blogspot.com/2015/06/eulers-theorem-rival-inputs-and.html) about Romer's discussion of Euler's theorem and rival inputs:

> _1\.  Output is constant returns to scale in rival inputs_
>
> _2\.  Non-rival inputs receive some portion of output_
>
> _3\.  Rival inputs receive output equal to their marginal product_ 

> _Pick two._ 

> _Romer’s argument is that (1) and (2) are true. (1) he asserts through replication arguments ..._

In my post I argued that (1) is generally not true because replication arguments assume replication of non-interacting things, indistinguishable things or effectively infinite things.



Now, I'd like to show in the information transfer framework that you don't have to pick two (Euler's theorem doesn't tell you anything) -- even if we let (1) be true. Let's start with a production function $Y(R, N)$ where $Y$ is output, $R$ are the rival inputs and $N$ are the non-rival inputs. Therefore we can say:




















If we take the equality sign in equation (d), then yes, (1), (2) and (3) cannot be simultaneously true (only two can be true at the same time). But if we take the greater than sign in equation (d) we can say:






where $w = \partial Y/ \partial R$, $p&gt;0$ and $\alpha = 1$. All three of (1), (2) and (3) are simultaneously true!



Where this comes from in the information transfer framework is the idea that wage (or price) of $R$ doesn't necessarily reflect the final value of $R$ -- i.e. $V(R) \geq w R$. Maybe there is a behavioral economics reason for this (the endowment effect comes to mind). Maybe there are other reasons (e.g. the computer cluster in [this post](http://informationtransfereconomics.blogspot.com/2015/06/eulers-theorem-rival-inputs-and.html)). The information transfer framework doesn't explain what is happening when the information $I(Y) \geq I(R)$ ... it just allows it to happen.



And a lot of the time you can get away with $I(Y) \approx I(R)$, but invoking Euler's theorem as a theoretical constraint requires ideal information transfer $I(Y) = I(R)$ even if you force $\alpha = 1$.
