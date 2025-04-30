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

# Initialize an empty list to store results
l1 = []

# Define a list of words
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

# Iterate through each word in the list
for i in items:
    # Check if the word contains the letter 'e' using re.search
    if not re.search(r"e", i):
        l1.append(i)

# Print the final filtered list
print("Filtered list:", l1)
```
## Output
![image](https://github.com/user-attachments/assets/33b62921-a884-4292-9880-10860d49eb58)

## Result
Program Executed Successfully.
