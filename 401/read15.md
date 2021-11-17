## Event Driven Architecture

### Review, Research, and Discussion

## What’s the difference between a FIFO and a standard queue?**

Standard queues provide at-least-once delivery, which means that each message is delivered at least once. FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it.

## How can the server be assured a message was properly received?**

Either receiving a response from the client confirming receipt of a message, or performing a status check at regular intervals.


## What classic design pattern is best represented by event driven programming?**

The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods

**4. How do you test an event driven system?**

- unit tests 
- service tests 
- end-to-end tests


## Document the following Vocabulary Terms

`FIFO Queue`  
FIFO (First-In-First-Out) queues are designed to enhance messaging between applications when the order of operations and events is critical, or where duplicates can't be tolerated. Examples of situations where you might use FIFO queues include the following:

- To make sure that user-entered commands are run in the right order.

- To display the correct product price by sending price modifications in the right order.

- To prevent a student from enrolling in a course before registering for an account.

`Pub/Sub`  

, which stands for Publisher/Subscriber, allows services to communicate asynchronously, with latencies on the order of 100 milliseconds.


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


`SNS`  
 is a distributed publish-subscribe system. Messages are pushed to subscribers as and when they are sent by publishers to SNS.
 
 ` SQS`    

  is distributed queuing system. Messages are not pushed to receivers 
 
 - SQS and SNS are important components for scalable, large scale, distributed, cloud-based applications:
- SNS is a distributed publish-subscribe service.
- SQS is distributed queuing service.  


- SNS supports several end points such as email, sms, http end point and SQS. If you want unknown number and type of subscribers to receive messages, you need SNS. 

   
![](https://miro.medium.com/max/700/1*DRrTtdyah9NHwR0VCm6MWA.png)   
   

- SQS is distributed queuing system. Messages are not pushed to receivers. Receivers have to poll SQS to receive messages. Messages can be stored in SQS for short duration of time (max 14 days).

![](https://miro.medium.com/max/700/1*7eL3udb6Cto4I9Ly1sN8oA.jpeg)   
   