# FUNCTIONAL PROGRAMMING

- What is functional programming?
    - a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data 
- What is a pure function and how do we know if something is a pure function?
    - pure functions are the simplest reusable building blocks of code in a program. You know if something is a pure function if it returns the same result, and if given the same arguments It does not cause any observable side effects
- What are the benefits of a pure function?
    - The code is easier to test, and can be tested in different contexts
- What is immutability?
    - Unable to change
- What is Referential transparency?
    - a function call can be replaced by its value or another referentially transparent call with the same result.

- What is a module?
    - a file containing related code
- What does the word ‘require’ do?
    - it loads and caches JavaScript modules
- How do we bring another module into the file the we are working in?
    - use the require function
- What do we have to do to make a module available?
    - export them