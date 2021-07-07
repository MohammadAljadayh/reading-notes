# HTML Images,CSS Color & Text

## Image

Images can improve the design and the appearance of a web page.


-  The <img> element is used to add images to a
web page.
-  You must always specify a src attribute to indicate the
source of an image and an alt attribute to describe the
content of an image.
-  You should save images at the size you will be using
them on the web page and in the appropriate format.
- Photographs are best saved as JPEGs; illustrations or
logos that use flat colors are better saved as GIFs. 

![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/07/html-images-df.jpg) 

HTML Images Syntax   
- The HTML <img> tag is used to embed an image in a web page.

- Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

- The <img> tag is empty, it contains attributes only, and does not have a closing tag.

- The <img> tag has two required attributes:

src - Specifies the path to the image  
alt - Specifies an alternate text for the image  

example :  
** <img src="wrongname.gif" alt="Flowers in jordan"> ** 

-----------------------------------------------------

## Color  
- Color not only brings your site to life, but also helps
convey the mood and evokes reactions.
-  There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.
-  Color pickers can help you find the color you want.
- It is important to ensure that there is enough contrast
between any text and the background color (otherwise
people will not be able to read your content).
- CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA.
- CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.

![](https://cdn.educba.com/academy/wp-content/uploads/2020/03/CSS-Color-Codes.jpg.webp)

Colors in CSS can be specified by the following methods:  

- Hexadecimal colors  
A hexadecimal color is specified with: #RRGGBB, where the RR (red), GG (green) and BB (blue) hexadecimal   
example :  #0000ff value is rendered as blue   
- Hexadecimal colors with transparency  
A hexadecimal color is specified with: #RRGGBB. To add transparency, add two additional digits between 00 and FF. 
example : #ff000080;
- RGB colors 
An RGB color value is specified with the rgb() function, which has the following syntax:

rgb(red, green, blue)  

- RGBA colors 
RGBA color values are an extension of RGB color values with an alpha channel - which specifies the opacity of the object.
- HSL colors
HSL stands for hue, saturation, and lightness - and represents a cylindrical-coordinate representation of colors.

An HSL color value is specified with the hsl() function, which has the following syntax:

hsl(hue, saturation, lightness)  
- HSLA colors 
HSLA color values are an extension of HSL color values with an alpha channel - which specifies the opacity of the object.

An HSLA color value is specified with the hsla() function, which has the following syntax:

hsla(hue, saturation, lightness, alpha)

- Predefined/Cross-browser color names
With the currentcolor keyword

140 color names are predefined in the HTML and CSS color specification.

For example: blue, red, coral, brown, etc:


---------------------------------------------

# CSS Text 
- There are properties to control the choice of font, size,
weight, style, and spacing.
-  There is a limited choice of fonts that you can assume
most people will have installed.
-  If you want to use a wider range of typefaces there are
several options, but you need to have the right license
to use them.
- You can control the space between lines of text,
individual letters, and words. Text can also be aligned
to the left, right, center, or justified. It can also be
indented.
-  You can use pseudo-classes to change the style of an
element when a user hovers over or clicks on text, or
when they have visited a link.  

![](https://cdn.educba.com/academy/wp-content/uploads/2019/08/CSS-Text-Formatting-Properties2.png)
### CSS has a lot of properties for formatting text.

- #### Text Color
The color property is used to set the color of the text. The color is specified by:

- a color name - like "red"
- a HEX value - like "#ff0000"
- an RGB value - like "rgb(255,0,0)" 

- #### Text Color and Background Color
background-color: lightgrey;  
  color: blue; 

 -  #### Text Alignment
The text-align property is used to set the horizontal alignment of a text.

A text can be left or right aligned, centered, or justified.

The following example shows center aligned, and left and right aligned text (left alignment is default if text direction is left-to-right, and right alignment is default if text direction is right-to-left 

- #### Text Direction
The direction and unicode-bidi properties can be used to change the text direction of an element 

- ##### Text Decoration
The text-decoration property is used to set or remove decorations from text.

The value text-decoration: none; is often used to remove underlines from links 

- #### Text Shadow
The text-shadow property adds shadow to text.

In its simplest use, you only specify the horizontal shadow (2px) and the vertical shadow (2px)





