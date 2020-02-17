# Ch2:text style
## HTML elements are used to describe the `structure` of the page ex:
- Heading (Html has six levels of heading)
- Paragraph
- Bold and Italic
- Superscript(use fir example for suffises of date) and Subscrip (used for chemical formulas)
- White Space(only show one space )
- Line Breaks (br)
- Horizontal(hr:to create a brake between themes)

## HTML elements  also provide `semantic` information ex:

- Strong (t indicates that its content has strong importance.)
- Emphasis(indicates emphasis that subtly changes the meaning of a sentence.)
- Quotation(blockquote: used for longer quotes that take up an entire paragrap)
- Quotation(q: used for shorter quotes)
- Abbreviations and Acronyms (abbr and acronym: used. A title attribute on the opening tag is used to specify the full term.)
- Citations (used in referencing)
- Definitions(used to indicate the defining instance of a new term.)
- Address(use: to contain contact details for the author of the page)
- Changes to Content( ins and del elements)


# Ch10:make web pages more attractive using CSS
-	BLOCK  and INLINE ELEMENTS
-	Example Styles :
    - Boxes (Width and height Borders (color, width, and style) Background 
     color and images ,Position in the browser window)
    - Text(Typeface Size Color Italics, bold, uppercase, lowercase, small-cap)
    
     ## CSS works by associating rules with HTML elements.
     ## CSS rule contains two parts:
- a selector (**indicate which element the rule applies to**)
- a declaration( **indicate how the elements referred to in the selector should be styled**)

## CSS declarations sit inside curly brackets and each is made up of two parts: 
-	a property (indicate the aspects of the element you want to change)
-	a value(specify the settings you want to use for the chosen properties)
To Using  an External CSS we need the link element

Link lives inside the head  element. It should use three attributes
-	Href(This specifies the path to the CSS file)
-	Type(This attribute specifies the type of document being linked to)
-	Rel(This specifies the relationship between the HTML page and the file it is linked to)


### To Using Internal CSS we need style element
### Style element usually also sits inside the head  element of the page.

**When building a site with more than one page, we should use an external CSS style sheet. This:  - Allows all pages to use the same style rules (rather than repeating them in each page).**
-  Keeps the content separate from how the page looks. 
- Means you can change the styles used across all pages by altering just one file (rather than each individual page).

### There are many different types of CSS selector that allow you to 
### target rules to specific elements in an HTML document
### also CSS selectors are case sensitive, so they must match element names and attribute values exactly
[more css  selector resourse](https://www.w3schools.com/cssref/css_selectors.asp)


## why use External Style Sheets?
-	All of the web pages can share the same style sheet
-	code does not need to be repeated in every pag
-	 rest of the site will load faster
-	The HTML code will be easier to read and edit because it does not have lots of CSS rules


# Java script:
  is a script is a series of instructions that a computer can follow one-by-one.
### STATEMENTS
-	Each individual instruction or step is known as a statement. 
-	Statements should end with a semicolon.	
-	curly braces indicate the start and end of a code block(Each code block could contain many more statements.)
 
 
 ### COMMENTSuse to: explain what your code does.
The comment has two different syntax :
-	for multi-line
-	for single-line


### VARIABLE
WHAT IS A VARIABLE?
-	It is a temporarily store to save the bits of information
-	A variable is a good name for this concept because the data stored in a variable can change (or vary) each time a script runs.
-	The use of variables to represent numbers or other kinds of data is very similar to the concept of algebra
-	Befor using a variable we should declear the variable first by giving it a name
-	Once we create a variable we give it a value

### DATA TYPES:
-	Numeric data type
-	String data type(consists of letters and other characters.)
-	Boolean data type(can have only  one of two values: true or false.)
-	Array
-	Object
-	Null
-	Undefined


##### Programmers sometimes use shorthand to create variables
Here are three variations of how to declare variables and assign them values

-	 Variables are declared and values assigned in the same statement. 
-	 Three variables are declared on the same line, then values assigned to each. 
-	Two variables are declared and assigned values on the same line. Then one is declared and assigned a value on the next line.


##### RULES FOR NAMING VARIABLES:
-  The name must begin with a letter, dollar sign ,or an underscore 
It must not start with a number
- The name can contain letters, numbers, dollar sign , or an underscore .
 Note that you must not use a dash or a period in a variable name.
-	You cannot use keywords or reserved words. Keywords are special words that tell the interpreter to do something. For example, var is a keyword used to declare a variable. Reserved words are ones that may be used in a future version of JavaScript.
-	All variables are case sensitive, so score and Score would be different variable names, but it is bad practice to create two variables that have the same name using different cases.
-	Use a name that describes the kind of information that the variable stores. For example, fi rstName might be used to store a person's first name, l astNarne for their last name, and age for their age.



### ARRAYS:
*using array when we are working with a list or a set of values that are related to each other
The values are assigned to the array inside a pair of square brackets, and each value is separated by a comma. 
The values in the array do not need to be *the same data type, so you can store* 
a string, a number and a Boolean all in the same array
Values in an array are accessed as if they are in a numbered list.
 *It is important to know that the numbering of this list starts at zero (not one)*
*Each item in an array is automatically given a number called an index*

### EXPRESSIONS:
An expression evaluates into (results in) a single value, there are two types of expressions.
-	EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE
-	EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE

### OPERATORS:
Expressions rely on things called operators; they allow programmers to create a single value from one or more values.
 Type of operator:
-	ASSIGNMENT OPERATORS
-	ARITHMETIC OPERATORS
-	STRING OPERATORS
-	COMPARISON OPERATORS
-	LOGICAL OPERATORS
![..](https://1.bp.blogspot.com/-N4BTD_uvqPg/XJh7TKNaH3I/AAAAAAAACI4/X73EKI50S-QGxynBSiT5i3kWjJS0vbCIgCLcBGAs/s1600/Arithmetic%2Boperators.png)

### SWITCH STATEMENTS
A switch statement starts with a variable called the switch value.
Each case indicates a possible value for this variable and the code that 
should run if the variable matches that value.

![..]( https://media.geeksforgeeks.org/wp-content/uploads/switch.png)

