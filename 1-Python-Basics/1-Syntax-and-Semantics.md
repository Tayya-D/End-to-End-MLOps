### Summary of Python Syntax and Semantics Notes

This document provides an overview of Python syntax and semantics, focusing on key concepts that are essential for beginners. Below is a concise summary of the topics covered:

---

### 1. **Comments in Python**
   - **Single-line comments**: Use `#` to write comments on a single line.
     ```python
     # This is a single-line comment
     ```
   - **Multi-line comments**: Use triple quotes (`'''` or `"""`) for comments spanning multiple lines. Note that this works in `.py` files but not in Jupyter notebooks.
     ```python
     '''
     This is a multi-line comment.
     It spans multiple lines.
     '''
     ```

---

### 2. **Syntax vs. Semantics**
   - **Syntax**: Refers to the rules that define how symbols and words are arranged to form a correctly structured program.
     - Example: Correct use of colons, indentation, and variable assignment.
   - **Semantics**: Refers to the meaning or interpretation of the code, i.e., what the code is supposed to do when executed.
     - Example: Understanding what a loop or function does when it runs.

---

### 3. **Basic Syntax Rules**
   - **Case Sensitivity**: Python is case-sensitive. Variables like `name` and `Name` are treated as different identifiers.
     ```python
     name = "Chris"
     Name = "Nick"
     print(name)  # Output: Chris
     print(Name)  # Output: Nick
     ```
   - **Indentation**: Python uses indentation (usually 4 spaces or a tab) to define blocks of code, such as in `if` statements, loops, and functions.
     ```python
     if age > 30:
         print("Age is greater than 30")  # Indented block
     ```
   - **Line Continuation**: Use a backslash (`\`) to continue a long line of code onto the next line.
     ```python
     total = 1 + 2 + 3 + \
             4 + 5 + 6
     ```
   - **Multiple Statements on a Single Line**: Use a semicolon (`;`) to write multiple statements on one line.
     ```python
     x = 5; y = 10; z = x + y
     ```

---

### 4. **Variable Assignment and Type Inference**
   - Python dynamically infers the type of a variable at runtime, allowing for dynamic typing.
     ```python
     age = 32  # Python infers 'age' as an integer
     name = "Chris"  # Python infers 'name' as a string
     ```
   - You can check the type of a variable using the `type()` function.
     ```python
     print(type(age))  # Output: <class 'int'>
     print(type(name))  # Output: <class 'str'>
     ```
   - Variables can be reassigned to different types.
     ```python
     var = 10  # Initially an integer
     var = "Chris"  # Now a string
     ```

---

### 5. **Common Syntax Errors**
   - **Indentation Error**: Occurs when indentation is not used correctly in blocks of code.
     ```python
     if age > 30:
     print("Age is greater than 30")  # Error: Missing indentation
     ```
   - **Name Error**: Occurs when a variable is used before it is defined.
     ```python
     print(b)  # Error: Name 'b' is not defined
     ```

---

### 6. **Practical Examples**
   - **Indentation in Nested Conditions**:
     ```python
     if True:
         print("Correct indentation")
         if False:
             print("This will not print")
         print("Outside the inner if block")
     print("Outside the if block")
     ```
   - **Dynamic Typing Example**:
     ```python
     var = 10
     print(type(var))  # Output: <class 'int'>
     var = "Chris"
     print(type(var))  # Output: <class 'str'>
     ```

---

### 7. **Key Takeaways**
   - Python syntax is strict about indentation and case sensitivity.
   - Comments help in documenting code and are ignored during execution.
   - Python uses dynamic typing, allowing variables to change types during runtime.
   - Common errors include indentation errors and name errors, which can be avoided by following syntax rules.

---

### Next Steps
In the next session, we will cover:
- Variables
- Data types
- Operators

---
