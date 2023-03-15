# Class 04 Reading: React and Forms

## Resources

* [React Docs - Forms](https://reactjs.org/docs/forms.html)
* [Ternary Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)
* [React Bootstrap - Forms](https://react-bootstrap.github.io/forms/overview/)
* [React Docs - Conditional Rendering](https://reactjs.org/docs/conditional-rendering.html)

### Reading Statement

Why this topic matters as it relates to what I am studying in this module?

### React Docs - Forms

1. What is a "controlled component"?

An input form element whose value is controlled by REACT. We combine the HTML state which is updated based on user input, along with REACTs mutable state which is updated with setState(). With the controlled component, the input's value is always driven by the REACT state. You can pass the value to other UI elements too, or reset it from other event handlers.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them?

You don't want to directly update/mutate state in REACT, that's considered bad practice. It will cause issues in your application. Your component will not be re-rendered on state change if you make a direct state change, you have to use the setState function that allows us to update the value of the state.

3. How do we target what the user is entering if we have an event handler on an input field?

You have to bind it in the constructor by using classes and arrow functions.

### The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?

It can shorten your if statements into one line of code. 

2. Rewrite the following statement using a ternary statement:
if(x===y){
  console.log(true);
} else {
  console.log(false);
}



#### Things I Would Like to Know More About

1.
2.
3.
