# Python Tkinter Calculator

## 1. Introduction
The Tkinter Calculator is a simple graphical user interface (GUI) application developed using Python. It allows users to perform basic arithmetic operations through an interactive interface. The project demonstrates the use of Tkinter widgets, functions, button events, and conditional statements in Python programming.

## 2. Objective
The main objective of this project is to develop a basic calculator using Python and understand the implementation of GUI applications using the Tkinter library.

## 3. Features
- User-friendly graphical interface.
- Buttons for entering numbers from 0 to 9.
- Supports addition, subtraction, multiplication, and division.
- Displays the calculated result using the equals button.
- Provides a clear button to erase the current input.

## 4. Technologies Used
- **Programming Language:** Python
- **GUI Library:** Tkinter
- **Development Environment:** Any Python-supported IDE, such as IDLE, VS Code, or PyCharm.

## 5. Working Principle
The calculator uses an entry box to accept numerical input from the user. When a number button is clicked, the corresponding digit is displayed in the entry box. When an arithmetic operator is selected, the first number and the selected operation are stored. The user then enters the second number and presses the equals button to calculate and display the result. The clear button removes the current input from the entry box.

## 6. Implementation
The project is implemented using the following components:

- **Tk():** Creates the main application window.
- **Entry():** Displays the numbers and calculation results.
- **Button():** Creates buttons for numbers and arithmetic operations.
- **Functions:** Handle button clicks, arithmetic operations, and clearing the input.
- **Conditional Statements:** Identify the selected arithmetic operation and calculate the result.
- **mainloop():** Keeps the calculator window active and responsive to user interactions.

## 7. How to Run the Project
1. Install Python 3.x on your system.
2. Ensure that the Tkinter library is available.
3. Save the source code in a file named `calculator.py`.
4. Open the terminal or command prompt in the project directory.
5. Execute the following command:

   ```bash
   python calculator.py
   ```

6. The calculator window will open, allowing the user to perform basic arithmetic calculations.

## 8. Limitations
- The calculator supports only basic arithmetic operations.
- It works with integer inputs for the entered numbers.
- It does not include advanced mathematical functions.
- Division by zero is not handled explicitly.

## 9. Conclusion
This project demonstrates the development of a basic calculator using Python's Tkinter library. It provides practical experience with GUI design, event handling, functions, and arithmetic operations. The project also serves as a foundation for developing more advanced GUI-based applications in Python.

## 10. Future Scope
The calculator can be improved by adding decimal number support, keyboard input, backspace functionality, advanced mathematical operations, and error handling for invalid inputs and division by zero.
