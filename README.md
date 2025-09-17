# Frontend-Interview

### Q1 CSS :- Difference Between relative and absolute
Answer:- Relative means the element is first placed in its normal position, and then you can shift it using top, left, right, or bottom.Even after moving, it still occupies its original space, so other elements are not affected.

Absolute means the element is taken out of the normal layout flow and placed exactly where you want using top, left, right, or bottom. It is positioned relative to the nearest parent that has a position (like relative, absolute, or fixed). If no such parent exists, it positions relative to the page (html/body).
***

### Q2 Javascript :- What are the different data types present in javascript?
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

### Q3 HTML :- The Basic Structure of an HTML Page
* **`<!DOCTYPE html>`**: This declaration is the very first line of code in an HTML document. It tells the browser that the document is an HTML5 page.
* **`<html>`** and **`</html>`**: These are the **opening** and **closing tags** that wrap around all the other content on the page. Everything inside these tags is part of the HTML document.
* **`<body>`** and **`</body>`**: The `body` element contains the visible content of your web page. All the text, images, links, and other elements that a user sees are placed inside the `<body>` tags.
* **Tags**: Tags are used to create elements in HTML. They usually come in pairs: an opening tag and a closing tag. For example, the **`<p>`** tag creates a paragraph, and it is closed with **`</p>`**. Some tags, like **`<img>`**, are self-closing.
* **Attributes**: Attributes provide additional information about an element. They are always specified in the opening tag. For example, **`align="center"`** is an attribute of the paragraph tag **`<p>`**, and it tells the browser to center the text. The **`src="image_path.jpeg"`** attribute for the **`<img>`** tag specifies the source or path of the image file.
***

### Q4 CSS What is the Box model in CSS?
In CSS, every element is treated like a box, which has content, padding, border, and margin. This is called the Box Model. It’s important for controlling spacing and layout on a webpage
* Content → The actual text, image, or content inside the box.
* Padding → The space between the content and the border (like breathing space inside the box).
* Border → The line (visible or invisible) around the padding and content.
* Margin → The outer space between this element’s border and the next element.
* ***

### Q5 Javascript Difference between “ == “ and “ === “ operators.
Both are comparison operators. The difference between both the operators is that “==” is used to compare values whereas, “ === “ is used to compare both values and types.

Example:
* var x = 2;
* var y = "2";
* (x == y)  // Returns true since the value of both x and y is the same
* (x === y) // Returns false since the typeof x is "number" and typeof y is "string"
***

### Q6 HTML What are tags and attributes in HTML?
Tags are the primary component of the HTML that defines how the content will be structured/ formatted, whereas Attributes are used along with the HTML tags to define the characteristics of the element. For example, <p align=” center”>Interview questions</p>,
***
***
***
***
***
