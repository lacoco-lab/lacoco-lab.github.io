# Compositionality DRAFT

**Course Description:** Compositionality --- roughly, the ability to correctly process wholes given the ability to correctly process their parts --- is a core property of human cognition and especially natural language, where it enables ``infinite use of finite means'' (von Humboldt 1836, as quoted by Chomsky
1965). Recent advances in modeling natural language have raised new questions in this domain: are modern artificial neural networks capable of compositional generalization --- and for that matter, how capable are humans? This blockseminar briefly reviews foundational and recent work on the core scientific question of compositionality.

**Course Management System:** [CMS](https://cms.sic.saarland/langmod_cogmod_ws23/) TODO 

**Instructors:** [Kate McCurdy](https://kmccurdy.github.io/)

**Time:** Block Seminar TODO

**Room:** TBD


## Format and requirements

This is a block seminar course.

Every student will give a XXX-minute presentation.

?? We expect all students to read the readings every week. Every student submits one question about the readings by Monday noon.


## Syllabus

**Note: The syllabus is subject to change. We will discuss this in the first and second meeting.**


paper collection

somewhat naively, a few papers that I know (to different degrees) -- there is no need to include any of these in the syllabus

Kim and Linzen, COGS https://arxiv.org/abs/2010.05465

Hupkes et al, Compositionality Decomposed: How do Neural Networks Generalise?  https://www.jair.org/index.php/jair/article/view/11674

Hupkes et al, A taxonomy and review of generalization research in NLP https://www.nature.com/articles/s42256-023-00729-y

Baroni, Linguistic generalization and compositionality in modern artificial neural networks https://royalsocietypublishing.org/doi/full/10.1098/rstb.2019.0307

Lindemann et al, Compositional Generalization without Trees using Multiset Tagging and Latent Permutations https://arxiv.org/abs/2305.16954

### Preliminary topics

- What is compositionality?
  - different views in linguistics -[Herbelot 2020](https://thegradient.pub/how-to-stop-worrying-about-compositionality-2)
  - ? in current philosophy - [Szabo 2020](https://plato.stanford.edu/entries/compositionality/)
  - a working approach in NLP - [Bender et al 2015](https://aclanthology.org/W15-0128)
  - ? a recent philosophical treatment w/r/t machine learning - [Nefdt 2020](https://doi.org/10.1007/s11023-020-09519-6)
- Do ANNs achieve compositional generalization? - evidence of problems
  - an early overview - [Baroni 2019](https://royalsocietypublishing.org/doi/full/10.1098/rstb.2019.0307)
  - ? COGS, an influential benchmark - [Kim and Linzen 2020](https://aclanthology.org/2020.emnlp-main.731)
  - ? maybe not a problem after all - [Csordas et al, 2021](https://aclanthology.org/2021.emnlp-main.49)
  - SLOG, a recent update - [Li et al 2023](https://aclanthology.org/2023.emnlp-main.194/)
- Foundational issue: abstraction
  - Rule- vs exemplar-based generalization - [Dasgupta et al 2022](https://proceedings.mlr.press/v162/dasgupta22b.html)
  - Information compression and model capacity - [Resnick et al 2020](https://www.ifaamas.org/Proceedings/aamas2020/pdfs/p1125.pdf)
  - Trade-off with variation - [Conklin and Smith 2023](https://openreview.net/pdf?id=-Yzz6vlX7V-)
- Some approaches to increasing ANN compositionality
  - Data augmentation - [Akyurek and Andreas 2023](https://aclanthology.org/2023.acl-long.38/)
  - Meta learning - will be discussed in human comparison part
  - TPRs, distributed representations for explicit composition - [Smolensky et al 2022](https://ojs.aaai.org/aimagazine/index.php/aimagazine/article/view/18599)
  - Neurosymbolic / program synthesis - pick some reference here TBD
- How compositional are humans anyway?
  - Humans generalize recursively to compose longer linguistic sequences than seen in training - [McCoy et al 2021](https://escholarship.org/uc/item/67z0195s)
  - Meta-learning better approximates human symbol mapping than symbolic composition - [Lake and Baroni 2023](https://www.nature.com/articles/s41586-023-06668-3)
  - ? Humans are biased toward abstraction, ANNs toward pattern-matching - [Kumar et al 2023](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1011316)
  - ? LMs are more logical than humans but repeat some fallacies - [Eisape et al 2023](https://arxiv.org/abs/2311.00445)
  - ? LMs show human-like content effects on reasoning tasks - [Dasgupta et al 2023](https://arxiv.org/abs/2207.07051)

  
| Date          | Topic               | Readings  | Slides  | Optional Material | Presenter  |
| ------------- | ------------------- | ------- | ------- | --------------------- | ---------- |


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

TODO Starting from the fourth week (Nov 13), every student submits one question about the readings by Monday noon.
Questions are graded on a 3-point scale (0: no question submitted, 1: superficial question, 2: insightful question).

### Presentations

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

TODO Aim for 40-60 minutes of presentation, allowing 30-40 minutes of discussion.
If you present on your own, your presentation can be somewhat shorter.
Discussion should happen not just after the presentation, but you should engage the audience and create ample opportunity for discussion during your presentation.
Before the presentation, take a look at the questions that have been posted in the forum and refer to these as needed. These may be useful for getting discussion started.
Conversely, when attending other students' talks, reciprocate by participating actively in the discussion.


### Term Papers

**Note: We will discuss this in the first and second meeting. Requirements may be changed based on popular demand.**

TODO Revise

Term papers will be about a small independent project.
You will investigate a question about LLMs' cognitive ability via prompting. For instance, you might test their ability to perform a certain kind of reasoning, or investigate how they respond to certain kinds of stimuli.

Option 1: You may develop your own question and prompts. In this case, you will be expected to design at least 25 (not more than 50) prompts.

Option 2: You may draw on a larger existing benchmark. In this case, you will be expected to find some new angle on the benchmark, e.g., by tweaking the stimuli or by evaluating the LLM's behavior in a different way.

The report is expected to contain a brief literature review, motivation of your question, a description of your prompts, and evaluation of the LLM's behavior. The report is expected to include quantitative evaluation of the LLM's behavior (e.g., using measures such as accuracy). Additionally including qualitative evaluation can also be beneficial.



The report should have 8 pages of main report, plus unlimited appendix. The main report should be self-contained, but you can use the appendix to report prompts, further analyses, or other material.

The report should be uploaded via CMS. The due date is TODO, 2024, 23:59.

Everyone is expected to report on their project idea in the December 19, 2023, session, and to participate in discussion to give feedback to other students' ideas. Students may prepare a short slide deck on their idea. This will not be graded; the December 19 session is intended to help improve and finetune project ideas.

## Contact

Please contact Kate (kmccurdy@lst.uni-saarland.de) or Michael (mhahn@lst.uni-saarland.de) for any questions.

## Accommodations

If you need any accommodations due to a disability or chronic illness, please either contact Michael at mhahn@lst.uni-saarland.de or the [Equal Opportunities and Diversity Management Unit](https://www.uni-saarland.de/en/administration/diversity.html) of the university.

