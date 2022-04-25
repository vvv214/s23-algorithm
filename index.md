


Machine learning models are powerful, but do you know they are also vunerable to different attacks?  In this course we will start from privacy attacks to different machine learning models.  We will then talk about defenses such as differential privacy.  Finally we will discuss other privacy enhancing technologies.  While the course is a 4-level course (we will also have a semester-long project and we assume you know basic concepts within computer science), junior students are welcome to take the challenge (we will go slowly and provide references so if you are not familiar with some concepts, you can catch up)! Prerequisites only include basic knowledge of coding (Python), algorithms, and probability.


- Instructor: [Tianhao Wang](https://tianhao.wang)
- Location: Mechanical Engr Bldg 341
- Time: MoWe 3:30pm - 4:45pm
- TA: TBD
- Discussion: TBD
- Office Hour
  - Tianhao: TBD and by appointment
  - TA: TBD and by appointment

## Format:
- Each lecture will involve reading one or more papers. Students will also be required to present at least one reading during the semester.
- Students will be evaluated based on class performance and a research project. Projects can focus on developing new theory/algorithms, or on implementing/adapting known algorithms to a real application setting. 



## Grading (tentative, subject to change): 
- Three assignments (60%, 20% each) on (1) privacy attacks towards machine learning, (2) differential privacy (dp for short), and (3) secure multi-party computation. Theory (proofs) and practice (programming in python) will be covered in each assignment.
- [Project](project.md) (group of 2: 40%).  Teams can utilize office hours to get feedbacks on the project. 

## Topics
1. week 1-3: privacy issues in machine learning
- privacy attacks and basic defenses to deep learning models 
  - including preliminaries of machine learning, nlp, graph neural networks, GANs, self-supervise learning, and federated learning)
  - covering membership inference attack, attribute inference attack, property inference attack, reconstruction attack
- machine unlearning
- potential privacy risks in model explanation
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
- applications: ml (dpsgd, nlp, fine-tuning)

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

| Week |       Dates      |                            Monday                            |                            Wednesday                            |
| :--: | :--------------: | :----------------------------------------------------------: | :-------------------------------------------------------------: |
|  1   | Aug 22 - Aug 26  |               No Class                                       |                                                                 |
|  2   | Aug 29 - Sep 2   |                                                              |                                                                 |
|  3   | Sep 5 - Sep 9    |                                                              |                                                                 |
|  4   | Sep 12 - Sep 16  |                                                              |                                                                 |
|  5   | Sep 19 - Sep 23  |                                                              |                                                                 |
|  6   | Sep 26 - Sep 30  |                                                              |                                                                 |
|  7   | Oct 3 - Oct 7    |                                                              |                                                                 |
|  8   | Oct 10 - Oct 14  |                                                              |                                                                 |
|  9   | Oct 17 - Oct 21  |                                                              |                                                                 |
|  10  | Oct 24 - Oct 28  |                                                              |                                                                 |
|  11  | Oct 31 - Nov 4   |                                                              |                                                                 |
|  12  | Nov 7 - Nov 11   |                                                              |                                                                 |
|  13  | Nov 14 - Nov 18  |                                                              |                                                                 |
|  14  | Nov 21 - Nov 25  |                                                              |          Thanksgiving                                           |
|  15  | Nov 28 - Dec 2   |                                                              |                                                                 |
|  16  | Dec 5 - Dec 9    |             Last Class                                       |                                                                 |


## More recourses
### Related courses
- [Privacy in Statistics and Machine Learning](https://dpcourse.github.io/schedule.html) ([video](https://drive.google.com/drive/folders/1Ds5KlyWrX93DeiQWrFLpBS0Zsk104bnd?usp=sharing)) Spring 2021 by Adam Smith (BU) and Jonathan Ullman (NEU) 
- [Data Privacy](https://jnear.github.io/cs211-data-privacy/) (mostly differential privacy) Fall 2021 by Joe Near (U of Vermont)
- [Algorithms for Private Data Analysis](http://www.gautamkamath.com/CS860-fa2020.html) ([video](https://www.youtube.com/playlist?list=PLmd_zeMNzSvRRNpoEWkVo6QY_6rR3SHjp)) Fall 2020 by Gautam Kamath (Waterloo) 
- [Applied Privacy for Data Science](http://people.seas.harvard.edu/~salil/cs208/spring19/) Spring 2019 by James Honaker and Salil Vadhan (Harvard)
- [Introduction to Differential Privacy: Theory, Algorithms and Applications](https://sites.cs.ucsb.edu/~yuxiangw/classes/DPCourse-2021Fall/) Fall 2021 by Yuxiang Wang (UCSB)
- [Design of Stable Algorithms for Privacy and Learning](https://courses.cs.duke.edu//fall16/compsci590.3/) Fall 2016 by Ashwin Machanavajjhala (Duke)
- [Algorithms for Private Data Analysis](http://www.cs.toronto.edu/~anikolov/CSC2412F20/CSC2412.html) Fall 2020 by Aleksandar Nikolov (UofT)
- [Data Privacy](http://www.cse.cuhk.edu.hk/~andrejb/csci5520/) Spring 2015 by Andrej Bogdanov (CUHK)
- [Differential Privacy: From Theory to Practice](http://cyber.biu.ac.il/event/the-7th-biu-winter-school/) 2017 Winter school by Katrina Ligett (Hebrew), Kobbi Nissim (Georgetown), Vitaly Shmatikov (Cornell), Adam Smith (BU), Jon Ullman (NEU)


### Books
- [The Algorithmic Foundations of Differential Privacy](https://www.cis.upenn.edu/~aaroth/Papers/privacybook.pdf)
- [Differential Privacy: From Theory to Practice](https://www.morganclaypool.com/doi/pdf/10.2200/S00735ED1V01Y201609SPT018)
- [Programming Differential Privacy](https://programming-dp.com/notebooks/ch3.html)
- [The Complexity of Differential Privacy](https://privacytools.seas.harvard.edu/files/privacytools/files/complexityprivacy_1_01.pdf)
- [Differential Privacy: A Primer for a Non-Technical Audience](https://salil.seas.harvard.edu/files/salil/files/differential_privacy_primer_nontechnical_audience.pdf)
- [Protecting Your Privacy In A Data-driven World](https://www.clairemckaybowen.com/book)
- [Differential Privacy for Databases](https://dpfordb.github.io/)


### More courses on other flavors
- Theoretical data analysis: [The Algorithmic Foundations of Adaptive Data Analysis](https://adaptivedataanalysis.com/lecture-schedule-and-notes/) Fall 2017 by Aaron Roth (Penn) and Adam Smith (BU) 
- System and/or ml: [Private Systems](https://systems.cs.columbia.edu/private-systems-class/) Spring 2020 by Roxana Geambasu (Columbia) 
- Database systems: [Building Privacy-aware Database Systems](https://cs.uwaterloo.ca/~xihe/cs848/) Spring 2021 by Xi He (Waterloo) 
- Mechanism design: [Differential Privacy in Game Theory and Mechanism Design](https://www.cis.upenn.edu/~aaroth/courses/gametheoryprivacyS14.html) Spring 2014 by Aaron Roth (Penn) 
- Fairness: [Privacy & Fairness In Data Science](https://sites.duke.edu/cs590f18privacyfairness/schedule/) Fall 2018 by Ashwin Machanavajjhala (Duke) 
- ML: [Privacy Preserving Machine Learning](http://researchers.lille.inria.fr/abellet/teaching/private_machine_learning_course.html) Spring 2021 by Aurélien Bellet (Inria) 

