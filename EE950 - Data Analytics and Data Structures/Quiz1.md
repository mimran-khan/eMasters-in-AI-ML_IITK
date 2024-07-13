# EE950 - Data Analytics and Data Structures

# Quiz - 1

 

 1.  What are correct statements about python:
 - [x] it has object-oriented functionality
 - [x] Python implementations include: Jython, IronPython, Stackless, PyPy
 - [x] Python comes under imperative, functional, procedural programming paradigm
 - [ ] Python is interpreted language, so there is no compiler inside at all

Explaination: 
 -   **It has object-oriented functionality**
        -   **Correct**: Python is an object-oriented programming language, which means it supports the concept of objects and classes. Python allows you to define classes, create objects, and implement concepts such as inheritance, polymorphism, and encapsulation.
 -   **Python implementations include: Jython, IronPython, Stackless, PyPy**
		- **Correct**: There are several implementations of Python:
			- **Jython**: Python implemented in Java, which allows you to run Python code on the Java platform.
		     -   **IronPython**: Python implemented in C# and integrated with the .NET framework.
		        -   **Stackless**: An enhanced version of Python providing microthreads for better concurrency handling.
		        -   **PyPy**: An alternative implementation of Python with a Just-In-Time (JIT) compiler to improve performance.
-   **Python comes under imperative, functional, procedural programming paradigm**
    -   **Correct**: Python supports multiple programming paradigms:
        -   **Imperative**: Python allows you to write code that changes state through statements.
        -   **Functional**: Python supports functional programming features like first-class functions, higher-order functions, and lambda expressions.
        -   **Procedural**: Python supports procedural programming, which involves writing procedures or functions that operate on data.
-   **Python is interpreted language, so there is no compiler inside at all**
     -   **Incorrect**: While Python is often referred to as an interpreted language, it actually uses a combination of interpreting and compiling. Python code is first compiled into bytecode by the Python interpreter, which is then executed by the Python Virtual Machine (PVM). Therefore, Python does have a compiler, but it is not a traditional one that produces machine code directly; it compiles to an intermediate bytecode.
--------
 2.  What are true about programming paradigms and python? 
 - [ ] Imperative paradigm focuses on 'What' i.e. what program should accomplish
 - [ ] Declarative paradigm focuses on 'How' i.e. how to execute via seq. of commands 
 - [ ] Pascal, C languages are examples of Declarative paradigm 
 - [x] Makefiles, Prolog are of Declarative paradigm
 - [x] Imperative paradigm should follow during production ready SW design

Explaination: 
-   **Imperative paradigm focuses on 'What' i.e. what program should accomplish**
    
    -   **Incorrect**: The imperative paradigm focuses on **'How'** to execute a sequence of commands to achieve a specific result. It involves giving the computer a sequence of tasks to perform in order, detailing the control flow (e.g., using loops and conditionals).
-   **Declarative paradigm focuses on 'How' i.e. how to execute via seq. of commands**
    
    -   **Incorrect**: The declarative paradigm focuses on **'What'** the desired result is, rather than detailing the steps to achieve it. This paradigm describes what the program should accomplish without specifying the control flow or how to achieve it (e.g., SQL, HTML, functional programming).
-   **Pascal, C languages are examples of Declarative paradigm**
    
    -   **Incorrect**: Pascal and C are examples of **imperative** programming languages, not declarative. They focus on explicitly describing the sequence of commands to achieve the desired result.
-   **Makefiles, Prolog are of Declarative paradigm**
    
    -   **Correct**: Makefiles and Prolog are examples of declarative programming:
        -   **Makefiles**: Specify what should be built and the dependencies, but do not specify the exact sequence of steps to build them.
        -   **Prolog**: A logic programming language that specifies the relationships and constraints, allowing the system to determine how to achieve the goals.
-   **Imperative paradigm should follow during production ready SW design**
    
    -   **Correct**: The imperative paradigm is commonly used in production-ready software design because it allows precise control over the program's behavior and performance. It facilitates detailed and fine-grained control over how tasks are executed, which is often necessary for robust and efficient software development.
   
