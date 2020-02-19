● Include an image in your web pages using HTML 
● Pick which image format to use 
● Show an image at the right size 
● Optimize an image for use on the web to make pages load faster

### To add an image into the page you need to use an  (img) element. . It must carry the following two attributes:src+alt +title 

### You will also often see an Error! Filename not specified.element use two other attributes that specify its size: height This specifies the height of the image in pixels. width This specifies the width of the image in pixels.

### Where you place the image in the code is important because browsers show HTML elements in one of two ways:

-block elements always appear on a new line

-inline elements sit within a block level element and do not start on a new line

### Forgrounding color
***The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways***
-	RGB VALUES
-	HEX CODES
-	COLOR NAMES

 
### Understanding Color
*Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker*

***CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).***

***Because some browsers will not recognize RGBA colors, you can offer a fallback so that they display a solid color. If there are two rules that apply to the same element, the latter of the two will take priority. To create the fallback, you can specify a color as a hex code, color name or RGB value, followed by the rule that specifies an RGBA value. If the browser understands RGBA colors it will use that rule. If it doesn't, it will use the RGB value.***

CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation, and lightness values.

![..]( https://img.favpng.com/19/22/14/



The hsl color property has been introduced in CSS3 as an alternative way to specify colors.
The value of the property starts with the letters hsl, followed by individual values inside parentheses for:

hue This is expressed as an angle (between 0 and 360 degrees). saturation This is expressed as a percentage. lightness This is expressed as a percentage with 0% being white, 50% being normal, and 100% being black
alpha This is expressed as a number between 0 and 1.0. For example, 0.5 represents 50% transparency, and 0.75 represents 75% transparency.

### CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.


### Typeface Terminology:
-	Serif
-	Sans-Serif
-	Monospace
***There are three pseudo-classes that allow you to change the appearance of elements when a user is interacting with them***
:hover
 :active
 :focus 


##### You can control the space between lines of text, individual letters, and words. Text can also be aligned to the left, right, center, or justified. It can also be indented. X You can use pseudo-classes to change the style of an element when a user hovers over or clicks on text, or when they have visited a link.





