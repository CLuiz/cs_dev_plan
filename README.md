# cs_dev_plan
My personal development past, present, and future in regards to computer science, data science, math, etc. 

Both format and large portions of content have been taken from the OSSU computer science curriculum found here:
https://github.com/ossu/computer-science/blob/master/README.md.

I have used the base classes for the open source cs degree as an evaluation baseline, and will work towards proficiency
in each topic as listed below.  I will note when a class has been completed, or if I have evaluated and skipped
it based on my current skill and/or previous education.


# Contents

- [Summary](#summary)
- [Goals](#goals)
- [Philosophy](#philosophy)
- [Methodology](#methodology)
- [Curriculum](#curriculum)
  - [Introduction to Computer Science](#introduction-to-computer-science)
  - [Core CS](#core-cs)
  - [Advanced CS](#advanced-cs)
  - [Advanced Math](#advanced-math)
  - [Pro CS](#pro-cs)
  - [Special Topics](#special-topics)
- [Background](#background)
- [References](#references)

# Summary
This document is intended to help me map out a personal learning plan.
(personal evaluation statement here)  

# Goals
1. Grow as a data scientist. Specifically the application and tuning of neural networks & building intelligent systems.
1. Attain an understanding of computer science equivalent to a holder of a masters degree from a top university.
1. Attain a familiarity with the mathematic principles covered in an undergraduate ms/cs degree.
1. Improve my skills in regards to general software engineering. 
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

Courses | Duration | Effort | Prerequisites | Notes
:-- | :--: | :--: | :--: | :--:
[Introduction to Computer Science - CS50](https://www.edx.org/course/introduction-computer-science-harvardx-cs50x#!) ([alt](https://cs50.harvard.edu/)) | 12 weeks | 10-20 hours/week | none | Complete!
[Introduction to Computer Science and Programming using Python](https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-10) | 9 weeks | 15 hours/week | high school algebra | Complete!

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

Courses | Duration | Effort | Prerequisites | Notes
:-- | :--: | :--: | :--: | :--:
[How to Code - Simple Data](https://www.edx.org/course/how-code-simple-data-ubcx-htc1x) | 7 weeks | 8-10 hours/week | none | [In Progress](https://github.com/CLuiz/how-to-code-simple-data)
[How to Code - Complex Data](https://www.edx.org/course/how-code-complex-data-ubcx-htc2x) | 6 weeks | 8-10 hours/week | How to Code: Simple Data |
[Software Construction - Data Abstraction](https://www.edx.org/course/software-construction-data-abstraction-ubcx-softconst1x) | 6 weeks | 8-10 hours/week | How to Code - Complex Data |
[Software Construction - Object-Oriented Design](https://www.edx.org/course/software-construction-object-oriented-ubcx-softconst2x) | 6 weeks | 8-10 hours/week | Software Construction - Data Abstraction |
[Programming Languages, Part A](https://www.coursera.org/learn/programming-languages) | 4 weeks | 8-16 hours/week | recommended: Java, C |
[Programming Languages, Part B](https://www.coursera.org/learn/programming-languages-part-b) | 3 weeks | 8-16 hours/week | Programming Languages, Part A |
[Programming Languages, Part C](https://www.coursera.org/learn/programming-languages-part-c) | 3 weeks | 8-16 hours/week | Programming Languages, Part B |

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

Courses | Duration | Effort | Prerequisites | Notes
:-- | :--: | :--: | :--: | :--:
[Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | - | - | pre-calculus | Complete!
[Linear Algebra - Foundations to Frontiers](https://www.edx.org/course/linear-algebra-foundations-frontiers-utaustinx-ut-5-04x#!) ([alt](http://ulaff.net/)) | 15 weeks | 8 hours/week | Essence of Linear Algebra |
[Calculus One](https://www.coursera.org/learn/calculus1)<sup>*1*</sup> ([alt](https://mooculus.osu.edu/)) | 16 weeks | 8-10 hours/week | pre-calculus | Completed Equivalent - UG
[Calculus Two: Sequences and Series](https://www.coursera.org/learn/advanced-calculus)| 7 weeks | 9-10 hours/week | Calculus One | Completed Equivalent - UG
[Mathematics for Computer Science](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/index.htm) | 13 weeks | 5 hours/week | single variable calculus (Calculus Two) | In progress

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

Courses | Duration | Effort | Prerequisites | Notes
:-- | :--: | :--: | :--: | :--:
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

Courses | Duration | Effort | Prerequisites | Notes
:-- | :--: | :--: | :--: | :--:
[Algorithms: Design and Analysis, Part I](https://lagunita.stanford.edu/courses/course-v1:Engineering+Algorithms1+SelfPaced/about) | 8 weeks | 4-8 hours/week | any programming language, Mathematics for Computer Science |
[Algorithms: Design and Analysis, Part II](https://lagunita.stanford.edu/courses/course-v1:Engineering+Algorithms2+SelfPaced/about) | 8 weeks | 4-8 hours/week | Part I |


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

Courses | Duration | Effort | Prerequisites | Notes
:-- | :--: | :--: | :--: | :--:
[Databases](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/about)| 12 weeks | 8-12 hours/week | some programming, basic CS |
[Machine Learning](https://www.coursera.org/learn/machine-learning)| 11 weeks | 4-6 hours/week | linear algebra | Complete!
[Cryptography I](https://www.coursera.org/course/crypto)| 6 weeks | 5-7 hours/week | linear algebra, probability |
[Software Engineering: Introduction](https://www.edx.org/course/software-engineering-introduction-ubcx-softeng1x) | 6 weeks | 8-10 hours/week | Software Construction - Object-Oriented Design |
[Software Development Capstone Project](https://www.edx.org/course/software-development-capstone-project-ubcx-softengprjx) | 6-7 weeks | 8-10 hours/week | Software Engineering: Introduction |

## Advanced CS

After completing **every required course** in Core CS, students should choose a subset of courses from Advanced CS based on interest.
Not every course from a subcategory needs to be taken.
But students should take *every* course that is relevant to the field they intend to go into.

The Advanced CS study should then end with one of the Specializations under [Advanced applications](#advanced-applications).
A Specialization's Capstone, if taken, may act as the [Final project](#final-project), if permitted by the Honor Code of the course.
If not, or if a student chooses not to take the Capstone, then a separate Final project will need to be done to complete this curriculum.

### Advanced programming

**Topics covered**:
`debugging theory and practice`
`goal-oriented programming`
`GPU programming`
`CUDA`
`parallel computing`
`object-oriented analysis and design`
`UML`
`large-scale software architecture and design`
`and more`

Courses | Duration | Effort | Prerequisites | Notes
:-- | :--: | :--: | :--: | :--:
[Compilers](https://lagunita.stanford.edu/courses/Engineering/Compilers/Fall2014/about)| 9 weeks | 6-8 hours/week | none |
[Software Debugging](https://www.udacity.com/course/software-debugging--cs259)| 8 weeks | 6 hours/week | Python, object-oriented programming |
[Software Testing](https://www.udacity.com/course/software-testing--cs258) | 4 weeks | 6 hours/week | programming experience |
[LAFF: Programming for Correctness](https://www.edx.org/course/laff-programming-correctness-utaustinx-ut-p4c-14-01x) | 7 weeks | 6 hours/week | linear algebra |
[Introduction to Parallel Programming](https://www.udacity.com/course/intro-to-parallel-programming--cs344) | 12 weeks | - | C, algorithms |
[Software Architecture & Design](https://www.udacity.com/course/software-architecture-design--ud821)| 8 weeks | 6 hours/week | software engineering in Java |

### Advanced math

**Topics covered**:
`parametric equations`
`polar coordinate systems`
`multivariable integrals`
`multivariable differentials`
`probability theory`
`and more`

Courses | Duration | Effort | Prerequisites | Notes
:-- | :--: | :--: | :--: | :--:
[Calculus: Parametric Equations and Polar Coordinates](https://ocw.mit.edu/courses/mathematics/18-01sc-single-variable-calculus-fall-2010/unit-4-techniques-of-integration/part-c-parametric-equations-and-polar-coordinates/) | - | - | single-variable calculus (Calculus Two) | Completed Equivalent - UG
[Multivariable Calculus](https://ocw.mit.edu/courses/mathematics/18-02sc-multivariable-calculus-fall-2010/index.htm) | 13 weeks | 12 hours/week | Parametric Equations and Polar Coordinates | Completed Equivalent - UG
[Introduction to Probability - The Science of Uncertainty](https://www.edx.org/course/introduction-probability-science-mitx-6-041x-2) | 18 weeks | 12 hours/week | Multivariable Calculus | Completed Equivalent - G

### Advanced systems

**Topics covered**:
`digital signaling`
`combinational logic`
`CMOS technologies`
`sequential logic`
`finite state machines`
`processor instruction sets`
`caches`
`pipelining`
`virtualization`
`parallel processing`
`virtual memory`
`synchronization primitives`
`system call interface`
`and more`

Courses | Duration | Effort | Prerequisites | Notes
:-- | :--: | :--: | :--: | :--:
[Electricity and Magnetism, Part 1](https://www.edx.org/course/electricity-magnetism-part-1-ricex-phys102-1x-0)<sup>1</sup> | 7 weeks | 8-10 hours/week | calculus, basic mechanics | Completed Equivalent - UG
[Electricity and Magnetism, Part 2](https://www.edx.org/course/electricity-magnetism-part-2-ricex-phys102-2x-0) | 7 weeks | 8-10 hours/week | Electricity and Magnetism, Part 1 | Completed Equivalent - UG
[Computation Structures 1: Digital Circuits](https://www.edx.org/course/computation-structures-part-1-digital-mitx-6-004-1x-0) | 10 weeks | 6 hours/week | electricity, magnetism | Compare to [6002.x](https://www.edx.org/course/circuits-electronics-1-basic-circuit-mitx-6-002-1x-0)
[Computation Structures 2: Computer Architecture](https://www.edx.org/course/computation-structures-2-computer-mitx-6-004-2x) | 10 weeks | 6 hours/week | Computation Structures 1
[Computation Structures 3: Computer Organization](https://www.edx.org/course/computation-structures-3-computer-mitx-6-004-3x-0) | 10 weeks | 6 hours/week | Computation Structures 2

**<sup>1</sup> Note**:
These courses assume knowledge of basic physics.
([Why?](FAQ.md#why-is-the-curriculum-missing-some-pre-requisites))
If you are struggling, you can find a physics MOOC or utilize the materials from Khan Academy:
[Khan Academy - Physics](https://www.khanacademy.org/science/physics)

### Advanced theory

**Topics covered**:
`formal languages`
`Turing machines`
`computability`
`event-driven concurrency`
`automata`
`distributed shared memory`
`consensus algorithms`
`state machine replication`
`computational geometry theory`
`propositional logic`
`relational logic`
`Herbrand logic`
`concept lattices`
`game trees`
`and more`

Courses | Duration | Effort | Prerequisites | Notes
:-- | :--: | :--: | :--: | :--:
[Introduction to Logic](https://www.coursera.org/learn/logic-introduction) | 10 weeks | 4-8 hours/week | set theory | -
[Automata Theory](https://lagunita.stanford.edu/courses/course-v1:ComputerScience+Automata+Fall2016/about) | 8 weeks | 10 hours/week | discrete mathematics, logic, algorithms | -
[Reliable Distributed Systems, Part 1](https://www.edx.org/course/reliable-distributed-algorithms-part-1-kthx-id2203-1x) | 5 weeks | 5 hours/week | Scala, intermediate CS | -
[Reliable Distributed Systems, Part 2](https://www.edx.org/course/reliable-distributed-algorithms-part-2-kthx-id2203-2x) | 5 weeks | 5 hours/week | Part 1 | -
[Computational Geometry](https://www.edx.org/course/computational-geometry-tsinghuax-70240183x) | 16 weeks | 8 hours/week | algorithms, C++ | -
[Introduction to Formal Concept Analysis](https://www.coursera.org/learn/formal-concept-analysis) | 6 weeks | 4-6 hours/week | logic, probability | -
[Game Theory](https://www.coursera.org/learn/game-theory-1) | 8 weeks | x hours/week | mathematical thinking, probability, calculus | -
[Advanced Data Structures](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-851-advanced-data-structures-spring-2012/) | 11 weeks | 12 hours/week | algorithms, data structures | - 


## CS Special Topics

### General Deep Learning/AI 
Courses | Duration | Effort | Prerequisites | Notes
:-- | :--: | :--: | :--: | :--:
[Deep Learning With Tensorflow](https://cognitiveclass.ai/courses/deep-learning-tensorflow/) | 1 week | 10 hours | python, deep learning | Complete!
[FastA1 Course 1](http://course.fast.ai/) | 7 weeks | 10 hours/week | python | -
[FastAI Course 2](http://course.fast.ai/part2.html) | 7 weeks | 10 hours/week | python, FastAI Course 1 | - 
[Computer Vision](https://www.udacity.com/course/introduction-to-computer-vision--ud810) | 12 weeks | | |-
AI course | | | |-

### Reinforcement Learning
Courses | Duration | Effort | Prerequisites | Notes
:-- | :--: | :--: | :--: | :--:
[UCL Course on RL](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html)| | | |
[Berkely CS 294: Deep Reinforcement Learning](http://rll.berkeley.edu/deeprlcourse/)| | | |
[Udacity Reinforcement Learning Course](https://www.udacity.com/course/reinforcement-learning--ud600)| | | |

### Misc
Courses | Duration | Effort | Prerequisites | Notes
:-- | :--: | :--: | :--: | :--:
[MIT 6.854J EE & CS](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-854j-advanced-algorithms-fall-2005/) | | | |


## Math Special Topics
Courses | Duration | Effort | Prerequisites | Notes
:-- | :--: | :--: | :--: | :--:
[MIT Math 18.315](https://ocw.mit.edu/courses/mathematics/18-315-combinatorial-theory-introduction-to-graph-theory-extremal-and-enumerative-combinatorics-spring-2005) | 13 weeks | 12 hours/week | Graph Theory|
[MIT Math 18.901 Topology](https://ocw.mit.edu/courses/mathematics/18-901-introduction-to-topology-fall-2004/) | | | |

## [Reading List](https://github.com/CLuiz/cs_dev_plan/blob/master/reading_list.md)

# [Background](https://github.com/CLuiz/cs_dev_plan/blob/master/background.md)

# References
  - http://csmajor.stanford.edu/ProgramSheets.shtml
  - https://github.com/ossu/computer-science/blob/master/README.md
