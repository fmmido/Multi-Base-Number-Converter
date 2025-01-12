# Multi-Base Number Converter with Complements and Arithmetic Operations

This project is a web-based multi-base number converter that supports binary, ternary, octal, decimal, and hexadecimal number systems. It provides detailed steps for conversion, as well as arithmetic operations including binary subtraction using 2's complement, binary addition, and decimal subtraction using 10's complement.

## Features

- Convert numbers between binary, ternary, octal, decimal, and hexadecimal systems.
- Display detailed steps for the conversion process.
- Calculate and display 2's complement for binary numbers and 10's complement for decimal numbers.
- Perform and explain arithmetic operations:
  - Binary subtraction using 2's complement.
  - Binary addition.
  - Decimal subtraction using 10's complement.
- User-friendly interface with UX colors and arrows to help beginners understand the steps.

## Usage

1. **Select the base of the input number:** Choose from binary, ternary, octal, decimal, or hexadecimal.
2. **Enter the number to be converted:** Input the number in the selected base.
3. **Select the base to convert to:** Choose the target base for conversion.
4. **View the conversion result and steps:** The converted output, detailed steps, and complements will be displayed.
5. **Perform arithmetic operations:**
   - **Binary Subtraction using 2's complement:** Input two binary numbers and select this operation.
   - **Binary Addition:** Input two binary numbers and select this operation.
   - **Decimal Subtraction using 10's complement:** Input two decimal numbers and select this operation.

## Example

### Binary Subtraction using 2's complement

**Input:**
- Binary Number 1: `11010.11001`
- Binary Number 2: `1101.1111`

**Output:**
```
Operations Result:
Binary subtraction (using 2's complement):
11010.11001 - 1101.11110 = 100010.11011

Steps:
1. 1's complement of 1101.11110: 0010.0000
2. 2's complement of 1101.11110: 0010.0001
3. Add 11010.11001 and 0010.0001 to get: 100010.11011
4. Final result (with binary point): 100010.11011
```

## Installation

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/multi-base-number-converter.git
   ```
2. Navigate to the project directory:
   ```bash
   cd multi-base-number-converter
   ```
3. Open the `index.html` file in your web browser to see the converter in action.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or features you would like to add.

## License

This project is licensed under the MIT License
