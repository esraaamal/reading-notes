##  point style 
**list-style-type**
The list-style-type property
allows you to control the shape or style of a bullet point (also
known as a marker)
It can be used on rules that
apply to the <ol>, <ul>, and <li>
elements.

## Ordered Lists
For an ordered (numbered) list
you can use the following values:
- decimal
1 2 3
- decimal-leading-zero
01 02 03
- lower-alpha
a b c
- upper-alpha
A B C
- lower-roman
i. ii. iii.
- upper-roman
## lise-style-postion:

also we can specify an **image** to act
as a bullet point using the
list-style-image property.

## list-style-position:
- outside
The marker sits to the left of the
block of text. (This is the default
behaviour if this property is not
used.)
- inside
The marker sits inside the box of
text (which is indented).
### some table properties:
- **width** to set the width of the
table
- **padding** to set the space
between the border of each table
cell and its content
- **text-transform** to convert the
content of the table headers to
uppercase
- **letter-spacing**, **font-size**
to add additional styling to the
content of the table headers

**border-top**, **border-bottom**
to set borders above and below
the table headers
**text-align** to align the writing
to the left of some table cells and
to the right of the others

**background-color** to change
the background color of the
alternating table rows

**hover** to highlight a table row
when a user's mouse goes over it
## empty-cells
if we want to
explicitly show or hide borders
on any empty cells then you
should use this property.
It can take one of three values:
- show
This shows the borders of any
empty cells.
- hide
This hides the borders of any
empty cells.
- inherit
If you have one table nested
inside another, the inherit
value instructs the table cells to
obey the rules of the containing
table.

This example demonstrates the
CSS properties commonly used
with text inputs, most of which
you have already met.
font-size sets the size of the
text entered by the user.
color sets the text color, and
background-color sets the
background color of the input.
border adds a border around
the edge of the input box, and
border-radius can be used
to create rounded corners (for
browsers that support this
property).
The :focus pseudo-class is
used to change the background
color of the text input when it
is being used, and the :hover
psuedo-class applies the same
styles when the user hovers over
them.
background-image adds a
background image to the box.
Because there is a different
image for each input, we are
using an attribute selector
looking for the value of the id
attribute on each input.

...
## List markers can be given different appearances
## using the list-style-type and list-style image properties.



## When the user interacts with the HTML on a web page, there are threesteps involved 
## in getting it to trigger some JavaScript code.Together these steps are known as event handling.

- Select t he elementnode(s) you want thescript to respond to.
- Indicate which event onthe selected node(s) willtrigger the response.
- State the code you wantto run when the eventoccurs. 

