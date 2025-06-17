# Theoretical Abilities and Limitations of Language Models

LLM have amazing capabilities, but also hallucinate and make reasoning mistakes. Can we understand these abilities and limitations theoretically, as way to figure out ways of overcoming them?
The incredible scale of current LLMs makes this a daunting prospect. However, recent research has developed mathematical understanding sheeding light on questions such as:

* Why do LLMs struggle with tasks (e.g., multiplying 6-digit numbers) that a simple calculator can perform easily? 

* Which problems can be solved by a transformer in one step? Which require a chain-of-thought? How long does a chain-of-thought have to be?

* Which kinds of problems is a transformer likely to generalize on well?

* What are differences between transformers and other architectures (e.g. state-space models)?

* What possible future architectures -- if any -- could replace transformers as the backbone of LLMs?

* Assuming that AGI can be realized by scaling current LLM architectures, what kind of abilities could we expect from this AGI?

Research on these questions draws on fields such as computational complexity, formal language theory, and statistical learning theory.

This seminar will not presuppose knowledge of any of these fields. However, a willingness to engage with technical content is important.

We will discuss recent research papers, both from our own group and from other groups. A lot of this content is highly technical, and it is absolutely fine if you do not understand everything in the paper you'll present. Our focus will be on discussing high-level take-aways for understanding the (in)abilities of current AI systems, and prospects for future developments.

# Syllabus

TBD. A few relevant papers. We will expand this.

Formal languages:

* Survey by Strobl et al https://arxiv.org/abs/2311.00208

Difficulty of Parity:

* Hahn https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00306/43545/Theoretical-Limitations-of-Self-Attention-in

Bound by TC0:

* Merrill et al https://arxiv.org/abs/2207.00729

Benefit of Depth:

* Merrill et al https://arxiv.org/abs/2503.03961

Chain of Thought:

* Li et al, https://openreview.net/forum?id=3EWTEy9MTM
* Feng et al, https://arxiv.org/abs/2305.15408
* Merrill et al, https://arxiv.org/abs/2310.07923
* Amiri et al, https://arxiv.org/abs/2502.02393

Generalization:

* Zhou et al https://arxiv.org/abs/2310.16028 and follow-up, Huang, Yang et al https://openreview.net/forum?id=U49N5V51rU

Relevance to LLMs:

* Veitsman et al https://arxiv.org/abs/2505.21785

Learning, Low-Sensitivity Bias:

* Bhattamishra et al https://arxiv.org/abs/2211.12316
* Hahn and Rofin https://arxiv.org/abs/2402.09963

Hard-Attention Transformers

*  https://arxiv.org/abs/2204.06618 https://arxiv.org/abs/2503.14615

SSMs:

* Merrill et al https://arxiv.org/abs/2404.08819
* Grazzi, Siems, et al https://arxiv.org/abs/2411.12537
* Yang et al, https://arxiv.org/abs/2505.16381
*  Bhattamishra et al

k-hop reasoning:

* Chen et al
* Wang et al
