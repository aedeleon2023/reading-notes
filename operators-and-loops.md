# Operators and Loops

## Assignment Operators
Assignment Operators assign a value to their left operand based on the value of their right operand.  The simple assignment operator is equal (=).

### Compound Assignment Operators 
(The following is in the Name/Shorthand operator/Meaning format.)
- Assignment  `x = f()` `x = f()`
- Addition assignment  `x += f()`  `x = x + f()`
- Subtraction assignment  `x -= f()`	 `x = x - f()`
- Multiplication assignment	 `x *= f()`  `x = x * f()`
- Division assignment	 `x /= f()` `x = x / f()`
- Remainder assignment  `x %= f()`	 `x = x % f()`
- Exponentiation assignment	 `x **= f()`	 `x = x ** f()`
- Left shift assignment	 `x <<= f()`	 `x = x << f()`
- Right shift assignment `x >>= f()`	 `x = x >> f()`
- Unsigned right shift assignment	 `x >>>= f()`	 `x = x >>> f()`
- Bitwise AND assignment `x &= f()` `x = x & f()`
- Bitwise XOR assignment  `x ^= f()`	`x = x ^ f()`
- Bitwise OR assignment	 `x |= f()`  `x = x | f()`
- Logical AND assignment	 `x &&= f()`	`x && (x = f())`
- Logical OR assignment	  `x ||= f()`	 `x || (x = f())`
- Logical nullish assignment	`x ??= f()`	`x ?? (x = f())`


## Comparison Operators
Comparison operators compare their operands and return a logical value based on whether the comparison is true. 
The operands can be:
- Numerical
- String 
- Logical
- Object Values

Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality.

### Comparison Operators
- Equal (==) - Returns true if the operands are equal. -  3 == var1, "3" == var,  1 3 == '3'
- Not equal (!=) - Returns true if the operands are not equal. - var1 != 4,  var2 != "3"
- Strict equal (===) - Returns true if the operands are equal and of the same type. - 	3 === var1
- Strict not equal (!==) - Returns true if the operands are of the same type but not equal, or are of different type. - var1 !== "3", 3 !== '3'
- Greater than (>) - Returns true if the left operand is greater than the right operand.	- var2 > var1, "12" > 2
- Greater than or equal (>=) - Returns true if the left operand is greater than or equal to the right operand. - var2 >= var1, var1 >= 3
- Less than (<) - Returns true if the left operand is less than the right operand. - var1 < var2, "2" < 12
- Less than or equal (<=) - Returns true if the left operand is less than or equal to the right operand. - var1 <= var2, var2 <= 5


## For Statements
A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement

### When a for loop executes, the following occurs:

1. The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
2. The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. Otherwise, the for loop terminates. (If the conditionExpression expression is omitted entirely, the condition is assumed to be true.)
3. The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.
4. If present, the update expression incrementExpression is executed.
5. Control returns to Step 2.

## While Statement
A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

while (condition)
  statement

If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

To execute multiple statements, use a block statement ({ ... }) to group those statements.

[HOME](https://aedeleon2023.github.io/reading-notes/)
