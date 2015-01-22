**Unit 2: The Logic of Quantified Statements** <span id="2"></span> 
*In the previous unit, we discussed the logical analysis of compound
statements, including those comprised of simple statements joined by OR,
AND, NOT, etc. operators. This analysis provides us with a better
understanding of human reasoning, but cannot be used to determine the
validity of the majority of mathematical situations. In some cases, it
becomes necessary to separate statements into parts, just as we parse
sentences in order to facilitate comprehension.*  
    
 *In this unit, we will learn to analyze and understand the special
roles that keywords and predicates (i.e.* *for all *and *some) play −
exercises that constitute the foundation of predicate calculus.*

**Unit 2 Time Advisory**  
This unit should take you 8.5 hours to complete.  
  
 ☐    Subunit 2.1: 3.5 hours  
  
 ☐    Subunit 2.2: 2 hours  
  
 ☐    Subunit 2.3: 1 hour  
  
 ☐    Assessment 1: 1 hour  
  
 ☐    Assessment 2: 1 hour

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:  
-   form predicate calculus statements using universal and existential
    quantifiers;
-   translate to and from English to predicate calculus statements;
-   apply AND, OR, NOT, =\> to statements containing universal and
    existential quantifiers;
-   apply predicate calculus rules to transform statements that contain
    both universal and existential quantifiers; and
-   prove predicate calculus statements using logic rules of inference.

**2.1 Quantified Statements** <span id="2.1"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Logic”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:*
    [“Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-logic-and-sets.pdf) (PDF)
       
      
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-logic-and-sets-Srini-Devadas.epub)  
        
     Instructions: Read Section 3 through 3.1 on pages 11 and 12. This
    reading introduces the universal quantifier and the existential
    quantifier. Logic without quantifiers is called propositional
    calculus; logic with quantifiers is called the (first order)
    predicate calculus.  
        
     Reading this selection and taking notes should take approximately
    45 minutes.  
        
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
    Williamson’s *Lectures in Discrete Mathematics\</em\>:*
    [“Arithmetic, Logic and Numbers: Unit Lo:
    Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.pdf)(PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.epub)  
      
     Instructions: Read Section 2: “Predicate Logic” up to and including
    Definition 4 on pages Lo-12 and Lo-13. As you read this text,
    consider that statements in the first order predicate calculus, or
    for us, simply, the predicate calculus, involve variables that can
    take on values from a set in a reference domain. We interpret the
    statement by introducing a domain of discourse or reference domain
    that the symbols (statements and operators), the rules, and
    variables represent or refer to. This is essentially what we do when
    we translate from English to logic. In other words, translation is
    using one domain, e.g. logic, to represent another domain, and
    setting up an association between symbols in one to those of the
    other. Just keep in mind, that the variables in a predicate calculus
    statement take on the values from a particular set, for example, the
    set of all boys in Chicago or the set of positive integers.  
      
     For an understanding of the universal quantifier, study Definition
    4, on page Lo-12, which is critically important for the study of
    logic, science and mathematics. This definition also defines the
    existential quantifier. These two quantifiers are often used
    together, as the examples in the next subunits will show.  
        
     Reading this selection and taking notes should take approximately 1
    hour.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**2.1.1 Translating between Formal and Informal Languages** <span
id="2.1.1"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer ScienceM*: “Logic”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:*
    [“Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-logic-and-sets.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-logic-and-sets-Srini-Devadas.epub)  
        
     Instructions: Read Sections 3.2 on page 12 and 3.6 on pages 14 and
    15. This reading also pertains to the topic in subunit 2.1.2. This
    reading shows how logic (a formal language) can be used to describe
    sets (another formal language).  
      
     Reading this selection and taking notes should take approximately
    45 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
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
        
     Instructions: Read Definition 5 up to and including example 8 on
    pages Lo-13 and Lo-14. This reading also applies to the topic for
    Subunit 2.1.2 of this course. This reading gives important examples
    of using logic to represent statements in mathematics. As you read
    this text, please keep in mind that formal language includes logic,
    binary functions, sets, and programming languages. Informal language
    includes English and other natural languages. Please note that
    translating from informal to informal language for subunit 2.1.2
    involves rewriting an informal statement into a different but
    equivalent statement.  
        
     Reading this selection and taking notes should take approximately 1
    hour.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**2.1.2 Translating from Informal to Informal Language** <span
