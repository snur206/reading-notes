[# Class 7 Reading Notes](https://github.com/snur206/readingnotes/blob/main/102/class7notes.md)
**Programming with JS**

***Control Flow***

Is the order in which the computer executes statements in a script.

Code is run in order from the first line in the file to the last line, unless the computer runs across the structures (extremely frequent) that change the control flow, like conditionals and loops.

Script submits validated data and the user leaves a required field empty, script will prompt you to fill it in.

Script will use a conditional structure or if...else, so that different code executes depending on whether the form is complete or not.

Typicaal script in JS include many control structures, includung conditionals, loops and functions. Part(s) of a script may also be set to execute when events occur.

Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution.

**JS Functions**

JS Function is a block of code designed to perform a particular task.

JS Function is executed when "something" invokes it (calls it).

JS function is defined with the function keyword, then by a name, followed by ()

Function names can contain letters, digits, underscores, and dollar signs. Same rules as variables.

() may include parameter names separated by commas. EX: (parameter1, parameter2, ...)

Code is executed, by the function, is placed inside {}

Function ***parameters*** are listed inside () in the function definition.

Function ***arguments*** are the ***values*** received by the function when it is invoked.

Inside the function the arguments (the parameters) behave as local variables.

**Function Invocation**

The code inside the function will execute when "something" *invokes* (calls) the function:

- When an event occurs (when a user clicks a button)

- When it is invoked (called) from JavaScript code

- Automatically (self invoked)

**Function Return**

When JS reaches a *return* statement, the function will stop ececuting.

If the function was invoked from a statement, JS will *return* to execute the code after the invoking statement.

Functions often compute a *return value*. Return value is "returned" back to the "caller"

**Why Fucntions?**

Can reuse code, define the code once and can use it more

Can use the same code many times with different aruments to produce different results.

**() Operator Invokes the Function**

Accessing a function without () will return the function object instead of the function result.

**Functions used as Variable Values**

Functions can be used the same way as you use variables, in all types of formulas, assignments, and calculations.

**Local Variables**

Variables declared in a JS function become *LOCAL* to the function

Local variables can only be accessed from within the function.

LV is only recognized inside their functions, variables with the same name can be used in different functions.

LV is created when a function starts, and deleted when the function is completed.

**JS Operators**

The *assignment* operator (=) assigns a value to a variable.

the + operator adds numbers.

the multiplications operator (*) multiplies numbers.

**Tyoes of JS Operators**

- Aritmetic Operators

- Assignment Operators

- Comparison Operators

- Logical Operators

- Conditional Operators

- Type Operators

**JS Arithmetic Operators**

- Addition +

- Subtraction -

- Multiplication *

- Exponentiation (ES2016) **

- Division /

- Modulus (Division Remainder) %

- Increment ++

- Decrement --

**JS Assignment Operators**

Assignment operators assign values to JavaScript variables.

The addition assignment operator (+=) adds a value to a variable.

**Adding JS Strings**

+ operator an also be used to add (concatenate) strings.

+= assignment operator can also be used to add (concatenate) strings.

**Adding strings and numbers**

Adding two numbers, will return the sum, but adding a number and a string will return a string:

**JS COMPARISON OPERATORS**

- ==	equal to

- ===	equal value and equal type

- !=	not equal

- !==	not equal value or not equal type

- >	greater than

- <	less than

- >=	greater than or equal to

- <=	less than or equal to

- ?	ternary operator

**JS logical operators**

- &&	logical and

- ||	logical or

- !	logical not

**JS Type Operators**

- typeof	Returns the type of a variable

- instanceof	Returns true if an object is an instance of an object type

**JS Bitwise Operators**

Bit operators work on 32 bits numbers.

Any numeric operand in the operation is converted into a 32 bit number. The result is converted back to a JavaScript number.

Operator	Description	Example	Same as	Result	Decimal

&	AND	5 & 1	 0101 & 0001	 0001	  1

|	 OR	 5 | 1	 0101 | 0001	 0101	  5

~	 NOT	 ~ 5	 ~0101	 1010	  10

^	 XOR	 5 ^ 1	  0101 ^ 0001	 0100	  4

<<	 left shift	 5 << 1	 0101 << 1	 1010	  10

>>	 right shift	 5 >> 1	 0101 >> 1	 0010	  2

>>>	u nsigned right shift 	5 >>> 1 	0101 >>> 1	 0010	   2

