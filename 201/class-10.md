# Error Handling and Debugging
- The JavaScript interpreter processes one line at a time
- when a statement needs data from a function it stacks the new function on top of the current task
- finding error in your code becomes easier when you understand execuion contexts and stacks
- debugging involves a process of deduction
the console can help narrow down the area in which the error is located so you can try and fix the exact error
- JavaScript has 7 different types of errors that each create their own error object
- error objects can tell you a line number end error description
- use the try, catch, finally statements to give your users helpful feedback 