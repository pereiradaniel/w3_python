# [Python Getting Started](https://www.w3schools.com/python/python_getstarted.asp)

## What is Python?

Python is a popular programming language. It was created by Guido van Rossum, and released in 1991.

It is used for:
- web development (server-side)
- software development
- mathematics
- system scripting

## What can Python do?

Python can be used on a server to create web applications.
Python can be used alongside software to create workflows.
Python can connect to database systems. It can also read and modify files.
Python can be used to handle big data and perform complex mathematics.
Python can be used for rapid prototyping, or for production-ready software development.

## Why Python?

Python works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc).
Python has a simple syntax similar to the English language.
Python has syntax that allows developers to write programs with fewer lines than some other programming languages.
Python runs on an interpreter system, meaning that code can be executed as soon as it is written. This means that prototyping can be very quick.
Python can be treated in a procedural way, an object-oriented way or a functional way.

## Good to know

The most recent major version of Python is Python 3, which we shall be using in this tutorial. However, Python 2, although not being updated with anything other than security updates, is still quite popular.

In this tutorial Python will be written in a text editor. It is possible to write Python in an Integrated Development Environment, such as Thonny, Pycharm, Netbeans or Eclipse which are particularly useful when managing larger collections of Python files.

## Python Syntax compared to other programming languages

Python was designed for readability, and has some similarities to the English language with influence from mathematics.
Python uses new lines to complete a command, as opposed to other programming languages which often use semicolons or parentheses.
Python relies on indentation, using whitespace, to define scope; such as the scope of loops, functions and classes. Other programming languages often use curly-brackets for this purpose.

## Hello World

```
print("Hello, World!")
```

## Command Line Basics

Open the Python interpreter from the command prompt: Python
To exit the interpreter: exit()

## Python file extension

The correct file extension for a Python file is .py

---

# [Python Syntax](https://www.w3schools.com/python/python_syntax.asp)

## Execute Python Syntax

Python can be executed by writing directly in the Python interpreter.
Python can be executed by creating a python file and running it in the Command Line.

```
python myfile.py
```

## Python Indendation

- Refers to spaces at the beginning of a code line.
- In other programming languages, indentation is for readability, in Python it is **very important**!
- Python uses indentation to indicate a block of code.

```
if 5 > 2:
print("Five is greater than two!")
```

_Python will give you an error if you skip the indentation!_

The number of spaces is up to the programmer.
1. Commonly four.
2. Must be at least one.
3. You have to use the same number of spaces in the same block fo code, otherwise Python gives an error.
    
## Python Variables

- Variables are created when you assign a value to it:
- Python has *no command* for declaring a variable!

```
x = 5
y = "Hello, World!"
```

## Comments

- Python allows comments for in-code documentation.
- Python will render the rest of any line starting with #.

```
# To check the Python version of the editor, you can find it by importing the sys module:
import sys
print(sys.version)
```

---

# [Python Comments](https://www.w3schools.com/python/python_comments.asp)

Comments can be used to:
1. Explain Python code.
2. Make the code more readable.
3. Prevent execution when testing code.

## Creating a Comment

Python will ignore everything after #, so a comment can be left at the end of a line:

```
print("Hello World!") # Outputs text to the screen
```

## Multiline Comments
Python does not have a syntax for multiline comments, just add # to the beginning of each line you want to be a comment.

Python will ignore string literals that are not assigned to a variable.
You can add a multiline string (triple quotes) and place a comment inside it:

```
"""
This is
a multiline
comment
"""

print("Hello, World!")
```

As long as the string is not assigned to a variable, Python will read the code, but then ignore it.

---

# [Python Variables](https://www.w3schools.com/python/python_variables.asp)

## Variables

Variables are containers for storing data values.

## Creating Variables

1. Python has no command for declaring a variable.
2. A variable is created the moment you first assign a value to it.

```
x = 5
y = "John"
print(x)
print(y)
```

3. Variables do not need to be declared with any particular type, and can even change type after they have been set.
*Python is NOT a strictly typed language!*

```
x = 4            # set x to 4
print(x)
x = "String"     # redefine x as "String"
print(x)
```

## Casting

If you want to specify the data type of a variable, this can be done with casting:

```
x = str(3)      # x will equal '3'
y = int(3)      # y will equal 3
z = float(3)    # z will be 3.0
```

## Get the Type

The *type()* function will return the data type of a variable.

```
x = 5
y = "String"
print(type(x))
print(type(y))
```

## Single or Double Quotes?

String variables can be declared either by using single or double quotes:

```
x = "John"
y = 'John'
```

## Case-Sensitive

Variable names are case-sensitive:

```
a = 4
A = "Sally" # Will not overwrite a
print(a)
print(A)
```

# [Python - Variable Names](https://www.w3schools.com/python/python_variables_names.asp)

## Variable Names

Variables can have short names or a more descriptive name.

### Rules for Python Variables:

1. Must start with a letter or the underscore character.
2. Cannot start with a number.
3. Can only contain alpha-numeric characters and underscores (A-z, 0-9, and _)
4. Case-sensitive.
5. Cannot be any of the Python keywords.

## Multi Words Variable Names

Variable names with more than one word are difficult to read. There are several techniques to make them more readable:

### Camel Case

myVariableName = "text"

### Pascal Case

MyVariableName = "text"

### Snake Case

my_variable_name = "text"

# [Python Variables - Assign Multiple Values](https://www.w3schools.com/python/python_variables_multiple.asp)

## Many Values to Multiple Variables

Python allows you to assign values to multiple variables in one line:

```
x, y, z = "Orange, "Banana", "Cherry"
print(x)
print(y)
print(z)
```

## One Value to Multiple Variables

```
x = y = z = "Orange"
print(x)
print(y)
print(z)
```

## Unpack a Collection

If you have a collection of values in a list, tuple, etc. Python allows you to extract the values into variables. This is called *unpacking*.

```
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
print(x)
print(y)
print(z)
```

# [Python - Output Variables](https://www.w3schools.com/python/python_variables_output.asp)

## Output Variables

The Python *print()* function is often used to output variables. In the *print()* function, you output mutliple variables, separated by a comma:

```
x = "Python "
y = "is "
z = "awesome"
print(x + y + z)
```

For numbers, the *+* character works as a mathematical operator:

```
x = 5
y = 10
print(x + y)
```

If you try to combine a string with a number in this way, Python will throw an error. The best way to output multiple variables in *print()* is to separate them with commas, which will support different data types:

```
x = 5
y = "text"
print(x, y)
```

# [Python - Global Variables](https://www.w3schools.com/python/python_variables_global.asp)

## Global Variables

Variables that are created outsiude of a function are known as *global variables*.
Global variables can be used by everyone, both inside of functions and outside.

```
x = "awesome"

def myfunc():
    print("Python is "+ x)

myfunc()
```

If you create a variable with the same name inside a function, this variable will be local, and can only be used inside the function. The global variable with the same name will remain as it was, global and with the original value.

```
x = "awesome"

def myfunc():
    x = "fantastic"
    print("Python is " + x)

myfunc()

print("Python is " + x)
```

## The *global* Keyword

Normally, when you create a variable inside of a function, that variable is local, and can only be used inside that function. To create a global variable inside of a function, you can use the *global* keyword.

```
def myfunc():
    global x
    x = "fantastic"

myfunc()

print("Python is " + x)
```

Also, use the *global* keyword if you want to change a global variable inside a function.

```
x = "awesome"

def myfunc():
    global x
    x = "fantastic"

myfunc()

print("Python is " + x)
```

