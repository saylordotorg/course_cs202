---
layout: default
title: "CS202: Discrete Structures"
course_description: "An introduction to the mathematical foundations from discrete mathematics that are used for analyzing computer algorithms for correctness and performance. This course introduces models of computation, including finite state machines and Turing machines."
next: ../Unit06
previous: ../Unit04
---
**Unit 5: Set Theory** <span id="5"></span> 
*Computer scientists often find themselves working with sets of
homogeneous or heterogeneous values. Scientists have devised set theory
in order to respond to these situations. In this unit, we will learn the
basics of set theory, taking a look at definitions and notations and
using the proof methods and counterexample means we introduced earlier
to establish set properties.*  
    
 *Set theory is a fundamental tool of mathematics and often used as the
starting point for its study and to define basic concepts, such as
functions, numbers, and limits.*

**Unit 5 Time Advisory**  
This unit should take you 15 hours to complete.  
  
 ☐    Subunit 5.1: 1.5 hours  
  
 ☐    Subunit 5.2: 4 hours  
  
 ☐    Subunit 5.3: 6.5 hours  
  
         ☐    Subunit-wide Reading: 1 hour  
  
         ☐    Subunit 5.3.1: 0.5 hours  
  
         ☐    Subunit 5.3.2: 0.5 hours  
  
         ☐    Subunit 5.3.3: 0.5 hours  
  
         ☐    Subunit 5.3.4: 0.5 hours  
  
         ☐    Subunit 5.3.5: 0.5 hours  
  
         ☐    Subunit 5.3.6: 0.5 hours  
  
         ☐    Subunit 5.3.7: 0.5 hours  
  
         ☐    Subunit 5.3.8: 0.5 hours  
  
         ☐    Subunit 5.3.9: 0.5 hours  
  
         ☐    Subunit 5.3.10: 0.5 hours  
  
         ☐    Subunit 5.3.11: 0.5 hours  
  
 ☐    Assignment 1: 1.5 hours  
  
 ☐    Assessment 2: 1.5 hours

**Unit5 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:
-   define sets, operations on sets, and prove important valid set
    properties, called set identities; and
-   apply the definitions and identities to prove set theoretic
    statements.

**5.1 Definition of Set Theory** <span id="5.1"></span> 
*Note: Set theory may seem strange until you get used to it. Then, it’s
so natural that you will often think in terms of sets -but this comes
with familiarity. So think carefully about the following material,
because it is VERY important.*

**5.1.1 Set Notation** <span id="5.1.1"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets, Equivalence
    and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
        
     Instructions: Study the notation used for sets in Section 1 on
    pages SF-1 to SF-2. This reading also applies to Subunits 5.1.2 and
    5.2.1 - 5.2.5.  
      
     A set is a collection of elements, called *members* of the set.
    Sets are denoted using capital letters; elements are denoted using
    small letters. We write a ∈A for an element of A; and a ÏA, for a
    not an element of A. Examples of sets can be found everywhere. All
    the units in this course comprise a set. The collection of people
    related to you comprises a set. Sets can be described using English
    descriptions, predicates in logic, or mathematical functions, in
    particular Boolean functions. A set can also be defined by listing
    the members of the set. A set can be finite, having a finite number
    of members; a set can be infinite. The number of elements of a set
    is one obvious property of a set.  
        
     The members, or elements, of a set can be anything, even sets
    themselves. For example, {a, b, {a, b}} is a set of 3 members, and
    one of the members is a set.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.1.2 Set Equality** <span id="5.1.2"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence,
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets,
    Equivalence, and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
        
     Instructions: Study Definition 1 on page SF-1. Typically, when an
    object is defined in mathematics, we next define when two of those
    objects are equal. Then we define operations on those objects. Now,
    for the objects are sets. When are two sets equal?  
        
     If A and B are sets, and if a ∈A, implies a ∈B, then we say A is a
    subset of B, denoted A Ì B. The number of subsets of a set A, is
    denoted 2A (the reason for this notation will become clear when you
    study functions.)  
        
     A = B, if and only if, A Ì B and B Ì A. A and B are assumed to be
    subsets of a universal set E. Ø is the empty set or the set that has
    no members.  
        
     Note that the order of the elements in a set does not change the
    set. Work sufficient examples to ensure that you completely
    understand the concept of set equality.  
        
     Reading this selection and taking notes should take approximately 1
    hour.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.2 Set Operations** <span id="5.2"></span> 
*Note: Recall that in logic, operations for building compound statements
were defined. We do the same for sets, i.e. define operations for
building new sets from old sets.*

