# Class 2 Reading

- The main difference between the ```PUT``` and ```PATCH``` method is that the ```PUT``` method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.
Provide links to 3 services or tools that allow you to “mock” an API for development like json-server

- [Postman](https://www.postman.com/)
- [Stoplight](https://stoplight.io/)
- [Mockable](https://www.mockable.io/)

Compare and contrast Swagger and APIDoc.js
- [Swagger](https://swagger.io/)
    - Swagger can design and document your APIs at scale
    - Used by many large companies
    - cloud based
    - In depth documentation
- [APIDoc.js](https://apidocjs.com/)
    - apiDoc creates a documentation from API annotations in your source code.
    - Default template
    - Without any parameter, apiDoc generate a documentation from all ```.cs``` ```.dart``` ```.erl``` ```.go``` ```.java``` ```.js``` ```.php``` ```.py``` ```.rb``` ```.ts``` files in current dir (incl. subdirs) and writes the output to ```./doc/.```
- HTTP Status UN-Successful Codes:
    - Client error responses (400–499)
    - Server error responses (500–599)

- ```SOAP``` stands for Simple Object Access Protocol
    -  a standards-based web services access protocol 
    - Originally developed by Microsoft
    - rigid set of messaging patterns
    - The rules in ```SOAP``` are important because we can't achieve any level of standardization without them.
    - Language, platform, and transport independent (REST requires use of HTTP)
    - Works well in distributed enterprise environments (REST assumes direct point-to-point communication)
    - Standardized
    - Provides significant pre-build extensibility in the form of the WS* standards
    - Built-in error handling
    - Automation when used with certain language products
- ```REST``` stands for REpresentational State Transfer
    - seeks to fix the problems with SOAP and provide a simpler method of accessing web services.
    - does not require processing and is naturally more flexible.
    - lighter-weight alternative.
    - No expensive tools require to interact with the web service
    Smaller learning curve
    - Efficient (```SOAP``` uses ```XML``` for all messages, ```REST``` can use smaller message formats)
    - Fast (no extensive processing required)
    - Closer to other web technologies in design philosophy

Document the following Vocabulary Terms

- Web Server: A web server is a computer that runs websites. It's a computer program that distributes web pages as they are requisitioned. The basic objective of the web server is to store, process and deliver web pages to the users. This intercommunication is done using Hypertext Transfer Protocol (HTTP).
- Express: Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.
- Routing: a way of organizing and managing application states.
- WRRC: Web request/response cycle.

> **Which 3 things had you heard about previously and now have better clarity on?** ```SOAP```, ```REsT```, and Mock JSON Servers
> **Which 3 things are you hoping to learn more about in the upcoming lecture/demo?** Mock JSON Servers
> **What are you most excited about trying to implement or see how it works?** Swagger

- **Sources**
    - https://apidocjs.com/ 
    - https://swagger.io/solutions/api-design/ 
    - 