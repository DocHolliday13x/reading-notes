# Class 07 Reading Assignment

## Domain Modeling

[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

1. Explain why we need domain modeling:
Domain modeling is the process of creating a conceptual model in code for a specific problem. A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

## HTML Table Basics

![HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

1. Why should tables not be used for page layouts?
Layout tables reduce accessibility for visually impaired users. Tables produce tag soup. Tables are not automatically responsive.

2. List and describe 3 different semantic HTML elements used in an HTML <table>:
   1. <td> / <tr> table data / table row
   2. <th> table headers
   3. <col> styling info for an entire column of data in one place.

## Introducing Constructors

[Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

1. What is a constructor and what are some advantages to using it?
A special function that creates and initiializes an object instance of a class. The constructor gets called when an object is created using the new keyword. The constructor creates a new object and set values for any existing object properties.

2. How does the term <this> differ when used in an object literal versus when used in a constructor?
When you only have to create a single object literal, it's not very useful. But when creating more than one, <this> enables you to use the same methond definition for every object you create.

## Object Prototypes Using a Constructor

[Object Prototypes Using a Constructor](https://ui.dev/beginners-guide-to-javascript-prototype)

1. Explain prototypes and inheritance via an anlogy from your previous work experience. <!-- This is a VERY common front-end developer interview question! -->
Every function in JavaScript has a prototype property that references an object. The most important difference between class- and prototype-based inheritance is that a class defines a type which can be instantiated at runtime, whereas a prototype is itself an object instance.

## Bookmark and Review

[HTML Table Advanced Features and Accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)