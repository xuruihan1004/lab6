# lab6
# Simple Python Program in Jupyter Notebook

# Step 1: Take a name input
name = input("Enter your name: ")
print(f"Hello, {name}!")

# Step 2: Take another input (a number)
number = int(input("Enter a number: "))

# Step 3: Do Something™ with the number (calculate its factorial)
def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n - 1)

result = factorial(number)
print(f"{name}, the factorial of {number} is {result}!")
