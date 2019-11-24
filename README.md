# ITFDN100-Mod07
 #### Files for Module 7

 Date: 11.21.19
 
 Descprition: File & Assignemnet documents for Module07
 
 Dev: Kstevens
 
 ITFDN100 A
 
 Assignment07
 
## Reference Docs for Module07
 
 _Mod7PythonProgrammingNotes.pdf | https://canvas.uw.edu/courses/1342958/modules/items/9973246
 
 Lab7-1_Starter.py | https://canvas.uw.edu/courses/1342958/modules/items/9973388
 
 Assignment07.pdf | https://canvas.uw.edu/courses/1342958/modules/items/9973247
 
 Module07 Course Video  | https://youtu.be/4IkIdXJBC6o
 


## Topics Covered in ITFDN100 Mod07

- Benefits of putting built-in Python command into functions
- Benefits of using structured error handling
- Differences between a text file and a binary file
- How Exception class is used
- How to "derive" a new class from the Exception class
- Creating a class derived from Exception classes
- Markdown languages
- Using Markdown on a GitHub webpages

```
# ------------------------------------------------------------------------ #
# Title: Assignment 07
# Description: Research Exception Handling & Pickling in Python
# ChangeLog (Who,When,What):
# Kstevens,11-20-19,Modified code to complete assignment 7
# ------------------------------------------------------------------------ #
# Research source: Python Tutorial: Using Try/Except Blocks for Error Handling,
# https://www.youtube.com/watch?v=NIWwJbo-9_8
# Research source (other/related to above): code_snippets/Exceptions/,
# https://github.com/CoreyMSchafer/code_snippets/tree/master/Exceptions
# Research topic: Exception Handling
# Code Version 7.3
# Example description: *Modifies the code found in example 7.2 
# (which was created from code in 7.1) to achieve the 
# requested Output Requirements described in Example 7.3 in Assignment07.docx or 
# on the my GitHub Webpage @ https://ksteve3.github.io/ITFDN100-Mod07/ under 
# Example 3 Output requirements

try:
    file = open('test_file.txt')
    var = bad_var
except FileNotFoundError as e:
    print(e)
except Exception as e:
    print(e)
else:
    print(file.read())
    file.close()
finally:
    print('Closing File/Database...')  # Indicates completion of "something that needs to get done" by displaying
    # final closeout message/ final closeout step(s) executed to user regardless if the code is successful or not.
```
