Readings: Authentication

- Explain what a “Singleton” is (in Computer Science terms)
    - a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system.
- Explain how the Singleton pattern can be used with Node modules, specifically with classes

    - We need to use a singleton when we want to make sure there is only one object instantiated. Therefore, instead of creating a new object we need to ensure the constructor is called only once and then we reuse the instance.
    - We can achieve this by refactoring our class to have a hidden (private)constructor and a public ```getInstance``` method that returns an instance of the class

- If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

    - Install Node and NPM.
    - Create server.js
    - Run the server via node server.js
    - set up middleware to be “global” middleware so that it will be called for every incoming request.

Document the following Vocabulary Terms

- Router Middleware: functions that have access to the request object ```(req)```, the response object ```(res)```, and the ```next``` middleware function in the application's request-response cycle.
- Dynamic Module Loading: Dynamic loading is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory.
- Singleton Pattern: limits the number of instances of a particular object to just one. This single instance is called the singleton. Singletons are useful in situations where system-wide actions need to be coordinated from a single central place. An example is a database connection pool.
- CRUD -> REST Method Matches: create -> POST , read -> GET , update -> PUT and PATCH and delete -> delete.
- Mock Testing: an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. In mock testing, the dependencies are replaced with objects that simulate the behavior of the real ones.

- Which 3 things had you heard about previously and now have better clarity on?
    - Singletons, CRUD, and Middleware.
- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
    - Singletons, Middleware, and Mock testing
- What are you most excited about trying to implement or see how it works?
    - Mock testing

- **Sources**
    - https://en.wikipedia.org/wiki/Singleton_pattern#:~:text=In%20software%20engineering%2C%20the%20singleton,coordinate%20actions%20across%20the%20system. 
    - https://medium.com/swlh/node-js-and-singleton-pattern-7b08d11c726a 
    - https://en.wikipedia.org/wiki/Dynamic_loading 
    