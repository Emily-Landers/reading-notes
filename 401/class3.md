# Review, Research, and Discussion

- You'd want to change the request with custom middleware to change the data type, to add a time or date to the request, and to include user identification.

- True or false: The route handler is middleware?
    - FALSE

- In what ways can a middleware function end the process and send data to the browser?
    - the ```next()``` function 

- At what point in the request lifecycle can you “inject” middleware?
    - When the request reaches the server 
- What can cause express to error with “Request headers sent twice, cannot start a second response”
    - When we are in the finished state, but a function tried to set a status code.
Document the following Vocabulary Terms
- Middleware: software that provides common services and capabilities to applications outside of what’s offered by the operating system. Data management, application services, messaging, authentication, and API management are all commonly handled by middleware.
- Request Object: the main entry point for an application to issue a request to the Library
- Response Object: a way to send output to the user from the server.
- Application Middleware: software that provides services beyond those provided by the operating system to enable the various components of a distributed system to communicate and manage data. 
- Routing Middleware: a route which is using to log requests to the console or validate specific parameters If It is for parameters .
- Test Driven Development: a programming practice which involves developing tests for every small functionality of an application.
- Behavioral Testing: testing of the external behavior of the program, also known as black box testing. It is usually a functional testing.

- Which 3 things had you heard about previously and now have better clarity on?
    - The ```next()``` function, middleware, and route handlers
- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
    - Routing middleware, application middleware, and Test driven development
- What are you most excited about trying to implement or see how it works?
    - Routing middleware