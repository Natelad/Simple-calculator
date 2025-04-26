# Simple-Calculator Application

## Overview
This is a simple calculator application built using Python's Tkinter library. The application provides a graphical user interface (GUI) that allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. 

## Features
- Basic arithmetic operations: addition, subtraction, multiplication, division, and percentage.
- Parentheses support for grouping operations.
- Clear button to reset the input.
- Display of the current equation and result.

## Requirements
- Python 3.x
- Tkinter (comes pre-installed with Python)

## Installation
1. Ensure you have Python 3.x installed on your machine. You can download it from [python.org](https://www.python.org/downloads/).
2. Clone or download this repository to your local machine.
3. Navigate to the directory where the code is located.

## Usage
1. Open a terminal or command prompt.
2. Run the application by executing the following command:
   ```bash
   python calculator.py
   ```
3. The calculator window will appear, allowing you to input numbers and operations.
4. Use the buttons to enter numbers and operations. 
5. Press the `=` button to calculate the result.
6. Press the `c` button to clear the current input.

## Code Explanation
- The `Calculator` class initializes the main window and sets up the layout of buttons and the display.
- The `show` method updates the current equation displayed in the entry field.
- The `clear` method resets the input field.
- The `solve` method evaluates the current equation using Python's `eval()` function and displays the result.

## Important Notes
- The use of `eval()` can be dangerous if the input is not controlled, as it can execute arbitrary code. This implementation is for educational purposes and should be modified for production use to ensure safety.
- The calculator currently does not handle errors (e.g., division by zero). Consider adding error handling for a more robust application.

## License
This project is open-source and available for personal and educational use. Please feel free to modify and enhance the code as needed.

## Acknowledgments
- This project utilizes the Tkinter library for creating the GUI.
- Special thanks to the Python community for their continuous support and resources.

Created by Natelad.
