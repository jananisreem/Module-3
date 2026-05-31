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

```py
word =input("Enter a word:",)
reversed_word = word[::-1]

if word == reversed_word:
    print("It's a palindrome!")
else:
    print("Not a palindrome.")
```

## Output
<img width="940" height="173" alt="Screenshot 2025-10-20 185921" src="https://github.com/user-attachments/assets/dd72355e-ff98-4549-b014-d985ac8f31a4" />

## Result
Successfully wrote a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.
