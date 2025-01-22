Basic Calculator

A basic calculator built with JavaScript that performs addition, subtraction, multiplication, and division. It also handles division by zero and invalid operations.
Features

    Addition: Adds two numbers.
    Subtraction: Subtracts one number from another.
    Multiplication: Multiplies two numbers.
    Division: Divides one number by another (with a check for division by zero).
    Error Handling: Returns a message if the operation is invalid or division by zero is attempted.

Demo

You can use this function to calculate results by passing two numbers and an operation as parameters. Example usage:

console.log(calculate(5, 10, "+"));  // Output: The result is 15
console.log(calculate(5, 0, "/"));   // Output: Division by zero is not allowed
console.log(calculate(5, 10, "x"));  // Output: Invalid operation

Function: calculate(num1, num2, operation)
Parameters:

    num1 (Number): The first number.
    num2 (Number): The second number.
    operation (String): The operation to perform. It can be one of:
        "+" for addition
        "-" for subtraction
        "*" for multiplication
        "/" for division

Returns:

    A string message with the result of the calculation or an error message if the operation is invalid or division by zero is attempted.

Example Usage

console.log(calculate(5, 10, "+"));  // The result is 15
console.log(calculate(5, 0, "/"));   // Division by zero is not allowed
console.log(calculate(5, 10, "x"));  // Invalid operation

Installation

    Clone the repository:
[
git clone https://github.com/diabolele/basiccalculatorjs

Navigate into the project directory:

    cd basic-calculator

    Open the index.html file in your browser or run the JavaScript file with Node.js.

License

This project is licensed under the MIT License - see the LICENSE file for details.
