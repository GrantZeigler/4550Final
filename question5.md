# Grant Zeigler - Question 5


* Single Responsibility Principle
  * Each class should have a single responsibility, and that responsibility should be encapsulated by that class
  * Incorrect class diagram:
  
  ![](https://yuml.me/ab86ad62.jpg)
  
  This violate the Principle by having a single class with multiple responsibilities
  
  * Correct class diagram: 
  
  ![](http://yuml.me/de1b5efa.jpg)
  
  This fixes the class by having each class only have one responsibility
* Open/Closed Principle
  * Software pieces, such as classes and and functions, should be able to be extended but not modified.
  * Incorrect class diagram:
  
  ![](http://yuml.me/a42e67da.jpg)
  
  This is incorrect since the functions should not be able to be modified, only extended
  * Correct class diagram:
  
 
  ![](https://yuml.me/3ace55b5.jpg)
  
  This fixes the class by having the function be extended through inheritance rather than directly modified
  
* Liskov Substitution Principle
  * Objects in a program should be replaceable with subtypes and the program should work fine.
  * Incorrect class diagram:
  
  ![](https://yuml.me/7a5f8fa8.jpg)
  
  This would not work since the extension cannot replace the original
  * Correct class diagram:
  
  ![](https://yuml.me/4a803d8b.jpg)
  
  This fixes the class since the subtype can replace the original easily, it just results in a slightly different output
  
* Interface Segregation Principle
  * It is better to develop client specific interfaces, rather than having one general purpose interface
  * Incorrect class diagram
  
  ![](https://yuml.me/ce177bc3.jpg)
  
  This is incorrect since the single interface does all of the operations
  * Correct class diagram
  
  ![](https://yuml.me/92258fa2.jpg)
  
  This is correct since the interfaces are specific to the operations
  
* Dependency Inversion Principle
  * Depend on abstractions not concretions
  
  * Incorrect class diagram
  
  ![](http://yuml.me/340fbe76.jpg)
  
  This is incorrect since the dependency is done through a concretion
  * Correct class diagram
  
  ![](https://yuml.me/2d0dac66.jpg)
  
  This is correct since the dependency is done through an abstraction
  
  
