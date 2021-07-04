# Html Text 


- HTML elements are used to describe the structure of
the page (e.g. headings, subheadings, paragraphs).
- They also provide semantic information (e.g. where
emphasis should be placed, the definition of any
acronyms used, when given text is a quotation).

**HTML Text Formatting Elements**
Tag	Description
- <b>	Defines bold text
- <em>	Defines emphasized text 
- <i>	Defines a part of text in an alternate voice or mood
- <small>	Defines smaller text
- <strong>	Defines important text
- <sub>	Defines subscripted text
- <sup>	Defines superscripted text
- <ins>	Defines inserted text
- <del>	Defines deleted text
- <mark>	Defines marked/highlighted text
For a complete list of all available HTML tags, visit our HTML T 

# Introducing CSS 



CSS (Cascading Style Sheets) allows you to create great-looking web pages, but how does it work under the hood? This article explains what CSS is, with a simple syntax example, and also covers some key terms about the language.


As we have mentioned before, CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc. 

- ## How To Add CSS

There are three ways of inserting a style sheet:

- **External CSS.**
With an external style sheet, you can change the look of an entire website by changing just one file! 
        
    <link rel="stylesheet" href="mystyle.css"> 

External styles are defined within the <link> element, inside the <head> section of an HTML page: 

and do the Style on external page like style.css 



- ** Internal CSS. ** 

An internal style sheet may be used if one single HTML page has a unique style.

The internal style is defined inside the <style> element, inside the head section. 

for example : 
<style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
}
</style>  




- **Inline CSS .**
An inline style may be used to apply a unique style for a single element.

To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

for example :  


<h1 style="color:blue;text-align:center;">This is a heading</h1>   


- **Multiple Style Sheets **
in Multiple Style Sheets we use many of style sheet toghater . 


### CSS color Property

The color property specifies the color of text. 

for example of type of color 

![Img](https://i.stack.imgur.com/0dz7c.png)

--------------------------------------------

# Basic JavaScript Instructions

** JavaScript Functions**

 A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).  

- **JavaScript Function Syntax**
A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

![JS](https://raw.githubusercontent.com/learn-co-curriculum/cssi-2.3-functions/master/images/functions.png)

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}

for example :   
function name(parameter1, parameter2, parameter3) {
  // code to be executed
}

- ** Function Invocation**   
The code inside the function will execute when "something" invokes (calls) the function:

When an event occurs (when a user clicks a button)
When it is invoked (called) from JavaScript code
Automatically (self invoked)

- **Function Return** 
When JavaScript reaches a return statement, the function will stop executing.

If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

- ** Functions Used as Variable Values**
Functions can be used the same way as you use variables, in all types of formulas, assignments, and calculations.

- **Local Variables**

Variables declared within a JavaScript function, become LOCAL to the function.

Local variables can only be accessed from within the function.

Since local variables are only recognized inside their functions, variables with the same name can be used in different functions.

![js2](https://miro.medium.com/max/1798/1*6kTeSUP0V2UIgOmavp-TDg.png)

--------------------------------------------
# JavaScript Operators 

- **JavaScript Arithmetic Operators**
- The Below Pic Explain All Type of the operator . 
![ms](https://www.learnsimpli.com/wp-content/uploads/2020/02/3-4.png)




