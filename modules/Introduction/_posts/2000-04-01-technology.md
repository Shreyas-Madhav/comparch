---
title: Current Computing Technology
---

![XKCD comic](https://imgs.xkcd.com/comics/log_scale.png)

This section give you some background on historic and modern computing technology.

{% include reading.html section="Chapter 1" %}

{% include reading-grad.html section="Chapter 1" %}

## Turing Lecture

{% include reading.html section="Sections 1.1, 1.2, 1.3" %}

{% include reading-grad.html section="Sections 1.1-1.4" %}

Before diving into anything, I'd like you to take about an hour to watch the Turing Lecture given by John Hennessy and David Patterson.
It's a relatively long video (and the longest I'll ask you to watch), but it's packed full of interesting historical information and future prognostications by two preeminent computer architecture researchers.
The [Turing Award](https://amturing.acm.org/) is the "Nobel Prize of Computer Science."
It's given once a year "for major contributions of lasting importance to computing."

In 2017, the Turing Award was given to two computer architects, John Hennessy and David Patterson (who happened to write your book as well!).
They gave a lecture with the International Symposium on Computer Architecture or ISCA the premiere venue for computer architecture research.
Given that their audience was computer architecture researchers, I don't expect you to understand everything in the lecture.
However, it's great overview of the past, present, and future of the field of computer architecture.
We will come back again and again to the themes presented in this lecture.

<iframe width="608" height="402" src="https://www.youtube.com/embed/3LVeEjsn8Ts" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Computing technology past to present

{% include reading.html section="Sections 1.4, 1.5" %}

{% include reading-grad.html section="Sections 1.5-1.7" %}

Now, let's briefly look at computing architecture history and see how we got to where we are today.
This video describes a brief history of computer architecture and modern process technology.

{% include video.html id="1_fh2rpo26" %}

And, to give this further context, here's an interview with someone who was actually there!
This is an interview with Jean Bartik, one of the first programmers.

<iframe width="560" height="315" src="https://www.youtube.com/embed/aPweFhhXFvY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Moore's Law and Dennard scaling

You all have probably heard of [Moore's Law](https://en.wikipedia.org/wiki/Moore%27s_law) which *doesn't* say "processors get twice as fast every 18 months".
Instead, Moore's Law is an *economic*, not technical, argument that we'll be able to find a way to manufacture twice as many transistors per chip every 12-24 months.
This video discusses Moore's Law and the driver of Moore's Law, [*Dennard Scaling*](https://en.wikipedia.org/wiki/Dennard_scaling).

{% include video.html id="0_xb6nu47m" %}

If you are interested, you can read the [original paper by Moore](https://newsroom.intel.com/wp-content/uploads/sites/11/2018/05/moores-law-electronics.pdf) from 1965.
It's a quick read, and it's interesting to see what a visionary was thinking about back in the 60's!

On the opposite end, there's a good [New York Times article about the end of Moore's Law](https://www.nytimes.com/2011/08/01/science/01chips.html) (subscription or campus VPN required) based on the paper ["Dark Silicon and the End of Multicore Scaling"](https://www.cc.gatech.edu/~hadi/doc/paper/2011-isca-dark_silicon.pdf) by Hadi Esmaeilzadeh, Emily Blem, Renée St. Amant, Karthikeyan (Karu) Sankaralingam, and Doug Burger.

Now that we've discussed Moore's Law and Dennard Scaling, I want to call your attention to a specific part of the Turing Lecture when Hennessy talks about what happens now that Moore's Law is dead.

<iframe width="608" height="402" src="https://www.youtube.com/embed/3LVeEjsn8Ts?start=2192&end=2344" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Hennessy talked about a paper called ["There's Plenty of Room at the Top"](https://science.sciencemag.org/content/368/6495/eaam9744).
If you're interested to read more, you can download the [PDF](https://science.sciencemag.org/content/368/6495/eaam9744/tab-pdf) if you log into the Campus VPN.

## Energy and Power of CMOS Devices

{% include reading.html section="Sections 1.7, 1.8" %}

{% include reading-grad.html section="Sections 1.5" %}

First, let's talk about how to reason about the energy and power of computer chips (also called [CMOS or complementary metal-oxide semiconductor](https://en.wikipedia.org/wiki/CMOS)).
In this video, I talk about some of the key contributing factors to the energy and power of these devices.

{% include video.html id="1_sqskmnog" %}

Finally, let's look at the trends in the past ~50 years or so.
Now that we have an idea of what contributes to the power dissipation of devices, we can see why today's processors aren't as much faster as last year's designs as they used to be.
This video talks about how power and energy relate, how transistors work, and brings in how this caused the end of Moore's Law

{% include video.html id="1_tlwrtx1k" %}

## **QUIZ** CMOS Energy, Power, and Moore's Law

See canvas for the quiz!
