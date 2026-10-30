# Theoretical Abilities and Limitations of Language Models

**Course Description:**
LLM have amazing capabilities, but also hallucinate and make reasoning mistakes. Can we understand these abilities and limitations theoretically, as way to figure out ways of overcoming them?
The incredible scale of current LLMs makes this a daunting prospect. However, recent research has developed mathematical understanding sheeding light on questions such as:

* Why do LLMs struggle with tasks (e.g., multiplying 6-digit numbers) that a simple calculator can perform easily?

* Which kinds of problems is a transformer likely to generalize on well?

* What possible future architectures -- if any -- could replace transformers as the backbone of LLMs?

Research on these questions draws on fields such as computational complexity, formal language theory, and statistical learning theory.

**Prerequisites:**
This seminar will not presuppose knowledge of any of these fields. However, a willingness to engage with technical content is **important**.

We will discuss recent research papers, both from our own group and from other groups. A lot of this content is highly technical, and starting early is highly recommended. It is okay to not understand everything in the paper assigned to you, but you are encouraged to ask questions about things that are confusing. We will try to help each other in getting familiar with techniques that are useful establishing such results, and also at the same time make sure everybody is on-board with the high level idea of the papers at the very least.

**Course Management System:** [CMS](https://cms.sic.saarland/theory_2627/)

**Instructors:** Yash Sarrof

**Time:** 12:15 - 13:45 (every Friday)

**Room:** C7.3 / C7.1, 1.14 (the building signage says C7.1).

**Registration:**

*There are no more spots left in the seminar.*
* ~~If you are an **LST / CoLi** student, and want to take this class, you should directly register in the [Course Management System (CMS)](https://cms.sic.saarland/theory_2627/). Admissions decision will be made by the 20th October.~~

* ~~If you are a **Computer Science** student, you should initially register via the Computer Science department seminar registration system. Only register in [Course Management System (CMS)](https://cms.sic.saarland/) once you were selected by the assignment system or otherwise admitted by us.~~


## Syllabus

<div role="region" aria-label="Syllabus readings" tabindex="0" style="overflow-x: auto;">
<table aria-labelledby="syllabus" style="display: table; width: 100%; min-width: 720px; table-layout: fixed;">
  <colgroup>
    <col style="width: 14%;">
    <col style="width: 41%;">
    <col style="width: 30%;">
    <col style="width: 15%;">
  </colgroup>
  <thead>
    <tr style="background: #f6f8fa;">
      <th scope="col" style="text-align: left;">Date</th>
      <th scope="col" style="text-align: left;">Session / core reading</th>
      <th scope="col" style="text-align: left;">Optional material</th>
      <th scope="col" style="text-align: left;">Presenters</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row" style="vertical-align: top; text-align: left;"><time datetime="2026-10-16">16 Oct 2026</time></th>
      <td style="vertical-align: top;">
        <strong>Course introduction</strong><br>
        <small>Logistics, course structure, and expectations.</small>
      </td>
      <td style="vertical-align: top;">—</td>
      <td></td>
    </tr>
    <tr>
      <th scope="row" style="vertical-align: top; text-align: left;"><time datetime="2026-10-23">23 Oct 2026</time></th>
      <td style="vertical-align: top;">
        <strong>No class</strong>
      </td>
      <td style="vertical-align: top;">—</td>
      <td></td>
    </tr>
    <tr>
      <th scope="row" style="vertical-align: top; text-align: left;"><time datetime="2026-10-30">30 Oct 2026</time></th>
      <td style="vertical-align: top;">
        <strong>Tutorial</strong><br>
        <small>For presenters of papers on expressivity and length generalization.</small>
      </td>
      <td style="vertical-align: top;">—</td>
      <td></td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th colspan="4" scope="rowgroup" style="text-align: left; background: #eaf1f8; color: #243b53;">
        Expressivity<br>
        <small style="font-weight: normal;">In principle, if we could magically hardcode the weights of a transformer, what would they be capable of? </small>
      </th>
    </tr>
    <tr>
      <th scope="row" style="vertical-align: top; text-align: left;"><time datetime="2026-11-06">6 Nov 2026</time></th>
      <td style="vertical-align: top;">
        <a href="https://aclanthology.org/2020.tacl-1.11/">Theoretical Limitations of Self-Attention in Neural Sequence Models</a><br>
        <small>Hahn · TACL 2020</small>
      </td>
      <td style="vertical-align: top;">
        <a href="https://aclanthology.org/2022.tacl-1.46/">Formal Language Recognition by Hard Attention Transformers: Perspectives from Circuit Complexity</a><br>
        <small>Hao, Angluin &amp; Frank · TACL 2022</small>
      </td>
      <td style="vertical-align: top;">Samuel BK</td>
    </tr>
    <tr>
      <th scope="row" style="vertical-align: top; text-align: left;"><time datetime="2026-11-13">13 Nov 2026</time></th>
      <td style="vertical-align: top;">
        <a href="https://openreview.net/forum?id=CDmerQ37Zs">The Expressive Power of Transformers with Chain of Thought</a><br>
        <small>Merrill &amp; Sabharwal · ICLR 2024</small>
      </td>
      <td style="vertical-align: top;">
        <a href="https://jmlr.org/papers/volume22/20-302/20-302.pdf">Attention is Turing-Complete</a><br>
        <small>Pérez, Barceló &amp; Marinkovic · JMLR 2021</small>
      </td>
      <td style="vertical-align: top;">Aftab Khan</td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th colspan="4" scope="rowgroup" style="text-align: left; background: #eaf1f8; color: #243b53;">
        Length Generalization<br>
        <small style="font-weight: normal;">When do Transformers learn to do a task, at lengths bigger than the maximum training length? </small>
      </th>
    </tr>
    <tr>
      <th scope="row" style="vertical-align: top; text-align: left;"><time datetime="2026-11-20">20 Nov 2026</time></th>
      <td style="vertical-align: top;">
        <strong>RASP:</strong> <a href="https://proceedings.mlr.press/v139/weiss21a.html">Thinking Like Transformers</a><br>
        <small>Weiss, Goldberg &amp; Yahav · ICML 2021</small><br><br>
        <strong>RASP-L:</strong> <a href="https://openreview.net/forum?id=AssIuHnmHX">What Algorithms can Transformers Learn? A Study in Length Generalization</a><br>
        <small>Zhou et al. · ICLR 2024</small>
      </td>
      <td style="vertical-align: top;">
        <strong>D-RASP:</strong> <a href="https://openreview.net/forum?id=QnWjcTk14G">Discovering Interpretable Algorithms by Decompiling Transformers to RASP</a><br>
        <small>Huang et al. · ICML 2026</small>
      </td>
      <td style="vertical-align: top;">Deng Zhepei</td>
    </tr>
    <tr>
      <th scope="row" style="vertical-align: top; text-align: left;"><time datetime="2026-11-27">27 Nov 2026</time></th>
      <td style="vertical-align: top;">
        <a href="https://openreview.net/forum?id=U49N5V51rU">A Formal Framework for Understanding Length Generalization in Transformers</a><br>
        <small>Huang et al. · ICLR 2025</small>
      </td>
      <td style="vertical-align: top;">
        <strong>C-RASP:</strong> <a href="https://openreview.net/forum?id=FmhPg4UJ9K">Counting Like Transformers: Compiling Temporal Counting Logic Into Softmax Transformers</a><br>
        <small>Yang &amp; Chiang · COLM 2024</small>
      </td>
      <td style="vertical-align: top;">Nazanin Zarei Rad</td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th colspan="4" scope="rowgroup" style="text-align: left; background: #eaf1f8; color: #243b53;">
        More Fine-Grained Insights<br>
        <small style="font-weight: normal;">How do depth, precision affect model capabilities, and do theoretical results give deeper insights into what exactly models are capable of, are they capable of hiding their reasoning, are they capable of arbitrary state tracking ? </small>
      </th>
    </tr>
    <tr>
      <th scope="row" style="vertical-align: top; text-align: left;"><time datetime="2026-12-04">4 Dec 2026</time></th>
      <td style="vertical-align: top;">
        <strong>Safety:</strong> <a href="https://arxiv.org/abs/2609.37312">Hidden Reasoning Must Leak, but Need Not Be Readable: Fundamental Opportunities and Limits for Chain-of-Thought Monitoring</a><br>
        <small>Mohammadkhani et al. · arXiv 2026</small>
      </td>
      <td style="vertical-align: top;">
        <a href="https://openreview.net/pdf?id=NikbrdtYvG">Let's Think Dot by Dot: Hidden Computation in Transformer Language Models</a><br>
        <small>Pfau, Merrill &amp; Bowman · COLM 2024</small>
      </td>
      <td style="vertical-align: top;">Paulina Hussein</td>
    </tr>
    <tr>
      <th scope="row" style="vertical-align: top; text-align: left;"><time datetime="2026-12-11">11 Dec 2026</time></th>
      <td style="vertical-align: top;">
        <strong>Precision:</strong> <a href="https://openreview.net/forum?id=29LwAgLFpj">Characterizing the Expressivity of Fixed-Precision Transformer Language Models</a><br>
        <small>Li &amp; Cotterell · NeurIPS 2025</small>
      </td>
      <td style="vertical-align: top;">
        <a href="https://arxiv.org/abs/2210.02671">A Logic for Expressing Log-Precision Transformers</a><br>
        <small>Merrill &amp; Sabharwal · NeurIPS 2023</small>
      </td>
      <td style="vertical-align: top;">Meropi Maria Lampropoulou</td>
    </tr>
    <tr>
      <th scope="row" style="vertical-align: top; text-align: left;"><time datetime="2026-12-18">18 Dec 2026</time></th>
      <td style="vertical-align: top;">
        <strong>Depth:</strong> <a href="https://openreview.net/forum?id=jPduiyxyfw">Knee-Deep in C-RASP: A Transformer Depth Hierarchy</a><br>
        <small>Yang, Cadilhac &amp; Chiang · NeurIPS 2025</small>
      </td>
      <td style="vertical-align: top;">
        <a href="https://openreview.net/forum?id=HBOZmG9MR9">Disentangling the Expressivity of RoPE</a><br>
        <small>Jerad et al. · COLM 2026</small>
      </td>
      <td style="vertical-align: top;">Zhanyu Chen</td>
    </tr>
    <tr>
      <th scope="row" style="vertical-align: top; text-align: left;"><time datetime="2027-01-08">8 Jan 2027</time></th>
      <td style="vertical-align: top;">
        <strong>State tracking:</strong> <a href="https://openreview.net/forum?id=fAvNUFbBfM">Algebraic Decomposition Theory for Transformer Length Generalization</a><br>
        <small>Yang et al. · COLM 2026</small>
      </td>
      <td style="vertical-align: top;">
        <a href="https://openreview.net/forum?id=De4FYqjFueZ">Transformers Learn Shortcuts to Automata</a><br>
        <small>Liu et al. · ICLR 2023</small>
      </td>
      <td style="vertical-align: top;">Gaspard Tomas</td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th colspan="4" scope="rowgroup" style="text-align: left; background: #eaf1f8; color: #243b53;">
        Towards Better Architectures?<br>
        <small style="font-weight: normal;">How can this kind of theory be useful? Can we make better architectures based on theoretical insights?</small>
      </th>
    </tr>
    <tr>
      <th scope="row" style="vertical-align: top; text-align: left;"><time datetime="2027-01-15">15 Jan 2027</time></th>
      <td style="vertical-align: top;">
        <a href="https://openreview.net/forum?id=UvTo3tVBk2">Unlocking State-Tracking in Linear RNNs Through Negative Eigenvalues</a><br>
        <small>Grazzi et al. · ICLR 2025</small>
      </td>
      <td style="vertical-align: top;">
        <a href="https://openreview.net/pdf?id=eV5YIrJPdy">The Expressive Capacity of State Space Models: A
Formal Language Perspective</a><br>
        <small>Sarrof, Veitsman &amp; Hahn · NeurIPS 2024</small>
      </td>
      <td style="vertical-align: top;">Phineas Degener</td>
    </tr>
    <tr>
      <th scope="row" style="vertical-align: top; text-align: left;"><time datetime="2027-01-22">22 Jan 2027</time></th>
      <td style="vertical-align: top;">
        <a href="https://arxiv.org/abs/2604.03444">Olmo Hybrid: From Theory to Practice and Back</a><br>
        <small>Merrill et al. · COLM 2026</small>
      </td>
      <td style="vertical-align: top;"><a href="https://openreview.net/forum?id=QZgo9JZpLq">The Illusion of State in State-Space Models</a><br>
        <small>Merrill, Petty &amp; Sabharwal · ICML 2024</small></td>
      <td style="vertical-align: top;">Ali Alfwari</td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th colspan="4" scope="rowgroup" style="text-align: left; background: #eaf1f8; color: #243b53;">
        What explains the success of Transformers best?<br>
        <small style="font-weight: normal;">Which theoretical perspectives best explain Transformer capabilities, limitations, and empirical performance?</small>
      </th>
    </tr>
    <tr>
      <th scope="row" style="vertical-align: top; text-align: left;"><time datetime="2027-01-29">29 Jan 2027</time></th>
      <td style="vertical-align: top;">
        <a href="https://openreview.net/forum?id=Yxz92UuPLQ">Transformers are Inherently Succinct</a><br>
        <small>Bergsträßer, Cotterell &amp; Lin · ICLR 2026</small>
      </td>
      <td style="vertical-align: top;">—</td>
      <td style="vertical-align: top;">Maike Kalms</td>
    </tr>
    <tr>
      <th scope="row" style="vertical-align: top; text-align: left;"><time datetime="2027-02-05">5 Feb 2027</time></th>
      <td style="vertical-align: top;">
        <a href="https://arxiv.org/html/2610.32104v1">Putting Transformer Theories to the Test</a><br>
        <small>Altabaa, Schnabel &amp; Tomlinson · arXiv 2026</small>
      </td>
      <td style="vertical-align: top;">—</td>
      <td style="vertical-align: top;">Seyedali Farokh</td>
    </tr>
  </tbody>
</table>
</div>


## Attendance

Active participation is expected in every seminar session. You may miss up to four sessions without providing justification. For each additional session missed beyond that, you must submit a short (~500 words) writeup summarizing your thoughts on the paper(s) discussed in the session you missed.

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

    

***Important: You need to be registered on LSF for the correct version of the class in order to receive credit.***

### Questions

Please register on the forum on CMS (in CMS, you will see "forum" on the top toolbar, and reply in the forum to post questions).

When the presentations starts, every student submits one question about the readings by Wednesday noon.
Questions are graded on a 3-point scale (0: no question submitted, 1: superficial question, 2: insightful question). Students can also submit a few more questions, the grade will be calculated as the highest score among questions.（So you can also ask some basic questions that you want clarification). Try to be direct with your questions, and ask the same question in class, if it hasn't been answered by the presenter.

### Presentations

Feel free to present in any format you like, including a white board presentation if you want. If you want a suggestion, here's a recommended format.

1. **Short overview**: Every presentation should start with, a **15 minute presentation** giving high level details, and the overall idea of the paper. You should also then leave about **15 minutes for Q&A**. You are encouraged to combine the Q&A with your presentation, but are not required to do so. In this version of the presentation, you should focus on **big picture findings** and conclusions, and you are not expected to include every finding from the paper.
For instance, instead of a table of numbers, highlight key results.
When there are multiple similar results in the paper, synthesize them.
If the papers have many studies, you might select a presentative subset to explain the paper's conclusions.
On the other hand, if the assigned papers primarily discuss/review other work, draw on material from the work cited to provide richer content and even details where useful.

2. **Discussing a specific claim in detail**: We won't have time to discuss all the claims of the paper in detail, and thus try to identify the central claim of the paper, and design and then aim for about **30 minutes**, to go into the details of that claim, including explaining the underlying proof, if necessary.
Give background on key concepts, if necessary to explain whats going on here.

3. **Your own opinion**: Finally end the paper, by critically engaging with the reading: contribute your own opinion on the key findings, and on the paper's motivation and arguments. In what ways do or don't you agree with arguments made by the authors? Aim for around **10** minutes here, leaving the rest of the time for Q&A.

You will have sufficient time, so avoid speaking too fast for others to keep up, make sure your audience is following. You can do so by giving more examples, or simply repeating again. Making presentation is to convey information, if audience cannot follow, it's waste of time for both sides.
Generating and moderating in-class discussion is a key component of your presentation -- thinking about what will be interesting to your audience will thus be important.
Try to engage the audience and **create ample opportunity for discussion during your presentation**.
Before the presentation, take a look at the questions that have been posted in the forum and refer to these as needed. These may be useful for getting discussion started.
Conversely, when attending other students' talks, reciprocate by participating actively in the discussion.

### Final Papers (for the 7CP version)

Term papers will be about a small independent project.
You will investigate some question about the abilities of language models. It can be a theoretical work, or an empirical project verifying insights from theoretical work or providing inputs to theoretical work. For example, one may do experiments to show the expressivity or generalization performance of some novel architectures ([1](https://arxiv.org/abs/2002.09402), [2](https://arxiv.org/abs/2402.13572v2), [3](https://arxiv.org/abs/2405.17394), [4](https://arxiv.org/abs/2409.15647), [5](https://arxiv.org/abs/2508.10875), do not repeat previous work, try to experiment with new architectures or new tasks).

The report is expected to contain a brief literature review, motivation of your study, a description of what you did, and you found. It's recommended to include quantitative validation of what you found, so that you show it's not an illusion.

The report should have 8 pages of main report, plus unlimited appendix, in the NeurIPS style format. The main report should be self-contained, but you can use the appendix to report prompts, further analyses, or other material.

The report should be uploaded via CMS. The due date is 23:59 on March 15, 2027.

### Contact

Please contact Yash (ysarrof@lst.uni-saarland.de) or Michael (mhahn@lst.uni-saarland.de) for any questions.

### Accommodations

If you need any accommodations due to a disability or chronic illness, please either contact Michael at mhahn@lst.uni-saarland.de or the [Equal Opportunities and Diversity Management Unit](https://www.uni-saarland.de/en/administration/diversity.html) of the university.

