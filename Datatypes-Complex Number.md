# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
a = int(input())

b = int(input())

x = complex(a, b)

print(x)

print(x.real)

print(x.imag)

## Output
<img width="161" height="106" alt="image" src="https://github.com/user-attachments/assets/c1ba814c-b944-4a90-bf02-ba5b55050f64" />

## Result
The program reads two integers to construct a complex number $a + bj$, then displays the full complex value followed by its real and imaginary components as floating-point numbers.
