# Class 1 Reading Notes

- Array.map will take an existing array and create a new array while executing a specified function for each element in that array.
- Array.reduce() will execute a function for array elements to condense them into a single value without altering the original array

- ``` function getCharacters() {
  superagent.get(swapi)
  .then( data => {
    let mainObj = data.body;
    let key = mainObj.name;
    let value = mainObj.url;
    let newObj = {
      [key]: value
    };

    console.log(newObj);
  })
  .catch(err => console.error(err));```

- ``` async function getCityData(city) {
  let results = await superagent.get('https://geocode.xyz/seattle?json=1');
  console.log(results.body.longt, results.body.latt);```
}


- Promises allow asynchronous functions to acs like they are synchronous by essentially promising a value in time.

- Not all callbacks are asynchronous, usually only the ones needing information from an external resource are asynchronous 

> Citations:

> - https://stackoverflow.com/questions/19083357/are-all-javascript-callbacks-asynchronous-if-not-how-do-i-know-which-are 
> - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise
> - https://tiftaylor.github.io/reading-notes/401/class01.html
> - https://www.javascripttutorial.net/javascript-array-reduce/ 
> - https://www.w3schools.com/jsref/jsref_reduce.asp 

