---
layout: default
title: "CS202: Discrete Structures"
course_description: "An introduction to the mathematical foundations from discrete mathematics that are used for analyzing computer algorithms for correctness and performance. This course introduces models of computation, including finite state machines and Turing machines."
next: ../Unit04
previous: ../Unit02
---
**Unit 3: Introduction to Number Theory and Proof Methods** <span
id="3"></span> 
*In this unit, we will learn the properties of integers, real numbers,
rational numbers, irrational numbers, and operations on all of these
types of numbers. Our goal will be to learn how to determine the
validity or falsity of a mathematical statement via a number of methods,
including counterexample and exhaustion. We will apply these methods to
not only prove the validity of the properties of the number types we are
studying in this unit, but provide a practical approach to them so that
future mathematical arguments can be proved or disproved using these
methods.*

**Unit 3 Time Advisory**  
This unit should take you 11.25 hours to complete.  
  
 ☐    Subunit 3.1: 4 hours  
  
 ☐    Subunit 3.2: 2 hours  
  
 ☐    Subunit 3.3: 3.25 hours  
  
 ☐    Assessment 1: 1 hour  
  
 ☐    Assessment 2: 1 hour

**Unit3 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:
-   apply the rules of logic and proof techniques to mathematical
    statements involving odd and even, prime, rational, and irrational
    numbers; and
-   prove and apply properties of divisibility.

**3.1 Direct Proofs and Indirect Proofs** <span id="3.1"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Proofs”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:*
    [“Proofs”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Proofs-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Proofs-Srini-Devadas.epub)  
        
     Instructions: Read the opening discussion, “Proofs,” Section 1,
    “The Axiomatic Method,” and Sections 2 - 6, inclusive. In Unit 3,
    you will get a chance to apply a lot of what you have thought about
    and mastered in Units 1 and 2. Our domain of discourse is number
    theory, in particular proofs in elementary number theory.  
        
     Consider the following comparison of direct and indirect proofs. A
    direct proof is an argument that shows that the conclusion logically
    follows from the premises or assumptions by applying rules of
    inference in a sequence of steps.  
        
     Sections 1, 2, 4, and 5 deal with direct proofs. Section 2,
    “Proving an Implication,” refers to statement such as *P implies Q*,
    and proving that Q is a consequence of P. In a logic system, P
    logically follows from the axioms and valid statements of the logic
    system, is another way of saying that P is a consequence of the
    axioms and valid statements or P is implied by them. This is what is
    meant by *proving an implication*.  
        
     Section 3 is related to indirect proof. Section 6 discusses
    indirect proof, also known as proof by contradiction, directly. An
    indirect proof, in contrast, is a proof in which the theorem to be
    proved is assumed false, and from this assumption, it is shown that
    a contradiction follows. Because the logic system is consistent,
    i.e. there are no contradictions, the theorem must be true. (Two
    statements are contradictions when they cannot both be true, and
    they cannot both be false.)  
        
     Reading this selection and taking notes should take approximately 1
    hour.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Arithmetic, Logic
    and Numbers: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
        
     Instructions: Read example 1 - example 4 on pages SF-3 - SF-6. It
    discusses proofs for sets.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**3.1.1 Odd and Even Numbers** <span id="3.1.1"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit NT: Number Theory”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit NT: Number
    Theory”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.epub)  
      
     Instructions: Read Section 1 through example 1 on pages NT-1 and
    NT-2. There are several commonly used sets of numbers that will be
    introduced to you; the first is the set of odd and even integers,
    i.e. the set of integers.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**3.1.2 Prime Numbers** <span id="3.1.2"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic,
    and Numbers: Unit NT: Number Theory”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic,
    Logic, and Numbers: Unit NT: Number
    Theory”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.epub)  
        
     Instructions: Read Section 1 beginning at “Prime Numbers and
    Factorization” on page NT-3, and continue up to example 3 on page
    NT-4. Example 3 also applies to 3.1.4 and 3.2.2 below. Prime numbers
    are the next set of commonly used numbers to be introduced. The
    introduction of prime numbers leads to the discussion of factoring
    an integer.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**3.1.3 Proving and Disproving Universal Statements** <span
id="3.1.3"></span> 
*Note: Statements often involve universal quantifiers. The following
subunits examine ways used to prove or disprove such statements. *

**3.1.3.1 Proof by Using the Method of Exhaustion** <span
id="3.1.3.1"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit NT: Number Theory”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit NT: Number
    Theory”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.epub)  
      
     Instructions: Reread example 2 on page NT-2, with special attention
    to the proof method, called proof by induction (an exhaustive proof
    method). This material also applies to the topic in subunit 3.3.1.1
    of this course. This reading discusses a universal statement, which
    is just a statement that involves universal quantification.  
        
     Reading this selection and taking notes should take approximately
    15 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

