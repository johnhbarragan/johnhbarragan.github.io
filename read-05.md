# Images
Having images in a separate folder helps you understand how the site is organized. On a big site, you could add subfolders.

`<img>` = used to add an image, no closing tag needed
`<src>` = tells the browser where it can find the image file
`<alt>` = provides a text description of teh image which describes the image if you cannot see it
`<title>` =  attribute which provides addition info about the image. see page 99

You can specify size in HTML but more popular in CSS

JPEG = save photos when there is many different colors
GIF or PNG = saving images with few or large areas of color 

`<figure>` = HTML5 element to contain images and their caption so that the two are associated. You can have more than one photo in a figure element but they would all have same caption. 
`<figcaption>` = adds caption to the photo

# Color
`color` = allows you to specify the color of text inside an element 
`background-color` = sets color of the background for that box 
`opacity` = allows you to specify the opacity of an element 

There are three ways to specify colors in CSS: RGB values, hex codes, and color names

# Text
**SERIF** = fonts have extra details on the ends of the main stroks of letters
**SANS-SERIF** = have straight ends to letters
**MONOSPACE** = Every letter in a monospace (fixed width) font is the same width 

`font-family` allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies

`font-size` can be edited in pixels, percentages (the default size of a text in broswers is 16px), or ems (an em is equivalent to the width of a letter m)

`font-weight` used to bold text, can be set to normal or bold

`font-style` used to italicize text

`text-transform` used to change the case of a text giving it one of the following: **uppercase**, **lowercase**, and **capitalize**

`text-decoration` cause be used to underline, overline, line-through, blink, none

`line-height` is for the vertical space between lines of text! Example:
  * ```
  p {
      line-height: 1.4em;
  } ```

`letter-spacing` 
`word-spacing`

Alignment can be adjusted with `text-align` or `vertical-align`

### Stying links (starting page 290)
`:link` allows you to set styles for links that have not been visisted
`:visited` allows you to set styles for links that have been clicked on
`:hover` applied when a user hovers over an element
`:active` applied when an element is being activated by a user


Source: Duckett, Jon. HTML & CSS. John Wiley & Sons Inc. 2011

Source: Duckett, Jon. JAVASCRIPT & JQUERY. John Wiley & Sons Inc. 2014 