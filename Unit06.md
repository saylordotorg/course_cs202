**Unit 6: Introduction to Counting and Probability** <span
id="6"></span> 
*Counting is not always as easy as it sounds. Say, for example, you are
asked to arrange three balls of three different colors. What are the
possibilities? What if two of them have the same color? This is an
example of a set of problems known as “counting problems.” In this unit,
we will learn different types of counting using possibility trees and
general counting theorems. Once we understand the concepts of counting,
we will discuss the probability of event occurrence, which refers to the
likelihood that a certain outcome for a given problem set will occur.
Events can be dependent or independent, making them subject to different
sets of rules. Throughout the unit, we will relate counting and
probability to computer science topics such as counting list and array
elements, password computation, and brute force attacks.*  
    
 *In this unit, we are going to rely on the Devadas and Lehman reference
as primary. Use the Bender and Williamson reference as a supplement.*

**Unit 6 Time Advisory**  
This unit should take you 15.25 hours to complete.  
  
 ☐    Subunit 6.1: 2.15 hours  
  
 ☐    Subunit 6.2: 2.75 hours  
  
 ☐    Subunit 6.3: 2.25 hours  
  
 ☐    Subunit 6.4: 5.25 hours  
  
         ☐    Subunit-wide Reading:1.75 hours  
  
         ☐    Subunit 6.4.1: 1.5 hours  
  
         ☐    Subunit 6.4.2: 0.75 hours  
  
         ☐    Subunit 6.4.3: 1.25 hours  
  
 ☐    Assignment 1: 1.5 hours  
  
 ☐    Assessment 2: 1.5 hours

**Unit6 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:
-   solve counting problems;
-   compute the number of permutations and combinations;
-   compute conditional probabilities; and
-   compute the probability of independent events.

**6.1 Definitions and Basic Counting** <span id="6.1"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Introduction to
    Probability”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science*: [“Introduction to
    Probability”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Probability-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Probability-Srini-Devadas.epub)  
        
     Instructions: Read from the Introduction to Probability through
    Section 1.2. This reading motivates our study of probability and
    also counting - because counting often comes up in the analysis of
    problems that we solve using probability.  
        
     Reading this selection and taking notes should take approximately
    15 minutes to complete.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**6.1.1 What Is a Sample Space?** <span id="6.1.1"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Introduction to
    Probability”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science*: [“Introduction to
    Probability”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Probability-Srini-Devadas.pdf) (PDF)
       
      
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Probability-Srini-Devadas.epub)  
      
     Instructions: Read Section 1.3 on pages 3 - 5. The previous reading
    introduced a four-step process for building a probabilistic model to
    analyze and solve problems using probability. This reading discusses
    the first step.  
      
     Reading this selection and taking notes should take approximately
    15 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**6.1.2 What Is an Event?** <span id="6.1.2"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Introduction to
    Probability”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science*: [“Introduction to
    Probability”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Probability-Srini-Devadas.pdf) (PDF)
       
      
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Probability-Srini-Devadas.epub)  
      
     Instructions: Read Section 1.4 on pages 5 - 6. This reading
    discusses the second step of the four-step process for building a
    probabilistic model for solving probability problems.   
      
     Reading this selection and taking notes should take approximately
    15 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**6.1.3 Equally Likely Probability Formula** <span id="6.1.3"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Introduction to
    Probability”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science*: [“Introduction to
    Probability”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Probability-Srini-Devadas.pdf) (PDF)
       
      
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Probability-Srini-Devadas.epub)  
      
     Instructions: Read Section 1.5 and Section 1.6 on pages 6 - 9. This
    reading discusses the third and fourth steps of the four-step
    process for building a probabilistic model for solving probability
    problems. In the third step, probabilities are assigned using the
    possibility tree drawn during steps one and two. In step three,
    probabilities are assigned to the edges of the tree. At each level
    of the tree, the branches of a node represent possible outcomes for
    that node. If the outcomes of a node are assigned the same
    probability (the outcomes of a node add to 1), we say that they
    represent equally likely outcomes.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**6.1.4 Counting Elements of Lists and Sublists** <span
