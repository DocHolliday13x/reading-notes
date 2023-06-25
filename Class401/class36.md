# Class 36 Reading: Application State with Redux

## Resources

- [Dan Abramov Redux Tutorials](https://egghead.io/courses/fundamentals-of-redux-course-from-dan-abramov-bd5cc867)

## Dan Abramov Redux Tutorials

1. What is the first principle of Redux?

    - [x] Principle 1: The state of your whole application is stored in an object tree within a single store.
    - [ ] Principle 2: The only way to change the state is to emit an action, an object describing what happened.
    - [ ] Principle 3: To specify how the state tree is transformed by actions, you write pure reducers.

2. What is a store and what do we use our reducers for within that store?

    - A store is a single JavaScript object that holds the state of your application. The store has a method called `getState` that returns the current state value inside of it. The store also has a method called `dispatch` that accepts an action object as its argument. The store also has a method called `subscribe` that accepts a callback function that will be run every time an action is dispatched.

    - Reducers are functions that take the current state value and an action object as arguments, and return a new state result. In other words, (state, action) => newState.

3. Name three Redux store methods given to us by `createStore` and describe their use.

    - `getState` - returns the current state value inside of the store.
    - `dispatch` - accepts an action object as its argument.
    - `subscribe` - accepts a callback function that will be run every time an action is dispatched.

### Bookmark and Review

- [Worlds Easiest Guide to Redux](https://www.freecodecamp.org/news/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6)
- [Testing Reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)
- [Redux Docs](https://redux.js.org/)

### Reflection

- [Course Schedule](https://codefellows.github.io/code-401-javascript-guide/curriculum/#module-8)
- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-00/)

1. Looking ahead at this module's course schedule, what do you look forward to learning?

    - [ ] Answer 1: I look forward to learning more about Redux and how to implement it into future applications.

2. What are your learning goals after reading and reviewing the class README?

    - [ ] Goal 1: Practice Adj Matrix to Adj List conversion for the upcoming whiteboard challenge.

- ![Graph GIF](https://media.giphy.com/media/3og0IExSrnfW2kUaaI/giphy.gif)
