# Class 31 Reading: Context API

## Resources

- [Choose the State Structure](https://react.dev/learn/choosing-the-state-structure)
- [Passing State Deeply with Context](https://react.dev/learn/passing-data-deeply-with-context)

## Choosing the State Structure

1. Summarize the five principles for structuring state.

    - **Principle 1**: *Group Related State* - If you always update two or more values together, they probably belong to the same piece of state.
    - **Principle 2**: *Avoid contradiction in State* - When the state is structured in a way that several pieces of state may contradict and “disagree” with each other, you leave room for mistakes. Try to avoid this.
    - **Principle 3**: *Avoid Redundant State* - If you can calculate a value from other values in state, don’t store it. Instead, calculate it on the fly.
    - **Principle 4**: *Avoid Duplication in State* - When the same data is duplicated between multiple state variables, or within nested objects, it is difficult to keep them in sync. Reduce duplication when you can.
    - **Principle 5**: *Avoid Deeply Nested State* - Deeply heirarchical state is difficult to update. Try to keep your state flat.

## Passing State Deeply with Context

1. What problems do Contexts aim to solve?

    - Contexts aim to solve the problem of passing props through multiple components. This can be tedious and time consuming. Context lets a parent component provide data to the entire tree below it.

2. What is one technique to try before `useContext`?

    - One technique to try before `useContext` is to pass props through multiple components. This is the default way of passing props.

3. What hook complements `useContext` for complex applications?

    - The hook that complements `useContext` for complex applications is `useReducer`. This hook is used for state management. It is an alternative to `useState`.

### Bookmark and Review

- [Sharing State Between Components](https://react.dev/learn/sharing-state-between-components)
- [Preserving and Resting State](https://react.dev/learn/preserving-and-resetting-state)

#### Things I Want to Know More About

1. I'm going to leave the three steps to using context below for later reference:

    - **Step 1**: *Create* a Context - `const MyContext = React.createContext(defaultValue);`
    - **Step 2**: *Provide* a Context - `<MyContext.Provider value={/* some value */}>`
    - **Step 3**: *Consume* a Context - `const value = useContext(MyContext);`

2. Use Cases for Context:

    - **Theme** - A theme is a good use case for context. You can use context to pass the theme to components that need it.
    - **Localization** - Localization is another good use case for context. You can use context to pass the current locale to components that need it.
    - **Dynamic Context** - You can use context to pass dynamic data to components that need it. This is a good use case for context.
    - **Current Account** - You can use context to pass the currently logged-in user to components that need it. This is a good use case for context.
    - **Routing** - You can use context to pass the current route to components that need it. This is a good use case for context.
    - **Managing State** - You can use context to pass state to components that need it. This is a good use case for context.

![GIF](https://media.giphy.com/media/aSGx1KcssI1OYXTRKk/giphy.gif)
