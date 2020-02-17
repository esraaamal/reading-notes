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


