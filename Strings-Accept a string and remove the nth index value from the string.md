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
    n = int(input("Enter the index to remove: "))
    a = ""   # Empty string to store result
    
    # Iterate through each index
    for i in range(len(s)):
        if i != n:      # Check if index is not equal to n
            a += s[i]   # Append character
    
    return a   # Return modified string


# Get input string
string = input("Enter a string: ")

# Call function and print result
result = remove(string)
print("Modified string:", result)

```
## Output
<img width="471" height="242" alt="image" src="https://github.com/user-attachments/assets/77262190-b3c5-47fc-a4a5-c33e6e0c453d" />

## Result
The given program was executed successfully.
