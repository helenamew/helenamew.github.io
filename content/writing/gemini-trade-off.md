---
title: "Veracity Versus Variety: Gemini’s Trade-off Mishap"
date: 2024-03-06
venue: The EI Network
original: https://theeinetwork.substack.com/p/generating-a-responsible-future
---

Last week, representatives from Google, Microsoft, and others gathered for the Mobile World Congress (MWC24), beginning conversations on the responsible deployment of artificial systems. The recent rise of generative AI tools poses a hoard of ethical questions, and recent events with Google’s image generator – [Gemini AI](https://blog.google/technology/ai/google-gemini-ai/#performance) – formed a central part of these conversations.

**What is Gemini?** We can think of Gemini as Google’s version of ChatGPT – in response to text prompts, Gemini generates text and images. Gemini was formerly known as Bard – a name change following the addition of image generation.

**What happened?** Google recently faced backlash, as viral posts exposed the generator creating historically inaccurate and over-representative images: ask it for a ‘historically accurate depiction of a medieval British king’ and you get a woman; ask for images of the ‘US founding fathers’ and you get a black founding father; ask for images of German soldiers during World War Two, and you get Asian soldiers in the same uniform. In these cases, the image generation tool failed to accurately portray historical figures.

It wasn’t only the inaccuracy of the model being scrutinised – some users reported Gemini refusing certain prompts, where requests explicitly asking for an image of someone of white descent (including historical figures) were declined.

Google immediately apologised, writing a blog post titled [‘Gemini image generation got it wrong. We’ll do better’](https://blog.google/products/gemini/gemini-image-generation-issue/). They have since paused the tool and are working on ‘improving the accuracy of its responses’. So, what went wrong? Google explained that they were trying to *avoid* creating violent or sexually explicit images, while trying to *programme* diversity into Gemini’s responses. Let’s unpack this.

## Veracity versus variety – a trade-off

Getting the outputs that we want will involve a careful balancing act, with veracity on the one hand and variety on the other.

In some cases, we want diverse outputs, rather than true ones. When we ask for a ‘leader’ we would probably be unsurprised to see a white man – we live in a world in which most ‘leaders’, whether in spirit or the CEOs of companies, are male and white. There’s a sense in which we’d want our technology to accurately reflect the way the world is. On the other hand, if we let our technologies reflect the way the world is, our tools may end up reinforcing gender stereotypes. Our technologies should embody a more representative ideal world, with leaders from a variety of underrepresented genders and races. Diversity, rather than accuracy, seems more important in this case.

In other cases, we may want accurate outputs, rather than diverse ones. When I ask for a black male teacher, then the output should be a black teacher, not a white woman. And when I ask for an individual in a particular historical or cultural context, such as the requests for German soldiers in World War Two, then the output should reflect this context. We want our images to be historically accurate – giving Asian soldiers, or women, in this context feels somehow over politically correct.

So, in trying to account for one problem – namely, the tendency of algorithms to replicate existing structural biases – Google seems to have created another. There’s a tension, then, between (1) wanting to be representative, and (2) wanting to be accurate.

The Gemini debacle raises an important number of questions, which aren’t so easy to answer. How we approach these complications will depend on what kinds of outputs we want to prioritise. What sorts of values do we want our technologies to embody? How should our technologies represent and remember history? Should we promote variety, or veracity? Answering these questions won’t be easy – this is in part because our answers will depend on what we’re using the technologies for. Generative AI tools like Gemini and ChatGPT can be used as creativity and productivity tools, but they can also be asked to represent the way the world is, and it’s unclear how we might programme these tools to serve one end, and not the other. One option could be to give users greater input – having the option to request, when filling out the text prompt, whether they are after a historically accurate or diverse output.

Time and time again, we see companies retrospectively apologising for mishaps, instead of proactively ensuring a tool is ready before it is released.

## What should we learn from this?

- [Testing our models and gathering user feedback is essential](https://www.linkedin.com/pulse/gemini-incident-call-ethical-ai-development-brandon-donnelly-tknse/).
- Any tool – whether used in healthcare, or open source – should go through a rigorous testing process, scrutinising outputs for accuracy on the one hand and bias on the other.
- Part of this validation process will depend on some idea of the kinds of values and principles we want a technology to embody, which will in turn depend on what we want it to be used for.
- Having set processes for iterative cycles of improvement will also be imperative. Technologies – especially those intended to have a wider user base – should have clear channels for feedback and built-in processes for adjusting technologies to reflect concerns.
