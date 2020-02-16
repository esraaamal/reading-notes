# To create a website Pages we foucus on three issue:
1- Html 
2- Css
3- practical

>About **Html**:
### Html hyper text markup language..it use to bulid the structure of the web Pages Webpages Organized through many tag used in Html
### To divide the page in order style…to make the code more readable and easier 


>About **Css**:
Css :refrence to cascading style sheet, that enable control of style ,layout of the webpages.
CSS properties fall on one of two categories:
- presentation: How to control things like the color of text, the fonts..eltc
- layout: How to control where the different elements are positioned on the screen
__________________________
>About **practical**:
*We look at new tags in HTML5 to help describe the structure of your pages*
*HTML5 is the latest version of HTML*
Because HTML5 build on previous versions of these languages, learning 
these means you will also be able to understand the earlier versions of them
_______________________
**When we create a webpage the browser send a request**
for special computer  known as webserver 
# but how websever work ?
that special computer connected to the internet directly to send 
webpage out  to people who send the request …
________________________
To find our websever that host our website ..first thing the browser connect to DNS …
But what `DNS `
`DNS` is  a domain name system also it is a `TCP/ip` protocol that maps ip addresses to their symbolic name
The DNS DataBase consists of the name of a site and a corresponding ip Number

_______________________
# Introduction:
We use structure to write webpages to make it more easier to understand
Html describes the structure of pages by adding a code to the words we
 want to appear on the page ..

Attributes Tell Us More About Elements
...
Where lang is the attribute name
And “en-us” is the attribute value

Here an attribute called lang is used to indicate the
language used in this element. The value of this attribute on this page specifies it is in US English.
_____________________________________
title tag : Anything written between the
title tags will appear in the
title bar (or tabs) at the top of
the browser window

**any Attributes require a name and a value.

# Ch8 Extra markup:

The different versions of HTML and how to indicate which
version you are using each new version designed to be an improvement 
on the last version (with new element and attribute)
but not all the user can view all of the latest features and markup 
..becuase not all the user have installed the latest browser 

# Example of a new version 
***HTML4 
All the element were available in Html5 was in Html vesrsion..
But there are some tags that are not recommended to use them any  more ex.
(center element for centering content on the page ,<font> :for controlling the appearance of text)
Html 1.0(released 2000)
Aslo called XTHML

# New version that follow some strict rules about writing markup,for example:
1- every element need to close tap 
2- attribute name in lower case
3- all attribute required avalue ,and all value placed in double quotes
Eltc….
One of the key benefits of this
change was that XHTML works
seamlessly with other programs
that are written to create and
process XML documents.

In order to help web page
authors move to this new syntax,
two main flavors of XHTML 1.0
were created:
- Strict XHTML 1.0, where
authors had to follow the rules
to the letter
- Transitional XHTML 1.0,
where authors could still use
presentational elements (such
as center and font).

# HTML5 
In html5 intrduce some element do not need to close tag also this version interduce new eelement and attribute
Even the HTML5 was not completed but 
The major browser started implemented many of new features 
Because there have been several versions of HTML
 each web page should begin with a DOCTYPE declaration to tell
 a browser which version of HTML the page is using
________________________
We use  <!DOCTYPE html> to Html5 version
_______________________________
Comment in Html <!-- -->
The comment is not visible for the user only for the coder …
comments will make it much easier to understand.the code
___________________

ID Attribute: every element can carry the id attribute
This id used to uniquely identify the element from other elements on the page a;so it allows you to style the element differently than any other instance 
_____________________________
Class Attribute: every element can carry the class attribute
Class attribute in any element can can share the same value
__________________________
Hint:using these attribure does not effect the presentation of an element ..it only change their appearance and style 
# Block element:
Some elements will always appear to start on a new line in the browser window. These are known as block leve elements.
___________________
# Inline Elements:
Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements.
Examples of inline elements are

_________________________
# Grouping Text  and Elements In a Block:
<div>
The <div> element allows you to
group a set of elements together
in one block-level box.

# Grouping Text and Elements Inline
 The span element acts like an inline equivalent of the div
element. It is used to either:
- Contain a section of text where there is no other suitable element to differentiate it from its surrounding text
- Contain a number of inline elements ,The most common reason why people use
  elements is so that they can control the appearance of the content of these elements using CSS.


_____________________
# iframes:

An iframe is like a little window that has been cut into your page — and in that
window you can see another page. The term iframe is an abbreviation of inline frame.
One common use of iframes (**that you may have seen on various websites**) is to embed a Google Map into a page

______________________
# meta
The meta element lives inside the element and contains information about that web page,
It is not visible to users.
Meta is a self closing tags
Meta telling search engines
about your page

____________________
# Escape Characters:
angled brackets ,if you want these characters to appear on your page..
For example,
to write a left angled bracket,
you can use either &lt; or
&#60;. For an ampersand, you
can use either &amp; or &#38; 


______________________
# CH 17 : HTML5 Layout
We can control the page layout
By div element, so we used class or id attributes
to indicate the role of the <div> element in the structure of the page.
In HTML5 many of the <div> element have been replaced by new layout..
For example, the header sits
inside a new <header> element,
the navigation in a <nav>
element, and the articles are in
individual <article> elements


# The side  element has two
purposes, depending on whetherit is inside an <article>
element or not.

When the aside element
is used inside an artical
element, it should contain
information that is related to the
article..
 
**but When the aside element is
used outside of an artical element, it acts as a container for content that is related to
the entire page…**

For example,
it might contain links to other
sections of the site, a list of
recent posts, a search box, or
recent tweets by the author


<section> element
groups related items together,
it may contain several distinct
<article> elements that have a
common theme or purpose.

if you have a
page with a long article, the
<section> element can be
used to split the article up into
separate sections.


# The section element should
not be used as a wrapper for
the entire page (unless the
page only contains one distinct
piece of content(
 If you want a
containing element for the entire
page, that job is still best left to the div element.


# Heading Groups: hgroup
The purpose of the hgroup
element is to group together a
set of one or more h1 through
h6 elements so that they are
treated as one single heading


# Figures:
Used to contain any content that is
referenced from the main flow of
an article (not just images).
Examples of usage include:
- Images
- Videos
- Graphs
- Diagrams
- Code samples
- Text that supports the main

**The figure element should
also contain a figcaption
element which provides a text
decription for the content of
the figure element


# Ch18:
**Every website should be designed for the
Target Audience: individuals**
- What is the age range of your target audience?
- Will your site appeal to more women or men? What is the mix?
- Which country do your visitors live in?
- Do they live in urban or rural areas?
- What is the average income of visitors?
- What level of education do they have?
- What is their marital or family status?
- What is their occupation?
- How many hours do they work per week?
- How often do they use the web?
- What kind of device do they use to access the web?



# Java script:
What mean of script 
A script is a series of instructions that a computer can follow to achieve a goal.
A browser can use diffrenet 


