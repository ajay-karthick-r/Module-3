# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
numbers = list(map(int, input().split()))
total = sum(numbers)
print("Sum of all elements =", total)
```
## Output
<img width="1245" height="199" alt="{F8B9C1BA-F7CF-4A4A-A4E7-84385953C106}" src="https://github.com/user-attachments/assets/496cb622-a23c-43ad-9530-72c65fb81a51" />

## Result
The program has been excecuted successfully

# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re

l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

for i in items:
    if not re.search(r"e", i):
        l1.append(i)

print(l1)
```
## Output
<img width="1215" height="296" alt="{F16413F5-6041-41A5-9101-8D32B09E67BB}" src="https://github.com/user-attachments/assets/bf9ba986-c555-48a5-97d2-8ba245fea5ca" />

## Result
Thus , the program has been excecuted successfully


# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
def remove(s):
    n = int(input())
    a = ""

    for i in range(len(s)):
        if i != n:
            a += s[i]

    return a

s = input()
print(remove(s))
```

## Output
<img width="1200" height="396" alt="{0258DD4C-1698-4C6E-BDA5-F3DD134A45D4}" src="https://github.com/user-attachments/assets/a6df4649-5a9f-4923-92bb-f7c349f5c52e" />

## Result
Thus , the program has been excecuted successfully


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


# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
x = ('a', 'b', 'n', 5, 8, 10)

print('n' in x)
print(8 in x)
```
## Output
<img width="1207" height="207" alt="{19AE03C7-D313-400A-8FA8-0EBDFB0B9BE9}" src="https://github.com/user-attachments/assets/e952a0d7-59c8-49f2-9b6a-79e7a66fd690" />


## Result
The program successfully checks whether the element 'n' and the number 8 exist in the tuple using the in operator.


