---
layout: page
title: AM207 Syllabus
---

**Instructors:** Verena Kaynig-Fittkau (Computer Science)

Welcome to AM207! The course is also offered through the Harvard University Extension School as distance education course APMA E-207. 

**What is this class about?**

This class is all about using stochastic methods to solve data inference and optimization problems. Over the course of a semester you will learn how to use Markov Chain Monte Carlo methods for a variety of applications, from solving integration problems to sampling from complicated posteriors. We will also talk about stochastic optimization methods like simulated annealing and stochastic gradient decent. 

Overall the course consists of the following modules:

* *Introduction to basic monte carlo methods*: Buffon\'s needle, pi estimation, rejection and importance sampling, variance reduction methods;

* *Bayes formalism and sampling*: Bayesian modeling, Markov Chains, Metropolis-Hastings, MCMC convergence analysis, hierarchical Bayes, Gibbs sampling;  

* *Stochastic Optimization*: simulated annealing, stochastic gradient decent, genetric algorithms;

* *Dynamic systems*: time series analysis, autoregressive\-moving\-average model, Box\-Jenkins method, hidden Markov model, Sequential Monte Carlo, Particle Filters, Gaussian Processes;

* *Advanced sampling methods*: slice sampling, Hamiltonian MC, Parallel Tempering, Emcee

* *Graphical Models*: Basic modeling assumptions, learning graphical models

**Why take this class?**
MCMC methods enable you to tackle multi-dimensional integrals, and thus are a key concept in Bayesian statistics, and computational sciences. 
Do you know the unsatisfactory feeling that a non-conjugate prior would actually better model your application, but you don\'t know how to handle the complicated resulting posterior? After this course this will be no problem anymore. 
Feeling stuck with estimating complex scenarios like neutron diffusion or the interaction of an electron beam with a biological sample? With MCMC you will save tons of paper and living trees by using stochastic simulation instead of pages over pages of numerical derivations. 
Also, stochastic optimization is widely used for optimizing highly non-convex loss functions, like they arise in training deep neural networks. 

## Course Logistics

**Prerequisites**

You should be familiar with basic statistics, multivariate calculus, basic linear algebra, and at least one programming language. 
We will do a brief recap of basic statistics, but it is really meant as a recap to get everyone on the same page, and not the first time introduction of these concepts. The course will be taught in Python. If you already are familiar with another programming language like C or Java, it should not be hard to switch to Python. However, it does mean some extra work for you in the beginning of the course. We expect you to be self-reliant in ramping up your background knowledge and be willing to read documentation on your own.  

**Required Textbook**

None. Instead, we have a list of recommended readings on the web site. 

**Online Discussion Forum**

We\'ll be using [Piazza](http://www.piazza.com/) as our online forum. Piazza is your main venue to ask questions, discuss problems, and help each other out. Piazza is a question-and-answer system designed to streamline class discussion outside of the classroom. It should always be your first recourse for seeking answers to your questions about the course, lecture or reading material, or the assignments. Piazza supports LaTeX, code formatting, embedding of images, and attaching of files. We will also use Piazza for all announcements, so it is important that you are signed up. 

**Online Videos**

Videos of all lectures and labs will be made available online. Archived videos will be available about 24 hours after meeting times from the course homepage. 

**Office Hours**

The staff will hold weekly office hours. Office hour times and locations will be listed on Piazza. Office hours provide you with an opportunity to review and discuss course materials as well as provide further guidance for your homework in a more intimate environment, with only your teaching fellow and maybe a handful of classmates present. Distance education students can make special arrangements directly with their assigned Teaching Fellows to meet online. 

## Course Components

**Lectures**

The class meets twice a week for lectures and joint class activities. The class activities are designed to help you master the relevant materials, to work on your homework in groups, and to get you started on your project. The weekly schedule of lectures is posted on the course web site. 

**Lab**

