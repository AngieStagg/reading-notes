# Readings: Chart.js, Canvas

## JavaScript Canvas
### What does the `<canvas>` allow a developer to achieve?
The <canvas> element allows a developer to draw 2D graphics using JavaScript.

### What is the importance of the closing `</canvas>` tag?
Unlike the `<img>` element, The `<canvas>` element requires the closing tag `</canvas>`. Any content between the opening and closing tags is fallback content that will display only if the browser doesn’t support the `<canvas>` element.

### Explain what the `getContext()` method does.
The getContext() method returns a render context object.  Initially, the canvas is blank. To draw something, you need to access the rendering context and use it to draw on the canvas.


## Chart.js Documentation:
### What is Chart.js and how it can be brought into your project?
Chart.js is an free JavaScript library for making HTML-based charts. It is one of the simplest visualization libraries for JavaScript, and comes with the following built-in chart types:

- Scatter Plot
- Line Chart
- Bar Chart
- Pie Chart
- Donut Chart
- Bubble Chart
- Area Chart
- Radar Chart
- Mixed Chart

To use:
First, add a link to the providing CDN (Content Delivery Network):

  `<script`
`src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.9.4/Chart.js">`
`</script>`

Then, add a `<canvas>` to where you want to draw the chart:

  `<canvas id="myChart" style="width:100%;max-width:700px"></canvas>`

Make sure the canvas element has a unique id, and that’s it.

### List 3 different Chart types you can create using Chart.js.
See the list in the previous question.


## Easily Create Stunning Animated Charts with Chart.js

### What are some advantages to displaying data via a chart over a table?
Charts are far better for displaying data visually than tables, they’re easier to look at and convey data quickly.

### How could Chart.js aid your previously created applications visually?
Aid, or destroy and remake?  It will make them look a heck of a lot better.  

[HOME](https://aedeleon2023.github.io/reading-notes/)
