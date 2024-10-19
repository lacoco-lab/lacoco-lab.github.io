# Augmenting Language Models with Tools and Knowledge

<!-----DESCRIPTION----->
**Course Description:**
Large Language Models such as ChatGPT or Claude have transformed natural language processing, and AI more broadly. However, language models on their own cannot be easily updated with new knowledge, and their abilities at complex reasoning are limited. This seminar looks into ongoing research on augmenting language models with external knowledge, updating their knowledge, and allowing them to draw on external tools to boost their reasoning abilities.

<!----PREREQ------------>

**Prerequisites:**
Many of our readings will be quite technical. You will need a good background in NLP or machine learning in order to thrive in this course.

<!-----REGISTRATION----->

**Registration:**
* If you are an **LST / CoLi** student, and want to take this class, you should directly register in the [Course Management System (CMS)](https://cms.sic.saarland/knowledge_24/). You may either be directly admitted or waitlisted.

* If you are a **Computer Science** student, you should initially register via the Computer Science department seminar registration system. If you want to take the seminar but were not selected by the assignment system, please apply for the waiting list by emailing xhuang@lst.uni-saarland.de. Only register in [Course Management System (CMS)](https://cms.sic.saarland/knowledge_24/) once you were selected by the assignment system or otherwise admitted by us.

* **In both cases**, please email xhuang@lst.uni-saarland.de (with cc to mhahn@lst.uni-saarland.de) your top-3 preferences among the items in the syllabus, and a brief explanation why you want to take this course and feel prepared for it. If you want, you are welcome to additionally mention any other topic that you would like to present. If you suggest something interesting, that may boost your chances of being admitted.


<!----CMS------------>

**Course Management System:** [CMS](https://cms.sic.saarland/knowledge_24/)

<!-----INSTRUCTORS----->
**Instructors:** [Xinting Huang](https://lacoco-lab.github.io/home/authors/xhuang/)

<!-----TIME----->
**Time:** Thu 12:15-13:45

<!-----ROOM----->
**Room:** Building C7.2, Room 1.12


## Format and requirements

This is a seminar course.
Starting from the fourth week, one or two students will present in each unit. Every student will present exactly once.
We expect all students to read the readings every week. Every student submits one question about the readings by Wednesday noon.


## Syllabus

Note: The syllabus is still subject to change.

In each session, two students will together present two papers (in the "Readings" column) on a common topic. **The optional material is for the Topic, rather than being specific to a particular paper**.



| Date          | Topic               | Readings  | Slides  | Optional Material | Presenter  |
| ------------- | ------------------- | ------- | ------- | --------------------- | ---------- |
|  2024-10-17    | no class               |  |  |                |          | 
|  2024-10-24    | no class |  |  |  |  |
| 2024-10-31    | Introduction to Transformers and (L)LMs               |   |  [slides](https://github.com/lacoco-lab/lacoco-lab.github.io/blob/main/courses/alignment-2024/session2.pdf) |              | Xinting   | 
| 2024-11-07    | RAG I           | Dense Passage Retrieval for Open-Domain Question Answering [Karpukhin et al.](https://arxiv.org/abs/2004.04906)       |       |         |  Viet Anh    |
|               |                     | Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks [Lewis et al.](https://arxiv.org/abs/2005.11401)    |       |     |   Muhammad Ebad Ullah   |
| 2024-11-14    | RAG II              |  Improving language models by retrieving from trillions of tokens (Retro) [Borgeaud et al.](https://arxiv.org/abs/2112.04426)       |         |        [Izacard et al.](https://arxiv.org/abs/2208.03299)              |        Zhenyu     |
|             |                  | REPLUG: Retrieval-Augmented Black-Box Language Models [Shi et al.](https://arxiv.org/abs/2301.12652) |    |    |  Alena  |
|  2024-11-21    |       Better Query for RAG   |   Query Rewriting for Retrieval-Augmented Large Language Models  [Ma et al.](https://arxiv.org/abs/2305.14283)   |         |             |    Entang         |
|             |                  | Precise Zero-Shot Dense Retrieval without Relevance Labels [Gao et al.](https://arxiv.org/abs/2212.10496) |    |    |  Prathvish  |
| 2024-11-28    |  Adaptive Retrieval  | Active Retrieval Augmented Generation [Jiang et al.](https://arxiv.org/abs/2305.06983)        |         |               |    Wadah          |
|               |                     | Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection [Asai et al.](https://arxiv.org/abs/2310.11511)      |         |                       |     Zaynab        |
| 2024-12-05    |   Rearranged RAG pipelines                  | Enhancing Retrieval-Augmented Large Language Models with Iterative Retrieval-Generation Synergy [Shao et al.](https://arxiv.org/abs/2305.15294)     |     |   |   TBD  |
|               |                | Demonstrate-Search-Predict: Composing retrieval and language models for knowledge-intensive NLP [Khattab et al.](https://arxiv.org/abs/2212.14024)  | |  | Muhammad Usama |
| 2024-12-12 | Project Ideas | | |  | Everyone |
| 2024-12-19    | RAG and CoT     | Interleaving Retrieval with Chain-of-Thought Reasoning for Knowledge-Intensive Multi-Step Questions [Trivedi et al.](https://arxiv.org/abs/2212.10509) | | | TBD |
|               |                     | RAT: Retrieval Augmented Thoughts Elicit Context-Aware Reasoning in Long-Horizon Generation [Wang et al.](https://arxiv.org/abs/2403.05313) |   |  | TBD |
| 2024-12-26 | no class
| 2025-01-02 | no class
| 2025-01-09    |  Generate rather than Retrieve    | Generate rather than Retrieve: Large Language Models are Strong Context Generators [Yu et al.](https://arxiv.org/abs/2209.10063)      |       |        |    TBD  |
|               |                     |  Augmented Large Language Models with Parametric Knowledge Guiding [Luo et al.](https://arxiv.org/abs/2305.04757)     |       |        |  TBD   |
| 2025-01-16    | Tool-augmented LLMs I                 | Toolformer: Language Models Can Teach Themselves to Use Tools [Schick et al.](https://arxiv.org/abs/2302.04761)    |       |   [Paranjape et al.](https://arxiv.org/abs/2303.09014)    | Nicholas      | 
|               |                     |  Chameleon: Plug-and-Play Compositional Reasoning with Large Language Models [Lu et al.](https://arxiv.org/abs/2304.09842)    |      |  | TBD |
| 2025-01-23    |   Tool-augmented LLMs II                  |  ReAct: Synergizing Reasoning and Acting in Language Models [Yao et al.](https://arxiv.org/abs/2210.03629)   |       |   [Gu et al.](https://arxiv.org/abs/2402.14672)     |   Paranjoy   |
|               |                     |   ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs [Qin et al.](https://arxiv.org/abs/2307.16789)   |       |   [Liang et al.](https://arxiv.org/abs/2303.16434)     |  TBD   |
| 2025-01-30    |  Tool-augmented LLMs III                   | WebGPT: Browser-assisted question-answering with human feedback [Nakano et al.](https://arxiv.org/abs/2112.09332)     |       |   StructGPT [Jiang et al.](https://arxiv.org/abs/2305.09645)     |   TBD  |
|               |                     |  MATHSENSEI: A Tool-Augmented Large Language Model for Mathematical Reasoning  [Das et al.](https://arxiv.org/abs/2402.17231)  |       |        |  TBD   |







In addition, here are some more paper highly related to the topic of this seminar (optional material):

[Retrieve and compress](https://arxiv.org/abs/2310.04408),
[Evaluator model assess the quality followed by different actions](https://arxiv.org/abs/2401.15884), 
[Integration of RAG and fine-tuning](https://arxiv.org/abs/2310.01352), 
[Analysis about how factors of retireved doc affect performance](https://arxiv.org/abs/2401.14887);

[Prompt Retriever](https://arxiv.org/abs/2303.08518);

[Benchmark for Tool-augmented LLMs](https://arxiv.org/abs/2304.08244), [Dataset for QA with Tools](https://arxiv.org/pdf/2306.13304).

  

## Evaluation

Important: Please make sure that your study program's regulations allow taking whichever version of the course (4 or 7 CP) you want to take.

For students taking the seminar for 4 credits:

    Presentation: 60%
    Questions about readings: 40%

For students taking the seminar for 7 credits:

    Presentation: 30%
    Questions about readings: 20%
    Final paper: 50%

### Questions

Please register on the forum on CMS.

Starting from the fourth week, every student submits one question about the readings by Wednesday noon.
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

Details TBD

The report is expected to contain a brief literature review, motivation of your study, a description of what you did, and you found. It's recommended to include quantitative validation of what you found, so that you show it's not an illusion.


The report should have 8 pages of main report, plus unlimited appendix, in the NeurIPS style format. The main report should be self-contained, but you can use the appendix to report prompts, further analyses, or other material.

The report should be uploaded via CMS. The due date is April 10, 2025.

Everyone is expected to report on their project idea in the 2024-12-12, session, and to participate in discussion to give feedback to other students' ideas. Feel free to come up with any ideas that might be interesting. Students may prepare a short slide deck on their idea. This will not be graded; the June 14 session is intended to help improve and finetune project ideas.

## Contact

Please contact Xinting (xhuang@lst.uni-saarland.de) or Michael (mhahn@lst.uni-saarland.de) for any questions.

## Accommodations

If you need any accommodations due to a disability or chronic illness, please either contact Michael at mhahn@lst.uni-saarland.de or the [Equal Opportunities and Diversity Management Unit](https://www.uni-saarland.de/en/administration/diversity.html) of the university.

