---
layout: default
title: "CS202: Discrete Structures"
course_description: "An introduction to the mathematical foundations from discrete mathematics that are used for analyzing computer algorithms for correctness and performance. This course introduces models of computation, including finite state machines and Turing machines."
next: ../Unit08
previous: ../Unit06
---
**Unit 7: Recursion** <span id="7"></span> 
*In previous sections, we learned about sequences in a general sense. In
this unit, we will take a look at a specific type known as a recursive
sequence. The unit will first present a number of examples that
demonstrate how one computes the terms of a recursive sequence and
analyzes certain kinds of problems recursively in order to generate a
general recursive sequence. We will then learn to use the proof method
of induction to prove the validity or falsity of a recursive
sequence.*  
    
 *In this unit, we are going to rely on the Bender and Williamson
reference as primary. Use the Devadas and Lehman reference as
supplementary. Switching primary references exposes us to some
differences in notation and perspective.*

**Unit 7 Time Advisory**  
This unit should take you 9 hours to complete.  
  
 ☐    Subunit 7.1: 1.75 hours  
  
 ☐    Subunit 7.2: 2.75 hours  
  
 ☐    Subunit 7.3: 1.5 hours  
  
 ☐    Assessment 1: 1.5 hours  
  
 ☐    Assessment 2: 1.5 hours

**Unit7 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:  
-   compute recursively defined sequences;  
      
-   solve recursive relations; and  
      
-   explain important recursive functions, including McCarthy’s 91 and
    Ackermann.

**7.1 Recursively Defined Sequences** <span id="7.1"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Lists, Decisions
    and Graphs: Unit DT: Decision Trees and Recursion”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Lists, Decisions
    and Graphs: Unit DT: Decision Trees and
    Recursion”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Decision-Trees-and-Recursion-DT-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Decision-Trees-and-Recursion-DT-Edward-Bender.epub)  
        
     Instructions: Read Section 4, “Recursion Equations,” up to example
    27 on pages DT-42 - DT-46.  
        
     Notice that the definition of induction, in “Unit IS: Induction,
    Sequences and Series,” is in terms of A(n), an assertion dependent
    on n. The A(n), n = 1, ..., n, ... is a sequence. In induction,
    A(n-1) is used to prove A(n). If A(n) is defined using A(n - 1), the
    sequence is recursively defined. Thus, induction and recursion both
    exploit a relationship between A(n) and A(n-1).  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.  
        
     *Note: This reading also applies to subunits 7.1.1 -* *7.1.4.*

**7.1.1 Computing Terms of a Recursively Defined Sequence** <span
id="7.1.1"></span> 
*Note: Given a recursive relation, the terms of its recursively defined
sequence are computed by evaluating the relation for the base value, say
n = 1, then evaluating it for successive values of n. *

**7.1.2 Sequences that Satisfy the Same Recurrence Relation** <span
id="7.1.2"></span> 
*Note: Given a recursive equation, also called a recursive relation,
Theorem 7 on page DT-43 of the reading in Subunit 7.1 tells us how to
verify a solution for it.*

**7.1.3 Converting Sequences with Explicit Formulas to Recurrence
(Recursive) Relation** <span id="7.1.3"></span> 
*Note: Let f(n) be an explicit formula for the nth term, A<sub>n</sub>,
of a sequence and assume that f(n) = A b<sup>n</sup> + K = A
b<sup>n</sup> + K + Kb - Kb = A b<sup>n</sup> + Kb + K - Kb = b (A
b<sup>n-1</sup> + K) + K ( 1 - b) = b f(n - 1) + K(1 - b). Thus, f(n) =
b f(n - 1) + C, a recursive equation, i.e. relation.*

