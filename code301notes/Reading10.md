### Understanding the JavaScript Call Stack

#### What is a ‘call’?
- a call is a function call
- it is an instruction package that is placed on a stack to be resolved with a certain priority amongst other calls

#### How many ‘calls’ can happen at once?
- functions are executed one at a time

#### What does LIFO mean?
- Last In, First Out

#### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
- function_3 // this is called last, but it resolves first to supply function 2 with a value
- function_2(function_3()) // this is called second
- function_1(function_2()) // this called first

#### What causes a Stack Overflow?
- a stack overflow is caused by calling a recursive function that never resolves
- all recursive functions need a base case and need to terminate
- this is similar to a while loop that never resolves


### JavaScript error messages

#### What is a ‘reference error’?
- using an undefined variable

#### What is a ‘syntax error’?
- literally using incorrect syntax
- a good example would be mishandling a data type

#### What is a ‘range error’?
- it is basically a common sense error
- a good example would be trying to decrease the length of an empty array

#### What is a ‘type error’?
- this occurs when data types are told to perform in ways they cannot, such as accessing an undefined variable

#### What is a breakpoint?
- a breakpoint is a point used to arbitrarily pause the code at advantageous places, commonly for debugging
- when a program has breakpoints, a developer can then look at the state of the program before it continues past that line of code

#### What does the word ‘debugger’ do in your code?
- debugger is a keyword that basically serves as a breakpoint
- it also informs different states of variables and such


[Back to Table of Contents](https://ryanhoffman4.github.io/reading-notes/)