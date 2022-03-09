
# Data Privacy (Fall 2022)

How can we learn from data collected from individuals while ensuring their privacy? The course explores this question, starting from privacy attacks to rigorous state-of-the-art solutions using differential privacy. The class will talk about both theoretical foundations and practical issues in real-world applications. **Prerequisites** include basic knowledge of coding (e.g., Python) and be comfortable reading and writing proofs involving algorithms and probability.


- Instructor: [Tianhao Wang](https://tianhao.wang)
- Location: TBD
- Time: TBD
- TA: TBD
- Discussion: TBD
- Office Hour
  - Tianhao: TBD and by appointment
  - TA: TBD and by appointment

## Format:
- Each lecture will involve reading one or more papers. Students will also be required to present at least one reading during the semester.
- Students will be evaluated based on class performance and a research project. Projects can focus on developing new theory/algorithms, or on implementing/adapting known algorithms to a real application setting. 



## Grading (tentative, subject to change): 
- Participation (10%): Students are expected to ask/answer questions during the presentation.
- Two assignments (10%) for theory (proofs) and practice (programming).
- [Project](project.md) (solo or a group of 2: 40%).  If desired, teams can utilize office hours to get feedbacks on the project. 
- Midterm (20%) 
- Final (20%) 

## Topics
1. privacy attacks
- reconstruction attacks
- k-anonymity, l-diversity and t-closeness
- attacks on k-anonymity, l-diversity and t-closeness
- privacy attacks to machine learning (prelims of machine learning)
- specific attacks to nlp
- membership inference attacks

2. dp
- dp, basics
- dp, primitives, advanced composition
- dp, applications: hierarchical method
- dp, applications: marginals and generative models (privsyn and privtrace)
- dp, applications: graph 
- dp, applications: ml (dpsgd, nlp, fine-tuning)

3. other flavors of dp
- local dp
- shuffle dp
- relaxed definition of dp (geo-indistinguishability, event-level, w-window, pufferfish, one-sided dp, label dp)
- interaction of dp with other domains, such as fairness, usability, explanabilities
- attacks to dp 

4. privacy-enhancing-technologies
- secure multi-party computation 1 (prelims of crypto)
- secure multi-party computation 2 (more on libraries)
- secure multi-party computation and dp (compare with shuffle dp, honeycrisp, etc)
- homomorphic encryption (crypte)
- zero-knowledge proofs
- encrypted databases
- oblivious RAM
- Tor
- secure hardware
- quantum computer 

5. privacy-preserving machine learning
- defenses to ml privacy attacks
- federated learning
- mpc machine learning (libraries like aby)
- machine unlearning
- auditing privacy issues of machine learning 

## Schedule (tentative, subject to change), we will meet in a hybrid format (both in-person and using zoom)
| Week |       Dates      |                            Monday                            |                            Wednesday                            |
| :--: | :--------------: | :----------------------------------------------------------: | :-------------------------------------------------------------: |
|  1   | Aug 22 - Aug 26  |               No Class                                               |                                                                 |
|  2   | Aug 29 - Sep 2   |                                                              |                                                                 |
|  3   | Sep 5 - Sep 9   |                                                              |                                                                 |
|  4   | Sep 12 - Sep 16   |                                                              |                                                                 |
|  5   | Sep 19 - Sep 23  |                                                              |                                                                 |
|  6   | Sep 26 - Sep 30  |                                                              |                                                                 |
|  7   | Oct 3 - Oct 7   |                                                              |                                                                 |
|  8   | Oct 10 - Oct 14   |                                                              |                                                                 |
|  9   | Oct 17 - Oct 21  |                                                              |                                                                 |
|  10  | Oct 24 - Oct 28  |                                                              |                                                                 |
|  11  | Oct 31 - Nov 4   |                                                              |                                                                 |
|  12  | Nov 7 - Nov 11    |                                                              |                                                                 |
|  13  | Nov 14 - Nov 18  |                                                              |                                                                 |
|  14  | Nov 21 - Nov 25  |                                                              |          Thanksgiving                                                       |
|  15  | Nov 28 - Dec 2  |                                                              |                                                                 |
|  16  | Dec 5 - Dec 9    |             Last Class                                                 |                                                                 |


## More recourses
### Related courses
- [Privacy in Statistics and Machine Learning](https://dpcourse.github.io/schedule.html) ([video](https://drive.google.com/drive/folders/1Ds5KlyWrX93DeiQWrFLpBS0Zsk104bnd?usp=sharing)) Spring 2021 by Adam Smith (BU) and Jonathan Ullman (NEU) 
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
- [The Complexity of Differential Privacy](https://privacytools.seas.harvard.edu/files/privacytools/files/complexityprivacy_1_01.pdf)
- [Differential Privacy: A Primer for a Non-Technical Audience](https://salil.seas.harvard.edu/files/salil/files/differential_privacy_primer_nontechnical_audience.pdf)
- [Protecting Your Privacy In A Data-driven World](https://www.clairemckaybowen.com/book.html)
- [Differential Privacy for Databases](https://dpfordb.github.io/)


### More courses on other flavors
- Theoretical data analysis: [The Algorithmic Foundations of Adaptive Data Analysis](https://adaptivedataanalysis.com/lecture-schedule-and-notes/) Fall 2017 by Aaron Roth (Penn) and Adam Smith (BU) 
- System and/or ml: [Private Systems](https://systems.cs.columbia.edu/private-systems-class/) Spring 2020 by Roxana Geambasu (Columbia) 
- Database systems: [Building Privacy-aware Database Systems](https://cs.uwaterloo.ca/~xihe/cs848/) Spring 2021 by Xi He (Waterloo) 
- Mechanism design: [Differential Privacy in Game Theory and Mechanism Design](https://www.cis.upenn.edu/~aaroth/courses/gametheoryprivacyS14.html) Spring 2014 by Aaron Roth (Penn) 
- Fairness: [Privacy & Fairness In Data Science](https://sites.duke.edu/cs590f18privacyfairness/schedule/) Fall 2018 by Ashwin Machanavajjhala (Duke) 
- ML: [Privacy Preserving Machine Learning](http://researchers.lille.inria.fr/abellet/teaching/private_machine_learning_course.html) Spring 2021 by Aurélien Bellet (Inria) 

## Course Policy
### Academic Integrity

The School of Engineering and Applied Science relies upon and cherishes its community of trust. We firmly endorse, uphold, and embrace the University’s Honor principle that students will not lie, cheat, or steal, nor shall they tolerate those who do. We recognize that even one honor infraction can destroy an exemplary reputation that has taken years to build. Acting in a manner consistent with the principles of honor will benefit every member of the community both while enrolled in the Engineering School and in the future. Students are expected to be familiar with the university [honor code](https://honor.virginia.edu/), including the section on [academic fraud](https://honor.virginia.edu/academic-fraud). 



### Students with disabilities or learning needs
It is my goal to create a learning experience that is as accessible as possible. If you anticipate any issues related to the format, materials, or requirements of this course, please meet with me outside of class so we can explore potential options. Students with disabilities may also wish to work with the Student Disability Access Center to discuss a range of options to removing barriers in this course, including official accommodations. Please visit [their website](sdac.studenthealth.virginia.edu) for information on this process and to apply for services online. If you have already been approved for accommodations through SDAC, please send me your accommodation letter and meet with me so we can develop an implementation plan together.


### Discrimination and power-based violence
The University of Virginia is dedicated to providing a safe and equitable learning environment for all students. To that end, it is vital that you know two values that I and the University hold as critically important:
1.	Power-based personal violence will not be tolerated.
2.	Everyone has a responsibility to do their part to maintain a safe community on Grounds.

If you or someone you know has been affected by power-based personal violence, more information can be found on the [UVA Sexual Violence website](www.virginia.edu/sexualviolence) that describes reporting options and resources available.

As your professor and as a person, know that I care about you and your well-being and stand ready to provide support and resources as I can. As a faculty member, I am a responsible employee, which means that I am required by University policy and federal law to report what you tell me to the University's Title IX Coordinator. The Title IX Coordinator's job is to ensure that the reporting student receives the resources and support that they need, while also reviewing the information presented to determine whether further action is necessary to ensure survivor safety and the safety of the University community. If you wish to report something that you have seen, you can do so at the Just Report It portal. The worst possible situation would be for you or your friend to remain silent when so many here are willing and able to help.

### Religious accommodations
It is the University's long-standing policy and practice to reasonably accommodate students so that they do not experience an adverse academic consequence when sincerely held religious beliefs or observances conflict with academic requirements. Students who wish to request academic accommodation for a religious observance should submit their request in writing directly to me (through email or Piazza private message) as far in advance as possible. Students who have questions or concerns about academic accommodations for religious observance or religious beliefs may contact the University’s Office for Equal Opportunity and Civil Rights (EOCR) at UVAEOCR@virginia.edu or 434-924-3200.

### Student support team
You have many resources available to you when you experience academic or personal stresses. In addition to your professor, the School of Engineering and Applied Science offers free tutoring, and has three staff members located in Thornton Hall who you can contact to help manage academic or personal challenges. Please do not wait until the end of the semester to ask for help! 

Lisa Lampe, Director of Undergraduate Education (academic), ll4uu@virginia.edu 
Blake Calhoun, Director of Undergraduate Success (academic), bic4sc@virginia.edu 
Alex Hall, Assistant Dean of Students (non-academic issues), aec5d@virginia.edu  

In addition to having an Assistant Dean of Students embedded in Engineering, we are also fortunate to have two CAPS counsellors embedded in our School. You may schedule time with Elizabeth Ramirez-Weaver or Katie Fowler through [Student Health](https://www.studenthealth.virginia.edu/getting-started-caps). When scheduling, be sure to specify that you are an Engineering student. You are also urged to use TimelyCare for either scheduled or on-demand 24/7 mental health care. 

Finally, the Center for Diversity in Engineering facilitates free tutoring during the academic year, helps students locate internships and research opportunities, and connects students with the many organizations on Grounds that provide information and support. The center also engages with student organizations, particularly those serving students who are traditionally underrepresented in engineering.

### Support for your career development
Your career development path may take you beyond the confines of UVA. Perhaps you applied for an internship and your interview is taking place in-person across the country. Maybe you submitted an abstract to a national technical conference and you have been asked to present your work. These are not only necessary steps on your path but are also invaluable lessons in and of themselves. I wish to encourage and support you in travel related to your career development. To that end, if you notify me at least one-week in advance of such an event, I will offer you the choice of either 
(1) completing assignments remotely, or 
(2) delaying assignment, exam, or quiz dates until at least 48 hours after your return. 

This offer comes with caveats: 
(1)	Extensions will not normally be granted for a team activity when only one member is traveling.
(2)	The delay will not extend beyond the last day of finals for the semester. 
