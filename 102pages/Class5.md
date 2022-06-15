# Class 5 Reading Notes 

Say goodybe to the few style template options from Github and hello to my new skills in CSS. No art skills required, just CSS Cheatsheeats and Google to get the layout that you want. 

In laymen terms:
CSS is a language that specifies how documents are shown to users: their style, the layout, the colors.

CSS can be used to create layouts like making columns, and even effects like animation.

Super fascinating to know is that CSS works  hard to never change things in a way that would break old websites. (The unintentionally while not written there, I'm sure was silent.) Although it is the browser rules that keep changing, vs CSS.

Teenage me is grateful to have embarrassing anime fan sites permanently etched in time as current me has no access to burn them from the internet (and secretly proud anyways).

## Adding CSS to document:

Three methods, best practice is to 
Create a file in the same folder as your HTML document and save it as styles.css. The .css extension shows that this is a CSS file.
To link styles.css to index.html, add the following line somewhere inside the <head> of the HTML document:

It will look like this: < link rel="stylesheet" href="styles.css" > **OMIT SPACE AFTER FIRST BRACKET, AND BEFORE LAST BRACKET**

Default is bold headers and lists are bullets. We use CSS to choose other layouts.

### Classes - 
a way to select a subset of the elements without changing the others.

*during reading made a text html and css enivorment to play around with CSS* (With Notepad)

A **selector** targets HTML to apply styles to content. . If CSS is not applying to content as expected, your selector may not match the way you think it should match.
Each CSS rule starts with a selector — or a list of selectors — in order to tell the browser which element or elements the rules should apply to. All the examples below are valid selectors or lists of selectors.

The CSS language has rules to control which selector is stronger in the event of a conflict. These rules are called cascade and specificity. In the code block below, we define two rules for the p selector, but the paragraph text will be blue. This is because the declaration that sets the paragraph text to blue appears later in the stylesheet. Later styles replace conflicting styles that appear earlier in the stylesheet. This is the cascade rule.

### Properties and values
At its most basic level, CSS consists of two components:

	* 	• Properties: These are human-readable identifiers that indicate which stylistic features you want to modify. For example, font-size, width, background-color.


	* Values: Each property is assigned a value. This value indicates how to style the property

When a property is paired with a value, this pairing is called a CSS declaration. CSS declarations are found within CSS Declaration Blocks. In the example below, highlighting identifies the CSS declaration block.

Finally, CSS declaration blocks are paired with selectors to produce CSS rulesets (or CSS rules). The example below contains two rules: one for the h1 selector and one for the p selector. The colored highlighting identifies the h1 rule.

Setting CSS properties to specific values is the primary way of defining layout and styling for a document. The CSS engine calculates which declarations apply to every single element of a page.
CSS properties and values are case-insensitive. The property and value in a property-value pair are separated by a colon (:).


	* Warning: If a property is unknown, or if a value is not valid for a given property, the declaration is processed as invalid. It is completely ignored by the browser's CSS engine
    
    
	* Warning: In CSS (and other web standards), it has been agreed that US spelling is the standard where there is language variation or uncertainty. For example, colour should be spelled color, as colour will not work

## How Does CSS Actually Work:
From <https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_works> 

1. The browser loads the HTML (e.g. receives it from the network).
2. It converts the HTML into a DOM (Document Object Model). The DOM represents the document in the computer's memory. The DOM is explained in a bit more detail in the next section.
3. The browser then fetches most of the resources that are linked to by the HTML document, such as embedded images and videos ... and linked CSS! JavaScript is handled a bit later on in the process, and we won't talk about it here to keep things simpler.
4. The browser parses the fetched CSS, and sorts the different rules by their selector types into different "buckets", e.g. element, class, ID, and so on. Based on the selectors it finds, it works out which rules should be applied to which nodes in the DOM, and attaches style to them as required (this intermediate step is called a render tree).
5. The render tree is laid out in the structure it should appear in after the rules have been applied to it.
The visual display of the page is shown on the screen (this stage is called painting).

### About the DOM

A DOM has a tree-like structure. Each element, attribute, and piece of text in the markup language becomes a DOM node in the tree structure. The nodes are defined by their relationship to other DOM nodes. Some elements are parents of child nodes, and child nodes have siblings.
Understanding the DOM helps you design, debug and maintain your CSS because the DOM is where your CSS and the document's content meet up. When you start working with browser DevTools you will be navigating the DOM as you select items in order to see which rules apply.

From <https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_works> 

## **INTERESTING TIDBIT: IF THE BROWSER DOESN'T UNDERSTAND THE CSS IT WILL SKIP IT.**
 you can use new CSS as an enhancement, knowing that no error will occur if it is not understood — the browser will either get the new feature or not. This enables basic fallback styling.

From <https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_works#a_real_dom_representation> 

## Cascading Order
Cascading Order
What style will be used when there is more than one style specified for an HTML element?
All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:
* Inline style (inside an HTML element)
* External and internal style sheets (in the head section)
* Browser defaultSo, an inline style has the highest priority, and will override external and internal styles and browser defaults.

From <https://www.w3schools.com/css/css_howto.asp> 

## **CSS Color Examples:**

* Set the text color with a HEX value:
body {color: #92a8d1;}

* Set the text color with an RGB value:
body {color: rgb(201, 76, 76);}

* Set the text color with an RGBA value: body {color: rgba(201, 76, 76, 0.6);}

* Set the text color with a HSL value:
body {color: hsl(89, 43%, 51%);}

* Set the text color with a HSLA value:
body {color: hsla(89, 43%, 51%, 0.6);}

From <https://www.w3schools.com/cssref/pr_text_color.asp> 

### **CSS Syntax**
color: color|initial|inherit;

### Property Values

>* color	Specifies the text color. Look at CSS Color Values for a complete list of possible color values.
>* initial	Sets this property to its default value. Read about initial	
> * inherit	Inherits this property from its parent element. Read about inherit	

From <https://www.w3schools.com/cssref/pr_text_color.asp> 

## **CSS Resets**
In a nutshell, a CSS reset removes default styling from page elements so that you are “starting fresh” with the attributes you choose to apply. This is important for two reasons. One, puts all browsers on a level playing field. Different browsers apply different default styling to elements, so if you are looking to have your website look the same in all the different browsers (you are), a CSS reset is important. Two, it allows you to “think forwards” as far as applying attributes like margin and padding to page elements. Instead of having to “think backwords” in removing attributes from elements, you can only apply them to elements you know need them.

From <https://css-tricks.com/poll-results-what-css-reset-do-you-use/> 


### Collection of CSS Resets
https://perishablepress.com/a-killer-collection-of-global-css-reset-styles/

Snippet from article:
>Eric Meyer’s CSS Reset
As discussed in the original article, CSS guru Erik Meyer set forth to create a universal set of reset styles. This is heavy-duty stuff, effectively neutralizing virtually every significant aspect of default, browser-applied CSS rules. This reset ruleset is far-reaching, resetting many different CSS properties. Keep this in mind during subsequent CSS development. If you experience unexpected, unexplainable behavior happening with your styles, begin by investigating and eliminating suspected aspects of this code (or any newly added reset styles) as the possible culprit — you’ll thank yourself later.. ;) 

From <https://perishablepress.com/a-killer-collection-of-global-css-reset-styles/> 

