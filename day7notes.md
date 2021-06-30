

## Functions and Comparison Operators
Operators - and, or not

Functions - **SMALL** bit of code that gives specific instructions

  - start with function variable () {}

Function paramater which would be included in () above: Primitive parameters (such as a number) are passed to functions by value; the value is passed to the function, but if the function changes the value of the parameter, this change is not reflected globally or in the calling function.

## Calling a function
Assuming function square (number){logic}, you could call it by saying square (5) and conosole.log(square(5)); 

## Nesting Functions
You may nest a function within another function. The nested (inner) function is private to its containing (outer) function.

  - The inner function can be accessed only from statements in the outer function.

  - The inner function forms a closure: the inner function can use the arguments and variables of the outer function, while the outer function cannot use the arguments and variables of the inner function.

  - ex) function addSquares(a, b) {
  function square(x) {
    return x * x;
  }
  return square(a) + square(b);
}
a = addSquares(2, 3); // returns 13
b = addSquares(3, 4); // returns 25
c = addSquares(4, 5); // returns 41