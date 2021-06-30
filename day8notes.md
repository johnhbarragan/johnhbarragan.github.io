# Loops

## What are loops?
Loops offer a quick and easy way to do something repeatedly. Loops are a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. 

- for statement
  - foor loop repeats until a specified condition evaluates as fals

  - ex: for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement

- do...while statement repeats until a specified condition evaluates as false
  - do
  statement
while (condition);

  - ex: let i = 0;
do {
  i += 1;
  console.log(i);
} while (i < 5);

- while statement executes its statements as long as a specified condition evaluates as true
  - while (condition)
  statement

  - If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

  - let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}

- labeled statement proves a statement with an identifier that lets you refer to it elsewhere in your program

- break statement: Use the break statement to terminate a loop, switch, or in conjunction with a labeled statement.

- continue statement can be used to restart a while, do-while, for, or label statement.

- for...in statement iterates a specified variable over all the enumerable properties of an object.

- for...of statement creates a loop Iterating over iterable objects (including Array, Map, Set, arguments object and so on), invoking a custom iteration hook with statements to be executed for the value of each distinct property.

[Source](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)