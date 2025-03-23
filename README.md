# Toy-Problems-Code-Challenge
This repository contains solutions to Toy-Problems challenges.

## Repository Structure

Each challenge is located in its own JavaScript file within the repository. A single file contains only one solution.

```
|-- toy-problems challenges/
    |-- net-salary-calculator.js
    |-- speed-detector.js
    |-- student-grade.js
|-- README.md
```

## Challenges

### 1. Student Grade Generator
**File:** `student-grade.js`

A function that prompts the user to input student marks (0-100) and outputs the corresponding grade:
- **A**: 80 - 100
- **B**: 60 - 79
- **C**: 50 - 59
- **D**: 40 - 49
- **E**: Below 40

**How to run:**
```sh
node student-grade.js
```

### 2. Speed Detector
**File:** `speed-detector.js`

A program that evaluates a car's speed:
- Speed < 70 → "Ok"
- Every 5 km/s over 70 adds a demerit point
- If points > 12, "License suspended"

**How to run:**
```sh
node speed-detector.js
```

### 3. Net Salary Calculator
**File:** `net-salarys-calculator.js`

Calculates an individual's net salary based on:
- **Gross Salary**: basic salary + benefits
- **Deductions**: Payee (Tax), NHIF, NSSF
- **Net Salary** = Gross Salary - Deductions

**How to run:**
```sh
node net-salary-calculator.js
```
