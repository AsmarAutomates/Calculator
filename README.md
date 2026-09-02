
**Simple Java Calculator:**

A simple command-line calculator built in Java. This program allows the user to enter two numbers and choose an arithmetic operation to calculate the result.

**Features:**
Addition
Subtraction
Multiplication
Division
Division-by-zero protection
User input through the console using Scanner
Handles invalid operation choices
Technologies Used
Java
Java Scanner for user input
How It Works

**The program:**

Prompts the user to enter the first number.
Prompts the user to enter the second number.
Displays a menu of available operations.
Asks the user to select an operation.
Performs the selected calculation.
Displays the result.
Prevents division by zero.
Closes the Scanner when the program finishes.

**Available Operations:**
Choice	Operation	Example
1	Addition	10 + 5 = 15
2	Subtraction	10 - 5 = 5
3	Multiplication	10 * 5 = 50
4	Division	10 / 5 = 2

Example Output
Enter the first number
10
10.0
Enter the second number
5
5.0
Choose an operation
1. Addition
2. Subtraction
3. Multiplication
4. Division
1
1
Result:15.0

Division by Zero

The program checks whether the second number is 0 before performing division.

Enter the first number
10
Enter the second number
0
Choose an operation
1. Addition
2. Subtraction
3. Multiplication
4. Division
4
ERROR:Division by zero is not allowed

Project Structure
project/
└── src/
    └── day3/
        └── Calculator.java

**How to Run**
1. Clone or download the project

Download the project to your computer or clone the repository.

2. Open the project

Open the project in a Java-compatible IDE such as IntelliJ IDEA, Eclipse, or Visual Studio Code.

3. Run the program

Run the Calculator.java file.

Alternatively, from the terminal:

javac Calculator.java
java day3.Calculator

Concepts Practiced

**This project demonstrates several fundamental Java concepts:**

Scanner for reading user input
Variables and data types such as double and int
if, else if, and else statements
Arithmetic operators
Comparison operators
Basic error handling
Closing resources with scanner.close()
Future Improvements
  
**Some possible improvements include:**

Add a loop so the user can perform multiple calculations.
Add support for more operations such as modulus and exponentiation.
Improve input validation for non-numeric input.
Use a switch statement instead of multiple if/else if statements.
Add a menu option to exit the program.
Format decimal results to a fixed number of decimal places.
License

