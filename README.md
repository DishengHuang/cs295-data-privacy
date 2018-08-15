# Data Privacy

## Course Description

How can we learn from sensitive data collected from individuals, while protecting the privacy of those individuals? 

This question is central to the study of data privacy, and is increasingly relevant with the widespread collection of our personal data. Analysis of this data can lead to important benefits for society, including advances in medicine and public infrastructure, but can also result in privacy breaches that expose our most closely-held secrets.

This course will explore both threats to privacy and solutions to the data privacy problem. We will demonstrate that traditional approaches to protecting privacy, such as anonymization, are subject to powerful attacks that reveal individuals' sensitive data. We will see that while more recent approaches for protecting privacy, including k-anonymity and l-diversity, are more resistant to these attacks, they are not immune.

Then, we will explore recent formal notions of privacy, including differential privacy. Differential privacy provides a rigorous formal definition of individual privacy that enables a wide range of statistical analyses while protecting privacy. We will explore a number of differentially private algorithms for analytics and machine learning, and learn about the algorithmic building blocks and proof techniques used to develop them.

In addition to learning about the mathematical foundations of differential privacy, we will explore its practical implications. We will learn about existing practical systems for enforcing differential privacy and examine the challenges of building such systems. This course will include programming assignments and an end-of-semester project, in which students are expected to demonstrate both mastery of the concepts we explore and understanding of their practical implications by building their own systems that perform privacy-preserving analyses on real data.

## Administrative

- **Lecture**:
- **Instructor**: Joe Near (jnear at uvm dot edu)
- **Office hours**: TBD, Votey 317


## Textbook & Other References

Please **do not** buy any books for this course. All required reference material is available online for free.

The primary textbook we will use for this course is:

- [D&R] [The Algorithmic Foundations of Differential Privacy](https://www.cis.upenn.edu/~aaroth/Papers/privacybook.pdf)  
  Cynthia Dwork and Aaron Roth.

The textbook is available in PDF form for free; buying a paper copy is difficult and not needed for this course. We will also use the following non-technical primer on differential privacy, also available for free:

- [Nissim] [Differential Privacy: A Primer for a Non-technical Audience](https://privacytools.seas.harvard.edu/files/privacytools/files/pedagogical-document-dp_new.pdf)  
   Kobbi Nissim, Thomas Steinke, Alexandra Wood, Micah Altman, Aaron Bembenek, Mark Bun, Marco Gaboardi, David R. O’Brien, and Salil Vadhan.

In addition to these, we will reference a number of academic papers throughout the semester (especially for the section on privacy-preserving machine learning).

## Policies

### Grading

Your grade for the course will be determined as follows:

- 10 homework assignments (5% each)
- midterm exam (25%)
- final project (25%)

### Exams

There will be a midterm exam during class on October 15. You will also be allowed one physical page (8 1/2" x 11") of notes for each exam. There is no final exam, and this course will conclude before the University's exam period.

### Homework Assignments

This course will use Python for examples and for programming assignments. Students are expected to be proficient in Python programming. Programming assignments will be distributed and turned in as Jupyter notebooks. See [this page](http://jupyter.org/install) for information on installing Jupyter; the Anaconda method is recommended, since it also installs the otherf libraries we will use in the course.

Homework will be turned in via Blackboard.

### Late Work

Homework assignments may be turned in late for a penalty of 10% per day after the deadline. Homework more than 10 days late will not be accepted.

### Collaboration & Allowed References

Collaboration on the high-level ideas and approach on assignments is encouraged. Copying someone else's work is not allowed. Any collaboration, even at a high level, must be declared when you submit your assignment. Every assignment must include a collaboration statement. E.g., "I discussed high-level strategies for solving problem 2 and 5 with Alex."

The official references for the course are listed in the schedule below. Copying from references other than these is not allowed. In particular, code and proofs should not be copied from other sources, including Stack Overflow and other public sources.

Students caught copying work are eligible for immediate failure of the course and disciplinary action by the University. All academic integrity misconduct will be treated according to [UVM's Code of Academic Integrity](https://www.uvm.edu/policies/student/acadintegrity.pdf).

## Final Projects

The course will include a final project, completed in groups of 1-3 students. The final project will demonstrate your mastery of the concepts covered in this course by implementing a practical system to perform privacy-preserving analysis of realistic data.

More information coming soon.

## Schedule

| Date     | Topics        | Reference | Notes | Homework |
| --------:|---------------|---------|-------|-------|
| 8/27/18  | Intro to data analytics & data privacy | Nissim, sec. 1&2 |
| 8/29/18  | Survey of privacy techniques | D&R, ch. 1 |
| 9/3/18   | No class (Labor day)
| 9/5/18   | Randomized response | D&R, sec. 3.2 | Guest speaker
| 9/10/18  | De-identification & re-identification | [Tockar](https://research.neustar.biz/author/atockar/)
| 9/12/18  | K-Anonymity & re-identification | TBD
| 9/17/18  | Intro & survey: differential privacy | Nissim, sec. 3&4; D&R, ch. 2 |
| 9/19/18  | Sensitivity and the Laplace mechanism | D&R, sec. 3.3 |
| 9/24/18  | Composition & post-processing | D&R, sec. 3.5, 3.5.1 |
| 9/26/18  | Approximate differential privacy & the Gaussian mechanism | D&R, sec. 3.5.2, appendix A
| 10/1/18  | Advanced composition | D&R, sec. 3.5.2
| 10/3/18  | Exponential mechanism | D&R, sec. 3.4
| 10/8/18  | No class (Fall break)
| 10/10/18 | Local sensitivity & smooth sensitivity | [NSRS07](http://www.cse.psu.edu/~ads22/pubs/NRS07/NRS07-full-draft-v1.pdf), sec. 1-3
| 10/15/18 | Midterm
| 10/17/18 | Subsample & aggregate | D&R, sec. 7.1; [NSRS07](http://www.cse.psu.edu/~ads22/pubs/NRS07/NRS07-full-draft-v1.pdf), sec. 4
| 10/22/18 | DP Programming Languages || TBD
| 10/24/18 | DP Programming Languages || TBD
| 10/29/18 | Variants of differential privacy | Renyi, zCDP, sampling
| 10/31/18 | Intro to private machine learning | Chaudhuri et al.     
| 11/5/18  | Differentially private SGD | Bassily et al.              
| 11/7/18  | Objective & output perturbation | Chaudhuri et al.       
| 11/12/18 | Private deep learning | Talwar et al.                    
| 11/14/18 | Private transfer learning | PATE 1 & 2
| 11/19/18 | No class (Thanksgiving break)
| 11/21/18 | No class (Thanksgiving break)
| 11/26/18 | Building privacy-preserving systems | PINQ, GUPT, Airavat, RAPPOR, Apple, Uber
| 11/28/18 | Open challenges | 
| 12/3/18  | Project presentations
| 12/5/18  | Project presentations