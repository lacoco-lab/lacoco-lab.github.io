# Aligning Language Models with Human Preferences: Methods and Challenges

**Course Description:** We will look into the rapidly developing field of aligning language models with human preferences, a central ingredient in today's LLMs. In the narrow sense, this refers to the finetuning process by which language models , originally trained to predict the next token, are turned into chatbots and other systems that can meaningfully interact with humans. Here, technical ideas such as Reinforcement Learning from Human Feedback are relevant. In a broader sense, this refers to research on how we can ensure LLMs behave in ways that humans desire, e.g. follow social and ethical norms, and are robust to malevolent adversarial prompting.

We will read a diverse set of recent technical papers from this highly dynamic field.

Many of our readings will be quite technical. You will need a good background in NLP or machine learning in order to thrive in this course.

**Registration:**
If you are an LST / computational linguistics student, and want to take this class, you should directly register in the [Course Management System (CMS)](https://cms.sic.saarland/alignment_2024/).

If you are a Comuter Science student, you should initially register via the Computer Science department seminar registration system.

If you register for the class, you may either be directly admitted or waitlisted. We will make final decisions by the end of the first week of the Summer semester.

If you want to take the course, please email mhahn@lst.uni-saarland.de your top-3 preferences among the items in the syllabus. If you want, you are welcome to additionally mention any other topic that you would like to present. If you suggest something interesting, that may boost your chances of being admitted.

**Course Management System:** https://cms.sic.saarland/alignment_2024/

**Instructors:** Michael Hahn

**Time:** Tue 12:15–13:45

**Room:** Building C7.3, Seminarraum 1.12


## Format and requirements

This is a seminar course.
Starting from the fourth week, one or two students will present in each unit (except for one session). Every student will present exactly once.
We expect all students to read the readings every week. Every student submits one question about the readings by Monday noon.


## Syllabus

**Note: The syllabus is subject to change, botht the selection of topics and their order. We will discuss this in the first and second meeting.**

In each session, two students will together present two papers on a common topic.
  
| Date          | Topic               | Readings  | Slides  | Related Material | Presenter  |
| ------------- | ------------------- | ------- | ------- | --------------------- | ---------- |
| (1) 2024-04-16    | no class               |  |  |                | [Michael](https://www.mhahn.info/)   | 
| (2) 2024-04-23    | Introduction to (L)LMs               |   | [slides](session2.pdf)  |                 | [Michael](https://www.mhahn.info/)  | 
| (3) 2024-04-30    | no class |
<!--Session-->
| (4) 2024-05-07   
| Reinforcement lerning background                     | PPO: [Schulman et al 2017](https://arxiv.org/abs/1707.06347)            |           |    TBD |
|               |                     | RLHF:  [Ouyang et al 2022, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2022/hash/b1efde53be364a73914f58805a001731-Abstract-Conference.html)            |           |    TBD |
|               |  | AlpacaFarm: [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/5fc47800ee5b30b8777fdd30abcaaf3b-Abstract-Conference.html) | | TBD |
<!--Session-->
| (5) 2024-05-14   |  Further developments                   | DPO: [Rafailov et al, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/a85b405ed65c6477a4fe8302b5e06ce7-Abstract-Conference.html)            |           |    TBD |
|               |                     | PRO:  [AAAI 2024](https://arxiv.org/abs/2306.17492)           |           |    TBD |
|      |                     |   Aligning Language Models with Human Preferences via a Bayesian Approach [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/99b419554537c66bf27e5eb7a74c7de4-Abstract-Conference.html)           |           |    TBD |
|               |                     |    RRHF: Rank Responses to Align Language Models with Human Feedback [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/23e6f78bdec844a9f7b6c957de2aae91-Abstract-Conference.html)          |           |    TBD |
<!--Session-->
| (6) 2024-05-21  |                   |   Human Preferences Dataset [Ji et al 2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/4dbb61cb68671edc4ca3712d70083b9f-Abstract-Datasets_and_Benchmarks.html)           |           |    TBD |
|               |                     |     Fine-Grained Human Feedback Gives Better Rewards for Language Model Training [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/b8c90b65739ae8417e61eadb521f63d5-Abstract-Conference.html)         |           |    TBD |
<!--Session-->
| (7) 2024-05-28  |                  |     constitutional AI [Bai et al 2022, arXiV](https://arxiv.org/abs/2212.08073)         |           |    TBD |
|               |                     |  self-alignment [Sun et al 2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/0764db1151b936aca59249e2c1386101-Abstract-Conference.html)            |           |    TBD |
<!--Session-->
| (8) 2024-06-04  |  Limitations of Alignment                   |  Open Problems and Fundamental Limitations of Reinforcement Learning from Human Feedback [2023, arXiV](https://arxiv.org/abs/2307.15217)          |           |    TBD |
|               |   Theoretical limitations of Alignment    |   [arXiv 2023](https://arxiv.org/pdf/2304.11082.pdf)    |           |    TBD |
| (9) 2024-06-11    |   Alignment in Vision and Language Models                  |   InstructBLIP: Towards General-purpose Vision-Language Models with Instruction Tuning [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/9a6a435e75419a836fe47ab6793623e6-Abstract-Conference.html)           |           |    TBD |
|               |                     |    Cheap and Quick: Efficient Vision-Language Instruction Tuning for Large Language Models [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/5e84e4413268b713f0d4a1b23a9dae57-Abstract-Conference.html)         |           |    TBD |
<!--Session-->
| (10) 2024-06-18 |                     |   In-Context Impersonation Reveals Large Language Models' Strengths and Biases [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/e3fe7b34ba4f378df39cb12a97193f41-Abstract-Conference.html)           |           |    TBD |
|               |                     |              |           |    TBD |
<!--Session-->
| (11) 2024-06-25  |  Safety        |                     |   ProPILE: Probing Privacy Leakage in Large Language Models [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/420678bb4c8251ab30e765bc27c3b047-Abstract-Conference.html)           |           |    TBD |
|               | Transferable attacks on aligned LMs     |  [arXiV 2023](https://arxiv.org/abs/2307.15043)     |           |    TBD |
<!--Session-->
| (12) 2024-07-02  |                     |   TrojLLM: A Black-box Trojan Prompt Attack on Large Language Models [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/cf04d01a0e76f8b13095349d9caca033-Abstract-Conference.html)           |           |    TBD |
|               | Sleeper Agents     | [arXiV 2024](https://arxiv.org/abs/2401.05566)      |           |    TBD |
|               |  Interpretable Prompt Injection    |  [arXiV 2023](https://arxiv.org/abs/2311.01011)     |           |    TB
<!--Session-->
| (13) 2024-07-09 | Alignment beyond language                    |  Language Is Not All You Need: Aligning Perception with Language Models  [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/e425b75bac5742a008d643826428787c-Abstract-Conference.html)          |           |    TBD |
|               |                     |    Language Models Meet World Models: Embodied Experiences Enhance Language Models [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/ee6630dcbcff857026e474fc857aa9f0-Abstract-Conference.html)          |           |    TBD |
<!--Session-->
| (14) 2024-07-16 |   Hallucination, Unfaithfulness, Truthfulness                  |    Language Models Don't Always Say What They Think: Unfaithful Explanations in Chain-of-Thought Prompting [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/ed3fea9033a80fea1376299fa7863f4a-Abstract-Conference.html)          |           |    TBD |
|               |   Truthfulness         |  [TODO](https://arxiv.org/abs/2110.06674)        |           |    TBD |
|               |   Honesty as best policy         | [arXiV 2023](https://arxiv.org/abs/2312.01350)         |           |    TBD |
|               |    Lie detection        |  [arXiV 2023](https://arxiv.org/abs/2309.15840)        |           |    TBD |
|               |   Faithfulness in CoT        |  [arXiV 2023](https://arxiv.org/abs/2307.13702)        |           |    TBD |
|               |  Sycophancy    | [arXiV 2023](https://arxiv.org/pdf/2310.13548.pdf)      |           |    TBD |
|               |                     |    Inference-Time Intervention: Eliciting Truthful Answers from a Language Model [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/81b8390039b7302c909cb769f8b6cd93-Abstract-Conference.html)          |           |    TBD |
<!--Session-->
| (16) 2024-07-23  |  Measuring Alignment                   |   MoCa: Measuring Human-Language Model Alignment on Causal and Moral Judgment Tasks [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/f751c6f8bfb52c60f43942896fe65904-Abstract-Conference.html)           |           |    TBD |
|               |                     |   ETHICS dataset [ICLR 2021](https://arxiv.org/pdf/2008.02275.pdf)           |           |    TBD |
|               |           | Whose opinions do LMs reflect?  [TODO](https://arxiv.org/abs/2303.17548)        |           |    TBD |


### a few other readings we could consider

|  Safety                   | Setting the Trap: Capturing and Defeating Backdoors in Pretrained Language Models through Honeypots [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/e7938ede51225b490bb69f7b361a9259-Abstract-Conference.html)             |           |    TBD |
|               |                     |  Defending Pre-trained Language Models as Few-shot Learners against Backdoor Attacks [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/677c8dc72c99482507323f313faf4738-Abstract-Conference.html)            |           |    TBD |


- Scaling Laws[2020, arXiV](https://arxiv.org/abs/2001.08361) 
- Language Models as Agent Models [TODO](https://arxiv.org/abs/2212.01681) 
- LMs helping align humans : [NeurIPS 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/f978c8f3b5f399cae464e85f72e28503-Abstract-Conference.html) 

- A General Language Assistant as a Laboratory for Alignment https://arxiv.org/abs/2112.00861
- 

- On Evaluating Adversarial Robustness of Large Vision-Language Models [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/a97b58c4f7551053b0512f92244b0810-Abstract-Conference.html) 

- using LLMs to find problems in ML systems: 
Mass-Producing Failures of Multimodal Systems with Language Models [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/5d570ed1708bbe19cb60f7a7aff60575-Abstract-Conference.html)

- Large Language Models of Code Fail at Completing Code with Potential Bugs [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/819cebb05f993840e8a52d7564c5c282-Abstract-Conference.html)

- finetuning over the internet [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/28bf1419b9a1f908c15f6195f58cb865-Abstract-Conference.html)

- Is Your Code Generated by ChatGPT Really Correct? Rigorous Evaluation of Large Language Models for Code Generation [2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/43e9d647ccd3e4b7b5baab53f0368686-Abstract-Conference.html)

- Failures of Safety Training [Wei et al 2023, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/fd6613131889a4b656206c50a8bd7790-Abstract-Conference.html)

- 

- LLMs leaking sensitive information [e.g. something here](https://scholar.google.com/scholar?hl=de&as_sdt=0%2C5&q=LLMs+leaking+sensitive+information&btnG=)

- Red Teaming LLMs [e.g., something here](https://scholar.google.com/scholar?hl=de&as_sdt=0%2C5&q=red+teaming+llms&btnG=)

- LLama adapter [TODO](https://arxiv.org/abs/2303.16199)





- alignment in vision

Hallucinations

- Tian et al, Fine-tuning Language Models for Factuality

- DPO



- Mechanistic Interpretability

- jailbreaking
- -- https://arxiv.org/abs/2310.06474
- -- https://arxiv.org/abs/2311.09827 (0 citations)
- -- https://arxiv.org/abs/2310.03684 (8 citations)
- -- https://arxiv.org/abs/2305.14950 (11 citations)

- hallucination

- vulnerabilities of open source LLMs https://arxiv.org/abs/2311.09447

surveys

- https://arxiv.org/abs/2309.15025
- https://arxiv.org/abs/2307.12966

??

- https://arxiv.org/abs/2302.14045
- https://arxiv.org/abs/2304.07327
- https://arxiv.org/abs/2212.10560
- https://arxiv.org/abs/2308.05374
- https://arxiv.org/abs/2310.02949
- https://arxiv.org/abs/2307.15043
- https://arxiv.org/abs/2308.09662 Red Teaming (12 citations)
- 


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

Starting from the fourth week (Nov 13), every student submits one question about the readings by Monday noon.
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

Aim for 40-60 minutes of presentation, allowing 30-40 minutes of discussion.
If you present on your own, your presentation can be somewhat shorter.
Discussion should happen not just after the presentation, but you should engage the audience and create ample opportunity for discussion during your presentation.
Before the presentation, take a look at the questions that have been posted in the forum and refer to these as needed. These may be useful for getting discussion started.
Conversely, when attending other students' talks, reciprocate by participating actively in the discussion.


### Term Papers

**Note: We will discuss this in the first and second meeting. Requirements may be changed based on popular demand.**

Term papers will be about a small independent project.
You will investigate a question about LLMs' cognitive ability via prompting. For instance, you might test their ability to perform a certain kind of reasoning, or investigate how they respond to certain kinds of stimuli.

Option 1: You may develop your own question and prompts. In this case, you will be expected to design at least 25 (not more than 50) prompts.

Option 2: You may draw on a larger existing benchmark. In this case, you will be expected to find some new angle on the benchmark, e.g., by tweaking the stimuli or by evaluating the LLM's behavior in a different way.

The report is expected to contain a brief literature review, motivation of your question, a description of your prompts, and evaluation of the LLM's behavior. The report is expected to include quantitative evaluation of the LLM's behavior (e.g., using measures such as accuracy). Additionally including qualitative evaluation can also be beneficial.



The report should have 8 pages of main report, plus unlimited appendix. The main report should be self-contained, but you can use the appendix to report prompts, further analyses, or other material.

The report should be uploaded via CMS. The due date is April 8, 2024, 23:59.

Everyone is expected to report on their project idea in the December 19, 2023, session, and to participate in discussion to give feedback to other students' ideas. Students may prepare a short slide deck on their idea. This will not be graded; the December 19 session is intended to help improve and finetune project ideas.

## Contact

Please contact Michael (mhahn@lst.uni-saarland.de) for any questions.

## Accommodations

If you need any accommodations due to a disability or chronic illness, please either contact Michael at mhahn@lst.uni-saarland.de or the [Equal Opportunities and Diversity Management Unit](https://www.uni-saarland.de/en/administration/diversity.html) of the university.

