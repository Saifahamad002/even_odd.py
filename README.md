# Python Even or Odd Checker

A simple Python program that checks whether a number entered by the user is even or odd.

## Features
- Takes user input
- Uses conditional statements (`if-else`)
- Checks number parity using the modulus operator (`%`)

## Code

```python
number = int(input("Please enter a number: "))

if number % 2 == 0:
    print("This number is Even")
else:
    print("This number is Odd")
