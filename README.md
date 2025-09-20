# Frontend-Interview

###   1.HTML:- The Basic Structure of an HTML Page
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


###   3.CSS:- What are the different types of Selectors in CSS?
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
* /* Descendant Selector */
div p {
  color: gray;
}
* /* Child Selector */
div > p {
  font-weight: bold;
}
* /* Adjacent Sibling Selector */
h1 + p {
  color: orange;
}
* /* General Sibling Selector */
h1 ~ p {
  font-style: italic;
}
* /* Attribute Selector */
input[type="text"] {
  border: 1px solid black;
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
React is a front-end and open-source JavaScript library which is useful in developing user interfaces specifically for applications with a single page. It is helpful in building complex and reusable user interface(UI) components of mobile and web applications as it follows the component-based approach.

The important features of React are:

* It supports server-side rendering.
* It will make use of the virtual DOM rather than real DOM (Data Object Model) as RealDOM manipulations are expensive.
* It uses reusable or composable UI components for developing the view.




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

***



***

***

***
