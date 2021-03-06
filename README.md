# Inference and Representation Fall 2019

## Course staff

| Soledad Villar | soledad.villar@nyu.edu | Instructor |
|----------------|------------------------|------------|
| Zhengdao Chen  | zc1216@nyu.edu         | TA         |
| Efe Onaran     | eonaran@nyu.edu        | Grader     |

## Syllabus

This is a graduate level course that presents fundamental tools of statistical inference, probabilistic graphical models and generative models for machine learning. 

Some of the covered topics include latent graphical models (Latent Dirichlet Allocation, Gaussian Processes), state-space models (Kalman Filter, Hidden Markov Models), Gibbs Models and Deep generative models (Variational autoencoders, GANs).

## Lecture (required)
Tuesdays 4:55pm-6:35pm, in 60 5th Ave, FA 110. 

## Recitation (required)
Mondays 4:55pm-5:45pm, in 60 5th Ave, FA 110. 

## Office hours
SV: Tuesdays, 3:00pm-4:45pm. Location: 60 5th ave, 6th floor, room 617.

## Grading
Homework 40%, midterm exam 25%, final project 30%, participation 5%.

## Materials
There is no required book. Assigned readings will come from freely-available online material. 

### Core Materials
  - David MacKay, [Information Theory, Inference and Algorithms](https://www.inference.org.uk/itprnn/book.pdf), Cambridge Press, 2003.
  - Kevin Murphy, [Machine Learning: a Probabilistic Perspective](http://www.cs.ubc.ca/%7Emurphyk/MLbook/index.html), MIT Press, 2012. You can read this online for free from [NYU Libraries](http://site.ebrary.com/lib/nyulibrary/detail.action?docID=10597102). We recommend the latest (4th) printing, as earlier editions had many typos. You can tell which printing you have as follows: check the inside cover, below the "Library of Congress" information. If it says "10 9 8 ... 4" you've got the (correct) fourth print.
  - Daphne Koller and Nir Friedman, [Probabilistic Graphical Models: Principles and Techniques](http://pgm.stanford.edu/), MIT Press, 2009.
  - Mike Jordan's notes on [Probabilistic Graphical Models](https://people.eecs.berkeley.edu/~jordan/prelims/)
  - [MIT lecture notes](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-438-algorithms-for-inference-fall-2014/lecture-notes/) on algorithms for inference.
  - [Probabilistic Programming and Bayesian Methods for Hackers](https://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/) by Cam Davidson Pilon
  - Trevor Hastie, Rob Tibshirani, and Jerry Friedman, [Elements of Statistical Learning](http://statweb.stanford.edu/~tibs/ElemStatLearn/), Second Edition, Springer, 2009. (Can be downloaded as PDF file.)6
  - David Barber, [Bayesian Reasoning and Machine Learning](http://web4.cs.ucl.ac.uk/staff/D.Barber/pmwiki/pmwiki.php?n=Brml.Online) , Cambridge University Press, 2012. (Can be downloaded as PDF file.)

### Background on Probability and Optimization
  - [Review notes from Stanford's machine learning class](http://cs229.stanford.edu/section/cs229-prob.pdf)
  - Sam Roweis's [probability review](http://cs.nyu.edu/%7Edsontag/courses/ml12/notes/probx.pdf)
  - [Convex Optimization](http://www.stanford.edu/%7Eboyd/cvxbook/) by Stephen Boyd and Lieven Vandenberghe.
  - [Carlos Ferndandez's notes on Statistics and Probability for Data Science DS-GA 1002](http://www.cims.nyu.edu/~cfgranda/pages/stuff/probability_stats_for_DS.pdf) 

### Further Reading
  - Mike Jordan and Martin Wainwright, [Graphical Models, Exponential Families, and Variational Inference](https://people.eecs.berkeley.edu/~wainwrig/Papers/WaiJor08_FTML.pdf)

### Additional Readings for the Recitation
  - Christopher Bishop, [Pattern Recognition and Machine Learning](http://users.isr.ist.utl.pt/~wurmd/Livros/school/Bishop%20-%20Pattern%20Recognition%20And%20Machine%20Learning%20-%20Springer%20%202006.pdf) (PRML)
  - Miranda Holmes-Cerfon, [Lecture notes on Markov Chains](https://cims.nyu.edu/~holmes/teaching/asa19/handout_Lecture2_2019.pdf)
  - Daniel Jurafsky and James Martin, [Book chapter on hidden Markov models](https://web.stanford.edu/~jurafsky/slp3/A.pdf)
  - Bill Freeman and Antonio Torralba, [Lecture notes on belief propagation](http://6.869.csail.mit.edu/fa13/lectures/slideNotesCh7rev.pdf)
  - Zoubin Ghahramani, [Slide on belief propagation](http://mlg.eng.cam.ac.uk/mlss09/mlss_slides/Ghahramani_2.pdf)
  - Miranda Holmes-Cerfon, [Lecture notes on MCMC](https://cims.nyu.edu/~holmes/teaching/asa19/handout_Lecture3_2019.pdf)
  - Michael I. Jordan, [Notes on EM](http://www.robots.ox.ac.uk/~cvrg/trinity2005/jordan_bishop.ps)


## Important dates
- October 15. No class and no office hours (legislative Monday).
- October 29. Midterm
- December 3, 4, 6. Final project presentations (see schedule).
- December 12. Final project due. 



| Date     | Topic                                                                                     | References                                                        | Homework |
|----------|-------------------------------------------------------------------------------------------|-------------------------------------------------------------------|----------|
| Sept 3rd | Introduction to inference and graphical models. Priors, likelihood functions, posteriors. | MacKay chapters 2 and 21.  Section 2.1 of Jordan and Wainwright. [Example seen in class](./materials/example_posterior_computation.ipynb). | HW 1 due 9/16.
| Sept 9th (recitation) | Basics of probability; data fitting and maximum likelihood inference. | PRML chapter 1.
|Sept 10th | Bayesian networks, naive bayes, hidden markov models        | Murphy chapters 10, 17, 3.  
| Sept 16th (recitation)| Markov chains and PageRank. | Murphy sections 17.2, 17.4; Lecture notes on Markov chains
| Sept 17th  | Bayesian networks (cont.) Bayes Ball algorithm, Undirected graphical models | Murphy chapter 10 and sections 19.1-19.4                                                                   | HW2 due 10/2 |
| Sept 23rd (recitation)  | Hidden Markov models, Viterbi algorithm | [Book chapter on HMMs](https://web.stanford.edu/~jurafsky/slp3/A.pdf) | |
| Sept 24th  | EM for mixtures of Gaussians and training HMMs | Bishop chapter 9 and https://web.stanford.edu/~jurafsky/slp3/A.pdf | |
| Sept 30th (recitation)  | Baum-Welch algorithm (EM algorithm) for HMMs | [Book chapter on HMMs](https://web.stanford.edu/~jurafsky/slp3/A.pdf) |  |
| Oct 1st  | Belief propagation and stochastic block model | Murphy chapter 20 and https://arxiv.org/pdf/1702.00467.pdf . See Zhengdao's paper about [community detection using GNNs](https://openreview.net/pdf?id=H1g0Z3A9Fm) . |  |
| Oct 7th (recitation) | Belief propagation | [Lecture notes on BP](http://6.869.csail.mit.edu/fa13/lectures/slideNotesCh7rev.pdf) and [slides on BP](http://mlg.eng.cam.ac.uk/mlss09/mlss_slides/Ghahramani_2.pdf)| |
| Oct 8th | Introduction to error correcting codes. Introduction to sampling methods | Chapters 1 and 47 of MacKay. Bishop chapter 11 | HW 3 due October 22 (noon) |
| Oct 21st (recitation)| Markov Chain Monte Carlo (MCMC) | [Lecture notes on MCMC](https://cims.nyu.edu/~holmes/teaching/asa19/handout_Lecture3_2019.pdf) | |
| Nov 4th (recitation)| MCMC cont'd; General EM algorithm | [Notes on EM](http://www.robots.ox.ac.uk/~cvrg/trinity2005/jordan_bishop.ps) | |
| Nov 5th | MCMC techniques for detecting Gerrymandering, Variational Autoencoders | [Gerrymandering](https://sites.duke.edu/quantifyinggerrymandering/) and papers [1](https://arxiv.org/pdf/1801.03783.pdf), [2](https://www.pnas.org/content/114/11/2860). VAEs [tutorial](https://arxiv.org/pdf/1606.05908.pdf) and [code example](https://github.com/nitarshan/variational-autoencoder) | Project proposal due 11/13|
| Nov 11th (recitation)| EM cont'd; basics of neural networks | ||
| Nov 12th | Variational inference | https://arxiv.org/abs/1601.00670||
| Nov 18th | GANs |https://papers.nips.cc/paper/5423-generative-adversarial-nets.pdf ||
| Nov 19th | Wasserstein GAN, GLO | https://arxiv.org/pdf/1701.07875.pdf and https://arxiv.org/pdf/1707.05776.pdf||
| Nov 25th (recitation) | Community detection and GNN | [Community detection](https://arxiv.org/abs/1702.00467), [GCN (Kipf & Welling)](https://arxiv.org/abs/1609.02907), [MPNN (Gilmer et al.)](https://arxiv.org/abs/1704.01212) ||
| Nov 26th | Gaussian processes | Chapter 2 of http://www.gaussianprocess.org/gpml/chapters/ ||
| Dec 2nd (recitation) | Representation learning with autoencoders and predictive coding | [Autoencoders](https://www.deeplearningbook.org/contents/autoencoders.html), [Contrastive Predictive Coding](https://arxiv.org/pdf/1807.03748.pdf), [Noise Contrastive Estimation](http://demo.clab.cs.cmu.edu/cdyer/nce_notes.pdf) |





