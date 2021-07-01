**What does an Assignment Operator do?**

* An assignment operator assigns a value to its left operand based on the value of its right operand. 

* The simple assignment operator is the equal sign (=), which assigns the value of its right operand to its left  operand. That is, x = y assigns the value of y to x.

**What is an Expression?**

An **Expression** is any valid unit of code that resolves to a value.

**What is a **Loop?**

Loops offer a quick and easy way to do something repeatedly.

**The statements for loops provided in JavaScript are:**
* for statement
* do...while statement
* while statement
* labeled statement
* break statement
* continue statement
* for...in statement
* for...of statement

**Information about Loops**

**A for loop** repeats until a specified condition evaluates to *false*.

A for statement looks as follows:
```
for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement
```
When a for loop executes, the following occurs:

1. The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
2. The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)
3. The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.
4. If present, the update expression incrementExpression is executed.
5. Control returns to Step 2.  

A **while statement** executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:
```
while (condition)
  statement
```
If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

