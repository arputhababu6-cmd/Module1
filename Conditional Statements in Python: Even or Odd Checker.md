# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
a = int(input())

if a % 2 == 0:
    print("EVEN")
else:
    print("ODD")

## Output
<img width="112" height="56" alt="image" src="https://github.com/user-attachments/assets/6d3de67d-d3d9-49cf-b86b-fb0186d95809" />
<img width="128" height="50" alt="image" src="https://github.com/user-attachments/assets/4dd01ab9-0832-4710-9c93-50912310f524" />

## Result
The program evaluates the user's input and determines its parity, returning "EVEN" if the number is exactly divisible by 2 and "ODD" if there is a remainder.
