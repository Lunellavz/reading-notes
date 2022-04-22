# Assignment operators
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators


An assignment operator assigns a value to its left operand based on the value of its right operand.

Assignment	x = f() meaning:	x = f()

Chaining assignments or nesting assignments in other expressions can result in surprising behavior.

# Comparison operators

A comparison operator compares its operands and returns a logical value based on whether the comparison is true. 
he operands can be numerical, string, logical, or object values.

Operator	Description	Examples returning true
Equal (==)	Returns true if the operands are equal.	3 == var1
"3" == var1

# Loops
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration

A *for* loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

When a for loop executes, the following occurs:

1. The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.

2. The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. Otherwise, the for loop terminates. (If the conditionExpression expression is omitted entirely, the condition is assumed to be true.)

3. The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.

4. If present, the update expression incrementExpression is executed.

5. Control returns to Step 2.

A while statement executes its statements as long as a specified condition evaluates to true.

The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

Avoid infinite loops. Make sure the condition in a loop eventually becomes false—otherwise, the loop will never terminate!
