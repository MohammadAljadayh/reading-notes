# FUNCTIONAL PROGRAMMING


- ## What is functional programming? 
Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data  

- ##  What is a pure function and how do we know if something is a pure function? 

A pure function is a function which:  

- It returns the same result if given the same arguments (it is also referred as deterministic)
- It does not cause any observable side effects

- ## What are the benefits of a pure function?  
- they are immediately testable. 

- ##  What is immutability?
When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.  so immutability is important to make our functions more consistent and predictable. The idea is to build a new collection with all absolute values 

- ##  What is Referential transparency? 
in simpel  pure functions + immutable data = referential transparency . 


![](https://ahsensaeed.com/wp-content/uploads/2019/11/11yVFdiXsp3u40OZfCrG14A.png)

- ## What is a module? 
Module in Node. js is a simple or complex functionality organized in single or multiple JavaScript files which can be reused throughout the Node. ... Each module in Node. js has its own context, so it cannot interfere with other modules or pollute global scope. Also, each module can be placed in a separate . 


- ## What does the word ‘require’ do? 

The basic functionality of require is that it reads a JavaScript file, executes the file, and then proceeds to return the exports object. 

- ##  How do we bring another module into the file the we are working in?
- To include functions defined in another file in Node.js, we need to import the module. we will use the require keyword at the top of the file.

- The result of require is then stored in a variable which is used to invoke the functions using the dot notation.

- To see that in action, let’s import the lib.js module by requiring it inside the main.js file and invoke the add() function with dot notation. 

- ## What do we have to do to make a module available? 

Local/File-based modules: It define the Node modules within a file in our application and is used within our application.

Core modules: The core modules are inbuilt modules in Node. js. 

Third-party modules: Third-party modules are the external Node modules.


![](http://www.lucedigitale.com/blog/wp-content/uploads/2020/04/nodejs-require.png)

## for More Details . 

### [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

### [Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)
