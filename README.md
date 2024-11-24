<h2>Day 1 - Beginner - Working with Variables in Python to Manage Data</h2>
<p>
  ### Self Note: Day 1 - Basics of Python Programming (Angela Yu - Udemy Python Course)

#### Key Points to Remember:
1. **What is Python?**  
   - Python is a beginner-friendly, high-level programming language. It's great for building simple projects or advanced applications like websites, games, and AI tools.

2. **How to Run Python Code**:
   - Use an **online IDE** (e.g., Replit, CodeSandbox) or install **Python** on your computer and run it using an editor like **VS Code**, **PyCharm**, or **IDLE**.

3. **First Program**:
   - Print messages to the screen using the `print()` function.
     ```python
     print("Hello, World!")  # Output: Hello, World!
     ```
   - The `print()` function is a basic way to output information.

4. **Comments in Python**:
   - Comments are notes in your code that Python ignores. Use them to explain what your code does.
     ```python
     # This is a single-line comment
     print("Hello!")  # This prints Hello to the screen
     ```

5. **Using `input()` to Take User Input**:
   - The `input()` function allows the user to type something in.
     ```python
     name = input("What is your name? ")  # User types their name
     print(f"Hello, {name}!")  # Output: Hello, [Name]!
     ```

6. **Variables**:
   - Variables are used to store data. Think of them as boxes where you keep values.
     ```python
     age = 20  # age is a variable holding the value 20
     print(age)  # Output: 20
     ```

7. **Naming Rules for Variables**:
   - Variable names must:
     - Start with a letter or an underscore (_).
     - Contain only letters, numbers, or underscores.
     - Not be a Python keyword (e.g., `print`, `if`).
   - Example of valid and invalid variables:
     ```python
     my_name = "Swaroop"  # Valid
     _age = 25            # Valid
     2cool4school = "No!"  # Invalid (can't start with a number)
     ```

8. **String Manipulation with `input()`**:
   - Combine user input with a message.
     ```python
     name = input("What is your name? ")
     print("Welcome " + name + " to Day 1 of Python!")  # Concatenating strings
     ```

---

#### Practice Task:
1. Write a Python program to:
   - Ask for the user's favorite color.
   - Print a personalized message using their input.
     ```python
     color = input("What is your favorite color? ")
     print(f"Wow! {color} is a great choice!")
     ```

2. Experiment with:
   - Changing variable values and printing them.
   - Using comments to explain what each part of your program does.

---

#### Fun Fact:
- Python was named after the comedy group **Monty Python**, not the snake! 🐍

---

This covers the basics you'll need on your first day with Python. Start experimenting with `print()`, variables, and `input()` to gain confidence!
</p>

<br/>
<br/>

<h2>DAY-2: Beginner - Understanding Data Types and How to Manipulate Strings</h2>
<p>
  ### Self Note: Beginner - Understanding Data Types and How to Manipulate Strings (Angela Yu - Udemy Python Course)

#### Key Points to Remember:
1. **Data Types in Python**:
   - Data types are categories of data that Python understands. Examples:
     - **String (`str`)**: A sequence of characters (e.g., `"Hello"`, `"123"`).
     - **Integer (`int`)**: Whole numbers (e.g., `42`, `-7`).
     - **Float (`float`)**: Decimal numbers (e.g., `3.14`, `-2.5`).
     - **Boolean (`bool`)**: True or False values.

2. **Identifying Data Types**:
   - Use the `type()` function to check the type of any value.
     ```python
     print(type("Hello"))  # Output: <class 'str'>
     print(type(42))       # Output: <class 'int'>
     print(type(3.14))     # Output: <class 'float'>
     print(type(True))     # Output: <class 'bool'>
     ```

3. **Manipulating Strings**:
   - Strings are one of the most commonly used data types in Python. They are always enclosed in single (`'`) or double (`"`) quotes.

4. **Basic String Operations**:
   - **Concatenation**: Joining strings together.
     ```python
     first_name = "Angela"
     last_name = "Yu"
     full_name = first_name + " " + last_name
     print(full_name)  # Output: Angela Yu
     ```

   - **Indexing**: Accessing individual characters in a string (Python starts counting at 0).
     ```python
     word = "Python"
     print(word[0])  # Output: P
     print(word[3])  # Output: h
     ```

   - **Slicing**: Getting a part of the string.
     ```python
     word = "Python"
     print(word[0:3])  # Output: Pyt (includes index 0 to 2)
     print(word[:4])   # Output: Pyth (same as 0:4)
     print(word[2:])   # Output: thon (from index 2 to the end)
     ```

5. **String Methods**:
   - Functions that perform actions on strings.
     ```python
     text = "hello world"
     print(text.upper())    # Output: HELLO WORLD
     print(text.lower())    # Output: hello world
     print(text.title())    # Output: Hello World
     print(text.replace("world", "Python"))  # Output: hello Python
     ```

6. **f-Strings (Formatted Strings)**:
   - Easily insert variables into strings.
     ```python
     age = 25
     name = "Swaroop"
     message = f"My name is {name} and I am {age} years old."
     print(message)  # Output: My name is Swaroop and I am 25 years old.
     ```

7. **Common Errors to Avoid**:
   - Mismatched quotes (e.g., `"Hello'` instead of `"Hello"`).
   - Forgetting to convert non-string values to strings when concatenating.
     ```python
     age = 25
     print("I am " + str(age) + " years old.")  # Use str() to convert `int` to `str`
     ```

---

#### Practice Task:
1. Write a Python program that:
   - Asks for your name and age.
   - Prints a message using your input.
   ```python
   name = input("What is your name? ")
   age = input("How old are you? ")

   print(f"Hello {name}! You are {age} years old.")
   ```

2. Experiment with string methods:
   - Use `.upper()`, `.lower()`, and `.replace()` on your input string.

--- 

This topic is perfect for building your foundational understanding of Python programming. Practice these steps, and you'll start to feel more confident!
</p>
