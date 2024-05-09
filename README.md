# Python Fundamentals

## Data Types

### Numeric Types:

- **int** (Integers) - Whole Numbers e.g 5, 10
- **floats** - Decimal Numbers e.g 1.2, 2.55

### Sequence Types:

- **str (strings)** - e.g "Hello World"
- **list** - Ordered Collection of Items e.g [1, 2, 3]
- **tuples** - Collection of Items (immutable) e.g (1, 2, 3)

### Boolean Types

- True or False

## Variables 

- Variable names can contain letters, digits, and underscores, 
**BUT** they cannot start with a digit. 

- Python variable names are case-sensitive.

- Variables in Python can hold values of any data type, including numbers, 
strings, lists, tuples, dictionaries, etc.

## Number and Math Operators

- **Arithmetic Operators**: Addition (+), subtraction (-), multiplication (*), 
division (/), exponentiation (**), modulo (%).
- **Comparison Operators**: Equality (==), inequality (!=), greater than (>), 
less than (<), greater than or equal to (>=), less than or equal to (<=).
- **Logical Operators**: AND (and), OR (or), NOT (not).
- **Assignment Operators**: Assigns a value to a variable, e.g., =, +=, -=, *=, /=.

## String Basics

- **String Manipulation Methods**: Methods like .upper(), .lower(), .capitalize(), .strip(),
.split(), .join(), .replace() for modifying and formatting strings.
- **String Interpolation**: Formatting strings using f-strings (formatted string literals) 
or .format() method.
- **Indexing and Slicing**: Accessing individual characters or substrings using indices
or slicing notation ([start:end:step]).

## Boolean and Equality Operators

- **Boolean Operators**: (and, or, not) are short-circuiting, meaning they evaluate 
operands from left to right and stop as soon as the outcome is determined.
- **Identity Operators**: is, is not - used to compare the memory locations of two objects. 
- **Membership Operators**: in, not in - used to check if a value exists in a sequence 
(e.g., string, list, tuple).

## Concatenation and Escape Characters

- **Concatenation**: Combining strings using the + operator or string formatting.
- **Escape characters** allow you to include special characters in strings that would otherwise 
be interpreted differently, such as newline (\n), tab (\t), or backslash (\\).

## Control FLow

- **Conditional Statements**: (if, elif, else) allow you to execute different blocks of code based on conditions. 
- **Loops**: (for, while) let you iterate over sequences or repeat blocks of code until a condition is met. 
- **Flow Control Statements**: (break, continue, pass) provide ways to alter the flow of control within loops or conditional statements.

## Lists, Dictionaries, and Tuples

- Lists and Dictionaries are **mutable**, meaning they can be changed after creation. Tuples are **immutable**. 
- Lists and Tuples are **ordered** collections, meaning the order of elements is preserved. Dictionaries, however, are **unordered** collections. 
- List comprehensions provide a concise way to create lists based on existing lists or other iterable objects.

## Loops

- **For** loops are used for iterating over sequences like lists, strings, or ranges. They're often used when the number of iterations is known. 
- **While** loops are used when the number of iterations is not known in advance and is determined by a condition. 
- **Nested** loops allow you to iterate over multiple sequences simultaneously, such as nested lists or matrices.

## Functions

- Functions are blocks of reusable code that perform a specific task. They help in modularizing code, improving readability, and reusability. 
- Functions can take input parameters, perform operations, and optionally return a result using the return statement. 
- In Python, functions are defined using the def keyword.
