# Class 39 Reading: Redux - Additional Topics

## Resources

- [Redux Toolkit](https://redux-toolkit.js.org/introduction/getting-started)
- [MobX](https://mobx.js.org/getting-started.html)
- [Tutorial](https://redux-toolkit.js.org/tutorials/overview)

## Redux Toolkit

1. What concerns are addressed by Redux Toolkit?

    - Redux Toolkit addresses three major concerns about Redux:
        1. "Configuring a Redux store is too complicated"
        2. "I have to add a lot of packages to get Redux to do anything useful"
        3. "Redux requires too much boilerplate code"

2. What does the `configureStore()` do?

    - `configureStore()` is a function that accepts a single configuration object argument, and returns a Redux store instance. It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension.

3. How would I use `createSlice()`?

    - `createSlice()` accepts an object of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with corresponding action creators and action types.

## MobX

1. What is MobX?

    - MobX is a simple, scalable, and battle tested state management solution. Instead of a traditional top-down approach, MobX uses a bottom-up approach. It allows you to update the state directly, and then MobX will make sure the right components are updated.

2. How does MobX make it "impossible" to produce an inconsistent state?

    - MobX makes it impossible to produce an inconsistent state by making sure that all changes to the state are tracked. If a change is made, MobX will make sure that all components that depend on that state are updated.

3. How would we build a reactive user interface?

    - We would build a reactive user interface by using MobX to track changes to the state, and then updating the components that depend on that state. This allows us to update the state directly, and then MobX will make sure the right components are updated.

## Tutorial

- [Tutorial](https://redux-toolkit.js.org/tutorials/overview)

1. What take-aways did this tutorial provide?

    - This tutorial provided a good overview of Redux Toolkit. It showed how to use Redux Toolkit to simplify common Redux use cases, and how to use Redux Toolkit to write "mutative" immutable update logic for your reducers.

### Bookmark and Review

- [Recux Toolkit (RTK)](https://redux-toolkit.js.org/)
- [HookState](https://hookstate.js.org/)

### Reflection

- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-39/)

1. What are your learning goals after reading and reviewing the class README?

    - [ ] Goal 1: I want to learn more about Redux Toolkit, like how to use Redux Toolkit to simplify common Redux use cases.

#### Things I Want to Know More About

1. I should really look further into the redux-toolkit. It looks like it could be very useful.

![GIF](https://media.giphy.com/media/l0G17S7BoPff3wGfC/giphy.gif)
