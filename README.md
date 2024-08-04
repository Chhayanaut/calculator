# Calculator Program

This is a simple calculator program written in Python. It performs basic arithmetic operations such as addition, subtraction, multiplication, and division. The calculator allows the user to perform multiple operations in sequence, using the result of the previous operation as the starting point for the next one.

## Features

- Addition
- Subtraction
- Multiplication
- Division

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Chhayanaut/calculator.git
    cd calculator
    ```

2. **Ensure Python is installed**:  
   Make sure you have Python installed on your system. You can download it from the [official Python website](https://www.python.org/downloads/).

## Usage

To use the calculator, simply run the Python script. You can do this from the command line:

```bash
python calculator.py
```

Follow the on-screen prompts to enter numbers and select operations.

### Example

1. **Start the program** and enter the first number when prompted.
   
   ```
   What is the first number?: 10
   ```

2. **Choose an operation** from the available options:

   ```
   +
   -
   *
   /
   Pick an operation from the line above: *
   ```

3. **Enter the second number**:

   ```
   What is the second number?: 5
   ```

4. **See the result**:

   ```
   10.0 * 5.0 = 50.0
   ```

5. **Continue or start a new calculation**:
   
   ```
   Type 'y' to continue calculating with 50.0, or type 'n' to start a new calculation: y
   ```

## Code Explanation

Here's a brief overview of the main components of the code:

- **Imports**:
  - The program imports a logo from a separate module or file called `art`. Make sure to have this file in the same directory as the script.

- **Functions**:
  - `add(n1, n2)`: Returns the sum of two numbers.
  - `subtract(n1, n2)`: Returns the difference between two numbers.
  - `multiply(n1, n2)`: Returns the product of two numbers.
  - `divide(n1, n2)`: Returns the quotient of two numbers.

- **Dictionary of Operations**:
  - Maps each arithmetic symbol to its corresponding function for easy selection during execution.

- **Calculator Function**:
  - Handles user input, performs the calculations, and manages the loop for continued use or reset.

## Customization

Feel free to modify the script to add more features or improve functionality. You might want to add error handling for invalid inputs or extend the calculator with additional operations like modulus, exponentiation, etc.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on GitHub.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

### Note
Ensure the `art` module or file is available in your project directory. If it contains a logo or ASCII art, you can customize it to suit your preferences.

---

This README provides an overview of the calculator program, guides the user on how to set it up and run it, and offers insights into the code and how to contribute. Adjust the text to better fit your actual repository details and any specific instructions you may have for users.
