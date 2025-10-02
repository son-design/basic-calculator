print("Simple Calculator")
a = float(input("Enter first number: "))
b = float(input("Enter second number: "))
op = input("Choose operation (+, -, *, /): ")

if op == "+":
    result = a + b
elif op == "-":
    result = a - b
elif op == "*":
    result = a * b
elif op == "/":
    if b != 0:
        result = a / b
    else:
        result = "Cannot divide by zero"
else:
    result = "Invalid operation"

print(f"Result: {result}")