id="6.1.4"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Counting I”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Counting
    I”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting-1.pdf) (PDF)  
      
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting-1-Srini-Devadas.epub)  
      
     Instructions: Read “Counting I” through Section 1.4. It presents
    some strategies and rules that aid us in counting members of sets
    arising in the analysis of probability problems.  
        
     This reading also applies to Subunit 6.1.5 below.  
      
     Reading this selection and taking notes should take approximately 1
    hour.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**6.1.5 Counting Elements of a One-Dimensional Array** <span
id="6.1.5"></span> 
*Note: Section 1.3 of the reading for Subunit 6.1.4 illustrates the
bijection rule for arrays and lists. The bijection rule can be applied
to counting the elements of an array. The elements of a list can be
mapped via a bijection to a one-dimensional array. Thus, because we can
count the elements of a list, we can count the elements of such an
array.* *(We count the elements of a list, by walking down the list and
incrementing a tally, initialized to zero, by one for each item of the
list.)*

**6.2 Possibility Trees and Advanced Counting** <span id="6.2"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Counting I”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Counting
    I”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting-1.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting-1-Srini-Devadas.epub)  
      
     Instructions: You have read this selection in Subunit 6.1.4 above.
    Each of the analyses discussed in “Counting I” can be illustrated by
    drawing a tree. Take another look at Section 2.1 and Section 2.2 of
    the readings on the sum rule and the product rule. These will be
    covered in a subunit below but are mentioned here to explain what a
    possibility tree is. If you illustrate these rules by drawing a
    tree, it will depict all the elements of a union of disjoint sets
    (sum rule) and of the product of sets (multiplication rule). If
    these sets represent outcomes for events, then the tree is called a
    possibility tree.  
      
     Reading this selection and taking notes should take approximately
    15 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology 
    OpenCourseWare. The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**6.2.1 Possibility Trees and the Multiplication Rule** <span
id="6.2.1"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Introduction to
    Probability”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science: *[“Introduction to
    Probability”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Probability-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Probability-Srini-Devadas.epub)  
        
     Instructions: Read up to Section 1.3. Look at the line drawings
    beginning in Section 1.3 and in following sections; these are
    possibility trees. Realize that they are just representations of
    functions used in modeling a problem. Note the modeling advice and
    steps 1 - 4 on pages 1 - 9.  
        
     *Multiplication*often applies to each level of the tree, i.e. each
    node at level 1 is expanded (multiplied) by the same number of
    branches at level 2, and so on, for each level. If the outcomes of
    an event for a probability problem are modeled using a tree is
    called a possibility tree.  
        
     Reading this selection and taking notes should take approximately
    45 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**6.2.2 Permutation** <span id="6.2.2"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Introduction to
    Probability”**
    Link: Massachusetts Institute of Technology : Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science: *[“Introduction to
    Probability”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Probability-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Probability-Srini-Devadas.epub)  
        
     Instructions: Read Section 1.3 for the definition of a permutation,
    how to count permutations, and a reminder of Stirling’s formula,
    which approximates n!  
        
     Reading this selection and taking notes should take approximately
    15 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology 
    OpenCourseWare. The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**6.2.3 Counting Elements of Sets: Addition, Product, and Division
