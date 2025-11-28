---
layout: post
title: Reflections on Starting Out as a Young Researcher in a Rapidly Changing World
date: 2025-11-27 12:00:00
description: Thoughts on how to do great research in a world where the capabilities of AI models grow quickly.
tags: research ai reflection
categories: blog
featured: false
---

As I am starting out as a young researcher, I naturally have many questions about how to do great research.

One of the most famous pieces of advice on this topic is Hamming's talk titled '[You and Your Research](https://www.cs.virginia.edu/~robins/YouAndYourResearch.html)'. In his talk, he among other things argues that great scientists

- have a tremendous drive and work very hard,
- work on important problems by regularly asking themselves what the most important problems are and then having the courage to pursue them,
- and are good at selling their work, collaborating with others, and working with the system rather than against it.

I think that developing these traits and practices is very relevant to this day, if one wants to do great research. At the same time, the question that occupies my mind a lot these days goes slightly further:

> What additional considerations matter for doing great research in *our rapidly changing world*?

## What I mean by 'great research' and 'a rapidly changing world'

Taking a step back, like Hamming, by 'great research' I mean the kind of research that years later is perceived as significant. I believe that most people reading this will have a reasonably clear idea of what it means when work is considered to be significant, though it is of course a lot harder to judge that at the time the work is done.

**When I refer to our 'rapidly changing world', what I primarily mean is the world we will experience over the next five to ten years as the capabilities of AI models grow.** Already today, models are able to reason through relatively complex problems and to work on multi-step tasks (e.g., internet research, software development) using a palette of tools. We are also seeing first signs of models being able to directly [accelerate scientific work](https://cdn.openai.com/pdf/4a25f921-e4e0-479a-9b38-5367b47e8fd0/early-science-acceleration-experiments-with-gpt-5.pdf) and signs that the US government is interested in further increasing these abilities through [coordinated national efforts](https://www.nature.com/articles/d41586-025-03890-z). It does not currently seem to me as if the growth in model capabilities will be slowing down anytime soon, and I personally believe that models are likely to reach a level where they can automate the vast majority of the currently ongoing scientific work within the next 5-15 years.[^1][^2]

Even if growth is slower or if we do not eventually get to the level of capabilities where we can automate all scientific workflows, I very strongly expect that we will in the next few years develop tools that automate *many parts* of the scientific process.

## Do rapid developments change *what makes* research significant?

> Imagine going out for dinner with your (ex-)scientist friends in 10 years. One of your friends asks what you think was the most important research that was done in your field in the last decade. You pause for a bit and start thinking.

Generally, I do not think that what makes research significant will change drastically from what has historically mattered. Making previously impossible-to-answer questions tractable, connecting seemingly disparate fields, resolving fundamental puzzles in relevant fields, or developing new methods that enable a lot of further research will all remain important.

At the same time, there are at least two (rough) kinds of research that I think will become *more important* over the next years.

Firstly, I think research that enables the scientific community and society to better ensure that rapidly developing new technologies do not lead to major harm will become increasingly important.[^3] This similarly applies for work that helps to make sure that the increasing number of scientific results being produced are [reproducible](https://en.wikipedia.org/wiki/Replication_crisis) and robust.[^4]

Furthermore, in the spirit of [the bitter lesson](https://www.cs.utexas.edu/~eunsol/courses/data/bitter_lesson.pdf), I believe that research that develops methods which are able to efficiently leverage resources that will become abundant over the next years – such as *automated reasoning, compute, and (synthetic) data* – will become more important. On the flip side, this also means there is increased danger of work becoming obsolete at or even before the end of its development. This can happen when massively more resources, which the work does not efficiently leverage, have become available by the time the it is completed.

## How will the approaches *to do* great research change?

> Imagine you are sitting in your office several years from now a few days before Christmas. You feel like the past year was by far the most productive in your scientific career and that you were able to put out research that you think will have a lasting impact. You start to reflect on what the approaches were that enabled you to be as productive in the last year.

While I expect what makes research significant not to change drastically over the next decade, I think the approaches to do great research will change a great deal.

On a high level, my view is that **approaches to doing great research should focus increasingly on *effectively* leveraging the aforementioned resources (automated reasoning, compute, and data) that will become massively more abundant over the next years**. Here, I emphasize the *effectively* since I believe that it will often not be very clear over the next years how to get the most benefits from these resources.

{% include figure.liquid path="assets/img/leveraging_the_tools.png" caption="Approaches to doing great research should increasingly focus on leveraging the resources (such as automated reasoning) that will become massively more abundant over the next years. But it is important not to overdo it and to focus on using them effectively. (Image generated using Nano Banana Pro.)" %}

Practically, I think leveraging the new resources available will amount to using new or existing products (such as LLM-Chatbots, AI Coding Agents, Literature Research Tools or platforms for compute orchestration) or building your own software/hardware to support parts of your research process.

Figuring out how to leverage these tools *effectively* though will likely be lot harder.

**The most important step in finding out what works will likely be to do a significant amount of experimentation.** Given how fast things are moving, I would argue that one should probably constantly be experimenting a bit and should be open to frequently changing one's research processes. Having a community of good researchers going through the same process, who can support each other and share insights on using new tools, will definitely be very helpful. Furthermore, drawing inspiration from friends who are not involved in research directly, but are also in the process of figuring out how to make the most of the new capabilities, can also be very valuable.

**When reflecting specifically on your usage of new *AI models*, I think one particularly relevant aspect to consider is which complementary strengths you currently have or want to develop.** I believe you should evaluate these both in comparison to current and future models, and relative to other researchers who are also using them. In comparison to models, some general complementary strengths good researchers have and will likely retain in the coming years are, in my view, better judgement in (a) determining which questions are worth pursuing and (b) selecting approaches to solve sub-problems, as well as (c) learning in real-time and applying that new understanding to current and future problems, and (d) high-quality writing.

Since it is pretty hard to think about how to use the new tools effectively 'to do great research', **I believe a reasonable proxy to often optimize for is getting more ambitious research results faster** (where results can mean empirical findings, theoretical insights, or simply a deeper understanding). More ambition hopefully leads to working on more important questions, while getting faster results leads to you being able to profit more from the [compound interest](https://en.wikipedia.org/wiki/Exponential_function) of your work.

As a last point of warning, **two failure modes to avoid when using these new tools are producing more research rather than better research, and failing to develop a deep enough understanding of the details of your work.** The latter point, in my opinion, is especially easy to fall into and bears the risk that a lack of deep understanding prevents you from developing good judgement on problems and approaches to them that might ultimately form your comparative advantage over AI models.[^5] It might also leave you unable to verify in detail whether results are correct in the future.

## Concluding thoughts

Reflecting on the fact that I am starting out as a researcher in a rapidly changing world often feels weird (and sometimes even scares me a bit). To be honest, I have no idea what exactly my job will look like at the end of my PhD. At the same time, I also feel extremely grateful for being able to take part in shaping how science will be done and for living through these very exciting times, in which we might be able to understand our world more deeply and develop more powerful tools to shape it than ever before!

---

*Thanks to Jennifer Zhang and Kilian Pschierer for feedback on drafts of this post. Thanks also to Jascha Sohl-Dickstein, whose [talk on this topic](https://x.com/jaschasd/status/1972360405885637021) inspired some of the thoughts in this text.*

[^1]: I believe that we will be able to automate work that can be done solely on a computer faster than research that requires physical interaction (e.g., running experiments in a wet lab). Nevertheless, I think it is likely that we will be able to automate both kinds of work within the next 5-15 years.

[^2]: Note that if we reach a level where AIs can automate most scientific work, this would not necessarily mean that all scientific work will only be done by AI models. For example, humans might still have an advantage in some parts of the scientific workflow, or from a societal perspective, we might still want humans to have the final say in certain decisions and/or to verify results.

[^3]: By new technologies potentially leading to major harm, I mean harm that might come from widespread usage of a technology without sufficient deliberation, from malicious use, or from unintended malfunctions. Areas in which advances might lead to such harm include, for example, biotechnology, geoengineering, or advances in AI capabilities directly (potentially leading to [catastrophic risks](https://yoshuabengio.org/2024/07/09/reasoning-through-arguments-against-taking-ai-safety-seriously/) or [gradual disempowerment](https://gradual-disempowerment.ai/)).

[^4]: Note that the generation of more research results might offer a natural opportunity for better reproducibility checks, since new results building upon or comparing to old results will often require reproducing previous findings in slightly perturbed settings.

[^5]: The question of where to draw the line between failing to develop the deep understanding needed to improve your judgement, and not using new capabilities enough to get feedback on that judgement, is a hard but important one.

