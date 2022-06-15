## Class 4 Reading Notes

UX extends beyond the graphics like UI,  but in every field or area that has users to enteract, store layout, ergonomics of vehicle, usability of a mobile -   as quoted from https://careerfoundry.com/en/blog/ux-design/what-is-user-experience-ux-design-everything-you-need-to-know-to-get-started/- 


1. What is a wireframe?

similar to architecetrual blueprint
a two dimensional skeletal outline of a webpage or app
provides clear overview of the page structure, layout, information arcitecture, user flow, funtionality, and intentended behaivors.
-since it reprepents the intitial product concept, styling, color,graphics are mininmum.

1. What is usually included in a wireframe? 
Logos, search fields, headeres, share buttons, and lorem ipsum placeholder text.

low fidelit - the most basic, useful for on the moment design or multple teams brainstorming

med fidelity - most common used. still avoid excess extractions, but more detailed assigned to specific componets to differentialte features.
different text weights, still black and white, but dif shades of grey,

(high fidelity wireframes include nav s stems, contact info, and footers.) 


(I enjoy how Squarespace builds their sites to have a different layout for mobile, and desktop. Website layout is something I care about,)

MAKING FIRST WIREFRAME:

1. Do your resserach

2. Prepare yoru research for quick reference

3.Make sure you have your user flow mapped out

4. Draft, don't draw. Sketch, don't illustrate

5. Add some detail and get testing

6. Start turning your wireframes into prototypes



HOW TO MAKE YOUR WIREFRAME GOOD:

1. Clarity - needs to answer the question of what the site page is, what the user can do, and if it satisifies their needs. It serves as the coder visual aid for layout of the site without being boggled down with aesthetic distrations

2. Confidence - Ease of navigation increases user confidence in brand.

3.Simplicity is key



MOZILLA GETING STARTED WITH HTML

My cat is very grumpy
<p>My cat is very grumpy</p>
<p> opening tag
MY cat is very grumpy (is the content)
</p> is the closing tag
<p>My cat is very grumpy</p> - the entire element is the openign, closing, and content


<!DOCTYPE html> — doctype. It is a required preamble. In the mists of time, when HTML was young (around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking and other useful things. However these days, they don't do much and are basically just needed to make sure your document behaves correctly. That's all you need to know for now.
<html></html> — the <html> element. This element wraps all the content on the entire page and is sometimes known as the root element.
<head></head> — the <head> element. This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, and more.
<meta charset="utf-8"> — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this and it can help avoid some problems later on.
<title></title> — the <title> element. This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when you bookmark/favorite it.
<body></body> — the <body> element. This contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks, or whatever else.


HEading levels (there are 6)
<!-- 4 heading levels: -->
<h1>My main title</h1>
<h2>My top level heading</h2>
<h3>My subheading</h3>
<h4>My sub-subheading</h4>

NOTE: Note: Anything in HTML between <!-- and --> is an HTML comment. The browser ignores comments as it renders the code. In other words, they are not visible on the page - just in the code. HTML comments are a way for you to write helpful notes about your code or logic.

SEMANTICS
In programming, Semantics refers to the meaning of a piece of code — for example "what effect does running that line of JavaScript have?", or "what purpose or role does that HTML element have" (rather than "what does it look like?".)

Semantics in JavaScript
In JavaScript, consider a function that takes a string parameter, and returns an <li> element with that string as its textContent. Would you need to look at the code to understand what the function did if it was called build('Peach'), or createLiWithContent('Peach')?

Semantics in CSS
In CSS, consider styling a list with li elements representing different types of fruits. Would you know what part of the DOM is being selected with div > ul > li, or .fruits__item?

Semantics in HTML
In HTML, for example, the <h1> element is a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page."