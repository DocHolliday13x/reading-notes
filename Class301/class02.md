# Class 2 Reading Assignment: State and Props

## Resources

* [React Lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)
* [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)
* [React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)
* [React Docs - Handling Events](https://reactjs.org/docs/handling-events.html)
* [React Tutorial Through Dev Tools](https://reactjs.org/tutorial/tutorial.html)
* [React Bootstrap Documentation](https://react-bootstrap.github.io/)
* [Bootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)
* [Bootstrap Shuffle](https://bootstrapshuffle.com/classes)
* [Netlify](https://www.netlify.com/)

## Topic Statement

This material is important to help me understand how REACT works by comparing it to material that I am already familiar with, such as comparing props components to arguments passed to functions. This material also has some charts to give me a visual representation of the REACT orders of operation process from start to finish. This is also nice to have to refer to when I get stuck in the creation process.

## Reading

1. Based of the diagram, what happens first, the 'render' or the 'componentDidMount'?
   * Render
2. What is the very first thing to happen in the lifecycle of React?
   * Mounting - when an instance of a component is being created and inserted into the DOM
3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates.
   * Constructor, Render, componentDidMount, componentWillUnmount, React Updates
4. What does componentDidMount do?
   * This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount(). setState() can be called here, but it should be used sparingly, because it will cause a rerender, which can lead to perfomance issues. (React: Component Lifecycle Events)

## Videos

1. What types of things can you pass in the props?
   * Like arguments to a function, but with components. Like storing titles and subtitles.

2. What is the big difference between props and state?
   * props you pass into a component and handled outside the component. state is handled inside of that component. When you change the state, it rerenders that section of your application.

3. When do we re-render our application?
   * When you change the state, it rerenders that section of your application. If you want to change something in your application, it needs to be stored in the state.

4. What are some examples of things that we could store in state?
   * We need state to store things we will be rerendering and updating the application based on something that the user has done.

### Things I Want to Know More About

* 1. 
* 2. 
* 3. 
