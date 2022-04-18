# Class Two Reading Notes

## Unit tests

- Exercise the input, the output and the behavior of your code.
- Start with what small things you can test, then larger
- use clear, easy to understand naming for each test that shows which file the test specifically belongs to.
- Ex: 
    - a file called ```gender.py``` should have a corresponding ```test_gender.py```
- Ex:

    ``` def test_should_return_female_when_the_name_is_from_female_gender():
    detector = GenderDetector()
    expected_gender = detector.run(‘Ana’)
    assert expected_gender == ‘female’

- The example should return 'female' when the name is from a female
- Testing structure is important. Try to use the "Arrange, Act, and Assert" method when writing tests.
    - Arrange: figure out how you want to write your tests (The input)
    - Act: execute your code
    - Assert: check to see if the output gave the desired result

## Recursion

- When a function either directly or indirectly calls itself it is called recursion
- Using recursion can be a more efficient way of problem solving for developers
- Ex:
    ``` 
    f(n) = 1                  n=1
    f(n) = n + f(n-1)    n>1 
- A recursive function is tail recursive when recursive call is the last thing executed by the function.
- recursive programming is less time and space efficient than iterative programming, but it is much cleaner and simpler to write.

### Resources:

- https://code.likeagirl.io/in-tests-we-trust-tdd-with-python-af69f47e6932 
- https://www.geeksforgeeks.org/recursion/ 
- https://www.youtube.com/watch?v=Mv9NEXX1VHc 
