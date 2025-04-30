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
# Define the remove function
def remove(input_string, n):
    # Initialize an empty string a to store the new string
    a = ""
    
    # Iterate over each index of the string
    for i in range(len(input_string)):
        # Check if the current index i is not equal to n
        if i != n:
            # Append the character at index i to string a
            a += input_string[i]
    
    # Return the modified string a
    return a

# Read the input string and index from the user
input_string = input("Enter a string: ")
n = int(input("Enter the index of the character to remove: "))

# Call the remove function and print the final result
modified_string = remove(input_string, n)
print("The modified string is:", modified_string)

```

## Output
![image](https://github.com/user-attachments/assets/f7a3632c-8639-43dc-931b-11a29a6400c0)

## Result
Program executed successfully.
