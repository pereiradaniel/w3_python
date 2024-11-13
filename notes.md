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
