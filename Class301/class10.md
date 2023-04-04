# Class 10 Reading: In Memory Storage

## Resources

* [Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)
* [JavaScript Error Message](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

### Reading Statement

Why this topic matters as it relates to the material I am studying: This topic matters because it is important to understand how the call stack works in order to understand how to debug code.

### Understanding the JavaScript Call Stack

1. *What is a call?* A call is a function invocation.

2. *How many 'calls' can happen at once?* One.

3. *What does LIFO mean?* Last In First Out.

4. *Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.* ![call stack](./callstack.png) 

5. *What causes a Stack Overflow?* A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.

### JavaScript Error Messages

1. *What is a 'reference error'?* A reference error is when you try to use a variable that is not yet declared.

2. *What is a 'syntax error'?* A syntax error is when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

3. *What is a 'range error'?* A range error is when you try to manipulate an object with some kind of length and give it an invalid length.

4. *What is a 'type error'?* A type error is when the types (number, string, etc.) you are trying to use or access are incompatible.

5. *What is a breakpoint?* A breakpoint is a point in your code where you can pause the execution of your code.

6. *What does the word 'debugger' do in your code?* The word debugger in your code will pause the execution of your code.

#### Bookmark and Review

* [JavaScript Error Reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)

#### Things I Would Like to Know More About

1. How to use the debugger in VS Code.
