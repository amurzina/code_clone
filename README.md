# Code clones detector

1. uses yacc for python
2. implemented for c grammar

### How it works:  
Based on C grammar builds an Abstract Syntax Tree for each file given to the program argv's. The tree is modified to more abstract by deleting extra information like variables values, function names and so on. Next counts Tree Edit Distance like how difficult to rebuild one tree to another. The bigger number we get the more unique code is.