Rules** <span id="6.2.3"></span> 
-   **Reading: Massachusetts Institute of Technology : Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Counting I”**
    Link: Massachusetts Institute of Technology : Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Counting
    I”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting-1.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting-1-Srini-Devadas.epub)  
      
     Instructions: This topic was covered in Subunit 6.1. Revisit
    Section 2, “Two Basic Counting Rules,” of the reading to reinforce
    your understanding of the counting rules, focusing on 2.1: “The Sum
    Rule” and 2.2: “The Product Rule.”    
      
     Reading this selection and taking notes should take approximately
    15 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Counting II”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Counting
    II”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting2-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting2-Srini-Devadas.epub)  
        
     Instructions: Study “Counting II” from the beginning through
    Section 1.2; then study the division rule covered in Section 2.
    Lastly, study Section 3, which discusses counting elements of the
    union of sets, extending the addition rule: disjoint sets and, then,
    non-disjoint sets.  
        
     Reading this selection and taking notes should take approximately
    45 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**6.2.4 The Difference Rule** <span id="6.2.4"></span> 
*Note: The difference rule is as follows: the number of elements in B -
A equals (the number of elements in B) minus (the number of elements in
B intersect A). In symbols \# (B - A) = \# (B) - \# (B Ç A).*

**6.2.5 Combinations** <span id="6.2.5"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Counting III”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science: *[“Counting
    III”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting3-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting3-Srini-Devadas.epub)  
        
     Instructions: Read Section 1 on pages 1 - 3. Section 1.1 and
    Section 1.2 discuss counting sequences; Section 1.3 discusses
    counting combinations.  
        
     Reading this selection and taking notes should take approximately
    15 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**6.2.6 The Algebra of Combinations** <span id="6.2.6"></span> 
-   **Reading: The Saylor Foundation’s “Combinations”**
    Link: The Saylor Foundation’s
    [“Combinations”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS202-Subunit-6.2.6-Combinations_FINAL.pdf) (PDF)  
        
     Instructions: Read this article for more information on the algebra
    of combinations.  
        
     Reading this selection and taking notes should take approximately
    15 minutes.

**6.2.6.1 Pascal’s Triangle** <span id="6.2.6.1"></span> 
*Pascal’s triangle is a simple, manual way to calculate binomial
coefficients.*  
    
 *Note: In the previous Saylor reading, look at the table at the bottom
of the reading. The first column, (0,1,2,3,4,5), contains the numbers of
the rows - the 0th row, 1st row, 2nd row, etc. - and corresponds to the
exponent ‘n’ in (x + y)n .*    
  
 *Ignore the first column for the moment. Take the nth row and shift it
n spaces to the left, i.e. the 0th row is not shifted, the 1st row is
shifted 1 space to the left, the 2nd row is shifted 2 spaces to the
left, the 3rd row is shifted 3 spaces to the left, etc. This shifting
results in a shape of a triangle - ‘1’ is at the top of the triangle in
the 0th row, ‘1   1’ is next in the 1st row offset by one space (so that
the ‘1’ at the top is above the space in ‘1   1’), etc. This triangle
for n from 0 to 5 generalizes to any n and is called Pascal’s triangle.
These numbers are the coefficients for the binomial equation presented
in the following subunit.*

