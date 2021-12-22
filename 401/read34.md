# Redux - Additional Topics


## What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?

Best practice would be to fire off an api call from a useEffect() call on pageload. Because this is asynchronous, this will require Thunk middleware. You may then  use mapStateToProps() to assign the returned data to props which can be passed to the component in question. 

## When using a thunk/async action that dispatches the actual action, which do you export from your reducer?

You export the thunk (async) action, which then dispatches the actual action locally.

## Document the following Vocabulary Terms

`middleware`  

 code that runs between two functions - in the case of redux, code that is wrapped between our `createStore()` function and our `connect()` function.

`thunk` 
 a kind of middlware that takes a function, does some processing, and returns another function.

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
-  Redux-Asynchronous Actions
---------------------------------------------------------------------
## Redux Toolkit 
The Redux core docs site at https://redux.js.org contains the primary tutorials for learning Redux, including how to use Redux Toolkit and React-Redux together.

## Using Redux Toolkit​

The RTK Usage Guide docs page explains the standard usage patterns for each of RTK's APIs. The API Reference section describes each API function and has additional usage examples.

The Redux Essentials tutorial also shows how to use each of the APIs while building an application.

![](https://cdn2.hubspot.net/hubfs/7088297/GenUI_April_2020/Images/modular-redux-intermediate-tutorial-redux-toolkit.png)
