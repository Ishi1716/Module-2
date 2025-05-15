# Built-in Functions -Binary Conversion Using Built-in Functions in Python


## 🎯 Aim

To write a Python program to convert the number 16 into its binary representation using built-in Python functions.

## 🧠 Algorithm

Assign the value 16 to a variable a.

Use the built-in bin() function to convert the number to binary.

Print the result.

##🧾 Program

```python

a=16

print(bin(a))

```

## Output

![image](https://github.com/user-attachments/assets/f10c8bf3-6384-4323-b32c-6a060a666c10)

## Result

Thus ,the program is executed successfully.


----

# Functions in Python: Modulo Calculator

## 🎯 Aim

To write a Python program that defines a function which accepts two values and returns their modulo using the % operator.

## 🧠 Algorithm

Define a function called result that takes two arguments a and b.

Inside the function, compute the modulo using a % b.

Print the result of the modulo operation.

Get two integer inputs from the user.

Call the result function with the user-provided values.

## 🧾 Program

``` python
def result(a,b):

mod=a%b

print(f"modulo is {mod}")

a = int(input())

b = int(input())

```

## Output

![image](https://github.com/user-attachments/assets/75861bbd-f244-4d83-a18c-490219273710)

## Result

Thus,the program is executed suucessfully.

----

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim

To write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum.

## 🧠 Algorithm

Get two integer inputs from the user.

Use a lambda function to define a function f that returns a + b.

Call the function with the user inputs and print the result.

## 🧾 Program

``` python

a=int(input())

b=int(input())

f=lambda a,b:a+b

print(f(a,b))

```

## Output

![image](https://github.com/user-attachments/assets/c07a955a-4fce-4d23-9b00-b978273acc20)


## Result

Thus,the program is executed successfully.

----

# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate Pascal’s Triangle, where the number of rows is provided by the user.

## 🎯 Aim

To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user.

## 🧠 Algorithm

Start the program.

Input the number of rows from the user.

Loop from 0 to the number of rows.

For each row:

Print appropriate spaces to shape the triangle.

Compute values using the formula:

[ C(n, k) = \frac{n!}{k!(n-k)!} ]

Print all rows of Pascal’s Triangle.

End the program.

## 🧪 Program

``` python
n=int(input())
for i in range(1,n+1):
    num=1
    for k in range(1,n-i+1):
        print(" ",end="")
    for j in range(0,i):
        if j==0 or i==0:
            num=1
        else:
            num=num*(i-j)//j
        print(num,end=" ")
    print()

```


## Sample Output

![image](https://github.com/user-attachments/assets/9b28c607-4da4-417f-9915-2981ffe5a14b)


## Result

Thus,the program is executed successfully.

----

# Loops in Python: Palindrome Number Checker

## 🎯 Aim

To write a Python program that checks whether a given number is a palindrome using loops.

## 🧠 Algorithm

Get input from the user and assign it to a variable num.

Assign the value of num to a temporary variable temp.

Initialize a variable rev to 0 (used to store the reversed number).

Use a while loop to reverse the digits:

While temp > 0:

rev = (10 * rev) + temp % 10

temp = temp // 10

After the loop, compare rev with num:

If equal, print that the number is a palindrome.

Else, print that it is not a palindrome.

## 🧾 Program

``` python

num = int(input())
rev = 0
temp = num

while temp > 0:
    digit = temp % 10  
    rev = rev * 10 + digit 
    temp //= 10 


if num == rev:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))

```


## Output

![image](https://github.com/user-attachments/assets/c5438030-8e3a-45b3-8bb5-f6cd6503eb4c)

## Result

Thus,the program as been executed successfully

