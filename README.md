# Frontend-Interview

Q1 CSS :- Difference Between relative and absolute
Answer:- Relative means the element is first placed in its normal position, and then you can shift it using top, left, right, or bottom. Even after moving, it still keeps its original space in the layout.
Absolute means the element is taken out of the normal layout flow and placed exactly where you want using top, left, right, or bottom. It is positioned relative to the nearest parent that has a position (like relative, absolute, or fixed). If no such parent exists, it positions relative to the page (html/body).

Q2 Javascript :- What are the different data types present in javascript?
JavaScript has two main kinds of data types: Primitive & nonPrimitive
In Primitive types there are
String - It represents a series of characters and is written with quotes. A string can be represented using a single or a double quote.
Number - It represents a number and can be written with or without decimals.
BigInt - This data type is used to store numbers which are above the limitation of the Number data type. It can store large integers { and is represented by adding “n” to an integer literal. }
Boolean - It represents a logical entity and can have only two values : true or false. Booleans are generally used for conditional testing.
Undefined - When a variable is declared but not assigned, it has the value of undefined and it’s type is also undefined.
Null - Represents no value or empty value.
Symbol - It is a new data type introduced in the ES6 version of javascript. It is used to store an anonymous and unique value.
And in Non-primitive 
Primitive data types can store only a single value. To store multiple and complex values, non-primitive data types are used.
Object - Used to store collection of data.  like array, function

Q3 HTML :- The Basic Structure of an HTML Page
* **`<!DOCTYPE html>`**: This declaration is the very first line of code in an HTML document. It tells the browser that the document is an HTML5 page.
* **`<html>`** and **`</html>`**: These are the **opening** and **closing tags** that wrap around all the other content on the page. Everything inside these tags is part of the HTML document.
* **`<body>`** and **`</body>`**: The `body` element contains the visible content of your web page. All the text, images, links, and other elements that a user sees are placed inside the `<body>` tags.

### Understanding Tags and Attributes
* **Tags**: Tags are used to create elements in HTML. They usually come in pairs: an opening tag and a closing tag. For example, the **`<p>`** tag creates a paragraph, and it is closed with **`</p>`**. Some tags, like **`<img>`**, are self-closing.
* **Attributes**: Attributes provide additional information about an element. They are always specified in the opening tag. For example, **`align="center"`** is an attribute of the paragraph tag **`<p>`**, and it tells the browser to center the text. The **`src="image_path.jpeg"`** attribute for the **`<img>`** tag specifies the source or path of the image file.
