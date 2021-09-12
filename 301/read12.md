# CRUD

- ### 1.In your own words, describe what each group of status code represents:
- 100 - 199Permalink
These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client. Like using a different protocol or telling the client that its request will fail before they start sending the body.

- 200 - 299Permalink
These are the success codes. They tell the client that its request was accepted. In case of asynchronous processing of a request (202), this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.

- 300 - 399Permalink
These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore. This can have multiple reasons, be temporary or permanent, but the client has to issue a request to the new location.

- 400 - 499Permalink
These are the client error codes. They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, etc. A client is sending incorrect input and should confirm the input parameters are correct before retrying the request.

- 500 - 599Permalink
These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server. These errors can be temporary or permanent. Usually it’s best for the client to retry the same request.

- ### 2.What is a status code 202?

In case of asynchronous processing of a request (202), this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.


- ### 3.What is a status code 308?

Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore. 

- ### 4.What code would you use if an update didn’t return data to a client?

204 

- ### 5.What code would you use if a resource used to exist but no longer does?

410 .

- ### 6.What is the ‘Forbidden’ status code?

403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

![](https://image.slidesharecdn.com/restapidesign-140729104120-phpapp02/95/rest-api-design-9-638.jpg?cb=1406675992)
------------------------------------------------------------------------------------------------------ 



- ### 1.Why do we need to pull our MongoDB database string out of our server and put it into our .env?

We want to put something there that is not localhost and to protect our information.

- ### 2.What is middleware?

Middleware is software that provides common services and capabilities to applications outside of what's offered by the operating system.

- ### 3.What does app.use(express.json()) do?

express. json() is a method inbuilt in express to recognize the incoming Request Object as a JSON Object. This method is called as a middleware in your application using the code: app

- ### 4.What does the /:id mean in a route?

 parameter that Gives access to whatever the user passes in.

- ### 5.What is the difference beween PUT and PATCH?

PUT is a method of modifying resource where the client sends data that updates the entire resource. It is used to set an entity’s information completely.
Unlike PUT, PATCH applies a partial update to the resource.

- ### 6.How do you make a defalut value in a schema?

Declaring Defaults in Your Schema ... Your schemas can define default values for certain paths
 
- ### 7.What does a 500 error status code mean?

The HTTP status code 500 is a generic error response. It means that the server encountered an unexpected condition that prevented it from fulfilling the request. This error is usually returned by the server when no other error code is suitable

- ### 8.What is the difference between a status 200 and a status 201?

 200 - request received and is processing.
 
 201 - request received, was successful.

![](https://drek4537l1klr.cloudfront.net/sholmes2/Figures/06fig01_alt.jpg)
 ### For More Details 
 
 - [mongodb](https://www.mongodb.com/live/register?tck=docs) 
- [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

