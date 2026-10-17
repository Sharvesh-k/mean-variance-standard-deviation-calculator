# Mean-Variance-Standard Deviation Calculator

A Python project that uses **NumPy** to perform statistical calculations on a list of nine numbers arranged into a 3 × 3 matrix.

Built as part of the [freeCodeCamp Data Analysis with Python Certification](https://www.freecodecamp.org/learn/data-analysis-with-python/).

## Overview

This project transforms a list of nine numbers into a 3 × 3 NumPy array and calculates statistical measures across columns, rows, and the entire matrix.

## Features

- Calculate the **mean** of rows, columns, and the entire matrix.
- Calculate the **variance** and **standard deviation**.
- Find the **maximum** and **minimum** values.
- Calculate the **sum** across rows, columns, and all elements.
- Validate the input and raise a `ValueError` when fewer than nine numbers are provided.

## Tech Stack

- **Language:** Python
- **Library:** NumPy
- **Testing:** Python `unittest`

## Project Structure

```text
mean-variance-standard-deviation-calculator/
├── mean_var_std.py
├── main.py
├── test_module.py
├── requirements.txt
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/Sharvesh-k/mean-variance-standard-deviation-calculator.git
cd mean-variance-standard-deviation-calculator
```

Install the dependency:

```bash
python -m pip install numpy
```

## Usage

Import the `calculate()` function and provide a list of nine numbers:

```python
from mean_var_std import calculate

result = calculate([0, 1, 2, 3, 4, 5, 6, 7, 8])

print(result)
```

The function returns a dictionary containing six calculations: `mean`, `variance`, `standard deviation`, `max`, `min`, and `sum`. Each calculation contains the column results, row results, and overall result.

## Run Tests

```bash
python -m unittest test_module.py
```

## Learning Outcomes

- Working with NumPy arrays and reshaping data.
- Performing statistical calculations using NumPy.
- Applying functions across array axes.
- Writing and validating Python unit tests.

## Acknowledgements

Project challenge provided by [freeCodeCamp](https://www.freecodecamp.org/).

---

**Author:** [Sharvesh-k](https://github.com/Sharvesh-k)
