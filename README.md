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
```py
num = int(input())
if num%2==0:
    print("EVEN")
else:
    print("ODD")
```

## Output
<img width="128" height="67" alt="image" src="https://github.com/user-attachments/assets/ed619d84-27c3-40f8-96c1-de486cc1caec" />

## Result
Thus the Python Program for determining whether the given number is odd or even has been executed successfully and the output has been verified.




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
```py
a = (0 == True)
b = (False == False)
c = True + True
d = False + 9

print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)
```

## Output
<img width="228" height="110" alt="image" src="https://github.com/user-attachments/assets/aebfe709-cd02-4d75-bd77-efc2983bdb32" />

## Result
Thus the given Python program has been executed successfully and the output has been verified.
