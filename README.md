1.Conditional Statements in Python: Even or Odd Checker

🎯 Aim
To write a Python program to check whether the given number is even or odd using if...else statements.

🧠 Algorithm
1.Get an input from the user.
2.Convert the input to an integer and store it in a variable a.
3.Use the modulo operator % to check if a % 2 == 0.
4.If true, print "EVEN".
5.Else, print "ODD".
6.End the program.

🧾 Program:
```
a = int(input("Enter a number: "))
if a % 2 == 0:
    print("EVEN")
else:
    print("ODD")
```
Output:
![Screenshot_24-3-2026_135836_www programiz com](https://github.com/user-attachments/assets/11565bca-ba90-4b34-99fa-2b0dbfc2dab7)

Result:
The program was successfully implemented.


2.Datatypes-Boolean Expression Evaluation in Python
🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving True and False.

🧠 Algorithm
1.Set variable a to the result of the expression 0 == True.
2.Set variable b to the result of the expression False == False.
3.Set variable c to the result of the expression True + True.
4.Set variable d to the result of the expression False + 9.
5.Print the value of a with the label "a is".
6.Print the value of b with the label "b is".
7.Print the value of c with the label "c:".
8.Print the value of d with the label "d:".
💻 Program:
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
Output:
![Screenshot_24-3-2026_14520_www programiz com](https://github.com/user-attachments/assets/4ec2443a-9314-48f2-892e-d68af886e99d)

Result:
The program was successfully implemented.



3.Datatypes-Character Literal in Python
🎯 Aim
To write a Python program that prints the characters 'T' and 'a' using character literals.

🧠 Algorithm
1.Print the character 'T'.
2.Print the character 'a'.
🧾 Program:
```
print('T')
print('a')
```
Output:
![Screenshot_24-3-2026_1491_www programiz com](https://github.com/user-attachments/assets/e32a8088-8dd7-4f74-973f-37be91777792)

Result:
The program was successfully implemented.



4.Datatypes-Complex Number Creation in Python
🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

🧠 Algorithm
1.Read an integer input from the user and assign it to the variable a (real part).
2.Read another integer input from the user and assign it to the variable b (imaginary part).
3.Create a complex number x using the complex(a, b) function.
4.Print the complex number x.
5.Print the real part of x using x.real.
6.Print the imaginary part of x using x.imag.
💻 Program:
```
a = int(input("Enter real part: "))
b = int(input("Enter imaginary part: "))
x = complex(a, b)
print("Complex number:", x)
print("Real part:", x.real)
print("Imaginary part:", x.imag)
```
Output:
![Screenshot_24-3-2026_141152_www programiz com](https://github.com/user-attachments/assets/ac3d56a5-2775-4c35-9b37-d98ad825e361)
Result:
The program was successfully implemented.



5.Datatypes-Read and Print a String in Python
🎯 Aim
To write a Python program to read a string from the user and then print it.

🧠 Algorithm
1.Assign a variable named men_stepped_on_the_moon.
2.Use input() to read a string from the user and store it in the variable.
3.Print the value stored in the variable.
🧾 Program:
```
men_stepped_on_the_moon = input("Enter a string: ")
print(men_stepped_on_the_moon)
```
Output:
![Screenshot_24-3-2026_14150_www programiz com](https://github.com/user-attachments/assets/1009a761-81d7-41f5-9992-d956287e18a3)

Result:
The program was successfully implemented.
