# CalculatorPlus & Geometry Calculator

## Overview
CalculatorPlus is a simple Python-based calculator that supports basic arithmetic operations such as:
- Addition
- Subtraction
- Multiplication
- Division
- Square Root Calculation

Additionally, this repository includes a Geometry Calculator that can calculate:
- Area of a circle

## Features
- Perform basic arithmetic calculations
- Handles division safely
- Supports square root calculations
- Calculate the area of a circle

## Installation
Clone the repository and navigate to the project directory:
```bash
git clone https://github.com/yourusername/git_assignment_HeroVired.git
cd git_assignment_HeroVired
```

## Usage
Run the Python script to use the calculator:
```bash
python calculator.py
```

### Example Output
```
16 + 4 = 20
16 - 4 = 12
16 * 4 = 64
16 / 4 = 4.0
The square root of 25 = 5.0
```

## Code Structure
```python
import math

class Calculator:
    def add(self, a, b):
        return a + b

    def subtract(self, a, b):
        return a - b

    def multiply(self, a, b):
        return a * b

    def divide(self, a, b):
        if b == 0:
            raise ValueError("Cannot divide by zero.")
        return a / b

    def square_root(self, x):
        return math.sqrt(x)

if __name__ == "__main__":
    calculator = Calculator()
    num1 = 16
    num2 = 4
    print(f"{num1} + {num2} = {calculator.add(num1, num2)}")
    print(f"{num1} - {num2} = {calculator.subtract(num1, num2)}") 
    print(f"{num1} * {num2} = {calculator.multiply(num1, num2)}")
    print(f"{num1} / {num2} = {calculator.divide(num1, num2)}")

    num3 = 25
    print(f"The square root of {num3} = {calculator.square_root(num3)}")
```

## Development Workflow
1. Clone the repository.
2. Create a new branch for feature development.
3. Implement changes and commit them.
4. Push the branch and create a Pull Request (PR).
5. Merge changes after review.

## Contribution
Feel free to fork the repository and submit pull requests. Collaborators can be added for teamwork.

## License
This project is licensed under the MIT License.

