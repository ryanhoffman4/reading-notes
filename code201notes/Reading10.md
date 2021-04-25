
#### From the Duckett JS book:

##### JavaScript book, Ch. 10, “Error Handling & Debugging”

- javascript uses the stack format to execute code
- global scope starts first, then functions change the scope and are added to the stack
- functions on the top of the stack resolve first, then the scope returns lower on the stack back to global scope
- javascript uses hoisting
- hoisting is a procedure of scanning the entire code once, then rescanning the code for execution on the stack
- hoisting allows function calls to be written before function definitions
- not all languages allow this; many languages only read top down 

- the browser does some JS error handling for the programmer
- the console keeps track of syntax error, potential bugs, exceptions thrown, etc.
- bugs and errors are technically different
- often times, solving one issue will get rid of many errors
- it helps to read code holistically and interpret many line references as one potential problem
- other tips include commenting out segments of code and only running code in peices to hone in on the issue
- a more efficient way of using this method would be to use breakpoints
- breakpoints stop code execution when encountered




[Back to Table of Contents](https://ryanhoffman4.github.io/reading-notes/)