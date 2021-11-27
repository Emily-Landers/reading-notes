# Tables
#### A table represents information in a grid format.
- The ```<table>``` element is used to add tables to a webpage
- A table is drawn out row by row. Each row is created with the ```<tr>``` element.
- Inside each row there are a number of cells represented by the <td> element (or ```<th>``` if it is a header).
- You can make cells of a table span more than one row or column using the rowspan and colspan attributes.
- For long tables you can split the table into a ```<thead>```, ```<tbody>```, and ```<tfoot>```.

# Functions, Methods, and Objects
#### Functions
- You must declare a function before you can call (or execute) it
- functions can store instructions for a specific task
- call the function when you want the task executed 
- the JS interpreter will run through a script before executing each statement, so a function can be called before its been declared
- some functions need parameters to perform a task 
- parameters are stored inside ```()``` when the function is called
- specify the values required when calling these functions
- parameters are words that act like variables 
- arguments are values being passed into the code
- some functions return a value
- functions can return more than one value using an array
#### Objects
- objects group together a set of variables and functions to create a model of something you would recognize from the real world. 
- in objects variables become known as properties
- functions inside objects become known as methods
- object literal notation is the easiest and most popular way to create objects
- separate each key from its value using a colon 
- separate each property and method with a comma 
- use dot notation to access properties or methods of an object using dot notation 
- you can also access properties using square brackets
- the new keyword and the object constructor create a blank object which you can then add properties and methods to 
- to update the value of properties use dot notation or square brackets 
- they work on objects created using literal or constructor notation 
- to delete a property use the delete keyword
- object constructors can use a function as a template for creating objects 
- first create the template with the objects properties and methods
- you can create instances of the object using the constructor function 
- the new keyword followed by a call to the function creates a new object 
- the properties of each object are given as arguments to the function 
- arrays are a special type of object that hold a related set of key/ value pairs, but the key for each value is its index number
- arrays and objects can be combined to create complex data structures. 
- arrays can store a series of objects and remember their order. 
- objects can hold arrays as values of their properties 
#### Built in objects
- the three sets of built in objects each offer a different range of tools that help you write scripts for web pages 
- the DOM creates a model of the current webpage 
- the browser object model creates a model of the browser tab or window 
- in order to work with dates you create an instance of the date object, you can then specify the time and date you want it to represent
- example ``` var today = new Date();```
- JavaScript has several built in objects such as string, number, math, and date