**6.2.6.2 The Binomial Theorem** <span id="6.2.6.2"></span> 
-   **Reading: Massachusetts Institute of Technology : Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Counting III”**
    Link: Massachusetts Institute of Technology : Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science: *[“Counting
    III”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting3-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting3-Srini-Devadas.epub)  
        
     Instructions: Read Section 2, which defines the binomial expansion
    expressed in the binomial theorem, that is, the expansion of (a +
    b)<sup>n</sup>. The binomial expansion is very important because it
    is used to make approximations in many domains, including the
    sciences, engineering, weather forecasting, economics, and
    polling.  
      
     The expansion of (a + b)n is a polynomial whose coefficients are
    the integers in the nth row of Pascal’s Triangle (see Subunit
    6.2.6.1 above).  
        
     Reading this selection and taking notes should take approximately
    15 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology 
    OpenCourseWare. The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**6.3 Probability Process** <span id="6.3"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Introduction to
    Probability”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Introduction to
    Probability”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Probability-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Probability-Srini-Devadas.epub)  
        
     Instructions: Read Section 2, which presents a four-step process
    for solving probability problems. This process incorporates basic
    probability axioms, albeit indirectly, as part of the process
    steps.  
        
     Reading this selection and taking notes should take approximately 1
    hour.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**6.3.1 Probability Axioms** <span id="6.3.1"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Lists, Decisions,
    and Graphs: Unit CL: Counting and
    Listing”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting-and-Listing-CL-Edward-Bender.pdf) (PDF)  
        
     Instructions: Read Section 4 on pages CL-28 through CL-30.  
        
     Some useful results are summarized here:

    -   ∑<sub>xε\\ S</sub> P(x) = 1, where S is the sample space, also
        written P(S) = 1;  
          
    -   P(x) \>=0, for x in the sample space;  
          
    -   Let E be an event, defined as a subset of S. P(E) =
        ∑<sub>xε\\ E</sub>P(x);  
          
    -   If E and D are events such that E is contained in D, then P(E)
        \<= P(D); and  
          
    -   P(E È D) = P(E) + P(D) for E, D disjoint.

    From the above the following can be proved: Let E be an event. E’ =
    S -E. P(E È E’) = P(E) + P(E’), P(S= E È E’) = 1; thus, 1 = P(E) +
    P(E’) and P(E’) = 1 - P(E).  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**6.3.2 The Probability of the Complement of an Event** <span
id="6.3.2"></span> 
*Note the probability of the complement of an event E is 1 -
(probability of E). This result is often very useful, because for some
problems the probability of E may be difficult to calculate, but the
probability of the complement of E may be easy to calculate.*

**6.3.3 The Probability of a General Union of Two Events** <span
id="6.3.3"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Conditional
    Probability”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Conditional
    Probability”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Conditional-Probability-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Conditional-Probability-Srini-Devadas.epub)  
        
     Instructions: Read Section 4, “Conditional Probability Pitfalls,”
    in particular, “Conditional Probability Theorem 2” and “Theorem 3”
    on page 12. This will serve as a lead-in to conditional probability,
    which is covered in the next section.  
        
     Reading this selection and taking notes should take approximately
    45 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**6.4 Conditional Probability and Independent Events** <span
id="6.4"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Introduction to
    Probability”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science: *[“Introduction to
    Probability”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Probability-Srini-Devadas.pdf) (PDF)  
      
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Probability-Srini-Devadas.epub)  
      
     Instructions: Focus on the modeling advice and steps 1 - 4 on pages
    1 - 9.  
      
     Reading this selection and taking notes should take approximately
    45 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Conditional
    Probability”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Conditional
    Probability”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Conditional-Probability-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Conditional-Probability-Srini-Devadas.epub)  
        
     Instructions: Read this lecture. Try to understand the concepts of
    conditional probability, and just scan the examples. We’ll take a
    closer look at the problems in the next section.  
        
     Reading this selection and taking notes should take approximately 1
    hour.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**6.4.1 Computing a Conditional Probability** <span id="6.4.1"></span> 
