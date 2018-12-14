####  Questions

>  What are the three types of conditional statements?


A:    If, Else, and Else If Statements.


>  What are four types of comparison operators and how you would use them?


A:  
* Equality Operator (==): Compares two values and returns ‘true’ if they are equivalent or ‘false’ if they are not.  Data types will be converted if they can be.

* Inequality Operator (!=): Compares two values and returns ‘true’ if they are not equivalent.  Data types will be converted if they can be.

* Greater than operator (>): Compares two numbers.  When the number on the left is greater than the number on the right, it returns ‘true’.  Otherwise, it returns ‘false’.  Data types will be converted if they can be.

* Logical “AND” operator (&&): Will return ‘true’ if the operands on both sides evaluate to ‘true’.


#### Code Practice

> Create a variable called grade and set it to the grade you plan to receive on this assignment. Then write an if statement that will check whether the grade is equal to an A, B, C, D, or F and inform the user if they passed or failed using console.log().

####   Code
```JS
let grade = 'A';
if (grade == 'A' || grade == 'B' || grade == 'C') {
  console.log('You passed!');
} else if (grade == 'D' || grade == 'F') {
  console.log('Sorry, you did not pass.');
} else {
  console.log('You did not enter a valid grade letter.')
}
```

