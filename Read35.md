# Pythonisms

### Dunder Methods

- Dunder or magic methods in Python are the methods having two prefix and suffix underscores in the method name. Dunder here means “Double Under (Underscores)”. These are commonly used for operator overloading. Few examples for magic methods are: __ init__, __ add__, __ len__, __ repr__ 

### What are iterators in Python?

- Iterator in python is an object that is used to iterate over iterable objects like lists, tuples, dicts, and sets. The iterator object is initialized using the iter() method. It uses the next() method for iteration. ... This method raises a StopIteration to signal the end of the iteration.

### Iterators

- An iterator is an object that contains a countable number of values.

- An iterator is an object that can be iterated upon, meaning that you can traverse through all the values.

- Technically, in Python, an iterator is an object which implements the iterator protocol, which consist of the methods __ iter__() and __ next__().

### What are the generators in Python?

- Python provides a generator to create your own iterator function. A generator is a special type of function which does not return a single value, instead, it returns an iterator object with a sequence of values. In a generator function, a yield statement is used rather than a return statement.

### Why generators are used in Python?

- Generators have been an important part of Python ever since they were introduced with PEP 255. Generator functions allow you to declare a function that behaves like an iterator. They allow programmers to make an iterator in a fast, easy, and clean way. ... An iterator is an object that can be iterated (looped) upon.