# Advanced State with Reducers

## How can we ensure that an effect hook runs only once? 

- If we pass an empty array [] , it just renders the component only once like componentDidMount 

## Can useState() update more than one state variable at the same time?

> yes 

## Is useState() synchronous?

useState and setState both are asynchronous.,They do not update the state immediately but have queues that are used to update the state object

**Term Definition** 

`State Hook `  

A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components. We'll learn other Hooks later.

`Component Lifecycle`   
The Component Lifecycle ... Each component has several “lifecycle methods” that you can override to run code at particular times in the process.


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
## useReducer 

`useReducer`  useReducer is one of the additional Hooks that shipped with React 16.8. An alternative to the useState Hook, it helps you manage complex state logic in React applications. When combined with other Hooks like useContext, useReducer can be a good alternative to Redux or MobX — indeed, it can sometimes be an outright better optio


## How does useReducer work?
- useReducer is used to store and update states, just like the useState Hook. It accepts a reducer function as its first parameter and the initial state as the second.

- useReducer returns an array that holds the current state value and a dispatch function, to which you can pass an action and later invoke. This is similar to the pattern Redux uses but with a few differences.

## useState vs. useReducer

Although useState is a Basic Hook for managing simple state transformation and useReducer is an Additional Hook for managing more complex state logic, it is worth noting that useState uses the useReducer internally. This implies that you could use useReducer for everything you can do with useState

## When to use the useReducer Hook
Once your application grows in size, you’ll most likely deal with more complex state transitions. At this point, you will be better off using useReducer as it gives us more predictable state transitions than useState. This becomes more important when state changes become so complex that you want to have one place (i.e., the render function) to manage state.


![](https://dmitripavlutin.com/static/c47eb25d68bef042100d2b32083d7c0a/c1bf2/cover.png)