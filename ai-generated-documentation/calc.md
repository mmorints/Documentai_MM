![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## Calculator Documentation

**1. Overview:** 

This Java program implements a simple command-line calculator that performs basic arithmetic operations (+, -, *, /) on two numbers provided by the user. It includes error handling for division by zero.

**2. Package/module name:**  `java.util` (for `Scanner`)

**3. Class/file name:** `Calculator.java`

**4. Detailed Documentation:**

   - **Function/Method: `main(String[] args)`**
     - **Description:** This is the entry point of the program. It initializes a `Scanner` object to read user input, prompts the user for two numbers and an operation, performs the calculation based on the chosen operation, and displays the result.
     - **Parameters:** 
       - `String[] args`: Command-line arguments (not used in this program).
     - **Return Values:** None.
     - **Important Logic:**
       - Uses a `Scanner` to read user input for two numbers and an operation character.
       - Uses a `switch` statement to perform the calculation based on the chosen operation.
       - Handles division by zero by checking if the second number is zero before performing the division. If it is, it prints an error message and exits the program using `return`.

   - **Function/Method: `calculate(double a, double b, char op)`** (This function could be extracted for better code organization)
     - **Description:** This function performs the actual calculation based on the given operation. 
     - **Parameters:**
       - `a`: The first number.
       - `b`: The second number.
       - `op`: The operation character (+, -, *, /).
     - **Return Values:**  The result of the calculation as a double.
     - **Important Logic:**
       - Uses conditional statements (`if`, `else if`) to perform the calculation based on the `op` parameter.

**5. Pseudo Code:**

```
// Class: Calculator

// Method: main(String[] args)
  1. Create a Scanner object to read user input.
  2. Print "Simple Java Calculator" message.
  3. Prompt the user to enter the first number and store it in variable 'a'.
  4. Prompt the user to enter the second number and store it in variable 'b'.
  5. Prompt the user to choose an operation (+, -, *, /) and store it in variable 'op'.
  6. Use a switch statement based on the value of 'op':
     - Case '+': Add 'a' and 'b', store the result in 'result'.
     - Case '-': Subtract 'b' from 'a', store the result in 'result'.
     - Case '*': Multiply 'a' and 'b', store the result in 'result'.
     - Case '/': 
        - Check if 'b' is equal to zero.
          - If yes, print "Cannot divide by zero!" and exit the program.
          - If no, divide 'a' by 'b', store the result in 'result'.
  7. Print the calculated result.

```



**Dependencies and Libraries:**

* **java.util.Scanner:** This class is used for reading user input from the console. 


Let me know if you have any other questions or need further clarification on any aspect of this documentation.