# Introductory HTML and JavaScript

### Structure web pages with HTML

-  HTML pages are text documents.
-  HTML uses tags (characters that sit inside angled
brackets) to give the information they surround special
meaning.
-  Tags are often referred to as elements.
- Tags usually come in pairs. The opening tag denotes
the start of a piece of content; the closing tag denotes
the end.
-  Opening tags can carry attributes, which tell us more
about the content of that element.
-  Attributes require a name and a value.
-  To learn HTML you need to know what tags are
available for you to use, what they do, and where they
can go.

In the browser window you can see a web page that features exactly  
the same content as the Word document you met on the page 18. To
describe the structure of a web page, we add code to the words we want  
to appear on the page.  
You can see the HTML code for this page below. Don't worry about what  the code means yet. We start to look at it in more detail on the next
page. Note that the HTML code is in blue, and the text you see on screen
is in black.  
- <html> 

- <body>  

-  <h1>This is the Main Heading</h1>

 - <p>This text might be an introduction to the rest of
 the page. And if the page is a long one it might
 be split up into several sub-headings.<p>  

 - <h2>This is a Sub-Heading</h2>  

 - <p>Many long articles have sub-headings so to help
 you follow the structure of what is being written.
 There may even be sub-sub-headings (or lower-level
 headings).</p>  

 - <h2>Another Sub-Heading</h2>  

 - <p>Here you can see another sub-heading.</p>  

- </body>
- </html>  

The HTML code (in blue) is made up of characters that live inside angled
brackets — these are called HTML elements. Elements are usually
made up of two tags: an opening tag and a closing tag. (The closing tag
has an extra forward slash in it.) Each HTML element tells the browser
something about the information that sits between its opening and
closing tags.




**HTML** is a markup language that defines the structure of your content. HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way  

- **The main parts of our element are as follows:**  
1- The opening tag  
2- The closing tag  
3- The content  
4- The element  

- **There is two tybe of elements**  
1- Nesting elements   
for example :  put elements inside other elements like   
*<p>My cat is <strong>very</strong> grumpy.</p> * 

2- Empty elements : Some elements have no content like      
*<img src="images/firefox-icon.png" alt="My test image">*   

[For More Details of Mozilla HTML Basics & All Tags ](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)  



### Semantics

![S](https://miro.medium.com/max/1000/1*zHJFnu7QF-PgUb8108aLcA.png)

 **Semantics** refers to the meaning of a piece of code — for example "what effect does running that line of JavaScript have?", or "what purpose or role does that HTML element have" (rather than "what does it look like?".)

 - **Semantics in HTML**   
 In HTML, for example, the <h1> element is a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page."  


 - **benefits from writing semantic markup are as follows:**
- Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
- Screen readers can use it as a signpost to help visually impaired users navigate a page
- Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
- Suggests to the developer the type of data that will be populated  

- **Semantic elements** 
These are some of the roughly 100 semantic elements available: 
- <article>
- <aside>
- <details>
- <figcaption>
- <figure>
- <footer>
- <header>
- <main>
- <mark>
- <nav>
- <section>
- <summary>
- <time>    


 [For More Details of Semantics] (https://developer.mozilla.org/en-US/docs/Glossary/Semantics)  


### Markdown

 Markdown is a way to style text on the web.   
When using Markdown you can to : 
- control the display of the document.
- formatting words 
- adding images
- creating lists .... etc.  
 
for example : 
1. text : we can make text bold,italic.. etc 
for Bold like this add tow star * in first of word and the other in the end of word **word**  
2. List : we can make order and unorder list . 
3. images : we can add any image you want . 
4. Header ,code ,Links...etc .  

In GitHub they uses its own version of the Markdown syntax 
these Markdown syntax provides an additional set of useful feature Like : 

- Syntax highlighting .
- Task Lists.
- Tables.
- Emoji . 
- Etc... 

For More Details and how to use each of thim in GitHup please check the below Link 





# JavaScript
![JavaScript](https://datavisioner.net/wp-content/uploads/2020/04/javascript-illustration.png) 

**JavaScript ** (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat.

Do not confuse JavaScript with the Java programming language. Both "Java" and "JavaScript" are trademarks or registered trademarks of Oracle in the U.S. and other countries. However, the two programming languages have very different syntax, semantic, and use


- **Input Output in plain JavaScript**    
we are going to see how to get input from the user and combine that with the other two, to create a simple page that can great you.  

[For More Details and Example Please Click](https://code-maven.com/input-output-in-plain-javascript)

- **JavaScript Variables**  
JavaScript variables are containers for storing data values.  

Before 2015, using the var keyword was the only way to declare a JavaScript variable.

The 2015 version of JavaScript (ES6) allows the use of the const keyword to define a variable that cannot be reassigned, and the let keyword to define a variable with restricted scope.

Because it is a little complicated to describe the difference between these keywords, and because they are not supported in older browsers, the first part of this tutorial will most often use var.


** JavaScript Identifiers**   
All JavaScript variables must be identified with unique names.

These unique names are called identifiers.

Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).

The general rules for constructing names for variables (unique identifiers) are:

Names can contain letters, digits, underscores, and dollar signs.
Names must begin with a letter
Names can also begin with $ and _ (but we will not use it in this tutorial)
Names are case sensitive (y and Y are different variables)
Reserved words (like JavaScript keywords) cannot be used as names

[For More Details and Example Please Click](https://www.w3schools.com/js/js_variables.asp)

**JavaScript Data Types**  
- undefined
- Boolean 
- Number 
- String ..etc.  














