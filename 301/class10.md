# In memory storage

- What is a ‘call'?
    - a function invocation 
- How many ‘calls' can happen at once?
    - One 
- What does LIFO mean?
    - Last in first out
- Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
    - ``` function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction(); ```
- What causes a Stack Overflow?
    - occurs when there is a function that calls itself without an exit point.

- What is a ‘refrence error'?
    - when you try to use a variable that is not yet declared
- What is a ‘syntax error'?
    - when you have something that cannot be parsed in terms of syntax
- What is a ‘range error'?
    - when you try to manipulate an object with some kind of length and give it an invalid length
- What is a ‘type error'?
    - when the types (number, string and so on) you are trying to use or access are incompatible
- What is a breakpoint?
    - a point in the program where the code will stop executing
- What does the word ‘debugger' do in your code?
    - allow the user to view the execution state and data of another application as it is running