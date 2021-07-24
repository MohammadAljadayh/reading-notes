# JS Debugging 

- If you understand execution contexts (which have two
stages) and stacks, you are more likely to find the error
in your code.
- Debugging is the process of finding errors. It involves a
process of deduction.
- The console helps narrow down the area in which the
- error is located, so you can try to find the exact error.
- JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error.
- If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback. 

![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Debugging-and-Testing-1200x720.png)

#### ORDER OF EXECUTION 

To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks

#### EXECUT.ION CONTEXTS 
The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope. 

#### UNDERSTANDING SCOPE  

In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object. 


#### ERROR OBJECTS 

Error objects can help you find where your mistakes are
and browsers have tools to help you read them.

- HOW TO DEAL WITH ERRORS   
 
 DEBUG THE SCRIPT TO FIX ERRORS 
  HANDLE ERRORS GRACEFULLY  

  #### A DEBUGGING  WORKFLOW 
  Debugging is about deduction: eliminating potential causes of an error.
Here is a workflow for techniques you will meet over the next 20 pages.
Try to narrow down where the problem might be, then look for clues. 

#### TYPING IN THE CONSOLE IN CHROME 

You can also just type code into the console
and it will show you a result. 

#### BREAKPOINTS

You can pause the execution of a script on any
line using breakpoints. Then you can check the
values stored in variables at that point in time.

#### TRY, CATCH, FINALLY 


![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Errors-1200x720.jpg)


----------------------------------

