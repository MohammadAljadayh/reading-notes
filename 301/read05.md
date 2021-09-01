
# Putting it all together

 ## 1. How would you break a mock into a component heirarchy?
 - The first thing you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names in breif  
 - select UI content and convert them to components . 
-  make component for each element,where each component matches one piece of your data model. 
-  sort the components  from parent to child . 

 ## 2. What is the single responsibility principle and how does it apply to components?
Single responsibility principle describes how to split requirements into components, encapsulation describes how to organize these components, and composition describes how to glue the whole system back.


 ## 3. What does it mean to build a static  version of your application?

it is meain  you will not use state into your components.

 ## 4. Once you have a static application, what do you need to add?
 you have to make it dynamic, by using states into each component that needs to change its data.
 
 ##  5. What are the three questions you can ask to determine if something is state?

- Is it passed in from a parent via props? If so, it probably isn’t state.
- Does it remain unchanged over time? If so, it probably isn’t state.
- Can you compute it based on any other state or props in your component? If so, it isn’t state.

 ##  6.  How can you identify where state needs to live? 

so we’ve decided that our state lives in FilterableProductTable. First, add an instance property this.state = {filterText: '', inStockOnly: false} to FilterableProductTable’s constructor to reflect the initial state of your application. Then, pass filterText and inStockOnly to ProductTable and SearchBar as a prop. Finally, use these props to filter the rows in ProductTable and set the values of the form fields in SearchBar.


------------------------------------------------------

## Start With A Mock  in five steps : 
- Step 1: Break The UI Into A Component Hierarchy
- Step 2: Build A Static Version in React
- Step 3: Identify The Minimal (but complete) Representation Of UI State
- Step 4: Identify Where Your State Should Live
- Step 5: Add Inverse Data Flow


## for more details 
[React Docs - thinking in React](https://reactjs.org/docs/thinking-in-react.html)
