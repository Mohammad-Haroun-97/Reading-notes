# The JavaScript Call Stack 

## What is a â€˜callâ€™?

Â is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call)

## How many â€˜callsâ€™ can happen at once?

JavaScript can do one single thing at a time because it has only one call stack

## What does LIFO mean?

When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.


**. What is a breakpoint?**
it is a point to stop the code when the execution reaches it.

**. What does the word â€˜debuggerâ€™ do in your code?**

to let you  see the â€œhistoryâ€ before reaching that breakpoint.

[JavaScript errors reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)
[JavaScript call stack](https://medium.com/@Zhabskyi/javascript-call-stack-8a2cfc0fdabf)

## What causes a Stack Overflow?

> **A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.**

>Example:

    function callMyself(){
        callMyself();
    }


# JavaScript error messages

## Reference errors

> Called a variable will not defined.

## Syntax error

> Write a variable or reserved word by wrong way (add leter).

## Range error

> **The Range is equal 0**

## tyep error

## What causes a Stack Overflow?

> **A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.**

>Example:

    function callMyself(){
        callMyself();
    }
    .![](https://media.geeksforgeeks.org/wp-content/uploads/20201213102457/global.png)


# JavaScript error messages

## Reference errors

> Called a variable will not defined.

## Syntax error

> Write a variable or reserved word by wrong way (add leter).

## Range error

> **The Range is equal 0**

## tyep error
