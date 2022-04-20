# Test Driven Development Lecture

- TS: 2:16 - pytest is what we use to run tests. type 'pytest' into terminal to run.

- TS: 2:20 - Make a folder for tests and then a file, it should look like this: tests/test_fizz_buzz.py then an init file that looks like this: tests/__init__.py. remember to create and activate your virtual environment after this. 

- TS: 2:22 - pytest is not built in and needs to be installed using pip. Command is "pip install pytest"

- TS: 2:26 - "pip freeze > requirements.txt" in terminal to place folder in appropriate place.
"assert" evaluates if the statement is truthy or falsy

- TS: 2:29 - test writing begins. 
``` def test_fizz_buzz_one():
actual = fizz_buzz(1)
expected = '1'
assert actual == expected
```

- TS: 2:32 - begin writing the code to be tested. syntax to import: from ```fizz_buzz``` import ```fizz_buzz```
from file to module (function name)

- TS: 2:36 - positional arguments requires if we want to input something to our function

- TS: 2:58 - to skip a test use "@pytest.mark.skip("pending")" above it, this is better then removing or commenting out because you will be less likely to forget about them

**computerphile video on recursion**

-------------------------------------