# Read: 01 - Introductory HTML and JavaScript

## *HTML & CSS* - Jon Duckett

## **Chapter 1: Structure**

* Great advice on setting up website. It mentioned to think of actual news papers or letters, or things in print and how they are set up. Headers, subheadings, bold, italics, etc. Formatting and structure of text makes it easier to read and absorb the content. Something to keep in mind when I am doing layouts.

Tags introduced
    * Headers h1-h6, p, body, html, title, footer

### Atributes

"Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign." - Duckett

book example: *no spaces in tags*

> &lt;p lang="en-us">Paragraph in English /p&gt;

## **Chapter 8: Extra Markup**

### Comments
 

&lt;!-- (text goes here) -->

It is good to use to keep track of steps while learning, like a written outline partnered with a wireframe. 

Also good way to organize content if on group work, or seperate content by content as well.

### ID Attribute

* The values should start with letter or underscore (no number or other characters)
* Needs to be unique. Can help with CSS and JS styling.
* A **global attribute** because it can be used on any element.

Example:

&lt;p id="attribute name"> Content that I want in this attribute. &lt;/p&gt;

### Class Attribute

* A way to identify several elementsas being different from the other elements on the page.
* per book using these attributes
does not affect the presentation
of an element. It will only change
their appearance if there is a CSS
rule that indicates it should be
displayed differently.

### Block Elements

* Are elements that will always appear to start on a new line.

Examples are  h1, p, ul, li tags

### Inline Elements

* Always appear to continue on the
same line as their neighbouring
elements.

Examples are &lt;a&gt; &lt;b&gt; &lt;em&gt; &lt;img&gt;

### Group Text & Elements In a Block

**&lt;div&gt;**

>The div  element allows you to
group a set of elements together
in one block-level box.

Advice given to use a html to state what the div is for.

### Grouping Text & Elements Inline

**&lt;span&gt;**

Reasons for span per book: Direct Quotes

> 1. Contain a section of text
where there is no other suitable
element to differentiate it from
its surrounding text
>2. Contain a number of inline
elements

The most common reason why
people use &lt;span&gt; elements
is so that they can control the
appearance of the content of
these elements using CSS.
You will usually see that a class
or id attribute is used with
&lt;span&gt; elements:

●To explain the purpose of this
&lt;span&gt; element

●So that CSS styles can be
applied to elements that
have specific values for these
attributes

### IFRAMES

**&lt;iframe&gt;**

> "iframe is like a little window
that has been cut into your
page — and in that window you
can see another page. The term
iframe is an abbreviation of inline frame."

Example Code Provided:

&lt;iframe width="450" height="350"
src="https://maps.google.co.uk/maps?q=moma+new+york&amp;output=embed">
		&lt;/iframe&gt;

### Information About Your Pages

**&lt;meta&gt;**

> "The &lt;meta&gt; element lives
inside the &lt;head&gt; element and contains information about that web page.
It is not visible to users but
fulfills a number of purposes
such as telling search engines
about your page, who created
it, and whether or not it is time
sensitive.
The &lt;meta&gt; element is an empty element so it does not have a
closing tag. It uses attributes to
carry the information."

## Escape Characters:

To write an element and attribute into your page so that the code is shown to the user rather than being processed by the browser you need to escape the angled brackets and quotation marks. 

Example &lt; is written as amperstand,lt; 
*From <https://www.htmlandcssbook.com/extras/html-escape-codes/>*


## Chapter 17:


## Chapter 18: 


## *Javascript and JQuery - Jon Duckett*

## Intro

* Basically going over the layout and stucture of this book and assumes a knowledge of html and CSS.

## Chapter 1:

* What are scripts and how to make them?



## Things I want to know more about