**7.1.4 The Towers of Hanoi and the Fibonacci Numbers** <span
id="7.1.4"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Lists, Decisions,
    and Graphs: Unit DT: Decision Trees and Recursion”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Lists, Decisions,
    and Graphs: Unit DT: Decision Trees and
    Recursions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Decision-Trees-and-Recursion-DT-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Decision-Trees-and-Recursion-DT-Edward-Bender.epub)  
        
     Instructions: The examples listed here illustrate the concepts in
    Subunit 7.1.3 and are examples of recursion. For the Fibonacci
    numbers, see theorem 9 and example 29 on pages DT-48 - DT-49.
    Example 29 starts with the sequence, F<sub>0</sub> = F<sub>1</sub> =
    1, F<sub>k</sub> = F<sub>k\\ -1</sub> + F<sub>k\\ -2</sub>, and
    develops a formula for F<sub>n</sub> which does not utilize an
    earlier F in the sequence.  
        
     For the Towers of Hanoi problem, see example 11 on pages DT-18 -
    DT-19.  
     This example solves a famous puzzle with a recursive solution,
    namely a solution for n discs in terms of a solution for n-1 and 1
    discs.  
        
     Reading this selection and taking notes should take approximately 1
    hour and 15 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Recurrences”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:*
    [“Recurrences”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Recurrences-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Recurrences-Srini-Devadas.epub)  
      
     Instructions: This reading presents an alternative illustration of
    the use of a recursive equation to solve the Tower of Hanoi problem.
    Read Section 1 on pages 1 - 5.  

       
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**7.2 Solving Recurrence Relations** <span id="7.2"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Lists, Decisions
    and Graphs: Unit DT: Decision Trees and Recursion”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Lists, Decisions
    and Graphs: Unit DT: Decision Trees and
    Recursion”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Decision-Trees-and-Recursion-DT-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Decision-Trees-and-Recursion-DT-Edward-Bender.epub)  
        
     Instructions: Read from example 27 to the end of the chapter on
    pages DT-46 - DT-50  
        
     A solution to a recursive equation is a formula that computes A(n)
    without having to compute A(k), for k \< n. Review the section on
    “Recursive Equations,” on page DT-44 up to example 26 on page
    DT-46.  
        
     1. A solution to a recursive equation can be found by inspection of
    the terms of a given sequence (example 27); OR  
     2. Apply theorem 8 if A(n) depends on A(n - 1) and theorem 9, if
    A(n) depends on A(n - 1) and A(n - 2).  
        
     Reading this selection and taking notes should take approximately 1
    hour and 15 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.  
      
     *Note: This reading also applies to Subunits 7.2.1 and 7.2.2.*

**7.2.1 Using the Method of Iteration** <span id="7.2.1"></span> 
*Note: We have seen in subunit 4.5 that mathematical induction and
recursion are related. Likewise, recursion is related to iteration, as
you will notice in Subunits 7.2.1.1 and 7.2.1.2. *

**7.2.1.1 Finding a Formula for a Recurrence Relation for an Arithmetic
Sequence** <span id="7.2.1.1"></span> 
*Regarding Theorem 8 on page DT-48 of the reading in Subunit 7.2, if*
*a<sup>n</sup> = ba<sup>n\\ -\\ 1</sup> +c ,* *then iterating,
a<sup>n</sup> = b( ba<sup>n\\ -\\ 2</sup>+c) + c = b(b (b
a<sup>n\\ -\\ 3</sup>+ c ) + c ) + c= ....= a<sub>0</sub>
b<sup>n</sup> + c b<sup>n-1</sup> + c b<sup>n-2</sup> + .... + c. This
is an example of 7.2.1.1 using the method of iteration for finding a
formula for a recurrence relation for an arithmetic sequence.*

**7.2.1.2 Finding a Formula for an Iterative Relation for a Geometric
Sequence** <span id="7.2.1.2"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Lists, Decisions
    and Graphs: Unit DT: Decision Trees and Recursion”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Lists, Decisions
    and Graphs: Unit DT: Decision Trees and
    Recursion”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Decision-Trees-and-Recursion-DT-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Decision-Trees-and-Recursion-DT-Edward-Bender.epub)  
        
     Instructions: A simple example of going from an iterative relation
    to a formula is as follows: given the iterative relation,
    *a<sub>n</sub> = ar<sup>n</sup> , ar<sup>n,</sup> = r a r
    <sup>n-1</sup> = r a <sub>n\\ -\\ 1</sub>, .* Continuing in this
    manner, we get the formula, *a<sub>n</sub> = r<sup>n</sup>
    a<sub>0</sub>*.  
        
     For another example, read over Exercise 4.7 on page DT-51. It
    discusses going from an iterative sequence to a recursive
    solution/equation, and vice versa, from the recursive equation to an
    iterative sequence.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

