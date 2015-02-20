---
layout: default
title: "CS202: Discrete Structures"
course_description: "An introduction to the mathematical foundations from discrete mathematics that are used for analyzing computer algorithms for correctness and performance. This course introduces models of computation, including finite state machines and Turing machines."
next: ../Unit05
previous: ../Unit03
---
**Unit 4: Mathematical Induction and Introduction to Sequences** <span
id="4"></span> 
*In the field of computer science, we are often required to prove the
correctness of an algorithm. Mathematics has a variety of methods in
order to do just that, one of which is known as mathematical induction.
In this unit, we will learn to use induction in order to determine
whether mathematical sequences are valid or invalid. This lesson is
extremely important, because mathematical sequences are the basis for
the study of repeated processes.*  
    
 *This unit will present induction first in an abstract form and then
through specialized proofs of sequences. We will examine mechanisms for
finding the general formula for a sequence and apply mathematical
induction to prove a given formula’s validity.*

**Unit 4 Time Advisory**  
This unit should take you 23 hours to complete.  
  
 ☐    Subunit 4.1: 3 hours  
  
 ☐    Subunit 4.2: 5.5 hours  
  
         ☐    Subunit-wide Reading: 3 hours  
  
         ☐    Subunit 4.2.1: 2 hours  
  
         ☐    Subunit 4.2.2: 0.5 hours  
  
 ☐    Subunit 4.3: 2 hours  
  
 ☐    Subunit 4.4: 2 hours  
  
 ☐    Subunit 4.5: 4.5 hours  
  
 ☐    Subunit 4.6: 1 hour  
  
 ☐    Assignment 1: 3 hours  
  
 ☐    Assessment 2: 2 hours

**Unit4 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:
-   analyze sequences and series, which use summation, product, and
    factorial operations;
-   write the terms of a sequence as a generalized formula;
-   use mathematical induction to prove the validity of a series; and
-   apply sequences, series, and induction to repeated processes.

**4.1 Sequences** <span id="4.1"></span> 
*Note: Sequences of numbers often arise in the applications of
mathematics. Sometimes a sequence is defined using a formula; sometimes
a sequence is defined by just listing the terms of the sequence in
order. *

**4.1.1 Finding Terms of Sequences Given by Explicit Formula** <span
id="4.1.1"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit IS: Induction, Sequences, and Series”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit IS: Induction, Sequences, and
    Series”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.epub)  
        
     Instructions: Read Section 2, “Sequences” on pages IS-12 - IS-19.
    In addition, read the examples mentioned below. This reading also
    applies to subunits 4.1.2 and 4.1.3.  
        
     See the definition of alternating sequence, immediately before
    example 14. Please pay particular attention to examples 7, 14
    (optional), and 17 for information specific to the topics in
    subunits 4.1.2 and 4.1.3. Given a sequence, f(k), f(k + 1), f(k +
    2), f(k + 3), ..., where k is a fixed integer, we may be able to
    determine a general expression for each term of this sequence. The
    general expression will have the form f(n), where n is a variable
    that takes on values from the set {n, n \> k}. If we can determine
    the form for f, we write f(n)n \>= k. See the exercises for section
    2 for examples.  
        
     Reading this selection and taking notes should take approximately 3
    hours.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**4.1.2 An Alternating Sequence** <span id="4.1.2"></span> 
*Note: This topic is covered by the reading in Subunit 4.1.1. If one
takes the first term of a sequence, then the sum of the first two terms,
then the sum of the first three terms, and so on, the result is a new
sequence, called a series. Alternating series are defined on page IS-24
of the Bender and Williamson reading above. An alternating sequence is
defined just like an alternating series; namely, the signs of the
adjacent terms of the sequence alternate in their signs. *

**4.1.3 Finding an Explicit Formula to Fit Given Initial Terms** <span
id="4.1.3"></span> 
*Note: The problem of finding an explicit formula for a sequence or
series is, in general, a hard problem. In some cases, there might not
even exist such a formula.  
    
 Finding an explicit formula pertains to three situations:  
 1.    Given a sequence of numbers, find a general formula for the nth
term of the sequence that depends on the n-1 term.  
 2.    Given a sequence of numbers, find a general formula for the nth
term of the sequence that depends on n.  
 3.    Given a sequence of numbers, find a general formula for the nth
term of the sequence that depends on one or more of the preceding
terms.  
    
 If the sequence has certain properties - such as the ability of each
