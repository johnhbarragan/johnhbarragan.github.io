
# Introducing CSS

> The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element. 
CSS allows you to create rules that control the way that each individual box (and contents of that box) is presented.

(Duckett, HTML Pages 229-230)

You can use CSS internally in HTML by using `<style>` within HTML or externally by referencing `<link>` 

CSS is read from top to bottom so *last rule* usually gets precedence if two or more rules apply to the same element. **Specificity** is also considered, the more specific rule takes precedence over general ones. Last, you can place a `!` after any property value to indicate it should be considered more important than other rules that apply to the same element

# JavaScript

> A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a STATEMENT. Statements should end with a semicolon.

(Duckett, JAVSCRIPT, page 56)

When you write JS, you have to tell the interpreter every individual step. You would use **VARIABLES** to remember values. 

Data type:

    - Numeric
    - String
    - Boolean = true/false

Arrays = special type of variable. It doesn't just store one value; it stores a list of values

### Expressions:
Evaluates into/results in a single value. Two types of expressions: 1. Expressions that just assign a value a variable. 2. Expressions that use two or more values to return a single value. 

    - Expression rely on **OPERATORS**
        - examples: 1. assignment operators color = 'beige'; 2. arithmetic operators `area = 3 * 2` and 3. string operators greeting = 'Hi' + 'Molly'

## Comparison Operators Cheatsheet
* Is equal to = `==`compares two values to see they are the same
* Is not equal to = `!=` compares two values to see if they are NOT the same
* Strict equal to = `===` compares two values to check that both the data type and value are the same
* Strict not equal to = `!==` compares two values to check that both the data type and value are NOT same
* Greater than or equal to = `>=` check if number on left compared to number on right



## General Cheatsheet

* headings from biggest to smallest = `<h1>, <h2>, <h3>, <h4>, <h5>, <h6>`
* paragraph = `<p></p>`
* bold and italic = `<b></b>` and `<i></i>`
* supercript and subscript = `<sup></sup>` and `<sub></sub>`
* line break = `<br  />`
* blockquote = `<blockquote></blockquote>`
* shorter quotes that sit within paragrahs = `<q></q>`
* changes to content = `<ins>,</ins>`, `<del></del>`, `<s></s>` see page 56 in HTML book 

Source: Duckett, Jon. HTML & CSS. John Wiley & Sons Inc. 2011
Source: Duckett, Jon. JAVASCRIPT & JQUERY. John Wiley & Sons Inc. 2014 