---
title: 
permalink: /
---


Machine learning models are powerful, but do you know they are also vulnerable to different attacks?  In this course we will start from privacy attacks to different machine learning models.  We will then talk about defenses such as differential privacy.  Finally we will discuss other privacy enhancing technologies.  While the course is a 4-level course (we will also have a semester-long project and we assume you know basic concepts within computer science), junior students are welcome to take the challenge (we will go slowly and provide references so if you are not familiar with some concepts, you can catch up)! Prerequisites only include basic knowledge of coding (Python), algorithms, and probability.


- Instructor: [Tianhao Wang](https://tianhao.wang)
- Location: Mechanical Engr Bldg 341 and [Zoom](https://virginia.zoom.us/j/91717635982?pwd=dVNEaHJ3VjJxaVBFTDRmMUlvU3VDZz09&from=addon) (I will also put recordings to the slack channel after the lectures)
- Time: MoWe 3:30pm - 4:45pm
- TA: [Dung Nguyen](https://biocomplexity.virginia.edu/person/dung-nguyen) and [Hannah Chen](https://hannahxchen.github.io/)
- Discussion: 
  - [Slack](https://fall22dataprivacy.slack.com) - for class communication, discussion, and resource sharing. You can join using your @virginia.edu email address
  - [Piazza](https://piazza.com/virginia/fall2022/cs4501) - for Q/A (so others can see your question)
- Office Hour
  - Dung: Mon 11am-12pm [Zoom](https://virginia.zoom.us/j/94028483212?pwd=NkJua3Jybjd2WjQ5cFRRNnJuWVNqUT09) and by appointment
  - Hannah: Wed 2pm-3pm [Zoom](https://virginia.zoom.us/j/6523934504) and by appointment
  - Tianhao: Fri 2pm-3pm [Zoom](https://virginia.zoom.us/j/95103321825?pwd=d09vN3lDOEhJaUduWGpocURxem80dz09&from=addon) and by appointment


## Grading (tentative, subject to change): 
- Three assignments (60%, 20% each) on (1) privacy attacks towards machine learning, (2) differential privacy (dp for short), and (3) secure multi-party computation. Theory (proofs) and practice (programming in python) will be covered in each assignment.
- [Project](project.md) (group of 2: 40%).  Teams can utilize office hours to get feedbacks on the project. 

## Topics
1. week 1-3: privacy issues in machine learning
- privacy attacks and basic defenses to deep learning models 
  - including preliminaries of machine learning, nlp, graph neural networks, GANs, self-supervise learning, and federated learning)
  - covering membership inference attack, attribute inference attack, property inference attack, reconstruction attack
- machine unlearning
- auditing/monitoring privacy issues of machine learning 

2. week 4-7: differential privacy (dp, the standard way for protecting privacy)
- earlier works of k-anonymity, l-diversity and t-closeness and their limitations
- basics of dp (definitions, compositions)
- primitives for satisfying dp
  - Laplace mechanism, Exponential mechanism, Report-noisy-max, SVT, Gaussian mechanism
- advanced composition
  - strong composition, renyi dp
- applications: hierarchical method
- applications: marginals and generative models (privsyn and privtrace)
- applications: graph 
- applications: ml (dpsgd)

3. week 8-10: other flavors of dp
- local dp
- shuffle dp
- relaxed definition of dp 
  - geo-indistinguishability, event-level, w-window, pufferfish, one-sided dp, label dp
- interaction of dp with other domains, such as fairness, usability, explanabilities
- safe implementation of dp (and floating-point attacks to dp)

4. week 11-14: privacy enhancing technologies
- prelims of crypto: encryption, hash, message authentication, public-key encryption
- secure multi-party computation (including review of some libraries)
- secure multi-party computation and machine learning (libraries like aby)
- secure multi-party computation and dp (compare with shuffle dp, honeycrisp, etc)
- homomorphic encryption (crypte)
- zero-knowledge proofs
- encrypted databases
- oblivious RAM
- Tor
- secure hardware
- quantum computer 

## Schedule (tentative, subject to change), we will meet in a hybrid format (both in-person and using zoom)

| Week |  Dates  |  Monday   |  Wednesday  |
| :--: | :-----: | :-------- | :---------: |
|  1   | Aug 22 - Aug 26  |  No Class       |  Introduction  |
|  2   | Aug 29 - Sep 2   |  ML Background  |  ML Background  |
|  3   | Sep 5 - Sep 9    |  ML Attacks     |  ML Attacks  |
|  4   | Sep 12 - Sep 16  |  ML Attacks     |  ML Attacks  |
|  5   | Sep 19 - Sep 23  |  ML Attacks     |  DP Definition |
|  6   | Sep 26 - Sep 30  |  DP Mechanisms  |  DP Applications  |
|  7   | Oct 3 - Oct 7    |  No Class       |  DP Applications  |
|  8   | Oct 10 - Oct 14  |  DP ML          |  Local DP  |
|  9   | Oct 17 - Oct 21  |  LDP            | LDP  |
|  10  | Oct 24 - Oct 28  |  LDP            | LDP  |
|  11  | Oct 31 - Nov 4   |  LDP            | Crypto Basics  |
|  12  | Nov 7 - Nov 11   |  No Class       |  No Class |
|  13  | Nov 14 - Nov 18  |  MPC            |  Project Presentation  |
|  14  | Nov 21 - Nov 25  |  Project Presentation  |  Thanksgiving  |
|  15  | Nov 28 - Dec 2   |  Project Presentation  |  Project Presentation  |
|  16  | Dec 5 - Dec 9    |  Project Presentation  |  No Class  |