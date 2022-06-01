# Automation

## Python Regular Expression

- Regular Expressions, often shortened as regex, are a sequence of characters used to check whether a pattern exists in a given text (string) or not. 
- Regex patterns are used at the server side to validate the format of email addresses or passwords during registration, used for parsing text data files to find, replace, or delete certain string, etc. They help in manipulating textual data, which is often a prerequisite for data science projects involving text mining.
- A raw string literal begins with an r before a string: `r"It looks like this"`. It changes how the string literal is interpreted. Such literals are stored as they appear.
- Special characters are characters that do not match themselves as seen but have a special meaning when used in a regular expression.
- With the `search` function, you scan through the given string/sequence, looking for the first location where the regular expression produces a match.
- The `group` function returns the string matched by the re.
- The group feature of regular expression allows you to pick up parts of the matching text.
- A period `.` matches any single character except the newline character.
- `^` A caret matches the start of the string.
- `$` matches the end of string.
- `[abc]` Matches a or b or c.
- `[a-zA-Z0-9]` Matches any letter from (a to z) or (A to Z) or (0 to 9).
- `\` Backslash.
    - If the character following the backslash is a recognized escape character, then the special meaning of the term is taken
    - Else if the character following the \ is not a recognized escape character, then the \ is treated like any other character and passed through
    - `\` can be used in front of all the metacharacters to remove their special meaning
- `\w` Lowercase 'w'. Matches any single letter, digit, or underscore.
- `\W` Uppercase 'W'. Matches any character not part of `\w` (lowercase w).
- When a special character matches as much of the search sequence (string) as possible, it is said to be a "Greedy Match".

## Shutil

- The shutil module includes high-level file operations such as copying and archiving.
- By default when a new file is created under Unix, it receives permissions based on the umask of the current user. To copy the permissions from one file to another, use copymode().
- copyfile() copies the contents of the source to the destination and raises IOError if it does not have permission to write to the destination file.
- shutil includes three functions for working with directory trees. To copy a directory from one place to another, use copytree(). It recurses through the source directory tree, copying files to the destination. The destination directory must not exist in advance.
- The which() function scans a search path looking for a named file. The typical use case is to find an executable program on the shell’s search path defined in the environment variable PATH.
- Python’s standard library includes many modules for managing archive files such as tarfile and zipfile. There are also several higher-level functions for creating and extracting archives in shutil. get_archive_formats() returns a sequence of names and descriptions for formats supported on the current system.
- It can be useful to examine the local file system to see how much space is available before performing a long running operation that may exhaust that space. disk_usage() returns a tuple with the total space, the amount currently being used, and the amount remaining free.

### Resources

- https://pymotw.com/3/shutil/ 
- https://www.datacamp.com/tutorial/python-regular-expression-tutorial 
- https://www.youtube.com/watch?v=qbW6FRbaSl0&t=69s 
- https://www.youtube.com/watch?v=dZLyfbSQPXI 