# Read: Class 01
## Readings: Introduction to React and Components

- A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.

 **Characteristics of Components** :  
  -  Reusability
  -  Replaceable
  -  Not context specific
   - Extensible
   - Encapsulated
   - Independent 
   
**dvantages of using component based architecture:** 
  - Ease of deployment 
  - Reduced cost
   - Ease of development
  -  Reusable
   - Modification of technical complexity
   - Reliability
  -  System maintenance and evolution
  -  Independent


   
-  **Props** is a special keyword in React, which stands for properties and is being used for passing data from one component to another.

**How to Use Props in React** : 
   - Firstly, define an attribute and its value(data)
- Then pass it to child component(s) by using Props
- Finally, render the Props Data


-  **Props** can only be passed to components in one-way (parent to child)
Props data is immutable (read-only) 

-----------------------------------------
## component
A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.

A software component can be defined as a unit of composition with a contractually specified interface and explicit context dependencies only. That is, a software component can be deployed independently and is subject to composition by third parties.

![](https://www.techdiagonal.com/wp-content/uploads/2019/08/React-components-blog-image.jpg) 

#### Principles of Component−Based Design 
A component-level design can be represented by using some intermediary representation (e.g. graphical, tabular, or text-based) that can be translated into source code. The design of data structures, interfaces, and algorithms should conform to well-established guidelines to help us avoid the introduction of errors.  


#### Props
React is a component-based library which divides the UI into little reusable pieces. In some cases, those components need to communicate (send data to each other) and the way to pass data between components is by using props.
“Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another. 

- Props stand for properties and is a special keyword in React
- Props are being passed to components like function arguments
- Props can only be passed to components in one-way (parent to child)
- Props data is immutable (read-only)

![](https://scriptverse.academy/img/tutorials/reactjs-components-props.png)

For More Details :   
[Component-Based Architecture](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)

[React Docs - hello world](https://reactjs.org/docs/hello-world.html)

[React Docs - introducing JSX](https://reactjs.org/docs/introducing-jsx.html)

[React Docs - rendering elements](https://reactjs.org/docs/rendering-elements.html)

[React Docs - Components and props](https://reactjs.org/docs/components-and-props.html)

