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

- O(n^2) is an algorithm whose performance is directly proportional to the square of the size of the input data set. Time and space will essentially compound on each other. (think nested loops)

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

