# Class 06 Reading Assignment

## JavaScript Object Basics

[JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

1. How would you describe an object to a non-technical friend yoiu grew up with?
An object is a collection of related data and/or functionality. They usually consist of several variables and functions (properties/methods when inside objects). It's easiest to think of it like a key with an assigned value.

2. What are some advantages to creating object literals?
It's common use when you want to transfer a series of structured, related data items in some manner, for example sending a request to the server to be put into a database. Sending a single object is more efficient than than sending several items individually.

3. How do objects differ from arrays?
They're easier to work with than an array when you want to identify individual items by name.


4. Give an example for when you wouild need to use bracket notations to access an object's property instead of dot notation:
If an object property name is held in a variable, you can't use dot notation to access the value, you have to use bracket notation.

5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?
![q5](img/class06Reading)

"this" enables us to use the same method definition for every object we create.
Here, "this" is refering to the method definitions name and age. It's advantage is that we can create more than a single object literal.

## Introduction to the DOM

[Introduction to the Dom](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

1. What is the DOM?
Document Object Model, the data representation of the objects that comprise the structure and content of a document on the web.

2. Briefly describe the relationship between the DOM and JavaScript:
The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts. The document as a whole, the head, tables within the document, table headers, text within the table cells, and all other elements in a document are parts of the document object model for that document. They can all be accessed and manipulated using the DOM and a scripting language like JavaScript. The DOM is not part of the JavaScript language, but is instead a web API used to build websites. The DOM was designed to be independent of any particular programming language, making the structural representation of the document available from a single, consistent API. Even if most web developers will only use the DOM through JavaScript, implementations of the DOM can be built for any language.

## Bookmark and Review

[Understanding Problem Domain](https://simpleprogrammer.com/solving-problems-breaking-it-down/)
[Difference Between Primitive Values and Object References](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)

## Things I Want to Know More About

In the udemy course I was studying prior to starting with code fellows, I left off prior to DOM manipulation. I know that is probably where we are going with this, so I need to better understand the relationship between JavaScript and the DOM.
