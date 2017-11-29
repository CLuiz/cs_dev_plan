# cs_dev_plan
My personal development past, present, and future in regards to computer science, data science, math, etc. 

Both format and large portions of content have been taken from the OSSU computer science curriculum found here:
https://github.com/ossu/computer-science/blob/master/README.md


# Contents

- [Summary](#summary)
- [Goals](#goals)
- [Philosophy](#philosophy)
- [Methodology](#methodology)
- [Curriculum](#curriculum)
  - [Prerequisites](#prerequisites)
  - [Introduction to Computer Science](#introduction-to-computer-science)
  - [Fundamental Math](#fundamental-math)
  - [Software Development](#software-development)
  - [Core CS](#core-cs)
  - [Advanced CS](#advanced-cs)
  - [Advanced Math](#advanced-math)
  - [Pro CS](#pro-cs)
  - [Special Topics](#special-topics)
- [Background](#background)
- [Code of conduct](#code-of-conduct)
- [Community](#community)
  - [How to show your progress](#how-to-show-your-progress)
  - [Team](#team)
- [References](#references)

# Summary
This document is intended to help me map out a personal learning plan.
(personal evaluation statement here)  

# Goals
1. Grow as a data scientist. Specifically the application and tuning of neural networks & building intelligent systems.
1. Attain an understanding of computer science equivalent to a holder of a masters degree from a top university.
1. Attain a familiarity with the mathematic principles covered in an undergraduate ms/cs degree.
1. Attain the skillset of a mid-level software engineer. 
1. Have fun!

# Philosophy
I believe I can reach the above goals by applying a mixed breadth and depth strategy 
where I develop familiarity with a broad range of topics, and go deep on those that either:
  - Are particularly interesting to me
  - Support my learning goals in several ways exs:
    - I'll spend quite a bit of time on algorithms, because they support goals 1-5 above.
    - I'll spend less time on say, operating system design, as it supports only goal 2, and is not within my target subdomain (ml/ai).

# Methodology
1. Finish 1 task every three weeks
1. Use top-level university programs when posssible
1. Opt for classes that produce a tangible product tha can be displayed within this repo.
1. Given two classes, take the harder one if it adresses more than one goal, else the easier one.
1. Use books as supplements to classes rather than replacements.

# Curriculum
## Introduction to Computer Science
These courses will introduce you to the world of computer science.
Both are required, but feel free to skip straight to the second course when CS50 (the first course) moves away from C.
([Why?](FAQ.md#why-do-you-recommend-skipping-the-second-half-of-cs50))

**Topics covered**:
`imperative programming`
`procedural programming`
`C`
`manual memory management`
`basic data structures and algorithms`
`Python`
`SQL`
`basic HTML, CSS, JavaScript`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Introduction to Computer Science - CS50](https://www.edx.org/course/introduction-computer-science-harvardx-cs50x#!) ([alt](https://cs50.harvard.edu/)) | 12 weeks | 10-20 hours/week | none
[Introduction to Computer Science and Programming using Python](https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-10) | 9 weeks | 15 hours/week | high school algebra

## Core CS

All coursework under Core CS is **required**, unless otherwise indicated.

### Core programming
**Topics covered**:
`functional programming`
`design for testing`
`program requirements`
`common design patterns`
`unit testing`
`object-oriented design`
`Java`
`static typing`
`dynamic typing`
`ML-family languages (via Standard ML)`
`Lisp-family languages (via Racket)`
`Ruby`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[How to Code - Simple Data](https://www.edx.org/course/how-code-simple-data-ubcx-htc1x) | 7 weeks | 8-10 hours/week | none
[How to Code - Complex Data](https://www.edx.org/course/how-code-complex-data-ubcx-htc2x) | 6 weeks | 8-10 hours/week | How to Code: Simple Data
[Software Construction - Data Abstraction](https://www.edx.org/course/software-construction-data-abstraction-ubcx-softconst1x) | 6 weeks | 8-10 hours/week | How to Code - Complex Data
[Software Construction - Object-Oriented Design](https://www.edx.org/course/software-construction-object-oriented-ubcx-softconst2x) | 6 weeks | 8-10 hours/week | Software Construction - Data Abstraction
[Programming Languages, Part A](https://www.coursera.org/learn/programming-languages) | 4 weeks | 8-16 hours/week | recommended: Java, C
[Programming Languages, Part B](https://www.coursera.org/learn/programming-languages-part-b) | 3 weeks | 8-16 hours/week | Programming Languages, Part A
[Programming Languages, Part C](https://www.coursera.org/learn/programming-languages-part-c) | 3 weeks | 8-16 hours/week | Programming Languages, Part B

#### Readings
- **Required** to learn about monads, laziness, purity: [Learn You a Haskell for a Great Good!](http://learnyouahaskell.com/)
  - **OBS**: probably the best resource to learn Haskell: [Haskell Programming from First Principles](http://haskellbook.com/) `paid`
- **Required**, to learn about logic programming, backtracking, unification: [Learn Prolog Now!](http://www.learnprolognow.org/)

### Core math

**Topics covered**:
`linear transformations`
`matrices`
`vectors`
`mathematical proofs`
`number theory`
`differential calculus`
`integral calculus`
`sequences and series`
`discrete mathematics`
`basic statistics`
`O-notation`
`graph theory`
`vector calculus`
`discrete probability`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | - | - | pre-calculus
[Linear Algebra - Foundations to Frontiers](https://www.edx.org/course/linear-algebra-foundations-frontiers-utaustinx-ut-5-04x#!) ([alt](http://ulaff.net/)) | 15 weeks | 8 hours/week | Essence of Linear Algebra
[Calculus One](https://www.coursera.org/learn/calculus1)<sup>*1*</sup> ([alt](https://mooculus.osu.edu/)) | 16 weeks | 8-10 hours/week | pre-calculus
[Calculus Two: Sequences and Series](https://www.coursera.org/learn/advanced-calculus)| 7 weeks | 9-10 hours/week | Calculus One
[Mathematics for Computer Science](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/index.htm) | 13 weeks | 5 hours/week | single variable calculus (Calculus Two)

**<sup>1</sup> Note**: When you are enrolled, please see this
[list of errors](https://www.coursera.org/learn/calculus1/discussions/forums/WcY9_8ayEeSWEiIAC0wC5g/threads/CgOJwV-jEeWncxKXIFxpFQ/replies/kH6u_2FPEeWukw4fFhIvKw)
and
[these recommendations](https://www.coursera.org/learn/calculus1/discussions/all/threads/W5P9mFY8EeWbVQrsfyQbuw/replies/XyyJflZDEeWBRg5dvElQww/comments/l-bON17nEeW9lgqcHapJBw)
for how to progress through the course.

### Core systems

**Topics covered**:
`boolean algebra`
`gate logic`
`memory`
`machine language`
`computer architecture`
`assembly`
`machine language`
`virtual machines`
`high-level languages`
`compilers`
`operating systems`
`network protocols`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Build a Modern Computer from First Principles: From Nand to Tetris](https://www.coursera.org/learn/build-a-computer) ([alt](http://www.nand2tetris.org/)) | 6 weeks | 7-13 hours/week | none
[Build a Modern Computer from First Principles: Nand to Tetris Part II ](https://www.coursera.org/learn/nand2tetris2) | 6 weeks | 12-18 hours/week | From Nand to Tetris Part I
[Introduction to Computer Networking](https://lagunita.stanford.edu/courses/Engineering/Networking-SP/SelfPaced/about)| 8 weeks | 4–12 hours/week | algebra, probability, basic CS
[ops-class.org - Hack the Kernel](https://www.ops-class.org/) | 15 weeks | 6 hours/week | algorithms

#### Readings
- **Recommended**: While Hack the Kernel recommends Modern Operating Systems as a textbook, we suggest using [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/).

### Core theory

**Topics covered**:
`divide and conquer`
`sorting and searching`
`randomized algorithms`
`graph search`
`shortest paths`
`data structures`
`greedy algorithms`
`minimum spanning trees`
`dynamic programming`
`NP-completeness`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Algorithms: Design and Analysis, Part I](https://lagunita.stanford.edu/courses/course-v1:Engineering+Algorithms1+SelfPaced/about) | 8 weeks | 4-8 hours/week | any programming language, Mathematics for Computer Science
[Algorithms: Design and Analysis, Part II](https://lagunita.stanford.edu/courses/course-v1:Engineering+Algorithms2+SelfPaced/about) | 8 weeks | 4-8 hours/week | Part I


### Core applications

**Topics covered**:
`Agile methodology`
`REST`
`software specifications`
`refactoring`
`relational databases`
`transaction processing`
`data modeling`
`neural networks`
`supervised learning`
`unsupervised learning`
`OpenGL`
`raytracing`
`block ciphers`
`authentication`
`public key encryption`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Databases](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/about)| 12 weeks | 8-12 hours/week | some programming, basic CS
[Machine Learning](https://www.coursera.org/learn/machine-learning)| 11 weeks | 4-6 hours/week | linear algebra
[Computer Graphics](https://www.edx.org/course/computer-graphics-uc-san-diegox-cse167x)| 6 weeks | 12 hours/week | C++ or Java, linear algebra
[Cryptography I](https://www.coursera.org/course/crypto)| 6 weeks | 5-7 hours/week | linear algebra, probability
[Software Engineering: Introduction](https://www.edx.org/course/software-engineering-introduction-ubcx-softeng1x) | 6 weeks | 8-10 hours/week | Software Construction - Object-Oriented Design
[Software Development Capstone Project](https://www.edx.org/course/software-development-capstone-project-ubcx-softengprjx) | 6-7 weeks | 8-10 hours/week | Software Engineering: Introduction

## Fundamental Math
## Software Development
## Core CS
## Advanced CS
## Advanced Math
## Pro CS
## Special Topics

# Background
- I have strong experience in a few sub-domains of data science
  - Science
    - Undergraduate degree in chemistry
    - Work experience via IX Power
  - Foundational Math
    - Calculus
    - Linear algebra 
  - Machine learning
  
- Intermediate experience in others.
  - Distributed Computing
  - Software Development
  - Advanced Math
  - foo
  - bar
  
- And lots of room to improve in others.
  - Probabalistic Programming
  - Computer Science topics
  - foo
  - bar

- Traditionally Offered Classes:
  - Undergrad
    - Calc 1-3 
      - Self explanatory
    - Mathematics for the physical sciences
      - multivariable calc
      - differential equations
      - linear algebra
    - General chemistry 1-3
      - Basic science series
    - General physics 1-3
    - Organic chemistry 1-3
      - Lab technique, experimental design
    - Physical Chemistry 1
      - Thermodynamics & statistical mechanics
    - Physcal Chemistry 2
      - Gases & fluids
    - Physical Chemistry 3
      - Quantum chemistry & mechanics
      - Linear algebra, vector calculus, qft, hilbert spaces, much more
   - Graduate
    - Statistical analysis of data
      - Inferential & descriptive stats
    - Spectral analysis
      - Signal processing
    - Advanced Inorganic Chemistry 1 & 2
      - Group theory, symmetry operations
      - My introduction to abstract algebra
      
- Non-traditional In Person Instruction
  - Galvanize Data Science Immersive
    - Grounded in Python, Galvanize's Data Science Immersive covers all the necessary tools and 
      concepts used by data scientists in industry, including machine learning, statistical inference, 
      and working with data at scale. The program is project based, and includes the development of 
      numerous data science applications. Topics include:
      - Exploratory Data Analysis and Software Engineering Best Practices
      - Statistical Inference, Bayesian Methods, A/B Testing, Multi-Armed Bandit
      - Regression, Regularization, Gradient Descent
      - Supervised Machine Learning: Classification, Validation, Ensemble Methods
      - Clustering, Topic Modeling (NMF, LDA), NLP
      - Network Analysis, Matrix Factorization, and Time Series
      - Hadoop, Hive, and MapReduce
      - Data Visualization with D3.js and Data Product Development
  
- MOOC Certificate Programs
  - Data Science for Executives (Columbia University via Edx)
    - Classes:
      - Statistical Thinking for Data Science and Analytics
      - Machine Learning for Data Science and Analytics
      - Enabling Technologies for Data Science and Analytics: The Internet of Things
  - Software Product Management (University of Alberta via Coursera)
    - link: https://www.coursera.org/account/accomplishments/specialization/F56XLQSAJHGE
    - Classes:
      - Introduction to Software Product Management
      - Software Processes and Agile Practices
      - Client Needs and Software Requirements
      - Agile Planning for Software Products
      - Reviews & Metrics for Software Improvements
  - Executive Data Science ( Johns Hopkins University via Coursera)
    - link: https://www.coursera.org/account/accomplishments/specialization/NS2NFFTCXKZE
    - Classes:
      - A Crash Course in Data Science
      - Building a Data Science Team
      - Managing Data Analysis
      - Data Science in Real Life
      - Executive Data Science Capstone

- Standalone MOOCS (roughly by subject)
  - Data Science
  - Computer Science
  - Math
  
    
    
In support of 
# Curriculum
