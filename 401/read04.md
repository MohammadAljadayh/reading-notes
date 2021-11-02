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
