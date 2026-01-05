# Frontend-Interview

###   1.HTML:- The Basic Structure of an HTML Page (html)
* **`<!DOCTYPE html>`**: This declaration is the very first line of code in an HTML document. It tells the browser that the document is an HTML5 page.
* **`<html>`** and **`</html>`**: These are the **opening** and **closing tags** that wrap around all the other content on the page. Everything inside these tags is part of the HTML document.
* **`<body>`** and **`</body>`**: The `body` element contains the visible content of your web page. All the text, images, links, and other elements that a user sees are placed inside the `<body>` tags.
* **Tags**: Tags are used to create elements in HTML. They usually come in pairs: an opening tag and a closing tag. For example, the **`<p>`** tag creates a paragraph, and it is closed with **`</p>`**. Some tags, like **`<img>`**, are self-closing.
* **Attributes**: Attributes provide additional information about an element. They are always specified in the opening tag. For example, **`align="center"`** is an attribute of the paragraph tag **`<p>`**, and it tells the browser to center the text. The **`src="image_path.jpeg"`** attribute for the **`<img>`** tag specifies the source or path of the image file.
***

###   2.HTML:- What are tags and attributes in HTML?
Tags are the primary component of the HTML that defines how the content will be structured/ formatted, whereas Attributes are used along with the HTML tags to define the characteristics of the element. For example, <p align=” center”> Interview questions **`</p>`**.
***

###  3.HTML:- What are void elements in HTML?
HTML elements which do not have closing tags or do not need to be closed are Void elements. For Example: `<br />`, `<img />`, `<hr />` etc
***

### 4.HTML:- What are different types of lists in HTML?
there are mainly three types of lists used to organize content. Ordered lists (&lt;ol&gt;) are used when the items need to follow a specific sequence, and they are usually displayed with numbers or letters. Unordered lists (&lt;ul&gt;) are used when the order of items doesn’t matter, and they are displayed with bullet points by default. Description lists (&lt;dl&gt;) are used to define terms and their descriptions, where &lt;dt&gt; represents the term and &lt;dd&gt; represents its definition.
***
### 5.HTML:- What are the various formatting tags in HTML?
formatting tags are used to style and emphasize text. Some of the commonly used tags are:
&lt;b&gt; for bold text, &lt;i&gt; for italic text, and &lt;em&gt; which also makes text italic but adds semantic importance.
&lt;strong&gt; highlights text as important, while &lt;mark&gt; highlights text with a background color.
&lt;small&gt; reduces the text size, whereas &lt;big&gt; increases it.
For scientific or mathematical notations, we use &lt;sub&gt; for subscript and &lt;sup&gt; for superscript.
&lt;del&gt; shows text as deleted with a strikethrough, and &lt;ins&gt; shows inserted or added text.
***

### 6.HTML:- What is the difference between &lt;strong&gt;, &lt;b&gt; tags and &lt;em&gt;, &lt;i&gt; tags?
both &lt;strong&gt; and &lt;b&gt; make text appear bold, but their meaning is different. The &lt;b&gt; tag is used only for styling, while &lt;strong&gt; adds semantic importance, telling browsers and search engines that the text is important. Similarly, both &lt;em&gt; and &lt;i&gt; make text appear italic, but &lt;em&gt; adds emphasis with meaning, while &lt;i&gt; is just for visual styling without extra importance. Using &lt;strong&gt; and &lt;em&gt; is preferred for accessibility and SEO.
***

### 6.HTML:- What is the difference between &lt;strong&gt;, &lt;b&gt; tags and &lt;em&gt;, &lt;i&gt; tags?
both &lt;strong&gt; and &lt;b&gt; make text appear bold, but their meaning is different. The &lt;b&gt; tag is used only for styling, while &lt;strong&gt; adds semantic importance, telling browsers and search engines that the text is important. Similarly, both &lt;em&gt; and &lt;i&gt; make text appear italic, but &lt;em&gt; adds emphasis with meaning, while &lt;i&gt; is just for visual styling without extra importance. Using &lt;strong&gt; and &lt;em&gt; is preferred for accessibility and SEO.
***


###   1.CSS:- Difference Between relative and absolute
Answer:- Relative means the element is first placed in its normal position, and then you can shift it using top, left, right, or bottom.Even after moving, it still occupies its original space, so other elements are not affected.
Absolute means the element is taken out of the normal layout flow and placed exactly where you want using top, left, right, or bottom. It is positioned relative to the nearest parent that has a position (like relative, absolute, or fixed). If no such parent exists, it positions relative to the page (html/body).
***

###   2.CSS:- What is the Box model in CSS?
In CSS, every element is treated like a box, which has content, padding, border, and margin. This is called the Box Model. It’s important for controlling spacing and layout on a webpage
* Content → The actual text, image, or content inside the box.
* Padding → The space between the content and the border (like breathing space inside the box).
* Border → The line (visible or invisible) around the padding and content.
* Margin → The outer space between this element’s border and the next element.
* ***

