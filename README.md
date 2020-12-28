# Learning-of-Computer-Science
First, I prefer to have a overview of a new topic I am ready to learn. This picture illustrates almost all of the areas related to computer science and there is a short [video](https://www.youtube.com/watch?v=SzJ46YA_RaA) talking about it. 
![image](https://github.com/Billy1900/Learning-of-Computer-Science/blob/master/large.png)
Besides, one well known subject classification system for computer science is the ACM Computing Classification System devised by the Association for Computing Machinery from the [Wiki](https://en.wikipedia.org/wiki/Outline_of_computer_science).



# 0. Basic/Introduction
- [CS50](https://cs50.harvard.edu/college/2020/fall/#:~:text=Introduction%20to%20the%20intellectual%20enterprises%20of%20computer%20science%20and%20the%20art%20of%20programming.): Introduction to the intellectual enterprises of computer science and the art of programming. 
- [CS106B Programming Abstractions](https://web.stanford.edu/class/cs106b/): this is a basic/introductory course from Stanford whose content includes knowledge of object-oriented programming, data structures (collections, graphs, etc.).
- [Computer Organization & Systems](http://web.stanford.edu/class/cs107/): CS107 is the third course in Stanford's introductory programming sequence. The CS106 courses provide you with a solid foundation in programming methodology and abstractions, and CS107 follows on this to build up and expand your breadth and depth of programming experience and techniques. The course will work from the C programming language down to the microprocessor to de-mystify the machine.
- [Mathematical foundations of computing](http://web.stanford.edu/class/archive/cs/cs103/cs103.1184/): This course is about mathematical techniques that are useful in computer science, to analyze algorithms and prove impossibility results. The course has four parts: (1) introduction to the kind of discrete mathematics that is useful in computer science, including sets, graphs and proofs by induction; (2) finite automata, which model simple linear-time algorithms and capture the power of regular expressions — we will be able to understand the power and limitation of this class of algorithms inside out; (3) turing machines and undecidability, in which we study the power of arbitrary algorithms that are allowed arbitrarily large running times — we will show that there are several important problems that are unsolvable even under such conditions; (4) complexity theory and NP-completeness, which is concerned with the study of what we can do with efficient algorithms. I think it is very important to grasp that how to write paper mathematically by reading these two--[Mathematical Writing](https://jmlr.org/reviewing-papers/knuth_mathematical_writing.pdf) and [Some Remarks on Writing Mathematical Proofs](https://sites.math.washington.edu/~lee/Writing/writing-proofs.pdf)
- [Simple overview of Computer Science](https://www.youtube.com/playlist?list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo): this video is a simplistic introduction of computer science, short but comprehensive, very friendly to beginners.



# 1. Mathematical Background
## 1.1 Calculus
- [Thomas Calculus](https://www.academia.edu/38787152/Pdf_Thomas_Calculus_Multivariable_14th_Edition): Thomas' Calculus helps students reach the level of mathematical proficiency and maturity you require, but with support for students who need it through its balance of clear and intuitive explanations, current applications, and generalized concepts. In the 14th Edition, new co-author Christopher Heil (Georgia Institute of Technology) partners with author Joel Hass to preserve what is best about Thomas' time-tested text while reconsidering every word and every piece of art with today's students in mind. The result is a text that goes beyond memorizing formulas and routine procedures to help students generalize key concepts and develop deeper understanding. This course ([Course Link](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)) could definitely help you intuitively get a better understanding of Calculus and it is really the best course I have ever taken.
## 1.2 Linear Algebra
- [MIT Linear Algebra](https://github.com/yizhen20133868/MIT-Linear-Algebra-Notes): This course parallels the combination of theory and applications in Professor Strang’s textbook Introduction to Linear Algebra. The course picks out four key applications in the book: Graphs and Networks; Systems of Differential Equations; Least Squares and Projections; and Fourier Series and the Fast Fourier Transform. This course ([Course Link](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)) could definitely help you intuitively get a better understanding of Calculus and it is really the best course I have ever taken. Moreover, this interactive book ([Book](https://textbooks.math.gatech.edu/ila/)) could help you learn Linear Algebra more interestingly.
## 1.3 Probabilistic
- [MIT RES.6-012](https://www.youtube.com/watch?v=1uW3qMFA9Ho&list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6): Probability is the science of how likely events are to happen. At its simplest, it’s concerned with the roll of a dice, or the fall of the cards in a game. But probability is also vital to science and life more generally. I really recommend this course from MIT, and this book ([Book](http://tomlr.free.fr/Math%E9matiques/Math%20Complete/Probability%20and%20statistics/CRC%20-%20standard%20probability%20and%20Statistics%20tables%20and%20formulae%20-%20DANIEL%20ZWILLINGER.pdf)) is the most comprehensive dictionary of probability and statistics I have ever seen.

Besides, as the course is too long, people have to spend a lot of time following it, there are some lecture notes which could help you have an overview of probalistic quickly.
- [Probability Theory: STAT310/MATH230](https://statweb.stanford.edu/~adembo/stat-310b/lnotes.pdf)
- [Probability for first year mathematicians at Cambridge in winter 2015](http://www.statslab.cam.ac.uk/~rrw1/prob/index.html)
## 1.4 Statistic
This course from MIT, named [Statistics for Applications (video)](https://ocw.mit.edu/courses/mathematics/18-650-statistics-for-applications-fall-2016/index.htm). This course offers an in-depth the theoretical foundations for statistical methods that are useful in many applications. The goal is to understand the role of mathematics in the research and development of efficient statistical methods. And for people who prefer slides, this [Site](https://ocw.mit.edu/courses/mathematics/18-650-statistics-for-applications-fall-2016/) may could help you, and chinese version [blog](https://zhuanlan.zhihu.com/p/29758751). [This repo](https://github.com/SleepyBag/Statistical-Learning-Methods) is Python implemented Statistical Leanring Methods, Li Hang the hard way.

## 1.5 Applied Mathematics for computer science
In some ways, computer science is an overgrown branch of applied mathematics. While many software engineers try—and to varying degrees succeed—at ignoring this, we encourage you to embrace it with direct study. Doing so successfully will give you an enormous competitive advantage over those who don’t. 

The most relevant area of math for CS is broadly called “discrete mathematics”, where “discrete” is the opposite of “continuous” and is loosely a collection of interesting applied math topics outside of calculus. Given the vague definition, it’s not meaningful to try to cover the entire breadth of “discrete mathematics”. A more realistic goal is to build a working understanding of logic, combinatorics and probability, set theory, graph theory, and a little of the number theory informing cryptography. Linear algebra is an additional worthwhile area of study, given its importance in computer graphics and machine learning.

For a more advanced treatment, we suggest [Mathematics for Computer Science](https://courses.csail.mit.edu/6.042/spring17/mcs.pdf), the book-length lecture notes for the MIT course of the same name.


# 2. Core Course in Computer Science
## 2.1 Operating system
- [CS 140: Operating Systems (Spring 2020)](http://web.stanford.edu/~ouster/cgi-bin/cs140-spring20/index.php): This class introduces the basic facilities provided by modern operating systems.
- [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/) is a good alternative that’s freely available online. We particularly like the structure and readability of the book, and feel that the exercises are worthwhile.
## 2.2 Compiler
- [The excellent introductory book: Crafting Interpreters](https://craftinginterpreters.com/contents.html)
- [CS143 compilers](http://web.stanford.edu/class/cs143/): Their knowledge generalizes; they are able to understand the operation of a new language more deeply and quickly than those who have merely learned specific languages.
- [Compiler Explorer](https://godbolt.org/z/bWe77x): Compiler Explorer is a handy website that lets you quickly write C code and see its assembly translation.
## 2.3 Computer network
- [CS 144: Introduction to Computer Networking, Fall 2020](https://cs144.github.io/)
- [Computer Networking: A Top-Down Approach](https://www.ucg.ac.me/skladiste/blog_44233/objava_64433/fajlovi/Computer%20Networking%20_%20A%20Top%20Down%20Approach,%207th,%20converted.pdf) is our favorite book on this topic. The small projects and exercises in the book are well worth doing, and we particularly like the [“Wireshark labs”](https://gaia.cs.umass.edu/kurose_ross/wireshark.htm).
## 2.4 Algorithm
- [DESIGN AND ANALYSIS OF ALGORITHMS](http://web.stanford.edu/class/cs161/): This course will cover the basic approaches and mindsets for analyzing and designing algorithms and data structures. Topics include the following: Worst and average case analysis. Recurrences and asymptotics. 

My preferred approach is to solve problems on Leetcode, some instructions are as follows:
- [fucking-algorithm](https://github.com/labuladong/fucking-algorithm): Crack LeetCode, not only how, but also why.
- [LeetCodeAnimation](https://github.com/MisterBooo/LeetCodeAnimation): Demonstrate all the questions on LeetCode in the form of animation.

Finally, we strongly recommend [How to Solve It](https://www.semanticscholar.org/paper/How-to-Solve-It.-A-New-Aspect-of-Mathematical-Bell-P%C3%B3lya/a161c79a03add75b74e4b4dc896b7c5c9b1cc5c3) as an excellent and unique guide to general problem solving; it’s as applicable to computer science as it is to mathematics
## 2.5 Computer/Digital system design/architecture
- [CS110 Principles of Computer Systems](http://web.stanford.edu/class/cs110/): Principles and practice of engineering of computer software and hardware systems. Topics include: techniques for controlling complexity; strong modularity using client-server design, virtual memory, and threads; networks; atomicity and coordination of parallel activities. Besides, I also recommend to use this book--[Computer Systems: A Programmer's Perspective](https://csapp.cs.cmu.edu/)
## 2.6 Database
One paper particularly worth mentioning for new students is [“Architecture of a Database System”](https://dsf.berkeley.edu/papers/fntdb07-architecture.pdf), which uniquely provides a high-level view of how relational database management systems (RDBMS) work. This will serve as a useful skeleton for further study. And for courses,
- [Data Management and Data Systems](https://cs145-fa19.github.io/): This course covers how to use databases in applications, first principles on how to scale for large data sets and how to design good data systems.



## 3. Complementary
- [Guides: Teach Yourself Computer Science](https://ozwrites.com/)
