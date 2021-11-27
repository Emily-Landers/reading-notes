# Reading 6
#### Functions, Methods, and Objects
- To create a function give it a name and then write the statements needed to achieve its tasks inside the curly braces (known as a function declaration)
- ```function() sayHello {
    document.write('hello')
}```
- functions need to be called in order to execute ```sayHello()```
- place paramaters of the function in the parenthesis 
- specify values or arguments of parameters
- some functions return information like calculations to the code that called them
- functions can return more than one value using an array
- literal notation is the easiest and most popular way to create objects
- the object is the curly braces, and their contents
- separate each key from its value using colon 
- separate each property and method with a comma 
- you can access the properties or methods of an object using dot notation or square brackets
- if you add 'new'to an object constructor it will create a blank object that you can add properties to 
- each statement that adds a property should end in a semicolon 
- ```var hotel = new Object ();```
```hotel.name = 'Quay';```
```hotel.rooms = 40;```
```hotel.booked = 25;```
```hotel.checkAvailability = function {```
``` return this.rooms - this.booked;```
```};```
- to update the value of properties use dot notation or square brackets 
- to delete a property use the delete keyword
- object constructors can use a function as a template for creating objects  
- first create the template with the objects properties and methods
- you create instances of the object using the constructor function 
- the new keyword followed by a call to the function creates a new object 
- the properties of each object are given as arguments to the function
- arrays are objects
- arrays and objects can be combined to create complex data structures
- objects can hold arrays
#### Document Object Model
- Methods that find elements in the DOM tree are called DOM queries
- use a variable to store this query if you plan on using an element more than once
- storing elements in variables is really storing the location of the elements
- the properties and methods of the element node work on the variable
- getElementById and querySelector can both search an entire document and return individual elements
- item will return an individual node from the nodelist
- there are two ways to select an element from a node list the item method and array syntax
- array syntax is preferred ove the item method because it is faster
- you can loop through a nodelist and apply the same statements to each
- there are two different approaches to adding and removing content from a DOM tree
- inner HTML and DOM manipulation
- DOM manipulation easily targets individual nodes in the DOM tree
- inner HTML is better for updating entire fragments
- once you have an element node you can use other properties and methods on that element node to access and change its attributes
 