[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15394765&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

      Python is a high-level, interpreted programming language known for its simplicity and readability. It was created by Guido van Rossum and first released in 1991. Python's syntax is designed to be clean and straightforward, allowing developers to express concepts in fewer lines of code compared to other languages.

      Key Features:

      Easy to Learn and Use: Python's simple syntax makes it an excellent choice for beginners.
      Interpreted Language: Python code is executed line by line, which simplifies debugging and testing.
      Dynamically Typed: Variables in Python do not require explicit declaration, making the code more flexible.
      Extensive Standard Library: Python comes with a vast library of modules and packages that facilitate various tasks like web development, data analysis, machine learning, and more.
      Cross-Platform: Python runs on various operating systems such as Windows, macOS, and Linux.
      Community Support: Python has a large and active community, providing a wealth of resources and libraries.
      Use Cases:

      Web Development: Using frameworks like Django and Flask.
      Data Analysis and Visualization: Libraries like Pandas, NumPy, and Matplotlib.
      Machine Learning and AI: Libraries such as TensorFlow, Keras, and scikit-learn.
      Scripting and Automation: Automating repetitive tasks using simple scripts.
      Scientific Computing: Tools like SciPy and Jupyter Notebooks.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
   Installing Python on Linux:

   `   Open Terminal.
      Use the package manager of your distribution to install Python. For example, on Ubuntu:
      sh
      sudo apt update
      sudo apt install python3
      Verifying Installation:

      Open a terminal or command prompt.
      Run:
      sh
      python --version
      or
      sh
      python3 --version
      This should display the installed Python version.
      Setting Up a Virtual Environment:

      Navigate to your project directory.
      Create a virtual environment:
      sh
      python -m venv env
      or
      sh
      python3 -m venv env
      Activate the virtual environment:
      On Windows:
      sh
      .\env\Scripts\activate
      On macOS/Linux:
      sh
      source env/bin/activate`

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

      print("Hello, World!")
      print: This is a built-in function in Python used to output text to the console.
      "Hello, World!": This is a string literal enclosed in double quotes. In Python, strings can be enclosed in either single or double quotes.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

       Basic Data Types:

         int: Integer type, e.g., 1, 42
         float: Floating-point type, e.g., 3.14, 2.0
         str: String type, e.g., "Hello", 'World'
         bool: Boolean type, e.g., True, False
         list: Ordered, mutable collection, e.g., [1, 2, 3]
         tuple: Ordered, immutable collection, e.g., (1, 2, 3)
         dict: Unordered collection of key-value pairs, e.g., {"key": "value"}
         set: Unordered collection of unique elements, e.g., {1, 2, 3}

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
         print(f"Is Student: {is_student}, Type: {type(is_student)}")

         # List
         numbers = [1, 2, 3, 4, 5]
         print(f"Numbers: {numbers}, Type: {type(numbers)}")

         # Tuple
         coordinates = (10.0, 20.0)
         print(f"Coordinates: {coordinates}, Type: {type(coordinates)}")

         # Dictionary
         person = {"name": "Alice", "age": 25}
         print(f"Person: {person}, Type: {type(person)}")

         # Set
         unique_numbers = {1, 2, 3, 4, 5}
         print(f"Unique Numbers: {unique_numbers}, Type: {type(unique_numbers)}")




5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

      Conditional Statements:
      Conditional statements allow for decision-making in code, executing different code blocks based on certain conditions.

      Example of an if-else statement:

      python

      age = 18
      if age >= 18:
         print("You are an adult.")
      else:
         print("You are a minor.")
      Loops:
      Loops allow for the repeated execution of a block of code.

      Example of a for loop:

      python

      # Loop through a list of numbers
      numbers = [1, 2, 3, 4, 5]
      for number in numbers:
         print(number)



6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

  `   Functions:
      Functions are reusable blocks of code that perform a specific task. They are useful for breaking down complex problems into smaller, manageable parts, improving code readability and maintainability.

      Example function:

      python

      def add_numbers(a, b):
         return a + b

      # Calling the function
      result = add_numbers(5, 3)
      print(f"The sum is: {result}")

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

   Lists:

   Ordered collections of items.
   Items can be accessed by their index.
   Items can be of different data types.
   Syntax: [item1, item2, item3]
   Dictionaries:

   Unordered collections of key-value pairs.
   Items can be accessed by their key.
   Keys must be unique and immutable.
   Syntax: {key1: value1, key2: value2}
   Script:

   python

   # List of numbers
   numbers = [1, 2, 3, 4, 5]
   print("List of numbers:", numbers)

   # Accessing elements in a list
   print("First number:", numbers[0])

   # Adding an element to a list
   numbers.append(6)
   print("Updated list:", numbers)

   # Dictionary with key-value pairs
   person = {
      "name": "Alice",
      "age": 25,
      "city": "New York"
   }
   print("Dictionary:", person)

   # Accessing values in a dictionary
   print("Name:", person["name"])

   # Adding a key-value pair to a dictionary
   person["email"] = "alice@example.com"
   print("Updated dictionary:", person)
8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

      Exception Handling:
      Exception handling in Python allows a program to deal with errors gracefully without crashing. It uses try, except, and finally blocks to catch and handle exceptions.

      Example:

      python

      try:
         # Code that might raise an exception
         result = 10 / 0
      except ZeroDivisionError as e:
         # Code to handle the exception
         print(f"Error: {e}")
      finally:
         # Code that will run no matter what
         print("Execution completed.")
9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
      Modules and Packages:

      Module: A single file (or files) containing Python code, which can define functions, classes, and variables. Modules help in organizing and reusing code.
      Package: A collection of modules in a directory that contains a special __init__.py file. Packages help in structuring large applications.
      Importing and Using a Module:
      Example using the math module:

      python

      import math

      # Using a function from the math module
      result = math.sqrt(16)
      print(f"The square root of 16 is: {result}")

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

    Reading from a File:

      python
      # Reading the content of a file
      try:
         with open('example.txt', 'r') as file:
            content = file.read()
            print(content)
      except FileNotFoundError:
         print("The file was not found.")
   Writing to a File:

      python
      # List of strings to write to a file
      lines = ["First line", "Second line", "Third line"]

      # Writing the list of strings to a file
      with open('output.txt', 'w') as file:
         for line in lines:
            file.write(line + "\n")

      print("Data written to output.txt successfully.")

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


