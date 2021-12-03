# Putting it all together

- The single responsibility principle says that a component should only do one thing
- to build a ‘static’ version of your application means to creat a version that is not interactive
- Once you have a static application you need to add in state
- To determine if something is a state ask three questions:

    > -  Is it passed in from a parent via props? If so, it probably isn’t state.
    > - Does it remain unchanged over time? If so, it probably isn’t state.
    > - Can you compute it based on any other state or props in your component? If so, it isnt a state.

- The state needs to live in the common owner component.

- A high order function is a function that operates on other functions
Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing? returning a value greater than the argument
- The map method transforms an array by applying a function to all of its elements and building a new array from the returned values. 