-   **Reading: The Saylor Foundation’s “Proof by Exhaustion”**
    Link: The Saylor Foundation’s [“Proof by
    Exhaustion”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS-202-Subunit-3.1.3.1-Proof-by-Exhaustion_FINAL.pdf) (PDF)  
        
     Instructions: This reading comments on proof by exhaustion.  
        
     Reading this selection and taking notes should take approximately
    15 minutes.

**3.1.3.2 Disproof by Counterexample** <span id="3.1.3.2"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit NT: Number Theory”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit NT: Number
    Theory”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.epub)  
        
     Instructions: Read over the Exercises for Section 1 on pages
    NT-10 - NT-13. Note the use of counterexamples. A universally
    quantified statement may be false. It can be proven false by showing
    that there exists an instance of the universally bound variable for
    which the statement is false. The instance is called a counter
    example. Exercises often have useful information, also applicable
    outside of the exercise.  
      
     Reading this selection and taking notes should take approximately
    30 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**3.1.4 Proving and Disproving an Existential Statement** <span
id="3.1.4"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit NT: Number Theory”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit NT: Number
    Theory”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.epub)  
      
     Instructions: Read example 5 on pages NT-5 and NT-6. An existential
    statement can be proved directly by specifying the instance of the
    existentially bound variable that makes the statement true. To
    disprove an existential statement, transform its negation to an
    equivalent universal statement, by using the property where the
    negation of an existential quantifier becomes a universal
    quantifier, (negating there exists an x such that P(x) becomes for
    all x not P(x)). Then, prove the universal statement.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in 

**3.2 Numbers: Direct Proofs and Counterexamples** <span
id="3.2"></span> 
*Note: Logic has application to other parts of mathematics, not just to
reasoning about the world. The following subunits apply logic to
statements about numbers. *

**3.2.1 Rational Numbers** <span id="3.2.1"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit NT: Number Theory”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit NT: Number
    Theory”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.epub)  
        
     Instructions: Read Section 1: “Basic Facts about Numbers,” example
    4 on page NT-5. This example proves an important property of
    rational numbers using a constructive proof technique. This reading
    also applies to the topic in subunit 3.2.3 of this course.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**3.2.2 Irrational Numbers** <span id="3.2.2"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit NT: Number Theory”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Arithmetic, Logic
    and Numbers: Unit NT: Number
    Theory”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.epub)  
      
     Instructions: Read Section 1: “Basic Facts about Numbers,” example
    5 on pages NT-5 and NT-6 and example 6 on pages NT-7 - NT-9. Example
    5 proves a property of real numbers using counterexamples. Example 6
    applies to integer, rational, and real numbers. This reading also
    applies to the topics in Subunits 3.2.3 and Subunit 3.3.  
        
     Reading this selection and taking notes should take approximately
    45 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**3.2.3 Proving Properties of Rational Numbers** <span
id="3.2.3"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Notes for
    Recitation 2”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Notes for Recitation
    2”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Case-Analysis.pdf) (PDF)  
      
     Instructions: Read the recitation on pages 1 - 5. These give more
    examples of proof techniques for numbers.  
      
     Reading this selection and taking notes should take approximately
    45 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**3.3 Divisibility: Direct Proofs and Counterexamples** <span
id="3.3"></span> 
*Note: The following subunits continue the appliction of logic to number
theory.*

**3.3.1 Divisibility** <span id="3.3.1"></span> 
*Note: The following subunits examine important properties of
divisibility.*

**3.3.1.1 Divisibility Definition** <span id="3.3.1.1"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Number Theory
    I”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Number Theory
    I”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NumberTheory1.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NumberTheory1-Srini-Devadas.epub)  
      
     Instructions: Read Section 1, “Divisibility” on pages 1 - 4 and
    Section 4, “The Greatest Common Divisor” on pages 7 - 12. This
    reading overlaps that of Bender and Williamson.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit NT: Number Theory”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Arithmetic, Logic
    and Numbers: Unit NT: Number
    Theory”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.epub)  
        
     Instructions: Read “Remainders and Modular Arithmetic*,”* page NT-6
    to the top of NT-9. Section 2 and Section 3 are motivational, and
    you should at a minimum scan over them. Note that these discussions
    in the readings pertain to integers. They also apply to the
    following Subunits: 3.3.1.2 and 3.3.1.3. In considering divisors of
    zero for Subunit 3.3.1.2 as you read through these sections,
    remember that every integer a divides 0, since a · 0 = 0. This also
    holds for rational, irrational, and real numbers, since w · 0 = 0
    for any real number w.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**3.3.1.2 Divisors of Zero and Division by Zero** <span
