# Code 102: Class 2 Reading Notes

## *HTML & CSS* - Jon Duckett

### **Chapter 2: Text**

Overview of previously covered content such as doing headings, paragraphs, formatting like bold, italics, emphasis
semantic language

**Semantic Markup**

Interesting in that it is not used to change the way your website looks, but more to describe content. Example are screenreaders adding extra emphasis to &lt;em> text


## Chapter 10: Introducing CSS

CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.

CSS helps style and format the look of website.

There is internal, inline, and external css

External is best practice.

## *JavaScript* - Jon Duckett

## Chapter 2: Basic JavaScript Instructions

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

## Chapter 4: Decisions and Loops **up to loop statements*

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

## Things I want to learn more about:

More CSS Selector practice and memorizing as many can with practie