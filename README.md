Description of Task-1:

**Overview**

The BasicCalculator is a command-line Java application designed to perform a variety of numeric operations. It enables users to input two numbers and choose from several mathematical operations, including addition, subtraction, multiplication, division, modulo, floor, and round. The program calculates and displays results based on the selected operation.

**Features**

1. Arithmetic Operations:

Addition: Computes the sum of two numbers.

Subtraction: Computes the difference between two numbers.

Multiplication: Computes the product of two numbers.

Division: Computes the quotient of two numbers, with error handling for division by zero.

Modulo Operation:Computes the remainder when the first number is divided by the second number, with error handling for modulo by zero.

2. Floor Operation:Computes the floor value of the first number, which is the largest integer less than or equal to that number.

3. Round Operation:Rounds the first number to the nearest integer.


**How It Works**

1. User Input:
The program prompts the user to enter two numbers (num1 and num2) for numeric operations.
It then asks the user to select an operation from a menu.

2. Operation Selection:
The user selects an operation by entering a number corresponding to the desired operation.

3. Operation Execution:
Based on the user’s selection, the program performs the appropriate operation and displays the result:
 
  i)Addition: Adds num1 and num2.

  ii)Subtraction: Subtracts num2 from num1.
  
  iii)Multiplication: Multiplies num1 and num2.
  
  iv)Division: Divides num1 by num2 and handles division by zero.
  
  v)Modulo: Computes the remainder of num1 divided by num2 and handles modulo by zero.
  
  vi)Floor: Computes the floor of num1, which is the greatest integer less than or equal to num1.
  
  vii)Round: Rounds num1 to the nearest integer.

5. Error Handling:
The program checks for division by zero and modulo by zero, providing appropriate error messages when these cases occur.
If the user selects an invalid operation, the program notifies them of the error.


**Code Structure**

1. Imports:
import java.util.Scanner; is used to handle user input.

2. Main Class and Method:
The BasicCalculator class contains the main method, which drives the program.

 3.User Input Handling:
 The Scanner object is used to read input values for the numbers and the operation selection.

 4.Switch Statement:
 The switch statement is used to perform different operations based on user input.
 Each case in the switch statement handles a specific operation and outputs the result.

 5.Mathematical Operations:
 Basic arithmetic operations (+, -, *, /), modulo operation (%), and methods from the Math class (Math.floor, Math.round) are used for calculations.

**Result**
![task-1](https://github.com/user-attachments/assets/bcfe0115-d15a-489a-8266-db46f85fa611)


![how to record screen in windows 10 - Google Search - Google Chrome 01-09-2024 12_28_37](https://github.com/user-attachments/assets/047c6532-c128-4fc0-bc90-a1df9745d32f)