term to be calculated from the preceding term - as in an arithmetic
sequence (where a fixed number is added to the n-1 term to obtain the
nth term), or a geometric sequence (where a fixed number is used to
multiply the n-1 term, to obtain the nth term), then one could use that
information to deduce a formula for each term. Thus, one makes
assumptions about the relationship of the n-1 term and the nth term. Or,
if one is given a formula for each term that depends on that term, one
could deduce a formula for the nth term.  
    
 Examples 7 and 17 of the reading in Subunit 4.1.1 touch on this
topic.  
 An example for the third situation above is that of the Fibonacci
series - f(n) = n + (n-1) and f(0) = 0, f(1) = 1.  (Note: Fibonacci
numbers also appear in Section 7.1.4 below).Chapter 1, Section 2 and
Chapter 2, Section 2 in the reading in Subunit 4.2 below touch on this
topic for series. *

**4.2 Summation** <span id="4.2"></span> 
-   **Reading: MIT: Srini Devadas and Eric Lehman’s *Mathematics for
    Computer Science*: “Sums and Approximations”**
    Link: MIT: Srini Devadas and Eric Lehman’s *Mathematics for Computer
    Science:* [“Sums and
    Approximations”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Summations.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Summations-Srini-Devadas.epub)  
        
     Instructions: Read this lecture. Take your time to understand the
    transition from one step to the next in the proofs. This can be time
    consuming, but it is rewarding. Don’t let the topic of the
    examples - annuities, for example - distract you. The domains (e.g.
    annuities, Taylor series, etc.) are important, but so is the method
    they illustrate. The method is more general than the specific domain
    of the example.  
        
     The reading mentions induction as a way of proving some of the
    expressions and then continues to give insight into the source of
    the expression. We will cover induction in Subunit 4.5 of this
    course.  
        
     Reading this selection and taking notes should take approximately 3
    hours.   
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: MIT OpenCourseWare. The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).  
      
     *Note: This reading applies to Sections 4.2.1, 4.2.2, and 4.3.2
    below.*

**4.2.1 Computing Summations** <span id="4.2.1"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit IS: Induction, Sequence, and Series”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit IS: Induction, Sequence, and
    Series”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.epub)  
        
     Instructions: Read Section 3 on pages 20 - 30.  
        
     For sequences, given a summation ∑n \> = k (f(n), we can expand it
    to the series, f(k), f(k) + f(k + 1), f(k) + f(k + 1) + f(k + 2),
    .... Given the series, f(k), f(k) + f(k + 1), f(k) + f(k + 1) +
    f(k + 2), f(k) + f(k + 1) + f(k + 2) + f(k + 3), ..., we can write
    it as ∑n \>= k f(n).  
        
     Reading this selection and taking notes should take approximately 2
    hours.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**4.2.2 Properties of Summation** <span id="4.2.2"></span> 
-   **Reading: The Saylor Foundation’s “Summation Properties”**
    Link: The Saylor Foundation’s [“Summation
    Properties”](http://www.saylor.org/site/wp-content/uploads/2011/06/CS202-Subunit-4.2.4-Summation_FINAL.pdf) (PDF)  
        
     Instructions: Read this brief note on summation.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.

**4.3 Products** <span id="4.3"></span> 
*Note: As for summation, we will now look at products, calculating them
and their properties. *

**4.3.1 Product Notation** <span id="4.3.1"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit IS: Induction, Sequence and Series”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Arithmetic, Logic
    and Numbers: Unit IS: Induction, Sequence and
    Series”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.epub)  
        
     Instructions: Read Section 1 on pages 1 - 11. ∏ is the symbol for
    product. If p<sub>1</sub> , p<sub>2,</sub> ... , p<sub>k\\ ...</sub>
    is a sequence, the series p<sub>1</sub> , p<sub>1</sub>
    p<sub>2</sub> , p<sub>1</sub> p<sub>2</sub> p<sub>3</sub> ,
    p<sub>1</sub> p<sub>2\\ ,</sub> ... , p<sub>k</sub> is written ∏
    p<sub>1</sub> p<sub>2</sub> ... p<sub>k</sub>. If you look over the
    exercises for section 1, you will see that this reading applies to ∏
    examples as well as ∑ examples. This reading also applies to topics
    in Subunit 4.3.2.  
        
     Reading this selection and taking notes should take approximately 1
    hour.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**4.3.2 Computing Products** <span id="4.3.2"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Sums and
    Approximations”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Sums and
    Approximations”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Summations.pdf) (PDF)
       
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Summations-Srini-Devadas.epub)  
        
     Instructions: Study Section 3.4 “Approximating 1 + x.”  
        
     Product computation is similar to the evaluation of the product of
    numbers in arithmetic. Product or multiplication is a binary
    operation that is commutative [i.e. a times b = a b = b a];
    associative [i.e. (a b) c = a (b c)]; and has an identity (i.e. a
    times 1 = 1). In addition, there are some tricks that can be used.  
        
     Some simple properties of products are:  
     1. a ∏ pi = ∏ a pi, where the ∏ ranges over a set of positive
    integers i.  
     2. ∏ pi ∏ qij = ∏ pi qj, where the product symbols varies over
    ranges for i and j.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit IS: Induction, Sequence and Series”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit IS: Induction, Sequence and
    Series”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.epub)  
        
     Instructions: Read Theorem 11 and example 17 on pages IS-27 through
    IS-30. In doing calculation involving series, we work with sums
    (since a series is the sum of the succeeding terms of a sequence).
    In working these calculations, we also encounter the product of
    terms, for example when determining whether a series is bounded.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**4.4 Factorial Notation** <span id="4.4"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Sums,
    Approximations, and Asymptotics II”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science: *[“Sums, Approximations,
    and Asymptotics
    II”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Approximations-Asymptotics.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Approximations-Asymptotics-Srini-Devadas.epub)  
        
     Instructions: Read Section 2 “The Factorial Function.” The reading
    also applies to the Subunit 4.4.1 and Subunit 4.4.2. In reading for
    Subunit 4.4.2, below, see the binomial theorem and its
    generalization to the multinomial theorem.  
        
     Reading this selection and taking notes should take approximately 1
    hour.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**4.4.1 The First Ten Factorials** <span id="4.4.1"></span> 
