## NO: 1 Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
a=16 
print(bin(a)
```
## Output
<img width="684" height="302" alt="568998402-60abf9a4-8fa7-4b69-abe2-eeb97646d756" src="https://github.com/user-attachments/assets/a10b6d44-a91c-4706-93ca-1533fa8b42ea" />

## Result
Thus, the program has been successfully executed.

## NO:2Functions in Python: Modulo Calculator

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
def result(a, b):
    modulo_value = a % b
    print("modulo is",modulo_value)
c=int(input())
d=int(input())
result(c,d)
```
## Output
<img width="812" height="360" alt="568998661-f2981ba0-001c-4f47-8f96-981fcd697cbd" src="https://github.com/user-attachments/assets/5f745d9f-dedb-47d8-9769-a56463e94e0e" />

## Result
The program to return two values modulo is successful.


## NO:3 Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
a=int(input()) 
b=int(input()) 
f=lambda a,b: a+b 
print(f(a,b))
```

## Output
<img width="573" height="234" alt="568999147-ad888b9c-f007-48d3-b368-7e23c878691e" src="https://github.com/user-attachments/assets/5a104c23-b746-4d0a-8054-53c732ae4b62" />

## Result
Thus, the program has been successfully executed.

## NO:4🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

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
```
def factorial(n):
    if n == 0 or n == 1:
        return 1
    return n * factorial(n - 1)

def combination(n, k):
    return factorial(n) // (factorial(k) * factorial(n - k))

num_rows = int(input("Enter number of rows: "))

for i in range(num_rows):
    print(' ' * (num_rows - i - 1), end='')
    for j in range(i + 1):
        print(combination(i, j), end=' ')
    print()
```

## Sample Output
<img width="726" height="374" alt="569000118-f6a863b5-d970-4ecb-8b4b-ef7d04459216" src="https://github.com/user-attachments/assets/aeca04fc-7c6d-4c4b-aca1-b10610bc2631" />

## Result
Thus, the program has been successfully executed.


## NO:5 Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
a=int(input())
num = a
temp = num
rev = 0
while temp>0:
    rev = (10*rev) + temp % 10
    temp = temp//10
if rev==num:
    print(f"The given number {num} is a Palindrome")
else:
    print("The given number {num) is not a Palindrome")
```
## Output
<img width="1250" height="241" alt="568999787-ef948d5c-a431-4d43-a728-3ca6f139d401" src="https://github.com/user-attachments/assets/a5c829a8-9787-4f82-9ab6-11dbde0d4a92" />

## Result
Thus, the program has been successfully executed.

