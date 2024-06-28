[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15344794&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.


Python is a high-level programming language known for its simplicity and readability. It was created by Guido van Rossum and first released in 1991.

Key features:
1. Free and Open Source: Python language is freely available at the official website and you can download it 

2. Easy to code: Python is very easy to learn the language as compared to other languages like C, C#, Javascript, Java, etc.

3. Object-Oriented Language: Python supports object-oriented language and concepts of classes, object encapsulation, etc. 

4. GUI Programming Support: Graphical User interfaces can be made using a module such as PyQt5, PyQt4, wxPython, or Tk in Python. PyQt5 is the most popular option for creating graphical apps with Python.

5. High-Level Language: Python is a high-level language. When we write programs in Python, we do not need to remember the system architecture, nor do we need to manage the memory.

6. Large Community Support: Python has gained popularity over the years. Our questions are constantly answered by the enormous StackOverflow community. These websites have already provided answers to many questions about Python, so Python users can consult them as needed.

7. Easy to Debug:  You are able to quickly identify and correct the majority of your program’s issues once you understand how to interpret Python’s error traces. Simply by glancing at the code, you can determine what it is designed to perform.

8. Python is a Portable language: If we have Python code for Windows and if we want to run this code on other platforms such as Linux, Unix, and Mac then we do not need to change it, we can run this code on any platform.

9. Python is an Integrated language: Python is also an Integrated language because we can easily integrate Python with other languages like C, C++, etc.
(source:https://www.geeksforgeeks.org/python-features/)

cases where Python is particularly effective:
Web Development.
Artificial Intelligence and Machine Learning.
Data Analysis.
Data Visualization.
Game Development.
Finance.
Web Scraping.
Desktop App Development.
(source:https://www.planeks.net/what-is-python-used-for/)



2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   1. Head over to http://wwww.python.org and "click download" to download the python appication.
   2. To install the application, "click install" button and follow the prompts on the screen, and Ensure to select the box that says "Add Python to PATH" during the installation. When done run the appication the python is installed.
   

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   # Simple Python program to print "Hello, World!" to the console

print("Hello, World!")

In Python, the print() function is used to display or output information to the standard output, which is typically the console or terminal. In this case, the print() function is passed the string “Hello, World!” as its argument. A string is a sequence of characters enclosed in quotation marks.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   Data Types In Python:Are Variables that can store data of different types, and different types can do different things.
      Numerical Data Type
      Strings
      Lists
      Tuples
      Sets
      Dictionary
      Range
      (source: https://www.w3schools.com/python/python_datatypes.asp, https://www.edureka.co/blog/variables-and-data-types-in-python/)

# Integer variable
age = 45

# Float variable
height = 6

# String variable
name = "Penina"

# Boolean variable
is_student = True

# List variable (collection of items)
favorite_fruits = ["grapes", "peach", "orange"]


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

  conditional statements and loops in Python: Allow programmers to automate repetitive tasks and control the flow of their programs based on certain conditions.
  (source: https://www.linkedin.com/pulse/loops-conditional-statements-python-can-arslan#:~:text=Loops%20and%20conditional%20statements%20are%20powerful%20constructs%20that%20allow%20programmers,statements%20in%20Python%20with%20examples.)

Examples:
x = 35

if x > 0:
    print("x is positive")
elif x == 0:
    print("x is zero")
else:
    print("x is negative")

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   A function is a block of code which only runs when it is called, it can return data as a result.
   functions say something about the connection or relationship between things. (source: https://www.houseofmath.com/encyclopedia/functions/theory-of-functions/fundamentals-of-functions/why-are-functions-important-in-real-life)

# Calling the function and storing the result in a variable
result = add_numbers(2, 9)

# Printing the result
print("the sum is:", 11)


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

   List vs Dictionary:
   Lists and Dictionaries are different data structures in Python. Lists are ordered collections of items, whereas the dictionary is an unordered collection of data in a key: value pair form. Both lists and dictionaries are mutable, i.e., you can add, edit, delete, or modify the elements.
   (source: https://www.shiksha.com/online-courses/articles/difference-between-list-and-dictionary-in-python/#Key-Differences-Between-List-and-Dictionary-in-Python)

# create a python list
myList = [2, 4, 6, 8, 10]
print(myList) 

then run the code, it will print the values of myList

# Create a dictionary with key-value pairs
person = [
    'name': 'Annah Bella',
    'age': 20,
    'city': 'Durban',
    'email': 'annahbella@gmail.com']
    print(person)

    then run the code, 

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

   Handling exceptions in Python when is error occurs that can cause the program to terminate.

   def divide_numbers(a, b):
    try:
        result = a / b  # Attempting division
    except ZeroDivisionError:
        print("Error: Division by zero!")  # Handling division by zero error
    except TypeError:
        print("Error: Unsupported operation!")  # Handling unsupported operation error (e.g., dividing a string)
    else:
        print(f"The result of {a} divided by {b} is: {result}")  # Executed if no exception is raised
    finally:
        print("Execution completed.")  # This block is always executed, regardless of exceptions

# Example usage:
divide_numbers(10, 2)  # Normal division
divide_numbers(10, 0)  # Division by zero
divide_numbers(10, '2')  # Unsupported operation


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. 
   
   Modules: Reusable pieces of code, using `import` to include them.
   Packages: Collections of modules, using `pip` to install packages.



   
   

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
    reads content of a file:
    Open the File: Use the open() function with the file path and mode ('r' for reading).
    Read the Content: Use methods like read(), readline(), or readlines() to retrieve the content.
    Close the File: Use the close() method to close the file once you're done reading.

    def read_file(file_path):
    try:
        with open(file_path, 'r') as file:
            content = file.read()
            print(content)

writes a list of string to a file:
Open the File: Use the open() function with the file path and mode ('w' for writing). If the file doesn't exist, it will be created. If it exists, its previous contents will be overwritten.
Write Content: Use methods like write() to write data into the file.
Close the File: Use the close() method to close the file after writing

def write_to_file(file_path, lines):
    try:
        with open(file_path, 'w') as file:
            for line in lines:
                file.write(line + '\n')
        print(f"Successfully wrote {len(lines)} lines to '{file_path}'.")
   

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [28 june 2024].


