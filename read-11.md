# Readings: Audio, Video, Images

## Video and Audio Content
### Explain how the ability to use video and audio on the web has evolved since the early 2000s.
In the early 2000s, we had proprietary plugin-based technologies that had security and accessibility issues.  Now, we native HTML solutions `<video>` and `<audio>` elements and the availability of JavaScript APIs for controlling them.

### Describe the use of the `src` and `controls` attributes in the `<video>` element.
The `src` (source) attribute contains a path to the video you want to embed.
The ‘controls` attribute allows users to control video and audio playback.
The `<video>` element allows you to embed a video.

### Why is it important to have fallback content inside the ‘<video>’ element?
Fallback content will be displayed if the browser accessing the page doesn't support the `<video>` element, allowing a fallback for older browsers.

### Write a very short story where `<audio>` and `<video>` are characters.
Once there was an `<audio>` tag who enjoyed playing music for people.  She heard about a new guy they called `<video>` tag.  She heard that he not only played sound but showed moving images as well.  She was very jealous.  But then she saw her single ability allowed her guest to enjoy her page while hearing their favorite tracks.  When she saw `<video>` tag’s guests, she thought they looked like zombies.  

## A Complete Guide To Grid
### How does Grid layout differ from Flex?
The difference between Grid and Flexbox is that flex was designed for layout in one dimension - either a row or a column. Grid was designed for a two-dimensional layout - rows, and columns at the same time.

### Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
- Grid Container - The element on which display: grid is applied. It’s the direct parent of all the grid items.
- Grid Item - The children (i.e. direct descendants) of the grid container.
- Grid Line - The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column.


## Responsive Images
### Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
Having responsive images helps us deliver optimal file size, displays the right image for the right screen size, improves user experience, and improves loading time.

### Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.
The `srcset` attribute allows you to define a list of different image resources along with size information so that browser can pick the most appropriate image based on the actual device's resolution.

The `sizes` attribute on an `<img>` element specifies different image widths.  These widths are tied to browser conditions which help create responsive images.

### How is `srcset` more helpful for responsive images than CSS or JavaScript?
The `srcset` attribute allows us to provide a comma-separated list of image sources with corresponding widths to an image tag. This lets the browser make a decision as to which image is the most appropriate to download.  CSS and JS don’t.

[HOME](https://aedeleon2023.github.io/reading-notes/)
