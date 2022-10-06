# Operations and Loops

**An expression** is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.

The expression x = 7 is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to 7.

The expression 3 + 4 is an example of the second type. This expression uses the + operator to add 3 and 4 together and produces a value, 7. However, if it's not eventually part of a bigger construct (for example, a variable declaration like const z = 3 + 4), its result will be immediately discarded — this is usually a programmer mistake because the evaluation doesn't produce any effects.

## Assignment operators
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal ('='), which assigns the value of its right operand to its left operand. That is, 'x = f()' is an assignment expression that assigns the value of 'f()' to' x.'

**There are also compound assignment operators that are shorthand for the operations :**

Name	Shorthand operator	Meaning
Assignment	x = f()	x = f()

Addition assignment	            x += f()	      ` x = x + f()`

Subtraction assignment	         x -= f()	      ` x = x - f()`

Multiplication assignment      	x *= f()	      ` x = x * f()`

Division assignment            	x /= f()	      ` x = x / f()`

Remainder assignment	           x %= f()	      ` x = x % f()`

Exponentiation assignment	      x **= f()     ` 	x = x ** f()`

Left shift assignment	          x <<= f()	    ` x = x << f()`

Right shift assignment	        x >>= f()	       `x = x >> f()`

Unsigned right shift assignment	 x >>>= f()	   ` x = x >>> f()`

Bitwise AND assignment	       x &= f()	        ` x = x & f()`

Bitwise XOR assignment	         x ^= f()          	`x = x ^ f()`

Bitwise OR assignment	         x |= f()	        ` x = x | f()`

Logical AND assignment	       x &&= f()        `	x && (x = f())`

Logical OR assignment	         x ||= f()	       `x || (x = f())`

Logical nullish assignment	     x ??= f()	      `x ?? (x = f())`



## **Comparison Operators **

`== `  (equal)

`!==` (not equal)

`===` (strict equal)

`!==` (strict not equal)

 ` > ` (greater than)
 
` >= ` (greater than or equal)

` < ` (less than)

` <= `(less than or equal)


For StatementLinks to an external site.
A for loop repeats until a specified condition evaluates to false

The Structure of a for loop looks like:

for( initial value; condition to evaluate; increment) { code to execute }

the initial value usually initializes one or more loops counters
if condition to evaluate is true, then the loops statements execute
While StatementLinks to an external site.
A while statement executes its statements as long as a specified condition evaluates to true

The Structure for a while loops looks like:

while ( condition to evaluate is true ){ execute this code }

the loop stop executing if the condition becomes false


