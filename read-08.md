# CSS Layout

### Flexbox is designed for one-dimensional content. Explain what this means.
Flexbox only deals with layout in a single direction, in columns or rows.

### Explain the difference between the main axis and the cross axis.
The main axis is the one set by your `flex-direction` property. If that is `row` your main axis is along the row, if it is `column` your main axis is along the column.

### How can using certain properties of flexbox negatively impact accessibility?
Certain properties of flexbox can negatively impact accessibility by reordering the visual display away from how things are ordered in the HTML document.  The reordering only happens for the visual order, not the logical order.  The logical order is the order that a screen reader will read out the content, therefore making the two disjointed.

### What are some advantages of using flexbox over float?
**Flexbox offers:**
- Vertically centering a block of content inside its parent.
- Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.
- Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.

**Float offers:**
- Limitations
- Frustrations

### How does this topic connect with your long-term goals?
I plan to only use Flexbox going forward into the future.


[HOME](https://aedeleon2023.github.io/reading-notes/)
