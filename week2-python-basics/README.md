# Week 2 - Python basics: data types, functions and best practices

Welcome to week 2! This week we will look at the concept of data types (despite Python being a dynamically-typed language, yes!), functions, classes as well as best practices. This file will explore a handful of topics that will be introduced in this week's homework. Please take some time to look over the content of this file as it will be a huge help when working through the notebooks. There is also a wiki file that contains a brief description of all the functions used in the homework notebooks to help you further understand. Good luck!

## Object orientated programming

Object-Oriented Programming, or OOP, is a programming paradigm that uses "objects" to design software. An **object** is a data structure that contains data (attributes) and functions (methods). These objects interact with one another to create complex applications. Imagine it like creating a blueprint (class) for a house (object), where the house has properties (like number of rooms) and behaviors (like opening a door).

## Dynamically typed progamming languages

In Python, a language that is dynamically typed, there isn't the need to declare the data type of a variable when you create it. The interpreter determines the type at runtime, which means you can assign different types of data to the same variable. For example, x = 5 (an integer) can be followed by x = "Hello" (a string) without any error - just a reassignment of the value of the variable x.

## Pythonic best practices

As proposed in the 8th Python Enchancement Proposal (PEP8 for short), there a plethora of best practices when it comes to design and styling code in Python - to view the entire document, please see the related links section. To pick a few key points though:

* Indentation: Use 4 spaces per indentation level.
* Line Length: Limit all lines to a maximum of 79 characters.
* Blank Lines: Use blank lines to separate functions and classes, and larger blocks of code inside functions.
* Imports: Always put imports at the top of the file and they should be on separate lines.
* Whitespace: Avoid extra spaces in situations where they are not needed (e.g., inside parentheses, brackets, or braces).
* Comments: Use inline comments sparingly and make sure they are clear and meaningful.
* Naming Conventions: Use `lowercase_with_underscores` for function and variable names, `UpperCase` for classes, and `ALL_CAPS` for constants.

## String and array slicing in Python

String and array slicing is a powerful feature in Python that allows you to extract a portion of a string or an array. Slicing is done using square brackets [] and a range of indices.

For strings, slicing allows you to extract a substring by specifying the start and end indices. The start index is inclusive, while the end index is exclusive. For example, `my_string[2:5]` will return the characters from index 2 to index 4 (not including index 5).

For arrays, slicing works in a similar way. You can extract a portion of an array by specifying the start and end indices. The start index is inclusive, while the end index is exclusive. For example, `my_array[1:4]` will return the elements from index 1 to index 3 (not including index 4).

Slicing can also accept a step value, allowing you to skip elements. For example, `my_string[::2]` will return every second character in the string.

## F-strings when printing variables

F-strings, short for formatted string literals, provide a concise and convenient way to embed expressions inside string literals. They are prefixed with the letter 'f' and enclosed in curly braces {}. F-strings allow you to directly insert variables and expressions into strings without the need for concatenation or formatting functions.

## Docstrings

In Python, docstrings are a type of comment used to explain the purpose of a function, method, or class. They are defined by enclosing text in triple quotes (""") at the beginning of the function. They can be accessed using the .__doc__ attribute or the help() function for better code readability and understanding.

## Lambda functions in Python

Lambda functions, also known as anonymous functions, are small, single-line functions that do not require a `def` statement. They are commonly used when a function is needed for a short period of time and does not need to be defined separately. Lambda functions are defined using the `lambda` keyword, followed by the function parameters and a single expression.

## Relevant links
* [PEP8 style guidelines](https://peps.python.org/pep-0008/)
* [PEP257 docstring guidlines](https://peps.python.org/pep-0257/)
* [Automating the Boring Stuff book](https://automatetheboringstuff.com/)
