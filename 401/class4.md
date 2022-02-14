# Data Modeling

- Name 3 advantages to Test Driven Development
    - Requires more code planning
    - Quicker feedback
    - Reduces time spent on rework.
    - Less time spent debugging.
    - ability to identify the errors and problems quickly.
- In what case would you need to use ```beforeEach()``` or ```afterEach()``` in a test suite?
    - We need the ```afterEach()``` method to rest the database after running the test, while the ```beforeEach()``` is called before the test runs.
- What is one downside of Test Driven Development
    - Not running tests frequently enough, writing tests that are too large, writing too many tests at once.
- What's the primary difference between ES6 Classes and Constructor/Prototype Classes?
    - a class defines a type which can be instantiated at runtime, whereas a prototype is itself an object instance.
- Why REST?
    - One of the key advantages of REST APIs is that they provide a great deal of flexibility. Data is not tied to resources or methods, so REST can handle multiple types of calls, return different data formats and even change structurally with the correct implementation of hypermedia.

Document the following Vocabulary Terms

- functional programming: the process of building software by composing pure functions, avoiding shared state, mutable data, and side-effects.
- object-oriented programming (OOP): a computer programming model that organizes software design around data, or objects, rather than functions and logic.
- class: a template for creating objects. They encapsulate data with code to work on that data.
- super: used to access and call functions on an object's parent. 
- this: keyword that refers to the object it belongs to.
- Test Driven Development (TDD): a programming practice that involves developing tests for every bit of functionality in an application.
- Jest: Javascript testing framework
- Continuous Integration (CI):a set of practices that drive development teams to implement small changes as a mechanism to integrate and validate changes.
- REST: stands for Representational State Transfer, it is an architectural pattern that works with plain text, XML, HTML and JSON.
- Data Model: an abstract model that organizes elements of data and standardizes how they relate to one another and to the properties of real-world entities.

- Which 3 things had you heard about previously and now have better clarity on?
    - Test driven development, Data Modeling, ad ReST
- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
    - Continuous Integration, Test Driven Development, and Jest
- What are you most excited about trying to implement or see how it works?
    - TDD and jest

- **Sources**
    - https://www.mulesoft.com/resources/api/restful-api#:~:text=One%20of%20the%20key%20advantages,the%20correct%20implementation%20of%20hypermedia
    - https://smartbear.com/blog/soap-vs-rest-whats-the-difference/ 
    - https://expressjs.com/en/guide/routing.html 
    - https://searchapparchitecture.techtarget.com/definition/object-oriented-programming-OOP#:~:text=Object%2Doriented%20programming%20(OOP)%20is%20a%20computer%20programming%20model,rather%20than%20functions%20and%20logic.&text=Once%20an%20object%20is%20known,sequences%20that%20can%20manipulate%20it. 
    - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/super 
    - 