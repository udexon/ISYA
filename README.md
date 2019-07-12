
### Inverse Shunting Yard Algorithm

Dr. Ng Liang Shing <br>
July 2019

1. [Dijkstra's Shunting Yard Algorithm (DSYA)](https://en.wikipedia.org/wiki/Shunting-yard_algorithm) might be regarded as the common ancestor of subsequent programming languages. It was central to the design of ALGOL, which influenced all other modern programming languages.

It laymen's terms, it transforms infix notation `1 + 2` to Reverse Polish Notation `1 2 +` which is better suited for the stack machine architecture used by the computers during the 1960s. 

Programming languages have proliferated over the years, which unexpectedly and unfortunately created many undesireable side effects: 

e.g. Programmers today typically need to master at least half a dozen of programming languages to make a living, leading to tremendous diminishing returns, not least due to extraneous efforts in integrating software components written in multiple programming languages. 

***The Inverse Shunting Yard Algorithm (ISYA) described in this presentation will provide a method to create a universal script that can unify all known programming langauges.***

2. Although the Forth programming language has been implemented in many host Programming Languages in the past, I believe I was the first to coin the term ***Inverse Shunting Yard Algorithm (ISYA)*** as a generalization of *translating reverse Polish notation into a host (high level, "third generation") programming language,* which is effectively the inverse of Dijkstra's now legendary Shunting Yard Algorithm (DSYA).

Briefly, the steps include parsing a list of tokens in the Reverse Polish Notation, pushing non-function tokens on to the stack, and executing a function upon reading a function token.


3. I have published ISYA in JavaScript ([Stack Machine Shell for Ajax](http://5gl.epizy.com/nsm/fgl.html?i=3)) (Figures 1 and 2) and made PHP ISYA available upon request. Prototypes in Python, Java, Kotlin (Android) (Figures 3 and 4) are also available. 

<p align="center"><img src="https://github.com/udexon/ISYA/blob/master/smash-top.png" alt="ISYA Kotlin"  width="600"> 
<br>Figure 1</p>

<p align="center"><img src="https://github.com/udexon/ISYA/blob/master/smash-output.png" alt="ISYA Kotlin"  width="600"> 
<br>Figure 2</p>

<p align="center"> <img src="https://github.com/udexon/ISYA/blob/master/isya-kotlin.png" alt="ISYA Kotlin"  width="600"> 
<br>Figure 3: RPN is used to invoke and access OpenCV image processing code on Android, besides the mandatory arithmetic operations.</p>

<p align="center"> <img src="https://github.com/udexon/ISYA/blob/master/kotlin-5gl.png" alt="ISYA Kotlin"  width="200"> 
<br>Figure 4: Reverse Polish Notation expression "5 6 + 7 +" entered at top of the screen. The results 18 is shown at the bottom.</p>


4. ISYA reduces the effort of an individual programmer to learn and master a new programming language effectively down to zero, or writing the initial ISYA engine if it has not been done already.

My initial motivation of developing ISYA was to find a programming language that I can use for writing programs on a mobile phone. It effectively became a full stack programming language after I wrote the front end JavaScript and back end PHP engine for ISYA. I have called it 5GL, the Fifth Generation Grah Language, in tribute to Forth and graph theory. 

5. My survey shows that Forth implementations are also available in Rust, Go, Haskell and LISP. I believe the list is not exhaustive. 

6. I believe writing ISYA engine for a new programming language can be accomplished by a competent student who has completed one semester of programming language course. 

7. As such, I believe ISYA will lead to a revolution in teaching and learning of programming languages, and beyond that, mathematics.


8. For many years, progress in artificial intelligence seems to have stuck in a "perpetual" last mile, with Google's Alpha Go and descendants being the last round of hot air. 

9. Perhaps **homoiconicity**, a unique property exhibited by the reverse Polish notation, is the last missing piece to solve the puzzle of artificial intelligence. 

To summarize, the principle of homoiconicity implies that *artificial intelligence needs to be written in a programming language that can be used to analyze itself.* 

10. While not attempting to disclose the complete explanation in a short presentation like this, I shall hint upon the idea with a glaring example:

-- How many programmers know how to write a program to solve the following algebraic equation?

<p align="center"> 5 x + 3 x = 8 </p>

(I shall be forgiven for choosing these lucky numbers as a Chinese Malaysian myself.) 

11. To cut the long story short, solution of the above requires what is known as computer algebra system, whose pioneering work began in the 1960s, but was not made publicly available until Maxima was open sourced. 

Three further important efforts to popularize computer algebra systems were made subsequently in SageMath, Python SymPy and JavaScript Algebrite. 

Although SageMath, Python SymPy and JavaScript Algebrite represent important effort to popularize CAS, the programming languages used are not homoiconic -- you cannot use that programming language to analyze itself. 

12. To illustrate, see: [Computer Algebra System using Forth like Reverse Polish Notation]( https://github.com/udexon/SMASH/blob/master/CASFRPN.md)


<p align="center"> <img src="https://github.com/udexon/ISYA/blob/master/gltf-home.png" alt="ISYA Kotlin"  width="600"> 
<br>Figure 5</p>

In summary, reverse Polish notation has an elegant solution for algebraic equations, thus serving as a foundation to construct and analyze mathematical objects.

RPN allows AI code to be analyze homoiconically piecewise, from high level to low level e.g. distributive law code. Because RPN can also work at high level, hence it can be used to analyze code written in high level programming languages. This is my novel contribution as the Forth programming community is focused on low level applications.

13. In conclusion, ISYA (RPN) can create breakthroughs in programming, mathematics and artificial intelligence.

Just like other "simple ideas" such as Linux, the World Wide Web and Bitcoin, which all have a humble beginning but have changed the world, I believe ISYA (RPN) has the potential to create another revolution.

14. Besides the applications mentioned above, ISYA / RPN has many other implications, which we will leave until next time:
- free software distributed ownership of technology (Internet services like Torrent that are operated and owned by everyone), 
- a unified distributed virtual world, operated and owned by everyone, as a robotics and artificial intelligence research platform, and for virtual reality E-commerce, social networks and gaming
- [stack machine shell (SMASH)](https://github.com/udexon/SMASH), 
- [untraceable anonymous messaging and payment transactions ](https://github.com/udexon/DatongToken). 

