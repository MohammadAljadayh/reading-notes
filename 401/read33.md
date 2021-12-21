# Redux - Asynchronous Actions


## How granular should your reducers be?

Generally, as granular as possible. This allows for easier organizion, debugging, and testing.

## Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched

 Having multiple reducers fire on a shared action is a great way to handle complex state changes in a predicable, reliable.
## Name a strategy for preventing the above

Use explicit names for each action to prevent unintended firing . 

## Document the following Vocabulary Terms

`store`    
 the object created by redux that stores all states for a given application. This is the single source of truth for our application.

`combined reducers`  
 a way redux allows us to 'export' many reducer files from a single source to our store, so that they are all available in different parts of an app.

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

## Redux Fundamentals, Part 6: Async Logic and Data Fetching 

In Part 5: UI and React, we saw how to use the React-Redux library to let our React components interact with a Redux store, including calling useSelector to read Redux state, calling useDispatch to give us access to the dispatch function, and wrapping our app in a <Provider> component to give those hooks access to the store.

## Redux Middleware and Side Effects
By itself, a Redux store doesn't know anything about async logic. It only knows how to synchronously dispatch actions, update the state by calling the root reducer function, and notify the UI that something has changed. Any asynchronicity has to happen outside the store.

Earlier, we said that Redux reducers must never contain "side effects". A "side effect" is any change to state or behavior that can be seen outside of returning a value from a function

### common kinds of side effects are things like:

- Logging a value to the console
- Saving a file
- Setting an async timer
- Making an AJAX HTTP request
- Modifying some state that exists outside of a function, or mutating arguments to a function
- Generating random numbers or unique random IDs (such as Math.random() or Date.now())

### Redux Async Data Flow​ 

![](https://d33wubrfki0l68.cloudfront.net/08d01ed85246d3ece01963408572f3f6dfb49d41/4bc12/assets/images/reduxasyncdataflowdiagram-d97ff38a0f4da0f327163170ccc13e80.gif)
