---
title: The information transfer model
date: 2013-04-24T15:57:00.001-07:00
updated: 2013-04-24T16:19:22.230-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2013/04/the-information-transfer-model.html
---

![](<media/transfer system.png>)



We will describe the economic laws of supply and demand as the result of an information transfer model. Much of the description of the information transfer model follows \[1\].



Following Shannon \[3\] we have a system that transfers information $I_q$ from a source $q$ to a destination $u$ (see figure above). Any process can at best transfer complete information, so we know that $I_u \leq I_q$.



We will follow \[1\] and use the Hartley definition of information $I= K^s n$ where $K^s=K^0 \log s$ where $s$ is the number of symbols and $K^0$ defines the unit of information (e.g. $1/\log 2$ for bits). If we take a rod of length $q$ (process source) and subdivide it in to segments $\delta q$ (process source signal) then $n_q=q/\delta q$ and we get (defining $\kappa = K_{u}^{s}/K_q^s$ the ideal transfer index)

$$(1) \space \kappa \frac{u}{\delta u} \leq \frac{q}{\delta q}$$

Compared to paper \[1\], we have dropped the absolute values in order to deal with positive quantities $q$, $u$ (and changed some of the notation, e.g. $\Delta q \rightarrow q$).



Now we define a process signal detector that relates the process source signal $\delta q$ emitted from the process source $q$ to a process destination signal $\delta u$ that is detected at the process destination $u$ and delivers an output value:

$$(2) \space p =\left(\frac{\delta q}{\delta u}\right)_\text{detector}$$

If our source and destination are large compared to our signals ($n_q , n_u \gg 1$) we can take $\delta q \rightarrow dq$, we can re-arrange the information transfer condition:

$$(3) \space p=\frac{dq}{du} \leq \frac{1}{\kappa} \frac{q}{u}$$

Next, we derive supply and demand using this model.



**References**





\[1\] Information transfer model of natural processes: from the ideal gas law to the distance dependent redshift P. Fielitz, G. Borchardt http://arxiv.org/abs/0905.0610v2

\[2\] http://en.wikipedia.org/wiki/Gronwall's\_inequality

\[3\] http://en.wikipedia.org/wiki/Noisy\_channel\_coding\_theorem#Mathematical\_statement

\[4\] http://en.wikipedia.org/wiki/Entropic\_force

\[5\] http://en.wikipedia.org/wiki/Sticky\_(economics)
