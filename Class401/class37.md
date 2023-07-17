# Class 37 Reading: Redux - Combined Reducers

## Resources

- [Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)
- [Redux Docs: Using Combined Reducers](https://redux.js.org/usage/structuring-reducers/using-combinereducers/)
- [Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)

## Multiple Reducers Example

1. Why create multiple reducers?

   - To keep the code clean and organized. It also allows for multiple reducers to be combined into one reducer.

2. How would you combine multiple reducers?

   - Using the `combineReducers` method from Redux. This method accepts an object as its argument, and each key/value pair in the object will become a key/value pair in the Redux state.

3. How will you manage state as an immutable object?

   - By using the `Object.assign()` method to create a new object with the updated state. This method accepts two arguments, the first being the object to be updated, and the second being the new state. The new state will overwrite the old state. This method will not mutate the original object.

## Redux Docs: Using Combined Reducers

1. `combineReducers` is a utility function to simplify the most common use case when writing `Redux reducers`. It turns an object whose values are different reducing functions into a single reducing function you can pass to `createStore`.

2. Explain how `combineReducers` assembles the new state tree.

   - `combineReducers` accepts an object full of slice reducer functions at its top level, and returns a new reducer function. When the new reducer is called, it calls each slice reducer with their current state and the current action, then it combines the results into a single state object. The state produced by `combineReducers()` namespaces the states of each reducer under their keys as passed to `combineReducers()`.

3. How would you define initial state in an application?

   - The initial state of the app is defined in the reducers. Each reducer will have its own initial state.

## Redux Docs: Combined Reducer Syntax

1. Why will you want to split your reducing functions as your app becomes more complex?

   - To keep the code clean and organized. It also allows for multiple reducers to be combined into one reducer.

2. The `combineReducers` helper function turns an object whose values are different reducing functions into a single reducing function you can pass to `createStore`. The resulting reducer calls every child reducer, and gathers their results into a single state object. The state produced by `combineReducers()` namespaces the states of each reducer under their keys as passed to `combineReducers()`.

3. What is a popular convention when naming reducers?

   - To name the reducer after the state slice it manages, rather than after the action type.

### Reflection

- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-37/)

1. What are your learning goals after reading and reviewing the class README?

    - [ ] Goal 1: I want to understand how to use Redux to manage state in my React applications.

#### Things I Want to Know More About

1. I would really like to learn more about combining reducers.

![GIF](https://media.giphy.com/media/jtPyWqapjIbFv1HJWu/giphy.gif)
