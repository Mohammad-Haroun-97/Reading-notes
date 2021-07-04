# Expressions and operators    

This chapter describes JavaScript's expressions and operators, including assignment, comparison, arithmetic, bitwise, logical, string, ternary and more.    
# Operators :
## Assignment operators 

| Name | Shorthand operato |  Meaning| 
|-----------------|:-------------|:---------------:|
| Assignment |x = y	| x = y      | 
| Addition assignment    |  	 	x += y      |  x = x + y     | 
| Subtraction assignment    |    	x -= y     |         	x = x - y     | 
|Remainder assignment|x *= y | 	x = x * y|
|Exponentiation assignment|	x %= y|	x = x % y|
|Left shift assignment|	x **= y|	x = x ** y|
|Right shift assignment|	x <<= y|	x = x << y|
|Unsigned right shift assignment|	x >>= y|	x = x >> y|
|Bitwise AND assignment|	x &= y|	x = x & y|

## Comparison operators

| Operator |Description | Examples returning true| 
|-----------------|:-------------|:---------------:|
| Equal (==) |Returns true if the operands are equal.|	3 == var1  |
| Not equal (!=)    |  	 		Returns true if the operands are not equal.     | var1 != 4| 
|Strict equal (===)   |  Returns true if the operands are equal and of the same type. See also Object.is and sameness in JS. |         	3 === var1    | 
|Strict not equal (!==)|Returns true if the operands are of the same type but not equal, or are of different type.| 	var1 !== "3"|
|Greater than (>)|	Returns true if the left operand is greater than the right operand.|	var2 > var1|
|Greater than or equal (>=)|	Returns true if the left operand is greater than or equal to the right operand.|var2 >= var1|
|Less than (<)|	Returns true if the left operand is less than the right operand.var1 < var2|	var1 < var2|
|Less than or equal (<=)|Returns true if the left operand is less than or equal to the right operand.|	var1 <= var2|

## Arithmetic operators
* Remainder (%)	Binary operator. Returns the integer remainder of dividing the two operands.	12 % 5 returns 2.  
* Increment (++)	Unary operator. Adds one to its operand. If used as a prefix operator (++x), returns the value of its operand after adding one; if used as a postfix operator (x++), returns the value of its operand before adding one.	If x is 3, then ++x sets x to 4 and returns 4, whereas x++ returns 3 and, only then, sets x to 4.  
* Decrement (--)	Unary operator. Subtracts one from its operand. The return value is analogous to that for the increment operator.	If x is 3, then --x sets x to 2 and returns 2, whereas x-- returns 3 and, only then, sets x to 2.  
* Unary negation (-)	Unary operator. Returns the negation of its operand.	If x is 3, then -x returns -3.
Unary plus (+)	Unary operator. Attempts to convert the operand to a number, if it is not already.	
+"3" returns 3.

+true returns 1.

### Exponentiation operator (**)	Calculates the base to the exponent power, that is, base^exponent	2 ** 3 returns 8.
10 ** -1 returns 0.1.


## Logical operators
* Operator	Usage	Description  
* Logical AND (&&)	expr1 && expr2	Returns expr1 if it can be converted to false; otherwise, returns expr2. Thus, when used with Boolean values, && returns true if both operands are true; otherwise, returns false.  
* Logical OR (||)	expr1 || expr2	Returns expr1 if it can be converted to true; otherwise, returns expr2. Thus, when used with Boolean values, || returns true if either operand is true; if both are false, returns false.  
* Logical NOT (!)	!expr	Returns false if its single operand that can be converted to true; otherwise, returns true.





  
    
      
 # Loops and iteration
 
 Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.

You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:


for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
}
## The statements for loops provided in JavaScript are: 

* for statement  
* do...while statement
* while statement
* labeled statement
* break statement
* continue statement
* for...in statement
* for...of statement  

## for statement
A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

A for statement looks as follows:

for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement
Copy to Clipboard
***When a for loop executes, the following occurs:***  

1. The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
2. The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)
3. The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.
4. If present, the update expression incrementExpression is executed.
Control returns to Step 2.

## while statement
A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

while (condition)
  statement
Copy to Clipboard
If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

To execute multiple statements, use a block statement ({ ... }) to group those statements.

***Example 1***
The following while loop iterates as long as n is less than 3:

*let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}*







      
