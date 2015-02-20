---
layout: default
title: "CS202: Discrete Structures"
course_description: "An introduction to the mathematical foundations from discrete mathematics that are used for analyzing computer algorithms for correctness and performance. This course introduces models of computation, including finite state machines and Turing machines."
next: ../Unit02
previous: ../Intro
---
**Unit 1: The Logic of Compound Statements** <span id="1"></span> 
*Great thinkers have studied logic since the time of the Greek
philosopher Aristotle; its rules serve as the basis for the study of
every branch of knowledge − including (and perhaps especially) computer
science. Logic is an abstraction and formalization of reasoning we use
every day, in mathematics, science, and, in particular, computer
science. Logic deals with logical systems consisting of symbols that
represent statements that are either true or false, definitions of
operations for combining statements (for example, addition is an
operation in arithmetic for combining numbers), rules for manipulating
statement and operator symbols, and rules for inferring new statements
from given statements. In Unit 1 and Unit 2, we will study two logical
systems: the propositional calculus and the first order predicate
calculus.*  
    
 *The following guidance will help you get started in our study of logic
in discrete structures. The definitions and rules are called axioms or
postulates (we use these terms synonymously). We use axioms and known
true statements to prove the truth or falseness of theorems. A theorem
is a statement that has a hypothesis (assumptions) and a conclusion.
Much of our work will involve proving theorems. You may notice that
several different notations are used in logic, depending on the author,
text, or reference. In this course, we use several different notations
so that you are introduced to these differences.*  
    
 *Logic is an extensive field of study and selected topics are included
in discrete structures. These topics vary depending on the institution
or school, course, instructor, and text. To expose you to some of the
variation, we use two main resources, as well as include supplementary
resources and our own original content. In this unit, we will examine
various rules of logic (i.e. negations, conjunctions, and disjunctions)
in order to determine how they can create conditional statements,
arguments, and rules but also prove the truthfulness or falseness of any
argument, whether presented in mathematical terms or in everyday
language.*  
    
 *Note:* *Discrete structures* *is the term used for* *discrete
mathematics* *for computer science. Discrete mathematics is often
referred to as* *finite mathematics.*

**Unit 1 Time Advisory**  
This unit should take you 9.75 hours to complete.  
  
 ☐    Subunit 1.1: 3.5 hours  
  
 ☐    Subunit 1.2: 2.75 hours  
  
 ☐    Subunit 1.3: 2 hours  
  
 ☐    Assessment 1: 0.5 hours  
  
 ☐    Assessment 2: 0.5 hours  
  
 ☐    Assessment 3: 0.5 hours

**Unit1 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:  
-   define propositions and the logic operators: NOT, AND, OR, and XOR;
-   calculate truthfulness or falseness of compound propositions using
    truth tables;
-   transform compound propositions using DeMorgan’s Law and other
    identities;
-   define tautology and contradiction; and
-   apply rules of inference.

**1.1 Compound Statements** <span id="1.1"></span> 
*Note: In logic, we define operations on statements, which result in new
statements, i.e. compound statements, much like in arithmetic where we
have operations on numbers that result in a new number. We will see some
of these logic operations in the next subunit.*

