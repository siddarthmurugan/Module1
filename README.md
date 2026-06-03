
# 1. Conditional Statements in Python: Even or Odd Checker

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
```py
a=int(input())
if a%2==0:
    print("EVEN")
else:
    print("ODD")
```
## Output
<img width="237" height="177" alt="image" src="https://github.com/user-attachments/assets/8b860266-ebdc-4b3f-84c2-b0b52b1333be" />
<img width="276" height="173" alt="image" src="https://github.com/user-attachments/assets/4303552e-c3e9-4cc2-8b00-ef8fb1a0fad6" />

## Result
Successfully wrote a Python program to check whether the given number is **even** or **odd** using `if...else` statements.


# 2. Datatypes-Boolean Expression Evaluation in Python

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
```py
a=0==True
b=False==False 
c=True+True
d=False+9
print("a is",a)
print("b is",b)
print("c:",c)
print("d:",d)
```
## Output
<img width="337" height="230" alt="image" src="https://github.com/user-attachments/assets/f6d799a2-91be-421b-be64-a5d6b56a6619" />

## Result
Successfully wrote a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.


# 3. Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```py
x='T'
y='a'
print(x)
print(y)
```
## Output
<img width="93" height="147" alt="image" src="https://github.com/user-attachments/assets/32b27cd5-d615-4715-be2b-cc281b4bf945" />

## Result
Successfully wrote a Python program that prints the characters `'T'` and `'a'` using character literals.

# 4. Datatypes-Complex Number Creation in Python

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
```py
a=int(input())
b=int(input())
x=complex(a,b)
print(x)
print(float(x.real))
print(float(x.imag))
```
## Output
<img width="462" height="306" alt="image" src="https://github.com/user-attachments/assets/3b99b238-0dd4-42d4-a9d2-5b1412586ebd" />

## Result
Successfully wrote a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.


# 5. Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```py
men_stepped_on_the_moon=int(input())
print(men_stepped_on_the_moon)
```
## Output
<img width="347" height="207" alt="image" src="https://github.com/user-attachments/assets/9dbd292a-5736-4618-b270-d9bcaf652fbe" />

## Result
Successfully wrote a Python program to read a string from the user and then print it.
