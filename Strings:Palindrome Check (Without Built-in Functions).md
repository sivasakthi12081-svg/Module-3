# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
s="google"
rev=s[::-1]
if(s==rev):
    print("Palindrome")
else:
    print("Not a Palindrome")
```
## Output
<img width="1919" height="709" alt="Screenshot 2026-05-31 190907" src="https://github.com/user-attachments/assets/ea891136-77fc-4ff7-9614-1469c1c71af3" />

## Result
The given string "google" was checked and found not to be a palindrome, since the original string and its reversed form are not equal.