**1.1.1 The NOT, AND, OR, and XOR Symbols** <span id="1.1.1"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Logic”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science*:
    [“Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-logic-and-sets.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-logic-and-sets-Srini-Devadas.epub)  
        
     Instructions: Read Section 1 through the end of Section 1.1.1 on
    pages 1 - 3. This reading discusses logical symbols or operators
    that apply to propositions (the operands) to form a compound
    statement. A proposition is a statement that is either true (T) or
    false (F). Propositions are often denoted by single letters, for
    example, P or Q. The resulting truth or falseness of the compound
    statement is determined either using a truth table based on the
    truth or falseness of the operands or, as we will see later, by
    applying inference rules to prove that the compound statement is
    inferred from true statements.  
        
     Truth tables for operations - negation, conjunction, and
    disjunction -are derived from the definition of the operation, as
    seen in this reading.  
        
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
    and Numbers: Unit BF: Boolean Functions and Computer Arithmetic”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Arithmetic, Logic
    and Numbers: Unit BF: Boolean Functions and Computer
    Arithmetic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-BF.dvi-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-BF.dvi-Edward-Bender.epub)  
        
     Instructions: Read Section 1: “Boolean Functions and Computer
    Arithmetic” up to example 6 on pages BF-1 to BF-4. Example 4
    includes XOR. This reading presents material similar to Devadas and
    Lehman, but uses the language of Boolean functions. Throughout our
    study, we will see the relationship of English statements, logic,
    Boolean functions, and sets, and will learn how to translate between
    them to represent the same meaning. Exclusive OR is defined in
    example 4. Example5 discusses the relation of Boolean functions and
    logic.  
        
     XOR is the exclusive OR symbol. It differs from OR in that the
    resulting value is true if and only if exactly one of the operands
    is true. Thus, the result value in the truth table for XOR is false
    (F) for the row where each operand has the value true (T).  
        
     Truth tables for operations, such as exclusive OR, are derived from
    the definition of the operation, as seen in this reading.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**1.1.2 Translating from English to Symbols** <span id="1.1.2"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Logic”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science*:
    [“Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-logic-and-sets.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-logic-and-sets-Srini-Devadas.epub)  
        
     Instructions: Read the beginning paragraphs in the *Logic* section
    up to Section 1, and then read Section 1.2 and Section 1.3 on pages
    3 - 6.  
        
     This reading (and the following readings for this section) shows
    the relationship of natural language, in our case English, to the
    language of logic. Logic deals with simple statements, called
    propositions, that are either true or false, and operators - for
    example, NOT, AND, and OR - that combine propositions to form
    compound statements. Translating from English to logic involves
    analyzing English statements, i.e. parsing them, into elementary
    statements that can be expressed as propositions, connected by
    conjunctions, which usually can be expressed as logic operations.
    However, since natural languages are not always precise, we have to
    be careful to understand the semantics, or meaning, of an English
    statement and then express that same meaning using logic.  
        
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
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic,
    and Numbers: Unit Lo: Logic”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit Lo:
    Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.epub)  
        
     Instructions: Read the beginning of Logic, “Section 1:
    Propositional Calculus,” from pages Lo-1 to page Lo-3, up to the
    “Implication” paragraph. This reading also applies to Subunit 1.1.3
    of this course.  
        
     These brief readings further introduce the use of logic in
    representing English or natural language statements, as well as for
    statements in mathematics. The translation discussion is continued
    in section 1.1.5 below.  
        
     Reading this selection and taking notes should take approximately
    15 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

-   **Reading: The Saylor Foundation’s “Translating from English to
    Logic Symbols”**
    Link: The Saylor Foundation’s [“Translating from English to Logic
    Symbols”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS202-Subunit-1.1.2-Translating-from-English-to-Logic-Symbols_FINAL.pdf) (PDF)  
        
     Instructions: Download this reading for a brief summary and review
    of translating English to logic symbols.  
        
     Reading this selection and taking notes should take approximately
    15 minutes.

**1.1.3 Double Negative Property** <span id="1.1.3"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit BF: Boolean Functions and Computer Arithmetic”**
       
     Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit BF: Boolean Functions and Computer
    Arithmetic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-BF.dvi-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-BF.dvi-Edward-Bender.epub)  
        
     Instructions: Read example 3 on page BF-2 in Section 1: “Boolean
    Functions and Computer Arithmetic” of the Bender and Williamson
    reading.  
        
     We have seen that some statements in English can be translated to
    logic. We have also seen in the Bender and Williamson reading in
    1.1.1, the equivalence of logic and Boolean functions. The term
    “equivalence” is used here in the context of equivalence of
    representations. The term “equivalence” in logic is used to mean
    that two propositions have the same truth value. Thus, the same word
    has two similar, yet different, meanings depending on the context in
    which it is used. Assignment of true to a proposition corresponds to
    a Boolean function that maps the proposition to 1. Assignment of
    false to a proposition corresponds to a Boolean function that maps
    the proposition to 0. The logic operators are translated to
    operations on Boolean functions.  
        
     NOT is a unary operator, meaning it has one operand. The other
    operators AND, OR, and XOR are binary operators, meaning they have
    two operands. “NOT P,” as a Boolean function is written as, NOT (P),
    or ~P, where P is in the set {0,1}. As a unary logic operator, it is
    defined by the truth table referenced in subunit 1.1.1, and as a
    Boolean function it is defined in example 3 in Devadas and Lehman.  
        
     The truth table for NOT P, can be used to evaluate the truth or
    falseness of NOT (NOT P), which is T when P is T, and F when P is F.
    Thus, it has the same values as P. We say that NOT (NOT P) and P are
    equivalent as logic operators. Using Boolean functions, NOT (NOT
    (P)) is evaluated as follows: P is either 0 or 1. When P is 1, NOT
    (NOT (1)) = 1. When P is 0, NOT (NOT (0)) = 0. Thus, NOT (NOT) (P) =
    identity function.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**1.1.4 Negations of AND and OR: DeMorgan’s Law** <span
