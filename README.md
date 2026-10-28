# Prime Number Checker

A simple Python program that checks whether an integer is prime.

## Requirements

- Python 3

## Run

Open a terminal in this folder and run:

```bash
python prime_checker.py
```

Enter an integer when prompted. For example:

```text
Enter an integer: 17
17 is a prime number.
```

The program reports that numbers less than 2 are not prime and displays a helpful message if the input is not a valid integer.

## How it works

The program checks whether the number has any divisors from 2 up to its square root. It handles 2 separately and then checks only odd divisors.
