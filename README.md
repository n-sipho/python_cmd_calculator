# Command Line Calculator

A simple Python-based calculator designed to run from the terminal. It allows users to perform basic arithmetic operations quickly without opening a graphical interface.

## Overview

This project is a lightweight command-line application for evaluating mathematical expressions. It is ideal for learning Python fundamentals such as:

- user input handling
- basic arithmetic logic
- validation and error handling
- CLI command execution

## Features

- Addition
- Subtraction
- Multiplication
- Division
- Modulo calculation
- Exponentiation
- Integer and floating-point arithmetic
- Clear error messages for invalid input

## Requirements

- Python 3.8 or later

## Installation

1. Open a terminal and navigate to the project directory:

   ```bash
   cd /path/to/cmd_calculator
   ```

2. (Optional) Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   source .venv/bin/activate   # Linux/macOS
   .venv\Scripts\activate      # Windows
   ```

3. Run the program:

   ```bash
   python calculator.py
   ```

## Usage

The calculator can be run from the command line by passing numbers and operators as arguments.

### Basic syntax

```bash
python calculator.py <number1> <operator> <number2>
```

### Examples

```bash
python calculator.py 10 + 5
python calculator.py 20 - 8
python calculator.py 6 * 7
python calculator.py 50 / 2
python calculator.py 9 % 4
python calculator.py 2 ^ 8
```

## Supported Operators

- `+` : addition
- `-` : subtraction
- `*` : multiplication
- `/` : division
- `%` : modulus
- `^` : exponentiation

## Example Output

```bash
$ python calculator.py 12 + 8
20
```

```bash
$ python calculator.py 9 / 3
3.0
```

## Error Handling

The program should handle invalid input gracefully, such as:

- missing values
- unsupported operators
- division by zero
- non-numeric input

For example:

```bash
$ python calculator.py 10 / 0
Error: division by zero
```

```bash
$ python calculator.py 5 $ 2
Error: invalid operator
```

## Project Structure

```text
cmd_calculator/
├── calculator.py
├── README.md
└── ...
```

## Notes

This project is intentionally simple and easy to extend. You can add features such as:

- support for parentheses
- more advanced math functions
- history of previous calculations
- interactive mode

## License

This project is provided for educational purposes. Add a license file if you plan to distribute or publish it publicly.

## Contributing

Contributions are welcome. If you would like to improve the application, consider:

- adding new operators
- improving validation and error messages
- refactoring code for readability
- adding test cases
