# Basic Rules of Python Syntax

Python’s syntax rules are crucial for writing clean, readable code. Below are the five fundamental rules:

## 1. Case Sensitivity
Python is case-sensitive, meaning that variable names and function names with different cases are treated as different identifiers.  
For example:
```python
Variable = 5
variable = 10
print(Variable)  # Outputs: 5
print(variable)  # Outputs: 10
```

## 2. Indentation
Indentation is important in Python, as it defines the blocks of code. All statements within a block must have the same indentation level.  
Incorrect indentation will lead to an `IndentationError`.  
Example:
```python
if True:
    print("This is true")  # Correct indentation
    print("This is also true")

# Incorrect indentation example
if True:
print("This will raise an error")  # This will cause an IndentationError
```

## 3. Code Blocks
A code block is a group of statements that perform a specific task. Blocks are defined by their indentation level. All statements within the block should be indented the same way.  Example:
```python
for i in range(5):
    print(i)  # This line is part of the for loop block
print("Done")  # This line is not part of the for loop block
```

## 4. Comments
Comments are used to explain code and are not executed. In Python, a comment starts with a hash mark (#). Here’s how to use both single-line and multi-line comments:
```python
# This is a single-line comment

"""
This is a multi-line comment.
It can span multiple lines.
"""
```

## 5. Statements and Newlines
In Python, each statement typically ends in a newline. You can use a semicolon (;) to separate multiple statements on a single line, but this is generally discouraged. Example:
```python
print("Hello, World!")  # This is a statement
print("This is on a new line.")

# Multiple statements on one line
x = 5; y = 10
print(x + y)
```

Learning these syntax rules is essential for any beginner in Python programming. They help in writing code that is easy to read and maintain.