
# Introducing CSS

> The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element. 
CSS allows you to create rules that control the way that each individual box (and contents of that box) is presented 
Ducket PG 229-230

You can use CSS internally in HTML by using `<style>` within HTML or externally by referencing `<link>` 

CSS is read from top to bottom so *last rule* usually gets precedence if two or more rules apply to the same element. **Specificity** is also considered, the more specific rule takes precedence over general ones. Last, you can place a `!` after any property value to indicate it should be considered more important than other rules that apply to the same element.

## Cheatsheet

* headings from biggest to smallest = `<h1>, <h2>, <h3>, <h4>, <h5>, <h6>`
* paragraph = `<p></p>`
* bold and italic = `<b></b>` and `<i></i>`
* supercript and subscript = `<sup></sup>` and `<sub></sub>`
* line break = `<br  />`
* blockquote = `<blockquote></blockquote>`
* shorter quotes that sit within paragrahs = `<q></q>`
* changes to content = `<ins>,</ins>`, `<del></del>`, `<s></s>`

Source: Ducket, Jon. HTML & CSS. John Wiley & Sons Inc. 2011