
# State and Props

### Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

start with render first then componentDidMount

### What is the very first thing to happen in the lifecycle of React?

The constructor for a React component is called before it is mounted.

### Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

- constructor
-  render
- componentDidMount
-  React Updates
-  componentWillUnmount


### What does componentDidMount do?

-  Used for DOM mainupolation and network requests.
- It is invoked  after a component is mounted.
-  It is a good place to set up any subscriptions.
- setState() can be called here, but it should be used sparingly.

### how to include React Bootstrap in the project

-  Installation
- Importing Components
- Browser globals. 
- CSS:import 'bootstrap/dist/css/bootstrap.min.css';`

## React State Vs Props

### What types of things can you pass in the props?  
 props used  to display things, like argument to function
 
### What is the big difference between props and state?
props: pass it to the component----> updated outside the component
state: it’s inside the component---->updated inside the component
### When do we re-render our application? 
when we change the state inside of our application
###  What are some examples of things that we could store in state?
use state to store date that are inside of a form like checkbox, textbox, or an input element that are being updated by the user.
### Things I want to know more about
When to use Lifecycle method.
How to set state of a component.

![](https://i.stack.imgur.com/wqvF2.png)

### What are component lifecycle events?  
React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.   

so Mounting, Updating, and Unmounting are the three phases of the component lifecycle.  
 
 ![](https://miro.medium.com/max/1400/1*6X_7HKFdQoh9eXqWgwQuvQ.png)


## for more information 
- [React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093#).
- [React Bootstrat Documentation](https://react-bootstrap.github.io/).
- [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI).



