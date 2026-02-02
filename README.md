# python-basic-calculator
A simple command-line calculator that performs basic arithmetic operations.
def add(x, y): return x + y
def subtract(x, y): return x - y
def multiply(x, y): return x * y
def divide(x, y): return x / y if y != 0 else "Error: Division by zero!"

print("Select operation:")
print("1.Add / 2.Subtract / 3.Multiply / 4.Divide")

choice = input("Enter choice (1/2/3/4): ")
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

if choice == '1': print(f"Result: {add(num1, num2)}")
elif choice == '2': print(f"Result: {subtract(num1, num2)}")
elif choice == '3': print(f"Result: {multiply(num1, num2)}")
elif choice == '4': print(f"Result: {divide(num1, num2)}")
else: print("Invalid Input")
# Python Basic Calculator
A simple Python script to perform basic math operations.

## Features
- Addition, Subtraction, Multiplication, and Division.
- Easy to use via terminal.

## How to use
Run `python calculator.py` and follow the instructions.
