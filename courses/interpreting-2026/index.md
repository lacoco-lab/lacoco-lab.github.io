# Interpreting and Analyzing Neural Language Models

<!-----DESCRIPTION----->
**Course Description:**
Despite their success, neural language models are still often treated as “black boxes”. This seminar focuses on post-hoc interpretability for transformer-based language models: understanding how models solve problems or why they behave in certain way with techniques like probing representations, attributing outputs to inputs, identifying computational circuits, and testing explanations through causal interventions. We will also combine these methods with recent applications to model editing, behavioral control, context use in retrieval-augmented generation, reasoning, and agent monitoring. Readings include academic papers and research posts.

<!----PREREQ------------>

**Prerequisites:**
Many of our readings will be quite technical. You will need a good background in NLP or machine learning in order to thrive in this course.

<!-----REGISTRATION----->

**Registration:**
* If you are an **LST / CoLi** student, and want to take this class, you should directly register in the [Course Management System (CMS)](https://cms.sic.saarland/probing_2627/). Admissions decision will be made around the end of the first week of the semester.

* If you are a **Computer Science** student, you should initially register via the Computer Science department seminar registration system. Only register in [Course Management System (CMS)](https://cms.sic.saarland/probing_2627/) once you were selected by the assignment system or otherwise admitted by us.

* **In both cases**, please fill in this [form](https://docs.google.com/forms/d/e/1FAIpQLSe-Pjf4nz0FIgXHYS7wh00i0DYnwtpzFW9XZSiiqDq2o_DIZw/viewform?usp=publish-editor) with your top-3 preferences among the items in the syllabus, and a brief explanation why you want to take this course and feel prepared for it. If you want, you are welcome to additionally mention any other topic that you would like to present.

<!-----INSTRUCTORS----->
**Instructors:** [Xinting Huang](https://lacoco-lab.github.io/home/authors/xhuang/)

<!-----TIME----->
**Time:** Tuesday, 14:15 - 15:45

<!-----ROOM----->
**Room:** C7.3 room 1.14


## Format and requirements

This is a seminar course.
After the introductory class, two students will present in each reading unit. Every student will present exactly once.
We expect all students to read the readings every week. Every student submits one question about the readings by Monday noon.


## Syllabus

| Date | Unit | Topic | Readings | Presenter | <small>Optional Material</small> |
| --- | --- | --- | --- | --- | --- |
| October 20, 2026 |  | no class |  |  |  |
| October 27, 2026 | 0 | Introduction, Q&A |  |  |  |
| November 3, 2026 | 1 | Transformer computations | [A Mathematical Framework for Transformer Circuits](https://transformer-circuits.pub/2021/framework/index.html) (2021; selected sections below) |  | <small>[Induction Heads](https://transformer-circuits.pub/2022/in-context-learning-and-induction-heads/index.html); [RASP](https://arxiv.org/abs/2106.06981)</small> |
|  |  | Vocabulary projections | [Eliciting Latent Predictions from Transformers with the Tuned Lens](https://arxiv.org/abs/2303.08112) (2023) |  | <small>[Logit Lens](https://www.lesswrong.com/posts/AcKRB8wDpdaN6v6ru/interpreting-gpt-the-logit-lens); [MLP vocabulary projections](https://arxiv.org/abs/2203.14680)</small> |
| November 10, 2026 | 2 | Probing | [Emergent World Representations: Exploring a Sequence Model Trained on a Synthetic Task](https://arxiv.org/abs/2210.13382) (2022) |  | <small>[Control Tasks](https://arxiv.org/abs/1909.03368); [BERT’s NLP Pipeline](https://arxiv.org/abs/1905.05950)</small> |
|  |  |  Probing | [Detecting Strategic Deception Using Linear Probes](https://arxiv.org/abs/2502.03407) (2025) |  | <small>[Deception Probe Benchmark](https://arxiv.org/abs/2507.12691)</small> |
| November 17, 2026 | 3 | Path patching | [Interpretability in the Wild: a Circuit for Indirect Object Identification in GPT-2 Small](https://arxiv.org/abs/2211.00593) (2022) |  | <small>[Causal Abstractions](https://proceedings.neurips.cc/paper/2021/hash/4f5c422f4d49a5a807eda27434231040-Abstract.html); [Path Patching](https://arxiv.org/abs/2304.05969)</small> |
|  |  | Activation patching; Model editing | [Locating and Editing Factual Associations in GPT](https://arxiv.org/abs/2202.05262) (2022) |  | <small>[Distributed Alignment Search](https://arxiv.org/abs/2303.02536)</small> |
| November 24, 2026 | 4 | Sparse autoencoders | [Towards Monosemanticity: Decomposing Language Models With Dictionary Learning](https://transformer-circuits.pub/2023/monosemantic-features/index.html) (2023; selected sections below) |  | <small>[Scaling Monosemanticity](https://transformer-circuits.pub/2024/scaling-monosemanticity/index.html)</small> |
|  |  | Sparse autoencoders | [Are Sparse Autoencoders Useful? A Case Study in Sparse Probing](https://arxiv.org/abs/2502.16681) (2025) |  |  |
| December 1, 2026 | 5 | Circuit tracing | [Circuit Tracing: Revealing Computational Graphs in Language Models](https://transformer-circuits.pub/2025/attribution-graphs/methods.html) (2025; selected sections below) |  | <small>[Transcoders](https://arxiv.org/abs/2406.11944)</small> |
|  |  | Circuit tracing | [On the Biology of a Large Language Model](https://transformer-circuits.pub/2025/attribution-graphs/biology.html) (2025; selected sections below) |  |  |
| December 8, 2026 | 6 | Task representations | [Function Vectors in Large Language Models](https://arxiv.org/abs/2310.15213) (2023) |  | <small>[Task Vectors](https://arxiv.org/abs/2310.15916)</small> |
|  |  | Refusal steering | [Refusal in Language Models Is Mediated by a Single Direction](https://arxiv.org/abs/2406.11717) (2024) |  |  |
| December 15, 2026 | 7 | Persona monitoring | [Persona Vectors: Monitoring and Controlling Character Traits in Language Models](https://arxiv.org/abs/2507.21509) (2025) |  | <small>[Persona Features](https://arxiv.org/abs/2506.19823)</small> |
|  |  | Training-data attribution | [Scalable Influence and Fact Tracing for Large Language Model Pretraining](https://arxiv.org/abs/2410.17413) (2024) |  | <small>[LLM Influence Functions](https://arxiv.org/abs/2308.03296); [Concept Influence](https://arxiv.org/abs/2602.14869); [DATE-LM](https://arxiv.org/abs/2507.09424)</small> |
| December 22, 2026 |  | no class |  |  |  |
| December 29, 2026 |  | no class |  |  |  |
| January 5, 2027 | 8 | Context attribution | [Attributing Response to Context: A Jensen–Shannon Divergence Driven Mechanistic Study of Context Attribution in Retrieval-Augmented Generation](https://proceedings.iclr.cc/paper_files/paper/2026/hash/ed67dff7cb96e7e86c4d91c0d5db49bb-Abstract-Conference.html) (2025) |  | <small>[Inseq](https://aclanthology.org/2023.acl-demo.40/); [Integrated Gradients](https://arxiv.org/abs/1703.01365); [Contrastive Explanations](https://aclanthology.org/2022.emnlp-main.14/)</small> |
|  |  | Activation explanations | [Natural Language Autoencoders Produce Unsupervised Explanations of LLM Activations](https://transformer-circuits.pub/2026/nla/index.html#introduction) (2026; selected sections below) |  | <small>[InversionView](https://arxiv.org/abs/2405.17653)</small> |
| January 12, 2027 | 9 | Reasoning step attribution | [Thought Anchors: Which LLM Reasoning Steps Matter?](https://arxiv.org/abs/2506.19143) (2025) |  |  |
|  |  | Reasoning faithfulness | [Reasoning Models Don't Always Say What They Think](https://arxiv.org/abs/2505.05410) (2025) |  | <small>[Unfaithful CoT](https://proceedings.neurips.cc/paper_files/paper/2023/hash/ed3fea9033a80fea1376299fa7863f4a-Abstract-Conference.html)</small> |
| January 19, 2027 | 10 | Auditing hidden objectives | [Auditing Language Models for Hidden Objectives](https://arxiv.org/abs/2503.10965) (2025) |  |  |
|  |  | Reward hacking detection |  [Monitoring and Discovering Reward Hacking with Internal Representations during LLM Evaluations](https://arxiv.org/abs/2609.19101) (2026) |  | <small>[Acompanying blogpost](https://www.goodfire.com/research/reward-hacking-activation-monitors); [Probe Monitor Guide](https://www.goodfire.com/blog/probe-monitors-101)</small> |

### Reading guidance

For readings without a selection below, read the main text, including figures and limitations; references, appendices, and supplementary material are optional. You are encouraged to check additional methodological details when needed to explain or assess a result.

The selections below are roughly a conference paper's worth of reading. Section ranges include all subsections, figures, and captions. Everything else is optional. These selections are approximate; you may need to skim relevant passages in other sections to understand the assigned sections.

* **A Mathematical Framework for Transformer Circuits:** Read from “Transformer Overview” through the end of “One-Layer Attention-Only Transformers”, then read “Induction Heads”.

* **Towards Monosemanticity: Decomposing Language Models With Dictionary Learning:** Read from the beginning through the end of “Detailed Investigations of Individual Features” (stop before “Global Analysis”).

* **Circuit Tracing: Revealing Computational Graphs in Language Models:** Read from the beginning through the end of “Attribution Graphs” (stop before “Global Weights”). Skim “Limitations”.

* **On the Biology of a Large Language Model:** Read from the beginning through the end of “Planning in Poems”, then read “Entity Recognition and Hallucinations”, “Refusals”, and “Limitations”.

* **Natural Language Autoencoders Produce Unsupervised Explanations of LLM Activations:** Read from the beginning through the end of “Characterizing NLA confabulations”, then read “Discussion and Limitations”.


## Evaluation

***IMPORTANT: Study programs may differ in which version(s) of a seminar course you can take. If in doubt, check with your study program coordinator.***

For students taking the seminar for 4 credits:

    Presentation: 60%
    Questions about readings: 40%

For students taking the seminar for 7 credits:

    Presentation: 30%
    Questions about readings: 20%
    Final paper: 50%

### Questions

Please register on the forum on CMS, and write questions there (click "forum" at the top after logging in CMS)

Starting with the first reading unit, every student submits one question about the readings by Monday noon.
Questions are graded on a 3-point scale, 0: no question submitted, 1: superficial question, 2: insightful question (insightful questions don't mean long questions). Students can also submit more than one questions, the grade will be calculated as the highest score among questions（So you can also ask some basic questions that you want clarification).

### Presentations

We expect that presentations will cover the key points from the readings, such as the main evidence for and against the key claims under consideration in the paper.

We do not expect that presentations will cover all details of the papers. Rather, you should focus on big picture findings and conclusions, and are not expected to include every finding from the paper in your presentation. Select what you consider the key points.

Make sure to motivate the papers' research question(s).
Give background on key concepts, and convey to the audience your understanding of why certain research decisions were made.

Critically engage with the reading: contribute your own opinion on the key findings, and on the paper's motivation and arguments. In what ways do or don't you agree with arguments made by the authors?

As you'll be presenting in teams of two, don't just present the two papers separately, but make sure to also draw connections and compare if two papers are related.

Aim for 50-60 minutes of presentation (sum of two papers), allowing 30-40 minutes of discussion. You will have sufficient time, so avoid speaking too fast for others to keep up, make sure your audience is following. Making presentation is to convey information, if audience cannot follow, it's waste of time for both sides.

Generating and moderating in-class discussion is a key component of your presentation -- thinking about what will be interesting to your audience will thus be important.

Discussion should happen not just after the presentation, but you should engage the audience and create ample opportunity for discussion during your presentation.

Before the presentation, take a look at the questions that have been posted in the forum and refer to these as needed. You are not expected to answer each question, feel free to cluster similar questions and discuss them during your presentation. These may be useful for getting discussion started.
Conversely, when attending other students' talks, reciprocate by participating actively in the discussion.


### Final Papers (for the 7CP version)

**Note: We will discuss this in the first meeting. Requirements may be changed based on popular demand.**

Term papers will be about a small independent project.

You will investigate some interpretability question about neural networks.
You could investigate an existing model, or train and interpret a model of your own.
You could use an existing method or try to come up with some new analysis approach.
You could also compare different analysis approaches, or investigate interpretability from a theoretical angle.

The report is expected to contain a brief literature review, motivation of your study, a description of what you did, and you found. It's recommended to include quantitative validation of what you found, so that you show it's not an illusion.

<!-- The report is expected to include quantitative evaluation of the LLM's behavior (e.g., using measures such as accuracy). Additionally including qualitative evaluation can also be beneficial. -->



The report should have 8 pages of main report, plus unlimited appendix, in the NeurIPS style format. The main report should be self-contained, but you can use the appendix to report prompts, further analyses, or other material.

The report should be uploaded via CMS. The due date is TBD (usually around the beginning of next semester).

## Contact

Please contact Xinting (xhuang@lst.uni-saarland.de) or Michael (mhahn@lst.uni-saarland.de) for any questions.

## Accommodations

If you need any accommodations due to a disability or chronic illness, please either contact Michael at mhahn@lst.uni-saarland.de or the [Equal Opportunities and Diversity Management Unit](https://www.uni-saarland.de/en/administration/diversity.html) of the university.
