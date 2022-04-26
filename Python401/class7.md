# Ten Thousand 2

## Python Scope

- The concept of scope rules how variables and names are looked up in your code
- The letters in the acronym LEGB stand for Local, Enclosing, Global, and Built-in scopes
- Global scope: The names that you define in this scope are available to all your code.
- Local scope: The names that you define in this scope are only available or visible to the code within the scope.
- your ability to access a given name will depend on where you’ve defined that name.
- variables in Python come into existence when you first assign them a value.
- Python uses the location of the name assignment or definition to associate it with a particular scope.
- The local scope or function scope is a Python scope created at function calls.
- You can inspect the names and parameters of a function using `.__code__`
- Enclosing or nonlocal scope is observed when you nest functions inside other functions.
- The built-in scope is a special Python scope that’s implemented as a standard library module named builtins in Python 3.x. All of Python’s built-in objects live in this module.
- Python provides two keywords that allow you to modify the content of `global` and `nonlocal` names.
- It’s worth noting that you can use global from inside any function or nested function and the names listed will always be mapped to names in the global Python scope.
- Use a coherent strategy to access, modify, or update names across all your Python code
- Make good use of global and local names across your programs to improve code maintainability
- Take advantage of Python scope to avoid or minimize bugs related to name collision

## References 

- https://realpython.com/python-scope-legb-rule/ 
