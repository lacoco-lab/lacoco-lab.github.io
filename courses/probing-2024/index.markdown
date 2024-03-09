# Probing and Analyzing Neural Language Models

### Warning: this page is currently revising, take the information with a grain of salt
DRAFT 

**Course Description:** Despite their huge success, neural networks are still widely considered “black-boxes”. In this seminar, we will look into interpretability methods that aim to demystify these models. We will focus on post-hoc interpretability for transformer-based language models, and work on relatively young and burgeoning fields such as Mechanistic Interpretability, which focuses on reverse-engineering model components into human-understandable algorithms. We will read recent papers that involve a diverse set of techniques for interpreting the inner-workings of language models.

**Course Management System:** TODO

**Instructors:** Xinting Huang

**Time:** Fr 14:15–15:45

**Room:** Building C7.3, Room -1.05 


## Format and requirements

This is a seminar course.
Starting from the fourth week, one or two students will present in each unit (except for the TODO session). Every student will present exactly once.
We expect all students to read the readings every week. Every student submits one question about the readings by Monday noon.


## Syllabus

**Note: The syllabus is subject to change. We will discuss this in the first and second meeting.**
  
| Date          | Topic               | Readings  | Slides  | Optional Material | Presenter  |
| ------------- | ------------------- | ------- | ------- | --------------------- | ---------- |
|   1            | Monosemanticity     | [Anthropic paper](https://transformer-circuits.pub/2023/monosemantic-features/index.html) | | [A very similar one](https://arxiv.org/abs/2309.08600), [paper](https://www.alignmentforum.org/posts/z6QQJbtpkEAX3Aojj/interim-research-report-taking-features-out-of-superposition) | TBD |
|               |                     | [Codebook Features](https://arxiv.org/abs/2310.17230) |   | | TBD |
|  2             |  Circuit Discovery  | [IOI](https://arxiv.org/abs/2211.00593)        |         |     [Greater-than](https://arxiv.org/abs/2305.00586),   [Doc-string](https://www.alignmentforum.org/posts/u6KXXmKFbXfWzoAXn/a-circuit-for-python-docstrings-in-a-4-layer-attention-only)                |             |
|               |                     | [ACDC](https://arxiv.org/abs/2304.14997)        |         |                       |             |
|   3            | From Circuits to Transformers     |  RASP       |         |                       |             |
|               |                     | [Tracr](https://arxiv.org/abs/2301.05062)        |         |                       |             |
|   4            | Frameworks for Understanding Transformers                    | [RASP](https://arxiv.org/abs/2106.06981)        |         |                       |             |
|               |                     |    [Anthropic framework](https://transformer-circuits.pub/2021/framework/index.html)     |         |                       |             |
|   5            |   Interpreting hidden states                  | [Logit Lens](https://www.lesswrong.com/posts/AcKRB8wDpdaN6v6ru/interpreting-gpt-the-logit-lens)      |       |   [Tuned Lens](https://arxiv.org/abs/2303.08112)  |      |
|               |                     | [Future Lens](https://arxiv.org/abs/2311.04897)  | | |
|   6            | Patching              |  [Patchscopes](https://arxiv.org/abs/2401.06102)      |       |        |      |
|               |                       | [Interchange intervention](https://arxiv.org/abs/2106.02997) | | [DAS](https://arxiv.org/abs/2303.02536) | |
|   7            | Probing               | [Probing in a synthetic setting](https://arxiv.org/abs/2210.13382)       |       |        |      |
|               |                     |  [Probing entities' property and relation](https://arxiv.org/abs/2106.00737)     |       |        |      |
|               |                     |  [Bert recovers NLP pipeline](https://arxiv.org/abs/2004.14992)     |       |        |      |
|   8            |  Role of MLPs       | [MLP are key-value memories](https://arxiv.org/abs/2012.14913)      |       |        |      |
|               |                     |  [link](https://arxiv.org/abs/2203.14680)     |       |        |      |
|   9            | Learning                    |  [Grokking](https://arxiv.org/abs/2301.05217)     |       |        |      |
|               |                     |  TODO     |       |        |      |
|  10            |  Attribution                   |  [What Does BERT Look At?](https://arxiv.org/abs/1906.04341)     |       |        |      |
|               |                     |  [Integrated Gradients](https://arxiv.org/abs/1703.01365)      |       |     [Diffmask](https://arxiv.org/abs/2004.14992)    |      |
|  11             |   Head importance                  |  [Sixteen Heads Better than One?](https://arxiv.org/abs/1905.10650)     |       |        |      |
|               |                     |   [Some heads do heavy lifting](https://aclanthology.org/P19-1580/)    |       |        |      |
|               |                     |       |       |        |      |
|               |                     |       |       |        |      |
|               |                     |       |       |        |      |
|               |                     |       |       |        |      |








TODO identify an ordering of these topics

also some earlier background reading

Monosemanticity: 
- [Anthropic paper](https://transformer-circuits.pub/2023/monosemantic-features/index.html)
  - [A very similar one](https://arxiv.org/abs/2309.08600)
  - Maybe they inspired by the same [paper](https://www.alignmentforum.org/posts/z6QQJbtpkEAX3Aojj/interim-research-report-taking-features-out-of-superposition)
- [Codebook Features](https://arxiv.org/abs/2310.17230)

Circuits Discovery:
- [ACDC](https://arxiv.org/abs/2304.14997)
- [IOI](https://arxiv.org/abs/2211.00593)
- [Greater-than](https://arxiv.org/abs/2305.00586)
- [Doc-string](https://www.alignmentforum.org/posts/u6KXXmKFbXfWzoAXn/a-circuit-for-python-docstrings-in-a-4-layer-attention-only)

Converting Circuits into Transformer
- [Tracr](https://arxiv.org/abs/2301.05062)
- Also RASP

Framework to understand Transformers
- [RASP](https://arxiv.org/abs/2106.06981)
- [Anthropic framework](https://transformer-circuits.pub/2021/framework/index.html)

A series of Lens (interpreting the hidden states)
- Original [Logit Lens](https://www.lesswrong.com/posts/AcKRB8wDpdaN6v6ru/interpreting-gpt-the-logit-lens)
- [Tuned Lens](https://arxiv.org/abs/2303.08112)
- [Future Lens](https://arxiv.org/abs/2311.04897)
- [Patchscopes](https://arxiv.org/abs/2401.06102)  (see its related work for more papers)

Probing
- [Probing in a synthetic setting](https://arxiv.org/abs/2210.13382) Probing game state, Gradient-based Intervention
- [Probing entities' property and relation](https://arxiv.org/abs/2106.00737)
- [Bert recovers NLP pipeline](https://arxiv.org/abs/2004.14992) Probing syntactic information

Causal operations (Activation Patching / Causal intervention / Path Patching)
- IOI, ACDC (Path Patching)
- Patchscopes (Activation Patching)
- [Interchange intervention](https://arxiv.org/abs/2106.02997) (Activation Patching) Mapping hidden representations to nodes in computational graph.
- [DAS](https://arxiv.org/abs/2303.02536) a follow-up work to the above paper
- More papers to be added

Other interesting papers:
- [Grokking](https://arxiv.org/abs/2301.05217)
- [MLP are key-value memories](https://arxiv.org/abs/2012.14913)
- A follow-up work to the above [link](https://arxiv.org/abs/2203.14680)  (to read)
- 

Some earlier papers
- [Integrated Gradients](https://arxiv.org/abs/1703.01365)  Attribution methods
- [Diffmask](https://arxiv.org/abs/2004.14992) Attribution methods
- [Sixteen Heads Better than One?](https://arxiv.org/abs/1905.10650) Estimate head importance, prune heads
- [Some heads do heavy lifting](https://aclanthology.org/P19-1580/) Estimate head importance, prune heads, examine attention
- [What Does BERT Look At?](https://arxiv.org/abs/1906.04341)  Examine attention pattern


--------



transformers as circuits


Othello-GPT https://arxiv.org/abs/2310.07582 https://arxiv.org/abs/2309.00941

Causal attribution https://arxiv.org/abs/2305.08809

Maze-Solving Transformers https://arxiv.org/abs/2312.02566

Automated Circuit Discovery https://arxiv.org/abs/2304.14997

Attribution Patching https://arxiv.org/abs/2310.10348

Activation Patching https://arxiv.org/abs/2309.16042

Grokking Group Multiplication with Cosets https://arxiv.org/pdf/2312.06581.pdf also: https://arxiv.org/abs/2301.05217

binding entities: https://arxiv.org/abs/2310.17191

Challenges: case study of Dyck languages https://arxiv.org/abs/2312.01429  (another paper about Dyck https://arxiv.org/abs/2303.02536)

Challenges: https://dl.acm.org/doi/pdf/10.1145/3236386.3241340

Clock and pizza: https://arxiv.org/abs/2306.17844


some other papers:

https://openaccess.thecvf.com/content/ICCV2023W/CLVL/html/Palit_Towards_Vision-Language_Mechanistic_Interpretability_A_Causal_Tracing_Tool_for_BLIP_ICCVW_2023_paper.html

https://arxiv.org/abs/2203.14680

https://arxiv.org/abs/2012.14913

https://arxiv.org/abs/2307.05471



## Evaluation


For students taking the seminar for 4 credits:

    Presentation: 60%
    Questions about readings: 40%

For students taking the seminar for 7 credits:

    Presentation: 30%
    Questions about readings: 20%
    Final paper: 50%

### Questions

TODO

Please register on the forum on CMS.

Starting from the fourth week (Nov 13), every student submits one question about the readings by Monday noon.
Questions are graded on a 3-point scale (0: no question submitted, 1: superficial question, 2: insightful question).

### Presentations

TODO

We expect that presentations will cover the key points from the readings, such as the main evidence for and against the key claims under consideration in the paper.

We do not expect that presentations will cover all details of the papers. Rather, you should focus on big picture findings and conclusions, and are not expected to include every finding from the paper in your presentation.
For instance, instead of a table of numbers, highlight key results.
When there are multiple similar results in the paper, synthesize them.
If the papers have many studies, you might select a representative subset to explain the paper's conclusions.
On the other hand, if the assigned papers primarily discuss/review other work (as is the case in some weeks), draw on material from the work cited to provide richer content and even details where useful.

Make sure to motivate the papers' research question(s).
Give background on key concepts, and convey to the audience your understanding of why certain research decisions were made.

Select what you consider the key points; you are not expected to cover every part of the paper exhaustively. Include details only to the extent that you believe them to be important.

If you present two papers, do not just present them separately. Rather, draw connections, and compare and contrast where appropriate.

Critically engage with the reading: contribute your own opinion on the key findings, and on the paper's motivation and arguments. In what ways do or don't you agree with arguments made by the authors?

Aim for 40-60 minutes of presentation, allowing 30-40 minutes of discussion.
If you present on your own, your presentation can be somewhat shorter.
Discussion should happen not just after the presentation, but you should engage the audience and create ample opportunity for discussion during your presentation.
Before the presentation, take a look at the questions that have been posted in the forum and refer to these as needed. These may be useful for getting discussion started.
Conversely, when attending other students' talks, reciprocate by participating actively in the discussion.


### Term Papers

TODO

**Note: We will discuss this in the first and second meeting. Requirements may be changed based on popular demand.**

Term papers will be about a small independent project.
You will investigate a question about LLMs' cognitive ability via prompting. For instance, you might test their ability to perform a certain kind of reasoning, or investigate how they respond to certain kinds of stimuli.

Option 1: You may develop your own question and prompts. In this case, you will be expected to design at least 25 (not more than 50) prompts.

Option 2: You may draw on a larger existing benchmark. In this case, you will be expected to find some new angle on the benchmark, e.g., by tweaking the stimuli or by evaluating the LLM's behavior in a different way.

The report is expected to contain a brief literature review, motivation of your question, a description of your prompts, and evaluation of the LLM's behavior. The report is expected to include quantitative evaluation of the LLM's behavior (e.g., using measures such as accuracy). Additionally including qualitative evaluation can also be beneficial.



The report should have 8 pages of main report, plus unlimited appendix. The main report should be self-contained, but you can use the appendix to report prompts, further analyses, or other material.

TODO

The report should be uploaded via CMS. The due date is April 8, 2024, 23:59.

Everyone is expected to report on their project idea in the December 19, 2023, session, and to participate in discussion to give feedback to other students' ideas. Students may prepare a short slide deck on their idea. This will not be graded; the December 19 session is intended to help improve and finetune project ideas.

## Contact

Please contact Xinting (xhuang@lst.uni-saarland.de) or Michael (mhahn@lst.uni-saarland.de) for any questions.

## Accommodations

If you need any accommodations due to a disability or chronic illness, please either contact Michael at mhahn@lst.uni-saarland.de or the [Equal Opportunities and Diversity Management Unit](https://www.uni-saarland.de/en/administration/diversity.html) of the university.

