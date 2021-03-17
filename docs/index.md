---
layout: page
title: "DSC 102: Systems for Scalable Analytics"
doodle: "/bd.png"
permalink: /
---

**Instructor**: Rod Albuyeh

**Office Hours**: Mon 8:00-9:00am

**Lectures**: M/W/F 11:00-11:50am; Remote

**Discussions**: W 1:00-1:50pm; Remote

&nbsp;

TAs:

- First Last (flast [at] eng.ucsd.edu); Office Hours

&nbsp;

---
* TOC
{:toc}

---

# Overview

This course covers the principles of computing systems and tools for 
scaling data analytics to large datasets. Scalable analytics systems
are a central part of modern data science in numerous application 
domains spanning enterprise business intelligence, Web search, e-commerce, 
social media, natural and social sciences, healthcare, digitial 
humanities, e-governance, Internet of Things, and more.

Topics include computer organization, memory hierarchy, basics of 
operating systems, scalable and parallel computing, cloud computing, 
design and use of parallel dataflow systems, and the use of deep 
learning tools. It will cover how relational algebra, SQL, linear 
algebra, and more general dataflow operations in such systems can 
be used to perform data preparation and feature engineering for 
machine learning (ML) at scale, how to scale ML training, how to 
perform ML model selection and deployment at scale, and how to handle 
data heterogeneity. It will also introduce the implementation of 
such data systems and touch upon the latest research in this space.

A major component of this course is hands-on Python programming to 
implement data exploration, data preparation, and model selection 
pipelines on large real-world data using scalable analytics tools 
and cloud resources.

#### Course Format

- The class meets 3 times a week for 50-minute lectures. All lectures
are mandatory.

- 2 programming assignments. There are no late days for the 
programming assignments; plan your work accordingly.

- This course will have one in-class midterm exam and one cumulative 
final exam. If you miss an exam, you will get no credit for it unless 
you pre-notify the instructor with a certifiable medical or emergency 
reason; in such cases, your grade will be based on a proportional 
reweighting of the other components.

- There will be (many) surprise quizzes on random lecture dates to 
help you retain the material. These will constitute your participation
score.

- The discussion sections will be used by the TAs to prepare you for the 
programming assignments and help you gain experience with cloud components.

- We will have a number of guest lecturers from industry, with opportunities 
both during class and outside of class. If the guest lecture occurs during
class, the content discussed is fair game for the final. If it occurs
outside of class, the content offers a small opportunity for extra credit
on a midterm or final.  

#### Prerequisites

DSC 100 (Introduction to Data Management); or substantial practical 
experience with scalable data systems and ML, subject to the consent 
of the instructor.

Proficiency in Python programming.

#### Suggested Textbooks

*Computer Organization and Design (5th edition)*, by David Patterson 
and John Hennessy (aka the "CompOrg Book").

*Operating Systems: Three Easy Pieces*, by Remzi and Andrea Arpaci-Dusseau 
(aka the "Comet Book").

*Database Management Systems (3rd edition)*, by Raghu Ramakrishnan and 
Johannes Gehrke (aka the "Cow Book").

*Spark: The Definitive Guide (1st edition)*, by Bill Chambers and Matei 
Zaharia (aka the "Spark Book").

*Data Management in Machine Learning Systems*, by Matthias Boehm, 
Arun Kumar, and Jun Yang (aka the "MLSys Book").

---

#### Grading

Components
- midterm exam: 30%
- programming assignments: 15% + 10%
- surprise quizzes: 5%
- cumulative final: 40%

Cutoffs:

Since this is a newly adapted version of this course, the grading 
scheme is a hybrid of absolute and relative grading to mitigate the 
"cold start" issue. The absolute cutoffs are based on your absolute 
total score. The relative bins are based on your position in the total
score distribution of the class. The better grade among the two 
(absolute-based and relative-based) will be your final grade. The 
cutoffs listed below offer a minimum guarantee on your grade; some 
thresholds might be lowered slightly later by the instructor but they 
will not be raised.

| Grade | Absolute Cutoff (>=) | Relative Bin (Use strictest)
| --- | --- |  --- |
| A+ | 95 | Highest 5% |
| A | 90 | Next 10% (5-15) |
| A- | 85 | Next 15% (15-30) |
| B+ | 80 | Next 15% (30-45) |
| B | 75 | Next 15% (45-60) |
| B- | 70 | Next 15% (60-75) |
| C+ | 65 | Next 5% (75-80) |
| C | 60 | Next 5% (80-85) |
| C- | 55 | Next 5% (85-90) |
| D | 50 | Next 5% (90-95) |
| F | <50 | Lowest 5% |

**Example**: Suppose the total score is 82 and the percentile is 33. 
So, the relative grade is B-, while the absolute grade is B+. The 
final grade then is B+.

#### Exam Dates

Midterm Exam: Friday, 04/30, in class

Cumulative Final Exam: Friday, 06/11, 11:30am-2:30pm

# Schedule

|Week|Topic|
|--|--|
|1-4|Basics of Computer Organization and Operating Systems|
|4|Basics of Cloud Computing|
|5-6|Parallel and Scalable Data Processing: Parallelism Basics|
|7|Parallel and Scalable Data Processing: Scalable Data Access|
|8|Parallel and Scalable Data Processing: Data Parallelism|
|9|Dataflow Systems|
|10|ML Data Sourcing|
|10|ML Model Building Systems|
|10|ML Model Building Systems|
