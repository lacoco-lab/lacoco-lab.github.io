# Interpreting and Analyzing Neural Language Models

<!-----DESCRIPTION----->
**Course Description:**
Despite their huge success, neural networks are still widely considered “black-boxes”. In this seminar, we will look into interpretability methods that aim to demystify these models. We will focus on post-hoc interpretability for transformer-based language models, and work on relatively young and burgeoning fields such as Mechanistic Interpretability, which focuses on reverse-engineering model components into human-understandable algorithms. We will read recent papers that involve a diverse set of techniques for interpreting the inner-workings of language models.

<!----PREREQ------------>

**Prerequisites:**
Many of our readings will be quite technical. You will need a good background in NLP or machine learning in order to thrive in this course.

<!-----REGISTRATION----->

**Registration:**
* If you are an **LST / CoLi** student, and want to take this class, you should directly register in the [Course Management System (CMS)](https://cms.sic.saarland/probing_25/). You may either be directly admitted or waitlisted.

* If you are a **Computer Science** student, you should initially register via the Computer Science department seminar registration system. If you want to take the seminar but were not selected by the assignment system, please apply for the waiting list by emailing xhuang@lst.uni-saarland.de. Only register in [Course Management System (CMS)](https://cms.sic.saarland/probing_25/) once you were selected by the assignment system or otherwise admitted by us.

* **In both cases**, please email xhuang@lst.uni-saarland.de your top-3 preferences among the items in the syllabus, and a brief explanation why you want to take this course and feel prepared for it. If you want, you are welcome to additionally mention any other topic that you would like to present. If you suggest something interesting, that may boost your chances of being admitted.


<!----CMS------------>

**Course Management System:** [CMS](https://cms.sic.saarland/probing_25/)

<!-----INSTRUCTORS----->
**Instructors:** [Xinting Huang](https://lacoco-lab.github.io/home/authors/xhuang/)

<!-----TIME----->
**Time:** Monday, 14:15-15:45

<!-----ROOM----->
**Room:** Room 1.12


## Format and requirements

This is a seminar course.
Starting from the fourth week, two students will present in each unit. Every student will present exactly once.
We expect all students to read the readings every week. Every student submits one question about the readings by Friday noon.


## Syllabus

Some optional material is for the Topic, rather than being specific to the paper in the same row.
 
| Date          | Topic               | Readings  | Slides  | Optional Material | Presenter  |
| ------------- | ------------------- | ------- | ------- | --------------------- | ---------- |
|  2025-04-14    | no class               |  |  |                |          | 
|  2025-04-21    | no class | | | | |
| 2025-04-28    | Introduction to Transformers and (L)LMs               |   |  [slides](https://github.com/lacoco-lab/lacoco-lab.github.io/blob/main/courses/alignment-2024/session2.pdf) |        [Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/) [Simplified code for GPT-2](https://github.com/lacoco-lab/lacoco-lab.github.io/blob/main/courses/probing-2024/modeling_gpt2_simplified.py)      |   | 
| 2025-05-05    | Understanding Transformers        |   [A mathematical framework](https://transformer-circuits.pub/2021/framework/index.html) Required Sec: see below    |       |        |      |
|  |         |   [RASP](https://arxiv.org/abs/2106.06981) Section 1, 2, 3 |       |        |      |
| 2025-05-12    | Probing               | [Othello-GPT](https://arxiv.org/abs/2210.13382)       |       |   [Bert recovers NLP pipeline](https://arxiv.org/abs/1905.05950)      |     |
|               |                     |  [Control tasks](https://arxiv.org/abs/1909.03368)      |       |  [Probing entities' property and relation](https://arxiv.org/abs/2106.00737)   |    |
| 2025-05-19   |   Projecting to vocabulary space                 | [Logit Lens](https://www.lesswrong.com/posts/AcKRB8wDpdaN6v6ru/interpreting-gpt-the-logit-lens)  + breifly mention [Tuned Lens](https://arxiv.org/abs/2303.08112)  |      |    [Future Lens](https://arxiv.org/abs/2311.04897) [Backward Lens](https://arxiv.org/abs/2402.12865) |     |
|               |                     |  [Interpret MLP via vocabulary space](https://arxiv.org/abs/2203.14680)     |       |    [MLP are key-value memories](https://arxiv.org/abs/2012.14913)    |     |
|  2025-05-26 |  Activation Patching, Path Patching  | [Interchange intervention](https://proceedings.neurips.cc/paper/2021/hash/4f5c422f4d49a5a807eda27434231040-Abstract.html) Sec. 1, 2, 3 + [ROME](https://arxiv.org/abs/2202.05262) Sec. 1, 2    |       | [Optimal ablation](https://neurips.cc/virtual/2024/poster/93600)  [DAS](https://arxiv.org/abs/2303.02536)      |       |        |      |
|               |                         | [IOI](https://arxiv.org/abs/2211.00593)        |         |   [Path Patching](https://arxiv.org/abs/2304.05969)   [Greater-than](https://arxiv.org/abs/2305.00586)      [ACDC](https://arxiv.org/abs/2304.14997)           |              |                      |             |
|  2025-06-02  |  Monosementicity    | [Towards Monosementicity](https://transformer-circuits.pub/2023/monosemantic-features/index.html) Required Sec: see below | | [Scaling monosemanticity](https://transformer-circuits.pub/2024/scaling-monosemanticity/index.html) Concurrent or earlier works [link](https://arxiv.org/abs/2309.08600)  [link](https://www.alignmentforum.org/posts/z6QQJbtpkEAX3Aojj/interim-research-report-taking-features-out-of-superposition) |  |
|               |          |  [Transcoders](https://arxiv.org/abs/2406.11944) | | [SAE on randomly initialized models](https://arxiv.org/abs/2501.17727) | |
| 2025-06-09 | no class | | | | |
|   2025-06-16  |  Attribution          |  [ContextCite](https://arxiv.org/abs/2409.00729)    |       |    [Integrated Gradients](https://arxiv.org/abs/1703.01365)  [Information flow routes](https://arxiv.org/abs/2403.00824)   |    |
|               |                     |   [AtP*](https://arxiv.org/abs/2403.00745)   |       |   [Diffmask](https://arxiv.org/abs/2004.14992)   [EAP](https://arxiv.org/abs/2310.10348)     |     |
|     2025-06-23          | Miscellaneous | [CCS](https://arxiv.org/abs/2212.03827)  | | | |
|                |                 | [Edge pruning](https://arxiv.org/abs/2406.16778) | | | |
| 2025-06-30 | Case study I | [Function Vectors](https://arxiv.org/abs/2310.15213) | | [Task Vectors](https://arxiv.org/abs/2310.15916) [Induction Circuit](https://arxiv.org/abs/2410.04468)| |
|            |              | [Knowledge Awareness](https://arxiv.org/abs/2411.14257) | | | |
| 2025-07-07 | Case study II | [Fine-Tuning Enhances Mechanisms](https://arxiv.org/abs/2402.14811) | | | |
|           |               | [Refusal Direction](https://arxiv.org/abs/2406.11717) | | | |
| 2025-07-14 | Case study III | [Belief State Geometry](https://arxiv.org/abs/2405.15943) | | | |
|          |                 | [Onion Representations](https://arxiv.org/abs/2408.10920) | | | |

As some papers are very long and require more time to understand and present, I specify some required sections to reduce the workload (Only these are required to be read/presented, but feel free to also read/present other parts).

Sections required to read:
* *A Mathematical Framework for Transformer Circuits*
    - Transformer Overview
    - Zero-Layer Transformers
    - One-Layer Attention-Only Transformers: Interpretation as Skip-Trigrams (Only one subsection)
    - Two-Layer Attention-Only Transformers: Analyzing a Two-Layer Model; Induction Heads (Two subsections)
    - (Other parts can be briefly covered as needed)

* *Thinking like Transformers* (RASP)
    - Section 1, 2, 3. 
    (Please focus on understanding RASP programs, topics regarding expressivity are optional. To have a clearer connection to real transformers, can you construct specific vectors for query, key, value, and other activations that execute specific operations?)

* *Causal Abstractions of Neural Networks*
    - Section 1, 2, 3

* *Locating and Editing Factual Associations in GPT*
    - Section 1, 2

* *Towards Monosemanticity: Decomposing Language Models With Dictionary Learning*
    - Problem Setup
    - Detailed Investigations of Individual Features
    (In other words, sections before and excluding Global Analysis)


There are some other works that do not fit in any topics above, they might be interesting to you but you're not required to read:
- [Parameter Decomposition](https://arxiv.org/abs/2501.14926)
- [Intrinsic dimension](https://arxiv.org/pdf/2405.15471)
- [Patchscopes](https://arxiv.org/abs/2401.06102)  
- [toy model CoT](https://arxiv.org/abs/2406.02128)
- [Attribute Lens](https://arxiv.org/abs/2308.09124)
- [A good survey](https://arxiv.org/abs/2405.00208)



## Evaluation

IMPORTANT: Study programs may differ in which version(s) of a seminar course you can take. If in doubt, check with your study program coordinator.

For students taking the seminar for 4 credits:

    Presentation: 60%
    Questions about readings: 40%

For students taking the seminar for 7 credits:

    Presentation: 30%
    Questions about readings: 20%
    Final paper: 50%

### Questions

Please register on the forum on CMS.

Starting from the fourth week, every student submits one question about the readings by Friday noon.
Questions are graded on a 3-point scale (0: no question submitted, 1: superficial question, 2: insightful question). Students can also submit a few more questions, the grade will be calculated as the highest score among questions.（So you can also ask some basic questions that you want clarification)

### Presentations

We expect that presentations will cover the key points from the readings, such as the main evidence for and against the key claims under consideration in the paper.

We do not expect that presentations will cover all details of the papers. Rather, you should focus on big picture findings and conclusions, and are not expected to include every finding from the paper in your presentation.
For instance, instead of a table of numbers, highlight key results.
When there are multiple similar results in the paper, synthesize them.
If the papers have many studies, you might select a representative subset to explain the paper's conclusions.
On the other hand, if the assigned papers primarily discuss/review other work, draw on material from the work cited to provide richer content and even details where useful. Also, sometimes there is just one paper in a seminar session, so you will have more time and may cover more details.

Make sure to motivate the papers' research question(s).
Give background on key concepts, and convey to the audience your understanding of why certain research decisions were made.

Select what you consider the key points; you are not expected to cover every part of the paper exhaustively. Include details only to the extent that you believe them to be important.

Critically engage with the reading: contribute your own opinion on the key findings, and on the paper's motivation and arguments. In what ways do or don't you agree with arguments made by the authors?

As you'll be presenting in teams of two, don't just present the two papers separately, but make sure to also draw connections and compare.
Aim for 40-60 minutes of presentation, allowing 30-40 minutes of discussion. You will have sufficient time, so avoid speaking too fast for others to keep up, make sure your audience is following. You can do so by giving more examples, or simply repeating again. Making presentation is to convey information, if audience cannot follow, it's waste of time for both sides.
Generating and moderating in-class discussion is a key component of your presentation -- thinking about what will be interesting to your audience will thus be important.
Discussion should happen not just after the presentation, but you should engage the audience and create ample opportunity for discussion during your presentation.
Before the presentation, take a look at the questions that have been posted in the forum and refer to these as needed. These may be useful for getting discussion started.
Conversely, when attending other students' talks, reciprocate by participating actively in the discussion.


### Final Papers (for the 7CP version)

**Note: We will discuss this in the first meeting. Requirements may be changed based on popular demand.**

Term papers will be about a small independent project.

You will investigate some interpretability question about neural networks.
You could investigate an existing model (e.g., GPT2-Small), or train and interpret a model of your own.
You could use an existing method or try to come up with some new analysis approach.
You could also compare different analysis approaches, or investigate interpretability from a theoretical angle.

The report is expected to contain a brief literature review, motivation of your study, a description of what you did, and you found. It's recommended to include quantitative validation of what you found, so that you show it's not an illusion.

<!-- The report is expected to include quantitative evaluation of the LLM's behavior (e.g., using measures such as accuracy). Additionally including qualitative evaluation can also be beneficial. -->



The report should have 8 pages of main report, plus unlimited appendix, in the NeurIPS style format. The main report should be self-contained, but you can use the appendix to report prompts, further analyses, or other material.

The report should be uploaded via CMS. The due date is TBD.

Everyone is expected to report on their project idea in the TBD, session, and to participate in discussion to give feedback to other students' ideas. Feel free to come up with any ideas that might be interesting. Students may prepare a short slide deck on their idea. This will not be graded; the June 14 session is intended to help improve and finetune project ideas.

## Contact

Please contact Xinting (xhuang@lst.uni-saarland.de) or Michael (mhahn@lst.uni-saarland.de) for any questions.

## Accommodations

If you need any accommodations due to a disability or chronic illness, please either contact Michael at mhahn@lst.uni-saarland.de or the [Equal Opportunities and Diversity Management Unit](https://www.uni-saarland.de/en/administration/diversity.html) of the university.

