# Grant Zeigler - Question 5


* Single Responsibility Principle
  * Each class should have a single responsibility, and that responsibility should be encapsulated by that class
  * Incorrect class diagram:
  
  ![](https://yuml.me/ab86ad62.jpg)
  
  This violate the Principle by having a single class with multiple responsibilities
  
  * Corret class diagram: 
  
  ![](http://yuml.me/de1b5efa.jpg)
  
  This fixes the class by having each class only have one responsibility
* Open/Closed Principle
  * Software pieces, such as classes and and functions, should be able to be extended but not modified.
* Liskov Substitution Principle
  * Objects in a program should be replaceable with subtypes and the program should work fine.
* Interface Segregation Principle
  * It is better to develop client specific interfaces, rather than having one general purpose interface
* Dependency Inversion Principle
  * Depend on abstractions not concretions
