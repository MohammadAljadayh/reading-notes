
# React and Forms
## Forms

## **What is a Controlled Component?**
In HTML, form elements such as input, textarea, and select typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().

We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.

So it is an element that when its value will change, it will be updated by setState and passed by props, this changing will be notifyed by the parent component and will control it.



##  **Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**

No,  beacuase we uesd the controlled component in form, like onChange property. 

##  **How do we target what the user is entering if we have an event handler on an input field?**

doing setState in the onChange function, storing the value then the  the target will be : event.target.name.value.  

----------------------------------------------------------------------------------
## Ternary Operator 

## **Why would we use a ternary operator?**
Use the ternary operator to simplify your if-else statements that are used to assign values to variables. The ternary operator is commonly used when assigning post data or validating forms.

## **Rewrite the following statement using a ternary statement:**
  - if(x===y){
 - console.log(true);
 -  } else {
 - console.log(false);
 -  }
  
  Answer :   
  - x===y ? console.log(true) : console.log(false)
  ------------------------------------------------------------------------------

  ![](https://res.cloudinary.com/practicaldev/image/fetch/s--KpQnReJ9--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://i1.wp.com/blogreact.com/wp-content/uploads/2020/03/forms.jpg%3Ffit%3D750%252C393%26ssl%3D1)  

  ## for More Details :
  [React Docs - Forms](https://reactjs.org/docs/forms.html)
  
  [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)
  


  