id="1.1.4"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit BF: Boolean Functions and Computer Arithmetic” and
    “Arithmetic, Logic and Numbers: Unit Lo: Logic”**
     Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit BF: Boolean Functions and Computer
    Arithmetic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-BF.dvi-Edward-Bender.pdf) (PDF)
    and [“Arithmetic, Logic and Numbers: Unit Lo:
    Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.epub) (Logic)  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-BF.dvi-Edward-Bender.epub) (Boolean
    Functions)  
        
     Instructions: Study Theorem 2 (Algebraic rules for Boolean
    Functions) on pages BF-6 and BF-7. In the article on Logic, study
    Theorem 1 (Algebraic rules for statement forms) on page Lo-3.  
        
     A similar argument could be used to prove DeMorgan’s law, which is
    very useful and widely used in communication, mathematics,
    engineering, and the sciences. Please make sure to familiarize
    yourself with DeMorgan’s law before moving on to other sections of
    this course.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**1.1.5 Tautologies and Contradictions** <span id="1.1.5"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit Lo: Logic”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit Lo:
    Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.epub)  
      
     Instructions: Study definition 1 (Tautology, contradiction) in
    Section 1 on pages Lo-2 and Lo-3. In Subunit 1.1.2 of this course,
    we introduced translation between English statements and logic. This
    reading, in addition to tautology and contradiction, adds to the
    translation story by discussing the relationship with set theory.
    Thus, you can translate from and to English, logic, and set symbols.
    The discussion of translation will continue when you study
    implication in the Subunit 1.2.1.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**1.2 Conditional Statements** <span id="1.2"></span> 
*Note: As you have likely noticed there is a similarity between the
language of logic and a natural language, such as English. In fact,
there is a similarity between implication in logic and the conditional
statement in English, i.e. an if statement. In the follow subsections,
we will study the application of operations to the logical if
statement. *

**1.2.1 Logical Equivalences Using Conditional Statements** <span
id="1.2.1"></span> 
-   **Reading: Massachusetts Institute of Technology: Reading: Srini
    Devadas and Eric Lehman’s *Mathematics for Computer Science*:
    “Logic”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science*:
    [“Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-logic-and-sets.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-logic-and-sets-Srini-Devadas.epub)  
        
     Instructions: Read Section 1.1.2 and Section 1.1.3 on pages 4 and
    5. Section 1.1.3 of this reading also applies to Subunit 1.2.5.  
        
     The conditional statement in English can be translated to
    implication in logic.  
        
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
    and Numbers: Unit Lo: Logic”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit Lo:
    Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.epub)  
        
     Instructions: Read the section titled “Implication” up to the
    exercises on pages Lo-4 - Lo-9. For the English translation
    discussion, see example 3 on page Lo-6 and Subunit 1.1.2 of this
    course. Example 3 also applies to Subunits 1.2.2, 1.2.3, and
    1.2.4.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**1.2.2 Negation of a Conditional Statement** <span id="1.2.2"></span> 
