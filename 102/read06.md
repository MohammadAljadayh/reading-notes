# Design web pages with CSS

CSS (Cascading Style Sheets) allows you to create great-looking web pages, but how does it work under the hood? This article explains what CSS is, with a simple syntax example, and also covers some key terms about the language.

![css](https://www.w3docs.com/uploads/media/default/0001/05/6d07a36ebe6d55273b39440f2391f1d7e6d4092a.png)

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

