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
<img width="338" height="107" alt="image" src="https://github.com/user-attachments/assets/48a538a6-44a5-4615-ad5d-714da9841d2d" />

## Result
Thus, the Python program to check whether a given number is even or odd using if...else statement was executed successfully.


# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
Add Code here
a = (0 == True)
b = (False == False)
c = True + True
d = False + 9

print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)
## Output
<img width="321" height="201" alt="image" src="https://github.com/user-attachments/assets/681c30f6-bae7-4839-8ff2-8f30531c844b" />

## Result
Thus, the Python program to evaluate boolean and a


# Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
print('T')
print('a')
## Output
<img width="331" height="165" alt="image" src="https://github.com/user-attachments/assets/7b26dfb5-7b6e-48bb-bf24-e1972643bdbf" />

## Result
Thus, the Python program to print characters using character literals was executed successfully.


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
a = int(input("Enter real part: "))
b = int(input("Enter imaginary part: "))
x = complex(a, b)

# Step 4–6: Display results
print("Complex number is:", x)
print("Real part is:", x.real)
print("Imaginary part is:", x.imag)

## Output
<img width="490" height="304" alt="image" src="https://github.com/user-attachments/assets/87ed6f01-93b8-42c5-a548-710b448a51ab" />

## Result
The program successfully creates a complex number using user inputs and displays its real and imaginary parts using .real and .imag attributes.
