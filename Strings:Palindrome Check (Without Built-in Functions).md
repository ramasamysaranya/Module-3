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
s = input()
if s==s[::-1]:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

## Output

<img width="949" height="331" alt="image" src="https://github.com/user-attachments/assets/ee471653-f013-4e7b-918b-9084e6b5487a" />

## Result
Thus, the program has been executed successfully.