id="3.3.1.2"></span> 
*Note: Division by zero is covered in the Bender and Williamson above.  
    
 We say that division by zero is undefined. Why do we say that? Consider
the following line of reasoning: suppose x is a non-zero number, and
when it is divided by zero, the result is the specific number y. It can
be proved that, if x / 0 = y, then x = 0 multiplied by y (i.e. x = 0 \*
y). But, then, x = 0 \* y = 0, because any number multiplied by 0 is 0.
However, we assumed that x was non zero, a contradiction.  
    
 If x were 0, then x / 0 = 0 / 0 = y. Again, this implies that 0 = 0 \*
y. This, in turn, implies that y could be any number. This is, again, a
contradiction, because we assumed that y was a specific number.  
    
 Mathematical definitions and proofs are specified to adhere to certain
rules. One of those rules is that results do not lead to contradictions.
Therefore, we say that division by 0 is not defined.*

**3.3.1.3 The Positive Divisors of a Positive Number** <span
id="3.3.1.3"></span> 
*Note: This topic is also covered by the Bender and Williamson in
Subunit 3.3.1.1. Theorem 1 on page NT-3 states that for any given
integer, \> or = 2, can be written as the product of prime numbers. Each
of these primes will be a divisor of the given integer.*

**3.3.1.4 Divisibility of Algebraic Expressions** <span
id="3.3.1.4"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Induction I”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science*: [“Induction
    I”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction1.pdf) (PDF)  
        
     Instructions: Read Section 3, “A Divisibility Theorem.” This
    reading also applies to the topics in subunits 3.3.2, 3.3.2.1,
    3.3.2.2, and 3.3.2.3 of this course.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

-   **Reading: The Saylor Foundation’s “General Theorem: Divisibility of
    Algebraic Expression”**
    Link: The Saylor Foundation’s [“General Theorem: Divisibility of
    Algebraic
    Expression”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS202-Subunit-3.3.1.4-General-Theorem-of-Divisibility-by-an-Integer_FINAL.pdf) (PDF)  
        
     Instructions: Read the text in its entirety.  
        
     Reading this selection and taking notes should take approximately
    15 minutes.

**3.3.2 Proving Properties of Divisibility** <span id="3.3.2"></span> 
*Note: The readings for the following subunits prove some properties of
divisibility (in particular, the fundamental theorem of arithmetic),
which we typically use often in arithmetic.*

**3.3.2.1 Transitivity of Divisibility** <span id="3.3.2.1"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Number Theory
    I”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Number Theory
    I”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NumberTheory1.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NumberTheory1-Srini-Devadas.epub)  
        
     Instructions: Review Lemma 1 in Section 1.1 on page 2.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**3.3.2.2 Divisibility by a Prime** <span id="3.3.2.2"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Number Theory
    I”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Number Theory
    I”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NumberTheory1.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NumberTheory1-Srini-Devadas.epub)  
        
     Instructions: Read Section 5, “The Fundamental Theorem of
    Arithmetic,” on pages 12 - 15.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**3.3.2.3 The Quotient-Remainder Theorem** <span id="3.3.2.3"></span> 
-   **Reading: Link: Massachusetts Institute of Technology: Srini
    Devadas and Eric Lehman’s *Mathematics for Computer Science*:
    “Number Theory I”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Number Theory
    I”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NumberTheory1.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NumberTheory1-Srini-Devadas.epub)  
        
     Instructions: Read Section 1.2, which presents the Division theorem
    in its entirety on pages 2 - 5.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**Unit 3: Assessment 1** <span id="3.4"></span> 
-   **Assessment: Massachusetts Institute of Technology: Srini Devadas
    and Eric Lehman’s *Mathematics for Computer Science*: “Problem Set
    3”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Problem Set
    3”](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-3-Questions.pdf) (PDF)  
        
     Instructions: Solve problems 4 - 7. You can check your answers on
    the solutions guide
    [here](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-3-Solutions.pdf).
    (PDF)  
        
     Reading this selection and taking notes should take approximately 1
    hour.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**Unit 3: Assessment 2** <span id="3.5"></span> 
-   **Assessment: University of California, San Diego: Edward Bender and
    S. Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic,
    Logic and Numbers: Unit NT: Number Theory and Cryptography”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Arithmetic, Logic
    and Numbers: Unit NT: Number Theory and
    Cryptography”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-NT-Number-Theory-Edward-Bende-rand-S.-Gill-Williamson.epub)  
        
     Instructions: Complete the review questions at the end of the
    chapter on pages NT-26 - NT-28.  
        
     Reading this selection and taking notes should take approximately 1
    hour.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.


