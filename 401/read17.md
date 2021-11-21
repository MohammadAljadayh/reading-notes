# AWS: Cloud Servers

### Review, Research, and Discussion

###  Describe the Web-Request-Response-Cycle

The request/response cycle traces how a user's request flows through the app. Understanding the request/response cycle is helpful to figure out which files to edit when developing an app (and where to look when things aren't working)

### Explain what a “server” is, as it relates to the WRRC

The client (usually a browser) opens a connection to the server and sends a request. The server processes the request, generates a response, and closes the connection if it finds a Connection: Close header. ... Headers are typically only sent for POST and PUT methods.


###  What does it mean to “deploy” an application? 

Application Deployment (also referred to as Software Deployment) is the process of installing, configuring, and enabling a specific application or set of applications, usually through an application manager (app manager) or software management system, to a specific URL on a server.  

 

`A server`  
 is a computer or system that provides resources, data, services, or programs to other computers, known as clients, over a network. In theory, whenever computers share resources with client machines they are considered servers. ... This means that a device could be both a server and a client at the same time   

`Pub/Sub,`  

 which stands for Publisher/Subscriber, allows services to communicate asynchronously, with latencies on the order of 100 milliseconds. 




# Preview
> Which 3 things had you heard about previously and now have better clarity on?
- Socket
- authentication & authorization 
- ACL 
> Which 3 things are you hoping to learn more about in the upcoming lecture/demo? 
- Aws
- Socket.io
- OSI Model 
> What are you most excited about trying to implement or see how it works?
-  AWS 

---------------------------------------------------------------------

Amazon Web Services offers reliable, scalable, and inexpensive cloud computing services. Free to join, pay only for what you use.  

Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale cloud computing easier for developers. Amazon EC2’s simple web service interface allows you to obtain and configure capacity with minimal friction. It provides you with complete control of your computing resources and lets you run on Amazon’s proven computing environment.  

Reliable, scalable, infrastructure on demand
- Increase or decrease capacity within minutes, not hours or days
- SLA commitment of 99.99% availability for each Amazon EC2 region. Each region consists of at least 3 availability zones
- The AWS Region/AZ model has been recognized by Gartner as the recommended approach for running enterprise applications that require high availability  

![](https://d1.awsstatic.com/products/EC2/Spot/product-page-diagram_EC2-Spot-Instances.6c3c51f4c6a28cd71d8fef8231510b5619e84eea.png)