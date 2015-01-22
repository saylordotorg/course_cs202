**Unit 9: Regular Expressions and Finite-State Automata** <span
id="9"></span> 
*Computer language compilers frequently use regular languages (which
feature regular expressions) to match patterns within text or perform
lexical analysis. This unit will introduce formal languages and state
automata to prove the correctness or falsity of a language. We will see
that some languages might not be valid for a state automaton, but that
we can also define and create state automata for languages defined using
regular expressions.*  
    
 *The definition of regular expressions is recursive. This definition
and that of regular sets and regular expressions requires careful
contemplation on your part.*  
    
 *The topic of formal languages and the related topic of finite state
automata are not directly addressed in our two references. Our study of
discrete structures has given us the background to develop these topics
in instruction paragraphs.*  
    
 *We begin with notation, terminology, and definitions and expressions
for formal languages. Then we introduce finite automata and their
relationship with regular expressions, and use them to solve problems.*

**Unit 9 Time Advisory**  
This unit should take you 5.5 hours to complete.  
  
 ☐    Subunit 9.1: 1 hours  
  
 ☐    Subunit 9.2: 1.5 hours  
  
 ☐    Assignment 1: 3 hours

**Unit9 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:  
-   define formal languages using operator precedence and regular
    expressions;  
      
-   construct and analyze finite state automata; and  
      
-   relate formal languages and automata.

**9.1 Formal Languages** <span id="9.1"></span> 
-   **Reading: The Saylor Foundation’s “Formal Languages”**
    Link: The Saylor Foundation’s [“Formal
    Languages”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS202-Subunit-9.1-Formal-Languages_FINAL.pdf) (PDF)  
        
     Instructions: Read this discussion of grammar and formal
    languages.  
        
     Reading this selection and taking notes should take approximately
    15 minutes.

**9.1.1 Polish Notation** <span id="9.1.1"></span> 
-   **Reading: The Saylor Foundation’s “Polish Notation”**
    Link: The Saylor Foundation’s [“Polish
    Notation”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS-202-Subunit-9.1.1-Polish-Notation_FINAL.pdf) (PDF)  
        
     Instructions: Read this discussion of Polish notation for
    describing expressions.  
        
     Reading this selection and taking notes should take approximately
    15 minutes.

**9.1.2 Languages Defined by Regular Expressions** <span
id="9.1.2"></span> 
-   **Reading: The Saylor Foundation’s “Languages Defined by Regular
    Expressions”**
    Link: The Saylor Foundation’s [“Languages Defined by Regular
    Expressions”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS-202-Subunit-9.1.2-Languages-Defined-by-Regular-Expressions_FINAL.pdf) (PDF)  
        
     Instructions: Read this discussion of languages defined by regular
    expressions.  
        
     Reading this selection and taking notes should take approximately
    15 minutes.

**9.1.2.1 Order of Precedence Rules** <span id="9.1.2.1"></span> 
-   **Reading: The Saylor Foundation’s “Order of Precedence Rules”**
    Link: The Saylor Foundation’s [“Order of Precedence
    Rules”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS-202-Subunit-9.1.2.1-Order-of-Precedence-Rules_FINAL.pdf) (PDF)  
        
     Instructions: Read this discussion of operator precedence.  
        
     Reading this selection and taking notes should take approximately
    15 minutes.

**9.1.2.2 Deciding Whether Regular Expressions Define the Same
Language** <span id="9.1.2.2"></span> 
-   **Reading: The Saylor Foundation’s “Deciding Whether Regular
    Expressions Define the Same Language”**
    Link: The Saylor Foundation’s [“Deciding Whether Regular Expressions
    Define the Same
    Language”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS-202-Subunit-9.1.2.2-Deciding-Whether-Regular-Expressions-Define-the-Same-Lanaguage_FINAL.pdf) (PDF)  
        
     Instructions: Download the linked file for a discussion of operator
    precedence.  
        
     Reading this selection and taking notes should take approximately
    15 minutes.

**9.2 Finite State Automata** <span id="9.2"></span> 
-   **Reading: The Saylor Foundation’s “Finite State Automata”**
    Link: The Saylor Foundation’s [“Finite State
    Automata”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS-202-Subunit-9.2-Finite-State-Automata_FINAL.pdf) (PDF)  
        
     Instructions: Read this discussion on finite state automata.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.

**9.2.1 Automaton and Accepted Language** <span id="9.2.1"></span> 
-   **Reading: The Saylor Foundation’s “Automaton and Accepted
    Language”**
    Link: The Saylor Foundation’s [“Automaton and Accepted
    Language”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS-202-Subunit-9.2.1-Automaton-and-Accepted-Language_FINAL.pdf) (PDF)  
        
     Instructions: Read this discussion of regular sets and their
    acceptance by finite state automata.  
        
     Reading this selection and taking notes should take approximately
    15 minutes.

**9.2.2 Designing a Finite State Automaton** <span id="9.2.2"></span> 
-   **Reading: The Saylor Foundation’s “Designing a Finite State
    Automaton”**
    Link: The Saylor Foundation’s [“Designing a Finite State
    Automaton”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS-202-Subunit-9.2.2-Designing-a-Finite-State-Automaton_FINAL.pdf) (PDF)  
        
     Instructions: Read this discussion of hints on designing a finite
    state automaton to recognize a given regular set.  
        
     Reading this selection and taking notes should take approximately
    15 minutes.

**9.2.3 Showing that a Language Is Not Regular** <span
id="9.2.3"></span> 
*Not all languages are regular. Because a finite state machine has a
finite number of states, it can only remember a finite number of inputs.
Consider the set {o<sup>n</sup> 1<sup>n</sup> for all n \>= 0}. Because
this set requires a recognizing machine to remember n 0’s for any n (so
that it can then look for n 1’s), the number of states is infinite, i.e.
not a finite state machine. Thus, the language is not regular. Hence,
one way to show that a language is not regular is to show that the
automaton that recognizes it has an infinite number of states. *

**9.2.4 Simplifying Finite State Automata** <span id="9.2.4"></span> 
-   **Reading: The Saylor Foundation’s “Simplifying Finite State
    Automata”**
    Link: The Saylor Foundation’s [“Simplifying Finite State
    Automata”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS-202-Subunit-9.2.4-Simplifying-Finite-State-Automata_FINAL.pdf) (PDF)  
        
     Instructions: Read this discussion of ways to simplify finite state
    automata.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.

**Unit 9: Assignment 1** <span id="9.3"></span> 
-   **Assignment: The Saylor Foundation’s “Unit 9 Assignment”**
    Link: The Saylor Foundation’s [“Unit 9
    Assignment”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS202-Unit-9-Assignment-Answers.pdf) (PDF)  
        
     Instruction: Please complete this assignment. Then, check your
    answers against the [answer
    key](http://www.saylor.org/site/wp-content/uploads/2013/07/CS202-Unit-9-Assignment_FINAL.pdf).  
        
     Completing this assignment should take approximately 3 hours.

**Final Exam** <span id="10"></span> 
-   **Final Exam: The Saylor Foundation’s “CS202 Final Exam”**
    Link: The Saylor Foundation’s [“CS202 Final
    Exam”](http://school.saylor.org/mod/quiz/view.php?id=331)  
      
     Instructions: You must be logged into your Saylor Foundation School
    account in order to access this exam. If you do not yet have an
    account, you will be able to create one, free of charge, after
    clicking the link.


