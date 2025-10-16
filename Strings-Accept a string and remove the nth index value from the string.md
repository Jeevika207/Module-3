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
def remove(string, n):
    a = ""
    for i in range(len(string)):
        if i != n:
            a += string[i]
    return a

s = input("Enter a string: ")
index = int(input("Enter index to remove: "))
result = remove(s, index)
print("Modified string:", result)
```

## Output

<img width="436" height="248" alt="image" src="https://github.com/user-attachments/assets/a249c720-9c05-4e5f-858d-9954e5c19b6a" />

## Result

Hence, the code is executed successfully, and the character at the specified index is removed from the string.
