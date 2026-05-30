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
s = "google"

rev = s[::-1]

if s == rev:
    print("Palindrome")
else:
    print("Not a Palindrome")
```
## Output
<img width="1242" height="279" alt="{6C0CE60E-E1AB-4053-BAF3-65867E276D30}" src="https://github.com/user-attachments/assets/e55bbcbf-5017-443d-85ff-eeb4025b48e9" />

## Result
Thus , the result has been excecuted successfully


