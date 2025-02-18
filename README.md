# Calculator Project

A simple Python calculator class that performs basic arithmetic operations.

## Features

The `Calculator` class currently supports the following operations:
- Addition
- Subtraction  
- Multiplication
- Division

## Usage

```python
from calculator import Calculator

# Create a calculator instance
calculator = Calculator()

# Perform calculations
result_add = calculator.add(10, 5)        # 15
result_sub = calculator.subtract(10, 5)   # 5
result_mul = calculator.multiply(10, 5)   # 50
result_div = calculator.divide(10, 5)     # 2.0
```

## Example

```python
calculator = Calculator()
num1 = 16
num2 = 4

print(f"{num1} + {num2} = {calculator.add(num1, num2)}")        # 16 + 4 = 20
print(f"{num1} - {num2} = {calculator.subtract(num1, num2)}")   # 16 - 4 = 12
print(f"{num1} * {num2} = {calculator.multiply(num1, num2)}")   # 16 * 4 = 64
print(f"{num1} / {num2} = {calculator.divide(num1, num2)}")     # 16 / 4 = 4.0
```

## Upcoming Features

The following features are planned for future implementation:
- Square root calculation

## Development Notes

- The square root feature is currently in development. Look for the TODO comments in the code to find where implementation is needed.
- The implementation will use the `math.sqrt()` function from Python's standard library.

## Known Issues

- The current version has an error in the main script: `if **name** == "__main__":` should be corrected to `if __name__ == "__main__":` with double underscores.
- Division by zero is not handled and will raise an exception.

## Requirements

- Python 3.x
- No external dependencies required

## Contributing

To contribute to this project:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

Priority items for contribution:
1. Implement the square root function
2. Add error handling for division by zero
3. Expand test coverage