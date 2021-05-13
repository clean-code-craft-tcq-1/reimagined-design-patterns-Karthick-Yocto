# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.
> 



**1.Adapter Pattern:

          -Adapter pattern works as a transulator between two incompatible interfaces.
          
          -This pattern involves function called adater which is responsible for communication between two 
           independent or incompatible interface.

**Problem statement:

    Whenever try to communicate two application with two different platform (32-bit and 64-bit), then we should need interface(Trasulator).
      
      
      A( 32- bit)      ----Transulator(Adapter)----- B( 64 - bit)


**Advantages:

          -This pattern is used to acheive two independent process communication    
          
          
          
  
**2. Bridge Pattern:
 
          Bridge pattern used to spilt implementation into two part

		1. Abstraction 
		2. Implementation
 
          Abstraction and implementation to be developed independently
          
  **Problem statement:        
              
	    Where ever, if any changes in abstraction layer, it won't effect in implementation layer. 
             Where ever, if any changes in implementation layer, it won't effect in abstraction layer.
