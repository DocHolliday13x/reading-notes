# Class 03 Reading: Passing Functions as Props

## Resources

* [Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)
* [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)
* [How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)
* [React Tutorial - Declaring a Winner](https://reactjs.org/tutorial/tutorial.html)
* [React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)

### Reading Statement

Why this topic matters as it relates to what I am studying in this module?

### React Docs - Lists and Keys

1. What does .map() return?

.map() returns a new array

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

By using .map()

3. Each list item needs a unique ____.

Element

4. What is the purpose of a key?

A key is a special string attribute included when creating lists of elments. They help REACT identify which items have changed, are added, or are removed.

### The Spread Operator

1. What is the spread operator?

A useful and quick syntax for adding itmes to arrays, combining objects or arrays, and spreading an array out into a function's arguments.

2. List 4 things that the spread operator can do.

   1. Add items to arrays
   2. Combine objects/arrays
   3. Copying an array
   4. Adding to state in REACT

3. Give an example of using the spread operator to combine two arrays.

[...["😋😛😜🤪😝"]] // Array [ "😋😛😜🤪😝" ]
[..."🙂🙃😉😊😇🥰😍🤩!"] // Array(9) [ "🙂", "🙃", "😉", "😊", "😇", "🥰", "😍", "🤩", "!" ]

const hello = {hello: "😋😛😜🤪😝"}
const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}

const helloWorld = {...hello,...world}
console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" }

4. Give an example of using the spread operator to add a new item to an array.

const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

5. Give an example of using the spread operator to combine two objects into one.

const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂

### How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?

2. In your own words, what does the increment function do?



3. How can you pass a method from a parent component into a child component?



4. How does the child component invoke a method that was passed to it from a parent 
component?



#### Things I Would Like to Know More About

1. 
2. 
3. 