### Functional Programming Concepts


#### What is functional programming?
- it is a programming paradigm that avoids changing state and mutable data, and treats computation as the evaluation of mathematical functions

#### What is a pure function and how do we know if something is a pure function?
- a pure function is essentially deterministic, meaning that it will always return the same result if given the same arguments
- a pure function does not cause any observable side effects, meaning it doesn't modify a global object, nor does it modify any parameters passed by reference

#### What are the benefits of a pure function?
- pure functions are easier to test

#### What is immutability?
- immutability usually refers to data
- data is immutable if its state cannot change after its created

#### What is Referential transparency?
- referential transparency is the property of always yielding the same result for the same input



### Node JS Tutorial for Beginners #6 - Modules and require()


#### What is a module?
- a module is essentially just a javascript file

#### What does the word ‘require’ do?
- require creates a reference to a file outside the working module

#### How do we bring another module into the file the we are working in?
- we can use the word 'require' to reference a file we want to utilize from outside the working file


#### What do we have to do to make a module available?
- we also need to write an export statement on the outside file and name the working file to create an info channel



[Back to Table of Contents](https://ryanhoffman4.github.io/reading-notes/)