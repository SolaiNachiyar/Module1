## Name: SOLAI NACHIYAR M S
## Register no: 212225080053

# Ex-1:Conditional Statements in Python: Even or Odd Checker
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
```
num = int(input("Enter a number: "))
if (num % 2) == 0:
    print("{} is Even".format(num))
else:
    print("{} is Odd".format(num))
```
## Output

<img width="825" height="331" alt="image" src="https://github.com/user-attachments/assets/e4b74226-400f-4934-8935-5969545933fb" />

## Result
Thus, the program has been excecuted successfully.



# Ex-2:Datatypes-Boolean Expression Evaluation in Python

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
```
a = (0 == True)
b = (False == False)
c = (True + True)
d = (False + 9)

print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)
```
## Output

<img width="606" height="637" alt="image" src="https://github.com/user-attachments/assets/325e9f8c-aa21-4a0c-9638-f73e8e4e0da1" />

## Result
Thus, the program has been excecuted successfully.


# Ex-3:Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```
print('T')
print('a')
```
## Output

<img width="564" height="297" alt="image" src="https://github.com/user-attachments/assets/b0cef8a3-5a99-46ab-af5b-9c6116444ef6" />

## Result
Thus, the program has been excecuted successfully.


# Ex-4: Datatypes-Complex Number Creation in Python

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
```
a = int(input("Enter the real part: "))
b = int(input("Enter the imaginary part: "))

x = complex(a, b)

print("Complex number:", x)
print("Real part:", x.real)
print("Imaginary part:", x.imag)
```
## Output

<img width="850" height="445" alt="image" src="https://github.com/user-attachments/assets/b4ecc60c-566f-41fe-af34-fdcff269b4c8" />

## Result
Thus, the program has been excecuted successfully.


# Ex-5: Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```
men_stepped_on_the_moon = input("Enter a string: ")
print(men_stepped_on_the_moon)
```
## Output

<img width="1141" height="217" alt="image" src="https://github.com/user-attachments/assets/3c0d2fba-55cc-4a37-9442-f47f3d088134" />

## Result
Thus, the program has been excecuted successfully.