id="2.1.2"></span> 
*Note: The Bender and Williamson reading for 2.1.1 addresses translating
from informal to informal language(s). In our study of logic, our
primary interest is translating between logic and English (or natural
languages). In addition, you will find it useful to translate between
informal (that is, natural) languages. For example, suppose you have an
English statement that you find difficult to translate to logic.
Rewriting or translating the statement to an equivalent English
statement usually makes the translation to logic easy. Translating
between informal or natural languages also occurs when we translate from
one natural language to another, for example, from English to Spanish.*

**2.2 Operating on Quantified Statements** <span id="2.2"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Logic”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:*
    [“Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-logic-and-sets.pdf) (PDF)
       
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-logic-and-sets-Srini-Devadas.epub)  
        
     Instructions: Read Sections 3.3 and 3.4 on page 13. We have seen
    the use of quantifiers in representing statements in other
    languages, e.g. English, mathematics, and programming. The next step
    is to see how statements with quantifiers can be combined and
    transformed using logic rules. This reading looks at statements that
    have both types of quantifiers, i.e. universal and existential, used
    together; it also looks at the order in which the quantifiers
    appear.  
        
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
      
     Instructions: Read example 15 on page Lo-19. Here you read about
    the use of quantifiers together with the use of logic operations,
    such as AND, OR.  
      
     As you study and read, you should THINK about the material, both on
    what it means in relation to what you already know and how it
    relates to other topics you have studied. To help you think about
    the material, you should look at the exercises, even if the
    instructions don’t explicitly state this.  
      
     Reading this selection and taking notes should take approximately
    30 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**2.2.1 Negations of Quantified Statements** <span id="2.2.1"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric *Lehman’s Mathematics for Computer Science*: “Logic”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science*:
    [“Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-logic-and-sets.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-logic-and-sets-Srini-Devadas.epub)  
        
     Instructions: Read Section 3.5 on page 14 on the use of quantifiers
    with negation.  
        
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
        
     Instructions: Please read example 9 and example 10 on pages Lo-14
    and Lo-15. These readings apply to the topics in 2.2.1.1, 2.2.1.2,
    and 2.2.2 through 2.2.4. Here is where you will have to apply some
    of your self-learning skills: you should review what a
    contrapositive, converse, and inverse are, and use what you have
    learned about how quantifiers and negation affect one another.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**2.2.1.1 Negating a Universal Statement** <span id="2.2.1.1"></span> 

*Note: The reading for 2.2.1 includes negation of statements having
quantifiers. Given a statement in logic, as you have seen with the
propositional logic, we can negate it. We can do the same for a
statement in predicate logic. Then, once we negate it, how can we
rewrite the negated statement as a logically equivalent statement, so
that the negation applies to the parts of the statement, rather than the
entire statement? Why do we care? Because by doing so, we often simplify
the statement or put it into a more convenient form for a particular
purpose. In effect, we can study ways to translate from logic to logic
in order to obtain a statement that is more convenient for what we might
need. *

**2.2.1.2 Negating an Existential Statement** <span
id="2.2.1.2"></span> 

*Note: The reading for 2.2.1 also includes the negation of an
existential quantifier.*

**2.2.2 Contrapositive of a Statement Having a Universal or Existential
Quantifier** <span id="2.2.2"></span> 

*Note: The reading for 2.2.1 also includes other “transformations,” in
addition to negation, of a logic statement that uses quantifiers. In
particular, that reading addresses the contrapositive of a statement
having a quantifier. *

