# PPL Assignment
Implemeting a parser for a language specifiaction given in our course "Principles of Programming Languages" in C.

# Language Description
The included PDF file contains the language descirption.

# Using this repo
Clone this repo, use the command 
'''make compileAll''' in the terminal to compile all the files.

Then, use '''make run''' to run the program. Make sure the file '''sourcecode.txt''' is present in the directory with the code you want to parse.

The program runs in a loop. Everytime it asks you to enter an option, you can do any one of the five tasks
- Option 0: Exits
- Option 1: Creates parse tree
- Option 2: Traverses the parse tree to construct typeExpressionTable. Also print the type errors while
  traversing the parse tree and accessing the typeExpressionTable.
- Option 3: Prints parse tree in the specified format
- Option 4: Prints typeExpressionTable in the specified format.
