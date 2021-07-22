# Error Handling and Debugging

JavaScript can be hard to learn and everyone makes mistakes when writing it. When you are writing JavaScript, do not expect to write it perfectly the first time. Programming is like problem solving: you are given a puzzle and not only do you have to solve it, but you also need to create the instructions that allow the computer to solve it.
   
     
      
     Example :
To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run:

![Drag Racing](https://www.oreilly.com/library/view/javascript-and-jquery/9781118531648/images/p452-001.jpg)

1. The greeting variable gets its value from the
greetUser() function.
2. greetUser() creates the message by combining
the string 'He 11 o ' with the result of getName ().
3. getName () returns the name to greetUser() .
2. greetUser() now knows the name, and combines
it with the string. It then returns the message to the
statement that ca lled it in step 1.
1. The va lue of the greeting is stored in memory.
4. This greeting variable is written to an alert box.

# ERROR OBJECTS

| OBJECT | DESCRIPTION | 
|-----------------|:-------------|
| Error | Generic error - the other errors  are all based upon this error  | 
| Syntax Error    | Syntax has not been followed        | 
| Ref erenceError    | Tried to reference a variable that is not declared within scope        | 
| TypeError     |   An unexpected data type that cannot be coerced           |  
|Range Error        |   Numbers not in acceptable range           |             


## Syntax Error
SYNTAX IS NOT CORRECT
This is caused by incorrect use of the rules of the
language. It is often the result of a simple typo.
## EX : 
MISMATCHING OR UNCLOSED QUOTES
document .write ("Howdyl );
SyntaxError: Unexp ec t ed EOF
## EX : 
MISSING CLOSING BRACKET
document .getElementByid('page' I
SyntaxErr or : Expected token ' ) '
## EX :  
MISSING COMMA IN ARRAY
Would be same for missing] at the end
var l ist = ['Item 1', 'Item 2 ' l 'rtem 3'];
SyntaxError: Expected token ']'
## EX :  
MALFORMED PROPERTY NAME
It has a space but is not surrounded by quote marks
user = { f i rstl name: "Ben", lastName: "Lee"};
Synt axError: Expected an identifier but
found 'name ' instead

# ReferenceError
***VARIABLE DOES NOT EXIST
This is caused by a variable that is not declared or is
out of scope.***
* VARIABLE IS UNDECLARED  
  

var wi dth = 12 ;
## var area = width * height ;
ReferenceError: Can 't find variable:
height
* NAMED FUNCTION IS UNDEFINED  
  

## document.write ( randomFunction() ) ;  

ReferenceError: Can't find variable :
randomFunction

# EvalError
***INCORRECT USE OF eval() FUNCTION***  
  

The eva l () function evaluates text through the
interpreter and runs it as code (it is not discussed
in this book). It is rare that you would see this type
of error, as browsers often throw other errors when
they are supposed to throw an Eva 1 Error


# URI Error
***INCORRECT USE OF URI FUNCTIONS***  
  

If these characters are not escaped in URls, they will
cause an error: / ? & I : ;
CHARACTERS ARE NOT ESCAPED
## EX : 

decodeURI('http: //bbc . com/ news . phpll?a=l') ;
URlError: URI error


# Type Error

***VALUE IS UNEXPECTED DATA TYPE
This is often caused by trying to use an object or
method that does not exist.***
## EX : 
INCORRECT CASE FOR document OBJECT
 Document.write ( 'Oops! ');
TypeError: 'undefined' is not a funct ion
(eval uating 'Document.write('Oops! ')')
## EX : 
INCORRECT CASE FOR write() METHOD
document. Write('Oops ! ') ;
TypeError: 'undefined' is not a function
(evaluating 'document.Write( 'Oops! ') ')
## EX : 
METHOD DOES NOT EXIST
var box = {};
box .@Mi}id;
II Create empty object
II Try to access getArea()
TypeError: 'undefined ' is not a function
(evaluating 'box.getArea()')
## EX : 

DOM NODE DOES NOT EXIST
var el = document .getElementByid( 'z') ;
el.innerHTML = 'Mango';
TypeError: 'null' is not an object
(evaluating 'el .innerHTML = 'Mango'')  

# RangeError
***NUMBER OUTSIDE OF RANGE
If you call a function using numbers outside of its
accepted range.***
## EX : 
CANNOT CREATE ARRAY WITH -1 ITEMS
var anArray = new Array(~);
RangeError : Array si ze is not a smal l
enough positive integer
## EX :  
  

NUMBER OF DIGITS AFTER DECIMAL IN
tofhed() CAN ONLY BE 0-20
var price = 9.99;
price.toFixed( fJI);
RangeError: toFixed() argument must be
between 0 and 20  
## EX :  
  

NUMBER OF DIGITS IN toPrecision() CAN
ONLY BE 1-21
num = 2.3456;
num.toPrecisi on(flJ ) ;
RangeError: toPrecision() argument must
be between 1 and 21     



# NaN
***NOT AN ERROR
Note: If you perform a mathematical operation using
a value that is not a number, you end up with the
value of NaN, not a type error.***
## EX : 
NOT A NUMBER
var t otal = 3 * lilllJil;
ERROR  
  
# A DEBUGGING WORKFLOW 
***Debugging is about deduction: eliminating potential causes of an error.
Here is a workflow for techniques you will meet over the next 20 pages.
Try to narrow down where the problem might be, then look for clues.***

## WHERE IS THE PROBLEM?
**First, should try to can narrow down the area where
the problem seems to be. In a long script, this is
especially important.** 

1. Look at the error message, it tells you:
• The relevant script that caused the problem.
• The line number where it became a problem for
the interpreter. (As you will see, the cause of
the error may be earlier in a script; but this is the
point at which the script could not continue.)
• The type of error (although the underlying cause
of the error may be different).
2. Check how far the script is running.
Use tools to write messages to the console to tell
how far your script has executed.
3. Use breakpoints where things are going wrong.
They let you pause execution and inspect the va lues
that are stored in variables.
