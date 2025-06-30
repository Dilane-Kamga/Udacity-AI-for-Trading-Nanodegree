# Python Refresher Notes

## Table of Contents
1. [Introduction to Python](#introduction-to-python)
2. [Data Types](#data-types)
3. [Control Structures](#control-structures)
4. [Functions](#functions)
5. [Data Structures](#data-structures)
6. [Modules and Libraries](#modules-and-libraries)
7. [File Handling](#file-handling)
8. [Error Handling](#error-handling)
9. [Conclusion](#conclusion)

## Introduction to Python
- Python is a high-level, interpreted programming language known for its readability and simplicity.
- It supports multiple programming paradigms, including procedural, object-oriented, and functional programming.

## Data Types
- **Basic Data Types**:
  - `int`: Integer numbers (e.g., `5`, `-3`)
  - `float`: Floating-point numbers (e.g., `3.14`, `-0.001`)
  - `str`: Strings (e.g., `"Hello, World!"`)
  - `bool`: Boolean values (`True` or `False`)

- **Type Conversion**:
  - `int()`, `float()`, `str()`: Functions to convert between data types.

## Control Structures
- **Conditional Statements**:
  ```python
  if condition:
      # code to execute if condition is true
  elif another_condition:
      # code to execute if another_condition is true
  else:
      # code to execute if none of the above conditions are true
- **Loops**:
  - **For Loop**:
    ```python
    for item in iterable:
        # code to execute for each item
  - **While Loop**:
  ```python
    while condition:
        # code to execute while condition is true
  
## Functions
- **Defining Functions**:
  ```python
   def function_name(parameters):
       # code to execute
       return result
- **Lambda Functions**:
  ```python
   lambda arguments: expression
   
## Data Structures
- **Lists**: Ordered, mutable collections.
  ```python
    my_list = [1, 2, 3, "four"]  
- **Tuples**: Ordered, immutable collections.
  ```python
    my_tuple = (1, 2, 3)
- **Dictionaries**: Key-value pairs.
  ```python
    my_dict = {"key1": "value1", "key2": "value2"}
- **Sets**: Unordered collections of unique elements.
  ```python
    my_set = {1, 2, 3}
  
## Modules and Libraries
- **Importing Modules**:
  ```python
    import module_name
    from module_name import function_name
- **Common Libraries**:
  - `numpy`: For numerical computations and array manipulations.
  - `pandas`: For data manipulation and analysis, especially with tabular data.
  - `matplotlib`: For data visualization, creating static, animated, and interactive plots.

## File Handling
- **Reading Files**:
  ```python
    with open('file.txt', 'r') as file:
        content = file.read()
- **Writing to Files**:
  ```python
    with open('file.txt', 'w') as file:
        file.write("Hello, World!")
- **Appending to Files**:
  ```python
    with open('file.txt', 'a') as file:
        file.write("Appending this line.")
  
## Error Handling
- **Try-Except Blocks**
  ```python
    try:
        # code that may raise an exception
    except ExceptionType:
        # code to execute if an exception occurs
  
## Conclusion
This refresher covers the fundamental concepts of Python that are essential for the AI for Trading Nanodegree. 
Make sure to practice coding and apply these concepts in your projects!