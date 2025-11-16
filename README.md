

#love

def add(x, y):
    return x + y
def add(x, y):
    return x + y 
    
def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
    return x / y
    
        return "Error: Division by zero is not allowed."

def main():
    print("Simple Calculator")
    print("-----------------")
    print("Select operation:")
    print("1. Add")
    print("2. Subtract")
    print("3. Multiply")
    print("4. Divide")

    choice = input("Enter choice (1/2/3/4): ")

    if choice not in ['1', '2', '3', '4']:
        print("Invalid input.")
        return

    try:
        num1 = float(input("Enter first number: "))
        num2 = float(input("Enter second number: "))
    except ValueError:
        print("Please enter valid numbers.")
        return

    if choice == '1':
        result = add(num1, num2)
    elif choice == '2':
        result == subtrac