**5.2.1 The Union Operator** <span id="5.2.1"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence,
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets,
    Equivalence, and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
      
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
      
     Instructions: Study set operations and the property of set
    operations Section 1 on pages SF-2 - SF-3. Set Union is defined on
    page SF-2. Note that A È B = {x : x ∈A or x ∈B}. You will read and
    reread this section several times, each time focusing on a basic set
    operation. These basic operations are so fundamental and ubiquitous
    (i.e. occur so frequently in mathematics, computer science, and
    their applications) that they deserve more than a quick reading.
    Work a lot of examples.   
      
     Reading this selection and taking notes should take approximately 1
    hour.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.2.2 The Difference Operator** <span id="5.2.2"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence,
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets,
    Equivalence, and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
        
     Instructions: This reading is the same as that for the previous
    section. For this section, study the definitions of complement and
    set difference on page SF-2. A-B = {x : x ∈A and x Ï B}, is called
    set difference, or the complement of B with respect to A.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.2.3 The Intersection Operator** <span id="5.2.3"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence,
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets,
    Equivalence, and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
        
     Instructions: Study the reading on set intersection, defined on
    page SF-2. Note: A ∩ B = {x : x ∈A and x ∈B}.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.2.4 The Complement of a Set** <span id="5.2.4"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence,
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets,
    Equivalence, and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
        
     Instructions: This time, focus on complement of a set. Complement
    is set difference with respect to the largest set, called the
    universal set, namely, E - A is the complement of A. E is the
    universal set, the set of all elements; when sets are defined, the
    type of the elements is specified. For example, in a set of all red
    cars, the type of the members in this example, is car. We also say
    that the domain of the elements is the (universal) set of all cars.
    The complement is also written A’. Note: A’ = {x : x Ï A} = {x : x Î
    E and x Ï A}, where E is the universal, containing all
    theelements.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.2.5 Cartesian Products** <span id="5.2.5"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence,
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets,
    Equivalence, and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
        
     Instructions: One last time, look over the above reading. Now study
    the product of sets defined on page  SF-2, just before the section
    titled “Set Properties and Proofs.” The Cartesian Product, A x B =
    {(a, b) : a ∈ A and b ∈ B}, is referred to as the set of ordered
    pairs of A and B. Clearly, it is analogous to multiplication of
    numbers.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.2.6 Binary Relation** <span id="5.2.6"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence,
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets,
    Equivalence, and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
      
     Instructions: Read example 10 on page SF-16.  
        
     Given a set A, a binary relation, R on A, is a subset of A x A.
    Note that a binary relation is a set of order pairs (x, y) where x
    and y are in A. The next subunits define properties of a binary
    relation, reflexive and symmetric. A third property is
    transitivity.  
        
     Relations are another critically important concept in set theory,
    functions, science, and every other subject. Work a lot of
    examples.  
        
     Reading this selection and taking notes should take approximately 1
    hour.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.2.6.1 Reflexive** <span id="5.2.6.1"></span> 
*Note: A binary relation on A is reflexive, if (a, a) ∈R.*

**5.2.6.2 Symmetric** <span id="5.2.6.2"></span> 
*Note: A binary relation is symmetric if (a, b) ∈R, then (b, a) ∈R.*

**5.2.6.3 Transitive** <span id="5.2.6.3"></span> 
*Note: A binary relation is transitive if (a, b) ∈ R, (b, c) ∈ R, then
(a, c ) ∈ R. There is an important consequence of a binary relation
being reflexive, symmetric, and transitive. A binary relation that has
all 3 properties is called an equivalence relation. If a binary relation
on A is an equivalence relation, it determines a partition of A. A
partition of A is a set of subsets of A, which are mutually disjoint,
and whose union is A.*

