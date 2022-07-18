# Problem Domain, Objects, and the DOM

### How would you describe an object to a non-technical friend you grew up with?
An object is a pairing of a name and value together.  So you have your label, the name) and then you define it, the value, with more detail or even a series of instructions to follow.  Think of me telling a dog to sit, that would be me calling out a name.  The dog would then go through the steps to sit, that would be the value or series of instructions built into me just calling out, “sit”.

### What are some advantages to creating object literals?
Object literals allow for simpler, shorter syntax and are easier to work with than an array.

### How do objects differ from arrays?
Interestingly, arrays are objects.  Arrays and objects both store information.  Arrays use numbers to access its "elements".  Objects use names to access its "members".  It’s all about what you want stored, and how you want to access that storage later on.  Groups of similarly typed data, which you need ordered or want to manipulate as a batch are better suited for arrays, and grouped properties of a single entity are better suited for objects.

### Give an example of when you would need to use bracket notation to access an object’s property instead of dot notation.
If an object property name is defined at runtime then you can't use dot notation to access the value.

### Evaluate the code below. What does this term refer to, and what is the advantage to using this?
`const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log('${this.name} is ${this.age*7} in human years');
  }
}`

This is bracket notation.  Setting members doesn't just stop at updating the values of existing properties and methods; you can also create completely new members.

### What is the DOM?
The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

### Briefly describe the relationship between the DOM and JavaScript.
DOM is an object-oriented representation of the web page, it can be modified with a scripting language such as JavaScript.

[HOME](https://aedeleon2023.github.io/reading-notes/)
