# Function for addition
def add(a, b):
    return a + b

# Function for subtraction
def subtract(a, b):
    return a - b

# Function for multiplication
def multiply(a, b):
    return a * b

# Function for division
def divide(a, b):
    if b != 0:
        return a / b
    else:
        return "Division by zero is not allowed!"

# Main program
def main():
print("Basic Arithmetic Operations")
num1 = 10 # example input 
num2 = 5 # example input 
addition_result= add (num1,num2)
subtraction_result = (num1,num2)
multiplication_result= multiply(num1,num2)
division_result=(num1,num2)

print("\nResults:")
print(f"Addition: {add(10, 5)}")     # Output:15
print(f"Subtraction: {subtract(10, 5)}") # output:5
print(f"Multiplication: {multiply(10, 5)}") # Output: 50 
print(f"Division: {divide(10, 5)}") #Output: 2

 
