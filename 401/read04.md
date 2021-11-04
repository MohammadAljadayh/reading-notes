# Express REST API


### Name 3 real world use cases where you’d want to change the request with custom middleware

- Handling error.
- validator of user with his data .
-  payment method security.

### True or false: The route handler is middleware?

- False


###  In what ways can a middleware function end the process and send data to the browser?

 - When there is an error in request 
 -  When the process is finish


### At what point in the request lifecycle can you “inject” middleware?

- befor  and after the route handler

### ”What can cause express to error with “Request headers sent twice, cannot start a second response”

- send more than one request to the server ->  interupt between this requests -> so the server will dell with this requests by send an error. 

### Document the following Vocabulary Terms

``Middleware``

Express middleware are functions that execute during the lifecycle of a request to the Express server. Each middleware has access to the HTTP request and response for each route (or path) it's attached to. ... This “chaining” of middleware allows you to compartmentalize your code and create reusable middleware.

``Request Object``

Short for request , the req object is one half of the request and response cycle to examine calls from the client side, make HTTP requests, and handle incoming data whether in a string or JSON object 

``Response Object``

Response — The res object represents the HTTP response that an Express app sends when it gets an HTTP request. In this documentation and by conventio

``Application Middleware``

Middleware functions are functions that have access to the request object ( req ), the response object ( res ), and the next function in the application's request-response cycle.

``Routing Middleware``

Routing defines the way in which the client requests are handled by the application endpoints.


``Test Driven Development``

Test-driven development (TDD) is a software development process relying on software requirements being converted to test cases before software is fully developed

``Behavioral Testing``

Behavioural Testing is a testing of the external behaviour of the program, also known as black box testing. It is usually a functional testing 

--------------------------------------------------------------------------
# Preview
> Which 3 things had you heard about previously and now have better clarity on?
- RESTful API 
- Sql lite 
- Mongoose 
> Which 3 things are you hoping to learn more about in the upcoming lecture/demo? 
- CRUD APP testing 
- Express Route
- SQL App tools 
> What are you most excited about trying to implement or see how it works?
- working with big database with multi of tabels 

-------------------------------------------------------
## Classes
Classes are a template for creating objects. They encapsulate data with code to work on that data. Classes in JS are built on prototypes but also have some syntax and semantics that are not shared with ES5 class-like semantics.

## Defining classes
Classes are in fact "special functions", and just as you can define function expressions and function declarations, the class syntax has two components: class expressions and class declarations.

### Class declarations : 

```
class Rectangle {
  constructor(height, width) {
    this.height = height;
    this.width = width;
  }
}
``` 

### Class expressions : 
-A class expression is another way to define a class. Class expressions can be named or unnamed. The name given to a named class expression is local to the class's body. However, it can be accessed via the name property.  


### Class body and method definitions 
- Strict mode : The body of a class is executed in strict mode 
- Constructor : The constructor method is a special method for creating and initializing an object created with a class. There can only be one special method with the name "constructor" in a class. 
 - Static initialization blocks : Class static initialization blocks allow flexible initialization of class static properties including the evaluation of statements during initialization, and granting access to private scope.

 ### Static methods and properties : 
 The static keyword defines a static method or property for a class. Static members (properties and methods) are called without instantiating their class and cannot be called through a class instance. Static methods are often used to create utility functions for an application, whereas static properties are useful for caches, fixed-configuration, or any other data you don't need to be replicated across instances.

----------------------------------------------------------------------------------

## Routing 
- Routing refers to how an application’s endpoints (URIs) respond to client requests. For an introduction to routing. 
- Route methods  A route method is derived from one of the HTTP methods, and is attached to an instance of the express class.
- Route paths : Route paths, in combination with a request method, define the endpoints at which requests can be made. Route paths can be strings, string patterns, or regular expressions.
- Route parameters : Route parameters are named URL segments that are used to capture the values specified at their position in the URL
- Route handlers : You can provide multiple callback functions that behave like middleware to handle a request

### Response methods : 
The methods on the response object (res) in the following table can send a response to the client, and terminate the request-response cycle. If none of these methods are called from a route handler, the client request will be left hanging 
- app.route() : You can create chainable route handlers for a route path by using app.route().
- express.Router : Use the express.Router class to create modular, mountable route handlers. A Router instance is a complete middleware and routing system; for this reason, it is often referred to as a “mini-app”.

-----------------------------------------------------------------------------------------------------
### With the inclusion of the Express 4.0 Router, we are given more flexibility than ever before in defining our routes.  we can:

- Use express.Router() multiple times to define groups of routes
- Apply the express.Router() to a section of our site using app.use()
- Use route middleware to process requests
- Use route middleware to validate parameters using .param()
- Use app.route() as a shortcut to the Router to define multiple requests on a route
- With all the ways we can define routes, I'm sure that our applications will benefit going forward. Sound off in the comments if you have any questions or suggestions 

### For More Details : 
[Learn to Use the New Router in ExpressJS 4.0](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)