*Note: Conditional English sentences can be difficult to interpret,
particularly when they are negated. Logic helps us to correctly
interpret such statements. This topic, negation of a conditional
statement, is addressed in the reading on implication in Subunit 1.2.1.*

**1.2.3 Contrapositive of a Conditional Statement** <span
id="1.2.3"></span> 
*Note: Given a conditional statement, we can derive several new
statements from it by inserting negation and/or inverting the antecedent
and consequent. For example, from P implies Q, we can derive NOT Q
implies NOT P. These two statements, namely the implication, P implies
Q, and the derived statement are logically equivalent. This derivation
is called the contrapositive of the implication. Contrapositive is
discussed in the Bender and Williamson reading in Subunit 1.2.1.*

**1.2.4 Converse and Inverse of a Conditional Statement** <span
id="1.2.4"></span> 
*Note: In addition to negation of a conditional statement and
contrapositive, two other common derivations from a conditional
statement are the converse and inverse. These are discussed in the
readings for Subunit 1.2.1.*

**1.2.5 If and Only If, Necessary and Sufficient Conditions** <span
id="1.2.5"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit Lo: Logic”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit Lo:
    Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.epub)  
        
     Instructions: Read example 5 on pages Lo-7 - Lo-8. Note that in the
    statement A if and only if B, abbreviated A iff B, A is called the
    necessary part and B the sufficient part.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**1.2.6 Proving Validity or Invalidity of an Argument Using Truth
Tables** <span id="1.2.6"></span> 
-   **Reading: Reading: Massachusetts Institute of Technology: Srini
    Devadas and Eric Lehman’s *Mathematics for Computer Science*:
    “Logic”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science*:
    [“Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-logic-and-sets.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-logic-and-sets-Srini-Devadas.epub)  
        
     Instructions: Read Section 1.2 on pages 5 and 6 and 1.4 on pages
    6 - 8 to learn about logical equivalence of statements. The term
    validity refers to an argument or proof. We say an argument is valid
    if its conclusion logically follows from its premises. We can do
    this by showing that a statement is logically equivalent to a
    premise, or by showing that a statement logically follows from a
    premise. Logically follows from, or is a consequence of, means that
    the conclusion is true if the premise is true.  
        
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
    and Numbers: Unit BF: Boolean Functions and Computer Arithmetic”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit BF: Boolean Functions and Computer
    Arithmetic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-BF.dvi-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-BF.dvi-Edward-Bender.epub)  
        
     Instructions: Read example 7 on pages BF-7 and BF-8. This is an
    example where a given expression is transformed into a logically
    equivalent expression, which, in turn, is translated into another
    equivalent express, and so on.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

-   **Reading: The Saylor Foundation’s “Validity and Arguments”**
    Link: The Saylor Foundation’s [“Validity and
    Arguments”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS202-Subunit-1.2.6-Validity-and-Arguments_FINAL.pdf) (PDF)  
      
     Instructions: Read through the entire text linked here.  
      
     Reading this selection and taking notes should take approximately
    15 minutes.

**1.3 Modus Ponens and Modus Tollens** <span id="1.3"></span> 
*Note: A proof, or an argument, is a series of statements where each
statement logically follows from the previous one(s). Logically follows
means that there is a logic rule of inference that derives it from the
previous statement(s). One famous rule of inference is modus ponens,
which we will study in the next subunits.*

