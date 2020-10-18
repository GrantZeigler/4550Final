# Question 2 -- Grant Zeigler


### Batch Sequential Architecture
* Uses a few stand alone systems that are fairly large
* Must be done in a sequential order
* All share one file, making the system tightly coupled

* Benefits:
  * Simple implementation due to linear structure
  * Good for transforming a single file multiple times
* Disadvantages:
  * Can't run multiple systems at the same time
  * Not very flexible
  * No realtime feedback

![](https://yuml.me/8c2a50b4.jpg)

* Used in situations where the classes need some knowledge of what needs to be done in a specific instance. Also used when a single class needs to do multiple operations on the same data.
  
### Pipe and Filter Architecture
* Two parts to these systems:
  * Filters: Subsystems that only know the content and format of the data being recieved.
    * Use this information to perform operations on the data
    * Know nothing about any other filter
    * Can execute at the same tim eas other filters
  * Pipes: Associations between the filters that send data from place to place 
    * Control synchronous execution of filters
  
* Benefits:
  * Easy to reconfigure
  * Systems can be executed at the same time
  * Each system does not know anything about the other systems
* Disadvantages:
  * All data must be transfered through the pipes
  
![](https://yuml.me/0b0c5194.jpg)

* Used in situations where multiple small operations are being done on the data, when it is done with one operation it is passed on to the next. This is also used in situations where the different operations need to be ran at the same time.
