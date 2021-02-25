# JavaScript

## A scripting language that enables you to create dynamically updating content.
control multimedia, animate images, and pretty much everything else.
(Okay, not everything, but it is amazing what you can achieve with a few lines of JavaScript code.)

## The core client-side JavaScript language consists of some common programming features that allow you to do things like:

* Store useful values inside variables. In the above example for instance, we ask for a new name to be entered then store that name in a variable called name.
* Operations on pieces of text (known as "strings" in programming).
  In the above example we take the string "Player 1: " and join it to the name variable to create the complete text label, e.g. ''Player 1: Chris".
* Running code in response to certain events occurring on a web page.
  We used a click event in our example above to detect when the button is clicked and then run the code that updates the text label.
  And much more!
  
  ## Operators
  
JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence.

## Expressions
An expression is any valid unit of code that resolves to a value.

Every syntactically valid expression resolves to some value but conceptually, there are two types of expressions: with side effects (for example: those that assign value to a variable) and those that in some sense evaluate and therefore resolve to a value.

The expression x = 7 is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to seven.

The code 3 + 4 is an example of the second expression type. This expression uses the + operator to add three and four together without assigning the result, seven, to a variable.

#A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

The name of the function.
A list of parameters to the function, enclosed in parentheses and separated by commas.
The JavaScript statements that define the function, enclosed in curly brackets, {...}.
For example, the following code defines a simple function named square:

function square(number) {
  return number * number;
}

