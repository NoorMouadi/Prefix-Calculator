# *Prefix Calculator*

## *Overview*
This program is designed as a prefix calculator that supports operations on mathematical equations expressed in infix notation. The calculator includes functionality for validating equations, converting infix expressions to prefix (Polish) notation, and evaluating the expressions in prefix notation. It is built using data structures such as stacks and linked lists, enabling efficient manipulation of operators and operands.

The program performs multiple tasks, including:
Checking the validity of mathematical equations.
Converting valid equations from infix to prefix notation.
Evaluating prefix expressions.
Printing invalid equations with specific reasons for their invalidity.
Reading input from files and outputting results to a file.


This project emphasizes good practices in algorithm design, data structure manipulation, and file handling in C.

## *Features*
- *Validation*: Verifies whether an equation is valid based on proper placement of operators, digits, and parentheses.
- *Conversion*: Converts infix expressions into prefix notation, maintaining proper operator precedence.
- *Evaluation*: Evaluates expressions in prefix notation, handling all basic arithmetic operations (+, -, *, /).
- *Parentheses Handling*: Supports balanced parentheses validation and reversal.
- *File Input/Output*: Allows reading equations from a file and writing results to a file.
- *Menu Options*: Interactive command-line menu to choose the operation to perform.

## *How to Use*

### *1. Compilation and Execution*
To compile the C source code, open a terminal window and run the following command:

```bash
gcc -o prefix_calculator prefix_calculator.c
