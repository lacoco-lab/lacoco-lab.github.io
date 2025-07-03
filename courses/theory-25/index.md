# Theoretical Abilities and Limitations of Language Models

LLM have amazing capabilities, but also hallucinate and make reasoning mistakes. Can we understand these abilities and limitations theoretically, as way to figure out ways of overcoming them?
The incredible scale of current LLMs makes this a daunting prospect. However, recent research has developed mathematical understanding sheeding light on questions such as:

* Why do LLMs struggle with tasks (e.g., multiplying 6-digit numbers) that a simple calculator can perform easily? 

* Which problems can be solved by a transformer in one step? Which require a chain-of-thought? How long does a chain-of-thought have to be?

* What are benefits and limits of allowing LLM agents to act in the world, and to collaborate with each other or humans?

* Which kinds of problems is a transformer likely to generalize on well?

* What are differences between transformers and other architectures (e.g. state-space models)?

* What possible future architectures -- if any -- could replace transformers as the backbone of LLMs?

* Assuming that AGI can be realized by scaling current LLM architectures, what kind of abilities could we expect from this AGI?

Research on these questions draws on fields such as computational complexity, formal language theory, and statistical learning theory.

This seminar will not presuppose knowledge of any of these fields. However, a willingness to engage with technical content is important.

We will discuss recent research papers, both from our own group and from other groups. A lot of this content is highly technical, and it is absolutely fine if you do not understand everything in the paper you'll present. Our focus will be on discussing high-level take-aways for understanding the (in)abilities of current AI systems, and prospects for future developments.

# Syllabus

TBD. A few relevant papers. We will expand this.

**You are very welcome to propose readings that you are interested in, as long as they are related to the topic of the seminar!**

The path to AGI:
* https://www.wired.com/story/what-is-artificial-general-intelligence-agi-explained/


Scaling laws and emergence:

* https://arxiv.org/abs/2206.07682
* https://arxiv.org/abs/2304.15004
* https://arxiv.org/abs/2001.08361

Formal languages as a tool for understanding transformers' limitations:
* Survey by Strobl et al https://arxiv.org/abs/2311.00208
* Difficulty of Parity: https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00306/43545/Theoretical-Limitations-of-Self-Attention-in
* Bound by TC0: Merrill et al https://arxiv.org/abs/2207.00729
* Benefit of Depth: Merrill et al https://arxiv.org/abs/2503.03961

Limitations affecting LLM performance:
* Veitsman et al https://arxiv.org/abs/2505.21785


Chain of Thought:

* Li et al, https://openreview.net/forum?id=3EWTEy9MTM
* Feng et al, https://arxiv.org/abs/2305.15408
* Merrill et al, https://arxiv.org/abs/2310.07923
* Amiri et al, https://arxiv.org/abs/2502.02393

Learning and Generalization:

* Length generalization: Zhou et al https://arxiv.org/abs/2310.16028 and follow-up, Huang, Yang et al https://openreview.net/forum?id=U49N5V51rU
* Sensitivity: Bhattamishra et al https://arxiv.org/abs/2211.12316 ; Hahn and Rofin https://arxiv.org/abs/2402.09963



<!--Hard-Attention Transformers *  https://arxiv.org/abs/2204.06618 https://arxiv.org/abs/2503.14615-->

SSMs as a competing architecture:

* Merrill et al https://arxiv.org/abs/2404.08819
* Grazzi, Siems, et al https://arxiv.org/abs/2411.12537
* Yang et al, https://arxiv.org/abs/2505.16381
*  Bhattamishra et al

k-hop reasoning:

* Chen et al https://arxiv.org/abs/2412.02975
* Wang et al https://arxiv.org/abs/2505.23683
