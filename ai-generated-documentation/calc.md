![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## Calculator Documentation

**1. Overview:**

This Java program implements a simple command-line calculator. It takes two numbers as input from the user, along with an arithmetic operator (+, -, *, /), and then performs the calculation, displaying the result. The program includes basic error handling to prevent division by zero.

**2. Package/module name:**  `default`

**3. Class/file name:** `Calculator.java`

**4. Detailed Documentation:**

**- `main(String[] args)`:**

   - **Description:** This is the main method of the program, where execution begins. It prompts the user for input, performs the calculation, and displays the result.
   - **Parameters:** `String[] args`: An array of strings representing command-line arguments (not used in this program).
   - **Return Values:** `void`: The method does not return any value.
   - **Important Logic:**
     - Creates a `Scanner` object to read user input from the console.
     - Prompts the user to enter two numbers and stores them in variables `a` and `b`.
     - Prompts the user to enter an arithmetic operator and stores it in the `op` variable.
     - Uses a `switch` statement to perform the calculation based on the operator:
       - `+`: Adds `a` and `b`.
       - `-`: Subtracts `b` from `a`.
       - `*`: Multiplies `a` and `b`.
       - `/`: Divides `a` by `b`, handling the case where `b` is zero by printing an error message and exiting the program.
     - Displays the result of the calculation.

**5. Pseudo Code:**

```
// Class: Calculator

// Method: main(String[] args)
  1. Create a Scanner object to read user input.
  2. Prompt the user to enter the first number and store it in variable 'a'.
  3. Prompt the user to enter the second number and store it in variable 'b'.
  4. Prompt the user to enter an arithmetic operator and store it in variable 'op'.
  5. Use a switch statement to perform the calculation based on the value of 'op':
    - Case '+':
      - Add 'a' and 'b' and store the result in variable 'result'.
    - Case '-':
      - Subtract 'b' from 'a' and store the result in variable 'result'.
    - Case '*':
      - Multiply 'a' and 'b' and store the result in variable 'result'.
    - Case '/':
      - Check if 'b' is equal to zero.
        - If 'b' is zero:
          - Print an error message "Cannot divide by zero!".
          - Exit the program.
        - If 'b' is not zero:
          - Divide 'a' by 'b' and store the result in variable 'result'.
    - End of switch statement.
  6. Display the value of 'result'.
```



**Dependencies and Libraries:**

- **java.util.Scanner:** This class is used for reading user input from the console. It is a built-in library in Java.

**Equivalent Libraries in Other Languages:**

- **Python:** `input()` function for reading user input.
- **C++:** `std::cin` object for reading user input.



