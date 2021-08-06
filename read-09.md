# Forms
Form has referred to a printed doc that contains spaces for you to fill in information. Best known form is google search bar. 

Form controls: `Adding text`, `Making choices`, and `Submitting forms`. 

## Cheatsheet
`<form>` = form controls live inside this element. This element should always carry the action attribute and will usually have a method and id attribute too. 

`<action>` = required on every `<form>` and its value is the URL for the page on the server that will receive the info in form. 

`<method>` = two methods - get or post (see page 151)

`<input>` = use to create several different form controls

`type="text"` = when the type attribute has a value of text, it create a single 
line of input

`name` = each form control requires a name attribute. The value of this attribute identifies the form control

`maxlenght` = limits the number of characters a user may enter into text field. 

## Password input
`<input>`. `type="password"` creates a textbox that acts like a single line text input, except the characters are blocked out. You would also use `name`, `size, maxlength`

`<textarea>` = used to create a multi line text input

Radio and Checkbox: see pages 155-156

## Drop down list box
`<select>` > attribute `<name>` > `<option>` > attribute `<value>`

File input/Submit button: see pages 159 and 160

## Lists, Tables and Forms
`list-style-type` = control the shape or style of a bullet point

`list-style-image` = allows you to specify an image to act as a bullet point 

`list-style-position` = allows you to indicate whether the marker should appear on the inside or the outside of the box

`list-style` = acts as a shorthand foro list style. Allows you to express the markers style, image, and position in any order 

### Tables
`empty-cells` can be used to specify whether or note empty cell borders should be shown with `show`, `hide`, or `inherit`

Gaps between cells can be altered using `border-spacing` or `border-collapse`

Styling text inputs/cursor styles - see page 342 & 347 

## Events
When you browse the web, your browser registers different types of events like `load`, mouse `click` or user `input`, etc. 

Events that trigger a JavaScript code aka a EVENT HANDLING:
  * Select element node you want the script to respond to
  * Indicate which event on the selected node will trigger the response
  * State the code you wan tto run when the even occurs

### Traditional DOM EVENT HANDLERS (page 252)
Example: `element.oneEvent = functionName;`. You can only attach a single function to any event

### EVENT LISTENERS
A more recent approach to handling events. They can deal with more than one function at a time but they are not supported in older browsers. Favored way of handling events. Example format: 
  * `element.addEventListener('event', functionName [, Boolean]);` see page 254