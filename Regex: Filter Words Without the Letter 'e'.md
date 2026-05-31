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

```py
import re

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
filtered = []

for word in items:
    if not re.search('e', word):
        filtered.append(word)

print("Words without 'e':", filtered)
```
## Output
<img width="913" height="75" alt="Screenshot 2025-10-20 185048" src="https://github.com/user-attachments/assets/b3eca58b-90bb-4d89-a386-1b900f79213e" />
## Result
Successfully wrote a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.
