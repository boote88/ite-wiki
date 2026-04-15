---
title: Tractability and scope
date: 2018-08-08T12:00:00.000-07:00
updated: 2018-08-13T12:02:24.528-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/2018/08/tractability-and-scope.html
---

![](<media/brownian PPF pic.png>)

> _Yes, your fantastic model will reproduce all sorts of stuff and will be great at forecasting—for some time, maybe even a long time—, but I will always be able to find some features of reality that will be of some relevance to some people that your model does not capture (as long as it is a model and not a perfect reproduction of reality itself, which I am not sure I would refer to as a model). And, sooner or later, human creativity will produce something that your model cannot forecast. A crisis will happen, and bashers of all types will again be screaming that we have to throw away the entire toolkit and start back from square one._  

That's Fabio Ghironi in his [recent note on tractability](http://faculty.washington.edu/ghiro/GhiroTractability080618.pdf) \[pdf\] that's worth reading. [I chimed in](https://informationtransfereconomics.blogspot.com/2018/04/tractability-for-tractabilitys-sake.html) on this discussion back in April with a different focus. However Prof. Ghironi's take brings me back [to Noah Smith](http://noahpinionblog.blogspot.com/2015/09/a-bit-of-pushback-against-empirical-tide.html):

> _I have not seen economists spend much time thinking about domains of applicability (what physicists usually call "scope conditions"). But it's an important topic to think about._

While this physicist didn't call them scope conditions, the concept is valid enough. One of the questions at my thesis defense was about the scope of the model I was using. I didn't have a great answer \[1\], so the subject has been burned in my brain. Scope defines where the model is valid and where it isn't. Sometimes you have an explicit mathematical representation (Newtonian physics is valid for velocities that are small compared to the speed of light — _v_ << _c_). Sometimes it's more qualitative. I wrote more about scope [in a post from a few years ago](https://informationtransfereconomics.blogspot.com/2015/10/we-built-this-theory-on-scope-conditions.html).



Prof. Ghironi's statement \[of the criticism\] loses a lot of its impact if we have a model with well-defined scope. Sure, you can eventually find a case it doesn't work for — but is it in scope? If no, then it's like saying Newtonian physics doesn't work for relativistic velocities — it's obvious. If yes, then we've learned more about the scope of the model. That's it. We don't have to throw anything away.



The other aspect of scope conditions is that they act like firewalls for your theory or model — just because you find one fact that doesn't agree with your model doesn't mean the entire model is burned to the ground (such that you have to "start back from square one"). There's scope that limits the damage. Quantum mechanics didn't burn down all of the successes of classical physics, just the parts where the change in action _dS_ was comparable to Planck's constant — _dS_ ~ Δ_p_ Δ_x_ ~ ℏ. Real understanding of a model is in understanding its scope. It's true that for a new model, you might not know the scope at first. Over time, empirical and theoretical results will show the limitations (e.g. physics did not know that Newtonian physics even had explicit theoretical scope conditions until Einstein and Planck).



Part of the problem with the ubiquitous DSGE models is that their scope is ill-defined (at least in my reading of the papers). But this issue is not limited to DSGE. What is the scope of [Diamond-Dybvig](https://en.wikipedia.org/wiki/Diamond%E2%80%93Dybvig_model)? What is the scope of a basic supply and demand diagram? One of the benefits of the information equilibrium approach (in my opinion) is that it makes scope more well-defined — an example in [my first paper on the subject](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2894072) derives the IS-LM model and notes that because of the assumptions made in the derivation it only applies when inflation is low (the high inflation limit is effectively the "quantity theory of money"). [I make an empirical case](https://informationtransfereconomics.blogspot.com/2018/01/money-is-aether-of-macroeconomics.html) that "money" (however defined) is only important when inflation is high. With an ill-defined scope, a ([purported](https://informationtransfereconomics.blogspot.com/2018/07/dsge-battle-royale-christiano-v-stiglitz.html)) failure like not being able to forecast the global financial crisis burns the whole theory down like a building with no fire doors.



However! _**Every**_ assumption (even an implicit assumption) that goes into a model becomes (or is related to) a scope condition. Newtonian physics implicitly assumes velocities can be infinite. Given the assumptions that go into DSGE models, maybe they only work near a macroeconomic equilibrium? This is basically the idea behind [David Glasner's discussion](https://uneasymoney.com/2013/10/25/microfoundations-aka-macroeconomic-reductionism-redux/) of "macrofoundations" of micro. I've actually made a case that representative agents and utility may only be in-scope near equilibrium (see [here](https://informationtransfereconomics.blogspot.com/2016/02/one-more-physics-analogy.html), [here](https://informationtransfereconomics.blogspot.com/2015/09/the-emergent-representative-agent-1.html), and [here](https://informationtransfereconomics.blogspot.com/2015/03/utility-in-information-equilibrium-model.html)) — but they are in-scope under those conditions and therefore useful concepts. This may not be comforting to many people, per Keynes famous quote:

> _In the long run we are all dead. Economists set themselves too easy, too useless a task, if in tempestuous seasons they can only tell us, that when the storm is long past, the ocean is flat again._

If DSGE models are only valid near the E, then maybe they're not useful for understanding major recessions. Of course, this means that a major recession wouldn't invalidate the model — it'd just be out of scope.



This brings us back to the assumptions made for tractability — what scope do they set and where do those assumptions break down? If the assumptions made in order to make your model tractable limit the scope of your model to an epsilon-sized ball in an _n_\-dimensional space, what use is the fact that the mechanisms are now accessible and understandable? In that sense, assumptions made for tractability need to be understood in terms of the scope they limit \[2\]. For example, the transversality conditions that make the [RCK model](https://en.wikipedia.org/wiki/Ramsey%E2%80%93Cass%E2%80%93Koopmans_model) tractable (i.e. yield sensible solutions) [can be seen as the entire economic content of the model](https://informationtransfereconomics.blogspot.com/2015/06/the-importance-of-transversality.html) (with the rest just being "accounting") effectively yielding a result with zero scope (i.e. the RCK model is invalid outside of the saddle path). That's just a basic econ example, and I think I will try to explain using a more relevant example in a future post.



...



**Footnotes:**



\[1\] It was complicated because there was an explicit scope that involved the [large-_Nc_ approximation to QCD](https://www.jlab.org/hugs/archive/Schedule2012/Thursday14/cordon_talk.pdf) \[pdf\], an explicit scale set by [the regulator](https://en.wikipedia.org/wiki/Pauli%E2%80%93Villars_regularization), and an additional scope limitation derived from the lack of [confinement](https://en.wikipedia.org/wiki/Color_confinement) that was more qualitative (i.e. not well understood because it is more an empirical fact that is consistent with QCD but not explicitly derived in it — there is an "effective force" that increases linearly with distance implying that as quarks separate they would have to generate almost infinite energy to become "free" but this isn't the same thing as theoretically proving confinement from an _SU(3)_ Yang Mills gauge theory).

\[2\] Putting my money where my mouth is, there are several assumptions that go into the information equilibrium approach — agents explore the state space ("ergoditicy"), the number of transactions or agents are very large, the time spent in non-equilibrium states like recessions is short compared to the time series data (particularly for the shocks in the dynamic equilibrium approach). These all limit the scope.
