# Lists
- ordered lists
- unordered lists
- definition lists
- Nested lists are lists inside lists
# Boxes
- use pixels to specify the size of a box
- overflow tells the browser what to do if the content inside a box is larger than the box itself
- can be hidden or scroll
- the three properties of a box are border, margin, and padding
- padding and margin are helpful for adding space between items on the page
- border- width is used to control the width of the border
- border style can be made solid, dotted, dashed double, groove, ridge, inset, outset, or hidden/none.
- you can change the styles of each side using border-top-style etc
- border color can also be specified
- padding is how much space is around the content
- margin controls the gap between boxes
- to center a box on a page set the left and right margins to auto
- requires a text- align property
- the display property can turn an inline property into a block level element
- can use inline, block, inline-block, or none
- boxes can be hidden or visible
- border-image applies an image to the border of any box
- box-shadow adds a shadow 
- can be horizontal offset, vertical offset, blur distance =, or spread of shadow
- border radius can create rounded edges
- px can be used to create more specific complex shapes
# Arrays
- Arrays store more than one value
- arrays can be given a name like other variables
- the technique for creating an array is known as an array literal
- array values can be changed
# Decisions and loops
- If... Else statements check a condition and executes first block if true, second block if false
- switch statements starts with the switch value variable 
- each case indicates a possible value for the variable and the code that should run
- if you use a data type JS did not expect it tries to make sense of the statement rather than reporting an error
- truthy and falsy values are treated as if they are true or false 
- the presence of an object or array can be considered truthy, it is often used to check for the existence of an element
- unary operators return a result with just one operand
### Short circuit values
- logical operators are processed left to right and stop as soon as they have a result
- they return the value that stopped the processing 
- logical operators will not always return true or false
- as soon as a truthy value is found remaining options are not checked
### Loops 
- loops check a condition
- if it returns true a code block will run
- it will repeat until it returns false
- for will execute a certain number of times
- while will continue as long as the condition is true
- do...while will always ru the statements at least once even if condition is false
