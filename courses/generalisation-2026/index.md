# Understanding Generalization in Machine Learning: A Theoretical Perspective

## Course Description

[NEEDS A LOT OF CHANGE, JUST A DRAFT.]

Modern machine learning achieves remarkable empirical success, yet our theoretical understanding of *why* and *when* models generalize remains incomplete. Deep networks memorize training data yet still generalize to unseen examples. Large language models exhibit emergent capabilities that seem to transcend their training distribution. Classical learning theory provides elegant frameworks, but often fails to explain the generalization of overparameterized models that dominate today's landscape.

This seminar explores the theoretical foundations of generalization in machine learning — from classical PAC learning to modern perspectives on deep learning. We'll trace the evolution of generalization theory and examine how recent empirical phenomena challenge traditional understanding.

We'll ask:
- What does it mean for a machine learning model to generalize?
- How do classical learning theory frameworks like PAC learning and VC dimension relate to modern deep learning?
- Why do overparameterized models generalize despite having the capacity to memorize?
- What new theoretical tools are needed to understand phenomena like double descent and in-context learning?

**Prerequisites:**
Solid mathematical background including probability, linear algebra, and basic machine learning concepts. Familiarity with learning theory concepts (though not required) will be helpful. A willingness to engage with both theoretical proofs and empirical studies is essential.

We'll read foundational and modern work from researchers like **Valiant, Vapnik, Kearns, Angluin, Bartlett, Mendelson, Belkin, Nagarajan, Flammarion, Garg,** and others. The seminar bridges classical learning theory with contemporary deep learning phenomena, offering both historical perspective and cutting-edge insights into one of machine learning's most fundamental questions.

