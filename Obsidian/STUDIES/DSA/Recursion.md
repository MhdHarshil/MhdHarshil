## What is Recursion??

A Way of a Solving a Problem by having a Function calling itself

- Performing the same operations's multiple with different input's
- In every time we try smaller inputs to make the problem smaller 
- Base Condition in needed to stop the recursion, otherwise infinite loop will occur.

## Why Recursion??

1. Recursive thinking is really important in programming and it helps you to breakdown big problem's into smaller one's. If you can divide the problem into similar sub problem's,you can use [[Recursion]]
2. The prominent usage of recursion in datastrucures like tree and graphs
3. Used in many Algorithms (Divide and conquer, greedy etc..)

## How Recursion Work's??

[YouTube](https://youtu.be/-5ydpDJ6bHM?si=ohXv_l4QPBFz5AeP)
### Condition's:
1. A method calling itself
2. Exit from infinite loop
### Basic Syntax:
	def Recur(para):
		if base condition:
			return value
		else:
			Recur(modified para)
Stack memory is used for managing recursive call 

## Recursion VS Iteration

![[Pasted image 20241006130545.png]]



## When to Use / Avoid Recursion??

### When to use it??

*  When we can easily breakdown a into similar sub problem's
* When we are fine with extra overhead (both time and space)
* When we are need a quick working solution instead of an efficient one
* Tree Traversal

### When to Avoid Recursion??

* When we cant's easily breakdown a problem into similar subproblem
* If the time and Space complexity matter's for us

## Write Recursion in 3 Steps

## Problem : Factorial of a Number

* #### Step 1: ![[Screenshot 2024-10-06 135541.png]]
* #### Step 2:![[Screenshot 2024-10-06 135623.png]]
* #### Step 3:![[Screenshot 2024-10-06 135648.png]]  
```python
def rec(n):  
    assert n>=0 and int(n)==n, 'Number must be a positive integer'  
    if n == 0:  
         return 1  
    else:  
         return n * rec(n-1)
```



## Find n'th Fibonacci Number??

### Sequence of Number's in Which each number is the sum of two preceding one's and the sequence start's from 0 and 1

### 0,1,1,2,3,5,8,13,21,34,55...


