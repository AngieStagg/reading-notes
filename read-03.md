# HTML Lists, Control Flow with JS, and the CSS Box Model


## Learn HTML

### When should you use an unordered list in your HTML document?
You would use an `<ul>` to create a list of related items, in no particular order.

### How do you change the bullet style of unordered list items?
To change the bullet style, use the STYLE attribute. Then set its value as “list-style-type: format” where format is the word circle, square, or disc. You add the STYLE attribute within the `<ul>` start tag. ` <ul style="list-style-type: disc;">`

### When should you use an ordered list vs an unordered list in your HTML document?
You would use an ordered list when you want the contents in sequential order.

### Describe two ways you can change the numbers on list items provided by an ordered list?
You can state at what number to start.  `<ol start="4">`  You can also reverse the order and have it countdown. `<ol start="3" reversed>`


## Learn CSS

### Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
The Box Model is the story of a vase being packaged for a long journey.  The role of padding is played by bubble wrap which wraps around the fragile vase and protects it from the box, also known as the border.  The margin watches over the proximity of the vase’s box to other boxes and anything else.  

### List and describe the four parts of an HTML elements box as referred to by the box model.
The four components are Content, Padding, Border, and Margin.  Around the content is padding.  Around the padding is the border, which frames the end of the box.  Around the box is the margin that adjusts how close it lies to its neighbors.


## Learn JS

### What data types can you store inside of an Array?
An array may contain data of any data type, including numbers, strings, booleans, functions, objects, and even other arrays.

### Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why? 
`const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];`

Yes, you can access the values stored in the console.

### List five shorthand operators for assignment in javascript and describe what they do.
`|=	Shorthand Bitwise Inclusive OR
&=	Shorthand Bitwise AND
^=	Shorthand Bitwise XOR
<<=	Shorthand Bitwise Left Shift
>>=	Shorthand Bitwise Right Shift`

### Read the code below and evaluate the last expression and explain what the result would be and why.
 `let a = 10;
 let b = 'dog';
 let c = false;
// evaluate this
(a + c) + b;`

I’m really not sure.  My guess would be (10 + ‘dog’) + false, based on what I know of math.  


### Describe a real-world example of when a conditional statement should be used in a JavaScript program.
In a game, if the player's number of lives is 0, then it's game over. In a weather app, you would see a sunrise picture in the morning and the moon at night.

### Give an example of when a Loop is useful in JavaScript.
Loops are useful when you have to execute the same lines of code repeatedly, for a specific number of times, or as long as a specific condition is true.

[HOME](https://aedeleon2023.github.io/reading-notes/)
