##  In memory storage

- ## What is a call ?

is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

- ## How many calls can happen at once?

only one function..

- ## What does LIFO mean?

LIFO: When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns
Example : 
function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();
       
- ## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

![](https://miro.medium.com/max/1400/1*rJ2sh-q1deQGGGVG5gYyIQ.png)

- ## What causes a Stack Overflow?

when there is a recursive function  without an exit point. 

- ## What is arefrence error? 

when you try to use a variable that is not declared

- ## What is a syntax error? 

when you have something that cannot be parsed in terms of syntax.

- ## What is a range error? 

Try to manipulate an object with some kind of length and give it an invalid length

- ## What is a tyep error ? 

when the types  you are trying to use or access are incompatible.

- ## What is a breakpoint?

it is a point to stop the code when the execution reaches it.

- ## What does the word ˜debugger do in your code?

to let you  see the history before reaching that breakpoint.


- for more details : 


[JavaScript call stack](https://medium.com/@Zhabskyi/javascript-call-stack-8a2cfc0fdabf)
[JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)
[JavaScript errors reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)