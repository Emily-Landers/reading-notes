# Class 9

## Dunder methods

- In Python, special methods are a set of predefined methods you can use to enrich your classes. They are easy to recognize because they start and end with double underscores, for example `__init__` or `__str__`.
- As it quickly became tiresome to say under-under-method-under-under Pythonistas adopted the term “dunder methods”, a short form of “double under.”
- Dunder methods let you emulate the behavior of built-in types.
- You can see Python’s data model as a powerful API you can interface with by implementing one or more dunder methods.
- `__repr__`: The “official” string representation of an object. This is how you would make an object of the class. The goal of `__repr__` is to be unambiguous.
- `__str__`: The “informal” or nicely printable string representation of an object. This is for the enduser.
- In Python, everything is an object. 
- You can make an object callable like a regular function by adding the `__call__`

## Basic Statistics in Python

- At the most basic level, probability seeks to answer the question, “What is the chance of an event happening?”
- probability gives us a framework for making predictions about how often events will happen.
- We can use statistics to calculate probabilities based on observations from the real world and check how it compares to the ideal.
- given enough data, statistics enables us to calculate probabilities using real-world observations.
- In probability, the normal distribution is a particular distribution of the probability across all of the events.
- the Central Limit Theorem dictates that the distribution of estimates will look like a normal distribution.
- The Three Sigma rule, also known as the empirical rule or 68-95-99.7 rule, is an expression of how many of our observations fall within a certain distance of the mean.
- The Z-score is a simple calculation that answers the question, “Given a data point, how many standard deviations is it away from the mean?”

### References

- https://www.dataquest.io/blog/basic-statistics-in-python-probability/ 
- https://dbader.org/blog/python-dunder-methods 
- https://www.youtube.com/watch?v=MdHtK7CWpCQ 
- https://www.youtube.com/watch?v=7jmBE4yPrOs 
