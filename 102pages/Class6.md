# Class 6 Reading Notes

## What is JavaScript?

JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions

While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles.

From <https://developer.mozilla.org/en-US/docs/Web/JavaScript> 

JavaScript is a scripting or programming language that allows you to implement complex features on web pages — every time a web page does more than just sit there and display static information for you to look at — displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, etc. — you can bet that JavaScript is probably involved. It is the third layer of the layer cake of standard web technologies, two of which (HTML and CSS) we have covered in much more detail in other parts of the Learning Area.

• HTML is the markup language that we use to structure and give meaning to our web content, for example defining paragraphs, headings, and data tables, or embedding images and videos in the page.
• CSS is a language of style rules that we use to apply styling to our HTML content, for example setting background colors and fonts, and laying out our content in multiple columns.
• JavaScript is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything else. (Okay, not everything, but it is amazing what you can achieve with a few lines of JavaScript code.)

From <https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript> 

## What can JavaScript Do?
The core client-side JavaScript language consists of some common programming features that allow you to do things like:
* Store useful values inside variables. In the above example for instance, we ask for a new name to be entered then store that name in a variable called name.

* Operations on pieces of text (known as "strings" in programming). In the above example we take the string "Player 1: " and join it to the name variable to create the complete text label, e.g. "Player 1: Chris".

* Running code in response to certain events occurring on a web page. We used a click event in our example above to detect when the label is clicked and then run the code that updates the text label.

* And much more!

What is even more exciting however is the functionality built on top of the client-side JavaScript language. So-called Application Programming Interfaces (APIs) provide you with extra superpowers to use in your JavaScript code.

From <https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript> 

## What are API's?
APIs are ready-made sets of code building blocks that allow a developer to implement programs that would otherwise be hard or impossible to implement. They do the same thing for programming that ready-made furniture kits do for home building — it is much easier to take ready-cut panels and screw them together to make a bookshelf than it is to work out the design yourself, go and find the correct wood, cut all the panels to the right size and shape, find the correct-sized screws, and then put them together to make a bookshelf.

## JavaScript Running Order:
When the browser encounters a block of JavaScript, it generally runs it in order, from top to bottom. This means that you need to be careful what order you put things in.

## Server Side vs Client Side Code:
Server-side versus client-side code
You might also hear the terms server-side and client-side code, especially in the context of web development. Client-side code is code that is run on the user's computer — when a web page is viewed, the page's client-side code is downloaded, then run and displayed by the browser. In this module we are explicitly talking about client-side JavaScript.
Server-side code on the other hand is run on the server, then its results are downloaded and displayed in the browser. Examples of popular server-side web languages include PHP, Python, Ruby, ASP.NET and... JavaScript! JavaScript can also be used as a server-side language, for example in the popular Node.js environment — you can find out more about server-side JavaScript in our Dynamic Websites – Server-side programming topic.

## Dynamic VS Static Code:
The word dynamic is used to describe both client-side JavaScript, and server-side languages — it refers to the ability to update the display of a web page/app to show different things in different circumstances, generating new content as required. Server-side code dynamically generates new content on the server, e.g. pulling data from a database, whereas client-side JavaScript dynamically generates new content inside the browser on the client, e.g. creating a new HTML table, filling it with data requested from the server, then displaying the table in a web page shown to the user. The meaning is slightly different in the two contexts, but related, and both approaches (server-side and client-side) usually work together.
A web page with no dynamically updating content is referred to as static — it just shows the same content all the time.

## How Do You Add JavaScript To Your Page?
How do you add JavaScript to your page?
JavaScript is applied to your HTML page in a similar manner to CSS. Whereas CSS uses < link > elements to apply external stylesheets and < style > elements to apply internal stylesheets to HTML, JavaScript only needs one friend in the world of HTML — the < script > element. Let's learn how this works.
Internal JavaScript
> * First of all, make a local copy of our example file apply-javascript.html. Save it in a directory somewhere sensible.
>* Open the file in your web browser and in your text editor. You'll see that the HTML creates a simple web page containing a clickable button.
> * Next, go to your text editor and add the following in your head — just before your closing < /head> tag:
< script>

// JavaScript goes here< /script>

## The 4 Ways to Declare a JavaScript Variable:

* Using var
* Using let
* Using const
* Using nothing

From <https://www.w3schools.com/js/js_variables.asp> 

## What are Variables?
Variables are containers for storing data (storing data values).
In this example, x, y, and z, are variables, declared with the var keyword:

## JavaScript Identifiers

All JavaScript variables must be identified with unique names.

These unique names are called identifiers.
Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).

The general rules for constructing names for variables (unique identifiers) are:

* Names can contain letters, digits, underscores, and dollar signs.
* Names must begin with a letter
* Names can also begin with $ and _ (but we will not use it in this tutorial)
 Names are case sensitive (y and Y are different variables)
* Reserved words (like JavaScript keywords) cannot be used as names

## LECTURE NOTES

javascript: is the muscle of the website, makes it move

HTM - structure/content
CSS WHAT it looks like
js - what you do!!!

Declare your variable

let - value may change (VARIABLE)
var - older browesrs- not genrally used anymore, can give unexpected behavior
const - something that isnt' supposed to change (CONSTANT)

data types: numbers, strings
number 1, 2, 3, 4
string - "1" "Hi how are ya?"

variables and case sensitiivity


let number = 1
let Number  = "one"

number  - 1
Number - "one"

--Lab walktrhough--
create a new file with .js extension
usually app.js

start with 'use strict'; 

each statement in Js also endsi n semicolon

THe = sign is an assignment operator. it does not mean equal. it ASSIGNS

if (userName ==== "Joraya" 
|| for conditional

such as if (userName ==="Joraya" || username 


example:
declaring variable userName  = prompt ("text?)

for the example it is linked in the body
float element to get text to wrap around images and elements
--

REMEMBER: WHEN I WANT ELEMENTS TO STAY ON SAME LINE, DISPLAY; INLINE-BLOCK; IS WAY TO GO

## VIDEO NOTES: HOW COMPUTERS WORK FROM CODE.ORG

1. What makes a computer a computer?
They need these 4 main things, (and modern devices have more but these are all that are needed):

* Inpiut
* Storage
* PRocessing
* Output

2. How Computers Work: BInary & Data
 --to be added
