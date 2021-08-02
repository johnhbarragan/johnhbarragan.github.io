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
  *`position: absolute` - when the positiion property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.). see page 367

Fixed Positioning
  * `position:fixed` - keeps block fixed even if scrolling down

### Overlapping elements
When you use relative, fixed, or absolute positioning, boxes can overlap. If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page. If you want to control which element sits on top, you can use `z-index`. See page 369 for an example. 

### Creating Multi-column layouts with floats
You can do this with `<div>`. For examples please see pages 375 and 376. 

***Designers keep pages within 960-1000 pixesls wide and indicate what the site is about within the top 600 pixels.*** 

Fixed Width Layout and Liquid Layout: Pages 381 - 386. 

### Multiple Style Sheets
`@import` can be used to attached other CSS style sheets in main CSS stylesheet, at the before the rules. You can also add by using `<link>` and listing each stylesheet individually. 


Source: Duckett, Jon. HTML & CSS. John Wiley & Sons Inc. 2011

Source: Duckett, Jon. JAVASCRIPT & JQUERY. John Wiley & Sons Inc. 2014 