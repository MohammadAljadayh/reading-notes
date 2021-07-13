# Forms and JS Events 
## Forms
- Whenever you want to collect information from
visitors you will need a form, which lives inside a
<form> element.
-  Information from a form is sent in name/value pairs.
- Each form control is given a name, and the text the
user types in or the values of the options they select
are sent to the server.
- HTML5 introduces new form elements which make it
easier for visitors to fill in forms. 

** An HTML form is used to collect user input. The user input is most often sent to a server for processing.**

#### The HTML <form> element
- The HTML <form> element is used to create an HTML form for user input:

- The <form> element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc. 

![](https://www.tutorialbrain.com/wp-content/uploads/2019/01/HTML-Form.jpg)

#### The <input> Element

The HTML <input> element is the most used form element.

An <input> element can be displayed in many ways, depending on the type attribute. 

- <input type="text">	Displays a single-line text input field
- <input type="radio">	Displays a radio button (for selecting one of many choices)
- <input type="checkbox">	Displays a checkbox (for selecting zero or more of many choices)
- <input type="submit">	Displays a submit button (for submitting the form)
- <input type="button">	Displays a clickable button 

![](https://i.ytimg.com/vi/MKSQYsLLFEo/maxresdefault.jpg)

#### Text Fields 
- The <input type="text"> defines a single-line input field for text input. 

![](https://i.ytimg.com/vi/U8YshrNwN8I/maxresdefault.jpg)

#### The <label> Element

- The <label> tag defines a label for many form elements.

- The <label> element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.

- The <label> element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within - the <label> element, it toggles the radio button/checkbox.

- The for attribute of the <label> tag should be equal to the id attribute of the <input> element to bind them together.


---------------------------------------------

## Lists, Tables and Forms  

-  In addition to the CSS properties covered in other
chapters which work with the contents of all elements,
there are several others that are specifically used to
control the appearance of lists, tables, and forms.
-  List markers can be given different appearances
using the list-style-type and list-style image
properties.
-  Table cells can have different borders and spacing in
different browsers, but there are properties you can
use to control them and make them more consistent.
- Forms are easier to use if the form controls are
vertically aligned using CSS.
-  Forms benefit from styles that make them feel more
interactive. 
-------------------------------------------

## Events javascript
![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/JavaScript-Event-Types.jpg) 

HTML events are "things" that happen to HTML elements.

When JavaScript is used in HTML pages, JavaScript can "react" on these events. 

Often, when events happen, you may want to do something.

JavaScript lets you execute code when events are detected.

HTML allows event handler attributes, with JavaScript code, to be added to HTML elements. 

#### Common HTML Events

- onchange	An HTML element has been changed
- onclick	The user clicks an HTML element
- onmouseover	The user moves the mouse over an HTML element
- onmouseout	The user moves the mouse away from an HTML element
- onkeydown	The user pushes a keyboard key
- onload	The browser has finished loading the page



#### What can JavaScript Do?
- Event handlers can be used to handle and verify user input, user actions, and browser actions:

- Things that should be done every time a page loads
- Things that should be done when the page is closed
- Action that should be performed when a user clicks a button
- Content that should be verified when a user inputs data
And more ...
- Many different methods can be used to let JavaScript work with events:

- HTML event attributes can execute JavaScript code directly
- HTML event attributes can call JavaScript functions
- You can assign your own event handler functions to HTML elements
- You can prevent events from being sent or being handled
And more ...


