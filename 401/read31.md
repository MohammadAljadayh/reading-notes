# Application State with Redux



## What are the advantages of storing tokens in “Cookies” vs “Local Storage”

Local Storage is vulnerable to XSS attacks, and cookies are automatically attached to every HTTP request on your server. 

## Explain 3rd party cookies.

 Third-party cookies are created by websites other than the one you are currently visiting.

## How do pixel tags work?

As a pixel loads, it runs associated javascript code which does a given action. In the context of advertising, these often collect and send data back to some third party.

## Document the following Vocabulary Terms

`cookies`- a small piece of data sent from a server to a client, which is then attached to every client request back to that server.

` authorization`  - a HTTP request header that contains required authentication credentials.

`access control` - the process of requiring client authenticaion to verify different levels of access on a server.

`conditional rendering` - the process of using React to render certain components or elements based on conditional logic.


--------------------------------------------------------------------- 
# Preview 

> Which 3 things had you heard about previously and now have better clarity on?
- JSX
- React 
- rendering
> Which 3 things are you hoping to learn more about in the upcoming lecture/demo? 
- rendering
- React
- Dynamo/Mongo
> What are you most excited about trying to implement or see how it works?
-  Redux
---------------------------------------------------------------------


- Redux stores all application state in a single javascript object called the state tree. All mutations and changes to the state data object are explicit, so we can keep track of them easily. The state tree is redundant, so we must use an action method to modify the data.

- SRedux provides a solid, stable, and mature solution to managing state in your React application. Through a handful of small, useful patterns, Redux can transform your application from a total mess of confusing and scattered state, into a delightfully organized, easy to understand modern JavaScript powerhouse.


