# Passing Functions as Props

- .map() returns an array based on what has been input. 
- You use curly braces for JSX
- Each list item needs a unique key to be easily identified

- the spread operator is three dots used to expand an array
- the spread operator can separate an array into separate arguments, copy arrays, add items to a list, and convert a node list into an array.
- here is an example of using the spread operator to combine two arrays:
    >
    >```[...["ððððĪŠð"]] // Array [ "ððððĪŠð" ]
    >[..."ððððððĨ°ððĪĐ!"] // Array(9) [ "ð", "ð", "ð", "ð", "ð", "ðĨ°", "ð"     "ðĪĐ", "!" ]

    >const hello = {hello: "ððððĪŠð"}
    >const world = {world: "ððððððĨ°ððĪĐ!"}

    >const helloWorld = {...hello,...world}
    >console.log(helloWorld) // Object { hello: "ððððĪŠð", world: "ððððððĨ°ððĪĐ!" }```
    
- Here is an example of using the spread operatpr to combine objects:
    > ```const objectOne = {hello: "ðĪŠ"}
    > const objectTwo = {world: "ðŧ"}
    > const objectThree = {...objectOne, ...objectTwo, laugh: "ð"}
    >console.log(objectThree) // Object { hello: "ðĪŠ", world: "ðŧ", laugh: "ð" }
    >const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("ð".repeat(5))}}
    >objectFour.laugh() // ððððð```

- the developer creates a function right below the state

- it uses the map method to update the array of people objects
- you can pass a function from parent to child like a prop (this.props.functionNName(parameters))
- a child can invoke a parent method like its props.