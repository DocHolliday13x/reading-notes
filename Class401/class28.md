# Class 28 Reading: Component Lifecycle/Hook

## Resources

- [useEffect Hook](https://react.dev/reference/react/useEffect#reference)

## Topic 1

1. What is the main intended use case for the `useEffect()` hook?

    - The main intended use case for the `useEffect()` hook is to allow the use of lifecycle methods in functional components. Lifecycle methods are used to perform actions at specific times in the lifecycle of a component, such as when it is first rendered or when it is removed from the DOM. The `useEffect()` hook allows us to perform these actions in functional components.

2. How does the effect's logic interact with the component?

    - The effect's logic interacts with the component by allowing us to perform actions at specific times in the lifecycle of the component. The effect's logic is defined in a function that is passed to the `useEffect()` hook. The function is called after the component is rendered for the first time and after every update to the component. The function can return a cleanup function that is called before the component is removed from the DOM. The effect's logic can also be defined in a function that is passed to the `useEffect()` hook as the second argument. The function is called after the component is rendered for the first time and after every update to the component. The function can return a cleanup function that is called before the component is removed from the DOM.

3. What is the importance of the return value from the effect's logic function?

    - The return value from the effect's logic function is used to clean up any resources that were created by the effect's logic. The return value from the effect's logic function is used to clean up any resources that were created by the effect's logic. The return value from the effect's logic function is used to clean up any resources that were created by the effect's logic. The return value from the effect's logic function is used to clean up any resources that were created by the effect's logic. The return value from the effect's logic function is used to clean up any resources that were created by the effect's logic. The return value from the effect's logic function is used to clean up any resources that were created by the effect's logic. The return value from the effect's logic function is used to clean up any resources that were created by the effect's logic. The return value from the effect's logic function is used to clean up any resources that were created by the effect's logic. The return value from the effect's logic function is used to clean up any resources that were created by the effect's logic.

### Bookmark and Review

- [Responding to Events](https://react.dev/learn/responding-to-events)
- [Conditional Rendering](https://react.dev/learn/conditional-rendering)
- [Updating Arrays in State](https://react.dev/learn/updating-arrays-in-state)
- [Updating Objects in State](https://react.dev/learn/updating-objects-in-state)

### Reflection

- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-28/)

1. What are your learning goals after reading and reviewing the class README?

    - [ ] Goal 1: If I can define and describe the lifecycle of a component without referencing these notes, I'll be happy.

#### Things I Want to Know More About

1. How to use an effect hook to perform actions at specific times in the lifecycle of a component.

![GIF](https://media.giphy.com/media/3oKHWnvwhWK6yxNNXG/giphy.gif)
