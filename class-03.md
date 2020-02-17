## Lists
***HTML provides us with three different types:***
Ordered lists: are lists where each item in the list is numbered 
- Unordered lists are lists that begin with a bullet point (rather than characters that indicate order). 
(The unordered list is created with the **ul** element.)
- Definition lists: are made up of a set of terms along with the definitions for each of those terms
      - The definition list is created with the **dl** element and usually consists of a series of terms and their definitions
      - **dt**This is used to contain the term being defined (the definition term).
      - **dd**This is used to contain the definition.
      
# Boxes
Control the box dimenstion by width and height
The most popular ways to specify the size of a box are to use
- Pixels(the most popular method that allow designers to accurately    control their size.)
 Percentages(When you use percentages, the size of the box is relative to the size of the browser window or, if the box is encased within another box, it is a percentage of the size of the containing box.

-or ems:( When you use ems, the size of the box is based on the size of text within it)

### Limiting Width
- Min width 
-max width

### limiting heigh

- min-height
- max-height





### Overflowing Content overflow
The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:
- hidden
- scroll


### Border, Margin and padding
- border: (Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.)
- Margin( Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.)
- Padding (Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents)


### Border Width
You can control the individual size of borders using four separate properties:
- border-top-width 
- border-right-width 
- border-bottom-width 
- border-left-width

### Border Style border-style
This border style can take the following values:
-	solid
-	dotted
-	dashed
-	double
-	groove
-	ridge
-	inset
-	outset
-	hidden or non
![..]( https://www.data2type.de/fileadmin/images/xml/border.jpg)

### You can individually change the styles of different borders using:
-	border-top-style 
-	border-left-style 
-	border-right-style 
-	border-bottom-style
also we can control the color of the bored from all the site


### Padding:
The padding property allows you to specify how much space should appear between the content of an element and its border.

### Margin:
The margin property controls the gap between boxes. Its value is commonly given in pixels, although you may also use percentages or ems

### Centering Content
to center  a box on a page you can set the left-margin and right –margin
also set the width for the box..
