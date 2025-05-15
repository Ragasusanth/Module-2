# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number *16* into its *binary representation* using built-in Python functions.

## 🧠 Algorithm
1. Assign the value 16 to a variable a.
2. Use the built-in bin() function to convert the number to binary.
3. Print the result.

## 🧾 Program


a=16
b=bin(a)
print(b)


## Output

![WhatsApp Image 2025-05-15 at 10 08 41_2b95c3a2](https://github.com/user-attachments/assets/990e9938-319e-41fb-b4ef-2354ce8c1331)

## Result

Thus,the Python program to convert the number 16 into its binary representation using built-in Python functions is created successfully.

# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their *modulo* using the % operator.

## 🧠 Algorithm
1. Define a function called result that takes two arguments a and b.
2. Inside the function, compute the modulo using a % b.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the result function with the user-provided values.

## 🧾 Program

def result(a,b):
    a=a%b
    return a
a=int(input())
b=int(input())
result1=result(a,b)
print("modulo is",result1)

## Output


![WhatsApp Image 2025-05-15 at 10 13 59_7e5209b3](https://github.com/user-attachments/assets/d71398f4-eb8d-42ac-97d2-1324955ef325)

## Result

Thus,the Python program that defines a function which accepts two values and returns their modulo using the % operator is created successfully.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a *lambda function* which takes two arguments a and b, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a *lambda function* to define a function f that returns a + b.
3. Call the function with the user inputs and print the result.

## 🧾 Program

a=int(input())
b=int(input())

f = lambda a, b: a+b

print(f(a, b))

## Output

![WhatsApp Image 2025-05-15 at 10 19 59_bf16fccd](https://github.com/user-attachments/assets/c44fedfa-a741-4af3-899d-eb3ff3333643)


## Result

Thus,the Python program that defines a lambda function which takes two arguments a , b  and returns their sum is created successfully.

# Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate *Pascal’s Triangle*, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates *Pascal's Triangle* using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program

rows = int(input())
count = 1

for i in range(1, rows+1):
    for space in range(1, rows-i+1):
        print(" ",end="")
    for j in range(0, i):
        if j==0 or i==0:
            count = 1
        else:
            count = count * (i - j)//j
        print(count, end = " ")
    print()

## Sample Output

![WhatsApp Image 2025-05-15 at 10 33 56_a9a7346a](https://github.com/user-attachments/assets/0a289fec-5073-46e0-a5cc-38cd8ddc2eab)


## Result

Thus,the Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is created successfully.

## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a *palindrome* using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable num.
2. Assign the value of num to a temporary variable temp.
3. Initialize a variable rev to 0 (used to store the reversed number).
4. Use a while loop to reverse the digits:
   - While temp > 0:
     - rev = (10 * rev) + temp % 10
     - temp = temp // 10
5. After the loop, compare rev with num:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program

num=int(input())
temp=num
rev=0
while temp>0:
    digit=temp%10
    rev=rev*10+digit
    temp=temp//10
if rev==num:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))

## Output

![WhatsApp Image 2025-05-15 at 10 39 40_12d7e9a6](https://github.com/user-attachments/assets/0a96ea26-8c14-4c57-b411-ec28db36e0f8)

## Result

Thus, the Python program that checks whether a given number is a palindrome using loops is created successfully.
