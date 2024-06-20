[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15305707&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   Python is a high-level, interpreted programming language known for its simplicity and readability. It supports multiple programming paradigms, including procedural, object-oriented, and functional programming. Some of its key features include:

- Easy to Learn and Use: Python's syntax is straightforward, making it an excellent choice for beginners.
- Interpreted Language: Python code is executed line-by-line, which makes debugging easier.
- Dynamically Typed: You don't need to declare the data type of a variable when you create it.
- Extensive Libraries: Python has a vast standard library and a large ecosystem of third-party packages.
- Cross-Platform: Python runs on various operating systems, including Windows, macOS, and Linux.
- Community Support: Python has a large and active community, which means plenty of resources and support are available.

* Use Cases:
- Web Development: Using frameworks like Django and Flask.
- Data Science and Machine Learning: Utilizing libraries such as Pandas, NumPy, and scikit-learn.
- Automation and Scripting: Writing scripts to automate repetitive tasks.
- Scientific Computing: Performing complex calculations with SciPy.
- Game Development: Using libraries like Pygame

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   1. Download the installer from the official Python website.
   2. Run the installer and select "Add Python to PATH" before clicking "Install Now".
   3. Verify the installation by opening Command Prompt and typing: python --version
   4. To set up a virtual environment, navigate to your project directory and run: python -m venv env


3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   print(): This is a built-in function that outputs the specified message to the console.
   "Hello, World!": This is a string, a sequence of characters enclosed in quotes.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   Basic Data Types:
- int: Integer numbers
- float: Floating-point numbers
- str: Strings (text)
- bool: Boolean values (True or False)
- list: Ordered sequence of values
- dict: Unordered collection of key-value pairs

   Script:
   # Integer
   age = 25
   print(f"Age: {age}, Type: {type(age)}")

   # Float
   height = 5.9
   print(f"Height: {height}, Type: {type(height)}")

   # String
   name = "Alice"
   print(f"Name: {name}, Type: {type(name)}")

   # Boolean
   is_student = True
   print(f"Is student: {is_student}, Type: {type(is_student)}")

   # List
   fruits = ["apple", "banana", "cherry"]
   print(f"Fruits: {fruits}, Type: {type(fruits)}")

   # Dictionary
   person = {"name": "Bob", "age": 30}
   print(f"Person: {person}, Type: {type(person)}")


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   Conditional Statements are used to execute different blocks of code based on certain conditions.
   Example:age = 20
   if age >= 18:
      print("You are an adult.")
   else:
      print("You are a minor.")

   Loops are used to repeat a block of code multiple times.
   Example of a for loop: fruits = ["apple", "banana", "cherry"]
                           for fruit in fruits:
                              print(fruit)

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   Functions are reusable blocks of code that perform a specific task. They help in organizing code, reducing redundancy, and improving readability.
   Example: 
      def add_numbers(a, b):
      return a + b

      # Calling the function
      result = add_numbers(5, 3)
      print(result)  # Output: 8


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
      
   Lists are ordered collections of elements that can be accessed by their index.
   Dictionaries are unordered collections of key-value pairs where each key is unique.

   Example:
      # List
      numbers = [1, 2, 3, 4, 5]
      print(numbers)
      numbers.append(6)
      print(numbers)
      print(numbers[2])  # Accessing the third element

      # Dictionary
      person = {"name": "Alice", "age": 25, "city": "New York"}
      print(person)
      person["email"] = "alice@example.com"
      print(person)
      print(person["name"])  # Accessing the value associated with the key 'name'

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

   Exception Handling is a way to handle runtime errors in your code, allowing the program to continue executing or to fail gracefully.
   Example: 
      try:
         result = 10 / 0
         except ZeroDivisionError:
            print("Error: Division by zero is not allowed.")
         finally:
            print("This block is always executed.")

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   Modules are files containing Python code (functions, classes, variables) that can be imported and used in other Python scripts. Packages are collections of modules organized in directories.

   Example using the math module:
      import math

      # Using the math module
      print(math.sqrt(16))  # Output: 4.0
      print(math.pi)  # Output: 3.141592653589793

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

    Reading from a file: 
      with open('example.txt', 'r') as file:
         content = file.read()
         print(content)

   Writing from a file: 
      lines = ["First line", "Second line", "Third line"]
      with open('output.txt', 'w') as file:
         for line in lines:
            file.write(line + "\n")



# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


