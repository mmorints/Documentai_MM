![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## Calculator Documentation

**1. Overview:**

This Java program implements a simple command-line calculator. It takes two numbers as input from the user, along with an arithmetic operator (+, -, *, /), and then performs the chosen operation to calculate the result. The program also includes error handling to prevent division by zero.

**2. Package/module name:**

-  `default` (no explicit package declared)

**3. Class/file name:**

-  `Calculator.java`

**4. Detailed Documentation:**

**- `main(String[] args)`**

   - **Description:** This is the main method of the program, where execution begins. It prompts the user for input, performs the calculation, and displays the result.
   - **Parameters:**
      - `args`: An array of strings representing command-line arguments (not used in this program).
   - **Return Values:**
      - `void` (does not return a value)
   - **Important Logic:**
      - Creates a `Scanner` object to read user input from the console.
      - Prompts the user to enter two numbers and stores them in variables `a` and `b`.
      - Prompts the user to enter an arithmetic operator and stores it in the `op` variable.
      - Uses a `switch` statement to perform the calculation based on the operator:
         - `+`: Adds `a` and `b`.
         - `-`: Subtracts `b` from `a`.
         - `*`: Multiplies `a` and `b`.
         - `/`: Divides `a` by `b`, but checks if `b` is zero first. If it is, it prints an error message and exits the program using `return`.
      - If the operation is successful, it stores the result in the `result` variable and does not explicitly display it.

**5. Pseudo Code:**

```
// Class: Calculator

// Method: main(String[] args)
  1. Create a Scanner object to read user input.
  2. Prompt the user to enter the first number and store it in variable 'a'.
  3. Prompt the user to enter the second number and store it in variable 'b'.
  4. Prompt the user to enter an arithmetic operator and store it in variable 'op'.
  5. Use a switch statement to perform the calculation based on the value of 'op':
     - Case '+': Add 'a' and 'b', store the result in 'result'.
     - Case '-': Subtract 'b' from 'a', store the result in 'result'.
     - Case '*': Multiply 'a' and 'b', store the result in 'result'.
     - Case '/':
        - Check if 'b' is equal to zero.
        - If 'b' is zero:
           - Print an error message "Cannot divide by zero!".
           - Exit the program.
        - Otherwise: Divide 'a' by 'b', store the result in 'result'.
  6. End of switch statement.
  7. The program does not explicitly display the 'result'.



```



**Dependencies and Libraries:**

- **java.util.Scanner:** This class is used for reading user input from the console. It's a built-in part of the Java standard library.

**Equivalent Libraries in Other Languages:**

- **Python:** `input()` function for reading user input.
- **C++:** `std::cin` object for reading user input.



