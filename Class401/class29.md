# Class 29 Reading: Advanced State with Reducers

## Resources

- [Extracting State Logic Into a Reducer](https://react.dev/learn/extracting-state-logic-into-a-reducer)

## Topic 1

1. What is the motivation for a reducer?

   - A reducer's motivation is to take in a state and an action and return a new state.

2. What are actions in the context of a reducer? How are they different than setting state directly?

   - Actions are objects that contain a type and a payload. They are different than setting state directly because they are passed into the reducer and the reducer returns a new state.

3. What common list operation is `useReduce()` nameed for, and why?

   - `useReduce()` is named for the reduce method. It is named this because it takes in a state and an action and returns a new state.

4. When should you switch from `useState()` to `useReducer()`?

   - You should switch from `useState()` to `useReducer()` when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. You should also switch when you have a lot of actions.

### Bookmark and Review

- [useReducer Hook](https://react.dev/reference/react/useReducer)
- [Keeping Components Pure](https://react.dev/learn/keeping-components-pure)
- [Queueing a Series of State Updates](https://react.dev/learn/queueing-a-series-of-state-updates)

### Reflection

- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-29/)

1. What are your learning goals after reading and reviewing the class README?

    - [ ] Goal 1: I struggled with state in the 301 course, and now it's getting even more complex. I aim to have the ability to describe and define reducers, actions, and dispatches, and to manage state using `useReducer()`.

#### Things I Want to Know More About

1. I need to learn more about reducers, actions, and dispatches. I also need to learn more about managing state using `useReducer()`. Because as of right now, I am still confused about all of it.

![GIF](https://media.giphy.com/media/wYXBg45usZ6T4MqxM8/giphy.gif)
