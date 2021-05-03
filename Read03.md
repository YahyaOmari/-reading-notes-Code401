# FileIO 

## File handling
- he key function for working with files in Python is the open() function.
- The open() function takes two parameters; filename, and mode, for example: 
- - f = open("demofile.txt")
- There are four different methods (modes) for opening a file:

1. "r" - Read - Default value. Opens a file for reading, error if the file does not exist
2. "a" - Append - Opens a file for appending, creates the file if it does not exist
3. "w" - Write - Opens a file for writing, creates the file if it does not exist
4. "x" - Create - Creates the specified file, returns an error if the file exists

# Exceptions

## What are Exceptions?
- **Exceptions are events that are used to modify the flow of control through a program when the error occurs. Exceptions get triggered automatically on finding errors in Python.**

#### I will give some example of exceptions: 
1. *Try/except*: catch the error and recover from exceptions hoist by programmers or Python itself.
2. *Try/finally*: Whether exception occurs or not, it automatically performs the clean-up action.
3. *Assert*: triggers an exception conditionally in the code.
4. *Raise*: manually triggers an exception in the code.

