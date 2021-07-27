# What is an Object?
Objects group together a set of variables and functions to create a model of something you owuld recognize from teh real world. In an object, variables and functions take on new names. 
  * property = variable part of object
  * method = a function part of an object 
  * key = name of a value to a property or method. You cannot have two keys with the same name

  You access the properties or methods of an object using dot notation or square brackets

  DOM = Document Object Model specifies how browsers should create a model of an HTML page and how JS can access and update the contents of a web page while it is in the browswer window. **DOM is neither part of HTML nor part of JS, it is rules that are implemented by browsers.**

  When a browser loads a web page, it creates a model of that page, called a `DOM tree`
    * Parts of a DOM tree: document node, element node, attribute node and text nodes

    Methods that return a single element node
    * `getElementById('id')`
    * `querySelector('css selector')`

    Methods that return one or more elements
    * `getElementsByClassName('class')` = allows you to select elements whose class attribute contains a specific value

    * `getElementsByTagName('tagName')` = allows yoou to select elements using their tag name

    * `querySelectorAll('css selector')` = treutnrs the first element node that matches the CSS-style selector 

    When a DOM method can return more than one element, it returns a `NodeList`. See pages 196 -197

    In order to select an element from a nodelist, you can use a `item()` but you have to specify the index number. You can also find though a `array syntax` which is faster. examples:

       * `var firstItem = elements.item(0);`
       * `var firstItem = elements [0];`

    WHen you have a NodeList, you can loop through each node in the collection and apply the same statements to each (see page 204). 


Source: Duckett, Jon. HTML & CSS. John Wiley & Sons Inc. 2011

Source: Duckett, Jon. JAVASCRIPT & JQUERY. John Wiley & Sons Inc. 2014 