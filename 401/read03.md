# Express

## What’s the difference between PUT and PATCH?

- The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.

## Provide links to 3 services or tools that allow you to “mock” an API for development like json-server

- [postman](https://www.postman.com/).
- [stoplight](https://stoplight.io/).
- [Nock](https://github.com/nock/nock).

## Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?
1. apiDocjs: Inline Documentation for RESTful web APIs. It creates a documentation from API annotations in your source code. It includes a default template which uses handlebars, Bootstrap, RequireJS and jQuery for the output of the generated apidata.js and apiproject.js as a html-page; 

-  Swagger status Codes:

    #### responses:
        - '200':
        description: OK
        - '400':
          description: Bad request. User ID must be an integer and larger than 0.
        - '401':
          description: Authorization information is missing or invalid.
        - '404':
          description: A user with the specified ID was not found.
        - '5XX':
          description: Unexpected error. 

2. Swagger Inspector: Test and Document Your APIs With Ease. It is a free cloud-based API testing and documentation tool to simplify the validation of any API and generate its corresponding OpenAPI documentation.


 - APIDoc.js HTTP status Codes:

    - 200	Successful request and response.
    - 400	Malformed parameters or other bad request

## Compare and contrast SOAP and ReST

The difference is:
-  SOAP is a XML-based message protocol, while REST is an architectural style.
-  SOAP uses WSDL for communication between consumer and provider, whereas REST just uses XML or JSON to send and receive data. 
- SOAP invokes services by calling RPC method, REST just simply calls services via URL path.

## Document the following Vocabulary Terms

``Web Server``

A web server is software and hardware that uses HTTP (Hypertext Transfer Protocol) and other protocols to respond to client requests made over the World Wide Web. The main job of a web server is to display website content through storing, processing and delivering webpages to users.

``Express``

Express, is a back end web application framework for Node. js, released as free and open-source software under the MIT License. It is designed for building web applications and APIs.

``Routing``

refers to determining how an application responds to a client request to a particular endpoint, which is a URI (or path) and a specific HTTP request method (GET, POST, and so on).

Each route can have one or more handler functions, which are executed when the route is matched

``WRRC``

Web request response cycle, The request/response cycle traces how a user's request flows through the app. Understanding the request/response cycle is helpful to figure out which files to edit when developing an app (and where to look when things aren't working).
------------------------------------------------------------------------------------------------------
# Preview
> Which 3 things had you heard about previously and now have better clarity on?
- ore About status Codes
> Which 3 things are you hoping to learn more about in the upcoming lecture/demo? 
- More A bout Middle Ware 
- SQL as DataBase 
- RESTful API
> What are you most excited about trying to implement or see how it works?
- CRUD APP WITH TESTING UNIT 
