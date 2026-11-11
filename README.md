# Simple Addition Program
print("Welcome to Simple Addition!")
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
result = num1 + num2
print(f"The sum of {num1} and {num2} is {result}")

# Extra friendly touch
if result > 100:
    print("Wow, that's a big number!")
else:
    print("Nice and simple!")
