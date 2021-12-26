# Reading: React Native


## Compare and Contrast Redux Toolkit with Redux “Ducks”?

RTK follows the ducks pattern and combines reducers, actions, and constants in one file called a slice. Each slice will provide an initial state and a reducer function for an object in store. So our component that provides the data, which is a duck now, will look like this.

## What is the principle advantage of Redux Toolkit ? 
Redux Toolkit makes it easier to write good Redux applications and speeds up development, by baking in our recommended best practices, providing good default behaviors, catching mistakes, and allowing you to write simpler code. Redux Toolkit is beneficial to all Redux users regardless of skill level or experience


`redux toolkit slices`    
For this tutorial, we assume that you're using Redux Toolkit with React, ... generated Redux action creators and the reducer function for the whole slice

`namespace`  
The Redux DevTools Extension docs initially suggest using some hand-written code that checks the global namespace to see if the extension is available..

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
-  React Native
---------------------------------------------------------------------

## React Native

React Native is like React, but it uses native components instead of web components as building blocks. So to understand the basic structure of a React Native app, you need to understand some of the basic React concepts, like JSX, components, state, and props. If you already know React, you still need to learn some React-Native-specific stuff, like the native components. This tutorial is aimed at all audiences, whether you have React experience or not.

## Example 
```
import React from 'react';
import { Text, View } from 'react-native';

const HelloWorldApp = () => {
  return (
    <View
      style={{
        flex: 1,
        justifyContent: "center",
        alignItems: "center"
      }}>
      <Text>Hello, world!</Text>
    </View>
  )
}

export default HelloWorldApp;
``` 
### What's going on here?​
- First of all, we need to import React to be able to use JSX, which will then be transformed to the native components of each platform.
- On line 2, we import the Text and View components from react-native

- Components​ : So this code is defining HelloWorldApp, a new Component. When you're building a React Native app, you'll be making new components a lot. Anything you see on the screen is some sort of component.

- Props​ : Most components can be customized when they are created, with different parameters. These creation parameters are called props.

- State​ : Unlike props that are read-only and should not be modified, the state allows React components to change their output over time in response to user actions, network responses and anything else.

![](https://programmersbrain.com/wp-content/uploads/2021/04/react-pros-cons.jpg)