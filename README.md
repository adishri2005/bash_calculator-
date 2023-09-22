# bash_calculator-

The provided code is a Bash script named `calculator.sh`, which functions as a simple command-line calculator. It allows the user to perform basic arithmetic operations (addition, subtraction, multiplication, and division) on two numbers. Below is a description of the code's functionality:

1. The script begins with a shebang line (`#!/bin/bash`), indicating that it should be executed using the Bash shell.

2. It defines four functions for performing arithmetic operations:
   - `add()`: Takes two arguments, calculates their sum, and displays the result.
   - `subtract()`: Takes two arguments, calculates their difference, and displays the result.
   - `multiply()`: Takes two arguments, calculates their product, and displays the result.
   - `divide()`: Takes two arguments, calculates their quotient (with error checking for division by zero), and displays the result or an error message.

3. The main part of the script begins with a series of echo statements to display a menu to the user:
   - "Simple Calculator"
   - "1. Add"
   - "2. Subtract"
   - "3. Multiply"
   - "4. Divide"

4. The script prompts the user to enter their choice (1, 2, 3, or 4) for the desired arithmetic operation using the `read` command.

5. The user is then prompted to enter two numbers, which are stored in the variables `num1` and `num2`.

6. A `case` statement is used to determine which arithmetic operation to perform based on the user's choice:
   - If the user selects 1, it calls the `add` function with `num1` and `num2` as arguments.
   - If the user selects 2, it calls the `subtract` function.
   - If the user selects 3, it calls the `multiply` function.
   - If the user selects 4, it calls the `divide` function.
   - If the user enters any other choice, it displays "Invalid choice."

7. The chosen arithmetic operation is executed, and the result or an error message is displayed to the user.

This script provides a simple interactive command-line calculator that allows users to perform basic arithmetic calculations with ease.
