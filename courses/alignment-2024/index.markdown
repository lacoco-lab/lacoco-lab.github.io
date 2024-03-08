# Aligning Language Models with Human Preferences: Methods and Challenges

**Course Description:** We will look into the rapidly developing field of aligning language models with human preferences, a central ingredient in today's LLMs. In the narrow sense, this refers to the finetuning process by which language models , originally trained to predict the next token, are turned into chatbots and other systems that can meaningfully interact with humans. Here, technical ideas such as Reinforcement Learning from Human Feedback are relevant. In a broader sense, this refers to research on how we can ensure LLMs behave in ways that humans desire, e.g. follow social and ethical norms, and are robust to malevolent adversarial prompting.

We will read a diverse set of recent technical papers from this highly dynamic field.

Many of our readings will be quite technical.

**Registration:**
If you are an LST / computational linguistics student, and want to take this class, you should directly register in the [Course Management System (CMS)](https://cms.sic.saarland/alignment_2024/).

If you are a Comuter Science student, you should initially register via the Computer Science department seminar registration system.

If you register for the class, you may either be directly admitted or waitlisted. We will make final decisions by the end of the first week of the Summer semester.

**Course Management System:** https://cms.sic.saarland/alignment_2024/

**Instructors:** Michael Hahn

**Time:** Tue 12:15–13:45

**Room:** Building C7.3, Seminarraum 1.12


## Format and requirements

This is a seminar course.
Starting from the fourth week, one or two students will present in each unit (except for one session). Every student will present exactly once.
We expect all students to read the readings every week. Every student submits one question about the readings by Monday noon.


## Syllabus

**Note: The syllabus is subject to change. We will discuss this in the first and second meeting.**
  
| Date          | Topic               | Readings  | Slides  | Optional Material | Presenter  |
| ------------- | ------------------- | ------- | ------- | --------------------- | ---------- |
| 2023-10-24    | First Meeting               |  |  |                | [Michael](https://www.mhahn.info/)   | 
| 2023-10-31    | no class               |  |  |                |          | 
| 2023-11-07    | Introduction to (L)LMs               |   | [slides](session2.pdf)  |                 | [Michael](https://www.mhahn.info/)  | 

- RLHF [Ouyang et al 2022, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2022/hash/b1efde53be364a73914f58805a001731-Abstract-Conference.html)

- constitutional AI [Bai et al 2022, arXiV](https://arxiv.org/abs/2212.08073)

- RL background: PPO [Schulman et al 2017](https://arxiv.org/abs/1707.06347)

- DPO [Rafailov et al, NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/a85b405ed65c6477a4fe8302b5e06ce7-Abstract-Conference.html)

Hallucinations

- Tian et al, Fine-tuning Language Models for Factuality

- DPO

- Limitations of Alignment [TODO 2023, arXiV](https://arxiv.org/pdf/2304.11082.pdf)

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

