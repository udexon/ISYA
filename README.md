
### Inverse Shunting Yard Algorithm

Dr. Ng Liang Shing

July 2019

Programming Languages have proliferated over the years. Programmers today typically need to master at least half a dozen of Programming Languages to make a living, leading to tremendous diminishing returns, not least due to extraneous efforts in integrating software components written in multiple Programming Languages. 

Although the Forth programming language has been implemented in many host Programming Languages in the past, I believe I was the first to coin the term Inverse Shunting Yard Algorithm (ISYA) as a generalization of translating reverse Polish notation into a host (high level, "third generation") programming language, which is effectively the inverse of Dijkstra's now legendary Shunting Yard Algorithm (DSYA).

I have published ISYA in JavaScript on ... and made PHP ISYA available upon request. Prototypes in Python , Java, Kotlin are also available. 

ISYA reduces the effort of an individual programmer to learn and master a new Programming Language effectively down to zero, or writing the initial ISYA engine if it has not been done already.

My survey shows that Forth implementations are also available in Rust, Go, Haskell and LISP. I believe the list is not exhaustive. 

I believe Writing ISYA for a new Programming Language can be accomplished by a competent student who has completed one semester of Programming Language course. 

As such, I believe ISYA will lead to a Revolution in teaching and learning of Programming Languages, and beyond that, mathematics.


For many years, progress in artificial intelligence seems to have stuck in a "perpetual" last mile, with Google's Alpha Go and descendants being the last round of hot air. 

Perhaps homoiconicity, a unique property exhibited by the reverse Polish notation, is the last missing piece to solve the puzzle of artificial intelligence. To summarize, the principle of homoiconicity implies that artificial intelligence needs to be written in a programming language that can be used to analyze itself. 

While not attempting to disclose the complete explanation in a short presentation like this, I shall hint upon the idea with a glaring example:

-- How many programmers know how to write a program to solve the following algebraic equation?

5 x + 3 x = 8

I shall be forgiven for choosing these lucky numbers as a Chinese Malaysian myself. 

To cut the long story short, solution of the above requires what is known as computer algebra system, whose pioneering work began in the 1960s, but was not made publicly available until Maxima was open sourced. 

Three further important efforts to popularize computer algebra systems were made subsequently in SageMath, Python SymPy and JavaScript Algebrite. 

Although SageMath, Python SymPy and JavaScript Algebrite represent important effort to popularize CAS, the programming languages used are not homoiconic -- you cannot use that programming language to analyze itself. 

To illustrate, see: [Computer Algebra System using Forth like Reverse Polish Notation]( https://github.com/udexon/SMASH/blob/master/CASFRPN.md)

In summary, reverse Polish notation has an elegant solution for algebraic equations, thus serving as a foundation to construct and analyze mathematical objects.

ISYA RPN has many other implications such as free software distributed ownership of technology, untraceable anonymous messaging and payment transactions ...., we end the presentation here, to continue on other topics next time. Stack machine shell.

Programming, mathematics, AI. 


RPN allows AI code to be analyze homoiconically piecewise, from high level to low level e.g. distributive law code. Because RPN can also work at high level, hence can analyze high level programming languages!!

