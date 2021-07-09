
# How to build a site

The first step in designing a website is understanding your target audience. It's important to design a website with different consumer perspectives in mind. The pool of consumers will likely have a wide range of varying traits so creating consumer personas can be a helpful step in grouping similar sets of users to better hone in on user motivations and goals.

### Why is this important?

  * You know **WHO** is coming to your site
  * You know **WHY** they are coming to your site and what information they are seeking
  * It provide cues on how to best design a website 


Useful tools to mapping out site are a **Site Map** and a **Wireframe**

  * Site map: diagram that will show how pages can be grouped
  * Wireframe: simple sketch of the info that needs to go on each page. Think about this as a sketch of a newspaper layout


# HTML

HTML desbribes the structures of web pages. Think about a newspaper or Microsoft word document, each has beginning, middle, and an end blocks. HTML code lives inside angled brackets. For example: `<body></body>` or `<head></head>` Example of basic HTML with a header and a body: 

```
<!DOCTYPE html>
<html>
<head>
  <title>My First HTML</title>
  <meta charset="UTF-8">
</head>
<body>

<p>The HTML head element contains meta data.</p>
<p>Meta data is data about the HTML document.</p>

</body>
</html>
```

### HTML5

There have been several versions of HTML with the newest version trying to improve on the last. HTML5 is indroducing a new set of elements that improve efficiency when structuring a page. The new elements provide clearer code. Important to note that some older browers might not support newer HTML features.

# JavaScript
Javascript is language that add more dynamic features to a site thus enhancing the experience of a user. It's best practice to keep JS code its own file/.js extension, separate from HTML pages and CSS style sheets. The way you reference JS is by announcing it in HTML with `<script>name of .js extension</script`>

# HTML, CSS, JavaScript working together

HTML provides structure (Skeleton/Frame or Black and White/Text/Not Pretty), CSS enhances HTML and adds a presentation layer(Interior Designer/Presentation or colors/text size/picture and sizing), and JS adds interactivity and makes the site more dynamic (Smarthome or bells and whistles/fun/moving pictures)


# Cheatsheet

* elements = characters that live inside angled brackets, usally made of two tags
* ID attribute = uniquely identify an element from other elements
* class attribute = way to identify a group of elements 
* `<!-- comment goes here -->` = comments in HTML
* block elements = always appear to start on a new line (i.e `<h1>`, `<p>`, `<ul>`)
* inline elements = appear to continue on the same line as neighboring elements (i.e. `<a>`, `<img>`)
* `<div>` = allows you to group a set of elements together in one block level box
* `<span>` = inline equivalent of `<div>`
* `<iframe>` = a little window that has been cut into the page...think small google map on page
* `<meta>` = element that lives inside the head element and contains info about the web page