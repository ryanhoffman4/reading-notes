
#### Forms
- a "controlled component" is a form component that is being handled by React, instead of by the actual form element
- different event handlers can be useful, and I'd say there is a place for both an event listener that listens on submit, as well as one that listens and gives feedback to an input field without sumbission
- I'd only store data upon submission, but I'd give reminders about valid phone numbers and things as they are updated in real time
- to scope an input field, use the event.target concept
#### Ternary Operators
- ternary operators provide a drier, shorthanded way of writing if else statements

- format:
- condition ? value if true : value if false
- the ? and : together in one line accept three arguments and act as one operator
- for example:
-  if(x===y){
-    console.log(true);
-  } else {
-    console.log(false);
-  }

- this can be rewritten as x===y ? console.log(true) : console.log(false)


##### Things I want to know more about
- I am curious to learn how many more "shorthand operators" there are for writing drier, single lines of code instead of having to write out common code constructs
- So far, I have learned the ternary operator for branch statements, arrow functions for standard function calls, and "for each" statements instead of writing out the entire for loop structure




[Back to Table of Contents](https://ryanhoffman4.github.io/reading-notes/)