**2.2.3 Converse of a Statement Having a Universal or Existential
Quantifier** <span id="2.2.3"></span> 
*Note: Just as with negation and contrapositive, the reading for 2.2.1
covers the converse of a statement having a quantifier.*

**2.2.4 Inverse of a Statement Having a Universal or Existential
Quantifier** <span id="2.2.4"></span> 
*Note: Just as with negation and contrapositive, the reading for 2.2.1
covers the converse of a statement having a quantifier.*

**2.3 Statements Containing Multiple Quantifiers** <span
id="2.3"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic, Logic
    and Numbers: Unit Lo: Logic”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: [“Arithmetic, Logic
    and Numbers: Unit Lo:
    Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.epub)  
      
     Instructions: Read from example 11 up to Exercises for Section 2 on
    pages Lo-16 - Lo-19. These readings also apply to topics in subunits
    2.3.1 and 2.3.2. The examples work with multiple quantifiers and
    pertain to translation between logic and math and English domains.  
        
     Reading this selection and taking notes should take approximately
    45 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.

**2.3.1 Translating Statements with Multiple Quantifiers from Formal to
Informal Language** <span id="2.3.1"></span> 
*Note: This topic is covered by the reading in subunit 2.3. The
direction of the translation in this topic, from formal to informal
language, is typically done to communicate a result obtained from logic,
back to the language in which the problem was specified.*

**2.3.2 Translating Statements with Multiple Quantifiers from Informal
to Formal Language** <span id="2.3.2"></span> 
*Note: This topic is covered by the reading in subunit 2.3. The
“direction” of this translation, from a natural language to logic, is
done to apply logic to a problem in some other discipline or everyday
task (e.g. history, science; making a decision, debating). Furthermore,
in applying logic, we also find it useful to translate from logic to
logic (to transform a statement into a more convenient form), and to
translate from a natural language to a natural language to simplify
translation to logic.*

**2.3.3 The Definition of a Limit** <span id="2.3.3"></span> 
-   **Reading: The Saylor Foundation’s “Definition of a Limit”**
    Link: The Saylor Foundation’s [“Definition of a
    Limit”](http://www.saylor.org/site/wp-content/uploads/2013/07/C202-Subunit-2.3.3-Definition-of-a-Limit_FINAL.pdf) (PDF)  
        
     Instructions: Read this text in its entirety to better understand
    the definition of a limit and primarily to illustrate the use of the
    notation from this unit.  
      
     Limits are studied in continuous mathematics, such as the
    differential and integral calculus, and in analysis. Discrete
    mathematics (which is studied in discrete structures) provides the
    concepts that are used in defining topics in continuous mathematics.
    This is illustrated with the reading for this topic.  
        
     Reading this selection and taking notes should take approximately
    15 minutes.

**Unit 2: Assessment 1** <span id="2.4"></span> 
-   **Assessment: Massachusetts Institute of Technology: Srini Devadas
    and Eric Lehman’s *Mathematics for Computer Science*: “Problem Set
    1”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Problem Set
    1”](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-1-Questions.pdf) (PDF)  
        
     Instructions: Solve problems 2 and 3. You can check your answers in
    the solutions guide
    [here](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-1-Solutions.pdf).
    (PDF)  
        
     Completing this assessment should take approximately 1 hour.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**Unit 2: Assessment 2** <span id="2.5"></span> 
-   **Assessment: University of California, San Diego: Edward Bender and
    S. Williamson’s *Lectures in Discrete Mathematics*: “Arithmetic,
    Logic, and Numbers: Unit Lo: Logic”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Arithmetic, Logic
    and Numbers: Unit Lo:
    Logic”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Unit-lo-logic-Edward-Bender.epub)  
        
     Instructions: Complete review questions 7 - 11 on page Lo-24 -
    Lo-25.  
        
     Completing this assessment should take approximately 1 hour.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.


