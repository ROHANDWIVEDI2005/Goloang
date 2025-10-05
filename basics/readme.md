# `Note`
- If you are runnig the code in this directiory your code editor may show you error in the main function that's because you have more than one go file in this directory containing a main fucntion
In Go, all files within a single directory are considered to be part of the same package. For an executable program (defined by package main), there can only be one main function to act as the program's 
entry point. The compiler sees two entry points and doesn't know which one to use, so it throws a "main redeclared" error.
- **To solve this simply run the `go [program you want to run]`command in your terminal make sure you are in the directory where the program file exists**
