# Class 3 Reading: Express REST API

## Resources

- [ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
- [Using Express Routing](https://expressjs.com/en/guide/routing.html)
- [Express Routing](https://www.digitalocean.com/community/tutorials/learn-to-use-the-new-router-in-expressjs-4)
- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-03/)

### ES6 Classes

1. Classes are templates for creating _________.
    - Objects

2. Can a class declaration be hoisted?
    - No, class declarations are not hoisted.

3. How would you describe a constructor and contextual "this" to a non-technical friend?
    - A constructor is a function that is used to create an object. The "this" keyword refers to the object that is being created. It's elementary, Watson.

### Using Express Routing

1. Within Express, what does routing refer to?
    - Routing refers to determining how an application responds to a client request to a particular endpoint, which is a URI (or path) and a specific HTTP request method (GET, POST, and so on).

2. What is the difference between a route path and a route method?
    - A route path is a string that represents a URL path, and a route method is an HTTP request method.

3. When is it appropriate to add `next` as a parameter to a route handler and what must you do if `next` has been passed to your middleware as a parameter?
    - It is appropriate to add `next` as a parameter to a route handler when you want to pass control to the next middleware function in the stack. If `next` has been passed to your middleware as a parameter, you must call `next()` to pass control to the next middleware function.

### Express Routing

1. What is an Express Router?
    - An Express Router is a way to modularize your routes into separate files to keep your code clean and organized.

2. By what means do we initialize `express.Router()` in an express server?
    - We initialize `express.Router()` in an express server by using `app.use()`.

3. What do we use route middleware for?
    - We use route middleware for things like logging, validation, and handling errors.

#### Reflection

1. What are your learning goals after reading and reviewing the class README?
    - My learning goals after reading and reviewing the class README are to understand how to use Express to create a REST API and to understand how to use Express middleware.

#### Things I Want to Know More About
