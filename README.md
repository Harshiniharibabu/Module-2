# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
a=16
b=bin(a)
print(b)
```

## Output
<img width="1919" height="1011" alt="image" src="https://github.com/user-attachments/assets/bb9e4ecb-551e-466a-87ca-feffadafa5a8" />


## Result
Thus, the program is executed successfully.

# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def result(a,b):
    print(a%b)
a=int(input("Enter the first number: "))
b=int(input("Enter the second number: "))
result(a,b)
```

## Output
<img width="1918" height="1021" alt="image" src="https://github.com/user-attachments/assets/3dfb025a-b938-43a1-becf-50b48011c96c" />


## Result
Thus, the program is executed successfully.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
a=int(input("Enter the first number: "))
b=int(input("Enter the second number: "))
f = lambda a , b : a + b
print("The sum is : ",f(a,b))
```

## Output
<img width="1919" height="1015" alt="image" src="https://github.com/user-attachments/assets/a112aa1a-7f37-4d39-a799-2026c149a3ef" />

## Result
Thus, the program is executed successfully.
