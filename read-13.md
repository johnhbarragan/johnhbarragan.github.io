# Local Storage

For native applications, the OS typically provides an abstraction layer for storing and retrieving application specific data. These values may be stored in a registry, INI files, XML files, or some other place according to platform convention. 

Cookies were can be used for persistent local storage of small amounts of data. 

# HTML 5 Storage

Web Storage which is certain browsers refer to "Local Storage" or "DOM Storage" is a way for web pages to store named key/value pairs locally, within the client web browser. Data is never transmitted to the remote web server. 

  * From the JS code, you can access storage through `localStorage` object on the global `window` object. 

## Using HTML5 storage
HTML5 storage is based on named key/value pairs with the key being a string. If you are storing anything other than string, you will need to use functions like `parseInt()` or `parseFloat()` to coerce your retrieved data into the expected JS datatype

## Tracking changes to the storage area
You can trap the storage event whenever a `setItem()`, `removeItem()`, or `clear()` is called and actually changes something. 