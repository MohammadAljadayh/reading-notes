# AWS: API, Dynamo and Lambda


##  What are serverless functions? 

Serverless computing is a cloud computing execution model in which the cloud provider allocates machine resources on demand, taking care of the servers on behalf of their customers. "Serverless" is a misnomer in the sense that servers are still used by cloud service providers to execute code for developers

##  If you were to create a system that emulated Lambda functions, how would you do it?

I would create some sort of system built off event listeners. These event listeners would listen for trigger events, and fire off functions once those events are executed.

## Describe how a CDN works

A CDN is a network of servers that distributes content from an “origin” server throughout the world by caching content close to where each end user is accessing the internet via a web-enabled device. The content they request is first stored on the origin server and is then replicated and stored elsewhere as needed.

Term Definition

`Serverless`   
 computing is a cloud computing execution model in which the cloud provider allocates machine resources on demand, taking care of the servers on behalf of their customers. "Serverless" is a misnomer in the sense that servers are still used by cloud service providers to execute code for developers  

`Cloud Storage`   
Cloud storage is a model of computer data storage in which the digital data is stored in logical pools, said to be on "the cloud". The physical storage spans multiple servers (sometimes in multiple locations), and the physical environment is typically owned and managed by a hosting company. 


`CDN` 
  
   A CDN is a network of servers that distributes content from an “origin” server throughout the world by caching content close to where each end user is accessing the internet via a web-enabled device. The content they request is first stored on the origin server and is then replicated and stored elsewhere as needed


# Preview
> Which 3 things had you heard about previously and now have better clarity on?
- DynamoDB
- the cloud
- CDN 
> Which 3 things are you hoping to learn more about in the upcoming lecture/demo? 
- Aws
- Autoscaling
- Serverless Functions
> What are you most excited about trying to implement or see how it works?
-  Cloud Storage 

---------------------------------------------------------------------
### Amazon API Gateway  
Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests.  

### How does API Gateway work?

API Gateway sits between the backend services of your API and your API’s users, handling the HTTP requests to your API endpoints and routing them to the correct backends. It provides a set of tools that help you manage your API definitions and the mappings between endpoints and their respective backend services. It can also generate API references from your definitions and make them available to your users as API documentation.

### What is DynamoDB?
DynamoDB is a hosted NoSQL database offered by Amazon Web Services (AWS). 

It offers:

- reliable performance even as it scales;
- a managed experience, so you won't be SSH-ing into servers to upgrade the crypto libraries;
- a small, simple API allowing for simple key-value access as well as more advanced query patterns.


- Amazon DynamoDB is a fully managed, serverless, key-value NoSQL database designed to run high-performance applications at any scale. DynamoDB offers built-in security, continuous backups, automated multi-region replication, in-memory caching, and data export tools. 

![](https://d1.awsstatic.com/product-marketing/DynamoDB/product-page-diagram_Amazon-DynamoDB.a8a97936b804de5abb83fec9329acd03dec33332.png)



### Dynamoose  

is a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose, which means if you are coming from Mongoose the syntax will be very familar  

### Key Features#
- Type safety
- High level API
- Easy to use syntax
- Ability to transform data before saving or retrieving documents
- Strict data modeling (validation, required attributes, and more)
- Support for DynamoDB Transactions
- Powerful Conditional/Filtering Support
- Callback & Promise support
