# Inference and Representation (DS-GA-1005, CSCI-GA.2569)
#### *Course staff:*
| | Name | E-mail  |
|----------|---------------|----------------|
|Instructor| [Joan Bruna](http://cims.nyu.edu/~bruna/)  |  bruna@cims.nyu.edu        |
|TA| Vlad Kobzar | vk283@nyu.edu |

### Syllabus
This graduate level course presents fundamental tools of probabilistic graphical models, with an emphasis on designing and manipulating generative models, and performing inferential tasks when applied to various types of data. 

We will study latent graphical models (Latent Dirichlet Allocation, Gaussian Processes), state-space models for (Kalman Filter, HMMs), Gibbs Models, Deep generative models (Variational autoencoders, GANs) covering both the methods (inference, sampling algorithms, learning, exponential families) and modeling applications to text, images and physics data.

### Lecture Location
Monday, 6:20-8:00pm, in 60 FA 110
### [Recitation/Laboratory](https://github.com/inf16nyu/home/tree/master/labs) (required for all students)
Wednesdays, 5:20-6:10pm in 60 FA 110

### Office hours
JB: Monday, 10:00-11:00pm. Location: 60 5th ave, 6th floor, room 612.

### Grading
problem sets (45%) + midterm exam (25%) + final project (25%) + participation (5%). 

### Piazza 
We will use [Piazza](https://piazza.com/class/j7ccyig9hwz1ze) to answer questions and post announcements about the course.  Students' use of Piazza, particularly for adequately answering other students' questions, will contribute toward their participation grade.

### Online recordings 
Most of the lectures and labs' videos will be posted to NYU Classes. Note, however, that class attendance is required.

## Schedule
| Week        | Lecture Date           | Topic       |  Reference                    |  Deliverables  |
| ---------------|----------------| ------------|---------------------------------|---------------|
| 2 | 9/11  | **Lec1** Introduction and Logistics. Inference Examples. Bayesian Networks. [Slides](https://github.com/inf17nyu/home/blob/master/slides/lecture1.pdf) | Murphy [Chapter 1](http://www.cs.ubc.ca/~murphyk/MLbook/pml-intro-22may12.pdf) (optional; review for most)<br /><br />[Notes on Bayesian networks](https://people.eecs.berkeley.edu/~jordan/prelims/chapter2.pdf) (Sec. 2.1)<br /><br />[Algorithm for d-separation](http://pgm.stanford.edu/Algs/page-75.pdf) (optional)| [PS1](https://github.com/inf17nyu/home/blob/master/hw/ps1.pdf), due 9/18 |
| 3 | 9/18  | **Lec2** Undirected Graphical Models. Markov Random Fields. Ising Model. Applications to Statistical Physics. [Slides](https://github.com/inf17nyu/home/blob/master/slides/lecture2.pdf) |[Notes on MRFs](https://people.eecs.berkeley.edu/~jordan/prelims/chapter2.pdf) (Sec. 2.2-2.4)<br /><br /> [Notes on exponential families](https://people.eecs.berkeley.edu/~jordan/courses/260-spring10/other-readings/chapter8.pdf) |  [PS2](https://github.com/inf17nyu/home/blob/master/hw/ps2/ps2.pdf) \[[data](https://github.com/inf17nyu/home/blob/master/hw/ps2/text_data.csv)\], due 9/25 |
| 4 | 9/25 | **Guest Lecture** TBA |  |  |
| 5 | 10/2 | **Lec3** Modeling Text Data. Topic Models. Latent Dirichlet Allocation. Gibbs sampling. [Slides](https://github.com/inf17nyu/home/blob/master/slides/lecture3.pdf)  | Barber [27.1-27.3.1](http://web4.cs.ucl.ac.uk/staff/D.Barber/textbook/181115.pdf)<br /><br />Murphy [Sec. 24.1-24.2.4](http://site.ebrary.com/lib/nyulibrary/reader.action?ppg=868&docID=10597102&tm=1474471957223) <br /><br />[Introduction to Probabilistic Topic Models](http://www.cs.princeton.edu/~blei/papers/Blei2011.pdf) <br /><br /> Explore topic models of: [politics over time](https://s3.amazonaws.com/smapp/lda/index.html), [state-of-the-union addresses](http://mimno.infosci.cornell.edu/jsLDA/), [Wikipedia](http://www.princeton.edu/~achaney/tmve/wiki100k/browse/topic-presence.html) | [PS3](https://github.com/inf17nyu/home/blob/master/hw/ps4/), due 10/17 <br /><br />[Project Proposal](https://github.com/inf16nyu/home/raw/master/project/final_project_proposal_inf.pdf), due 10/24 |
| 6 |  10/9 | **Lec4** PCA. ICA. Applications to Survey Data [Slides](https://github.com/inf17nyu/home/blob/master/slides/lecture4.pdf) | [Elements of Statistical Learning, Ch.14](http://statweb.stanford.edu/~tibs/ElemStatLearn/)<br /><br /> [Finding Structure in Randomness (...), Halko, Martinsson, Tropp](https://arxiv.org/pdf/0909.4061v2.pdf) |  [PS4](https://github.com/inf17nyu/home/blob/master/hw/ps5/), due 10/24 |
| 7 | 10/16 | **Lec5** Clustering. EM. Markov Chain Monte-Carlo (MCMC). [slides](https://github.com/inf17nyu/home/blob/master/slides/lecture5.pdf) | [MIT Lecture 18 Notes](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-438-algorithms-for-inference-fall-2014/lecture-notes/MIT6_438F14_Lec18.pdf) <br /><br /> Elements of Stat. Learning 14.5 and 8.5 <br /><br /> [Hamilton Monte-Carlo (optional)](http://www.mcmchandbook.net/HandbookChapter5.pdf)|   | 
| 8 | 10/23 | **Guest Lecture** TBA | |  |
| 9 | 10/30 | **Midterm Exam** | |  |
| 10 | 11/6 | **Lec6** Variational Inference. Revisiting EM. Mean Field.  [slides](https://github.com/inf17nyu/home/blob/master/slides/lecture6.pdf) | [Graphical Models, Exponential Families and Variational INference, Chapter 3](https://people.eecs.berkeley.edu/~wainwrig/Papers/WaiJor08_FTML.pdf) [Variational INference with Stochastic Search](http://www.cs.berkeley.edu/%7Ejordan/papers/paisley-etal-icml12.pdf) |  |
| 12 | 11/13 | **Lec7**  Structured Output Prediction. Conditional Random Fields (CRF), Hidden Markov Models, Moment Matching | | [PS5](https://github.com/inf17nyu/home/blob/master/hw/ps5/ps5.pdf), due 11/21 | 
| 13 | 11/20 | **Lec8** Sequential Models [slides](https://github.com/inf17nyu/home/blob/master/slides/lecture8.pdf) <br /><br />**No lab this week** | Murphy, Secs. 19.5 & 19.6 <br /> [Notes on pseudo-likelihood](http://cs.nyu.edu/~dsontag/courses/inference15/slides/pseudolikelihood_notes.pdf) <br /> [An Introduction to Conditional Random Fields](http://arxiv.org/pdf/1011.4088v1) (section 4; optional) <br /> [Approximate maximum entropy learning in MRFs](http://arxiv.org/abs/1206.3257) (optional) | |
| 14 | 11/27 |  **Lec9**  Boltzmann Machines. Variational Autoencoders [slides](https://github.com/inf17nyu/home/blob/master/slides/lecture9.pdf) |  | [PS6](https://github.com/inf17nyu/home/blob/master/hw/ps7/), due 12/5 |
| 15 | 12/4 | **Guest Lecture TBA**  |  |  |
| 16 | 12/11 | **Lec10** Modeling Images and high-dimensional data. Deep Auto-regressive Models. Normalizing Flows. Generative Adversarial Networks | references in slides |  |
|  | 12/12  | **Lec11**  Further applications of GANS. Open Problems | references in slides | [Project writeup](https://github.com/inf16nyu/home/blob/master/hw/project_writeup.pdf), due 12/16. |
| 17 | 12/18 | **Final Day**  Poster Presentations of Final Projects <br /><br /> <b>Location: Center for Data Science, 60 5th ave, in the 7th floor open space</b> | | |

### Bibliography
There is no required book. Assigned readings will come from freely-available online material.
#### Core Materials
  - Kevin Murphy, [Machine Learning: a Probabilistic Perspective](http://www.cs.ubc.ca/%7Emurphyk/MLbook/index.html), MIT Press, 2012. You can read this online for free from [NYU Libraries](http://site.ebrary.com/lib/nyulibrary/detail.action?docID=10597102). We recommend the latest (4th) printing, as earlier editions had many typos. You can tell which printing you have as follows: check the inside cover, below the "Library of Congress" information. If it says "10 9 8 ... 4" you've got the (correct) fourth print.
  - Daphne Koller and Nir Friedman, [Probabilistic Graphical Models: Principles and Techniques](http://pgm.stanford.edu/), MIT Press, 2009.
  - Mike Jordan's notes on [Probabilistic Graphical Models](https://people.eecs.berkeley.edu/~jordan/prelims/)
  - [MIT lecture notes](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-438-algorithms-for-inference-fall-2014/lecture-notes/) on algorithms for inference.
  - [Probabilistic Programming and Bayesian Methods for Hackers](https://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/) by Cam Davidson Pilon
  - Trevor Hastie, Rob Tibshirani, and Jerry Friedman, [Elements of Statistical Learning](http://statweb.stanford.edu/~tibs/ElemStatLearn/), Second Edition, Springer, 2009. (Can be downloaded as PDF file.)6
  - David Barber, [Bayesian Reasoning and Machine Learning](http://web4.cs.ucl.ac.uk/staff/D.Barber/pmwiki/pmwiki.php?n=Brml.Online) , Cambridge University Press, 2012. (Can be downloaded as PDF file.)

#### Background on Probability and Optimization
  - [Review notes from Stanford's machine learning class](http://cs229.stanford.edu/section/cs229-prob.pdf)
  - Sam Roweis's [probability review](http://cs.nyu.edu/%7Edsontag/courses/ml12/notes/probx.pdf)
  - [Convex Optimization](http://www.stanford.edu/%7Eboyd/cvxbook/) by Stephen Boyd and Lieven Vandenberghe.
  - [Carlos Ferndandez's notes on Statistics and Probability for Data Science DS-GA 1002](http://www.cims.nyu.edu/~cfgranda/pages/stuff/probability_stats_for_DS.pdf) 

#### Further Reading
  - Mike Jordan and Martin Wainwright, [Graphical Models, Exponential Families, and Variational Inference](https://people.eecs.berkeley.edu/~wainwrig/Papers/WaiJor08_FTML.pdf)
 

### Academic Honesty

We expect you to try solving each problem set on your own. However, when being stuck on a problem, we encourage you to collaborate with other students in the class, subject to the following rules:
  - You may discuss a problem with any student in this class, and work together on solving it. This can involve brainstorming and verbally discussing the problem, going together through possible solutions, but should not involve one student telling another a complete solution.
  - Once you solve the homework, you must write up your solutions on your own, without looking at other people's write-ups or giving your write-up to others.
  - In your solution for each problem, you must write down the names of any person with whom you discussed it. This will not affect your grade.
  - Do not consult solution manuals or other people's solutions from similar courses.

#### *Late submission policy*
During the semester you are allowed at most two extensions on the homework assignment. Each extension is for at most 48 hours and carries a penalty of 25% off your assignment.
