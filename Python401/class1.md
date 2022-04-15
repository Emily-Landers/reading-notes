# Class 1 Reading Notes

## Big O Notation

- Big O is how we determine the efficiency of our algorithm using two parameters: time and space
- Specifically the worst case scenario for our code
- O(1) id not dependent on size of input. Executed the same time (or space) always.

``` 
bool IsFirstElementNull(IList<String> elements)
{
    return elements[0] == null;
}
```

- O(n) is dependent on size of input (think loops)

``` {
    foreach (var element in elements)
    {
        if (element == value) return true;
    }
    return false;
}
```

- O(N²) is an algorithm whose performance is directly proportional to the square of the size of the input data set. Time and space will essentially compound on each other. (think nested loops)

``` 
bool ContainsDuplicates(IList<string> elements)
{
    for (var outer = 0; outer < elements.Count; outer++) 
    {
        for (var inner = 0; inner < elements.Count; inner++) 
        { 
            // Don't compare with self 
            if (outer == inner) continue;             
            
            if (elements[outer] == elements[inner]) return true; 
        }
    }    
    return false;
}
```

- O(2^N) indicates an algorithm whose growth doubles with each addition to the input data set. This algorithm sees exponential growth. (Think recursive calculation of Fibonacci numbers)

``` int Fibonacci(int number)
{
    if (number <= 1) return number;
       
    return Fibonacci(number - 2) + Fibonacci(number - 1); 
} 
```

- O(log N) indicates an algorithm that produces a growth curve that peaks at the beginning and slowly flattens out as the size of the data sets increase e.g. an input data set containing 10 items takes one second to complete, a data set containing 100 items takes two seconds, and a data set containing 1,000 items will take three seconds.

``` for (i = 0; i < log2(input.count); i++) {
    doSomething(...);
} 
```
### Things I Want To Learn More About

- Big O notation and code efficiency
- Logarithms

- References:
    - https://softwareengineering.stackexchange.com/questions/146021/determining-if-an-algorithm-is-o-log-n
    - https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation 
    - https://www.codenewbie.org/basecs/8 

