Comparison Operators

You may be familiar with comparison operators from math class. Let’s make sure there aren’t any gaps in your knowledge.

Less than (<) — returns true if the value on the left is less than the value on the right, otherwise it returns false.
Greater than (>) — returns true if the value on the left is greater than the value on the right, otherwise it returns false.







Logical Operators

Comparison operators allow us to assert the equality of a statement with JavaScript. For example, we can assert whether two values or expressions are equal with ===, or, whether one value is greater than another with >.

There are scenarios, however, in which we must assert whether multiple values or expressions are true. In JavaScript, we can use logical operators to make these assertions.

&& (and) — This operator will be truthy (act like true) if and only if the expressions on both sides of it are true.
|| (or) — This operator will be truthy if the expression on either side of it is true. Otherwise, it will be falsy (act like false).
var isTrue = ('yellow' === 'green') && (4 >= 4);

In the example above, we check if the string 'yellow' is equal to the string 'green' and (&&) if 4 is greater than or equal to 4. Let’s break this down into the two comparison expressions.
The first expression is false, because the string 'yellow' is not the same (equal) as the string 'green'.
The second expression is true, because the number 4 is greater than or equal to 4.

The && operator requires that both expressions be true in order for the expression to be truthy. Because one expression is false and the other is true, the expression is falsy and evaluates to false.