**1.3.1 Rules of Inference** <span id="1.3.1"></span> 
-   **Reading: Wikipedia: “List of Rules of Inference, Table: Rules of
    Inference - A Short Summary”**
    Link: Wikipedia: [“List of Rules of Inference, Table: Rules of
    Inference - A Short
    Summary”](http://www.saylor.org/site/wp-content/uploads/2011/06/List-of-Rules-of-inference.pdf) (PDF)  
        
     Instructions: Read over the text from Wikipedia on rules of
    inference. Rules of inference are used to show that one statement is
    a consequence of another statement and, thus, are used for
    constructing proofs. The summary table is located before the truth
    table and the examples. The Rules of Inference are referred to by
    names in the 3rd column in the table. In this course, alternate
    names are also used. Those that have corresponding alternate names
    are listed in the following table:  
        

    <table>
    <tbody>
    <tr class="odd">
    <td align="left"><strong> Wikipedia Name</strong></td>
    <td align="left"><strong> Alternate Name</strong></td>
    </tr>
    <tr class="even">
    <td align="left"> Disjunction</td>
    <td align="left"> Generalization</td>
    </tr>
    <tr class="odd">
    <td align="left"> Conjunction</td>
    <td align="left"> Specialization</td>
    </tr>
    <tr class="even">
    <td align="left"> Elimination</td>
    <td align="left"> Generalization</td>
    </tr>
    <tr class="odd">
    <td align="left"> Modus Ponens</td>
    <td align="left"> </td>
    </tr>
    <tr class="even">
    <td align="left"> Modus Tollens</td>
    <td align="left"> </td>
    </tr>
    <tr class="odd">
    <td align="left"> Hypothetical Syllogism</td>
    <td align="left"> Transitivity</td>
    </tr>
    <tr class="even">
    <td align="left"> Disjunctive Syllogism</td>
    <td align="left"> Disjunctive Elimination</td>
    </tr>
    <tr class="odd">
    <td align="left"> Resolution</td>
    <td align="left"> Elimination</td>
    </tr>
    </tbody>
    </table>

       
     Reading this selection and taking notes should take approximately
    45 minutes.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/)You can find the
    original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/List_of_rules_of_inference).

-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Proofs”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science*:
    [“Proofs”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Proofs-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Proofs-Srini-Devadas.epub)  
        
     Instructions: Read Section 1, “The Axiomatic Method,” up to Section
    3 on pages 3 - 7. Please note that reading Section 3 on pages 7 - 9
    is optional.  
        
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
    and Numbers: Unit Lo: Logic”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Arithmetic, Logic
    and Numbers: Unit Lo:
    Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.epub)  
        
     Instructions: Review example 4 (Right Triangles and the Pythagorean
    theorem) on pages Lo-6 - Lo-7. It illustrates some of the rules of
    inference.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

-   **Reading: The Saylor Foundation’s “Modus Ponens and Other Types of
    Reasoning”**
    Link: The Saylor Foundation’s [“Modus Ponens and Other Types of
    Reasoning”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS202-Subunit-1.3.1-Modus-Ponens-and-Types-of-Reasoning_FINAL.pdf) (PDF)  
      
     Instructions: This is a summary of Modus Ponens and other types of
    reasoning.  
      
     Reading this selection and taking notes should take approximately
    15 minutes.

**Unit 1: Assesment 1** <span id="1.4"></span> 
-   **Assessment: Massachusetts Institute of Technology: Srini Devadas
    and Eric Lehman’s *Mathematics for Computer Science*: “Problem Set
    1”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Problem Set
    1”](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-1-Questions.pdf) (PDF)
       
      
     Instructions: Complete problem \#1. You can check your answers on
    the solutions guide
    [here](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-1-Solutions.pdf).
    (PDF)  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**Unit 1: Assesment 2** <span id="1.5"></span> 
