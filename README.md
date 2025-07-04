# CodSoft-Task-2
Name: Priyanshi Bansal 
Company: CodSoft 
Batch: B33
Duration:10 June 2025 to 10 July 2025 
**Overview of the Project**
Project: Basic Calculator Implementation in Python.
Objective:
To develop a simple Python-based calculator that performs basic arithmetic operations such as addition, subtraction, multiplication, and division through user input.
Key Activities:
1.Display Program Title
print("Simple Calculator")
Displays a simple title indicating the program's purpose.
2.Accept User Input for Numbers
Prompts the user to input two numeric values and converts them to float for decimal support.
3.Validate Numeric Input Using Try-Except
Catches any invalid (non-numeric) input and gracefully exits with an error message.
4.Display Operation Menu
Provides the user with a list of four basic arithmetic operations to choose from.
5.Capture User’s Operation Choice
Accepts the user's selection of an arithmetic operation (1/2/3/4).
6.Perform Arithmetic Operation Based on User Choice
Uses conditional statements to determine which operation to perform based on the user's input.
7.Handle Division by Zero
Specifically checks for division by zero and prevents the program from crashing.
8.Display the Final Result
Outputs the complete arithmetic expression and result in a formatted manner.
Technologies & Concepts Used:
1. Programming Language
Python:
The entire code is written in the Python programming language.
2. Input/Output Functions
input() Function:
Used to take user input from the console.
print() Function:
Used to display messages and results to the user.
3. Type Conversion
float():
Converts the user input (which is a string by default) into a floating-point number.
4. Exception Handling
try-except Block:
Used to handle errors (specifically, ValueError) that may occur if the user enters non-numeric input.
5. Conditional Statements
if-elif-else Statements:
Used to select the arithmetic operation based on user input and to handle invalid choices.
6. Arithmetic Operations
Addition (+), Subtraction (-), Multiplication (*), Division (/):
Basic arithmetic operations performed on the input numbers.
7. Exit Function
exit():
Used to terminate the program if an error occurs (like invalid input or division by zero).
8. Formatted String Literals (f-strings)
f"" Strings:
Used to format and display the result in a readable way.
Key Insights:
1.User-Friendly Interaction:
The program provides a clear, step-by-step interface for users to input two numbers and select an arithmetic operation (addition, subtraction, multiplication, division).
2.Input Validation:
It uses exception handling to check if the user inputs are valid numbers. If not, the program displays an error and exits, preventing runtime errors and improving robustness.
3.Error Handling for Division:
The code specifically checks for division by zero and handles it gracefully by displaying an error message and stopping execution, which is important for preventing crashes or undefined behavior.
4.Conditional Logic:
The program uses if-elif-else statements to determine which arithmetic operation to perform based on the user's choice, ensuring only valid operations are executed.
5.Formatted Output:
The result is displayed using formatted strings, making the output clear and easy to understand.
6.Simplicity and Readability:
The code is straightforward and easy to follow, making it suitable for beginners learning about user input, conditionals, and exception handling in Python.
7.Extensibility:
While the program currently supports four basic operations, its structure allows for easy extension to add more operations in the future.