###   3.CSS:- Display Properties in CSS?
block me elements ek ke niche ek aate hai inline me horizontal single me aate hai
The display property in CSS controls how an element appears in the layout. Block elements start on a new line and take full width, inline elements stay in the same line and don’t allow width or height, while inline-block allows inline placement with width and height. We also use display: none to hide elements, display: flex for one-dimensional layout, and display: grid for two-dimensional layouts. This property helps in managing how elements occupy space on a webpage
* ***

###   4.CSS:- What are the different types of Selectors in CSS?
CSS **selectors** are used to target HTML elements and apply styles.\

* /* Universal Selector */
* {
  margin: 0;
  padding: 0;
}
* /* Type Selector */
p {
  color: blue;
}
* /* Class Selector */
.button {
  background: green;
}
* /* ID Selector */
#header {
  font-size: 20px;
}
* /* Grouping Selector */
h1, h2, h3 {
  color: red;
}
* /* Pseudo-class */
a:hover {
  color: red;
}
*  /* Pseudo-element */
p::first-letter {
  font-size: 30px;
}
***
## 5. CSS: Difference between block, inline, and inline-block elements

1. Block Elements
**Interview Answer:**  
Block elements take full width of their parent and always start on a new line.

**Box Model:**  
- width, height, padding, margin (all sides) work

**Default Behavior:**  
- Width is 100% if not specified

2. Inline Elements
**Interview Answer:**  
Inline elements stay on the same line, take only content width, and do not support width and height.

**Box Model:**  
- width and height are ignored  
- padding and margin work only left and right

**Default Behavior:**  
- Flow with text

3. Inline-Block Elements
**Interview Answer:**  
Inline-block elements stay on the same line and allow full box styling like block elements.

**Box Model:**  
- width, height, padding, margin (all sides) work

**Use Case:**  
- Buttons, navigation items, horizontal cards

One-Line Summary
Block elements start on a new line and take full width, inline elements stay inline and ignore sizing, while inline-block stays inline and supports full box styling.
---

###   1.Javascript:- What are the different data types present in javascript?
JavaScript has two main kinds of data types: Primitive & nonPrimitive

In Primitive types there are
String - It represents a series of characters and is written with quotes. A string can be represented using a single or a double quote.
Number - It represents a number and can be written with or without decimals.
BigInt - This data type is used to store numbers which are above the limitation of the Number data type. It can store large integers { and is represented by adding “n” to an integer literal. }
Boolean - It represents a logical entity and can have only two values : true or false. Booleans are generally used for conditional testing.
Undefined - When a variable is declared but not assigned, it has the value of undefined and it’s type is also undefined.
Null - Represents no value or empty value.
Symbol - It is a new data type introduced in the ES6 version of javascript. It is used to store an anonymous and unique value.

In Non-primitive 
Primitive data types can store only a single value. To store multiple and complex values, non-primitive data types are used.
Object - Used to store collection of data.  like array, function
***

###  2.Javascript:- What is the difference between var, let, and const in JavaScript?
var is function-scoped, which means it is accessible throughout the entire function in which it is declared, even outside of block statements like if or for. On the other hand, let and const are block-scoped, meaning they are only accessible within the specific block { } where they are defined. This makes let and const safer to use because they prevent accidental access or modification outside their intended block. Generally, const is used for values that should not change, while let is used when the value needs to be updated
***

###  3.Javascript:- Difference between “ == “ and “ === “ operators.
Both are comparison operators. The difference between both the operators is that “==” is used to compare values whereas, “ === “ is used to compare both values and types.
Example:
* var x = 2;
* var y = "2";
* (x == y)  // Returns true since the value of both x and y is the same
* (x === y) // Returns false since the typeof x is "number" and typeof y is "string"
***

###  1.React:- What is React?
React is an open-source, front-end JavaScript library for building user interfaces, that focuses on reusable components and virtual DOM for performance.
***

###  2.React:- What is React component?
A React component is the basic building block of a React application.
It is a reusable piece of UI that controls what appears on the screen and how it behaves.
***

###  3.React:- What is JSX and why do we use it in React?
JSX is a syntax extension for JavaScript used in React to write HTML-like code inside JavaScript. It makes UI code more readable, allows combining logic and markup in one place.
***

###  4.React:- What is Virtual DOM in React?
The Virtual DOM is a lightweight copy of the real DOM that React keeps in memory.
When something changes in the app, React first updates the Virtual DOM instead of updating the real DOM directly.
React then compares the new Virtual DOM with the old one and updates only the changed parts in the real DOM. This makes the application faster and more efficient.
***

###  5.React:- How do you create a component in React?
A React component is created by defining a JavaScript function that returns JSX and exporting it for reuse.
***

###  6.React:- What is React Router?
React Router is a tool that lets you move between pages in a React app without reloading the page.
***

###  7.React:- What is a stateful component?
A stateful component is a React component that stores and manages its own data using state. This data can change over time due to user actions, API responses, or events. Whenever the state changes, React automatically re-renders the component to update the UI. In modern React, stateful components are usually created using functional components with Hooks like useState and useEffect, while earlier they were implemented using class components with this.state and setState.
***


***

***


***

***

***

***



***

***



***

***



***

***

***
