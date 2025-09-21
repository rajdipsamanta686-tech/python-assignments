def add(a,b):
    return a + b
def subs(a,b):
    return a - b
def multi(a,b):
    return a * b
def div(a,b):
    return a / b
def mod(a,b):
    return a % b

num1 = float(input("Please enter a number:> "))
num2 = float(input("Please enter a number:> "))

choice = input("Please enter an operation (+, -, *, /, %):> ")

if choice == '+':
    print(f"{num1} + {num2} = {add(num1, num2)}")
elif choice == '-':
    print(f"{num1} - {num2} = {subs(num1, num2)}")
elif choice == '*':
    print(f"{num1} * {num2} = {multi(num1, num2)}")
elif choice == '/':
    print(f"{num1} / {num2} = {div(num1, num2)}")
elif choice == '%':
    print(f"{num1} % {num2} = {mod(num1, num2)}")
else :
    print("Error")