-   **Activity: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Conditional
    Probability”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    *Mathematics for Computer Science:* [“Conditional
    Probability”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Conditional-Probability-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Conditional-Probability-Srini-Devadas.epub)  
        
     Instructions: Work through the following examples in this lecture:

    -   Section 1, “The Halting Problem” (fictitious name of a hockey
        team) on page 2;  
          
    -   Section 2.1, “A Coin Problem” on page 6;  
          
    -   Section 2.2, “A Variant of the Two Coins Problem” on page 8;  
          
    -   Section 3, “Medical Testing” on page 9;  
          
    -   Section 4.1, “Carnival Dice” on page 11;  
          
    -   Section 4.3, “Discrimination Lawsuit” on page 14; and  
          
    -   Section 4.4, “On-Time Airlines” on page 15.

    Understanding the examples is critical to really understanding
    conditional probability.  
        
     Completing this activity should take approximately 1 hour and 30
    minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**6.4.2 Bayes’s Theorem** <span id="6.4.2"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Lists, Decisions,
    and Graphs: Unit DT: Decision Trees and Recursion”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Lists, Decisions,
    and Graphs: Unit DT: Decision Trees and
    Recursion”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Decision-Trees-and-Recursion-DT-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Decision-Trees-and-Recursion-DT-Edward-Bender.epub)  
        
     Instructions: Read Section 3 on pages DT-28 through DT-35.  
        
     Bayes’ theorem is a famous theorem for computing conditional
    probabilities. Assume E<sub>i</sub> are mutually exclusive events
    for i = 1,..., n and U<sub>i</sub> E<sub>i</sub> = D, for arbitrary
    event D, P(E<sub>i</sub> | D) = P(D | E<sub>i</sub> )
    P(E<sub>i</sub>) / [P(D|E<sub>1</sub>)P( E<sub>1</sub>) + ....+
    P(D|E<sub>n</sub>) P(E<sub>n</sub>)]. Statements of Bayes’ theorem
    are given on pages DT-28 and DT-32. Like the binomial theorem,
    Bayes’ theorem is very useful in calculating probabilities for many
    applications, for example, in diagnosis and in decision theory.  
        
     Reading this selection and taking notes should take approximately
    45 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**6.4.3 Computing the Probability of Independent Events** <span
id="6.4.3"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Independence”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science*:
    [“Independence”](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/lecture-notes/l19_prob_indep.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Independence-Srini-Devadas.epub)  
        
     Instructions: Read this lecture for practice with the probability
    of independent events.  
        
     Reading this selection and taking notes should take approximately 1
    hour and 15 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**Unit 6: Assessment 1** <span id="6.5"></span> 
-   **Assessment: Massachusetts Institute of Technology: Srini Devadas
    and Eric Lehman’s *Mathematics for Computer Science*: “Problem Set
    3,” “Problem Set 7,” and “Problem Set 8”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Problem Set
    3”](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-3-Questions.pdf),
    [“Problem Set
    7”](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-7-Questions.pdf),
    and [“Problem Set
    8”](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-8-Questions.pdf) (PDF)  
        
     Instructions: Work through Problem 2 in “Problem Set 3,” Problems
    2 - 5 in “Problem Set 7,” and Problem 3 in “Problem Set 8.” You can
    check your answers on the solutions guide for “Problem Set 3”
    [here](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-3-Solutions.pdf),
    “Problem Set 7”
    [here](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-7-Solutions.pdf),
    and “Problem Set 8”
    [here](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-8-Solutions.pdf).  
        
     Completing this assessment should take approximately 1 hour and 30
    minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**6.6 Unit 6: Assessment 2** <span id="6.6"></span> 
-   **Assessment: University of California, San Diego: Edward Bender and
    S. Williamson’s *Lectures in Discrete Mathematics*: “Lists,
    Decisions and Graphs: Unit CL: Counting and Listing” and “Unit DT:
    Decision Trees and Recursion”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Lists, Decisions
    and Graphs: Unit CL: Counting and
    Listing”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting-and-Listing-CL-Edward-Bender.pdf) (PDF)
    and [“Unit DT: Decision Trees and
    Recursion”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Decision-Trees-and-Recursion-DT-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Counting-and-Listing-CL-Edward-Bender.epub) (Counting
    and Listing)  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Decision-Trees-and-Recursion-DT-Edward-Bender.epub) (Decision
    Trees and Recursion)  
        
     Instructions: Complete the multiple-choice review questions are at
    the end of the unit on pages CL-41 - CL-44 in the “Counting and
    Listing” document. Then, complete review questions 17 - 23 on pages
    DT-55 - DT-57 in the “Decision Trees and Recursion” document.  
        
     Completing this assessment should take approximately 1 hour and 30
    minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.


