# JavaScript

- JavaScript has both binary and unary operators, and one special ternary operator (the conditional operator)

- a binary operator requires an operand before and after the operator

- a unary operator requires one operand either before or after the operator

## Expressions and Operators

- Assignment operators
  - assigns a value to its left operand based on the value of its right operand
  - the simple assignment operator is = (x=y)
  - evaluate each left to right

- Comparison operators
  - compares operands and returns a logical value based on whether the comparison is true 
  - can be numerical string, logical =, or object values
  -compared based on lexicographical ordering using unicode values.
  - generally not the same type of operand
  - comparison
  - exceptions being === and !==
  -var var1 = 3; var var2 = 4;

- Arithmetic operators
  - An arithmetic operator takes numerical values as their operands and returns a single numerical value.
  - + - * / 
  -1 / 2; // 0.5
1 / 2 == 1.0 / 2.0; // this is true

- Bitwise operators
  -A bitwise operator treats their operands as a set of 32 bits (zeros and ones), rather than as decimal, hexadecimal, or octal numbers. For example, the decimal number nine has a binary representation of 1001. Bitwise operators perform their operations on such binary representations, but they return standard JavaScript numerical values.

- Logical operators
  - Logical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value.

- String operators
  - In addition to the comparison operators, which can be used on string values, the concatenation operator (+) concatenates two string values together, returning another string that is the union of the two operand strings

- Conditional (ternary) operator
  - The conditional operator is the only JavaScript operator that takes three operands. The operator can have one of two values based on a condition
- Comma operator
  -The comma operator (,) evaluates both of its operands and returns the value of the last operand. This operator is primarily used inside a for loop, to allow multiple variables to be updated each time through the loop

- Unary operators
  - Operation with only one operand

- Relational operators
  - compares its operands and returns a Boolean value based on whether the comparison is true

## Loops

- used to repeat an action

- A for loop repeats until a specified condition evaluates to false
  for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement
  - initializing expression is executed
  - condition expression is evaluated
  - statement executes
  - updated increment expression is executed
- A do...while statement repeats until a specific condition evaluates to false
  - do statement  while (condition)
  - statement is always executed once before the condition is checked
  - If condition is true, the statement executes again

- A while statement executes its statements as long as a specified condition evaluates to true
  - while (condition) statement
  - If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.
