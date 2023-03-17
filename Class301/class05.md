# Class 05 Reading: Putting It All Together

## Resources

* [React Docs - Thinking in React](https://react.dev/learn/thinking-in-react)
* [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

### Reading Statement

Why this topic matters as it relates to the material I am studying:


### React Docs - Thinking in React

1. What is the single responsibility principle and how does it apply to components?

   * The Single Responsibility Principle (SRP) is a design principle in software development that states that each module, class, or function should have only one reason to change. In other words, a module, class, or function should have only one responsibility. A component is a modular and reusable piece of code that performs a specific task or functionality in a larger application. It's important to follow this principle to ensure that each component is responsible for only one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

2. What does it mean to build a static version of your application?

   * Building a "static" version of an application typically means creating a version of the application that is not connected to a backend server or database. This version of the application can be viewed as a collection of static files, such as HTML, CSS, and JavaScript files, that can be served directly from a web server without any dynamic processing. To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. Props are a way of passing data from parent to child. (If you’re familiar with the concept of state, don’t use state at all to build this static version. State is reserved only for interactivity, that is, data that changes over time. Since this is a static version of the app, you don’t need it.)

3. Once you have a static version of your application, what do you need to add?

   * You can either build “top down” by starting with building the components higher up in the hierarchy, or “bottom up” by working from components lower down. In simpler examples, it’s usually easier to go top-down, and on larger projects, it’s easier to go bottom-up. After building your components, you’ll have a library of reusable components that render your data model. Because this is a static app, the components will only return JSX. The component at the top of the hierarchy will take your data model as a prop.

4. What are the three questions you can ask to determine if something is in state?

   1. Does it remain unchanged over time? If so, it isn't state.
   2. Is it passed in from a parent via props? If so, it isn't state.
   3. Can you compute it based on existing state or props in your component? If so, it isn't state.

5. How can you identify where state needs to live?

   * React uses one-way data flow, passing data down the component hierarchy from parent to child component. You can identify where state needs to live by following these steps:
     1. Identify every component that renders something based on state.
     2. Find their closest common parent component - a component above them all in the heirarchy.
     3. Decide where the state should live:
        1. Often, you can put the state directly into the common parent.
        2. You can also put the state into some component above their common parent.
        3. If you can't find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the heirarchy above the common parent component.

### Higher-Order Functions

1. What is a higher-order function?

   * Functions that operate on other functions, either by taking them as arguments or by returning them.

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

   * The best way I can describe it is that line 2 is generating another function following the execution of it's parent function, and this particular function is doing the computing behind whether m is greater than n and if it is, to return that value.

3. Explain how either map or reduce operates, with regards to higher-order functions:

   * The map method transforms an array by applying a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array, but its content will have been mapped to a new form by the function.

#### Things I Would Like to Know More About...
