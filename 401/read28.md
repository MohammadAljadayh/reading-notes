## Login /> and Auth /> 



### Why is the Context API useful?

> The Context API is a React structure that enables you to exchange unique details and assists in solving prop-drilling from all levels of your application.

### Can a component outside of a provider get its context?

> yes  we can  by use the useContext hook. 

### What are some common use cases for using the Context API?

> Context is primarily used when some data needs to be accessible by many components at different nesting levels. Apply it sparingly because it makes component reuse more difficult. If you only want to avoid passing some props through many levels, component composition is often a simpler solution than context.

### Describe “Context Hell

> the React Context hell is the nasty code you get taking advantage of the React Context API.

**Term Definition** 


`global state`   
  Context provides a way to pass data through the component tree without having to pass props down manually at every level, managing state in multiple components that are not directly connected. ... Enough talking about it.


`global context`   
designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language. For example, in the code below we manually thread through a “theme” prop in order to style the Button component: class App extends React.


`provider`     
 The component makes the Redux store available to any nested components that need to access the Redux store. Since any React component in a React Redux app can be connected to the store, most applications will render a at the top level, with the entire app's component tree inside of it.


`consumer`   
 A React component that subscribes to context changes. Using this component lets you subscribe to a context within a function component. Requires a function as a child. The function receives the current context value and returns a React node.



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
-  useContext
---------------------------------------------------------------------


### DEFINITION OF ROLE-BASED ACCESS CONTROL (RBAC)
Role-based access control (RBAC) restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control. The roles in RBAC refer to the levels of access that employees have to the network. 


### EXAMPLES OF ROLE-BASED ACCESS CONTROL : 

Through RBAC, you can control what end-users can do at both broad and granular levels. You can designate whether the user is an administrator, a specialist user, or an end-user, and align roles and access permissions with your employees’ positions in the organization. Permissions are allocated only with enough access as needed for employees to do their jobs. 

![](https://www.researchgate.net/publication/332732675/figure/fig1/AS:753014671409160@1556544096630/Scheme-of-role-based-access-control-RBAC-model.ppm)