--------   
3.  What is true about various environments below? 
 - [x] core python comes with CPython interpreter as backend environment 
 - [x] Ipython is interactive shell for python commands 
 - [x] 'conda' is package manager to control python versions or mange it 
 - [x] Python useful IDE includes Spyder, PyScripter, PyCharm etc.

Explaination: 
-   **Core Python comes with CPython interpreter as backend environment**
    
    -   **Correct**: The standard implementation of Python is CPython, which is the reference implementation of the language. When you download and install Python from the official Python website, you are getting the CPython interpreter.
-   **IPython is an interactive shell for Python commands**
    
    -   **Correct**: IPython is an enhanced interactive shell that provides additional features compared to the default Python shell. It includes features such as syntax highlighting, auto-completion, and easy access to shell commands. IPython is commonly used within Jupyter Notebooks as well.
-   **'Conda' is a package manager to control Python versions or manage it**
    
    -   **Correct**: Conda is an open-source package management and environment management system. It can be used to manage Python packages, dependencies, and versions. Conda is especially popular in scientific computing and data science for managing complex software environments.
-   **Python useful IDE includes Spyder, PyScripter, PyCharm, etc.**
    
    -   **Correct**: Several integrated development environments (IDEs) are popular among Python developers, including:
        -   **Spyder**: An IDE particularly useful for scientific computing and data analysis, often used with Anaconda.
        -   **PyScripter**: A lightweight and fast Python IDE for Windows.
        -   **PyCharm**: A widely used professional IDE for Python development by JetBrains, offering a range of powerful features for code editing, debugging, and project management.

--------
4. What the print() statement will do?
 - [ ] it will print blank space
 - [x] it will print new line (enter) character
 - [ ] it will do nothing as no argument is specified
 - [ ] it will print double hollow parentheses like "()"
 - [ ] it is same as python "pass" keyword

Explaination: 
-   **It will print blank space**
    
    -   **Incorrect**: The `print()` function without any arguments does not print a blank space.
-   **It will print a new line (enter) character**
    
    -   **Correct**: The `print()` function without any arguments prints a newline character (`\n`). This results in moving the cursor to the next line in the console or terminal.
-   **It will do nothing as no argument is specified**
    
    -   **Incorrect**: The `print()` function does perform an action even without any arguments; it prints a newline character.
-   **It will print double hollow parentheses like "()"**
    
    -   **Incorrect**: The `print()` function without arguments does not print double hollow parentheses. It prints a newline character instead.
-   **It is the same as the Python `pass` keyword**
    
    -   **Incorrect**: The `print()` function and the `pass` keyword serve different purposes. The `pass` keyword is a null statement and does nothing when executed, while `print()` without arguments prints a newline character.


--------
5. finally = used with exceptions and will be executed irrespective of exception occurrence
Select one:
 - [x] True
 - [ ] False

Explanation : 
The `finally` block in Python is used in exception handling and is always executed, whether an exception occurs or not.

    try:
        print("Try block executed")
    
    finally:
        print("Finally block executed")



--------
6. from = used to import specific part of the module
Select one:
 - [x] True
 - [ ] False

Explanation: 
The `from` keyword is used to import specific parts of a module.
   
   

    from math import sqrt  
    print(sqrt(16))  
    #Output: 4.0

--------
7.  elif = used to handle elongated exception with conditioning ('if')
Select one:
 - [ ] True
 - [x] False

Explanation: 
The `elif` statement is used in conditional statements, not exception handling.

--------

8.  lambda = used to create function
Select one:
 - [x] True
 - [ ] False
 
Explanation: 
The `lambda` keyword is used to create small anonymous functions.

    square = lambda x: x * x
    print(square(5))  
    #Output: 25

--------
9.  with = used in exception handling with simplification
Select one:
 - [x] True
 - [ ] False

Explanation: 
The `with` statement is used to wrap the execution of a block with methods defined by a context manager, often simplifying exception handling.

    with open('example.txt', 'w') as file:
          file.write('Hello, World!')

The with statement simplifies exception handling by ensuring that resources are properly managed,
for example, closing a file after it is written to, regardless of whether an exception occurs or not.


--------
