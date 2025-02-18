# CalculatorPlus

A simple Python calculator that performs basic arithmetic operations. This project also includes a **square root feature** (to be implemented).

## Features

- Basic arithmetic operations:
  - Addition
  - Subtraction
  - Multiplication
  - Division
- **Planned Feature**:
  - Square root calculation

## Installation

Ensure you have Python 3.x installed.

### Clone the repository:
```bash
git clone https://github.com/yourusername/git_assignment_HeroVired.git
cd git_assignment_HeroVired
```

## Usage

Run the script using Python:

```python
from calculator import Calculator

# Create a calculator instance
calculator = Calculator()

num1 = 16
num2 = 4

# Basic operations
print(f"{num1} + {num2} = {calculator.add(num1, num2)}")
print(f"{num1} - {num2} = {calculator.subtract(num1, num2)}")
print(f"{num1} * {num2} = {calculator.multiply(num1, num2)}")
print(f"{num1} / {num2} = {calculator.divide(num1, num2)}")

# TODO: Uncomment and test the square root feature
# num3 = 25
# print(f"The square root of {num3} = {calculator.square_root(num3)}")
```

## Implementation Details

### **Calculator Class**
The `Calculator` class provides the following methods:
- `add(a, b)`: Returns the sum of `a` and `b`.
- `subtract(a, b)`: Returns the difference of `a` and `b`.
- `multiply(a, b)`: Returns the product of `a` and `b`.
- `divide(a, b)`: Returns the division of `a` by `b`.
  - **Note:** The function currently does not handle division by zero.
- **Planned Feature**: `square_root(x)` will return the square root of `x`.

## Contributing

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/sqrt`).
3. Implement and test the square root feature.
4. Commit changes (`git commit -m "Implemented square root function"`).
5. Push the branch (`git push origin feature/sqrt`).
6. Open a pull request.

## License

This project is licensed under the MIT License.

## Author

Prince Thakur

## Acknowledgments

- Python `math` module documentation
- Contributors and maintainers
