# Class 8 Reading Notes

### Lecture Notes

Continually building upon our existing scripts in previous classes.

What is a loop?
Quick and easy way to repeat some code
a sequence of instructions continally repeated unti la conditon is reached

What's a while loop?
a loop that will repeat while a certain condition is met
a type of loops that is repeated unti la conditon is achieved

Whats a "for" loop?
Repeats for as long as we tell it to
Repeated a specific amount of times

WHat does increment mean? Increase
What does decrement mean? Decrease

## Reading Notes w/ links to the source for more detailed review

## Operators
JavaScript has the following types of operators.

	• Assignment operators
	• Comparison operators
	• Arithmetic operators
	• Bitwise operators
	• Logical operators
	• String operators
	• Conditional (ternary) operator
	• Comma operator
	• Unary operators
	• Relational operators

>JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator:

From <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators> 

### Comparison Operator
>A comparison operator compares its operands and returns a logical value based on whether the comparison is true. 

>The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. 

>The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality. 

>Equal (==)	Returns true if the operands are equal.	
3 == var1
"3" == var1

>Not equal (!=)	Returns true if the operands are not equal.	var1 != 4
var2 != "3"

Strict equal (===)	Returns true if the operands are equal and of the same type. See also Object.is and sameness in JS.	3 === var1

Strict not equal (!==)	Returns true if the operands are of the same type but not equal, or are of different type.	var1 !== "3"
3 !== '3'

Greater than (>)	Returns true if the left operand is greater than the right operand.	var2 > var1
"12" > 2

Greater than or equal (>=)	Returns true if the left operand is greater than or equal to the right operand.	var2 >= var1
var1 >= 3

Less than (<)	Returns true if the left operand is less than the right operand.	var1 < var2
"2" < 12

Less than or equal (<=)	Returns true if the left operand is less than or equal to the right operand.	var1 <= var2
var2 <= 5

## Assignment operators
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. 

That is, x = f() is an assignment expression that assigns the value of f() to x.

There are also compound assignment operators that are shorthand for the operations listed in the following table:


## Loops

### for statement
A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

A for statement looks as follows:
for([initialExpression];[conditionExpression];[incrementExpression])statement

When a for loop executes, the following occurs:

* The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
* The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. Otherwise, the for loop terminates. (If the conditionExpression expression is omitted entirely, the condition is assumed to be true.)
* The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.
* If present, the update expression incrementExpression is executed.
* Control returns to Step 2.

### While Statement

A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:
while(condition)statement

If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

The condition test occurs before statement in the loop is executed. 
If the condition returns true, statement is executed and the condition is tested again. 

If the condition returns false, execution 
stops, and control is passed to the statement following while.

To execute multiple statements, use a block statement ({ ... }) to group those statements.

## IMPORTANT
void infinite loops. Make sure the condition in a loop eventually becomes false—otherwise, the loop will never terminate! The statements in the following while loop execute forever because the condition never becomes false:
// Infinite loops are bad!while(true){console.log('Hello, world!');

From <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#while_statement> 
