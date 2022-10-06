# Operations and Loops

**An expression** is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.

The expression x = 7 is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to 7.

The expression 3 + 4 is an example of the second type. This expression uses the + operator to add 3 and 4 together and produces a value, 7. However, if it's not eventually part of a bigger construct (for example, a variable declaration like const z = 3 + 4), its result will be immediately discarded — this is usually a programmer mistake because the evaluation doesn't produce any effects.

## Assignment operators
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal ('='), which assigns the value of its right operand to its left operand. That is, 'x = f()' is an assignment expression that assigns the value of 'f()' to' x.'

**There are also compound assignment operators that are shorthand for the operations :**

Name	Shorthand operator	Meaning
Assignment	x = f()	x = f()

Addition assignment	            `x += f()	`       ` x = x + f()`

Subtraction assignment	         `x -= f()	`       ` x = x - f()`

Multiplication assignment      	`x *= f()	`       ` x = x * f()`

Division assignment            	`x /= f()	`       ` x = x / f()`

Remainder assignment	           `x %= f()`	       ` x = x % f()`

Exponentiation assignment	     ` x **= f()`      ` 	x = x ** f()`

Left shift assignment	          `x <<= f()	`    ` x = x << f()`

Right shift assignment	       ` x >>= f()	`       `x = x >> f()`

Unsigned right shift assignment	 `x >>>= f()`	   ` x = x >>> f()`

Bitwise AND assignment	       `x &= f()	`         ` x = x & f()`

Bitwise XOR assignment	        `x ^= f()  `         	`x = x ^ f()`
 
Bitwise OR assignment	         `x |= f()	`         ` x = x | f()`

Logical AND assignment	       `x &&= f() `        `	x && (x = f())`

Logical OR assignment	        ` x ||= f()	`        `x || (x = f())`

Logical nullish assignment	    ` x ??= f()`        `x ?? (x = f())`



## **Comparison Operators **

`== `  (equal) Returns true if the operands are equal.

`(!==)` (not equal)  Returns true if the operands are not equal.

`(===)` (strict equal) Returns true if the operands are equal and of the same type. 

`(!==)` (strict not equal) Returns true if the operands are of the same type but not equal, or are of different type.

 `( > )` (greater than)  Returns true if the left operand is greater than the right operand.
 
`( >=) ` (greater than or equal)  Returns true if the left operand is greater than or equal to the right operand.

` (<) ` (less than)  Returns true if the left operand is less than the right operand.

`( <=) `(less than or equal)   Returns true if the left operand is less than or equal to the right operand.


## Loops and iteration

Loops offer a quick and easy way to do something repeatedly.

There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times.

The various loop mechanisms offer different ways to determine the start and end points of the loop. There are various situations that are more easily served by one type of loop over the others.

### For Statement

A for loop repeats until a specified condition evaluates to false. 

If you know how many times it's gonna execute, use FOR LOOP

For Statment looks like:

for ([initialExpression]; [conditionExpression]; 

[incrementExpression])

  statement
  
  
1- The initializing expression `initialExpression`, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
2- The conditionExpression expression is evaluated. If the value of `conditionExpression` is true, the loop statements execute. Otherwise, the for loop terminates. (If the conditionExpression expression is omitted entirely, the condition is assumed to be true.)
3- The statement executes. To execute multiple statements, use a block statement ({ }) to group those statements.
4- If present, the update expression incrementExpression is executed.
5- Control returns to Step 2.






