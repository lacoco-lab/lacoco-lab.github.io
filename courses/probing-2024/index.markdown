# Probing and Analyzing Neural Language Models

<!-----DESCRIPTION----->
**Course Description:**
Despite their huge success, neural networks are still widely considered “black-boxes”. In this seminar, we will look into interpretability methods that aim to demystify these models. We will focus on post-hoc interpretability for transformer-based language models, and work on relatively young and burgeoning fields such as Mechanistic Interpretability, which focuses on reverse-engineering model components into human-understandable algorithms. We will read recent papers that involve a diverse set of techniques for interpreting the inner-workings of language models.

<!----PREREQ------------>

**Prerequisites:**
Many of our readings will be quite technical. You will need a good background in NLP or machine learning in order to thrive in this course.

<!-----REGISTRATION----->

**Registration:**
* If you are an **LST / CoLi** student, and want to take this class, you should directly register in the [Course Management System (CMS)](https://cms.sic.saarland/probing_24/). You may either be directly admitted or waitlisted.

* If you are a **Computer Science** student, you should initially register via the Computer Science department seminar registration system. If you want to take the seminar but were not selected by the assignment system, please apply for the waiting list by emailing xhuang@lst.uni-saarland.de. Only register in [Course Management System (CMS)](https://cms.sic.saarland/probing_24/) once you were selected by the assignment system or otherwise admitted by us.

* **In both cases**, please email xhuang@lst.uni-saarland.de your top-3 preferences among the items in the syllabus, and a brief explanation why you want to take this course and feel prepared for it. If you want, you are welcome to additionally mention any other topic that you would like to present. If you suggest something interesting, that may boost your chances of being admitted.


<!----CMS------------>

**Course Management System:** [CMS](https://cms.sic.saarland/probing_24/)

<!-----INSTRUCTORS----->
**Instructors:** [Xinting Huang](https://lacoco-lab.github.io/home/authors/xhuang/)

<!-----TIME----->
**Time:** Fr 14:15–15:45

<!-----ROOM----->
**Room:** Building C7.3, Room -1.05 


## Format and requirements

This is a seminar course.
Starting from the fourth week, one or two students will present in each unit. Every student will present exactly once.
We expect all students to read the readings every week. Every student submits one question about the readings by Thursday noon.


## Syllabus

Note: The syllabus is still subject to change.

In each session, two students will together present two papers (in the "Readings" column) on a common topic. In some sessions there is only one paper, because they reqire more time and effort to understand or they should be presented in greater detail. In this case, two students will coordinate together and present it. **The optional material is for the Topic, rather than being specific to a particular paper**.

  
| Date          | Topic               | Readings  | Slides  | Optional Material | Presenter  |
| ------------- | ------------------- | ------- | ------- | --------------------- | ---------- |
|  2024-04-19    | no class               |  |  |                |          | 
| 2024-04-26    | Introduction to Transformers and (L)LMs               |   |  [slides](https://github.com/lacoco-lab/lacoco-lab.github.io/blob/main/courses/alignment-2024/session2.pdf) |        [Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/) [Simplified code for GPT-2](https://github.com/lacoco-lab/lacoco-lab.github.io/blob/main/courses/probing-2024/modeling_gpt2_simplified.py)      | [Michael](https://www.mhahn.info/)  | 
|  2024-05-03    | no class |
| 2024-05-10    | Probing               | [Othello-GPT](https://arxiv.org/abs/2210.13382)       |       |   [Bert recovers NLP pipeline](https://arxiv.org/abs/1905.05950)      |  Greg    |
|               |                     |  [Control tasks](https://arxiv.org/abs/1909.03368)      |       |  [Probing entities' property and relation](https://arxiv.org/abs/2106.00737)   |   Herald   |
| 2024-05-17    | Frameworks for Understanding Transformers I                |  [A mathematical framework](https://transformer-circuits.pub/2021/framework/index.html)       |         |        [Induction heads](https://transformer-circuits.pub/2022/in-context-learning-and-induction-heads/index.html)               |        Asmaa, Mark     |
|  2024-05-24    |       Frameworks for Understanding Transformers II   |    [RASP](https://arxiv.org/abs/2106.06981)     |         |       [Learning Transformer Programs](https://arxiv.org/abs/2306.01128)        |    Yash         |
| 2024-05-31    |  Path Patching, Circuit Discovery  | [IOI](https://arxiv.org/abs/2211.00593)        |         |   [Path Patching](https://arxiv.org/abs/2304.05969)   [Greater-than](https://arxiv.org/abs/2305.00586)                |    Santanu          |
|               |                     | [ACDC](https://arxiv.org/abs/2304.14997)        |         |                       |     Aleksandra        |
| 2024-06-07    |   Interpreting hidden states                  | [Logit Lens](https://www.lesswrong.com/posts/AcKRB8wDpdaN6v6ru/interpreting-gpt-the-logit-lens)      |   [slides](https://github.com/lacoco-lab/lacoco-lab.github.io/blob/main/courses/probing-2024/interpret-hidden-states.pdf)    |   [Tuned Lens](https://arxiv.org/abs/2303.08112) [Future Lens](https://arxiv.org/abs/2311.04897) |   Xinting (brief intro)   |
|               |                | [Patchscopes](https://arxiv.org/abs/2401.06102)   | | [Attribute Lens](https://arxiv.org/abs/2308.09124) |  |
| 2024-06-14 | Project Ideas | | |  | Everyone |
| 2024-06-21    | Monosemanticity     | [Towards Monosementicity](https://transformer-circuits.pub/2023/monosemantic-features/index.html) | | [A very similar one](https://arxiv.org/abs/2309.08600) | Misha |
|               |                     | [Codebook Features](https://arxiv.org/abs/2310.17230) |   | [Scaling monosemanticity](https://transformer-circuits.pub/2024/scaling-monosemanticity/index.html)| TBD |
| 2024-06-28    |  Role of MLPs       | [MLP are key-value memories](https://arxiv.org/abs/2012.14913)      |       |        |    Nadia  |
|               |                     |  [Interpret MLP via vocabulary space](https://arxiv.org/abs/2203.14680)     |       |        |  TBD    |
| 2024-07-05    | Activation Patching, Causality                    | [Interchange intervention](https://proceedings.neurips.cc/paper/2021/hash/4f5c422f4d49a5a807eda27434231040-Abstract.html)     |       |     [Geiger et al, arXiV 2023](https://arxiv.org/abs/2301.04709)   [Boundless DAS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/f6a8b109d4d4fd64c75e94aaf85d9697-Abstract-Conference.html)  | Michael      |        |      |
|               |                     |  [DAS](https://arxiv.org/abs/2303.02536)    |      |  | TBD |
| 2024-07-12    |  Attention, Attribution                   |  [What Does BERT Look At?](https://arxiv.org/abs/1906.04341)     |       |    [Integrated Gradients](https://arxiv.org/abs/1703.01365)    |   TBD   |
|               |                     |    [Diffmask](https://arxiv.org/abs/2004.14992)   |       |      [Information flow routes](https://arxiv.org/abs/2403.00824)    |  TBD    |
| 2024-07-19    |   Head importance                  |  [Sixteen Heads Better than One?](https://arxiv.org/abs/1905.10650)     |       |        |   Muhammad   |
|               |                     |   [Some heads do heavy lifting](https://aclanthology.org/P19-1580/)    |       |        |   Yiming   |

<!--| 2024-07-17    | Grokking                    |  [Grokking](https://arxiv.org/abs/2301.05217)     |       |        |      |
|               |                     |  [Stander et al](https://arxiv.org/abs/2312.06581)     |       |        |      |
-->


<!--

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

-->

## Evaluation


For students taking the seminar for 4 credits:

    Presentation: 60%
    Questions about readings: 40%

For students taking the seminar for 7 credits:

    Presentation: 30%
    Questions about readings: 20%
    Final paper: 50%

### Questions

Please register on the forum on CMS.

Starting from the fourth week, every student submits one question about the readings by Thursday noon.
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

The report should be uploaded via CMS. The due date is October 13, 2024, 23:59.

Everyone is expected to report on their project idea in the June 14, 2024, session, and to participate in discussion to give feedback to other students' ideas. Feel free to come up with any ideas that might be interesting. Students may prepare a short slide deck on their idea. This will not be graded; the June 14 session is intended to help improve and finetune project ideas.

## Contact

Please contact Xinting (xhuang@lst.uni-saarland.de) or Michael (mhahn@lst.uni-saarland.de) for any questions.

## Accommodations

If you need any accommodations due to a disability or chronic illness, please either contact Michael at mhahn@lst.uni-saarland.de or the [Equal Opportunities and Diversity Management Unit](https://www.uni-saarland.de/en/administration/diversity.html) of the university.

