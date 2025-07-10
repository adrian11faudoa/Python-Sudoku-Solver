Subject:

In Python, a class is a blueprint for creating objects. Objects created from a class are instances of that class. You can create a class using this syntax:

Example Code:
```
    class ClassName:
        pass
```


A new instance of a class is created by using the function notation, which involves appending a pair of parentheses to the class name.


Classes can have methods, which are like local functions for each instance. Within a class, methods are declared as follows:

Example Code:
```
    class ClassName:
        def method_name():
            pass
```


To call an instance method, you need to use dot notation:

Example Code:
```
instance_name.method_name()
```


The instantiation creates an empty object. 
The __init__ method is a special method that allows you to instantiate an object to a customized state. 
When a class implements an __init__ method, __init__ is automatically called upon instantiation.


An attribute is a variable associated with an object, which is used to store data as regular variables.


The enumerate built-in function takes an iterable as its argument and returns an enumerate object you can iterate over. It provides the count (which by default starts at zero) and the value from the iterable.

Example Code:
```
    iterable = ['a', 'b', 'c']
    for i, j in enumerate(iterable):
        print(i, j)
```
The loop from the example above would output the tuples 
0, a, 1, b, and 2, c.


The try statement is used to encapsulate code that might raise an exception. 
The except clause, on the other hand, offers alternative code to execute if an exception occurs:

Example Code:
```
    try:
        <code>
    except:
        <code>
```


tuple unpacking
A tuple can be unpacked, meaning that the elements contained in the tuple can be assigned to variables, like this:

Example Code:
```
    spam = ('lemon', 'curry')
    item1, item2 = spam
```


The := operator gives you the ability to assign variables in the middle of an expression. The syntax is: name := val, where name is the variable name and val is the variable value.

This construct is formally named assignment expressions, while the := operator is commonly referred to as the walrus operator.


The __str__ method is a special method that is called under the hood when the object is printed using the print() function, or converted into a string using the str() function.

