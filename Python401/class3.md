# FileIO & Exceptions

## Reading and Writing Files in Python

- At its core, a file is a contiguous set of bytes used to store data. 
- In the end, these byte files are then translated into binary 1 and 0 for easier processing by the computer.
- Files on most modern file systems are composed of three main parts:
    - Header: metadata about the contents of the file (file name, size, type, and so on)
    - Data: contents of the file as written by the creator or editor
    - End of file (EOF): special character that indicates the end of the file
- When you access a file on an operating system, a file path is required. The file path is a string that represents the location of a file.
- to open a file in python use the .open() built in method
- using a with statement is the cleanest way to close your file
```
with open('dog_breeds.txt') as reader:
    # Further file processing goes here
```
- use the built in method .readlines() to iterate over every line of a file
-  .readlines() returns a list where each element in the list represents a line in the file
```
>>> with open('dog_breeds.txt', 'r') as reader:
>>>     for line in reader.readlines():
>>>         print(line, end='')
Pug
Jack Russell Terrier
English Springer Spaniel
German Shepherd
Staffordshire Bull Terrier
Cavalier King Charles Spaniel
Golden Retriever
West Highland White Terrier
Boxer
Border Terrier
```
## Python Exceptions

- when syntactically correct Python code results in an error its called an exception error
- ```Exception errors``` will throw a specific error message 
- Python has many different built in exception errors
- ```raise``` allows you to throw an exception at any time.
- ```Try``` ```except``` blocks are used to handle exceptions
- When an exception occurs in a program running this function, the program will continue as well as inform you about the fact that the function call was not successful.
- you can also use an ```else``` clause at the end of your try catch that will instruct a program to execute a certain block of code only in the absence of exceptions.
- use ```finally``` to clean up after a ```try``` ```catch```
- everything in the ```finally``` clause will be executed even if an exception is found in the ```try``` ```catch```

## Things I want to know more about

- Built in functions on files

### Resources
- https://realpython.com/read-write-files-python/#what-is-a-file 
- https://realpython.com/python-exceptions/
- https://realpython.com/lessons/reading-and-writing-files-python-overview/ 
