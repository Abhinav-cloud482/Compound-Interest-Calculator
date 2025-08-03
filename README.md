# Compound-Interest-Calculator

## Python Compound Interest Calculator

A simple Python script to calculate compound interest based on user input for principal amount, interest rate, and time duration. This project is ideal for beginners learning Python fundamentals like loops, conditionals, and user input handling.

---

## Features

- Validates user input to ensure values are positive
- Calculates compound interest using the standard formula
- Displays the final balance with formatted output

---

## Formula Used

The compound interest is calculated using :

A = P × (1 + r/100)ᵗ

Where:
- `A` = Final amount
- `P` = Principal amount
- `r` = Annual interest rate (in %)
- `t` = Time in years

---

##  How It Works

1. Prompts the user to enter:
   - Principal amount
   - Interest rate
   - Time in years
2. Validates that all inputs are greater than zero
3. Computes the compound interest
4. Displays the final balance after the given time period

---

##  Usage

Run the script using any Python interpreter:

```bash

python compound_interest_calculator.py

```

Follow the prompts to input:
- Principal amount (must be > 0)
- Interest rate (must be > 0)
- Time in years (must be > 0)


Example output:

```bash

Enter the principal amount: 1000
Enter the interest rate: 5
Enter the time in years: 3
Balance after 3 year/s : $ 1157.63

```

---

## File Structure

```bash

compound_interest_calculator/
│
├── compound_interest_calculator.py   # Main script
└── README.md                         # Project documentation

```

---

### Requirements
- Python 3.x
- No external libraries required

---

## Contributing

Feel free to fork the repo and submit pull requests for improvements, such as:
- Adding GUI support
- Supporting monthly/quarterly compounding
- Enhancing input validation

---

## License
This project is open-source and available under the MIT License.

---

## Inspiration
Created as a beginner-friendly project to reinforce Python basics and financial logic. Perfect for students, educators, or anyone curious about how compound interest works.

---