**Course Management System:** [CMS](https://cms.sic.saarland/generalization_2026/)

**Instructors:** Yash Sarrof

**Time:** TBD (Potentially as a blocked seminar)

**Room:** TBD

**Registration:**
* If you are an **LST / CoLi** student, and want to take this class, you should directly register in the [Course Management System (CMS)](https://cms.sic.saarland/generalization_2026/). Admissions decision will be made around the end of the first week of the semester.

* If you are a **Computer Science** student, you should initially register via the Computer Science department seminar registration system. If you want to take the seminar but were not selected by the assignment system, please apply for the waiting list by emailing ysarrof@lst.uni-saarland.de. Only register in [Course Management System (CMS)](https://cms.sic.saarland/generalization_2026/) once you were selected by the assignment system or otherwise admitted by us.


## Syllabus

Each session covers foundational or contemporary work on generalization theory, presented by students and followed by discussion. The topics span from classical learning theory to modern empirical phenomena in deep learning. This list is preliminary and may be adjusted based on participant interest and background.

#### **Theme 1 – Foundations of Learning Theory**
- Valiant (1984): *A Theory of the Learnable* (PAC Learning)
- Vapnik & Chervonenkis (1971): *On the Uniform Convergence of Relative Frequencies of Events to their Probabilities*
- Blumer et al. (1989): *Learnability and the Vapnik-Chervonenkis Dimension*

#### **Theme 2 – Query Learning and Active Learning**
- Angluin (1987): *Learning Regular Sets from Queries and Counterexamples*
- Angluin (1988): *Queries and Concept Learning*

#### **Theme 3 – Concentration Inequalities and Uniform Convergence**
- McDiarmid (1989): *On the Method of Bounded Differences*
- Bartlett & Mendelson (2002): *Rademacher and Gaussian Complexities: Risk Bounds and Structural Results*
- Mohri et al. (2012): *Foundations of Machine Learning* (Selected chapters on concentration bounds)

#### **Theme 4 – Stability and Generalization**
- Bousquet & Elisseeff (2002): *Stability and Generalization*
- Mukherjee et al. (2006): *Learning Theory: Stability is Sufficient for Generalization and Necessary and Sufficient for Consistency of Empirical Risk Minimization*

#### **Theme 5 – The Classical-Modern Divide: Overparameterization**
- Zhang et al. (2017): *Understanding Deep Learning Requires Rethinking Generalization*
- Neyshabur et al. (2017): *Exploring Generalization in Deep Learning*

#### **Theme 6 – Double Descent and Benign Overfitting**
- Belkin et al. (2019): *Reconciling Modern Machine Learning Practice and the Classical Bias–Variance Trade-off*
- Nakkiran et al. (2021): *Deep Double Descent: Where Bigger Models and More Data Hurt*
- Bartlett et al. (2020): *Benign Overfitting in Linear Regression*

#### **Theme 7 – Implicit Regularization and Optimization**
- Neyshabur et al. (2015): *In Search of the Real Inductive Bias: On the Role of Implicit Regularization in Deep Learning*
- Gunasekar et al. (2018): *Implicit Regularization in Matrix Factorization*
- Woodworth et al. (2020): *Kernel and Rich Regimes in Overparametrized Models*

#### **Theme 8 – Generalization in Modern Architectures**
- Jiang et al. (2020): *Fantastic Generalization Measures and Where to Find Them*
- Fort et al. (2019): *Deep Ensembles: A Loss Landscape Perspective*

#### **Theme 9 – Meta-Learning and In-Context Learning**
- Garg et al. (2022): *What Can Transformers Learn In-Context? A Case Study of Simple Function Classes*
- Akyürek et al. (2023): *What Learning Algorithm is In-Context Learning? Investigations with Linear Models*

#### **Theme 10 – Information-Theoretic Perspectives**
- Tishby & Zaslavsky (2015): *Deep Learning and the Information Bottleneck Principle*
- Xu & Raginsky (2017): *Information-Theoretic Analysis of Generalization Capability of Learning Algorithms*

#### **Theme 11 – Neural Tangent Kernels and Feature Learning**
- Jacot et al. (2018): *Neural Tangent Kernel: Convergence and Generalization in Neural Networks*
- Chizat & Bach (2018): *On the Global Convergence of Gradient Descent for Over-parameterized Models using Optimal Transport*

#### **Theme 12 – Distributional Robustness and Domain Adaptation**
- Ben-David et al. (2010): *A Theory of Learning from Different Domains*
- Sagawa et al. (2020): *Distributionally Robust Neural Networks for Group Shifts: On the Importance of Regularization for Worst-Case Generalization*


## Questions about readings

Please register on the forum on CMS (link will be added here soon) for posting questions.
Starting from Week 2, every student submits one question about the readings by Tuesday noon.
Students can also submit a few more questions, the grade will be calculated as the highest score among questions (so you can also ask some basic questions on which you want clarification).

- Submit **one question per week** (by Tuesday at noon).
- Grading:
  - 0 = not submitted  
  - 1 = superficial  
  - 2 = thoughtful / insightful


## Presentations

- Each week students present in **pairs**. 
- Target: **45 min presentation + 30–40 min discussion**

Given the mathematical nature of many papers, presentations should balance theoretical rigor with intuitive explanations. For foundational theory papers, focus on the key insights and proof techniques rather than getting lost in technical details. For modern empirical papers, connect the observations back to theoretical principles and discuss what they reveal about our understanding of generalization.

When preparing your talk, consider: What generalization phenomena does this paper address? How does it build on or challenge previous theoretical understanding? What are the practical implications? For theoretical papers, work through key examples and provide geometric or algorithmic intuitions where possible.

Presentations will typically be done in pairs. Coordinate to highlight connections between papers and contrasting perspectives on generalization. The mathematical content should be accessible to the audience while maintaining precision about key results.

A key component of the presentation is facilitating discussion. Engage the audience throughout, refer to questions submitted on the forum, and encourage critical analysis of the theoretical assumptions and empirical claims.

## Final Papers (for the 7 CP version)

Students taking the 7 CP version will complete a term paper based on a small, well-scoped independent project exploring some aspect of generalization theory. The goal is to bridge theory and practice by either:

1. **Theoretical analysis**: Extending existing theoretical results, providing new bounds, or analyzing generalization in specific settings
2. **Empirical validation**: Testing theoretical predictions on controlled experiments or analyzing generalization phenomena in practice
3. **Survey and synthesis**: Providing a coherent perspective on a particular aspect of generalization theory by synthesizing multiple papers

Good projects might revisit classical bounds in the context of modern deep learning, empirically investigate the conditions under which theoretical predictions hold, or provide theoretical analysis of recently observed generalization phenomena.

### Deliverable & format

**Report**: up to 8 pages main text (self-contained) in NeurIPS style, with unlimited appendix for proofs, code, extra figures/analyses.

**Content**: 
  - Brief literature review (situating your question in generalization theory)
  - Motivation and research question
  - Methods (theoretical analysis or experimental setup)
  - Results (theoretical findings or empirical observations)
  - Discussion/limitations and connections to broader generalization theory

**Evidence**: For theoretical projects: rigorous proofs or analysis. For empirical projects: systematic experiments with proper controls and statistical analysis.

**Submission**: via CMS. Due: September end, 2026

Target something achievable with reasonable mathematical complexity or computational resources. Focus on providing new insights into generalization rather than incremental extensions.

How it's graded:
- Grounding in generalization theory literature and accuracy of technical content
- Clarity of research question and appropriateness of approach
- Rigor of theoretical analysis or empirical methodology
- Insightfulness of results and discussion of implications for generalization theory
- Writing quality and reproducibility

## Attendance

Active participation is expected in every seminar session. You may miss up to two sessions without providing justification. For each additional session missed beyond that, you must submit a short (~500 words) writeup summarizing your thoughts on the paper(s) discussed in the session you missed.

## Evaluation

***Important: Study programs may differ in which versions of the class you can take. Please check with your study program coordinator if in doubt.***

For students taking the seminar for 4 credits:

    Presentation: 40%
    Questions about readings: 30%
    Participation in class: 30%

For students taking the seminar for 7 credits:

    Presentation: 20%
    Questions about readings: 15%
    Participation in class: 15%
    Final paper: 50%


## Contact

Please contact Yash (ysarrof@lst.uni-saarland.de) or Michael (mhahn@lst.uni-saarland.de) for any questions.

## Accommodations

If you need any accommodations due to a disability or chronic illness, please either contact Michael at mhahn@lst.uni-saarland.de or the [Equal Opportunities and Diversity Management Unit](https://www.uni-saarland.de/en/administration/diversity.html) of the university.