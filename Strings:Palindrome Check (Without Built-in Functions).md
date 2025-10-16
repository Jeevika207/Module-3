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
reversed_s = s[::-1]

if s == reversed_s:
    print(s, "is a palindrome")
else:
    print(s, "is not a palindrome")
```

## Output

<img width="442" height="163" alt="image" src="https://github.com/user-attachments/assets/e48a5cc6-5bd7-4c9b-a81c-53cfccd65e65" />

## Result

Hence, the code is executed successfully, and the string `"google"` is determined **not** to be a palindrome.
