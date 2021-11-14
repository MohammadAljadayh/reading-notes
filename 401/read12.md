# Event Driven Applications

## Why is access control important?

Access controls limit access to information and information processing systems. When implemented effectively, they mitigate the risk of information being accessed without the appropriate authorisation, unlawfully and the risk of a data breach.


## Describe an application that would need access control.

Account management in canvas  there is role for the students  TA;s's and the instructor.


## What is a role used for?

The role determines which permissions the system grants to the user. 
 an application, a role is an abstract name for a group of users. ... When an application developer is creating an internal payroll website, the developer would use the same set of data for all of its corporate users, but would allow different access to the data depending on the role the user is in.


## Why is role based access control more scalable than discretionary or mandatory access control?
Role Based Access Control (RBAC), also known as Non discretionary Access Control, takes more of a real world approach to structuring access control. Access under RBAC is based on a user's job function within the organization to which the computer system bel



## Document the following Vocabulary Terms

``Authorization :``

Authorization is the function of specifying access rights/privileges to resources, which is related to general information security and computer security, and to access control in particular. More formally, "to authorize" is to define an access policy


``Role Based Access Control :``
 Role-based access control (RBAC) restricts network access based on a person’s role within an organization and has become one of the main methods for advanced access control.


`` Capabilities :``

A capability is a communicable, unforgeable token of authority. It refers to a value that references an object along with an associated set of access rights.

---------------------------------------------------------------------------
# Preview
> Which 3 things had you heard about previously and now have better clarity on?
- User Role 
- authentication & authorization 
- ACL 
> Which 3 things are you hoping to learn more about in the upcoming lecture/demo? 
- setting the role
- JWT.
- Bearer Authorization 
> What are you most excited about trying to implement or see how it works?
-  more about access control using CRUD function 

---------------------------------------------------------------------
# Event Driven Programming


- Event-Driven Programming is a logical pattern that we can choose to confine our programming within to avoid issues of complexity and collision. In this article we’re going to go over how Event-Driven Programming works and how we can make the best use of it in our Node.js projects

- Event-Driven Programming makes use of the following concepts:

1. An Event Handler is a callback function that will be called when an event is triggered.
2. A Main Loop listens for event triggers and calls the associated event handler for that event.
- Node. js uses event driven programming. It means as soon as Node starts its server, it simply initiates its variables, declares functions and then simply waits for event to occur. It is the one of the reason why Node.
![](https://image.slidesharecdn.com/eventdrivenprogramming1-130410221316-phpapp01-140921164519-phpapp02/95/event-driven-programming-nodejs-12-638.jpg?cb=1411317978 )

## Difference between Events and Callbacks: 
Although, Events and Callbacks look similar but the differences lies in the fact that callback functions are called when an asynchronous function returns its result where as event handling works on the observer pattern. Whenever an event gets fired, its listener function starts executing. Node.js has multiple in-built events available through events module and EventEmitter class which is used to bind events and event listeners.
