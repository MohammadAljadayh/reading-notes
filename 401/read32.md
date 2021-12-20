# Redux - Combined Reducers


## Why choose Redux instead of the Context API for global state?

Because it enforces single-source-of-truth, and allows us to standardize how our state is updated across our app. 

## What is the purpose of a reducer? 

A reducer is a pure function that handles updating the state of our application . 

## What does an action contain?

An action contains an object with properties `type` and `payload`. 

## Why do we need to copy the state in a reducer? 

State in react is immutable, so we must pass a new copy to our reducer in order to re-set it.


**Term Definition**

`immutable state` - In redux, the state of an object is immutable. This allows for simpler debugging, change detection, and prevents unwatnted state changes from happening as side-effects elsewhere in your app.

`time travel in redux` - by tracking state, redux allows devs to "time travel" by reversing state. Because redux is predictable, you can reliably recreate previous states by passing those state objects into the application state.

`action creator` - a function that actually returns an action object to our reducer. By abstracting the call to the action, we simplify our implemented code.

`reducer` - a switch function that handles updating the application state (by creating a new state object) depending on the given action call made to it.

`dispatch`- the act of passing (or, dispatching) an action from an action creator to a reducer.

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

## Using combineReducers
 Core Concepts​
The most common state shape for a Redux app is a plain Javascript object containing "slices" of domain-specific data at each top-level key. Similarly, the most common approach to writing reducer logic for that state shape is to have "slice reducer" functions, each with the same (state, action) signature, and each responsible for managing all updates to that specific slice of state. Multiple slice reducers can respond to the same action, independently update their own slice as needed, and the updated slices are combined into the new state object

## There are several important ideas to be aware of when using combineReducers:

 - First and foremost, combineReducers is simply a utility function to simplify the most common use case when writing Redux reducers. You are not required to use it in your own application, and it does not handle every possible scenario. It is entirely possible to write reducer logic without using it, and it is quite common to need to write custom reducer logic for cases that combineReducer does not handle. (See Beyond combineReducers for examples and suggestions.)
- While Redux itself is not opinionated about how your state is organized, combineReducers enforces several rules to help users avoid common errors. (See combineReducers for details.)
- One frequently asked question is whether Redux "calls all reducers" when dispatching an action. Since there really is only one root reducer function, the default answer is "no, it does not". However, combineReducers has specific behavior that does work that way. In order to assemble the new state tree, combineReducers will call each slice reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed. So, in that sense, using combineReducers does "call all reducers", or at least all of the slice reducers it is wrapping.
- You can use it at all levels of your reducer structure, not just to create the root reducer. It's very common to have multiple combined reducers in various places, which are composed together to create the root reducer.