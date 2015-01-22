**Unit 8: Graphs and Trees** <span id="8"></span> 
*Graphs serve innumerable functions: they can represent communications
systems, chart knowledge, and even solve problems. In this unit, we will
acquaint ourselves with special kinds of mathematical graphs while
discussing graph concepts from degree and vertex to isomorphism. We will
then turn to trees, which comprise a special category of graphs, as they
serve special purposes and have different structures. We will conclude
with a study of tree and graph properties. Trees and graphs have
application to artificial intelligence, scheduling problems, and
transportation systems.*

**Unit 8 Time Advisory**  
This unit should take you 8.25 hours to complete.  
  
 ☐    Subunit 8.1: 2 hours  
  
 ☐    Subunit 8.2: 0.5 hours  
  
 ☐    Subunit 8.3: 0.75 hours  
  
 ☐    Subunit 8.4: 1 hour  
  
 ☐    Assessment 1: 2 hours  
  
 ☐    Assessment 2: 2 hours

**Unit8 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:  
-   construct and identify different types of graphs and trees;  
      
-   determine properties of graphs and trees, including degree,
    diameter, connectivity, tours, and cycles;  
      
-   prove graph isomorphism; and  
      
-   use graphs and trees to model and solve problems.

**8.1 Introduction to Graph Theory** <span id="8.1"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Graph Theory”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Graph
    Theory”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Graphs1-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Graphs1-Srini-Devadas.epub)  
        
     Instructions: Read this article.  
        
     A graph is simple if there is at most one arc associated with a
    pair of vertices. A graph that is not simple is called a
    multigraph.  
        
     Think of graphs as models for representing the elements and
    relations of a problem that we wish to solve.  
        
     Reading this selection and taking notes should take approximately 2
    hours.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**8.2 The Concept of Graph Degrees** <span id="8.2"></span> 
*Note: Think about a graph and imagine some properties that a graph
might have that are characteristic of a graph - essential properties,
i.e. not superficial properties like the labels for the nodes. Think
some more about how we might define quantitative properties, i.e. those
properties that take on numeric values. The following subunits present
some thinking on these matters. *

**8.2.1 Total Degrees of a Graph** <span id="8.2.1"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics*: “Lists, Decisions
    and Graphs: Basic Concepts in Graph Theory”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Lists, Decisions,
    and Graphs: Basic Concepts in Graph
    Theory”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Graph-Theory-GT-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Graph-Theory-GT-Edward-Bender.epub)  
        
     Instructions: Read Definition 3 on pages GT-4 to GT-5.  
        
     Reading this selection and taking notes should take approximately
    15 minutes.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder. 

**8.2.2 The Handshake Theorem** <span id="8.2.2"></span> 
-   **Reading: Wikipedia: “Handshaking Lemma”**
    Link: Wikipedia: [“Handshaking
    Lemma”](http://www.saylor.org/site/wp-content/uploads/2011/06/Handshaking-lemma.pdf) (PDF)  
        
     Instructions: Read the article for a description of the handshaking
    lemma and the degree sum formula.  
        
     Reading this selection and taking notes should take approximately
    15 minutes.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/). You can find
    the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Handshake_lemma).

**8.3 Isomorphism of Graphs** <span id="8.3"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: “Graph Theory”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Graph
    Theory”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Graphs1-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Graphs1-Srini-Devadas.epub)  
        
     Instructions: Read Section 1.6. Isomorphism of two graphs is a
    formal way of saying that two graphs are essentially the same.
    *Essentially the same* means that they are the same with respect to
    specified properties that characterize a graph.  
        
     Let G and H be two graphs. To show G and H are isomorphic,
    construct a bijection from the vertices of G to the vertices of H
    that preserves adjacency. The adjacency matrix, defined in section
    4, is helpful in supping the construction of an isomorphic
    mapping.  
        
     G and H are not isomorphic if:

    -   there is no bijection from the vertices of G to H;  
          
    -   there is no bijection that preserves adjacency of vertices;
        and  
          
    -   G and H have different properties, e.g. vertices have different
        degrees.

    Reading this selection and taking notes should take approximately 45
    minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**8.4 Trees** <span id="8.4"></span> 
-   **Reading: Massachusetts Institute of Technology: Srini Devadas and
    Eric Lehman’s *Mathematics for Computer Science*: Graph Theory**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Graph
    Theory”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Graphs1-Srini-Devadas.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Graphs1-Srini-Devadas.epub)  
        
     Instructions: Read Section 5 on trees on pages 15 - 18. Please note
    that the definition of tree or the properties of trees (Theorem 8)
    can be used to determine if a graph is a tree.  
        
     Reading this selection and taking notes should take approximately
    30 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

-   **Reading: The Saylor Foundation’s “Types of Trees”**
    Link: The Saylor Foundation’s [“Types of
    Trees”](http://www.saylor.org/site/wp-content/uploads/2013/07/CS202-Subunit-8.4-Types-of-Trees_FINAL.pdf) (PDF)  
      
     Instructions: Read this article for a discussion of types of trees.
       
      
     Reading this selection and taking notes should take approximately
    30 minutes.

**Unit 8: Assessment 1** <span id="8.5"></span> 
-   **Assessment: Massachusetts Institute of Technology: Srini Devadas
    and Eric Lehman’s *Mathematics for Computer Science*: “Problem Set
    5”**
    Link: Massachusetts Institute of Technology: Srini Devadas and Eric
    Lehman’s *Mathematics for Computer Science:* [“Problem Set
    5”](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-5-Questions.pdf) (PDF)  
        
     Instructions: Solve problems 1 - 6. You can check your answers on
    the solutions guide
    [here](http://www.saylor.org/site/wp-content/uploads/2012/07/Problem-Set-5-Solutions.pdf).  
        
     Completing this assessment should take approximately 2 hours.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Srini Devadas, Eric Lehman and Massachusetts Institute
    of Technology: Massachusetts Institute of Technology OpenCourseWare.
    The original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2005/).

**Unit 8: Assessment 2** <span id="8.6"></span> 
-   **Assessment: University of California, San Diego: Edward Bender and
    S. Williamson’s *Lectures in Discrete Mathematics*: “Lists,
    Decisions and Graphs: Unit GT: Basic Concepts in Graph Theory”**
    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Lectures in Discrete Mathematics:* [“Lists, Decisions
    and Graphs: Unit GT: Basic Concepts in Graph
    Theory”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Graph-Theory-GT-Edward-Bender.pdf) (PDF)  
        
     Also Available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Decision-Trees-and-Recursion-DT-Edward-Bender1.epub)  
        
     Instructions: Complete the review questions on pages GT-52 -
    GT-55.  
        
     Completing this assessment should take approximately 2 hours.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson. Please note that
    this material is under copyright and cannot be reproduced in any
    capacity without explicit permission from the copyright holder.


