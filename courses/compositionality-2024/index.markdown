# Compositionality in Language and Computation 

**Course Description:** Compositionality --- roughly, the ability to correctly process wholes given the ability to correctly process their parts --- is a core property of human cognition and especially natural language, where it enables ``infinite use of finite means'' as known linguistic elements combine to produce novel words and sentences. Recent advances in Natural Language Processing have raised new questions in this domain: are modern artificial neural networks capable of compositional generalization --- and for that matter, how capable are humans? This blockseminar briefly reviews foundational and recent work on the core scientific question of compositionality.

If you want to take this class, please register in [CMS](https://cms.sic.saarland/composition_24/).

**Course Management System:** [CMS](https://cms.sic.saarland/composition_24/) 

**Instructors:** [Kate McCurdy](https://kmccurdy.github.io/). For any questions, please contact me by email: [kmccurdy@lst.uni-saarland.de](mailto:kmccurdy@lst.uni-saarland.de)

**Time (block seminar):** 1-4 pm Monday, Wednesday, and Friday; September 9-13, 2024.

In addition, there will be an introductory lecture + coordination session **3-5 pm Monday June 24**, in the Fishbowl, 3rd floor in C7 4.

**Room:** TBD


## Format and requirements

This is a block seminar course.

Every student will give a 30-minute presentation.

Students that do not present on a given day are expected to prepare a two-page high-level overview which summarizes the day's assigned reading and explains how the papers relate to each other. The summary should conclude with a question for discussion. These summaries will be submitted at the end of each classroom session.


## Syllabus

| Date          | Theme |  Reading               | Presenter/s  |
| ------------- | ------------------- | ------------------- | --------------------- | 
|  2024-09-09 | Defining compositionality  | [Herbelot 2020](https://thegradient.pub/how-to-stop-worrying-about-compositionality-2)   | Bao Di  |  
|    | Compositionality in ANNs| [Baroni 2019](https://royalsocietypublishing.org/doi/full/10.1098/rstb.2019.0307) | Joel Joachim Schnubel |  
|    | ... in emergent languages | [Chaabouni et al, 2020](https://arxiv.org/abs/2004.09124)  | Maximilian Jones Schmidt |  
| 2024-09-11 | Benchmarking compositionality | [Kim and Linzen 2020](https://aclanthology.org/2020.emnlp-main.731) | Amanda Silina |  
|    | Compositional representations | [McCoy et al, 2019](https://openreview.net/forum?id=BJx0sjC5FX) | Ansh Dawda | 
|    | More representations | [Lepori et al., 2023](https://proceedings.neurips.cc/paper_files/paper/2023/hash/85069585133c4c168c865e65d72e9775-Abstract-Conference.html) | Sundam Adnan Soomro |  
|    | Data structures | [Akyurek and Andreas 2023](https://aclanthology.org/2023.acl-long.38/) | Denys Pyshchai |   
|  2024-09-13  | Comparing to humans |[Lake and Baroni 2023](https://www.nature.com/articles/s41586-023-06668-3) | Daria Solovieva |  
|    |  | [Kumar et al, 2023](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1011316) | Verma Abhishek |  
|    |  | [Galke et al, 2024](https://arxiv.org/abs/2302.12239) | Anamika Sreeja Sadanandan |  


## Evaluation


For students taking the seminar for 4 credits:

    Presentation: 50%
    Reading summaries: 50%

For students taking the seminar for 7 credits:

    Presentation: 25%
    Reading summaries: 25%
    Final report: 50%


### Presentations

Given time limitations, presentations will be strictly kept to 10 minutes each, followed by a general discussion covering all of the papers. The presentation should focus on high-level points from the readings, such as the main argument and evidence for and against key claims under consideration.


### Term Papers

**Note: We will discuss this in the first meeting. Requirements may be changed based on popular demand.**

You will write a 6 page report (ACL format) on one of the two following topics:

  1. Is compositionality a significant concern for modern artificial neural networks (ANNs), or can we consider this a solved problem? Give reasons for or against one of these perspectives, and motivate your points by citing relevant literature. You should address points considered in class, such as various interventions which have been shown to enhance ANNs' compositional processing, and evidence for and against compositionality in human behavior. 
  2. Select an exisiting compositionality benchmark (e.g. SCAN, COGS, SLOG, CFQ) and evaluate at least one proposed approach to improve compositional generalization (e.g. data augmentation, auxiliary tasks/fine-tuning, specialized model architecture) against a standard model baseline. Write up your findings in a technical report.

The report should be uploaded via CMS. The due date will be one month following our final in-person session, i.e. Oct. 13 or 20.

## Contact

Please contact Kate (kmccurdy@lst.uni-saarland.de) or Michael (mhahn@lst.uni-saarland.de) for any questions.

## Accommodations

If you need any accommodations due to a disability or chronic illness, please either contact Michael at mhahn@lst.uni-saarland.de or the [Equal Opportunities and Diversity Management Unit](https://www.uni-saarland.de/en/administration/diversity.html) of the university.



### Optional: additional background reading 

- What is compositionality?
  - different views in linguistics -[Herbelot 2020](https://thegradient.pub/how-to-stop-worrying-about-compositionality-2)
  - ? in current philosophy - [Szabo 2020](https://plato.stanford.edu/entries/compositionality/)
  - a working approach in NLP - [Bender et al 2015](https://aclanthology.org/W15-0128)
  - ? a recent philosophical treatment w/r/t machine learning - [Nefdt 2020](https://doi.org/10.1007/s11023-020-09519-6)
- Foundational issue: abstraction
  - Rule- vs exemplar-based generalization - [Dasgupta et al 2022](https://proceedings.mlr.press/v162/dasgupta22b.html)
  - Information compression and model capacity - [Resnick et al 2020](https://www.ifaamas.org/Proceedings/aamas2020/pdfs/p1125.pdf)
  - Trade-off with variation - [Conklin and Smith 2023](https://openreview.net/pdf?id=-Yzz6vlX7V-)
  - Information-theoretic decomposition of morphology - [Socolof et al 2022](https://aclanthology.org/2022.coling-1.5.pdf)
- Do ANNs achieve compositional generalization? - evidence of problems
  - an early overview - [Baroni 2019](https://royalsocietypublishing.org/doi/full/10.1098/rstb.2019.0307)
  - ? COGS, an influential benchmark - [Kim and Linzen 2020](https://aclanthology.org/2020.emnlp-main.731)
  - ? maybe not a problem after all - [Csordas et al, 2021](https://aclanthology.org/2021.emnlp-main.49)
  - SLOG, a recent update - [Li et al 2023](https://aclanthology.org/2023.emnlp-main.194/)
- Some approaches to increasing ANN compositionality
  - Data augmentation - [Akyurek and Andreas 2023](https://aclanthology.org/2023.acl-long.38/)
  - Meta learning - will be discussed in human comparison part
  - Explicit composition of distributed representations - [Smolensky et al 2022](https://ojs.aaai.org/aimagazine/index.php/aimagazine/article/view/18599)
  - Symbolic methods: Neurosymbolic / program synthesis - reference TBD
- How compositional are humans anyway?
  - Humans generalize recursively to compose longer linguistic sequences than seen in training - [McCoy et al 2021](https://escholarship.org/uc/item/67z0195s)
  - Meta-learning better approximates human symbol mapping than symbolic composition - [Lake and Baroni 2023](https://www.nature.com/articles/s41586-023-06668-3)
  - ? Humans are biased toward abstraction, ANNs toward pattern-matching - [Kumar et al 2023](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1011316)
  - ? LMs are more logical than humans but repeat some fallacies - [Eisape et al 2023](https://arxiv.org/abs/2311.00445)
  - ? LMs show human-like content effects on reasoning tasks - [Dasgupta et al 2023](https://arxiv.org/abs/2207.07051)

  


