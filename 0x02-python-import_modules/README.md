# Python Import & Modules
## General
- Why Python programming is awesome
- Howe to import functions from another file
- How to use importted functions
- How to create a module
- How to use the built-in function dir()
- How to prevent code in the script from being executed when imported
- How to use command line arguments with Python programs
## Requirements
### General
- Alllowed editors: vi, vim, emacs
- All the files will be interpreted/compiled on Ubuntu 20.04 LTS using python3(version 3.8.5)
- All files should end with a new line
- The first line of every file should be #!/usr/bin/python3
- A README.md file, at the root of this folder of the project
- The code should use the pycodestyle(version2.7.*)
- All the files should be executable
- The length of the files will be tested using wc
## Tasks 0. Import a simple function from a simple file
### filename: 0-add.py
Imports the function def add(a, b): from the file add_0.py and prints the result of the addition 1 + 2 = 3.
- The print function should be usued with string format to display integers
- the asteric * should not be used for imporint of __import__
- The code should not be executed when imported -by using __import__
## Task 1. My first toolbox
### filename: 1-calculation.py
Imports functions from the file calculator_1.py, does some Maths, and prints the result
- Do not use the print() more than four times.
- The code should not be executed when imported by using __import__
## Task 2. How to make a script dynamic
### filename: 2-args.py
Prints the number of and the list of arguments to the program.
- The code should not be executed when imported.
## Task 3. Infinite addition
### filename: 3-infinite_add.py
The program prints the result of the addition of all arguments.
- The output should be the result of the addition of all arguments, followed by a new line.
- The code should not be executed when imported.
## Task 4. Who are you?
### filename: 4-hidden_discovery.py
The program prints all the names defined by the compiled hidden_5.pyc file.
- Print one nme per line, in alpha order
- Print only names that do not start with __
- The code should not be executed when imported
- hidden_4.pyc has been compiled with Python 3.8.x
## task 5. Everything can be imported
### filename: 5-variable_load.py
Imports the variable a from the file varaible_load_5.py and prints its value.
- asterik * and __import__ should not be used
- The code should not be executed when imported
