# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

Add code here
```py
numbers = [10, 20, 30, 40]
total = sum(numbers)
print("Sum:", total)
```
## Output
<img width="925" height="121" alt="Screenshot 2025-10-20 184619" src="https://github.com/user-attachments/assets/a6cd5884-aac4-4f38-9d28-b47af0231457" />

## Result
Successfully wrote a Python program that calculates the **sum of all elements** in a list.


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
Add code here
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
Add Code Here
```py
def remove(s):
    n = int(input("Enter index to remove: "))
    a = ""
    for i in range(len(s)):
        if i != n:
            a += s[i]
    return a

# Example usage
text = input("Enter a string: ")
result = remove(text)
print("Modified string:", result)
```


## Output
<img width="963" height="127" alt="Screenshot 2025-10-20 185415" src="https://github.com/user-attachments/assets/c76779c4-a257-4983-be83-727e8339b014" />

## Result
Successfully wrote a Python program that accepts a string and removes the character at a specified index.

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

Add code here
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
 

 # Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
Add code here
```py
x = ('a', 'b', 'n', 3, 8, 'z')

print('n' in x) 
print(8 in x)
```

## Output
<img width="872" height="104" alt="Screenshot 2025-10-20 190444" src="https://github.com/user-attachments/assets/23819123-2afb-493b-b54e-dac74de7d376" />

## Result
Successfully wrote a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.
