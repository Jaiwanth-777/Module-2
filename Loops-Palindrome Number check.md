## Loops in Python: Palindrome Number Checker

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
