# Code 102: Class 2 Reading Notes

## *HTML & CSS* - Jon Duckett

## **Chapter 3: Lists**

Book direct quotes in quotations: Most content covered in Code 102

Ordered lists are lists where each item in the list is
numbered." Basically 1, 2, 3, and so on.

Unordered lists are lists that begin with a bullet point
(rather than characters that indicate order).

Definition lists are made up of a set of terms along with the
definitions for each of those terms.

You can also nest lists inside lists

New html code learned:

Defintion lists:

&lt;dl&gt;
The definition list is created with
the &lt;dl&gt; element and usually
consists of a series of terms and
their definitions.

Inside the &lt;dl&gt; element you will
usually see pairs of &lt;dl&gt; and
&lt;dd&gt; elements.

&lt;dt&gt;
This is used to contain the term
being defined (the definition
term).
&lt;dd&gt;
This is used to contain the
definition.



## Chapter 13: Boxes

CSS steps on borders, margins, box sizes including how to customize min-width and max-width, paddings and margins.

*Centering is CSS can be tricky, so ch 13 is helpful as a good resource for images for example.

Information on inline, block, and inline-block, which so far those are probably my most used CSS properties I've used beyond ones such as color and font. Helpful for basic formatting for beginners.

#### Chapter Summary From Book

* CSS treats each HTML e XX lement as if it has its own box.
*  You can use CSS to control the dimensions of a box.
* You can also control the borders, margin and padding for each box with CSS.
* It is possible to hide elements using the display and visibility properties.
* Block-level boxes can be made into inline boxes, and inline boxes made into block-level boxes.
* Legibility can be improved by controlling the width of boxes containing text and the leading.
* CSS3 has introduced the ability to create image
borders and rounded borders.

## *JavaScript* - Jon Duckett

### Chapter 2: Basic JavaScript Instructions

Overiveiw of the synta and grammar and how the browser runs the tasks

* A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon.

JavaScript is case sensitive.
username and userName are different

STATEMENTS ARE INSTRUCTIONS AND
EACH ONE STARTS ON A NEW LINE
A statement is an individual instruction that the
computer should follow. Each one should start on a new line and end with a semicolon. 

**The semicolon also tells the JavaScript interpreter when a step is over, indicating that it should move to the next step.** 

STATEMENTS CAN BE ORGANIZED INTO CODE BLOCKS

Some statements are surrounded by curly braces;
these are known as code blocks. The closing curly
brace is not followed by a semicolon

Comments explain what my code does, and also easy ot understand for others who read my code

#### **New Knowledge:**

MULTI-LINE COMMENTS
To write a comment that stretches over more than
one line, you use a multi-line comment, starting with
the /* characters and ending with the * / characters.
Anything between these characters is not processed·
by the JavaScript interpreter.
Multi-line comments are often used for descriptions
of how the script works, or to prevent a section of
the script from running when testing it.

SINGLE-LINE COMMENTS
In a single-line comment, anything that follows the
two forward slash characters I/ on that line will not
be processed by the JavaScript interpreter. Singleline
comments are often used for short descriptions
of what the code is doing.
Good use of comments will help you if you come
back to your code after several days or months.
They also help those who are new to your code.

Have to annouce and declare variables before using.

can use var or let

Data Types: (Also learned in lecture 5/10)
Notes taken during lecture:
## Types

### Strings

- a sequence of characters used to respent text. Written with single quotes.
  - 'hello'
  - 'efksfhksdaghj'

  ### Number

  - numeric data type
    - full numners, negatives, decimals

### Booleans

- Logical types
  - 'true'
  - 'false'

### Undefined

- it has not been defined yet
  - 'let dog;'


### Null

- something that has been defined as none
  - 'let dog = null;'

### Const

- cannot change the variable
  ex: const bird = 'chirp'; 
    can not reassign or change variable
    ** exceptions dealing with arrays**

## If/Else

Am I hungry 
 if yes - end statement

 if no ... start the chain:
  Am I hungry?
    no?
      am i thirsty?
        yes 
          then drink water

JavaScript wording:
if(this conditions evaulues to ture){execute this following code black}

//if false to being hungry
{execute this action}

Basically it will keep reading top to bottom until the condition is met OR reach the end of the statement //


if(iAmHungry){
  eat;
  else if(IAmThirsty)
  drink;
} ekse {
  take a nap;
}

Replit Notes

## Comparison Operators

// === comparative equals "loosely equals"
// ! means bang symbol
  != "loosely not equals'
  **OUR WORLD***
  === strictly equals
  !== stricty not equals

We want to learn by being very strict in the beginning.

<> less than, greater than
<=  less than/ or equal too
=> greater then or equal too 

let a = 5;

console.log(a === 5); *will run as* **true**
console.log(a === '5'); *will run as **false** since it is a string not number*
console.log (a == '5'); *will run **loosely true**, because it will see that it is loosely equal by looking under the hood and seeing that it is still a number even though under a string quote. Loosely equal to be avoided during the course for now, due to it being up to JS to intepret and can be upredicatable.*

### Logical Operators

&& - AND
|| - OR
! - NOT


Chapter 2 Summary:

* A script is made up of a series of statements. Each statement is like a step in a recipe.
* Scripts contain very precise instructions. For example, you might specify that a value must be remembered before creating a calculation using that value.
* Variables are used to temporarily store pieces of
information used in the script.
* Arrays are special types of variables that store more
than one piece of related information.
* JavaScript distinguishes between numbers (0-9),
strings (text), and Boolean values (true or false).
* Expressions evaluate into a single value.
* Expressions rely on operators to calculate a value.

### Chapter 4: Decisions and Loops (up to switch statements)


**EVALUATIONS** 
You can analyze values in
your scripts to determine
whether or note they
match expected results.

**DECISIONS & LOOPS
DECISIONS**
Using the results ofevaluations, you candecide which path your script should go down.

**LOOPS**
There are also many occasions where you will want to perform the same set of steps repeatedly.

### Switch Statements

A switch statement starts with a
variable called the switch value.
Each case indicates a possible
value for this variable and the
code that should run if the
variable matches that value.

## Things I want to know more about

Want to see more loops and switch in action to understand and practice.