# Assignment 0: Leap Year Checker

## Overview
This assignment implements a leap year checker using Python. The program determines whether a given year is a leap year based on the following rules:

- A year is a leap year if it is divisible by 4 **AND** not divisible by 100, **OR**
- A year is a leap year if it is divisible by 400

## Directory Structure
```
ASSIGNMENT_0/
├── README.md
├── .gitignore
└── src/
    └── leap_year.ipynb
```

## Contents
- **leap_year.ipynb**: Jupyter notebook containing the leap year function implementation and comprehensive test cases

## How to Use
1. Open `leap_year.ipynb` in Jupyter Notebook or JupyterLab
2. Run each cell in sequence to:
   - Import necessary libraries
   - Define the leap year function
   - Test with sample years (2020, 2021, 1900, 2000)
   - Validate edge cases (century years and years divisible by 4)

## Leap Year Rules
- Years divisible by 400 are always leap years (e.g., 2000)
- Years divisible by 100 are NOT leap years, unless they are also divisible by 400
- Years divisible by 4 are leap years, unless they are also divisible by 100
- All other years are not leap years

## Example Results
- 2000: Leap Year (divisible by 400)
- 1900: Not a Leap Year (divisible by 100 but not by 400)
- 2020: Leap Year (divisible by 4 and not by 100)
- 2021: Not a Leap Year (not divisible by 4)
