# Read: Class 13 : Message Queues




## What does it mean that web sockets are bidirectional? Why is this useful?

BIDIRECTIONAL. Whereas HTTP relies on a client request to receive a response from the server for every exchange, WebSockets allow for full-duplex bidirectional communication. This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time.

## Does socket.io use HTTP? Why?

js) and the Socket.IO client (browser, Node. js, or another programming language) is established with a WebSocket connection whenever possible, and will use HTTP long-polling as fallback. ... the high-level API: Socket.IO itself.
  
## What happens when a client emits an event? 

The client emits an event and then the server handles the event using the on method.

## What happens when a server emits an event?

Server emits the event and it is handled by the client side . 

## What happens if a client “misses” an event?
 Nothing happens with it The event will be ignored if it is missed.


## Document the following Vocabulary Terms

`Socket : `

  : A socket is one endpoint of a two-way communication link between two programs running on the network. A socket is bound to a port number so that the TCP layer can identify the application that data is destined to be sent to. ... Every TCP connection can be uniquely identified by its two endpoints

 `Web Socket `

   WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection. The WebSocket protocol was standardized by the IETF as RFC 6455 in 2011, and the WebSocket API in Web IDL is being standardized by the W3C. WebSocket is distinct from HTTP

`Socket.io : `

Socket.IO is a JavaScript library for realtime web applications. It enables realtime, bi-directional communication between web clients and servers. It has two parts: a client-side library that runs in the browser, and a server-side library for Node.js. Both components have a nearly identical AP

`Client: `  

it is the library that runs inside the browser(Accesses services or functionality from server)

` Server :  ` 
 It is the library for Node.js(Provides services and functionality for clients)

`OSI Model :`  

 (Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system. The OSI model characterizes computing functions into a universal set of rules and requirements in order to support interoperability between different products and software.



`TCP Model:`  

    specifications for translating the network addressing methods used in the Internet Protocol to link-layer addresses, such as media access control (MAC) addresses.


`TCP: `  

   Transmission control protocol. TCP provides reliable, ordered, and error-checked delivery of a stream of octets (bytes) between applications running on hosts communicating via an IP network. (Transmission Control Protocol - a connection-based communication protocol used for the transmission of data within a network.)

` UDP :`

 (User Datagram Protocol) is a communications protocol that is primarily used for establishing low-latency and loss-tolerating connections between applications on the internet. It speeds up transmissions by enabling the transfer of data before an agreement is provided by the receiving party.(a connectionless communication protocol used for time-sensitive transmission of data.)

` Packets :`

a formatted unit of data carried by a packet-switched network. A packet consists of control information and user data; the latter is also known as the payload. Control information provides data for delivering the payload

# Preview
> Which 3 things had you heard about previously and now have better clarity on?
- Socket
- authentication & authorization 
- ACL 
> Which 3 things are you hoping to learn more about in the upcoming lecture/demo? 
- Socket
- Socket.io
- OSI Model 
> What are you most excited about trying to implement or see how it works?
-   Socket.io

---------------------------------------------------------------------
# Messaging Queue 
`Messaging Queue` enables asynchronous communication, where application puts a message onto a message queue and does not require an immediate response to continuing processing. 

The producer and consumer do not interact directly with each other, but they interact with message queue. This way of handling messages decouples the producer from the consumer so that they do not need to interact with the message queue simultaneously.
In this article, we will look at how to build a simple message queue in Node.js and RabbitMQ.

![img](https://www.mulesoft.com/sites/default/files/cmm_files/what%20is%20messaging%20queue.png)

