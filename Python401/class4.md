# Reading Four

## Thinking Recursively

- Recursion is basically like dividing up the work to be done into more efficient pieces
- When dealing with recursive functions, keep in mind that each recursive call has its own execution context
- A data structure is recursive if it can be deﬁned in terms of a smaller version of itself.
- Recursion can also be seen as self-referential function composition. We apply a function to an argument, then pass that result on as an argument to a second application of the same function, and so on.
- List is not the only recursive data structure. 

## Classes and Objects

- Objects are an encapsulation of variables and functions into a single entity. Objects get their variables and functions from classes. Classes are essentially a template to create your objects.
- You can create multiple different objects that are of the same class(have the same variables and functions defined). However, each object contains independent copies of the variables defined in the class. 
- The __init__() function, is a special function that is called when the class is being initiated. It's used for assigning values in a class.

## Testing with Pytest

- objects available to all of your tests are often called "fixtures"
- In pytest, you define fixtures using a combination of the pytest.fixture decorator, along with a function definition. 
- You can decide how often a fixture is run
- there's a package called pytest-cov on PyPI to find out the coverage your tests are getting
- you can invoke pytest with the ```--cov``` option

### Resources

- https://realpython.com/python-thinking-recursively/ 
- https://www.learnpython.org/en/Classes_and_Objects
- https://www.linuxjournal.com/content/python-testing-pytest-fixtures-and-coverage 