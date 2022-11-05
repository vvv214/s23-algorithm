---
title: Project
permalink: /project/
---

### Goal

The goal of doing a project in this course is to explore data privacy by yourself and find something that interests you and make you feel really excited to investigate deeper.  During the process, you will learn and practice to do a comprehensive review, plan on your time to finish a project, and write reports.

### Format

You are not restricted to follow any format.  Latex or Google doc or anything that can convey the knowledge would suffice.  There are two categories of a project: 
 - research: a research project aims to introduce new ideas or apply existing techniques to a new domain/dataset, in a non-trivial way
 - evaluation: an evaluation project aims to do a comprehensive evaluation and comparison of a topic, e.g., summarize and evaluate all the existing algorithms (code) for a specific problem


If you aim to do a research project and you put a lot of effort into, say, organizing and cleaning existing methods that no one ever did before (which is also very important), but you only produce a minor new result, that is probably unfortunate in real research.  But it is fine in this class, as we can evaluate on both sides.  Similarly, if you find new insights during your evaluation, that is also great.  Please mark your contribution from two sides clearly.


You are allowed to work individually or form a group of at most two, but keep in mind the expected amount of work will also double if you work in a group.  Students in a group will be given the same grade.  There is no preference from my side on the research format, topics, or whether you work individually or in a group.


A good project consists of a good proposal (topic evolves as the project goes on, but the more planning you do at this stage, the better), a comprehensive survey of existing work within the topic, and a complete execution.  At any stage, you are very welcome to send your plan or draft to the instructor or TA for feedbacks to keep yourself on track.  

#### Metric for research projects

| Item | Explanation |
| :--: | :--------------: |
| Literature review (50%) | You must do a comprehensive literature review of existing solutions. A good approach is to find a good-quality paper[^1] that is very related, and read its related work section. This gives you a good view of work prior to this paper. Then try to see which papers cite this paper from Google scholar. This gives you a good view of work after this paper. Finally, summarize and organize these existing solutions. | 
| Novelty (10%) | Is your solution a new solution different from existing ones? If you summarize existing work into a taxonomy, where does your proposed solution fit? | 
| Effectiveness (15%) | Your solution must have some advantages (e.g., better utility, running faster) over existing ones. Identify these advantages. You can either theoretically show superity of your solution or empirically (implement necessary solutions and run experiments) show it. | 
| Comparison (15%) | A more comprehensive comparison over existing solutions. Also acknowledge scenarios where your solution does not work well. | 
| Analysis (10%) | Why your solution work well in this setting and not that well in other settings? Are there theoretical bounds or empirical insights? | 

[^1]: A good-quality paper is one that is typically published at a top-tier venue (e.g., the ones listed in csrankings.org) or has many citations from Google scholar (e.g., >10 per year after publication), or authored by famous researchers (e.g., >1000 citations) or coming from a good university.
#### Metric for evaluation projects

| Item | Explanation |
| :--: | :--------------: |
| Literature review (50%) | Same as before. | 
| Evaluation (30%) | Summarize existing work into a taxonomy. Where does each solution fit? Also summarize the evaluations from existing papers. Are those evaluations reasonable? If not, try to come up with a more comprehensive evaluation setting. | 
| Comparison (15%) | A comprehensive comparison over existing solutions. You can use existing code or implement the solutions yourself. Identify the advantages and disadvantages of each solution. | 
| Analysis (5%) | Why each solution work well in some setting and not that well in other settings? Are there theoretical bounds or empirical insights? |  

### Some ideas

Below are some ideas (and you are very welcome to come up with your own idea):
 - Evaluate/benchmark existing methods for differentially private machine learning
 - Incorporate public information during differentially private data release 
 - Differential privacy into new machine learning algorithms (I am not an expert of machine learning; I only know image CNN, NLP, GNN; if you know more and want to apply differential privacy to some machine learning paradigm that no one did before, that would be great)
 - Privacy attacks of new machine learning algorithms
 - Generating differentially private code automatically
 - Building a differentially private system (e.g., an SQL engine or a machine learning training system)
 - Interplay between differential privacy and fairness or poison attacks