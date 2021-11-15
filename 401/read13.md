# Socket.io

## What is the benefit of transforming data into packets? 


TDM-based networks must transform into packet-based networks to meet the demands of pervasive data-centric applications and services. Packet-based networks not only enable new innovations, services, and business opportunities, they are also the most cost-effective, efficient, and scalable networks for content delivery.

## UDP is often refereed to as a connectionless protocol. Why is this?

UDP is a connectionless protocol. No connection needs to be established between the source and destination before you transmit data. UDP does not have a mechanism to make sure that the payload is not corrupted.

## Can a socket server application have multiple socket connections?

Multiple connections on the same server can share the same server-side IP/Port pair as long as they are associated with different client-side IP/Port pairs, and the server would be able to handle as many clients as available system resources allow it to. 

## Can a socket connection application be connected to multiple socket servers?

A connected socket is assigned to a new (dedicated) port, so it means that the number of concurrent connections is limited by the number of ports, unless multiple sockets can share the same port 

## Can an application be both a socket server and a socket connection? 

You can not combine server and client sockets into one, because a TCP/IP connection goes from a source port to a destination port 



``Observer Pattern`` 
The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods
|
`` Listener`` 
 An event listener is a procedure in JavaScript that waits for an event to occur. The simple example of an event is a user clicking the mouse or pressing a key on the keyboard.
 
 
`Event Handler`
Events are signals fired inside the browser window that notify of changes in the browser or operating system environment. Programmers can create event handler code that will run when an event fires, allowing web pages to respond appropriately to change.

`Event Driven Programming` 
In computer programming, event-driven programming is a programming paradigm in which the flow of the program is determined by events such as user actions (mouse clicks, key presses), sensor outputs, or message passing from other programs or threads.
`Event LoopIn` 
The event loop is the secret behind JavaScript’s asynchronous programming. JS executes all operations on a single thread, but using a few smart data structures, it gives us the illusion of multi-threading. Let’s take a look at what happens on the back-end 

`Event QueueAn`
An event queue is a repository where events from an application are held prior to being processed by a receiving program or system. Event queues are often used in the context of an enterprise messaging system.   

`Call Stack`
In computer science, a call stack is a stack data structure that stores information about the active subroutines of a computer program. This kind of stack is also known as an execution stack, program stack, control stack, run-time stack, or machine stack, and is often shortened to just "the stack


`Subscribe`
As a publisher, you create an Observable instance that defines a subscriber function. ... To execute the observable you have created and begin receiving notifications, you call its subscribe() method, passing an observer. This is a JavaScript object that defines the handlers for the notifications you receive

`database`  
A database is an organized collection of structured information, or data, typically stored electronically in a computer system. A database is usually controlled by a database management system (DBMS). ... The data can then be easily accessed, managed, modified, updated, controlled, and organized.

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
-   Socket.io

---------------------------------------------------------------------
## Socket.io
`WebSocket `
 is a computer communications protocol, providing full-duplex communication channels over a single TCP connection. The WebSocket protocol was standardized by the IETF as RFC 6455 in 2011, and the WebSocket API in Web IDL is being standardized by the W3C.

 Socket.IO enables real-time bidirectional event-based communication. It works on every platform, browser or device, focusing equally on reliability and speed. Socket.IO is built on top of the WebSockets API (Client side) and Node.js. It is one of the most depended upon library on npm (Node Package Manager). 

 ### Difference Between WebSocket and Socket.io
 - WebSocket is the communication Protocol that provides bidirectional communication between the Client and the Server over a TCP connection; WebSocket remains open all the time, so they allow real-time data transfer. When clients trigger the request to the server, it does not close the connection on receiving the response; it rather persists and waits for the Client or server to terminate the request.

- Socket.IO is a library that enables real-time and full-duplex communication between the Client and the Web servers. It uses the WebSocket protocol to provide the interface. Generally, it is divided into two parts; both WebSocket vs Socket.io are event-driven libraries.

### Key features of Socket.IO
- It helps in broadcasting to multiple sockets at a time and handles the connection transparently.
- It works on all platform, server or device, ensuring equality, reliability, and speed.
- It automatically upgrades the requirement to WebSocket if needed.
- It is a custom real-time transport protocol implementation on top of other protocols.
- It requires both libraries to be used Client side as well as a server-side library.

### Socket.IO Example : 
![](https://raw.githubusercontent.com/socketio/socket.io-redis-emitter/HEAD/assets/emitter.png)