-   **Reading: Massachusetts Institute of Technology: : Srini Devadas
    and Eric Lehman’s *Mathematics for Computer Science*: “Sums and
    Approximations”**
    Link: Massachusetts Institute of Technology: : Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science:* [“Sums and
    Approximations”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Summations.pdf) (PDF)  
      
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Summations-Srini-Devadas.epub)  
      
     Instructions: Note that you have already read this lecture in
    Subunit 4.2. Focus on re-reading Section 1.2 on page 3, which finds
    a formula not for the terms of the sequence, but for the sum of the
    terms of the sequence.  
      
     Reading this selection and taking notes should take approximately
    15 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology:
    OpenCourseWare. The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**7.2.2 Using Mathematical Induction** <span id="7.2.2"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: Lists, Decisions
    and Graphs: “Unit DT: Decision Trees and Recursion”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Lists, Decisions
    and Graphs: Unit DT: Decision Trees and
    Recursion”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Decision-Trees-and-Recursion-DT-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Decision-Trees-and-Recursion-DT-Edward-Bender.epub)  
        
     Instructions: Read Section 4 on pages DT-42 to DT-44 up to
    “Recursion Equations.” Note that mathematical induction and
    recursion are closely related concepts.  
        
     Reading this selection and taking notes should take approximately
    45 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**7.3 Recursive Functions** <span id="7.3"></span> 
*Note: Many well-know functions are defined recursively. Several such
functions are presented in the next few subunits.*

**7.3.1 McCarthy’s 91 Function** <span id="7.3.1"></span> 
-   **Reading: Wikipedia: “McCarthy 91 Function”**
    Link: Wikipedia: [“McCarthy 91
    Function”](http://www.saylor.org/site/wp-content/uploads/2011/06/McCarthy-91-Function.pdf) (PDF)  
      
     Instructions: Read the Wikipedia article for a description of the
    McCarthy 91 function, an example of a recursive function used in
    computer science as a test case for the performance of formal
    verification techniques and methods.  
      
     Reading this selection and taking notes should take approximately
    30 minutes.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/). You can find
    the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/McCarthy_91_function).

**7.3.2 The Ackermann Function** <span id="7.3.2"></span> 
-   **Reading: Wikipedia: “Ackermann Function”**
    Link: Wikipedia: [“Ackermann
    Function”](http://www.saylor.org/site/wp-content/uploads/2011/06/Ackermann-Function.pdf) (PDF)  
        
     Instructions: Read the Wikipedia article for a description of the
    Ackermann function, an example of a recursive function that grows
    very rapidly.  
        
     Reading this selection and taking notes should take approximately 1
    hour.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/). You can find
    the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Ackermann_Function).

**Unit 7: Assessment 1** <span id="7.4"></span> 
-   **Assessment: Massachusetts Institute of Technology: Srini Devadas
    and Eric Lehman’s *Mathematics for Computer Science*: “Problem Set
    6”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Problem Set
    6”](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-6-Questions.pdf) (PDF)  
        
     Instructions: Try to work through problems 1, 5, 6, and 8. You can
    check your answers on the solutions guide
    [here](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-6-Solutions.pdf).  
        
     Completing this assessment should take approximately 1 hour and 30
    minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**Unit 7: Assessment 2** <span id="7.5"></span> 
-   **Assessment: University of California, San Diego: Edward Bender and
    S. Williamson’s *Lectures in Discrete Mathematics*: “Lists,
    Decisions and Graphs: Unit DT: Decision Trees and Recursion”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Lists, Decisions
    and Graphs: Unit DT: Decision Trees and
    Recursion”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Decision-Trees-and-Recursion-DT-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Decision-Trees-and-Recursion-DT-Edward-Bender.epub)  
        
     Instructions: Complete the review questions at the end of the
    chapter, numbers 1 - 16 on pages DT-53 and DT-54.  
        
     Completing this assessment should take approximately 1 hour and 30
    minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.


