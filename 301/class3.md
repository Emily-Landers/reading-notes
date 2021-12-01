# Passing Functions as Props

- .map() returns an array based on what has been input. 
- You use curly braces for JSX
- Each list item needs a unique key to be easily identified

- the spread operator is three dots used to expand an array
- the spread operator can separate an array into separate arguments, copy arrays, add items to a list, and convert a node list into an array.
- here is an example of using the spread operator to combine two arrays:
    >
    >```[...["😋😛😜🤪😝"]] // Array [ "😋😛😜🤪😝" ]
    >[..."🙂🙃😉😊😇🥰😍🤩!"] // Array(9) [ "🙂", "🙃", "😉", "😊", "😇", "🥰", "😍"     "🤩", "!" ]

    >const hello = {hello: "😋😛😜🤪😝"}
    >const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}

    >const helloWorld = {...hello,...world}
    >console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" }```
    
- Here is an example of using the spread operatpr to combine objects:
    > ```const objectOne = {hello: "🤪"}
    > const objectTwo = {world: "🐻"}
    > const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
    >console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
    >const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
    >objectFour.laugh() // 😂😂😂😂😂```

- the developer creates a function right below the state

- it uses the map method to update the array of people objects
- you can pass a function from parent to child like a prop (this.props.functionNName(parameters))
- a child can invoke a parent method like its props.