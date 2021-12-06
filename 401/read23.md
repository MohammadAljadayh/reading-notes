# useEffect() Hook

## Why do we not need more .html pages in a multi-page React app? 

 react based on   single page app ,A React app  view the contanit as a componant 
 A single-page application is an application that loads a single HTML page and all the necessary assets (such as JavaScript and CSS) required for the application to run

##  If we wanted a component to show up on every page, where would we put it and why? 

 - Inside the <BrowserRouter />, outside a <Route />

## What does routing do with the components that were rendered when a new route is requested 

- render a  new componetnt and cleans the previous one

## What does props.children contain?

- My simple explanation of what this.props.children does is that it is used to display whatever you include between the opening and closing tags when invoking a component.

## How do useState() and this.setState() differ? 

- The setState function is used to handle the state object in a React class component. This is something you will see a lot of in the examples below. Anytime you see a this.setState() this is how we are setting the state in a class component.
-  The useState() is a Hook that allows you to have state variables in functional components , it takes the initial state as an argument and returns an array of two entries. 

**Term Definition** 
`State Hook`   
  The useState() is a Hook that allows you to have state variables in functional components , it takes the initial state as an argument and returns an array of two entries.
`Mounting and Un-Mounting`   
A React component's lifecycle contains distinct phases for creation and deletion. In coding terms, these are called mounting and unmounting. You can also think of them as "setup" and "cleanup".

If you were going to have a picnic, just before you lay down the picnic blanket you'd make sure the ground was level and clean. Also, after you're done, and before you clean up your picnic blanket, you'd make sure you've taken all your belongings off it and cleared up any garbage left on the grass so people after you can easily use the same spot.

That's very similar to what happens with React components. The browser window is almost like a great big field that loads the components that can be used. And when they leave, it's only polite of them to clean up the space they were using — so that other components can reuse the same space without any annoyances due to things left behind.

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
-  setState
---------------------------------------------------------------------

## Using the Effect Hook 

- The Effect Hook lets you perform side effects in function components 

- Effects Without Cleanup
Sometimes, we want to run some additional code after React has updated the DOM. Network requests, manual DOM mutations, and logging are common examples of effects that don’t require a cleanup. We say that because we can run them and immediately forget about them. Let’s compare how classes and Hooks let us express such side effects. 

- What does useEffect do? By using this Hook, you tell React that your component needs to do something after render. React will remember the function you passed (we’ll refer to it as our “effect”), and call it later after performing the DOM updates. In this effect, we set the document title, but we could also perform data fetching or call some other imperative API. 

- Why is useEffect called inside a component? Placing useEffect inside the component lets us access the count state variable (or any props) right from the effect. We don’t need a special API to read it — it’s already in the function scope. Hooks embrace JavaScript closures and avoid introducing React-specific APIs where JavaScript already provides a solution.

 ![](https://miro.medium.com/max/1400/1*Un-R2o9nigypQCo3S6DLow.png)




