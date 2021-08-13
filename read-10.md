# Error Handling and Debugging
You need to know the **ORDER OF EXECUTION** which might be in a different order than you might expect. 

The JS interpreter uses the concept of **EXECUTION CONTEXTS**
  * Global context = code that is in script but not in function
  * Function context = code that is being run within a function
  * Eval context = text is executed like code in an internal function called eval()

JavaScript interpreter processes one line of code at a time. When a statement needs data from another function, it **STACKS** the new function on top of the current task. 

If a JS statement generates an error, then it throws an **EXCEPTION**. Examples:
  * `SyntaxError` = syntax has not been followed
  * `TypeError` = an unexpected data type that cannot be coerced
  * `ReferenceError` = tried to reference a variable that is not declared/within scope 

When finding an error in google Chrome, you can type in the console and it will show you a results 

If you know your code might fail, use **try**, **catch**, and **finally** (see page 480-481)



Source: Duckett, Jon. HTML & CSS. John Wiley & Sons Inc. 2011

Source: Duckett, Jon. JAVASCRIPT & JQUERY. John Wiley & Sons Inc. 2014 
