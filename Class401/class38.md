# Class 38 Reading: Redux - Asynchronous Actions

## Resources

- [Async Actions](https://redux.js.org/tutorials/fundamentals/part-6-async-logic)
- [Thunk Middleware](https://github.com/reduxjs/redux-thunk)

## Async Actions

1. Why use Redux middleware?

   - To handle asynchronous actions. Redux middleware provides a third-party extension point between dispatching an action, and the moment it reaches the reducer. It can be used for logging actions, reporting errors, making asynchronous requests, and more.

2. Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.

   - The flow begins with the React component calling `store.dispatch(action)`. The action is then passed to the middleware, which can either pass it on to the next middleware, or pass it to the reducers. The reducers then update the state, and the state is passed back to the React component.

3. How are we accomodating async in our Redux app?

   - By using the `redux-thunk` middleware. This middleware allows us to write action creators that return a function instead of an action. The thunk can be used to delay the dispatch of an action, or to dispatch only if a certain condition is met. The inner function receives the store methods `dispatch` and `getState` as parameters.

## Thunk Middleware

1. Why would you need `redux-thunk` middleware?

   - To handle asynchronous actions. Redux middleware provides a third-party extension point between dispatching an action, and the moment it reaches the reducer. It can be used for logging actions, reporting errors, making asynchronous requests, and more.

2. Redux Thunk middleware allows you to write action creators that return a *function* instead of an action.

3. Describe how any return value from the inner thunk function will be made available.

   - The inner function receives the store methods `dispatch` and `getState` as parameters. The inner function can then dispatch actions and read the current state of the Redux store.

### Reflection

- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-38/)

1. What are your learning goals after reading and reviewing the class README?

    - [ ] Goal 1: I want to learn more about Redux middleware, like how to use Redux middleware to handle asynchronous actions.

![GIF](https://media.giphy.com/media/3ogwFSQpfbWZ1dgc1y/giphy.gif)