*Note the first ten factorials: 10! 9! 8! 7! 6! 5! 4! 3! 2! 1! =
10<sup>1</sup> x 9<sup>2</sup> x 8<sup>3</sup> x 7<sup>4</sup> x
6<sup>5</sup> x 5<sup>6</sup> x 4<sup>7</sup> x 3<sup>8</sup> x
2<sup>9</sup> x 1<sup>10</sup>. *

**4.4.2 Computing with Factorials** <span id="4.4.2"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Counting II” and
    “Counting III”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science*: [“Counting
    II”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting2-Srini-Devadas.pdf) (PDF)
    and [“Counting
    III”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting3-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting2-Srini-Devadas.epub) (Counting
    II)  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting3-Srini-Devadas.epub) (Counting
    III)  
        
     Instructions: In “Counting II,” read Section 1.3, “Permutations.”
    In “Counting III,” read Section 1.3, “Combinations” and Section 2,
    “Binomial Theorem.”  
        
     Reading this selection and taking notes should take approximately 1
    hour.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**4.5 Mathematical Induction** <span id="4.5"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Induction I”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science*: [“Induction
    I”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction1.pdf) (PDF)
       
      
     Instructions: You have encountered mathematical induction in some
    of the previous readings in this course. Read Sections 1 and 2 on
    pages 1 - 4. This reading also applies to Subunits 4.5.1, 4.5.2, and
    4.5.4 below. As you read about induction in the references, note
    that induction has a relationship to recursion.  
        
     Reading this selection and taking notes should take approximately 1
    hour.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: MIT OpenCourseWare. The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Induction III”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science*: [“Induction
    III”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction3-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction3-Srini-Devadas.epub)  
        
     Instructions: Read Section 2 on pages 2 - 5 and Section 4 on pages
    8 - 12. These readings give helpful guidance in correct use of
    induction.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**4.5.1 Application of Principle of Mathematical Induction** <span
id="4.5.1"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit IS: Induction, Sequence, and Series”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit IS: Induction, Sequence and
    Series”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.epub)  
        
     Instructions: Study the applications of induction in Section 1 on
    pages IS-1 through IS-8.  
        
     This reading is a good formal review. Again, the presentation
    relies on a lot of examples. Don’t forget to look over the exercises
    at the end of the section. Some of these examples will be utilized
    in following subunits.  
        
     Reading this selection and taking notes should take approximately 1
    hour.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**4.5.2 Proof by Induction of the Sum of First n Integers** <span
