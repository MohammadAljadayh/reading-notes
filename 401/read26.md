## Read: Class 31 - Context API

### Describe use cases `useState()`  vs `useReducer()`?

useState is a Basic Hook for managing simple state transformation and useReducer is an Additional Hook for managing more complex state logic, it is worth noting that useState uses the useReducer internally. This implies that you could use useReducer for everything you can do with useState.

useReducer returns state and a dispatch function. You can pass the dispatch function down to other components which should call it with a type. [medium]

## Why do custom hooks need the use prefix?

 standard


## Using any list of custom hooks, research and name one that you think will be useful in your applications?

- useContext: Accepts a context object  and returns the current context value for that context. 



**Term Definition** 

`reducer`   
  A reducer is a function that determines changes to an application's state. 


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
-  setEffect
---------------------------------------------------------------------

## Context 

- In a typical React application, data is passed top-down (parent to child) via props, but such usage can be cumbersome for certain types of props (e.g. locale preference, UI theme) that are required by many components within an application. Context provides a way to share values like these between components without having to explicitly pass a prop through every level of the tree.

- When to Use Context
Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.

- Caveats : Because context uses reference identity to determine when to re-render, there are some gotchas that could trigger unintentional renders in consumers when a provider’s parent re-renders. For example, the code below will re-render all consumers every time the Provider re-renders because a new object is always created for value  

![](https://www.carlrippon.com/static/0d1f722d0fe4c2bc4c3d71595dbe67dd/ca682/prop-drilling-v-context.png)