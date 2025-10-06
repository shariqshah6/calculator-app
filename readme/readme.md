# 🧮 Simple Python Calculator

A **beginner-friendly calculator** built using Python.  
It performs basic arithmetic operations like **Addition, Subtraction, Multiplication**, and **Division** — all in the command line!

---

## 🚀 Features
- ➕ Addition  
- ➖ Subtraction  
- ✖️ Multiplication  
- ➗ Division  
- 🧠 Easy to understand and modify  

---

## 🧑‍💻 How It Works
1. The user enters two numbers.  
2. Chooses an operator (`+`, `-`, `*`, `/`).  
3. The calculator prints the result on the screen.  

---

## 🧰 Technologies Used
- **Python 3**

---

## 🧩 Code Example
```python
print("Simple Calculator")
num1 = float(input("Enter first number: "))
op = input("Enter operator (+, -, *, /): ")
num2 = float(input("Enter second number: "))

if op == '+':
    print("Result:", num1 + num2)
elif op == '-':
    print("Result:", num1 - num2)
elif op == '*':
    print("Result:", num1 * num2)
elif op == '/':
    print("Result:", num1 / num2)
else:
    print("Invalid operator")
