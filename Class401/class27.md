# Class 00 Reading: Topic

## Resources

- [Thinking in React](https://react.dev/learn/thinking-in-react)
- [State: A Component's Memory](https://react.dev/learn/state-a-components-memory)

## Thinking in React

1. Summarize the five steps of thinking in react.

    - The five steps of thinking in React are:
        1. Break the UI into a component hierarchy
           - Draw boxes around every component (and subcomponent) in the mock and give them all names.
        2. Build a static version in React
           - Build a version of the UI that takes the data model and renders the UI but has no interactivity.
        3. Identify the minimal (but complete) representation of UI state
           - Identify the minimal set of mutable state that the UI needs.
        4. Identify where your state should live
           - Identify which component each piece of state should live in.
        5. Add inverse data flow
           - Add inverse data flow to make the UI interactive.

## State: A Component's Memory

1. What is one reason a local variable isn’t sufficient for managing a React component?

    - Local variables are not sufficient for managing a React component because they are not preserved between renders. They are reinitialized each time the component is rendered. This means that they cannot be used to store state.

2. What is the argument to the useState hook, and what are the two parts of its return array?

    - The argument to the useState hook is the initial state. The two parts of its return array are the current state and a function that updates the state. The function that updates the state can be called with a new state value, which will cause the component to re-render with the new state value. The function that updates the state can also be called with a function that takes the current state as an argument and returns a new state value. This is useful when the new state value depends on the current state value.

3. How can Component A access state from Component B?

        - Component A can access state from Component B by passing the state from Component B to Component A as a prop. Component A can then access the state from Component B by accessing the prop. If Component B needs to update the state, it can pass a function to Component A as a prop. Component A can then call the function with the new state value, which will cause Component B to re-render with the new state value. If Component B needs to update the state based on the current state value, it can pass a function to Component A as a prop. Component A can then call the function with a function that takes the current state as an argument and returns a new state value. This is useful when the new state value depends on the current state value.

### Bookmark and Review

- [Passing Props to a Component](https://react.dev/learn/passing-props-to-a-component)
- [Rendering Lists](https://react.dev/learn/rendering-lists)
- [State as Snapshot](https://react.dev/learn/state-as-a-snapshot)
- [useState Hook](https://react.dev/reference/react/useState)

### Reflection

- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-27/)

1. What are your learning goals after reading and reviewing the class README?

    - [ ] Goal 1: I want to understand how to use React to build a UI. After gaining a decent foundation with React, I would like to update the UI in past projects that I have built.

#### Things I Want to Know More About

1. Hooks in general.

![GIF](https://media.giphy.com/media/YDL8WPvV0Ob3ZmtAmF/giphy.gif)
