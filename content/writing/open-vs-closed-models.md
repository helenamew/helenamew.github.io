---
title: "Open vs. Closed Models"
date: 2024-04-03
venue: The EI Network
original: https://theeinetwork.substack.com/p/opening-up-about-ai
---

We have very recently seen an increased demand for openness in AI. Much of this has been spurred by the NTIA’s (National Telecommunications and Information Administration) recent [request for comments](https://www.ntia.gov/press-release/2024/ntia-solicits-comments-open-weight-ai-models) on the risks, benefits and potential policy related to advanced “open-weight” AI models. The public call for comments aimed to understand how making model weights widely available could impact our society and security, in terms of both benefits and risks. These comments will shape the NTIA’s report, which will in turn [influence US policy](https://www.aisnakeoil.com/p/on-the-societal-impact-of-open-foundation) on open foundation models. The EU and UK are also actively considering how to regulate open foundation models.

Decisions about openness and transparency in AI will have major implications for the future of open innovation. This week, I’ll be guiding you through this debate: what is ‘open AI’, and is openness something we should welcome or ward off?

## What does it mean for a model to be open, or closed?

A foundational model can be released in two ways. Models may be *closed* if access to them is limited to the interface a developer provides. ChatGPT is a closed model: you get what you’re given. On the other hand, we have *open* models, such as Meta’s Llama 2. When a model is open, the model weights (which form a central building block of AI systems) are given, enabling downstream modifications to occur. Think of it this way: when a model is closed, you’re given a hardened statue – the end product, which is near impossible to modify. When a model is open, you’re given a soft clay statue – the building blocks, which have been crafted for you but are amenable for you to finish off.

It’s worth recognising that things aren’t so simple as an open and closed dichotomy – there are [gradients in between](https://arxiv.org/abs/2302.04844). At one end of the spectrum, we have models which are fully open; at the other end, we have models which are fully closed. In between we have gradual access, hosted access, cloud-based access, and downloadable access. Considering the relative risks and benefits of each of these in-betweens will be essential going forward. But to keep things simple, we’ll be focusing on the risks associated with fully open models.

Fully open models involve relinquishing *all* control over who can use a model once it’s released. Developers could say, “only use this for ethical means” or “do not use this model for A, B and C”; however, once a model is fully open source, malicious actors will be free to ignore any guidelines stipulated – restrictions are incredibly challenging to enforce.

Let’s briefly overview some of the arguments for and against open-source models.

## The goods and ills of open-source models

The openness of AI has formed a central debate in AI policy, and there is widespread disagreement about the relative goods and ills of openness on society. The following will review some of the central risks and benefits to give you a handle on the debate.

### Potential benefits

- **Innovation.** Democratising access would enable developers to build on previous work (it would mean, for example, that a developer could skip a great deal of the training process), thus broadening the availability of AI. Increased accessibility could end up boosting benefits and innovation widely; however, it may also increase the scale of misuse and harms.
- **Transparency.** Open models also play a vital role in helping to drive transparency. When models are open source, researchers, developers and authorities can [“look under the hood”](https://spectrum.ieee.org/open-source-ai-good) of AI systems and better understand them before deploying them.
- **[Distributing who defines acceptable model behaviour](https://crfm.stanford.edu/open-fms/).** When models are closed, developers get to decide what is and what is not acceptable. Open-source models would allow for greater diversity in defining what model behaviour is acceptable, and consequently the needs of a wider range of stakeholders.

### Potential risks

- **Abuse.** Malicious actors may be more able to abuse AI capabilities and cause harm in society: by [building weapons, or creating misinformation campaigns](https://spectrum.ieee.org/open-source-ai-2666932122). These risks deserve to be taken seriously, but we should keep in mind that such risks are not unique to open-source AI models. The idea that technologies may be misused applies to the majority of new innovations.
- **Modifications.** Guardrails preventing models from generating offensive or harmful content might be removed, or [modifications](https://about.fb.com/wp-content/uploads/2024/03/NTIA-RFC-Meta-Response-March-2024.pdf) might make model weights more susceptible to biases.

Striking a balance between the optimal amount of openness or transparency will be a critical challenge for developers and policy makers going forward. We may need to dig beyond the simple ‘open’ versus ‘closed’ framing to figure out the next steps forward; understanding the complexities of these risks and benefits relative to the level of openness or closedness, and in conjunction with the regulations and guidelines accompanying each.
