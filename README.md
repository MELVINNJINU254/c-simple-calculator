# Simple Calculator in C

A beginner-friendly console-based calculator application built in C as a first project for learning the fundamentals of C programming.

## 📋 Description

This is a simple command-line calculator that performs basic arithmetic operations. It demonstrates fundamental C programming concepts including user input/output, control structures, functions, and error handling.

## ✨ Features

- **Basic Arithmetic Operations:**
  - Addition (+)
  - Subtraction (-)
  - Multiplication (*)
  - Division (/)

- **Continuous Operation:** Calculate multiple times without restarting the program
- **Error Handling:** Prevents division by zero
- **User-Friendly Interface:** Clear prompts and formatted output with 2 decimal places

## 🚀 Getting Started

### Prerequisites

- GCC compiler (or any C compiler)
- Terminal/Command prompt

### Compilation

```bash
gcc calculator.c -o calculator
```

### Running the Program

```bash
./calculator
```

## 💻 Usage

1. Run the program
2. Enter the first number
3. Enter an operator (+, -, *, /)
4. Enter the second number
5. View the result
6. Choose whether to perform another calculation (1 for yes, 0 for no)

### Example

```
=== Simple Calculator ===
Enter first number: 10
Enter operator (+, -, *, /): *
Enter second number: 5
10.00 * 5.00 = 50.00

Do you want to perform another calculation? (1 for yes, 0 for no): 1
Enter first number: 100
Enter operator (+, -, *, /): /
Enter second number: 4
100.00 / 4.00 = 25.00

Do you want to perform another calculation? (1 for yes, 0 for no): 0
Thank you for using the calculator!
```

## 🔧 Code Structure

### Key Components

- **Variables:** Uses `double` for decimal number support and `char` for operators
- **Input/Output:** `scanf()` for user input, `printf()` for displaying results
- **Control Flow:**
  - `while` loop for continuous operation
  - `switch` statement for operation selection
  - `if-else` for error handling
- **Error Handling:** Checks for division by zero

### Main Functions

- `main()`: Entry point of the program, contains the calculator logic

## 📚 Learning Objectives

This project covers:

- ✅ Variable declaration and initialization
- ✅ User input/output operations
- ✅ Conditional statements (if-else)
- ✅ Switch statements
- ✅ While loops
- ✅ Basic arithmetic operations
- ✅ Error handling
- ✅ Program flow control

## 🎯 Future Enhancements

Ideas to extend this project:

- [ ] Add modulus (%) operation
- [ ] Implement power and square root functions
- [ ] Create separate functions for each operation
- [ ] Add input validation for non-numeric entries
- [ ] Implement calculation history
- [ ] Support for parentheses and complex expressions
- [ ] Add scientific calculator functions (sin, cos, tan, log, etc.)

## 🛠️ Built With

- **Language:** C
- **Libraries:** stdio.h

## 📖 What I Learned

- Basic C syntax and structure
- Working with different data types
- Handling user input and output
- Using control structures effectively
- Implementing error handling
- The difference between loops (repetition) and selection statements (choices)

## 🤝 Contributing

This is a learning project, but suggestions and improvements are welcome! Feel free to fork and experiment.

## 📝 License

This project is open source and available for educational purposes.

## 👨‍💻 Author

Melvin

---

*This calculator was built as part of my journey learning C programming, focusing on understanding core concepts before moving to more advanced topics.*
