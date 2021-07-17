# Lists
There are three different types of lists:
  * Ordered lists `<ol></ol>`- where each item list is numbered
  * Undeordered lists `<ul></ul>`- lists that begin with a bullet point

Definition lists - set of terms along with the definitions for each of those terms
  * `<dl></dl>` is used to create a definition list. It is usually paired with `<dt></dt>` which contains the term being defined and `<dd></dd>` which contains the definition. 

**You can nest lists by adding a list inside of an `<li>` element**

# Boxes 
You can alter boxes by adjusting `width` and `height`. You can adjust these by using pixels, percentages or ems. Pixels are usually most popular method. 
  * `mind-width` = specifies the smallest size a box can be displayed at when the browser window is narrow 
  * `max-width` = same as above except when window is wide
  * `min-height` and `max-height` limit height

### Overflowing content
Overflow property tells browser what to do if the content is larger than the box itself. `hidden` hides any extra content that does not fit in the box. `scroll` adds a scrollbar to the box so that you can see the missing content. Example code: 

```p.one {
    overflow: hidden;}
p.two {
    overflow: scroll;}
}
``` 
### Border, Margin & Padding
  * `border-width` can be altered with thin, mediem, thick
  * `border-style` can be edited with solid, dotted, dashed, double, groove, ridge, inset, outset, hidden, none
  * `border` allows you to specify the width, style and color of a border
  * `padding` specifies how much space should appear between the content of an element and its border. Use `paddint-top`, `padding-right`, `padding-bottom` and `padding-left`
  * `margin`controls the gap between boxes. You can alter by using `margin-top`, `margin-right`, `margin-bottom`, and `margin-left`
  * You can add `auto` to `left-margin` or `right-margin` to center a box on the page (or center it inside the element that it sits in)


### Arrays
Each item in an array is automatically given a number called an **INDEX**. For example: `colors = ['white', 'black', 'custom];` would mean that 0 = white, 1 = black and 2 = custom

### Switch statements
A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value. You would use a switch if you have a `default` option that is run if none of the cases match. If a match is found, the code is run then the `break` statement stops the rest of the switch 

`falsy` values are trested as if they are false. Examples: `var highScore = false;`, `highscore = 0` `highscore = ''`

`truthy` values are trested as if they are true

### Loops
Loops offer a quick and easy way to do something repeatedly. Loops are a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. 

- for statement
  - for loop repeats until a specified condition evaluates as fails

  - ex: for `([initialExpression]; [conditionExpression];[incrementExpression])`
  statement

- while statement executes its statements as long as a specified condition evaluates as true
  - while (condition)
  statement

  - If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

- break statement: Use the break statement to terminate a loop, switch, or in conjunction with a labeled statement.
