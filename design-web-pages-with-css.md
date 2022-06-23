# Design Web Pages With CSS

CSS, Cascading Style Sheets, is a language that styles mark-ups.  Think of color, layout, and font and that is CSS.

**To make a CSS rule we need:**
* a Selector - this is the HTML element that we will be styling.
* Curly Braces - between these will lie our declarations
* Declarations - these take the form of property, colon, value, and semi-colon

For example, to give our `<h1>` element a red color we would write this:

`h1  {
      color: red;
 }`

**There are three ways to use CSS**:
* External - create a separate file to style a whole webpage
* Internal - At the top of your HTML file you can include a CSS section
* Inline - you can include CSS into a single HTML element

If CSS rules should compete for the same element then inline commands will win.  If no inline CSS exists then the first rule take precedence.  The !important instruction has the highest precedence of all precedence factors.

**The Color property, in CSS, has three values:**
* Color - specifies  the color of the HTML element
* Initial - sets the color to the default
* Inherent - sets the color from its parent element

**There are five ways to input the color value:**
* HEX
* RGB 
* RGBA
* HSL
* HSLA

[HOME](https://aedeleon2023.github.io/reading-notes/)