-   **Assessment: University of California, San Diego: Edward Bender and
    S. Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic,
    Logic, and Numbers: Unit Lo: Logic”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Arithmetic, Logic
    and Numbers: Unit Lo:
    Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.epub)  
        
     Instructions: Given that a set P is a subset of set Q, let *a* be
    an element that is not in Q. Prove using the propositional calculus
    that *a* is not in set P. Hint: Translate the statements to the
    predicate calculus and use rules of inference. For background
    reading for this problem, select the hyperlink “Lo PDF” to download
    the file for the Logic Unit. In this Logic Unit, you may want to
    reread the material from example 1 up to example 3 as a review. Keep
    in mind the difference between implication, which is a Binary
    function, or logic operator for combining two statements, and a rule
    of inference, such as Modus Ponens, with which we form proofs or
    arguments.  
        
     Answer: Assume, without loss of generality, that sets P and Q
    consist of members from a universal set U. Let *y* be any member of
    U, and *a* be a specific member of U.  
        
     Then, we have to prove that NOT (a in P) logically follows from [(y
    in P) --\> (y in Q)] / [NOT (a in Q)].  
      
     The truth table for this follows.  
        

    <table>
    <tbody>
    <tr class="odd">
    <td align="left">1</td>
    <td align="left">y in P</td>
    <td align="left">y in Q</td>
    <td align="left">y in P<br /> ----&gt;<br /> y in Q</td>
    <td align="left">a in Q</td>
    <td align="left">NOT (a in Q)</td>
    <td align="left">[(y in P) --&gt;<br /> (y in Q)] /<br /> (NOT (a in Q))</td>
    </tr>
    <tr class="even">
    <td align="left">2</td>
    <td align="left">F</td>
    <td align="left">F</td>
    <td align="left">T</td>
    <td align="left">F</td>
    <td align="left">T</td>
    <td align="left">T</td>
    </tr>
    <tr class="odd">
    <td align="left">3</td>
    <td align="left">F</td>
    <td align="left">F</td>
    <td align="left">T</td>
    <td align="left">T</td>
    <td align="left">F</td>
    <td align="left">F</td>
    </tr>
    <tr class="even">
    <td align="left">4</td>
    <td align="left">F</td>
    <td align="left">T</td>
    <td align="left">T</td>
    <td align="left">F</td>
    <td align="left">T</td>
    <td align="left">T</td>
    </tr>
    <tr class="odd">
    <td align="left">5</td>
    <td align="left">F</td>
    <td align="left">T</td>
    <td align="left">T</td>
    <td align="left">T</td>
    <td align="left">F</td>
    <td align="left">F</td>
    </tr>
    <tr class="even">
    <td align="left">6</td>
    <td align="left">T</td>
    <td align="left">F</td>
    <td align="left">F</td>
    <td align="left">F</td>
    <td align="left">T</td>
    <td align="left">T</td>
    </tr>
    <tr class="odd">
    <td align="left">7</td>
    <td align="left">T</td>
    <td align="left">F</td>
    <td align="left">F</td>
    <td align="left">T</td>
    <td align="left">F</td>
    <td align="left">F</td>
    </tr>
    <tr class="even">
    <td align="left">8</td>
    <td align="left">T</td>
    <td align="left">T</td>
    <td align="left">T</td>
    <td align="left">F</td>
    <td align="left">T</td>
    <td align="left">T</td>
    </tr>
    <tr class="odd">
    <td align="left">9</td>
    <td align="left">T</td>
    <td align="left">T</td>
    <td align="left">T</td>
    <td align="left">T</td>
    <td align="left">F</td>
    <td align="left">F</td>
    </tr>
    </tbody>
    </table>

       
     SINCE y is a variable, it HOLDS for a specific value, y = a, and we
    can REPLACE y with a in the table. This yields a table for [(a in
    P) --\> (a in Q)] / [NOT (a in Q)].  
      
     The hypothesis included that a is not in Q. This occurs for the
    rows: 2, 4, 6, and 8. Rows 4 and 8 are not applicable because they
    state (a in Q) and (a not in Q), which can’t occur, at least not in
    our reality. Look at row 6; it states that the implication, (a in
    P) --\> (a in Q) is false; our hypothesis states otherwise, namely
    we assume it’s true. Therefore, only row 2 is applicable; row 2
    states a in P is false, which is what we wanted to prove, i.e. a is
    not in P.  
        
     Of course we could have proved this assessment using set theory,
    but because this is a unit on logic, we wanted to demonstrate the
    translation from sets to logic, and then use logic to prove the
    hypothesis.  
        
     Completing this assessment should take approximately 30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**Unit 1: Assesment 3** <span id="1.6"></span> 
-   **Assessment: University of California, San Diego: Edward Bender and
    S. Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic,
    Logic, and Numbers: Unit Lo: Logic”**
    Link: University of California, San Diego: Edward Bender and S.
    *Williamson’s Lectures in Discrete Mathematics:* [“Arithmetic, Logic
    and Numbers: Unit Lo:
    Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.epub)  
        
     Instructions: Do review Questions 1 - 6 on page Lo-23.  
        
     Completing this assessment should take approximately 30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.


