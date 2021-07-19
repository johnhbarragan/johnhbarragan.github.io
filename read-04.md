# Links
Links enable you to go from one place to another. 

Link are created using `<a>` element For examples
  * `<a href="http://www.imdb.com">IMDB</a>`

`href` is an attribute to `<a>`

When you link to a different website, the URL is known as **absolute**

When you are linking to other pages within the same site, URL is **relative**. In these you dont have to post the domain name. 

`mailto:` creates link to startup user's email program. Example code:
  * `<a href="mailto:johnnyb@gmail.com">Johnny's Fake Email</a>`

`target` creates link to open link in new window. Example code:
  * `<a href="http://www.imdb.com" targer="_blank"> TITLE</a>  `


# Layout
CSS has positioning schemes that allow you to control the layout of a page: Normal flow, relative positioning, and absolute positioning. You can also float elements.

### Normal flow 
  * Every block level element appears on a new line causing each item to appear lower down the page than the previous one. 
  * `position: static` - you do not need a CSS property to indicate that elements should appear in normal flow

### Relative Positioning
  * This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. 
  * `position: relative` - you would actually use this. Example code:
```
  p.example {
      position:relative;
      top: 10px;
      left: 100px;}
```

### Absolute Positioning
  * This positions the element in relation to its containing element. 
  *`position: absolute` see page 367

Fixed Positioning
  * `position:fixed` - keeps block fixed even if scrolling down

### Overlapping elements
When you use relative, fixed, or absolute positioning, boxes can overlap. If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page. If you want to control which element sits on top, you can use `z-index`. See page 369 for an example. 

### Creating Multi-column layouts with floats
You can do this with `<div>`. For examples please see pages 375 and 376. 

***Designers keep pages within 960-1000 pixesls wide and indicate what the site is about within the top 600 pixels.*** 

## Functions (pages 86-99)
Function let you group a series of statements together to perform a specific task

When you ask a function to perform a task it is known as **CALLING**
Pieces of info passed to a function are known as **PARAMETERS**
When you expect a function to provide an an answer is **RETURN VALUE**

  * The location where you declare a variable will affect where it can be used within your code. If you declare it within a function, it can only be used within that function. This is known as the variable's **scope** 

## Pair Programming
Pair programming is great because there's:

  * Greater efficiency
  * Engaged collaboration
  * Learning from fellow students
  * Social skills
  * Job interview readiness
  * Work environment readiness



Source: Duckett, Jon. HTML & CSS. John Wiley & Sons Inc. 2011
Source: Duckett, Jon. JAVASCRIPT & JQUERY. John Wiley & Sons Inc. 2014 