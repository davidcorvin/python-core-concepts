# Practice Exercise

This program demonstrates a simple calculator that can perform basic operations such as addition, subtraction, multiplication, and division. Each function in the program is designed to take two arguments (numbers) and return the result of the operation.

## Calculator Program

```python
def add(x, y):
    """Add two numbers."""
    return x + y

def subtract(x, y):
    """Subtract the second number from the first."""
    return x - y

def multiply(x, y):
    """Multiply two numbers."""
    return x * y

def divide(x, y):
    """Divide the first number by the second. Raises an error for division by zero."""
    if y == 0:
        raise ValueError("Cannot divide by zero.")
    return x / y

def main():
    print("Welcome to the simple calculator!")
    print("Select operation:")
    print("1. Add")
    print("2. Subtract")
    print("3. Multiply")
    print("4. Divide")

    choice = input("Enter choice (1/2/3/4): ")

    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))

    if choice == '1':
        print(f"{num1} + {num2} = {add(num1, num2)}")

    elif choice == '2':
        print(f"{num1} - {num2} = {subtract(num1, num2)}")

    elif choice == '3':
        print(f"{num1} * {num2} = {multiply(num1, num2)}")

    elif choice == '4':
        print(f"{num1} / {num2} = {divide(num1, num2)}")

    else:
        print("Invalid input")

if __name__ == "__main__":
    main()
```

## Explanation

1. **Function Definitions**: Each operation (addition, subtraction, multiplication, division) is defined in a separate function. This modular approach allows for easy testing and debugging.
  
2. **Error Handling**: The divide function checks for division by zero to prevent runtime errors.
  
3. **User Interaction**: The `main` function provides an interface for users to select an operation and input numbers, making it user-friendly.

4. **Code Execution**: The program can be executed in a standard Python environment, allowing easy testing and use.