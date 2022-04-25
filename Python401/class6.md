# Ten Thousand Game 1

## The Random Module

- The random module provides access to functions that support many operations.
- If we wanted a random integer, we can use the randint function Randint accepts two parameters: a lowest and a highest number. Generate integers between 1,5. The first value should be less than the second.

 ```
import random
print random.randint(0, 5)
This will output either 1, 2, 3, 4 or 5.
```
- If you want a larger number, you can multiply it.

For example, a random number between 0 and 100:

```
import random
random.random() * 100
```

- Choice: Generate a random value from the sequence.

```
random.choice( ['red', 'black', 'green'] ).
```

- Shuffle: The shuffle function, shuffles the elements in list in place, so they are in a random order.

```
from random import shuffle
x = [[i] for i in range(10)]
shuffle(x)
```

## Risk Analysis in Software Testing

- The probability of any unwanted incident is defined as Risk.
- In Software Testing, risk analysis is the process of identifying the risks in applications or software that you built and prioritizing them to test.
- To perform risk analysis complete these three steps:
    - Search the risk
    - Analyze the impact of each individual risk
    - Measure for the risk identified

## Test Coverage

- Test coverage is a useful tool for finding untested parts of a codebase.  
- you are doing enough testing if you rarely get bugs that escape into production, and
you are rarely hesitant to change some code for fear it will cause production bugs.
- You are testing too much if you can remove tests while still having enough. 


### Resources
- https://www.pythonforbeginners.com/random/how-to-use-the-random-module-in-python 
- https://www.edureka.co/blog/risk-analysis-in-software-testing/
- https://martinfowler.com/bliki/TestCoverage.html 