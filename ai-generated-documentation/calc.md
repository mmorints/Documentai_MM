![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## Calculator Documentation



**2. Package/module name:**

-  `default` (no explicit package declared)

**3. Class/file name:**

-  `Calculator.java`



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



