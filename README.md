# PPL Assignment
This repo contains implementation of a parser for a language specifiaction given in our course "Principles of Programming Languages" in C. It uses various data structures like linked list, stack and hash table, all of which have been implemented from scratch.

# Language Description
The included PDF file ```assignment 1.pdf``` contains the language descirption.

# Using this repo
Clone this repo, move inside the ```PPL-Assignment``` directory, use the command ```make compileAll``` in the terminal to compile all the files.

Then, use ```make run``` to run the program. By default, the program searches for ```sourcecode.txt``` to get the code, so make sure this file is present in the directory.

A few test cases have been included in the ```testcases``` directory inside ```PPL-Assignment```.

The program runs in a loop. Everytime it asks you to enter an option, you can do any one of the five tasks
- Option 0: Exits
- Option 1: Creates parse tree
- Option 2: Traverses the parse tree to construct typeExpressionTable. Also print the type errors while
  traversing the parse tree and accessing the typeExpressionTable.
- Option 3: Prints parse tree in the specified format
- Option 4: Prints typeExpressionTable in the specified format.
