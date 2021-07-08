# Problem Domain, Objects, and the DOM

- ### Understanding The Problem Domain Is The Hardest Part Of Programming 
Writing code is a lot like putting together a jigsaw puzzle.  We put together code with the purpose of building components that we have taken out of the “bigger picture” of the problem domain.

The big issue is that many problem domains are like a puzzle with a blurry picture or no picture at all. 

- Programming is easy if you understand the problem domain
A long time ago, I worked for Hewlett Packard writing software for multi-function printers.

- Most of the work at the time was basic waterfall development.  There wasn’t much Agile happening there—at least at the time I was there.

- What can you do about it?
If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

Make the problem domain easier  
Get better at understanding the problem domain 

--------------------------------------------------
## Objects 
In real life, a car is an object.

A car has properties like weight and color, and methods like start and stop:

You have already learned that JavaScript variables are containers for data values

Objects are variables too. But objects can contain many values.

- Object Definition  
You define (and create) a JavaScript object with an object literal:   
 const person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};  

-  Object Properties  
The name:values pairs in JavaScript objects are called properties:

- Accessing Object Properties  
You can access object properties in two ways: 
1- objectName.propertyName 
2- objectName["propertyName"]

- Object Methods
Objects can also have methods.

Methods are actions that can be performed on objects.

Methods are stored in properties as function definitions.  

A method is a function stored as a property.

 ![](https://res.cloudinary.com/practicaldev/image/fetch/s--rJeH0yGE--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/t52ni02srb8688lh3eh8.png)
 --------------------------------------------------

 ### JavaScript HTML DOM
 When a web page is loaded, the browser creates a Document Object Model of the page.

The HTML DOM model is constructed as a tree of Objects: 

![](https://www.w3schools.com/js/pic_htmltree.gif)

With the object model, JavaScript gets all the power it needs to create dynamic HTML:

- JavaScript can change all the HTML elements in the page
- JavaScript can change all the HTML attributes in the page
- JavaScript can change all the CSS styles in the page
- JavaScript can remove existing HTML elements and attributes
- JavaScript can add new HTML elements and attributes
- JavaScript can react to all existing HTML events in the page
- JavaScript can create new HTML events in the page 

The HTML DOM is a standard object model and programming interface for HTML. It defines:

- The HTML elements as objects  
- The properties of all HTML elements
- The methods to access all HTML elements
*- The events for all HTML elements
- In other words: The HTML DOM is a standard for how to get,-  change, add, or delete HTML elements. 

![](https://simplesnippets.tech/wp-content/uploads/2018/10/what-is-document-object-model-in-JS-featured-image.jpg)