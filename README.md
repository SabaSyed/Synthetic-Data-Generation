# Synthetic Data Generation

This repository contains scripts and resources for generating synthetic datasets, focusing on mathematical expressions. The aim is to create diverse, randomized data that can be used for training models, particularly for tasks involving LaTeX-to-Python code conversion.

## Overview

To run the scripts in this repository, you need to install the **SymPy** library in Python. SymPy is used to generate and manipulate mathematical expressions programmatically.

```bash
pip install sympy
```

### Generated Data

We created 100 random expressions for each of the following categories:

- **Multivariable equations**
- **Trigonometric functions**
- **Geometric expressions**
- **Diophantine equations**
- **Summation equations**

These expressions are generated using Python's SymPy library. The `lambdify` function is utilized to convert the symbolic SymPy expressions into executable Python code, which can be evaluated and tested.

## Future Improvements

- Expand the range of mathematical functions and expressions.
- Optimize test case generation for more complex scenarios.

Feel free to contribute by providing feedback, issues, or pull requests!
