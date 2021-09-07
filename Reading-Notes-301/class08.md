# Functional Programming Concepts 
![1](https://devopedia.org/images/article/21/5929.1491735653.png)
## What is functional programming?
In computer science, functional programming is a programming paradigm where programs are constructed by applying and composing functions. ... When a pure function is called with some given arguments, it will always return the same result, and cannot be affected by any mutable state or other side effects.

## What is a pure function and how do we know if something is a pure function?
The definition of a pure function is: The function always returns the same result if the same arguments are passed in. It does not depend on any state, or data, change during a program's execution. It must only depend on its input arguments.


- ### *What are the benefits of a pure function?*
### When the code is written using the functional programming style, a capable compiler is able to:
### 1- Memorize the results
### 2- Parallelize the instructions
### 3- Wait for evaluating results
<br>

![functional](https://www.xenonstack.com/hubfs/xenonstack-functional-programming.png)


- ### *What is immutability?*
### Variables are immutable i.e. it isnâ€™t possible to modify a variable once it has been initialized. Though we can create a new variable, modifying existing variables is not allowed.
<br>

- ### *What is Referential transparency?*
### An expression, in a program, may be replaced by its value (or anything having the same value) without changing the result of the program. This implies that methods should always return the same value for a given argument, without having any other effect.

## What does the word â€˜requireâ€™ do?

Â isÂ intended to add separate pieces of code (â€œmodulesâ€) to the current scope, a featureÂ 

## How do we bring another module into the file the we are working in?

By using import name and the path of the module

