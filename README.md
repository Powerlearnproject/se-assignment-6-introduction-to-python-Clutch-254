[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15240747&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
   python is a hig level, object oriented programming language
   python is used for: 
                      -build websites and software
                      -automate tasks
                      -conduct data analysis
                      reference 2024 Coursera Inc.
2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
   Open Linux Terminal.
   - Execute command sudo apt install software-properties-common  to
   - Run the command sudo add-apt-repository ppa:deadsnakes/ppa      download a file from the repository.
   - Execute command sudo apt install python(version-name)

   to check python version and verification open the terminal and type python –version or python -V

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
   print("Hello, World!")
   print - a function used to take in input and print out the posted texts
   "" - quotation marks are used to mark texts as either strings or characters
   () - parenthasis ar used to harbour inputs that may include functions, parameters and/or variables


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
   String - these are texts usually typed in english. Eg i = ("apple")
   integer - these are whole numbers. Eg i = (2)
   float - these are decimal numbers. Eg i = (3.14)
   boolean - these is a data type that concludes and determines if a condition is true and should be met. Eg Ismale = True
   Lists - these data types that store multiple similar or different datatypes Eg fruit = ["apple", 7]
   Tuple - this is a data type that stores multiple different or similar data types but is immutable. Eg Car = ("Toyota", 5)

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
     Conditional statements are used to ensure that the required task is performed until a specific condition is met
     i = 5
     for s in i;{
      print(i)
      i--
     }

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
   Functions are blocks of code that store specific data and can be called to give out as the data stored within them

   def add(num1, num2)
     sum = num1 + num2
     print(sum)

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
   Lists are datatypes that are used to store different or similar data types while dictionaries are used to store similar data types only
   Lists use the [] as parenthasis while dictionaries use {}
   Dictionaries stoe values in pairs while lists do not
   Dictionaries have keys for each value stored while lists do not
   List = ["supra", 6, "math"]
   thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
   exception handling is used to check the code for errors
   try:
  print(x)
  except:
  print("An exception occurred")

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
    Python module is essentially a . py file containing Python definitions and statements.
   eg math.py

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
    File_object.writelines(L) for L = [str1, str2, str3]

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


