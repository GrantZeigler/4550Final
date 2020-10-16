# Question 2 -- Grant Zeigler


### Batch Sequential Architecture



### Pipe and Filter Architecture
* Two parts to these systems:
  * Filters: Subsystems that only know the content and format of the data being recieved.
    * Use this information to perform operations on the data
    * Know nothing about any other filter
    * Can execute at the same tim eas other filters
  * Pipes: Associations between the filters that send data from place to place 
    * Control synchronous execution of filters
  

