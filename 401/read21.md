# Component Based UI

## Name 5 Javascript UI Frameworks (other than React)**

- Node.js
- Vue.js
- Ember.js
- Backbone.js
- AngularJS

## What’s the difference between a framework and a library?

> A `framework` inverts the control of the program. It tells the developer what they need. A `library` doesn't. The programmer calls the library where and when they need it


**Term Definition** 

`Rendering`   
Rendering is the most important procedure that a programmer has to manage in frontend development. In React, the render() method is the only required method in a class component, and is responsible for describing the view to be rendered to the browser window.  
`Templates`  
 A template is a chunk of HTML that you need to inject onto the page.
` State`    
React components has a built-in state object.

The state object is where you store property values that belongs to the component.

When the state object changes, the component re-renders. 
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
-  sass 

---------------------------------------------------------------------


`React`  
 is a JavaScript library, and so we’ll assume you have a basic understanding of the JavaScript language  

`JSX `  
 it is a syntax extension to JavaScript. We recommend using it with React to describe what the UI should look like. JSX may remind you of a template language, but it comes with the full power of JavaScrip  

### Why JSX?  
React doesn’t require using JSX, but most people find it helpful as a visual aid when working with UI inside the JavaScript code. It also allows React to show more useful error and warning messages.  

![](https://miro.medium.com/max/1400/1*wQxgEiVsgG0o7ti45WuFTQ.png)  


### Rendering Elements
 - An element describes what you want to see on the screen . 
 - React elements are plain objects, and are cheap to create. 
 - React DOM takes care of updating the DOM to match the React elements.


Even though we create an element describing the whole UI tree on every tick, only the text node whose contents have changed gets updated by React DOM.

In our experience, thinking about how the UI should look at any given moment, rather than how to change it over time, eliminates a whole class of bugs. 

![](https://reactjs.org/c158617ed7cc0eac8f58330e49e48224/granular-dom-updates.gif)

