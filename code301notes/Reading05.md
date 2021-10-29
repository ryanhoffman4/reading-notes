#### React Docs - Thinking in React

##### What is the single responsibility principle and how does it apply to components?
- one component should only do one thing!

##### What does it mean to build a ‘static’ version of your application?
- a static application means there is no interaction between the application and the user

##### Once you have a static application, what do you need to add?
- building a static application mostly requires the use of props, so it is now time to fill out component states

##### What are the three questions you can ask to determine if something is state?
- Is it passed in from a parent via props?
- Does it remain unchanged over time?
- Can you compute it based on any other state or props in your component?
- If the answer to any of these questions is 'yes', then it probably isn't state.

##### How can you identify where state needs to live?
- identify each component that uses the state
- find a component that all others depend on
- that component or one above it should hold the state
- if no components are sensible, create a component solely to own that state



#### Higher-Order Functions

##### What is a “higher-order function”?
- higher order functions are functions that are abstractions upon abstractions, or functions that implement several other functions at a time

##### Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
- the greater than function takes a built-in value, m in this case, and compares its magnitude against the argument, n.

##### Explain how either map or reduce operates, with regards to higher-order functions.
- map takes an array and callback function as arguments
- then, it constructs a new local array
- then, it iterates over the elements of the array passed as its argument
- as it does this, its feeds the elements through the callback function and pushes them to the local array
- then, it returns the local array

[Back to Table of Contents](https://ryanhoffman4.github.io/reading-notes/)