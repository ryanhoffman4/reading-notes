#### React Lifecycle


##### According to the diagram:
- render happens before componentDidMount

##### What is the very first thing to happen in the lifecycle of React?
- the construction of a component is the first thing to happen

##### The following items are in order of happening:
- constructor
- render
- React Updates (if applicable)
- componentDidMount
- componentWillUnmount

##### What does componentDidMount do?
- it allows the cleaning up of the DOM and network requests



#### React State vs. Props


##### What tyes of things can you pass in the props?
- counters
- displays, things like titles and subtitles

##### What is the big difference between props and state?
- props are passed into a component and handled outside a component
- state exists inside a component

##### When do we rerender our application?
- changing a state always rerenders the application

##### What are some examples of things we could store in a state?
- state most commonly stores things that are added/modified/updated by a user


##### Things I want to know more about:
- why does React update in the middle of its cycle?


[Back to Table of Contents](https://ryanhoffman4.github.io/reading-notes/)