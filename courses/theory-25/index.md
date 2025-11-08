# Theoretical Abilities and Limitations of Language Models

**Course Description:**
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

**Prerequisites:**
This seminar will not presuppose knowledge of any of these fields. However, a willingness to engage with technical content is important.

We will discuss recent research papers, both from our own group and from other groups. A lot of this content is highly technical, and it is absolutely fine if you do not understand everything in the paper you'll present. Our focus will be on discussing high-level take-aways for understanding the (in)abilities of current AI systems, and prospects for future developments.


**Course Management System:** [CMS](https://cms.sic.saarland/theory_2526/)

**Instructors:** Xinting Huang and Michael Hahn

**Time:** Wed 10:15–11:45 

**Room:** Building C7.3 Room 1.14

**Registration:**
* If you are an **LST / CoLi** student, and want to take this class, you should directly register in the [Course Management System (CMS)](https://cms.sic.saarland/theory_2526/). Admissions decision will be made around the end of the first week of the semester.

* If you are a **Computer Science** student, you should initially register via the Computer Science department seminar registration system. If you want to take the seminar but were not selected by the assignment system, please apply for the waiting list by emailing xhuang@lst.uni-saarland.de. Only register in [Course Management System (CMS)](https://cms.sic.saarland/theory_2526/) once you were selected by the assignment system or otherwise admitted by us.

* **In both cases**, please fill in this [form](https://docs.google.com/forms/d/e/1FAIpQLSefoXLB-nR_TNplGNt_N1JfjVUhgfV_2htvSgB7sMR2HobcaA/viewform?usp=header) with your top-3 preferences among the items in the syllabus, and a brief explanation why you want to take this course and feel prepared for it. If you want, you are welcome to additionally mention any other topic that you would like to present. If you suggest something interesting, that may boost your chances of being admitted.

## Syllabus

Subject to minor changes

| Date | Topic | Readings | Slides | Optional Material | Presenter |
| --- | --- | --- | --- | --- | --- |
| October 15, 2025 | no class |  |  |  |  |
| October 22, 2025 | Short intro, Q&A | No readings |  |  |  |
| October 29, 2025 | no class |  |  |  |  |
| November 5, 2025 |  Expressivity | Thinking Like Transformers [Weiss et al](https://arxiv.org/abs/2106.06981) |  |  | Liliia, Anish |
| November 12, 2025 | Expressivity | Theoretical Limitations of Self-Attention in Neural Sequence Models [Hahn](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00306/43545/Theoretical-Limitations-of-Self-Attention-in) |  |  | Florian, Rimsha |
| November 19, 2025 | Expressivity | The Parallelism Tradeoff: Limitations of Log-Precision Transformers [Merrill et al](https://arxiv.org/abs/2207.00729) |  |  |  Asim, Aiman |
| November 26, 2025 | Learnability | Why are Sensitive Functions Hard for Transformers? [Hahn and Rofin](https://arxiv.org/abs/2402.09963) |  | [Bhattamishra et al](https://arxiv.org/abs/2211.12316) | Zichao, Neshmia |
| December 3, 2025 | Inductive bias | Exposing Attention Glitches with Flip-Flop Language Modeling [Liu et al](https://arxiv.org/abs/2306.00946) |  |  | Barbare, Shane  |
| December 10, 2025 | Length Generalization | What Algorithms can Transformers Learn? A Study in Length Generalization [Zhou et al](https://arxiv.org/abs/2310.16028) |  |  | Mubeen, Yonghua |
| December 17, 2025 | Length Generalization | A Formal Framework for Understanding Length Generalization in Transformers [Huang, Yang et al](https://arxiv.org/abs/2410.02140) |  | [Veitsman et al](https://arxiv.org/abs/2505.21785) | Shayan, Arvind  |
| December 24, 2025 | no class |  |  |  |  |
| December 31, 2025 | no class |  |  |  |  |
| January 7, 2026 | CoT | Towards Revealing the Mystery behind Chain of Thought: A Theoretical Perspective [Feng et al](https://arxiv.org/abs/2305.15408) |  |  | Usama, Ateeb |
| January 14, 2026 | CoT | Lower Bounds for Chain-of-Thought Reasoning in Hard-Attention Transformers [Amiri et al](https://arxiv.org/abs/2502.02393) |  |  | Malik, Entang  |
| January 21, 2026 | SSMs | The Illusion of State in State-Space Models [Merrill et al](https://arxiv.org/abs/2404.08819)  |  | [Sarrof et al](https://arxiv.org/abs/2405.17394) | Hongxu, Pragya |



**You are very welcome to propose readings that you are interested in, as long as they are related to the topic of the seminar! Please email us such suggestions.**


There are also many other great papers, which we don't have time to cover them in the seminar. But we encourage you to read, for example:

The path to AGI:
* https://www.wired.com/story/what-is-artificial-general-intelligence-agi-explained/

Scaling laws and emergence:

* https://arxiv.org/abs/2206.07682
* https://arxiv.org/abs/2304.15004
* https://arxiv.org/abs/2001.08361

Formal languages as a tool for understanding transformers' limitations:
* [Survey by Strobl et al](https://arxiv.org/abs/2311.00208)
* Benefit of Depth: [Merrill et al](https://arxiv.org/abs/2503.03961), [Yang et al](https://arxiv.org/abs/2506.16055)

Theoretical results and  LLM performance:
* [Veitsman et al](https://arxiv.org/abs/2505.21785)
* [Hu et al](https://arxiv.org/abs/2502.19249)


Chain of Thought:

* [Li et al](https://openreview.net/forum?id=3EWTEy9MTM)
* [Merrill et al](https://arxiv.org/abs/2310.07923)

Learning and Generalization:

* Sensitivity: [Bhattamishra et al](https://arxiv.org/abs/2211.12316)



<!--Hard-Attention Transformers *  https://arxiv.org/abs/2204.06618 https://arxiv.org/abs/2503.14615-->

SSMs as a competing architecture:

* Grazzi, Siems, et al https://arxiv.org/abs/2411.12537
* Yang et al, https://arxiv.org/abs/2505.16381

k-hop reasoning:

* Chen et al https://arxiv.org/abs/2412.02975
* Wang et al https://arxiv.org/abs/2505.23683


## Evaluation

***Important: Study programs may differ in which versions of the class you can take. Please check with your study program coordinator if in doubt.***

For students taking the seminar for 4 credits:

    Presentation: 60%
    Questions about readings: 40%

For students taking the seminar for 7 credits:

    Presentation: 30%
    Questions about readings: 20%
    Final paper: 50%

***Important: You need to be registered on LSF for the correct version of the class in order to receive credit.***

### Questions

Please register on the forum on CMS (in CMS, you will see "forum" on the top toolbar, and reply in the forum to post questions).

Starting from the fourth week, every student submits one question about the readings by Tuesday noon.
Questions are graded on a 3-point scale (0: no question submitted, 1: superficial question, 2: insightful question). Students can also submit a few more questions, the grade will be calculated as the highest score among questions.（So you can also ask some basic questions that you want clarification)

### Presentations

Because most papers in this seminar require more effort than usual, we will discuss only one paper per week, with two students jointly presenting it. Each team should aim for a 40–60 minute presentation, followed by 30–40 minutes of discussion. You may organize and divide the presentation between the two presenters in any way you find appropriate. However, each student will be graded individually.

Some papers are relatively easier than others, but presentations on those papers will be evaluated more strictly.

We expect that presentations will cover the key points from the readings, such as the main evidence for and against the key claims under consideration in the paper.

We do not expect that presentations will cover all details of the papers. Rather, you should focus on big picture findings and conclusions, and are not expected to include every finding from the paper in your presentation.
For instance, instead of a table of numbers, highlight key results.
When there are multiple similar results in the paper, synthesize them.
If the papers have many studies, you might select a presentative subset to explain the paper's conclusions.
On the other hand, if the assigned papers primarily discuss/review other work, draw on material from the work cited to provide richer content and even details where useful. Also, sometimes there is just one paper in a seminar session, so you will have more time and may cover more details.

Make sure to motivate the papers' research question(s).
Give background on key concepts, and convey to the audience your understanding of why certain research decisions were made.

Select what you consider the key points; you are not expected to cover every part of the paper exhaustively. Include details only to the extent that you believe them to be important.

Critically engage with the reading: contribute your own opinion on the key findings, and on the paper's motivation and arguments. In what ways do or don't you agree with arguments made by the authors?

You will have sufficient time, so avoid speaking too fast for others to keep up, make sure your audience is following. You can do so by giving more examples, or simply repeating again. Making presentation is to convey information, if audience cannot follow, it's waste of time for both sides.
Generating and moderating in-class discussion is a key component of your presentation -- thinking about what will be interesting to your audience will thus be important.
Discussion should happen not just after the presentation, but you should engage the audience and create ample opportunity for discussion during your presentation.
Before the presentation, take a look at the questions that have been posted in the forum and refer to these as needed. These may be useful for getting discussion started.
Conversely, when attending other students' talks, reciprocate by participating actively in the discussion.

No need to upload your slides to CMS (unlike previous seminars we offered)

### Final Papers (for the 7CP version)

**Note: We will discuss this in the first meeting. Requirements may be changed based on popular demand.**

Term papers will be about a small independent project.

You will investigate some question about the abilities of language models. It can be a theoretical work, or an empirical project verifying insights from theoretical work.
The report is expected to contain a brief literature review, motivation of your study, a description of what you did, and you found. It's recommended to include quantitative validation of what you found, so that you show it's not an illusion.

The report should have 8 pages of main report, plus unlimited appendix, in the NeurIPS style format. The main report should be self-contained, but you can use the appendix to report prompts, further analyses, or other material.

The report should be uploaded via CMS. The due date is April TBD, 2026, 23:59.

<!--Everyone is expected to report on their project idea in the TBD, session, and to participate in discussion to give feedback to other students' ideas. Feel free to come up with any ideas that might be interesting. Students may prepare a short slide deck on their idea. This will not be graded; the session is intended to help improve and finetune project ideas. -->

## Contact

Please contact Xinting (xhuang@lst.uni-saarland.de) or Michael (mhahn@lst.uni-saarland.de) for any questions.

## Accommodations

If you need any accommodations due to a disability or chronic illness, please either contact Michael at mhahn@lst.uni-saarland.de or the [Equal Opportunities and Diversity Management Unit](https://www.uni-saarland.de/en/administration/diversity.html) of the university.

