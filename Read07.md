# Python Scopes

### Scope Built-in Functions

1. globals()
- The globals() function returns the global symbol table as a dictionary.
- A symbol table contains necessary information about the current program

#### Syntax of global function: 
 - globals()
 - It takes no parameters

2. locals()
- The locals() function returns the local symbol table as a dictionary.

- A symbol table contains necessary information about the current program.

#### Syntax of locals function: 
 - locals()
 - It takes no parameters



3. vars()
- The vars() function returns the __dic__ attribute of an object.
- The __dict __ attribute is a dictionary containing the object's changeable attributes.
>  calling the vars() function without parameters will return a dictionary containing the local symbol table.

#### Syntax of vars function: 
 - vars(object)
 - It takes object parameters, the description of the parameter should be ""Any object with a __dict__attribute""


4. dir()
- The dir() function returns all properties and methods of the specified object, without the values.
- This function will return all the properties and methods, even built-in properties which are default for all object.

#### Syntax of dir function: 
 - dir(object)
 - It takes object parameters, the description of the parameter should be ""The object you want to see the valid attributes of""

