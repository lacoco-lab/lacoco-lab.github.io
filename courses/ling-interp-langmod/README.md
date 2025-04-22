# Linguistic Interpretability for Neural Models of Language

Software Project

<!-----DESCRIPTION----->
**Course Description:**

For this course, you will work with one or two other students to propose and implement a software project focused on linguistic interpretabilty for neural-network-based models of language. This course runs in the summer semester, i.e. April-July 2025.

You will select an interpretability **method** and use it to analyze how one or more neural models represent and/or process formal linguistic **categories** (cf. examples below). You can use a pre-trained model, trained on language modeling or some other objective, or for more complicated methods / tasks you have the option of training your own smaller model. The model can be trained on any natural language. Many of the technical aspects are flexible and open to discussion, e.g. at the project proposal phase. The key requirement is that your final project will analyze linguistically relevant categories, and how they are realized in a given neural network model.

For a more comprehensive technical background, I highly recommend taking the seminar [Interpreting and Analyzing Neural Language Models](https://lacoco-lab.github.io/courses/interpreting-2025/) in parallel with this project.

<!-----INSTRUCTORS----->
**Instructors:** [Kate McCurdy](https://lacoco-lab.github.io/home/authors/kmccurdy/)

<!----PREREQ------------>

**Prerequisites:**
You should be comfortable working with neural networks and various machine learning techniques. You should also have sufficient linguistic background to understand and evaluate the categories of interest. Look through the lists of example methods and tasks --- if you would not be capable of implementing one of the listed methods, or evaluating one of the listed tasks, this is probably not the course for you.

<!-----REGISTRATION----->

**Registration:**
 If you want to take part, please send an email to kmccurdy ( at sign ) lst.uni-saaland.de, deadline **Friday April ~~11~~ 18** (i.e. after the kickoff meeting on April 10 - feel free to come and ask questions there). N.B. registration deadline extended by one week to accommodate lack of CMS page!
 
In your email, please:

  - Give your name, semester, study program
  - Tell me why you want to take part in this course
  - Describe your previous experience:
    - in deep learning or machine learning in general
    - in linguistics and/or natural language processing in particular
  - Will you also take the concurrent [seminar on interpretibilty](https://lacoco-lab.github.io/courses/interpreting-2025/)? If not, please provide supporting evidence of your familiarity and/or capability with modern interpretibility methods.

## Project Timeline

- Kick-off **meeting**, in-person
  - date **Thursday April 10** at **14h**, C7 4 Aquarium
  - Kick-off meeting [slides](https://docs.google.com/presentation/d/1_x5AFsW2MDsH03pNx1NdxVBGb_nIgvGBtA8Of39ohoM/edit#slide=id.g349fa282d82_0_0)
- April: Develop Project Proposal
  - ~~May 1~~ **May 5**: **Submit** 3 page project proposal (20% of your grade)
- May: Explore Interpretibility Methods
  - Progress **presentation** + check-in meeting, remote
    -  date TBD May 19-23
- June: Analyze Linguistic Categories
  - Progress **presentation** + check-in meeting, remote
    - date TBD June 16-20
- July: Prepare Final Report
  - July 31: **Submit** final project report (50% of your grade) + code (30% of your grade)
- Final **meeting**, in person
  - date TBD July 14-15
 
## Example project components

### Example methods

Note that some methods can be used on large language models, while others are more suitable for smaller models. Select a method appropriate for the task. 

- Probing [e.g.](https://arxiv.org/abs/1909.03368)
- Disentangling Labels [e.g.](https://arxiv.org/pdf/2406.02449)
- Logit Lens [e.g.](https://www.lesswrong.com/posts/AcKRB8wDpdaN6v6ru/interpreting-gpt-the-logit-lens)
- Sparse Autoencoders [e.g. Gemma Scope](https://deepmind.google/discover/blog/gemma-scope-helping-the-safety-community-shed-light-on-the-inner-workings-of-language-models/)
- Activation Patching [e.g. Patchscope](https://arxiv.org/abs/2401.06102)
- Replacement Model + Attribution Graph [e.g. Circuit Tracing](https://transformer-circuits.pub/2025/attribution-graphs/methods.html)

### Example categories

- Parts of speech (e.g. nouns, verbs, ...)
- Morphemes (e.g. morphological segmentation)
- Syllables (e.g. in poetic rhyme)
- Prosodic constituents
- Syntactic heads (e.g. governing subject-verb agreement)
- Semantic heads (e.g. Semantic Role Labeling, Universal Dependencies, ...)

## Case Studies

Research works with a linguistic interpretability focus.

- Tenney et al., 2019: [BERT Rediscovers the Classical NLP Pipeline](https://aclanthology.org/P19-1452.pdf)
  - Linguistic category: multiple - PoS, dep. heads, semantic roles, …
  - Method + model: probe + BERT
- Dankers et al., 2021: [Generalising to German Plural Noun Classes, from the Perspective of a Recurrent Neural Network](https://aclanthology.org/2021.conll-1.8)
  - Linguistic category: German plural classes
  - Method + model: probe + LSTM
- Chen et al., 2024: [SUDDEN DROPS IN THE LOSS: SYNTAX ACQUISITION, PHASE TRANSITIONS, AND SIMPLICITY BIAS IN MLMS](https://arxiv.org/pdf/2309.07311v5)
  - Linguistic category: syntactic dependencies
  - Method + model: probe + BERT at different stages in training
- Lindsey et al., 2025: [Tracing circuits - Planning in Poems](https://transformer-circuits.pub/2025/attribution-graphs/biology.html#dives-poems)
  - Method + model: attribution graphs via local replacement model + Claude
- Brinkmann et al., 2025: [Large Language Models Share Representations of Latent Grammatical Concepts Across Typologically Diverse Languages](https://arxiv.org/pdf/2501.06346)
  - Method + model: SAEs + Llama


