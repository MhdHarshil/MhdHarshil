## Runtime :

Exploring the runtime of algorithms is important because using an inefficient algorithm could make our program slow or even unworkable.

By understanding algorithm runtime we can choose the right algorithm for our need, and we can make our programs run faster and handle larger amounts of data effectively.
___
## Actual Runtime : 

When considering the [[#Runtime]] for different algorithms, we will **not** look at the actual time an implemented algorithm uses to run, and here is why.

If we implement an algorithm in a programming language, and run that program, the actual time it will use depends on many factors:

* the programming language used to implement the algorithm
* how the programmer writes the program for the algorithm
* the compiler or interpreter used so that the implemented algorithm can run
* the hardware on the computer the algorithm is running on
* the operating system and other tasks going on on the computer
* the amount of data the algorithm is working on
_______
## Time Complexity :

To evaluate and compare different algorithms, instead of looking at the [[#Actual Runtime]] for an algorithm, it makes more sense to use something called [[#Time Complexity]]

[[#Time Complexity]] is the number of operations needed to run an algorithm on large amounts of data. And the number of operations can be considered as time because the computer uses some time for each operation.

____________________________________________________________


## "One Operation"

When talking about "operations" here, "one operation" might take one or several CPU cycles, and it really is just a word helping us to abstract, so that we can understand what time complexity is, and so that we can find the time complexity for different algorithms.

*One operation in an algorithm can be understood as something we do in each iteration of the algorithm, or for each piece of data, that takes constant time.*