Lectures are supplemented by weekly labs led by the teaching fellows. The lab is designed to give you an easier access to the homework material, and it will be recorded and made available online. Labs will typically consist of a short presentation and live coding by a teaching fellow, followed by the opportunity for you to work on your homework assignment and projects while a TF is present to answer your questions. 

**Homework**

The homework is going to provide an opportunity to put the theory you learned in lecture into practice and to test your understanding of the material. See the homework as an opportunity to learn, and not to "earn points". The homework will be graded holistically to reflect this objective. 

**Project**

Towards the end of the course you will work on a final project. The goal of the project is to  apply the material learned during the course to a topic of your own choosing. 
You will work closely with other classmates in a **3-4 person project team**. You can come up with your own teams and use Piazza to find prospective team members. If you cannot find a partner we will team you up randomly. 
We consider team work a very important skill, and exceptions to the 3-4 person rule will only be given in extenuating circumstances. 
The project deliverables include a written paper (no longer than 6 pages), a 2 minute screencast and a poster. All code and data (of reasonable size) used for the project must also be submitted. This may be in Ipython notebooks, or separate files. If your data set is large, tell us where to find it. If it is proprietary, talk to us ahead of time.

## Course Policies

**Assessment Procedure**

Your final grade will be determined by the number of points you collect. You can collect various amounts of points for the different parts of the class:

* **Homework: 55%**, assessed on your individual submission.
* **Project: 40%**, assessed on meeting the project criteria and your peer assessment.
* **Participation: 5%** assessed on participation on Piazza, and for on-campus students, lectures and labs.

Homework, project, and participation will be graded holistically beyond mechanical correctness and focusing on the overall quality of the work. We will use the following 5 point scale in 0.5 point increments:

5 = Exceptional/above and beyond

4 = Solid / no mistakes (or really minor)

3 = Good / some mistakes

2 = Fair / some major conceptual errors

1 = Poor / did not finish

0 = Did not participate / did not hand in

Teaching Fellows will evaluate your work holistically beyond mechanical correctness and focus on the overall quality of the work. What we are looking for is your understanding of the problem. This means that it is very important for you to communicate your understanding. Undocumented code often does not very well communicate this. Think of your homework as a report to a knowledgeable peer. Explain your approach and the solution, and your expectations and surprises along the way.

In addition to the scores the Teaching Fellows will give detailed written feedback.

**Project Group Peer Assessment**

After the team-based project you will provide an assessment of the contributions of the members of your team, including yourself. Your teammates\' assessment of your contributions and the accuracy of your self-assessment will be considered as part of your overall course evaluation.

**Collaboration Policy**

You are welcome to discuss the course\'s ideas, material, and homework with others in order to better understand it, but **the work you turn in must be your own** (or for the project, yours and your teammate\'s). For example, you must **write your own code**, run your own data analyses, and communicate and explain the results in your own words and with your own visualizations. You may not submit the same or similar work to this course that you have submitted or will submit to another. Nor may you provide or make available solutions to homework to individuals who take or may take this course in the future. You are responsible for understanding the [Harvard College](https://college.harvard.edu/academics/academic-integrity) and [Extension School](www.extension.harvard.edu/resources-policies/student-conduct/academic-integrity) policies on academic integrity and how to use sources responsibly. Not knowing the rules, misunderstanding the rules, running out of time, submitting "the wrong draft", or being overwhelmed with multiple demands are not acceptable excuses. There are no excuses for failure to uphold academic integrity. 

**Quoting Sources**

You must acknowledge any source code that was not written by you by mentioning the original author(s) directly in your source code (comment or header). You can also acknowledge sources in a README.txt file if you used whole classes or libraries. Do not remove any original copyright notices and headers. However, you are encouraged to use libraries, unless explicitly stated otherwise! You may use examples you find on the web as a starting point, provided its license allows you to re-use it. You must quote the source using  proper citations (author, year, title, time accessed, URL) both in the source code and in any publicly visible material. You may not use existing complex combinations or large examples. For example, you may not use a ready to use multiple linked view visualization. You may use parts out of such examples. To support your learning about academic citation rules, please visit the Harvard Extension School [Tips to Avoid Plagiarism](www.extension.harvard.edu/resources-policies/resources/tips-avoid-plagiarism), where you\'ll find links to the Harvard Guide to Using Sources and two, free, online 15-minute tutorials to test your knowledge of academic citation policy. The tutorials are anonymous open-learning tools. 

