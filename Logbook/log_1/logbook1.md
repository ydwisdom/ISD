- [Introduction to programming part 1](#introduction-to-programming-part-1)
  - [Section 1: Setting Up a Code Editor and Running Python Scripts](#section-1-setting-up-a-code-editor-and-running-python-scripts)
  - [Exercise 2: Running a Script Using the Command Line](#exercise-2-running-a-script-using-the-command-line)
- [Section 2: Python Introduction](#section-2-python-introduction)
- [Exercise 1: Variables and Types](#exercise-1-variables-and-types)


# Introduction to programming part 1

Setup PC to run small python examples.
Topics include: Visual Studio Code, Running Python Code, Variables, Operators, Print, Casting, Strings, f-Strings

## Section 1: Setting Up a Code Editor and Running Python Scripts

Setup Visual studio code with extensions.
Check Python is installed.

## Exercise 2: Running a Script Using the Command Line

Needed to check that the terminal was open to the folder which contained the code.  Then tried two alternative ways of starting python from the command line.

```console
PS C:\Users\B01834170\Documents\GitHub\ISD\Sessions\session_1> python lab_week_1.py
Python was not found; run without arguments to install from the Microsoft Store, or disable this shortcut from Settings > Apps > Advanced app settings > App execution aliases.
PS C:\Users\B01834170\Documents\GitHub\ISD\Sessions\session_1> py lab_week_1.py
Hello. Welcome to the ISD Module.
This program has been run successfully.
Welcome to the ISD module. There are 20 students in this class.
Welcome to the ISD module. There are 20 students in this class.
PS C:\Users\B01834170\Documents\GitHub\ISD\Sessions\session_1>
```

Python starts from command line using Py command.  But for rest of module we will click on the run icon to start.

# Section 2: Python Introduction

Work with variables.

# Exercise 1: Variables and Types

Confirm that variables have different types.

**Task 1**

Identify types of variables

```python
#%%
# Exercise 1 task: Variables and Types

var_1 = True # Type = bool
var_2 = 1 # Type = int
var_3= 3.14159 # Type = float
var_4 = "Hello" # Type = string

print(type(var_1))
print(type(var_2))
print(type(var_3))
print(type(var_4))
```
Produces output

```console
<class 'bool'>
<class 'int'>
<class 'float'>
<class 'str'>
```

**Task 2**

1. Create a variable called my_int and assign it the value 5.
2. Create a variable called my_float and assign it the value 5.5.
3. Create a variable called my_bool and assign it the value True.
4. Print the value of each variable.
5. Cast my_int to a float and store the result in a variable called my_int_float.
6. Cast my_float to an integer and store the result in a variable called my_float_int.
7. Cast my_bool to an integer and store the result in a variable called my_bool_int.
8. Print the value of each variable.

