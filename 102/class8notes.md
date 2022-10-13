# [Class 8 Reading Notes](https://github.com/snur206/reading-notes/blob/main/102/class8notes.md)

**Assignment Operators**

***Assignment Operator** assigns a value to its left operand based on the value of its right operand. 

 The simple assignment operator is =, assigns the value of its right operand to its left operand
 
 x = f() is an assignment expression that assigns the value of f() to x
 
There are also compound assignment operators that are shorthand for the operations

*Assinging to properties*

If an expression evaluates to an object, the left-hand side of an assignment expression may make assignments to properties of the expression

If an expression does not evaluate to an object, then assignments to properties of that expression do not assign

Cannot assign properties to primitives.

It is an error to assign values to unmodifiable properties or to properties of an expression without properties (null or undefined).


*Destructing*

Destructing assignment syntax is a JS expression that makes it possible to extract data from arrays pr objects using a syntax that mirrors the construction of array and object literals

*Evaluation and Nesting*

JS style guides discourage chaining or nesting assignments.

Assignment chaining and nesting may occur sometimes so it is important to be able to understand how they work.

By chaining or nesting an assignment expression, its result can itself be assigned to another variable. It can be logged, it can be put inside an array literal or function call, and so on.

When chaining without parentheses or other grouping operators like array literals, the assignment expressions are grouped right to left, but they are evaluated left to right

For all assignment operators other than =, the resulting values are always based on the operands' values before the operation

***Avoid assignment chains**

Chaining assignments or nesting assignments in other expressions can result in surprising behavior. For this reason, chaining assignments in the same statement is discouraged

In particular, putting a variable chain in a const, let, or var statement often does not work. Only the outermost/leftmost variable would get declared; other variables within the assignment chain are not declared by the const/let/var statement

**Comparison operators**

A comparison operator compares its operands and returns a logical value based on whether the comparison is true

The operands can be numerical, string, logical, or object values.

Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison

That behavior generally results in comparing the operands numerically

The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality

**Loops and iteration**

***For Statement***

A for loop repeats until a specified condition evaluates to false

The JavaScript for loop is similar to the Java and C for loop

When a for loop executes, the following occurs:

- The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables

- The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. Otherwise, the for loop terminates. (If the conditionExpression expression is omitted entirely, the condition is assumed to be true.)

- The statement executes. To execute multiple statements, use a block statement ({ }) to group those statements.

- If present, the update expression incrementExpression is executed.

- Control returns to Step 2.

*JS*

for statement declares the variable i and initializes it to 0. It checks that i is less than the number of options in the <select> element, performs the succeeding if statement, and increments i by 1 after each pass through the loop.
  
**while statement**

A while statement executes its statements as long as a specified condition evaluates to true. 
  
If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.
  
The condition test occurs before statement in the loop is executed
  
Condition returns true, statement is executed and the condition is tested again
  
Condition returns false, execution stops, and control is passed to the statement following while 

To execute multiple statements, use a block statement ({ }) to group those statements.
  
Each iteration, the loop increments n and adds that value to x
  
After completing the third pass, the condition n < 3 is no longer true, so the loop terminates.
                                                    
Avoid infinite loops. Make sure the condition in a loop eventually becomes false—otherwise, the loop will never terminate!                                