**5.3 Set Identities and Proof of Set Identities** <span
id="5.3"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets, Equivalence
    and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
      
     Instructions: Read “Set Properties and Proofs” on pages SF-2 -
    SF-6. This reading applies to 5.3.1 - 5.3.3, 5.3.7, 5.3.9, and
    5.3.10.  
      
     Reading this selection and taking notes should take approximately 1
    hour.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.3.1 Commutative Laws** <span id="5.3.1"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets, Equivalence
    and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
        
     Instructions: Study Theorem 1, on pages SF-2 and SF-3, on the
    commutative laws: A È B = B È A, A Ç B = B Ç A. Prove the
    commutative laws.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.3.2 Associative Laws** <span id="5.3.2"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets, Equivalence
    and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
      
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
      
     Instructions: Study Theorem 1 on pages SF-2 and SF-3 on the
    associative laws: (A È B) È C = A È (B È C) = A È B È C. Note that
    we can write the rightmost expression, which has no parenthesis,
    because È is associative. Replacing È by the intersection
    operations, gives the associative law for intersection. Prove the
    associative laws.    
      
     Reading this selection and taking notes should take approximately
    30 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.3.3 Distributive Laws** <span id="5.3.3"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets, Equivalence
    and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
        
     Instructions: Study Theorem 1 on pages SF-2 and SF-3 on the
    distributive laws: A È (B Ç C) = (A È B) Ç (A È C); A Ç (B È C) = (A
    Ç B) È (A Ç C). The former shows union distributes over
    intersection; and the latter shows intersection distributes over
    union. Prove the distributive laws.   
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.3.4 Identity Laws** <span id="5.3.4"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets, Equivalence
    and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
      
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
      
     Instructions: Study the identities (equality of two set
    expressions) on pages SF-3 and SF-4 (the top of SF-3 and examples 2,
    3, and 4). It follows from the definition of the empty set that A È
    Ø = A, A Ç Ø = Ø. Prove these identities.  
      
     Reading this selection and taking notes should take approximately
    30 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.3.5 Complement Laws** <span id="5.3.5"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets, Equivalence
    and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
        
     Instructions: Study the identities involving complement on pages
    SF-3 and SF-4. For universal set E, E’ = Ø= A ∩ A’; A - A = Ø. Study
    example 1 on SF-4; VENN diagrams are a visual representation of
    sets, which are useful for depicting set membership of complements
    as well as other sets resulting from set operations. Use a VENN
    diagram to prove one of the identities involving complement.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.3.6 Double Complement Laws** <span id="5.3.6"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets, Equivalence
    and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
        
     Instructions: Study Theorem 1 on pages SF-2 and SF-3. Double
    complement is also referred to as double negative: (A’) ‘ = A. Take
    the identities in the theorem involving set difference or
    complement. Insert a second difference or complement operator, thus
    creating some new set equations, and check whether the new set
    equations are still identities. Prove or disprove several of the
    equations you created by adding a second difference or complement
    operation.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.3.7 Idempotent Laws** <span id="5.3.7"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets, Equivalence
    and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
        
     Instructions: Study the idempotent identities of Theorem 1 on pages
    SF-2 and SF-3. An idempotent is an object A such that (A operation
    A) = A. The idempotent laws for union and intersection are: A È A =
    A, A Ç A = A. Prove several of the idempotent identities.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.3.8 Universal Laws** <span id="5.3.8"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets, Equivalence
    and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
        
     Instructions: Study the identities involving the universal set in
    Theorem 1 and in examples 1 and 2 on pages SF-2 to SF-4. Note that
    it follows that A È A’ = E, E Ç A = A. Prove some of the identities
    involving the universal set.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.3.9 DeMorgan’s Laws** <span id="5.3.9"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets, Equivalence
    and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
      
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
      
     Instructions: Study Theorem 1 on pages SF-2 and SF-3 on DeMorgan’s
    laws: (A È B) ‘ = A’ Ç B’; (A Ç B)’ = A’ È B’. In English, the
    complement of A union B is the intersection of A complement and B
    complement; and the complement of A intersect B is the complement of
    A union the complement of B. DeMorgan’s laws are famous and appear
    in many places in mathematics, engineering, and computer science.
    Prove DeMorgan’s Laws.  
      
     Reading this selection and taking notes should take approximately
    30 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.3.10 Absorption Laws** <span id="5.3.10"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets, Equivalence
    and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
        
     Instructions: Study Theorem 1 on pages SF-2 and SF-3 on absorption
    laws: If A ⊂ B, then A È B = B, A Ç B = A; or more generally, P È (P
    Ç Q), = P, P Ç (P È Q) = P. These are called absorption identities
    because one of the sets is absorbed by the other(s). Prove the
    absorption laws.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**5.3.11 Set Difference Laws** <span id="5.3.11"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Sets, Equivalence
    and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Sets, Equivalence
    and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
        
     Instructions: Study pages SF-1 and SF-2, and Theorem 1 on pages
    SF-2 and SF-3. The set difference laws: A - (B È C) = (A - B) Ç (A -
    C); A - (B Ç C) = (A - B) È (A - C) follow from the definition of
    set difference and DeMorgan’s laws. Prove these identities using the
    fact the A - B = A Ç B’.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**Unit 5: Assessment 1** <span id="5.4"></span> 
-   **Assessment: Massachusetts Institute of Technology: Srini Devadas
    and Eric Lehman’s *Mathematics for Computer Science*: “Problem Set
    1”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Problem Set
    1”](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-1-Questions.pdf) (PDF)  
        
     Instructions: Solve problems 5 and 6. You can check your answers on
    the solutions guide
    [here](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-1-Solutions.pdf) (PDF).  
        
     Completing this assessment should take approximately 1 hour and 30
    minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**Unit 5: Assessment 2** <span id="5.5"></span> 
-   **Assessment: University of California, San Diego: Edward Bender and
    S. Williamson’s *Lectures in Discrete Mathematics*: “Sets,
    Equivalence, and Order: Unit SF: Sets and Functions”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Sets,
    Equivalence, and Order: Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.epub)  
        
     Instructions: Work on the review questions at the end of the
    chapter on pages SF-29 - SF-32.  
        
     Completing this assessment should take approximately 1 hour and 30
    minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.


