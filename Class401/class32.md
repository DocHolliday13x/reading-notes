# Class 32 Reading: Context API - Behaviors

## Resources

- [Scaling Up with Reducer and Context](https://react.dev/learn/scaling-up-with-reducer-and-context)

## Topic 1

1. How do `useReducer()` and `useContext()` work together to simplify state management in a React application?

    - 'useReducer()' is used to update state based on a given action. `useReducer()` is a hook that provides an alternative to the useState hook for managing complex state logic. It takes in a reducer function and an initial state, and returns the current state and a dispatch function. The reducer function receives the current state and an action, and returns the new state based on the action type. By encapsulating state updates in a single reducer function, useReducer promotes predictable and centralized state management
    - 'useContext()' is another hook that allows you to access the value of a context provided by a Context.Provider component. Context provides a way to share data between components without having to pass props through intermediate components. By using useContext, you can consume the value of a context directly within a component, eliminating the need for prop drilling.
    - When used together, `useReducer()` and `useContext()` can greatly simplify state management in a React application. By defining a context and providing it through a `Context.Provider` component, you can make the state accessible to any component that needs it. The `useReducer()` hook can then be used within the consuming components to handle state updates using the dispatched actions. This combination enables you to have a central state store that can be accessed and modified by multiple components without the need for prop passing or lifting state up. It promotes a more modular and scalable approach to managing state, making your code easier to read, reason about, and maintain.
    - Overall, by leveraging the power of `useReducer()` and `useContext()` together, you can simplify your state management in a React application, improve code organization, and reduce the complexity associated with passing state through multiple layers of components.

### Things I Want to Know More About

1. How to use `useReducer()` and `useContext()` to simplify state management in a React application.

![GIF](https://media.giphy.com/media/gEvab1ilmJjA82FaSV/giphy.gif)