id="4.5.2"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit IS: Induction, Sequence, and Series”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit IS: Induction, Sequence, and
    Series”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.epub)  
      
     Instructions: Read Section 1, example 2 on page IS-2.   
      
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**4.5.3 Proof by Induction of the Sum of a Geometric Sequence** <span
id="4.5.3"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit IS: Induction, Sequence and Series”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit IS: Induction, Sequence and
    Series”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.epub)  
        
     Instructions: Read Theorem 2 on pages 5 - 7, example 11 on page 22,
    and example 12 on page 23. Some of the examples are more difficult,
    but hard examples push our understanding and expand our skill.   
      
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**4.5.4 Proving Divisibility by Induction** <span id="4.5.4"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Induction I”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science*: [“Induction
    I”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction1.pdf) (PDF)  
      
     Instructions: Read Section 3 and Section 4 on pages 5 - 7.   
      
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**4.5.5 Proving an Inequality by Induction** <span id="4.5.5"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit IS: Induction, Sequence, and Series”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit IS: Induction, Sequence, and
    Series”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.epub)  
        
     Instructions: Read example 4 on pages 3 and 4.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**4.6 Loop Invariants** <span id="4.6"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Induction III”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science*: [“Induction
    III”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction3-Srini-Devadas.pdf) (PDF)
       
      
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction3-Srini-Devadas.epub)  
        
     Instructions: Read Section 3.2. The reading presents a proof that
    an initial configuration of the 9-number puzzle cannot be
    transformed into its inverse. The proof uses the fact that after
    each move the number of inversions remains even; this is an
    invariant. Invariants are used in proofs and in proving the
    correctness of programs.  
        
     Invariants are only introduced in this course; they are covered in
    detail in programming language courses.   
      
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

-   **Reading: The Saylor Foundation’s “Loop Invariants”**
    Link: The Saylor Foundation’s [“Loop
    Invariants”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS-202-Subunit-4.6-Loop-Invariants_FINAL.pdf) (PDF)  
      
     Instructions: Review this article for more information on
    invariants. This reading also applies to Subunits 4.6.1 - 4.6.4,
    where more detail is given about the four components of a loop
    invariant.  
      
     Reading this selection and taking notes should take approximately
    30 minutes.

**4.6.1 Basis Property** <span id="4.6.1"></span> 
*Note: The reading “Loop Invariants” in subunit 4.6defines the four
components of a loop invariant. The first of these is the basis
property, which is the start condition for performing the statements of
the loop. The basis property is the value of an expression that is true
before performing the statements of a loop.*

**4.6.2 Inductive Property** <span id="4.6.2"></span> 
*Note: The inductive property is the key property of a loop invariant.
If the statements of the loop are performed, the basis property is still
true after performing the statements of the loop.*

**4.6.3 Eventual Falsity of Guard** <span id="4.6.3"></span> 
*Note: The eventual falsity of the guard is necessary to stop the loop
so that it is not performed continuously, i.e. an infinite loop.*

**4.6.4 Correctness of the Post-Condition** <span id="4.6.4"></span> 
*Note: The fourth property of a loop invariant is the correctness of the
post-condition − the value of the base expression when the guard is
false, i.e. when the loop terminates. *

**Unit 4: Assessment 1** <span id="4.7"></span> 
-   **Assessment: Massachusetts Institute of Technology: Srini Devadas
    and Eric Lehman’s *Mathematics for Computer Science*: “Problem Set
    2” and “Problem Set 3”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science: *[“Problem Set
    2”](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-2-Questions.pdf) and
    [“Problem Set
    3”](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-3-Questions.pdf) (PDF)
       
      
     Instructions: Solve problems 1 - 4 in “Problem Set 2”; complete
    problems 1 and 3 in “Problem Set 3.” You can check your solutions
    for “Problem Set 2”
    [here](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-2-Solutions.pdf) and
    for “Problem Set 3”
    [here](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-3-Solutions.pdf).  
        
     Completing this assessment should take approximately 3 hours.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of TechnologyOpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**Unit 4: Assessment 2** <span id="4.8"></span> 
-   **Assessment: University of California, San Diego: Edward Bender and
    S. Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic,
    Logic, and Numbers: Unit IS: Induction, Sequence, and Series”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Arithmetic,
    Logic, and Numbers: Unit IS: Induction, Sequence, and
    Series”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Induction-Sequences-Series-Edward-Bender.epub)  
        
     Instructions: Complete the multiple-choice review questions are at
    the end of the unit on pages IS-31 - IS-33.  
        
     Completing this assessment should take approximately 2 hours.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.