**Missed Activities and Assignment Deadlines**

Projects and homework **must** be turned in on time, with the exception of late days for homework as stated below. It is important that everybody attends and proactively participates in class and online. We understand, however, that certain factors may occasionally interfere with your ability to participate or to hand in work on time. If that factor is an extenuating circumstance, we will ask you to provide documentation directly issued by the University, and we will try to work out an agreeable solution with you (and your teammates). 

**Homework Deadlines and Late Days**

The majority of the homework assignments will be bi-weekly. In the weeks when homework are due, they will be **due on Thursdays at 11:59 pm EST** unless otherwise announced. Each student is given **six late days** for homework at the beginning of the semester. A late day extends the individual homework deadline by 24 hours without penalty. **No more than two late days may be used on any one assignment. Assignments handed in more than 48 hours after the original deadline will not be graded.** If you have already used all of your late days for the semester, we will deduct 1 point for assignments <24 hours late, and 2 points for assignments 24-48 hours late. We do not accept any homework under any circumstances more than 48 hours after the original deadline. Late days are intended to give you flexibility: you can use them for any reason - no questions asked. You don\'t get any bonus points for not using your late days. You can only use late days for the individual homework deadlines. All other deadlines (e.g., project milestones) are hard. 

**Regrading Policy**

It is very important to us that all assignments are properly graded. If you believe there is an error in your assignment grading, please submit an explanation via email to us (the staff mailing list) **within 4 days of receiving the grade**. No regrade requests will be accepted orally, and no regrade requests will be accepted more than 4 days after the grades for the assignment have been sent out. The teaching staff will re-examine your entire assignment. So your score may go up, stay the same, or go down.    

**Guest Lecture Attendance**

We are lucky to have some of the world\'s best researchers take time out of their busy schedules to give guest lectures. We expect all non-distance students to attend these lectures in person and to engage the speakers with questions and comments. You must send an email to the staff at least one day before a guest lecture to be excused.

## Additional Information

**Accessibility**

If you have a documented disability (physical or cognitive) that may impair your ability to complete assignments or otherwise participate in the course and satisfy course criteria, please meet with us at your earliest convenience to identify, discuss, and document any feasible instructional modifications or accommodations. You should also contact the Accessible Education Office to request an official letter outlining authorized accommodations. The Extension School is committed to providing an accessible academic community. The Disability Services Office offers a variety of accommodations and services to students with documented disabilities. Please visit [this webpage](www.extension.harvard.edu/resources-policies/resources/disability-services-accessibility) for more information. 

**Credits**

Some of the material in this course is based on other classes. We have also heavily drawn on materials and examples found online and tried our best to give credit by linking to the original source. Please contact us if you find materials where the credit is missing or that you would rather have removed. 

**User Notice for Copyrighted Materials on Course Websites**

This course website, and much of the text, images, graphics, audio and video clips, and other content of the site (collectively, the "Content"), are protected by copyright law. In some cases, the copyright is owned by third parties, and Harvard is making the third-party Content available to you under the fair use doctrine. Fair use permits only certain limited uses of the Content. You may use the website and its Content only for your personal, noncommercial educational and scholarly use. Some Content may be provided via streaming or other means that restrict copying; you may not circumvent those restrictions. If you wish to distribute or make any of the Content available to others, or to use any Content commercially, or to use any Content for any purpose other than your personal, noncommercial educational and scholarly use, you must obtain any required permission from the copyright holder. User notice courtesy of the Harvard University Office of General Counsel.






